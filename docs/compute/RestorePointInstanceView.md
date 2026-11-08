# AzureRest::RestorePointInstanceView

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **disk_restore_points** | [**Array&lt;DiskRestorePointInstanceView&gt;**](DiskRestorePointInstanceView.md) | The disk restore points information. | [optional] |
| **statuses** | [**Array&lt;InstanceViewStatus&gt;**](InstanceViewStatus.md) | The aggregate status information for the restore point. The list may include separate aggregate entries for replication and, in supported API versions, Instant Access, as applicable. For more information about Instant Access, see [Use virtual machine restore points](https://learn.microsoft.com/azure/virtual-machines/virtual-machines-create-restore-points#instant-access). | [optional] |

## Example

```ruby
require 'azure_rest'

instance = AzureRest::RestorePointInstanceView.new(
  disk_restore_points: null,
  statuses: null
)
```

