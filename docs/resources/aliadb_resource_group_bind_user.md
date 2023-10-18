---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "st-alicloud_aliadb_resource_group_bind_user Resource - terraform-provider-st-alicloud"
subcategory: ""
description: |-
  Provides a Aliadb resource group association resource.
---

# st-alicloud_aliadb_resource_group_bind_user (Resource)

Provides a Aliadb resource group association resource.

## Example Usage

```terraform
resource "st-alicloud_aliadb_resource_group_bind_user" "bind_user" {
  dbcluster_id = "am-3ns9eg3ntm1g7y0m3"
  group_name   = "TEST"
  group_user   = "dts"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `dbcluster_id` (String) The ID of the AnalyticDB for MySQL Data Warehouse Edition (V3.0) cluster.
- `group_name` (String) The name of the resource group.
- `group_user` (String) The database account with which to associate the resource group.