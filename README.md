A minimal Go project demonstrating Prow integration for presubmit testing.

## Project Structure

- `go.mod`: Go module definition file.
- `math.go`: Contains a simple `Add` function.
- `math_test.go`: Contains a test for the `Add` function.
- `prow-jobs.yaml`: Prow configuration for presubmit testing.

## Running Tests Locally

To run the tests locally, execute:

```bash
go test
```

## Prow Integration

This project is configured to run unit tests using Prow on every pull request. The configuration is defined in `prow-jobs.yaml`. 
