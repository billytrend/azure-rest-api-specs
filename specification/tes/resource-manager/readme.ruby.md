## Ruby

These settings apply only when `--ruby` is specified on the command line.

```yaml
package-name: azure_mgmt_tes
package-version: 1234123
azure-arm: true
```

### Tag: package-1234123 and ruby

These settings apply only when `--tag=package-1234123 --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

```yaml $(tag) == 'package-1234123' && $(ruby)
namespace: Microsoft.asdf
output-folder: $(ruby-sdks-folder)/tes
```
