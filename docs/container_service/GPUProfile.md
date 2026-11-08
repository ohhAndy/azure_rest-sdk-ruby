# AzureRest::GPUProfile

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **driver** | [**GPUDriver**](GPUDriver.md) |  | [optional] |
| **nvidia** | [**NvidiaGPUProfile**](NvidiaGPUProfile.md) |  | [optional] |

## Example

```ruby
require 'azure_rest'

instance = AzureRest::GPUProfile.new(
  driver: null,
  nvidia: null
)
```

