# Setup Vcpkg Action

GitHub Action to set up vcpkg tool in your GitHub Actions workflows.
It does not checkout a registry.

## Usage

```yaml
steps:
  - uses: open-vcpkg/setup-vcpkg@v1
```

## Outputs

Sets the following environment variables:
- `VCPKG_ROOT`: Path to vcpkg installation