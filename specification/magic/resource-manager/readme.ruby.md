## Ruby

These settings apply only when `--ruby` is specified on the command line.

```yaml
package-name: azure_mgmt_magic
package-version: 1351325
azure-arm: true
```

### Tag: package-1351325 and ruby

These settings apply only when `--tag=package-1351325 --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

```yaml $(tag) == 'package-1351325' && $(ruby)
namespace: Microsoft.magic
output-folder: $(ruby-sdks-folder)/magic
```
