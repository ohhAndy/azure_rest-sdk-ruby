# AzureRest::FlexProfile

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **preferred_vm_size** | **String** | Specifies the preferred VM size, for example Standard_D4s_v5. Azure may deploy a compatible alternative size based on capacity and placement considerations. Supported VM families for FlexProfile may vary by region. The recommended way to get the list of available sizes is using these APIs: [List all available virtual machine sizes in a region](https://docs.microsoft.com/rest/api/compute/resourceskus/list), [List all available virtual machine sizes for resizing](https://docs.microsoft.com/rest/api/compute/virtualmachines/listavailablesizes). |  |

## Example

```ruby
require 'azure_rest'

instance = AzureRest::FlexProfile.new(
  preferred_vm_size: null
)
```

