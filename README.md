# Check changelog

Check if the last pull request includes a changelog.


# Usage

The changelog files must be in YAML format and added in the directory `releases/unreleased`.

```
on: pull_request

jobs:
  check-changelog:
    runs-on: ubuntu-latest
    name: Check changelog included
    steps:
      - uses: bitergia/release-tools-check-changelog@main
```
