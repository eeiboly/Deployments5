# day1package

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] day1package`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree day1package`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init day1package
kpt live apply day1package --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
