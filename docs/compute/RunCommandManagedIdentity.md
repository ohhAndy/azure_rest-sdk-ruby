# AzureRest::RunCommandManagedIdentity

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **client_id** | **String** | Client Id (GUID value) of the user-assigned managed identity. ObjectId should not be used if this is provided. | [optional] |
| **_object_id** | **String** | Object Id (GUID value) of the user-assigned managed identity. ClientId should not be used if this is provided. | [optional] |

## Example

```ruby
require 'azure_rest'

instance = AzureRest::RunCommandManagedIdentity.new(
  client_id: null,
  _object_id: null
)
```

