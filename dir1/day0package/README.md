# day0package

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] day0package`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree day0package`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init day0package
kpt live apply day0package --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
