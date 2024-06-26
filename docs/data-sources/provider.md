---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "myscribae_provider Data Source - myscribae"
subcategory: ""
description: |-
  
---

# myscribae_provider (Data Source)



## Example Usage

```terraform
data "myscribae_provider" "example" {
  api_key    = "<YOUR-API-KEY>"
  secret_key = "<YOUR-SECRET-KEY>"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- `api_key` (String) The api key of the provider
- `secret_key` (String) The secret key of the provider

### Read-Only

- `account_service` (Boolean) Is the provider an account service
- `alt_id` (String) The alt id of the provider
- `banner_url` (String) The banner url of the provider
- `color` (String) The color choice of the provider as hex color code (e.g. #000000)
- `description` (String) The description of the provider
- `id` (String) The id of the provider
- `logo_url` (String) The logo url of the provider
- `name` (String) The name of the provider
- `public` (Boolean) Is the provider public
- `url` (String) The url of the provider
- `uuid` (String) The uuid of the provider
