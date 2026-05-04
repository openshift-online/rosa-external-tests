# rosa-external-tests
Tests run from outside of the service to test the ROSA service.

## Quick Start

```bash
export OCM_TOKEN=<your-token>
make test        # Run external tests against ROSA service
```

## Installation

Clone the repository:

```bash
git clone https://github.com/openshift-online/rosa-external-tests.git
cd rosa-external-tests
```

### Prerequisites

- Access to a ROSA service environment (staging or production)
- Valid OCM credentials

## Usage

Tests are run against a live ROSA service:

```bash
# Configure credentials
export OCM_TOKEN=<your-token>

# Run the test suite
go test ./...
```

## Development

### Contributing

1. Fork this repository
2. Add or modify tests
3. Verify tests pass against a staging environment
4. Submit a pull request
