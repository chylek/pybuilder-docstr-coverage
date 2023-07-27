# PyBuilder plugin that checks documentation coverage using docstr-coverage

Uses docstr-coverage to check documentation coverage of your project.

## Tasks

### `docstr_coverage`

Generates docstring coverage report and fails the build if the coverage
is below specified threshold (100 % by default)

## Properties

### `docstr_coverage_config`
The path to the configuration file for docstr-coverage. Default: .docstr.yaml

### `docstr_coverage_fail_under`
The minimum coverage percentage (int) that must be achieved. 
If the coverage is below this value, the build will fail. If set (not None) 
it will take precedence over the value set in the configuration file.