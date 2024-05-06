# Github Action to Increment Tagged Version

## About

This action is designed to bump the tags of a given repository based on the name of the branch that was just merged to main.

## Usage

```workflow
...
  steps:
  - name: Increment Tagged Version
    uses: launchbynttdata/actions-lcaf-increment_tagged_version@v0
...
```

## Compatibility

This action has only been tested on GitHub.com.
