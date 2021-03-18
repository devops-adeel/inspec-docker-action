# Inspec docker action
This action executes Inspec exec against a named path.

## Inputs

### `path`

**Required** The path where `inspec.yml` exists.

## Outputs

### `results`

The result output from Inspec.


## Example usage

yaml```
uses: actions/inspec-docker-action@v1
with:
  path: 'integration_tests'
```
