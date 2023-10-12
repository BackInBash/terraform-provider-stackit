---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "stackit_logme_credential Resource - stackit"
subcategory: ""
description: |-
  LogMe credential resource schema.
---

# stackit_logme_credential (Resource)

LogMe credential resource schema.

## Example Usage

```terraform
resource "stackit_logme_credential" "example" {
  project_id  = "xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx"
  instance_id = "xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `instance_id` (String) ID of the LogMe instance.
- `project_id` (String) STACKIT Project ID to which the instance is associated.

### Read-Only

- `credentials_id` (String) The credentials ID.
- `host` (String)
- `hosts` (List of String)
- `http_api_uri` (String)
- `id` (String) Terraform's internal resource identifier. It is structured as "`project_id`,`instance_id`,`credentials_id`".
- `name` (String)
- `password` (String, Sensitive)
- `port` (Number)
- `uri` (String)
- `username` (String)