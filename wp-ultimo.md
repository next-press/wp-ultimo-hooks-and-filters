### wp_ultimo_debug

*No description provided.*

```php
do_action("wp_ultimo_debug")
```

Location: inc/debug/class-debug.php:597

---
### wu_rest_register_endpoint_args

*No description provided.*

```php
apply_filters("wu_rest_register_endpoint_args")
```

Location: inc/api/class-register-endpoint.php:523

---
### wu_checkout_template_id

*No description provided.*

```php
apply_filters("wu_checkout_template_id")
```

Location: inc/api/class-register-endpoint.php:624

---
### wu_billing_address_get_{$name}

*No description provided.*

```php
apply_filters("wu_billing_address_get_{$name}")
```

Location: inc/objects/class-billing-address.php:105

---
### wu_billing_address_set_{$name}

*No description provided.*

```php
apply_filters("wu_billing_address_set_{$name}")
```

Location: inc/objects/class-billing-address.php:119

---
### wu_billing_address_fields

Allow plugin developers to filter the billing address fields.

Added in 2.0.0

```php
apply_filters("wu_billing_address_fields", array $fields, bool $zip_only)
```

Location: inc/objects/class-billing-address.php:334

#### Arguments
* `$fields` (_array_) Billing Address array.
* `$zip_only` (_bool_) If we only need zip and country.

#### Expected Return
(_array_) No description provided.

---
### wu_limit_classes

*No description provided.*

```php
apply_filters("wu_limit_classes")
```

Location: inc/objects/class-limitations.php:417

---
### wu_note_get_{$name}

*No description provided.*

```php
apply_filters("wu_note_get_{$name}")
```

Location: inc/objects/class-note.php:107

---
### wu_note_set_{$name}

*No description provided.*

```php
apply_filters("wu_note_set_{$name}")
```

Location: inc/objects/class-note.php:121

---
### wu_apply_plan_limits

Allow plugin developers to short-circuit the limitations.

You can use this filter to run arbitrary code before any of the limits get initiated. If you filter returns any truthy value, the process will move on, if it returns any falsy value, the code will return and none of the hooks below will run.

Added in 1.7.0

```php
apply_filters("wu_apply_plan_limits")
```

Location: inc/limits/class-post-type-limits.php:54

#### Arguments
*None.*

#### Expected Return
(_bool_) No description provided.

---
### wu_apply_plan_limits

Allow plugin developers to short-circuit the limitations.

You can use this filter to run arbitrary code before any of the limits get initiated. If you filter returns any truthy value, the process will move on, if it returns any falsy value, the code will return and none of the hooks below will run.

Added in 1.7.0

```php
apply_filters("wu_apply_plan_limits")
```

Location: inc/limits/class-disk-space-limits.php:55

#### Arguments
*None.*

#### Expected Return
(_bool_) No description provided.

---
### wu_replace_text_allowed_domains

*No description provided.*

```php
apply_filters("wu_replace_text_allowed_domains")
```

Location: inc/class-whitelabel.php:132

---
### wu_hosting_support_supports

*No description provided.*

```php
apply_filters("wu_hosting_support_supports")
```

Location: inc/integrations/host-providers/class-base-host-provider.php:349

---
### wu_cloudflare_should_add_www

First, try to detect the domain as a proxied on the current zone, if applicable

```php
apply_filters("wu_cloudflare_should_add_www")
```

Location: inc/integrations/host-providers/class-cloudflare-host-provider.php:267

---
### wu_cloudflare_should_proxy

Adds the www version, if necessary.

```php
apply_filters("wu_cloudflare_should_proxy")
```

Location: inc/integrations/host-providers/class-cloudflare-host-provider.php:282

---
### wu_cloudflare_on_add_domain_data

*No description provided.*

```php
apply_filters("wu_cloudflare_on_add_domain_data")
```

Location: inc/integrations/host-providers/class-cloudflare-host-provider.php:284

---
### wu_list_table_fetch_ajax_results

*No description provided.*

```php
do_action("wu_list_table_fetch_ajax_results")
```

Location: inc/class-ajax.php:83

---
### wu_before_search_models

Fires before the processing of the search request.

Added in 2.0.0

```php
do_action("wu_before_search_models")
```

Location: inc/class-ajax.php:100

#### Arguments
*None.*

---
### wu_search_models_functions

Allow plugin developers to add more search models functions.

Added in 2.0.0

```php
apply_filters("wu_search_models_functions")
```

Location: inc/class-ajax.php:249

#### Arguments
*None.*

---
### wu_should_use_saved_currency

*No description provided.*

```php
apply_filters("wu_should_use_saved_currency")
```

Location: inc/models/class-product.php:455

---
### wu_product_is_taxable

*No description provided.*

```php
apply_filters("wu_product_is_taxable")
```

Location: inc/models/class-product.php:1114

---
### wu_product_tax_category

*No description provided.*

```php
apply_filters("wu_product_tax_category")
```

Location: inc/models/class-product.php:1148

---
### wu_get_as_variation_price_variation

*No description provided.*

```php
apply_filters("wu_get_as_variation_price_variation")
```

Location: inc/models/class-product.php:1337

---
### wu_product_get_price_variation

*No description provided.*

```php
apply_filters("wu_product_get_price_variation")
```

Location: inc/models/class-product.php:1421

---
### save_post_wpultimo_plan

*No description provided.*

Deprecated in 2.0.0 **

```php
do_action("save_post_wpultimo_plan")
```

Location: inc/models/class-product.php:1450

---
### wu_save_plan

*No description provided.*

Deprecated in 2.0.0 *Use 'wu_product_post_save' instead.*

```php
do_action("wu_save_plan")
```

Location: inc/models/class-product.php:1458

---
### wu_is_online_minutes_interval

*No description provided.*

```php
apply_filters("wu_is_online_minutes_interval")
```

Location: inc/models/class-customer.php:843

---
### wu_checkout_form_meta_fields_list

*No description provided.*

```php
apply_filters("wu_checkout_form_meta_fields_list")
```

Location: inc/models/class-checkout-form.php:371

---
### wu_checkout_form_single_step_template

*No description provided.*

```php
apply_filters("wu_checkout_form_single_step_template")
```

Location: inc/models/class-checkout-form.php:556

---
### wu_checkout_form_multi_step_template

*No description provided.*

```php
apply_filters("wu_checkout_form_multi_step_template")
```

Location: inc/models/class-checkout-form.php:706

---
### wu_checkout_form_membership_change_form_fields

Add Checkout step

```php
apply_filters("wu_checkout_form_membership_change_form_fields")
```

Location: inc/models/class-checkout-form.php:1279

---
### wu_site_is_customer_allowed

*No description provided.*

```php
apply_filters("wu_site_is_customer_allowed")
```

Location: inc/models/class-site.php:1017

---
### wu_{$this->model}_pre_delete

Fires after an object is stored into the database.

Added in 2.0.0

```php
do_action("wu_{$this->model}_pre_delete", \WP_Ultimo\Models\Base_Model $this)
```

Location: inc/models/class-site.php:1583

#### Arguments
* `$this` (_\WP_Ultimo\Models\Base_Model_) The object instance.

---
### wu_{$this->model}_post_delete

Fires after an object is stored into the database.

Added in 2.0.0

```php
do_action("wu_{$this->model}_post_delete", bool $result, \WP_Ultimo\Models\Base_Model $this)
```

Location: inc/models/class-site.php:1605

#### Arguments
* `$result` (_bool_) True if the object was successfully deleted.
* `$this` (_\WP_Ultimo\Models\Base_Model_) The object instance.

---
### wu_site_created

Fires after a site is created for the first time.

Added in 2.0.0

```php
do_action("wu_site_created", array $data, \WP_Ultimo\Models\Base_Model $this)
```

Location: inc/models/class-site.php:1743

#### Arguments
* `$data` (_array_) The object data that will be stored.
* `$this` (_\WP_Ultimo\Models\Base_Model_) The object instance.

---
### wu_model_post_save

Fires after an object is stored into the database.

Added in 2.0.0

```php
do_action("wu_model_post_save", array $model, array $data, array $data_unserialized, \WP_Ultimo\Models\Base_Model $this, array $new)
```

Location: inc/models/class-site.php:1838

#### Arguments
* `$model` (_array_) The model slug.
* `$data` (_array_) The object data that will be stored, serialized.
* `$data_unserialized` (_array_) The object data that will be stored.
* `$this` (_\WP_Ultimo\Models\Base_Model_) The object instance.
* `$new` (_array_) If this object is a new one.

---
### wu_{$this->model}_post_save

Fires after an object is stored into the database.

Added in 2.0.0

```php
do_action("wu_{$this->model}_post_save", array $data, \WP_Ultimo\Models\Base_Model $this, array $new)
```

Location: inc/models/class-site.php:1849

#### Arguments
* `$data` (_array_) The object data that will be stored.
* `$this` (_\WP_Ultimo\Models\Base_Model_) The object instance.
* `$new` (_array_) If this object is a new one.

---
### wu_get_default_system_messages

*No description provided.*

```php
apply_filters("wu_get_default_system_messages")
```

Location: inc/models/class-event.php:321

---
### wp_ultimo_coupon_after_save

*No description provided.*

Deprecated in 2.0.0 *Use 'wu_discount_code_post_save' instead.*

```php
do_action("wp_ultimo_coupon_after_save")
```

Location: inc/models/class-discount-code.php:769

---
### wu_domain_has_correct_dns

Allow plugin developers to add new checks in order to define the results.

Added in 2.0.4

```php
apply_filters("wu_domain_has_correct_dns", bool $result, self $this, array $domains_and_ips)
```

Location: inc/models/class-domain.php:461

#### Arguments
* `$result` (_bool_) the current result.
* `$this` (_self_) The current domain instance.
* `$domains_and_ips` (_array_) The list of domains and IPs found on the DNS lookup.

#### Expected Return
(_bool_) If the DNS is correctly setup or not.

---
### mercator.mapping.created

Deprecated: Mercator created domain.

Added in 2.0.0
Deprecated in 2.0.0 *Use 'wu_domain_post_save' instead.*

```php
do_action("mercator.mapping.created")
```

Location: inc/models/class-domain.php:515

#### Arguments
* `` (_self_) The domain object after saving.
* `` (_self_) The domain object before the changes.

#### Expected Return
(_\WP_Ultimo\Models\void._) No description provided.

---
### mercator.mapping.updated

Deprecated: Mercator updated domain.

Added in 2.0.0
Deprecated in 2.0.0 *Use 'wu_domain_post_save' instead.*

```php
do_action("mercator.mapping.updated")
```

Location: inc/models/class-domain.php:536

#### Arguments
* `` (_self_) The domain object after saving.
* `` (_self_) The domain object before the changes.

#### Expected Return
(_\WP_Ultimo\Models\void._) No description provided.

---
### mercator.mapping.deleted

Deprecated: Mercator Deleted domain.

Added in 2.0.0
Deprecated in 2.0.0 *Use 'wu_domain_post_delete' instead.*

```php
do_action("mercator.mapping.deleted")
```

Location: inc/models/class-domain.php:580

#### Arguments
* `` (_self_) The domain object just deleted.

#### Expected Return
(_\WP_Ultimo\Models\void._) No description provided.

---
### wu_post_default_status

Filters the object data before it is stored into the database.

Added in 2.0.0

```php
apply_filters("wu_post_default_status", string $status, string $post_type, \WP_Ultimo\Models\Base_Model $this)
```

Location: inc/models/class-post-base-model.php:323

#### Arguments
* `$status` (_string_) The default status.
* `$post_type` (_string_) The post type.
* `$this` (_\WP_Ultimo\Models\Base_Model_) The object instance.

---
### wu_membership_is_customer_allowed

*No description provided.*

```php
apply_filters("wu_membership_is_customer_allowed")
```

Location: inc/models/class-membership.php:373

---
### wu_membership_delete_scheduled_swap

We only care about products.

```php
do_action("wu_membership_delete_scheduled_swap")
```

Location: inc/models/class-membership.php:788

---
### wu_membership_calculated_date_expiration

Filters the calculated expiration date.

Added in 2.0

```php
apply_filters("wu_membership_calculated_date_expiration", string $expiration, int $membership_id, \WP_Ultimo\Models\Membership $this)
```

Location: inc/models/class-membership.php:1268

#### Arguments
* `$expiration` (_string_) Calculated expiration date in MySQL format.
* `$membership_id` (_int_) ID of the membership.
* `$this` (_\WP_Ultimo\Models\Membership_) Membership object.

---
### wu_membership_is_active

*No description provided.*

```php
apply_filters("wu_membership_is_active")
```

Location: inc/models/class-membership.php:1479

---
### wu_before_pending_site_published

*No description provided.*

```php
do_action("wu_before_pending_site_published")
```

Location: inc/models/class-membership.php:1847

---
### wu_pending_site_published

*No description provided.*

```php
do_action("wu_pending_site_published")
```

Location: inc/models/class-membership.php:1872

---
### wu_membership_renewal_expiration_date

Filters the calculated expiration date to be set after the renewal.

Added in 2.0.0

```php
apply_filters("wu_membership_renewal_expiration_date", string $expiration, \WP_Ultimo\Models\Product $plan, int $membership_id, \WP_Ultimo\Models\Membership $this)
```

Location: inc/models/class-membership.php:2045

#### Arguments
* `$expiration` (_string_) Calculated expiration date.
* `$plan` (_\WP_Ultimo\Models\Product_) Membership level object.
* `$membership_id` (_int_) The ID of the membership.
* `$this` (_\WP_Ultimo\Models\Membership_) Membership object.

---
### wu_membership_pre_renew

Triggers before the membership renewal.

Added in 2.0

```php
do_action("wu_membership_pre_renew", string $expiration, int $membership_id, \WP_Ultimo\Models\Membership $this)
```

Location: inc/models/class-membership.php:2058

#### Arguments
* `$expiration` (_string_) New expiration date to be set.
* `$membership_id` (_int_) The ID of the membership.
* `$this` (_\WP_Ultimo\Models\Membership_) Membership object.

---
### wu_membership_post_renew

Triggers after the membership renewal.

Added in 2.0

```php
do_action("wu_membership_post_renew", string $expiration, int $membership_id, \WP_Ultimo\Models\Membership $this)
```

Location: inc/models/class-membership.php:2095

#### Arguments
* `$expiration` (_string_) New expiration date to be set.
* `$membership_id` (_int_) The ID of the membership.
* `$this` (_\WP_Ultimo\Models\Membership_) Membership object.

---
### wu_membership_pre_cancel

Triggers before the membership is cancelled.

Added in 2.0

```php
do_action("wu_membership_pre_cancel", int $membership_id, \WP_Ultimo\Models\Membership $this)
```

Location: inc/models/class-membership.php:2128

#### Arguments
* `$membership_id` (_int_) The ID of the membership.
* `$this` (_\WP_Ultimo\Models\Membership_) Membership object.

---
### wu_membership_post_cancel

Triggers after the membership is cancelled.

This triggers the cancellation email.

Added in 2.0

```php
do_action("wu_membership_post_cancel", int $membership_id, \WP_Ultimo\Models\Membership $this)
```

Location: inc/models/class-membership.php:2147

#### Arguments
* `$membership_id` (_int_) The ID of the membership.
* `$this` (_\WP_Ultimo\Models\Membership_) Membership object.

---
### wu_gateway_{$gateway}_as_option_title

*No description provided.*

```php
apply_filters("wu_gateway_{$gateway}_as_option_title")
```

Location: inc/models/class-payment.php:593

---
### wu_payment_payable_statuses

*No description provided.*

```php
apply_filters("wu_payment_payable_statuses")
```

Location: inc/models/class-payment.php:781

---
### wu_{$this->model}_meta_pre_save

Filters the data meta before it is serialized to be stored into the database.

Added in 2.0.0

```php
apply_filters("wu_{$this->model}_meta_pre_save", array $meta, array $data_unserialized, \WP_Ultimo\Models\Base_Model $this)
```

Location: inc/models/class-base-model.php:544

#### Arguments
* `$meta` (_array_) The meta data that will be stored, unserializedserialized.
* `$data_unserialized` (_array_) The object data that will be stored.
* `$this` (_\WP_Ultimo\Models\Base_Model_) The object instance.

---
### wu_{$this->model}_pre_save

Filters the object data before it is stored into the database.

Added in 2.0.0

```php
apply_filters("wu_{$this->model}_pre_save", array $data, array $data_unserialized, \WP_Ultimo\Models\Base_Model $this)
```

Location: inc/models/class-base-model.php:582

#### Arguments
* `$data` (_array_) The object data that will be stored, serialized.
* `$data_unserialized` (_array_) The object data that will be stored.
* `$this` (_\WP_Ultimo\Models\Base_Model_) The object instance.

---
### wu_model_post_save

Fires after an object is stored into the database.

Added in 2.0.0

```php
do_action("wu_model_post_save", array $model, array $data, array $data_unserialized, \WP_Ultimo\Models\Base_Model $this)
```

Location: inc/models/class-base-model.php:630

#### Arguments
* `$model` (_array_) The model slug.
* `$data` (_array_) The object data that will be stored, serialized.
* `$data_unserialized` (_array_) The object data that will be stored.
* `$this` (_\WP_Ultimo\Models\Base_Model_) The object instance.

---
### wu_{$this->model}_post_save

Fires after an object is stored into the database.

Added in 2.0.0

```php
do_action("wu_{$this->model}_post_save", array $data, \WP_Ultimo\Models\Base_Model $this)
```

Location: inc/models/class-base-model.php:640

#### Arguments
* `$data` (_array_) The object data that will be stored.
* `$this` (_\WP_Ultimo\Models\Base_Model_) The object instance.

---
### wu_{$this->model}_pre_delete

Fires after an object is stored into the database.

Added in 2.0.0

```php
do_action("wu_{$this->model}_pre_delete", \WP_Ultimo\Models\Base_Model $this)
```

Location: inc/models/class-base-model.php:668

#### Arguments
* `$this` (_\WP_Ultimo\Models\Base_Model_) The object instance.

---
### wu_{$this->model}_post_delete

Fires after an object is stored into the database.

Added in 2.0.0

```php
do_action("wu_{$this->model}_post_delete", bool $result, \WP_Ultimo\Models\Base_Model $this)
```

Location: inc/models/class-base-model.php:682

#### Arguments
* `$result` (_bool_) True if the object was successfully deleted.
* `$this` (_\WP_Ultimo\Models\Base_Model_) The object instance.

---
### wu_geolocation_update_database_periodically

*No description provided.*

```php
apply_filters("wu_geolocation_update_database_periodically")
```

Location: inc/class-geolocation.php:113

---
### wu_geolocation_ip_lookup_apis

*No description provided.*

```php
apply_filters("wu_geolocation_ip_lookup_apis")
```

Location: inc/class-geolocation.php:176

---
### wu_geolocation_ip_lookup_api_response

*No description provided.*

```php
apply_filters("wu_geolocation_ip_lookup_api_response")
```

Location: inc/class-geolocation.php:185

---
### wu_geolocate_ip

*No description provided.*

```php
apply_filters("wu_geolocate_ip")
```

Location: inc/class-geolocation.php:207

---
### wu_geolocation_local_database_path

*No description provided.*

```php
apply_filters("wu_geolocation_local_database_path")
```

Location: inc/class-geolocation.php:253

---
### wu_geolocation_geoip_apis

*No description provided.*

```php
apply_filters("wu_geolocation_geoip_apis")
```

Location: inc/class-geolocation.php:345

---
### wu_geolocation_geoip_response_{$service_name}

*No description provided.*

```php
apply_filters("wu_geolocation_geoip_response_{$service_name}")
```

Location: inc/class-geolocation.php:370

---
### wu_get_setting

*No description provided.*

```php
apply_filters("wu_get_setting")
```

Location: inc/class-settings.php:199

---
### wu_save_setting

*No description provided.*

```php
apply_filters("wu_save_setting")
```

Location: inc/class-settings.php:214

---
### wu_before_save_settings

*No description provided.*

```php
do_action("wu_before_save_settings")
```

Location: inc/class-settings.php:252

---
### wu_saving_setting

For the current tab, we need to assume toggle fields.

```php
do_action("wu_saving_setting")
```

Location: inc/class-settings.php:283

---
### wu_after_save_settings

*No description provided.*

```php
do_action("wu_after_save_settings")
```

Location: inc/class-settings.php:291

---
### wu_settings_get_sections

*No description provided.*

```php
apply_filters("wu_settings_get_sections")
```

Location: inc/class-settings.php:309

---
### wu_settings_section_core_fields

*No description provided.*

```php
apply_filters("wu_settings_section_core_fields")
```

Location: inc/class-settings.php:318

---
### wu_settings_section_{$section_slug}_fields

*No description provided.*

```php
apply_filters("wu_settings_section_{$section_slug}_fields")
```

Location: inc/class-settings.php:371

---
### wu_settings_login

Handle selectize.

```php
do_action("wu_settings_login")
```

Location: inc/class-settings.php:774

---
### wu_settings_memberships

*No description provided.*

```php
do_action("wu_settings_memberships")
```

Location: inc/class-settings.php:930

---
### wu_settings_site_templates

*No description provided.*

```php
do_action("wu_settings_site_templates")
```

Location: inc/class-settings.php:1022

---
### wu_settings_payment_gateways

*No description provided.*

```php
do_action("wu_settings_payment_gateways")
```

Location: inc/class-settings.php:1108

---
### wu_settings_emails

*No description provided.*

```php
do_action("wu_settings_emails")
```

Location: inc/class-settings.php:1120

---
### wu_settings_domain_mapping

*No description provided.*

```php
do_action("wu_settings_domain_mapping")
```

Location: inc/class-settings.php:1133

---
### wu_settings_integrations

*No description provided.*

```php
do_action("wu_settings_integrations")
```

Location: inc/class-settings.php:1153

---
### wu_should_log_api_calls

Log API errors

Added in 2.0.0

```php
apply_filters("wu_should_log_api_calls")
```

Location: inc/class-api.php:271

#### Arguments
*None.*

---
### wu_is_api_enabled

Allow plugin developers to force a given state for the API.

Added in 1.7.4

```php
apply_filters("wu_is_api_enabled")
```

Location: inc/class-api.php:383

#### Arguments
*None.*

#### Expected Return
(_boolean_) No description provided.

---
### wu_register_rest_routes

Allow additional routes to be registered.

This is used by our /register endpoint.

Added in 2.0.0

```php
do_action("wu_register_rest_routes", self $this)
```

Location: inc/class-api.php:417

#### Arguments
* `$this` (_self_) The current API instance.

---
### wu_enable_taxes

*No description provided.*

```php
apply_filters("wu_enable_taxes")
```

Location: inc/tax/class-tax.php:108

---
### wu_get_tax_rate_types

*No description provided.*

```php
apply_filters("wu_get_tax_rate_types")
```

Location: inc/tax/class-tax.php:144

---
### wu_get_tax_rate_defaults

*No description provided.*

```php
apply_filters("wu_get_tax_rate_defaults")
```

Location: inc/tax/class-tax.php:170

---
### wu_get_tax_rates

*No description provided.*

```php
apply_filters("wu_get_tax_rates")
```

Location: inc/tax/class-tax.php:195

---
### wu_activation

Let other parts of the plugin attach their routines for activation

Added in 1.9.6

```php
do_action("wu_activation")
```

Location: inc/class-hooks.php:88

#### Arguments
*None.*

#### Expected Return
(_void_) No description provided.

---
### wu_deactivation

Let other parts of the plugin attach their routines for deactivation

Added in 1.9.6

```php
do_action("wu_deactivation")
```

Location: inc/class-hooks.php:110

#### Arguments
*None.*

#### Expected Return
(_void_) No description provided.

---
### mercator.sso.enabled

*No description provided.*

Deprecated in 2.0.0 *Use 'wu_sso_enabled' instead.*

```php
apply_filters("mercator.sso.enabled")
```

Location: inc/domain-mapping/class-sso.php:70

---
### wu_sso_enabled

Enable/disable cross-domain single-sign-on capability.

Filter this value to turn single-sign-on off completely, or conditionally enable it instead.

```php
apply_filters("wu_sso_enabled", bool $enabled)
```

Location: inc/domain-mapping/class-sso.php:82

#### Arguments
* `$enabled` (_bool_) Should SSO be enabled? (True for on, false-ish for off.)

---
### wu_sso_loaded

Allow plugin developers to add additional hooks, if needed.

This needs to be delayed until the init as SSO is something that runs on sunrise.

Added in 2.0.0

```php
do_action("wu_sso_loaded", self $this)
```

Location: inc/domain-mapping/class-sso.php:162

#### Arguments
* `$this` (_self_) The SSO class.

---
### wu_sso_loaded_on_init

*No description provided.*

```php
do_action("wu_sso_loaded_on_init")
```

Location: inc/domain-mapping/class-sso.php:166

---
### wu_sso_main_domain_network

Change the network used to check main domain.

For multi-network sites, this allows using only the main network rather than network-local.

```php
apply_filters("wu_sso_main_domain_network", \WP_Ultimo\Domain_Mapping\stdClass $network, string $domain, \WP_Ultimo\Domain_Mapping\stdClass|null $supplied_network)
```

Location: inc/domain-mapping/class-sso.php:265

#### Arguments
* `$network` (_\WP_Ultimo\Domain_Mapping\stdClass_) Network object to be used
* `$domain` (_string_) Domain to check
* `$supplied_network` (_\WP_Ultimo\Domain_Mapping\stdClass_|_null_) Original network object provided as an argument

---
### wu_sso_is_main_domain

Is this domain the main domain?

```php
apply_filters("wu_sso_is_main_domain", boolean $is_main, string $domain, \WP_Ultimo\Domain_Mapping\stdClass $network)
```

Location: inc/domain-mapping/class-sso.php:308

#### Arguments
* `$is_main` (_boolean_) Is this the main domain?
* `$domain` (_string_) Domain we checked against.
* `$network` (_\WP_Ultimo\Domain_Mapping\stdClass_) Network we fetched the cookie domain from

---
### wu_sso_action_url

*No description provided.*

```php
apply_filters("wu_sso_action_url")
```

Location: inc/domain-mapping/class-sso.php:371

---
### wu_sso_login_url

*No description provided.*

```php
apply_filters("wu_sso_login_url")
```

Location: inc/domain-mapping/class-sso.php:746

---
### wu_sso_expiration

How long should the SSO tokens last?

```php
apply_filters("wu_sso_expiration", int $duration)
```

Location: inc/domain-mapping/class-sso.php:818

#### Arguments
* `$duration` (_int_) Session duration in seconds

---
### wu_should_redirect_to_primary_domain

Allow developers to short-circuit the redirection, preventing it from happening.

Added in 2.0.0

```php
apply_filters("wu_should_redirect_to_primary_domain", $should_redirect)
```

Location: inc/domain-mapping/class-primary-domain.php:79

#### Arguments
* `$should_redirect` (__) If we should redirect or not.

#### Expected Return
(_bool_) No description provided.

---
### wu_is_development_mode

Allow plugin developers to add additional tests for development mode.

Added in 2.0.0

```php
apply_filters("wu_is_development_mode", bool $is_development_mode, string $site_url)
```

Location: inc/domain-mapping/class-helper.php:63

#### Arguments
* `$is_development_mode` (_bool_) The current development status.
* `$site_url` (_string_) The site URL.

#### Expected Return
(_bool_) No description provided.

---
### wu_get_network_public_ip

See more about this filter below, on this same method.

```php
apply_filters("wu_get_network_public_ip")
```

Location: inc/domain-mapping/class-helper.php:100

---
### wu_get_network_public_ip

Allow developers to change the public IP address of the network.

This is displayed to the customer/users when new domains are mapped and need DNS records configured. This is useful in cases where a load balancer might be present and IP might vary.

```php
apply_filters("wu_get_network_public_ip", string $_ip_address, bool $local)
```

Location: inc/domain-mapping/class-helper.php:146

#### Arguments
* `$_ip_address` (_string_) The public IP address.
* `$local` (_bool_) True if this is a local network (localhost, .dev, etc.), false otherwise.

#### Expected Return
(_string_) The new IP address.

---
### wu_duplicate_site

Allow developers to hook after a site duplication happens.

Added in 1.9.4

```php
do_action("wu_duplicate_site")
```

Location: inc/helpers/class-site-duplicator.php:252

#### Arguments
*None.*

#### Expected Return
(_void_) No description provided.

---
### wu_validator_error_messages

*No description provided.*

```php
apply_filters("wu_validator_error_messages")
```

Location: inc/helpers/class-validator.php:63

---
### wu_sender_recipients_strategy

*No description provided.*

```php
apply_filters("wu_sender_recipients_strategy")
```

Location: inc/helpers/class-sender.php:138

---
### wu_checkout_step_validation_submittable_field_types

Allow developers to bypass the check if a field is auto-submittable.

Added in 2.0.0

```php
apply_filters("wu_checkout_step_validation_submittable_field_types", array $submittable_field_types)
```

Location: inc/helpers/validation-rules/class-checkout-steps.php:103

#### Arguments
* `$submittable_field_types` (_array_) The list of field types.

#### Expected Return
(_array_) No description provided.

---
### cron_request

*No description provided.*

```php
apply_filters("cron_request")
```

Location: inc/class-requirements.php:207

---
### https_local_ssl_verify

*No description provided.*

```php
apply_filters("https_local_ssl_verify")
```

Location: inc/class-requirements.php:212

---
### wp_ultimo_skip_network_active_check

Allow for developers to short-circuit this check.

This is useful when using composer-based and other custom setups, such as Bedrock, for example, where using plugins as mu-plugins are the norm.

Added in 2.0.0

```php
apply_filters("wp_ultimo_skip_network_active_check")
```

Location: inc/class-requirements.php:268

#### Arguments
*None.*

#### Expected Return
(_bool_) No description provided.

---
### wu_available_{$hook}_options

*No description provided.*

```php
apply_filters("wu_available_{$hook}_options")
```

Location: inc/database/engine/class-enum.php:100

---
### wu_available_{$hook}_labels

*No description provided.*

```php
apply_filters("wu_available_{$hook}_labels")
```

Location: inc/database/engine/class-enum.php:163

---
### wu_available_{$hook}_classes

*No description provided.*

```php
apply_filters("wu_available_{$hook}_classes")
```

Location: inc/database/engine/class-enum.php:179

---
### wu_available_{$hook}_icon_classes

*No description provided.*

```php
apply_filters("wu_available_{$hook}_icon_classes")
```

Location: inc/database/engine/class-enum.php:195

---
### wu_{$hook}_to_array

*No description provided.*

```php
apply_filters("wu_{$hook}_to_array")
```

Location: inc/database/engine/class-enum.php:219

---
### wu_limits_is_post_above_limit

Checks if a given post type is allowed on this plan Allow plugin developers to filter the return value

Added in 1.7.0

```php
apply_filters("wu_limits_is_post_above_limit")
```

Location: inc/limitations/class-limit-post-types.php:56

#### Arguments
* `` (_bool_) If the post type is disabled or not
* `` (_\WP_Ultimo\Limitations\WU_Plan_) Plan of the current user
* `` (_int_) User id

---
### wu_post_count_statuses

Allow plugin developers to change which post status should be counted By default, published and private posts are counted

Added in 1.9.1

```php
apply_filters("wu_post_count_statuses", array $post_status, string $post_type)
```

Location: inc/limitations/class-limit-post-types.php:85

#### Arguments
* `$post_status` (_array_) The list of post statuses
* `$post_type` (_string_) The post type slug

#### Expected Return
(_array_) New array of post status

---
### wu_post_count

Allow plugin developers to change the count total

Added in 1.9.1

```php
apply_filters("wu_post_count", int $count, object $post_counts, string $post_type)
```

Location: inc/limitations/class-limit-post-types.php:106

#### Arguments
* `$count` (_int_) The total post count
* `$post_counts` (_object_) WordPress object return by the wp_count_posts fn
* `$post_type` (_string_) The post type slug

#### Expected Return
(_int_) New total

---
### wu_{$this->id}_limit_setup

*No description provided.*

```php
do_action("wu_{$this->id}_limit_setup")
```

Location: inc/limitations/class-limit.php:164

---
### wu_limit_{$this->id}_{$type}_allowed

*No description provided.*

```php
apply_filters("wu_limit_{$this->id}_{$type}_allowed")
```

Location: inc/limitations/class-limit.php:205

---
### wu_schedule_membership_check_interval

*No description provided.*

```php
apply_filters("wu_schedule_membership_check_interval")
```

Location: inc/class-cron.php:126

---
### wu_membership_renewal_days_before_expiring

*No description provided.*

```php
apply_filters("wu_membership_renewal_days_before_expiring")
```

Location: inc/class-cron.php:150

---
### wu_membership_renewal_check_query_params

*No description provided.*

```php
apply_filters("wu_membership_renewal_check_query_params")
```

Location: inc/class-cron.php:152

---
### wu_membership_trial_check_query_params

*No description provided.*

```php
apply_filters("wu_membership_trial_check_query_params")
```

Location: inc/class-cron.php:192

---
### wu_membership_grace_period_days

*No description provided.*

```php
apply_filters("wu_membership_grace_period_days")
```

Location: inc/class-cron.php:324

---
### wu_membership_expired_check_query_params

*No description provided.*

```php
apply_filters("wu_membership_expired_check_query_params")
```

Location: inc/class-cron.php:326

---
### wu_installer_{$installer}_callback

*No description provided.*

```php
apply_filters("wu_installer_{$installer}_callback")
```

Location: inc/installers/class-base-installer.php:86

---
### wp_ajax_wu_setup_install

*No description provided.*

```php
do_action("wp_ajax_wu_setup_install")
```

Location: inc/installers/class-migrator.php:140

---
### wu_get_migration_steps

Allow developers and add-ons to add new migration steps

Added in 2.0.0

```php
apply_filters("wu_get_migration_steps", array $steps, \WP_Ultimo\Migrator $this)
```

Location: inc/installers/class-migrator.php:437

#### Arguments
* `$steps` (_array_) The list of steps.
* `$this` (_\WP_Ultimo\Migrator_) This class.

---
### wu_installer_{$installer}_callback

*No description provided.*

```php
apply_filters("wu_installer_{$installer}_callback")
```

Location: inc/installers/class-migrator.php:525

---
### wu_core_installer_install_sunrise

Allow host providers to install the constant differently.

Returning true will prevent WP Ultimo from trying to write to the wp-config file.

Added in 2.0.0

```php
apply_filters("wu_core_installer_install_sunrise", bool $short_circuit)
```

Location: inc/installers/class-core-installer.php:160

#### Arguments
* `$short_circuit` (_bool_) 

---
### wp_network_dashboard_setup

*No description provided.*

```php
do_action("wp_network_dashboard_setup")
```

Location: inc/class-dashboard-widgets.php:378

---
### wu_log_add

*No description provided.*

```php
do_action("wu_log_add")
```

Location: inc/class-logger.php:174

---
### wu_log_clear

*No description provided.*

```php
do_action("wu_log_clear")
```

Location: inc/class-logger.php:191

---
### wu_light_ajax_should_skip_referer_check

*No description provided.*

```php
apply_filters("wu_light_ajax_should_skip_referer_check")
```

Location: inc/class-light-ajax.php:56

---
### wu_light_ajax_allowed_hooks

For security reasons, we limit the number of actions available for hooking into. This filter allows developers to expand that list if necessary.

Added in 2.0.0

```php
apply_filters("wu_light_ajax_allowed_hooks")
```

Location: inc/class-light-ajax.php:87

#### Arguments
*None.*

#### Expected Return
(_array_) The hook list.

---
### wu_before_light_ajax

In some cases, we'll need to load extra juice to handle actions.

This action can be used to load extra dependencies when needed.

Added in 2.0.0

```php
do_action("wu_before_light_ajax")
```

Location: inc/class-light-ajax.php:124

#### Arguments
*None.*

---
### wu_ajax_{$action}

Allow for cross-domain requests (from the front end).

```php
do_action("wu_ajax_{$action}")
```

Location: inc/class-light-ajax.php:151

---
### wu_ajax_nopriv_{$action}

*No description provided.*

```php
do_action("wu_ajax_nopriv_{$action}")
```

Location: inc/class-light-ajax.php:155

---
### wu_core_update

Triggers an action that be used to perform tasks on a core update.

Added in 2.0.0

```php
do_action("wu_core_update")
```

Location: inc/class-core-updates.php:78

#### Arguments
*None.*

---
### wu_current_get_site_param

Warning! The log message below CANNOT be localized using __(). Doing that will crash Ultimo on new installs.

```php
apply_filters("wu_current_get_site_param")
```

Location: inc/class-current.php:159

---
### wu_current_get_customer_param

*No description provided.*

```php
apply_filters("wu_current_get_customer_param")
```

Location: inc/class-current.php:160

---
### wu_current_site_get_manage_url

Allow developers to modify the manage site URL parameters.

Added in 2.0.9

```php
apply_filters("wu_current_site_get_manage_url", string $manage_site_url, int $id, string $site_hash)
```

Location: inc/class-current.php:216

#### Arguments
* `$manage_site_url` (_string_) The manage site URL.
* `$id` (_int_) The site ID.
* `$site_hash` (_string_) The site hash.

#### Expected Return
(_string_) The modified manage URL.

---
### wu_current_set_site

Allow developers to modify the default behavior and set the current site differently.

Added in 2.0.9

```php
apply_filters("wu_current_set_site", \WP_Ultimo\Models\Site $site)
```

Location: inc/class-current.php:321

#### Arguments
* `$site` (_\WP_Ultimo\Models\Site_) The current site to set.
* `` (_self_) The Current class instance.

#### Expected Return
(_\WP_Ultimo\Models\Site_) No description provided.

---
### wu_current_set_customer

Allow developers to modify the default behavior and set the current customer differently.

Added in 2.0.9

```php
apply_filters("wu_current_set_customer", \WP_Ultimo\Models\Customer $customer)
```

Location: inc/class-current.php:370

#### Arguments
* `$customer` (_\WP_Ultimo\Models\Customer_) The current customer to set.
* `` (_self_) The Current class instance.

#### Expected Return
(_\WP_Ultimo\Models\Customer_) No description provided.

---
### wu_maintenance_mode_text

*No description provided.*

```php
apply_filters("wu_maintenance_mode_text")
```

Location: inc/class-maintenance-mode.php:129

---
### wu_maintenance_mode_title

*No description provided.*

```php
apply_filters("wu_maintenance_mode_title")
```

Location: inc/class-maintenance-mode.php:134

---
### wu_admin_themes_compatibility

*No description provided.*

```php
apply_filters("wu_admin_themes_compatibility")
```

Location: inc/class-admin-themes-compatibility.php:69

---
### wu_domain_mapping_get_ip_address

*No description provided.*

```php
apply_filters("wu_domain_mapping_get_ip_address")
```

Location: inc/deprecated/early-deprecated.php:36

---
### mucd_get_site_list_args

*No description provided.*

```php
apply_filters("mucd_get_site_list_args")
```

Location: inc/duplication/functions.php:86

---
### mucd_get_sites_args

*No description provided.*

```php
apply_filters("mucd_get_sites_args")
```

Location: inc/duplication/functions.php:179

---
### mucd_get_sites_args

*No description provided.*

```php
apply_filters("mucd_get_sites_args")
```

Location: inc/duplication/functions.php:187

---
### mucd_copy_dirs

*No description provided.*

```php
apply_filters("mucd_copy_dirs")
```

Location: inc/duplication/files.php:34

---
### mucd_string_to_replace

*No description provided.*

```php
apply_filters("mucd_string_to_replace")
```

Location: inc/duplication/data.php:189

---
### mucd_copy_blog_data_saved_options

*No description provided.*

```php
apply_filters("mucd_copy_blog_data_saved_options")
```

Location: inc/duplication/option.php:143

---
### mucd_default_fields_to_update

*No description provided.*

```php
apply_filters("mucd_default_fields_to_update")
```

Location: inc/duplication/option.php:175

---
### mucd_default_primary_tables_to_copy

*No description provided.*

```php
apply_filters("mucd_default_primary_tables_to_copy")
```

Location: inc/duplication/option.php:208

---
### mucd_before_copy_files

*No description provided.*

```php
do_action("mucd_before_copy_files")
```

Location: inc/duplication/duplicate.php:80

---
### mucd_after_copy_files

*No description provided.*

```php
do_action("mucd_after_copy_files")
```

Location: inc/duplication/duplicate.php:82

---
### mucd_before_copy_data

*No description provided.*

```php
do_action("mucd_before_copy_data")
```

Location: inc/duplication/duplicate.php:86

---
### mucd_after_copy_data

*No description provided.*

```php
do_action("mucd_after_copy_data")
```

Location: inc/duplication/duplicate.php:88

---
### mucd_before_copy_users

*No description provided.*

```php
do_action("mucd_before_copy_users")
```

Location: inc/duplication/duplicate.php:92

---
### mucd_after_copy_users

*No description provided.*

```php
do_action("mucd_after_copy_users")
```

Location: inc/duplication/duplicate.php:94

---
### wu_template_previewer

Runs when inside the template previewer context.

Added in 2.0.4

```php
do_action("wu_template_previewer", self $template_previewer)
```

Location: inc/ui/class-template-previewer.php:83

#### Arguments
* `$template_previewer` (_self_) Instance of the current class.

---
### wu_append_preview_parameter

*No description provided.*

```php
apply_filters("wu_append_preview_parameter")
```

Location: inc/ui/class-template-previewer.php:184

---
### wu_get_template_preview_slug

Check if this is a site template

```php
apply_filters("wu_get_template_preview_slug")
```

Location: inc/ui/class-template-previewer.php:271

---
### wu_settings_fields_sanitization_rules

*No description provided.*

```php
apply_filters("wu_settings_fields_sanitization_rules")
```

Location: inc/ui/class-field.php:297

---
### wu_async_remove_old_primary_domains

*No description provided.*

```php
"wu_async_remove_old_primary_domains")
```

Location: inc/ui/class-domain-mapping-element.php:419

---
### wu_domain_created

Triggers when a new domain mapping is added.

```php
do_action("wu_domain_created")
```

Location: inc/ui/class-domain-mapping-element.php:428

---
### wu_async_remove_old_primary_domains

*No description provided.*

```php
"wu_async_remove_old_primary_domains")
```

Location: inc/ui/class-domain-mapping-element.php:606

---
### wu_tour_finished

*No description provided.*

```php
apply_filters("wu_tour_finished")
```

Location: inc/ui/class-tours.php:156

---
### wu_is_toolbox_enabled

*No description provided.*

```php
apply_filters("wu_is_toolbox_enabled")
```

Location: inc/ui/class-toolbox.php:58

---
### wu_current_site_actions

*No description provided.*

```php
apply_filters("wu_current_site_actions")
```

Location: inc/ui/class-current-site-element.php:343

---
### wu_form_edit_site

*No description provided.*

```php
apply_filters("wu_form_edit_site")
```

Location: inc/ui/class-current-site-element.php:402

---
### wu_{$id}_form_atts

*No description provided.*

```php
apply_filters("wu_{$id}_form_atts")
```

Location: inc/ui/class-form.php:51

---
### wu_{$id}_form_fields

Filters the fields on a form. The form is identified by the ID in the filter name.

Added in 2.0.0

```php
apply_filters("wu_{$id}_form_fields", array $fields)
```

Location: inc/ui/class-form.php:148

#### Arguments
* `$fields` (_array_) List of fields of the form.

---
### wu_element_loaded

*No description provided.*

```php
do_action("wu_element_loaded")
```

Location: inc/ui/class-base-element.php:216

---
### wu_element_block_types_to_check

We might need to add additional blocks later.

Added in 2.0.0

```php
apply_filters("wu_element_block_types_to_check")
```

Location: inc/ui/class-base-element.php:245

#### Arguments
*None.*

#### Expected Return
(_array_) No description provided.

---
### wu_contains_element

Allow developers to change the results of the initial search.

This is useful for third-party builders and such.

Added in 2.0.0

```php
apply_filters("wu_contains_element", bool $contains_elements, string $content)
```

Location: inc/ui/class-base-element.php:506

#### Arguments
* `$contains_elements` (_bool_) If the element is contained on the content.
* `$content` (_string_) The content being examined.
* `` (_self_) The current element.

---
### wu_element_maybe_extract_arguments

Adds generic filter to allow developers to extend this parser to deal with additional builders or plugins.

Added in 2.0.0

```php
apply_filters("wu_element_maybe_extract_arguments")
```

Location: inc/ui/class-base-element.php:563

#### Arguments
*None.*

#### Expected Return
(_false_|_array_) No description provided.

---
### wu_element_should_enqueue_scripts

*No description provided.*

```php
apply_filters("wu_element_should_enqueue_scripts")
```

Location: inc/ui/class-base-element.php:583

---
### wu_{$this->id}_scripts

Triggers the enqueue scripts hook.

This is used by the element to hook its register_scripts method.

Added in 2.0.0

```php
do_action("wu_{$this->id}_scripts")
```

Location: inc/ui/class-base-element.php:595

#### Arguments
*None.*

---
### wu_element_display_super_admin_notice

*No description provided.*

```php
apply_filters("wu_element_display_super_admin_notice")
```

Location: inc/ui/class-base-element.php:1028

---
### wu_{$this->id}_scripts

*No description provided.*

```php
do_action("wu_{$this->id}_scripts")
```

Location: inc/ui/class-base-element.php:1107

---
### wu_{$this->id}_scripts

*No description provided.*

```php
do_action("wu_{$this->id}_scripts")
```

Location: inc/ui/class-base-element.php:1198

---
### wu_element_is_preview

*No description provided.*

```php
apply_filters("wu_element_is_preview")
```

Location: inc/ui/class-base-element.php:1263

---
### wu_setup_checkout

*No description provided.*

```php
do_action("wu_setup_checkout")
```

Location: inc/ui/class-checkout-element.php:211

---
### wu_checkout_form_final_fields

Adds the same logic as the above for the template_id field.

Added in 2.0.8

```php
apply_filters("wu_checkout_form_final_fields")
```

Location: inc/ui/class-checkout-element.php:441

#### Arguments
*None.*

---
### wu_element_get_site_actions

*No description provided.*

```php
apply_filters("wu_element_get_site_actions")
```

Location: inc/ui/class-site-actions-element.php:277

---
### wu_element_get_site_actions

*No description provided.*

```php
apply_filters("wu_element_get_site_actions")
```

Location: inc/ui/class-site-actions-element.php:304

---
### wu_get_post_types

Allow developers to select which post types should be displayed.

Added in 2.0.0

```php
apply_filters("wu_get_post_types", array $post_types)
```

Location: inc/ui/class-limits-element.php:257

#### Arguments
* `$post_types` (_array_) List of post types.

#### Expected Return
(_array_) New list.

---
### wu_is_jumper_enabled

*No description provided.*

```php
apply_filters("wu_is_jumper_enabled")
```

Location: inc/ui/class-jumper.php:65

---
### wu_link_list

Adds Main Site Dashboard

```php
apply_filters("wu_link_list")
```

Location: inc/ui/class-jumper.php:484

---
### mercator_load

On WP Ultimo 1.X builds we used Mercator. The Mercator actions and filters are now deprecated.

Deprecated in 2.0.0 *Use 'wu_domain_mapping_load' instead.*

```php
do_action("mercator_load")
```

Location: inc/class-domain-mapping.php:157

---
### wu_domain_mapping_load

Fired after our core Domain Mapping has been loaded

Hook into this to handle any add-on functionality.

```php
do_action("wu_domain_mapping_load")
```

Location: inc/class-domain-mapping.php:166

---
### mercator.use_mapping

*No description provided.*

Deprecated in 2.0.0 *Use 'wu_use_domain_mapping' instead.*

```php
apply_filters("mercator.use_mapping")
```

Location: inc/class-domain-mapping.php:300

---
### wu_use_domain_mapping

Determine whether a mapping should be used

Typically, you'll want to only allow active mappings to be used. However, if you want to use more advanced logic, or allow non-active domains to be mapped too, simply filter here.

```php
apply_filters("wu_use_domain_mapping", boolean $is_active, \WP_Ultimo\WP_Ultimo\Models\Domain $mapping, string $domain)
```

Location: inc/class-domain-mapping.php:315

#### Arguments
* `$is_active` (_boolean_) Should the mapping be treated as active?
* `$mapping` (_\WP_Ultimo\WP_Ultimo\Models\Domain_) Mapping that we're inspecting
* `$domain` (_string_) 

---
### wu_domain_mapping_register_filters

Some plugins will save URL before the mapping was active or will build URLs in a different manner that is not included on the above filters.

In cases like that, we want to add additional filters. The second parameter passed is the mangle_url callback. We recommend against using this filter directly. Instead, use the Domain_Mapping::apply_mapping_to_url method.

Added in 2.0.0

```php
do_action("wu_domain_mapping_register_filters")
```

Location: inc/class-domain-mapping.php:472

#### Arguments
* `` (_array_) The mangle callable.
* `` (_self_) This object.

#### Expected Return
(_void_) No description provided.

---
### wu_system_info_data

*No description provided.*

```php
apply_filters("wu_system_info_data")
```

Location: inc/admin-pages/class-system-info-admin-page.php:329

---
### wu_handle_add_new_domain_modal

Fires before handle the add new domain modal request.

Added in 2.0.0

```php
do_action("wu_handle_add_new_domain_modal")
```

Location: inc/admin-pages/class-domain-list-admin-page.php:215

#### Arguments
*None.*

---
### wu_async_remove_old_primary_domains

*No description provided.*

```php
do_action("wu_async_remove_old_primary_domains")
```

Location: inc/admin-pages/class-domain-list-admin-page.php:246

---
### wu_handle_ajax_installers

*No description provided.*

```php
apply_filters("wu_handle_ajax_installers")
```

Location: inc/admin-pages/class-setup-wizard-admin-page.php:274

---
### wu_setup_wizard

Allow developers to add additional setup wizard steps.

Added in 2.0.0

```php
apply_filters("wu_setup_wizard", array $sections, bool $is_migration, object $this)
```

Location: inc/admin-pages/class-setup-wizard-admin-page.php:559

#### Arguments
* `$sections` (_array_) Current sections.
* `$is_migration` (_bool_) If this is a migration or not.
* `$this` (_object_) The current instance.

#### Expected Return
(_array_) No description provided.

---
### wu_setup_get_general_settings

*No description provided.*

```php
apply_filters("wu_setup_get_general_settings")
```

Location: inc/admin-pages/class-setup-wizard-admin-page.php:601

---
### wu_setup_get_payment_settings

*No description provided.*

```php
apply_filters("wu_setup_get_payment_settings")
```

Location: inc/admin-pages/class-setup-wizard-admin-page.php:629

---
### wp_ultimo_skip_network_active_check

*No description provided.*

```php
apply_filters("wp_ultimo_skip_network_active_check")
```

Location: inc/admin-pages/class-setup-wizard-admin-page.php:772

---
### wu_dashboard_display_filter

*No description provided.*

```php
apply_filters("wu_dashboard_display_filter")
```

Location: inc/admin-pages/class-dashboard-admin-page.php:111

---
### wu_dashboard_filter_bar

*No description provided.*

```php
apply_filters("wu_dashboard_filter_bar")
```

Location: inc/admin-pages/class-dashboard-admin-page.php:171

---
### wu_dashboard_{$this->tab}_widgets

Allow plugin developers to add widgets to Network Dashboard Panel.

Added in 2.0.0

```php
do_action("wu_dashboard_{$this->tab}_widgets", string $tab, \WP_Screen $screen, \WP_Ultimo\Admin_Pages\Dashboard_Admin_Page $page)
```

Location: inc/admin-pages/class-dashboard-admin-page.php:200

#### Arguments
* `$tab` (_string_) The current tab.
* `$screen` (_\WP_Screen_) The screen object.
* `$page` (_\WP_Ultimo\Admin_Pages\Dashboard_Admin_Page_) WP Ultimo admin page instance.

---
### wu_dashboard_widgets

Allow plugin developers to add widgets to Network Dashboard Panel.

Added in 2.0.0

```php
do_action("wu_dashboard_widgets", string $tab, \WP_Screen $screen, \WP_Ultimo\Admin_Pages\Dashboard_Admin_Page $page)
```

Location: inc/admin-pages/class-dashboard-admin-page.php:211

#### Arguments
* `$tab` (_string_) The current tab.
* `$screen` (_\WP_Screen_) The screen object.
* `$page` (_\WP_Ultimo\Admin_Pages\Dashboard_Admin_Page_) WP Ultimo admin page instance.

---
### wu_discount_code_options_sections

*No description provided.*

```php
apply_filters("wu_discount_code_options_sections")
```

Location: inc/admin-pages/class-discount-code-edit-admin-page.php:224

---
### wu_unlock_{$this->object_id}

Allow plugin developers to add actions to the unlocking process.

Added in 1.8.2

```php
do_action("wu_unlock_{$this->object_id}")
```

Location: inc/admin-pages/class-edit-admin-page.php:192

#### Arguments
*None.*

---
### wu_save_{$this->object_id}

Allow plugin developers to add actions to the saving process

Added in 1.8.2

```php
do_action("wu_save_{$this->object_id}")
```

Location: inc/admin-pages/class-edit-admin-page.php:229

#### Arguments
*None.*

---
### wu_delete_{$this->object_id}

Allow plugin developers to add actions to the deleting process

Added in 1.8.2

```php
do_action("wu_delete_{$this->object_id}")
```

Location: inc/admin-pages/class-edit-admin-page.php:265

#### Arguments
*None.*

---
### wu_edit_admin_page_labels

Calls the deleting function

```php
apply_filters("wu_edit_admin_page_labels")
```

Location: inc/admin-pages/class-edit-admin-page.php:296

---
### wu_allowed_line_item_types

Now, we deal with all the types.

First, check the valid types.

```php
apply_filters("wu_allowed_line_item_types")
```

Location: inc/admin-pages/class-payment-edit-admin-page.php:571

---
### wu_payments_options_sections

*No description provided.*

```php
apply_filters("wu_payments_options_sections")
```

Location: inc/admin-pages/class-payment-edit-admin-page.php:985

---
### wu_{$gateway_id}_remote_payment_url

*No description provided.*

```php
apply_filters("wu_{$gateway_id}_remote_payment_url")
```

Location: inc/admin-pages/class-payment-edit-admin-page.php:1080

---
### wu_site_options_sections

*No description provided.*

```php
apply_filters("wu_site_options_sections")
```

Location: inc/admin-pages/class-site-edit-admin-page.php:572

---
### wu_render_settings

*No description provided.*

```php
do_action("wu_render_settings")
```

Location: inc/admin-pages/class-settings-admin-page.php:608

---
### wu_customer_options_sections

Enqueue to the future

```php
apply_filters("wu_customer_options_sections")
```

Location: inc/admin-pages/class-customer-edit-admin-page.php:437

---
### wu_pending_site_published

*No description provided.*

```php
do_action("wu_pending_site_published")
```

Location: inc/admin-pages/class-site-list-admin-page.php:211

---
### wu_checkout_form_field_{$type}_id

Auto-assign ID if none is set

```php
apply_filters("wu_checkout_form_field_{$type}_id")
```

Location: inc/admin-pages/class-checkout-form-edit-admin-page.php:838

---
### wu_page_added

Allow plugin developers to run additional things when pages are registered.

Unlike the wu_page_load, which only runs when a specific page is being seen, this hook runs at registration for every admin page being added using WP Ultimo code.

Added in 2.0.0

```php
do_action("wu_page_added", string $page_id)
```

Location: inc/admin-pages/class-base-admin-page.php:201

#### Arguments
* `$page_id` (_string_) The ID of this page.

#### Expected Return
(_void_) No description provided.

---
### wu_page_load

Allow plugin developers to add additional hooks to our pages.

Added in 1.8.2

```php
do_action("wu_page_load", string $id, string $page_hook, self $admin_page)
```

Location: inc/admin-pages/class-base-admin-page.php:305

#### Arguments
* `$id` (_string_) The ID of this page.
* `$page_hook` (_string_) The page hook of this page.
* `$admin_page` (_self_) TThe page instance.

#### Expected Return
(_void_) No description provided.

---
### wu_page_{$this->id}_load

Allow plugin developers to add additional hooks to our pages.

Added in 1.8.2

```php
do_action("wu_page_{$this->id}_load", string $id, string $page_hook, self $admin_page)
```

Location: inc/admin-pages/class-base-admin-page.php:319

#### Arguments
* `$id` (_string_) The ID of this page.
* `$page_hook` (_string_) The page hook of this page.
* `$admin_page` (_self_) TThe page instance.

#### Expected Return
(_void_) No description provided.

---
### wu_page_before_render

Allow plugin developers to add additional content before we print the page.

Added in 1.8.2

```php
do_action("wu_page_before_render", string $this->id)
```

Location: inc/admin-pages/class-base-admin-page.php:374

#### Arguments
* `$this->id` (_string_) The id of this page.

#### Expected Return
(_void_) No description provided.

---
### wu_page_{$this->id}_before_render

Allow plugin developers to add additional content before we print the page.

Added in 1.8.2

```php
do_action("wu_page_{$this->id}_before_render", string $this->id)
```

Location: inc/admin-pages/class-base-admin-page.php:383

#### Arguments
* `$this->id` (_string_) The id of this page.

#### Expected Return
(_void_) No description provided.

---
### wu_page_after_render

Allow plugin developers to add additional content after we print the page

Added in 1.8.2

```php
do_action("wu_page_after_render", string $this->id)
```

Location: inc/admin-pages/class-base-admin-page.php:397

#### Arguments
* `$this->id` (_string_) The id of this page

#### Expected Return
(_void_) No description provided.

---
### wu_page_{$this->id}_after_render

Allow plugin developers to add additional content after we print the page

Added in 1.8.2

```php
do_action("wu_page_{$this->id}_after_render", string $this->id)
```

Location: inc/admin-pages/class-base-admin-page.php:406

#### Arguments
* `$this->id` (_string_) The id of this page

#### Expected Return
(_void_) No description provided.

---
### wp_ultimo_remove_branding

Add the default hooks

```php
apply_filters("wp_ultimo_remove_branding")
```

Location: inc/admin-pages/class-base-admin-page.php:501

---
### wu_enqueue_extra_hooks

Allow plugin developers to add additional hooks

Added in 1.8.2

```php
do_action("wu_enqueue_extra_hooks")
```

Location: inc/admin-pages/class-base-admin-page.php:640

#### Arguments
* `` (_string_) 

---
### wu_page_get_title_links

Allow plugin developers, and ourselves, to add action links to our edit pages

Added in 1.8.2

```php
apply_filters("wu_page_get_title_links", \WP_Ultimo\Admin_Pages\WU_Page_Edit $this)
```

Location: inc/admin-pages/class-base-admin-page.php:671

#### Arguments
* `$this` (_\WP_Ultimo\Admin_Pages\WU_Page_Edit_) This instance

#### Expected Return
(_array_) No description provided.

---
### wu_form_scripts

*No description provided.*

```php
do_action("wu_form_scripts")
```

Location: inc/admin-pages/class-addons-admin-page.php:171

---
### wu_customer_facing_page_{$this->id}_fields

*No description provided.*

```php
apply_filters("wu_customer_facing_page_{$this->id}_fields")
```

Location: inc/admin-pages/class-base-customer-facing-admin-page.php:164

---
### wu_membership_options_sections

*No description provided.*

```php
apply_filters("wu_membership_options_sections")
```

Location: inc/admin-pages/class-membership-edit-admin-page.php:389

---
### wu_{$gateway_id}_remote_customer_url

*No description provided.*

```php
apply_filters("wu_{$gateway_id}_remote_customer_url")
```

Location: inc/admin-pages/class-membership-edit-admin-page.php:693

---
### wu_{$gateway_id}_remote_subscription_url

*No description provided.*

```php
apply_filters("wu_{$gateway_id}_remote_subscription_url")
```

Location: inc/admin-pages/class-membership-edit-admin-page.php:734

---
### wu_load_edit_placeholders_list_page

*No description provided.*

```php
do_action("wu_load_edit_placeholders_list_page")
```

Location: inc/admin-pages/class-placeholders-admin-page.php:109

---
### wu_edit_placeholders_columns

*No description provided.*

```php
apply_filters("wu_edit_placeholders_columns")
```

Location: inc/admin-pages/class-placeholders-admin-page.php:111

---
### wu_load_tax_rates_list_page

*No description provided.*

```php
do_action("wu_load_tax_rates_list_page")
```

Location: inc/admin-pages/class-tax-rates-admin-page.php:111

---
### wu_tax_rates_columns

*No description provided.*

```php
apply_filters("wu_tax_rates_columns")
```

Location: inc/admin-pages/class-tax-rates-admin-page.php:113

---
### wu_product_edit_save_widget

*No description provided.*

```php
apply_filters("wu_product_edit_save_widget")
```

Location: inc/admin-pages/class-product-edit-admin-page.php:267

---
### wu_plans_advanced_options_tabs

*No description provided.*

Deprecated in 2.0.0 *Use 'wu_product_options_sections' instead.*

```php
apply_filters("wu_plans_advanced_options_tabs")
```

Location: inc/admin-pages/class-product-edit-admin-page.php:538

---
### wu_product_options_sections

*No description provided.*

```php
apply_filters("wu_product_options_sections")
```

Location: inc/admin-pages/class-product-edit-admin-page.php:888

---
### wu_account_update_message

*No description provided.*

```php
apply_filters("wu_account_update_message")
```

Location: inc/admin-pages/customer-panel/class-account-admin-page.php:590

---
### wu_template_switching_admin_page_scripts

*No description provided.*

```php
do_action("wu_template_switching_admin_page_scripts")
```

Location: inc/admin-pages/customer-panel/class-template-switching-admin-page.php:130

---
### wu_template_switching_admin_page

*No description provided.*

```php
do_action("wu_template_switching_admin_page")
```

Location: inc/admin-pages/customer-panel/class-template-switching-admin-page.php:142

---
### wu_checkout_scripts

*No description provided.*

```php
do_action("wu_checkout_scripts")
```

Location: inc/admin-pages/customer-panel/class-checkout-admin-page.php:122

---
### wu_setup_checkout

*No description provided.*

```php
do_action("wu_setup_checkout")
```

Location: inc/admin-pages/customer-panel/class-checkout-admin-page.php:134

---
### wu_template_selection_rewrite_rule_slug

*No description provided.*

```php
apply_filters("wu_template_selection_rewrite_rule_slug")
```

Location: inc/checkout/class-checkout.php:212

---
### wu_get_checkout_from_query_vars

*No description provided.*

```php
apply_filters("wu_get_checkout_from_query_vars")
```

Location: inc/checkout/class-checkout.php:246

---
### wu_checkout_get_auto_submittable_fields

They key should be the signup field ID to search for, while the value should be the parameter we should watch for changes so we can submit the form when we detect one.

```php
apply_filters("wu_checkout_get_auto_submittable_fields")
```

Location: inc/checkout/class-checkout.php:417

---
### wu_before_handle_order_submission

*No description provided.*

```php
do_action("wu_before_handle_order_submission")
```

Location: inc/checkout/class-checkout.php:471

---
### wu_after_handle_order_submission

*No description provided.*

```php
do_action("wu_after_handle_order_submission")
```

Location: inc/checkout/class-checkout.php:487

---
### wu_cart_parameters

*No description provided.*

```php
apply_filters("wu_cart_parameters")
```

Location: inc/checkout/class-checkout.php:555

---
### wu_checkout_after_process_order

Allow developers to triggers additional hooks.

Added in 2.0.9

```php
do_action("wu_checkout_after_process_order", \WP_Ultimo\Checkout\Checkout $checkout, \WP_Ultimo\Checkout\Cart $cart)
```

Location: inc/checkout/class-checkout.php:859

#### Arguments
* `$checkout` (_\WP_Ultimo\Checkout\Checkout_) The checkout object instance.
* `$cart` (_\WP_Ultimo\Checkout\Cart_) The checkout cart instance.

#### Expected Return
(_void_) No description provided.

---
### wu_maybe_create_customer

Allow plugin developers to do additional stuff when the customer is added.

Here's where we add the hooks for adding the customer-&gt;user to the main site as well, for example.

Added in 2.0.0

```php
do_action("wu_maybe_create_customer", \WP_Ultimo\Checkout\Customer $customer, \WP_Ultimo\Checkout\Checkout $this)
```

Location: inc/checkout/class-checkout.php:1027

#### Arguments
* `$customer` (_\WP_Ultimo\Checkout\Customer_) The customer that was maybe created.
* `$this` (_\WP_Ultimo\Checkout\Checkout_) The current checkout class.

---
### wu_handle_customer_meta_fields

Allow plugin developers to save meta data in different ways if they need to.

Added in 2.0.0

```php
do_action("wu_handle_customer_meta_fields", array $meta_repository, \WP_Ultimo\Checkout\Customer $customer, \WP_Ultimo\Checkout\Checkout $this)
```

Location: inc/checkout/class-checkout.php:1081

#### Arguments
* `$meta_repository` (_array_) The list of meta fields, key =&gt; value structured.
* `$customer` (_\WP_Ultimo\Checkout\Customer_) The WP Ultimo customer object.
* `$this` (_\WP_Ultimo\Checkout\Checkout_) The checkout class.

---
### wu_handle_user_meta_fields

Allow plugin developers to save user meta data in different ways if they need to.

Added in 2.0.4

```php
do_action("wu_handle_user_meta_fields", array $meta_repository, \WP_User $user, \WP_Ultimo\Checkout\Customer $customer, \WP_Ultimo\Checkout\Checkout $this)
```

Location: inc/checkout/class-checkout.php:1115

#### Arguments
* `$meta_repository` (_array_) The list of meta fields, key =&gt; value structured.
* `$user` (_\WP_User_) The WordPress user object.
* `$customer` (_\WP_Ultimo\Checkout\Customer_) The WP Ultimo customer object.
* `$this` (_\WP_Ultimo\Checkout\Checkout_) The checkout class.

---
### wu_checkout_template_id

Do basically the same thing, now for user meta.

Added in 2.0.4

```php
apply_filters("wu_checkout_template_id")
```

Location: inc/checkout/class-checkout.php:1271

#### Arguments
*None.*

---
### wu_get_checkout_variables

Allow plugin developers to filter the pre-sets of a checkout page.

Be careful, missing keys can completely break the checkout on the front-end.

Added in 2.0.0

```php
apply_filters("wu_get_checkout_variables", array $variables, \WP_Ultimo\Checkout\Checkout $this)
```

Location: inc/checkout/class-checkout.php:1607

#### Arguments
* `$variables` (_array_) Localized variables.
* `$this` (_\WP_Ultimo\Checkout\Checkout_) The checkout class.

#### Expected Return
(_array_) The new variables array.

---
### wu_checkout_validation_rules

*No description provided.*

```php
apply_filters("wu_checkout_validation_rules")
```

Location: inc/checkout/class-checkout.php:1651

---
### wu_checkout_done

Add the additional required fields.

```php
do_action("wu_checkout_done")
```

Location: inc/checkout/class-checkout.php:2028

---
### wp_ultimo_registration

*No description provided.*

Deprecated in 2.0.0 **

```php
do_action("wp_ultimo_registration")
```

Location: inc/checkout/class-checkout.php:2046

---
### wp_ultimo_redirect_url_after_signup

Set the redirect URL.

This is a legacy filter. Some of the parameters passed are not available, such as the $site_id.

Added in 1.1.3

```php
apply_filters("wp_ultimo_redirect_url_after_signup")
```

Location: inc/checkout/class-checkout.php:2087

#### Arguments
*None.*

---
### wu_checkout_custom_css

*No description provided.*

```php
apply_filters("wu_checkout_custom_css")
```

Location: inc/checkout/class-checkout.php:2191

---
### wu_maybe_redirect_to_admin_panel_exclusion_list

Create an exclusion list of parameters that prevent the auto-redirect.

This is needed because otherwise page builder won't be able to edit the login page once it is defined.

Added in 2.0.4

```php
apply_filters("wu_maybe_redirect_to_admin_panel_exclusion_list")
```

Location: inc/checkout/class-checkout-pages.php:350

#### Arguments
*None.*

#### Expected Return
(_array_) No description provided.

---
### wu_get_pricing_table_templates

*No description provided.*

```php
apply_filters("wu_get_pricing_table_templates")
```

Location: inc/checkout/signup-fields/class-signup-field-site-url.php:272

---
### wu_cart_setup

Allow developers to make additional changes to the checkout object.

Added in 2.0.0

```php
do_action("wu_cart_setup")
```

Location: inc/checkout/class-cart.php:274

#### Arguments
* `` (_self_) The cart object.

---
### wu_cart_after_setup

Allow developers to make additional changes to the checkout object.

Added in 2.0.0

```php
do_action("wu_cart_after_setup")
```

Location: inc/checkout/class-cart.php:329

#### Arguments
* `` (_self_) The cart object.

---
### wu_cart_is_tax_exempt

*No description provided.*

```php
apply_filters("wu_cart_is_tax_exempt")
```

Location: inc/checkout/class-cart.php:373

---
### wu_cart_set_payment_allowed_status

*No description provided.*

```php
apply_filters("wu_cart_set_payment_allowed_status")
```

Location: inc/checkout/class-cart.php:537

---
### wu_checkout_calculate_prorate_credits

Allow plugin developers to meddle with the credit value.

Added in 2.0.0

```php
apply_filters("wu_checkout_calculate_prorate_credits", int $credit, self $cart)
```

Location: inc/checkout/class-cart.php:993

#### Arguments
* `$credit` (_int_) The credit amount.
* `$cart` (_self_) This cart object.

---
### wu_checkout_credit_line_item_params

*No description provided.*

```php
apply_filters("wu_checkout_credit_line_item_params")
```

Location: inc/checkout/class-cart.php:1004

---
### wu_cart_should_collect_payment

*No description provided.*

```php
apply_filters("wu_cart_should_collect_payment")
```

Location: inc/checkout/class-cart.php:1190

---
### wu_add_product_line_item

*No description provided.*

```php
apply_filters("wu_add_product_line_item")
```

Location: inc/checkout/class-cart.php:1418

---
### wu_apply_signup_fee

Filters whether or not the signup fee should be applied.

Added in 3.1

```php
apply_filters("wu_apply_signup_fee", bool $add_signup_fee, object $product, \WP_Ultimo\Checkout\Cart $this)
```

Location: inc/checkout/class-cart.php:1463

#### Arguments
* `$add_signup_fee` (_bool_) Whether or not to add the signup fee.
* `$product` (_object_) Membership level object.
* `$this` (_\WP_Ultimo\Checkout\Cart_) Registration object.

---
### wu_cart_get_total_fees

*No description provided.*

```php
apply_filters("wu_cart_get_total_fees")
```

Location: inc/checkout/class-cart.php:1730

---
### wu_cart_get_proration_fees

*No description provided.*

```php
apply_filters("wu_cart_get_proration_fees")
```

Location: inc/checkout/class-cart.php:1764

---
### wu_cart_get_total_discounts

*No description provided.*

```php
apply_filters("wu_cart_get_total_discounts")
```

Location: inc/checkout/class-cart.php:1786

---
### wu_cart_get_subtotal

Filter the "initial amount" total.

```php
apply_filters("wu_cart_get_subtotal", float $subtotal)
```

Location: inc/checkout/class-cart.php:1831

#### Arguments
* `$subtotal` (_float_) Total amount due today.
* `` (_\WP_Ultimo\Checkout\Cart_) Cart object.

---
### wu_cart_get_total

Filter the "initial amount" total.

```php
apply_filters("wu_cart_get_total", float $total)
```

Location: inc/checkout/class-cart.php:1865

#### Arguments
* `$total` (_float_) Total amount due today.
* `` (_\WP_Ultimo\Checkout\Cart_) Cart object.

---
### wu_cart_get_recurring_total

Filters the "recurring amount" total.

```php
apply_filters("wu_cart_get_recurring_total", float $total)
```

Location: inc/checkout/class-cart.php:1926

#### Arguments
* `$total` (_float_) Recurring amount.
* `` (_\WP_Ultimo\Checkout\Cart_) Cart object.

---
### wu_cart_get_recurring_total

Filters the "recurring amount" total.

```php
apply_filters("wu_cart_get_recurring_total", float $subtotal)
```

Location: inc/checkout/class-cart.php:1966

#### Arguments
* `$subtotal` (_float_) Recurring amount.
* `` (_\WP_Ultimo\Checkout\Cart_) Cart object.

---
### wu_cart_applicable_tax_rates

No tax category, bail.

```php
apply_filters("wu_cart_applicable_tax_rates")
```

Location: inc/checkout/class-cart.php:2173

---
### wu_cart_get_extra_params

*No description provided.*

```php
apply_filters("wu_cart_get_extra_params")
```

Location: inc/checkout/class-cart.php:2255

---
### wu_geolocation_error_message

Product passed

```php
apply_filters("wu_geolocation_error_message")
```

Location: inc/checkout/class-legacy-checkout.php:397

#### Arguments
*None.*

---
### wu_signup_step_handler_{$this->step}

Allows for handler rewrite

```php
apply_filters("wu_signup_step_handler_{$this->step}")
```

Location: inc/checkout/class-legacy-checkout.php:446

---
### wu_replace_signup_urls_exclude

Go to the next step

```php
apply_filters("wu_replace_signup_urls_exclude")
```

Location: inc/checkout/class-legacy-checkout.php:550

---
### wu_current_step

*No description provided.*

```php
apply_filters("wu_current_step")
```

Location: inc/checkout/class-legacy-checkout.php:603

---
### wu_signup_fields_domain

Let's try to locate a custom template on the user's theme. If it's there, we use it instead

```php
apply_filters("wu_signup_fields_domain")
```

Location: inc/checkout/class-legacy-checkout.php:722

---
### wu_signup_site_title_label

*No description provided.*

```php
apply_filters("wu_signup_site_title_label")
```

Location: inc/checkout/class-legacy-checkout.php:725

---
### wu_signup_site_title_tooltip

*No description provided.*

```php
apply_filters("wu_signup_site_title_tooltip")
```

Location: inc/checkout/class-legacy-checkout.php:729

---
### wu_signup_site_url_label

*No description provided.*

```php
apply_filters("wu_signup_site_url_label")
```

Location: inc/checkout/class-legacy-checkout.php:735

---
### wu_signup_site_url_tooltip

*No description provided.*

```php
apply_filters("wu_signup_site_url_tooltip")
```

Location: inc/checkout/class-legacy-checkout.php:739

---
### wu_signup_username_label

Since there are some conditional fields on the accounts step, we need to declare the variable before so we can append items and filter it later

```php
apply_filters("wu_signup_username_label")
```

Location: inc/checkout/class-legacy-checkout.php:766

---
### wu_signup_username_tooltip

*No description provided.*

```php
apply_filters("wu_signup_username_tooltip")
```

Location: inc/checkout/class-legacy-checkout.php:770

---
### wu_signup_email_label

*No description provided.*

```php
apply_filters("wu_signup_email_label")
```

Location: inc/checkout/class-legacy-checkout.php:777

---
### wu_signup_email_tooltip

*No description provided.*

```php
apply_filters("wu_signup_email_tooltip")
```

Location: inc/checkout/class-legacy-checkout.php:781

---
### wu_signup_password_label

*No description provided.*

```php
apply_filters("wu_signup_password_label")
```

Location: inc/checkout/class-legacy-checkout.php:788

---
### wu_signup_password_tooltip

*No description provided.*

```php
apply_filters("wu_signup_password_tooltip")
```

Location: inc/checkout/class-legacy-checkout.php:792

---
### wu_signup_password_conf_label

*No description provided.*

```php
apply_filters("wu_signup_password_conf_label")
```

Location: inc/checkout/class-legacy-checkout.php:799

---
### wu_signup_password_conf_tooltip

*No description provided.*

```php
apply_filters("wu_signup_password_conf_tooltip")
```

Location: inc/checkout/class-legacy-checkout.php:803

---
### wu_signup_fields_account

Submit Field

```php
apply_filters("wu_signup_fields_account")
```

Location: inc/checkout/class-legacy-checkout.php:889

---
### wp_ultimo_registration_steps

Add additional steps via filters

```php
apply_filters("wp_ultimo_registration_steps")
```

Location: inc/checkout/class-legacy-checkout.php:895

---
### get_site_url_for_previewer

Allow plugin developers to filter the URL used in the previewer

Added in 1.7.2

```php
apply_filters("get_site_url_for_previewer")
```

Location: inc/checkout/class-legacy-checkout.php:1256

#### Arguments
* `` (_string_) Default domain being used right now, useful for manipulations
* `` (_array_) List of all the domain options entered in the WP Ultimo Settings -&gt; Network Settings -&gt; Domain Options

#### Expected Return
(_string_) New domain to be used

---
### wp_ultimo_registration_step_plans_save_transient

*No description provided.*

```php
apply_filters("wp_ultimo_registration_step_plans_save_transient")
```

Location: inc/checkout/class-legacy-checkout.php:1286

---
### wp_ultimo_registration_step_plans_save

*No description provided.*

```php
do_action("wp_ultimo_registration_step_plans_save")
```

Location: inc/checkout/class-legacy-checkout.php:1289

---
### wp_ultimo_registration_step_domain_save

Sanitizes Input

```php
do_action("wp_ultimo_registration_step_domain_save")
```

Location: inc/checkout/class-legacy-checkout.php:1333

---
### wu_should_load_multiple_accounts_support

*No description provided.*

```php
apply_filters("wu_should_load_multiple_accounts_support")
```

Location: inc/compat/class-multiple-accounts-compat.php:177

---
### wu_checkout_scripts

In the case of the legacy layout, we need to load extra styles.

```php
do_action("wu_checkout_scripts")
```

Location: inc/compat/class-legacy-shortcodes.php:309

---
### wu_setup_checkout

*No description provided.*

```php
do_action("wu_setup_checkout")
```

Location: inc/compat/class-legacy-shortcodes.php:311

---
### wu_checkout_form_shortcode_pricing_table_fields

If not using the legacy checkout, we'll need a submit field.

```php
apply_filters("wu_checkout_form_shortcode_pricing_table_fields")
```

Location: inc/compat/class-legacy-shortcodes.php:397

---
### wu_checkout_scripts

*No description provided.*

```php
do_action("wu_checkout_scripts")
```

Location: inc/compat/class-legacy-shortcodes.php:403

---
### wu_setup_checkout

*No description provided.*

```php
do_action("wu_setup_checkout")
```

Location: inc/compat/class-legacy-shortcodes.php:405

---
### wu_checkout_form_shortcode_templates_list_fields

In the case of the legacy layout, we need to load extra styles.

```php
apply_filters("wu_checkout_form_shortcode_templates_list_fields")
```

Location: inc/compat/class-legacy-shortcodes.php:531

---
### wu_checkout_scripts

*No description provided.*

```php
do_action("wu_checkout_scripts")
```

Location: inc/compat/class-legacy-shortcodes.php:539

---
### wu_setup_checkout

*No description provided.*

```php
do_action("wu_setup_checkout")
```

Location: inc/compat/class-legacy-shortcodes.php:541

---
### wu_gutenberg_support_should_load

*No description provided.*

```php
apply_filters("wu_gutenberg_support_should_load")
```

Location: inc/compat/class-gutenberg-support.php:43

---
### wu_gutenberg_support_preview_message

*No description provided.*

```php
apply_filters("wu_gutenberg_support_preview_message")
```

Location: inc/compat/class-gutenberg-support.php:74

---
### wu_documentation_links_list

*No description provided.*

```php
apply_filters("wu_documentation_links_list")
```

Location: inc/class-documentation.php:86

---
### wu_documentation_get_link

Allow plugin developers to filter the links.

Not sure how that could be useful, but it doesn't hurt to have it

Added in 1.7.0

```php
apply_filters("wu_documentation_get_link", string $link, string $slug, string $default_link)
```

Location: inc/class-documentation.php:127

#### Arguments
* `$link` (_string_) The link registered
* `$slug` (_string_) The slug used to retrieve the link
* `$default_link` (_string_) The default link registered

---
### wp_ultimo_url

*No description provided.*

```php
apply_filters("wp_ultimo_url")
```

Location: inc/class-helper.php:70

---
### wp_ultimo_render_vars

Allow plugin developers to add extra variable to the render context globally.

Added in 2.0.0

```php
apply_filters("wp_ultimo_render_vars", array $vars, string $view, string $default_view)
```

Location: inc/class-helper.php:115

#### Arguments
* `$vars` (_array_) Array containing variables passed by the render call.
* `$view` (_string_) Name of the view to be rendered.
* `$default_view` (_string_) Name of the fallback_view

#### Expected Return
(_array_) No description provided.

---
### wu_view_override_replaceable_views

Allows developers to add additional folders to the replaceable list.

Be careful, as allowing additional folders might cause out-of-date copies to be loaded instead of the WP Ultimo versions.

Added in 2.0.0

```php
apply_filters("wu_view_override_replaceable_views", array $replaceable_views)
```

Location: inc/class-helper.php:136

#### Arguments
* `$replaceable_views` (_array_) List of allowed folders.

#### Expected Return
(_array_) No description provided.

---
### wu_view_override

*No description provided.*

```php
apply_filters("wu_view_override")
```

Location: inc/class-helper.php:143

---
### wu_get_option

*No description provided.*

```php
apply_filters("wu_get_option")
```

Location: inc/class-helper.php:267

---
### wu_drop_tables

*No description provided.*

```php
apply_filters("wu_drop_tables")
```

Location: inc/class-helper.php:388

---
### wu_drop_tables_except

*No description provided.*

```php
apply_filters("wu_drop_tables_except")
```

Location: inc/class-helper.php:395

---
### wu_blocks

*No description provided.*

```php
apply_filters("wu_blocks")
```

Location: inc/builders/block-editor/class-block-editor-widget-manager.php:56

---
### wu_{$this->id}_get_items

*No description provided.*

```php
apply_filters("wu_{$this->id}_get_items")
```

Location: inc/list-tables/class-site-list-table.php:94

---
### wu_{$this->id}_get_items

Accounts for hashes

```php
apply_filters("wu_{$this->id}_get_items")
```

Location: inc/list-tables/class-payment-list-table-widget.php:89

---
### wu_{$this->id}_get_items

*No description provided.*

```php
apply_filters("wu_{$this->id}_get_items")
```

Location: inc/list-tables/class-email-list-table.php:88

---
### wu_{$this->id}_get_items

Accounts for hashes

```php
apply_filters("wu_{$this->id}_get_items")
```

Location: inc/list-tables/class-base-list-table.php:313

---
### wu_{$this->id}_get_views

Call parents implementation.

```php
apply_filters("wu_{$this->id}_get_views")
```

Location: inc/list-tables/class-base-list-table.php:577

---
### wu_bulk_actions

*No description provided.*

```php
apply_filters("wu_bulk_actions")
```

Location: inc/list-tables/class-base-list-table.php:670

---
### wu_process_bulk_action

*No description provided.*

```php
do_action("wu_process_bulk_action")
```

Location: inc/list-tables/class-base-list-table.php:756

---
### wu_events_list_table_get_columns

*No description provided.*

```php
apply_filters("wu_events_list_table_get_columns")
```

Location: inc/list-tables/class-event-list-table.php:222

---
### wu_{$this->id}_get_items

Accounts for hashes

```php
apply_filters("wu_{$this->id}_get_items")
```

Location: inc/list-tables/class-membership-list-table-widget.php:89

---
### wu_stripe_create_payment_intent_args

Filters the payment intent arguments.

Added in 2.0

```php
apply_filters("wu_stripe_create_payment_intent_args", array $intent_args, \WP_Ultimo\Gateways\Stripe_Gateway $this.)
```

Location: inc/gateways/class-stripe-gateway.php:310

#### Arguments
* `$intent_args` (_array_) The list of intent args.
* `$this.` (_\WP_Ultimo\Gateways\Stripe_Gateway_) 

#### Expected Return
(_array_) No description provided.

---
### wu_gateway_payment_processed

*No description provided.*

```php
do_action("wu_gateway_payment_processed")
```

Location: inc/gateways/class-base-gateway.php:649

---
### wu_stripe_customer_create_args

*No description provided.*

```php
apply_filters("wu_stripe_customer_create_args")
```

Location: inc/gateways/class-base-stripe-gateway.php:405

---
### wu_stripe_create_subscription_options

*No description provided.*

```php
apply_filters("wu_stripe_create_subscription_options")
```

Location: inc/gateways/class-base-stripe-gateway.php:551

---
### wu_stripe_create_subscription_args

*No description provided.*

```php
apply_filters("wu_stripe_create_subscription_args")
```

Location: inc/gateways/class-base-stripe-gateway.php:558

---
### wu_stripe_webhook_membership

Filters the membership record associated with this webhook.

This filter was introduced due to conflicts that may arise when the same Stripe customer may be used on different sites.

```php
apply_filters("wu_stripe_webhook_membership", \WP_Ultimo\Models\Membership|false $membership, \WP_Ultimo\Dependencies\Stripe\Event $event)
```

Location: inc/gateways/class-base-stripe-gateway.php:1365

#### Arguments
* `$membership` (_\WP_Ultimo\Models\Membership_|_false_) The membership object.
* `$event` (_\WP_Ultimo\Dependencies\Stripe\Event_) The event received.

---
### wu_webhook_recurring_payment_profile_created

*No description provided.*

```php
do_action("wu_webhook_recurring_payment_profile_created")
```

Location: inc/gateways/class-base-stripe-gateway.php:1394

---
### wu_recurring_payment_failed

*No description provided.*

```php
do_action("wu_recurring_payment_failed")
```

Location: inc/gateways/class-base-stripe-gateway.php:1613

---
### wu_stripe_charge_failed

*No description provided.*

```php
do_action("wu_stripe_charge_failed")
```

Location: inc/gateways/class-base-stripe-gateway.php:1617

---
### wu_stripe_existing_plan_id

Filters the ID of the plan to check for. If this exists, the new subscription will use this plan.

```php
apply_filters("wu_stripe_existing_plan_id", string $plan_id, object $membership_level)
```

Location: inc/gateways/class-base-stripe-gateway.php:1915

#### Arguments
* `$plan_id` (_string_) ID of the Stripe plan to check for.
* `$membership_level` (_object_) Membership level object.

---
### wu_stripe_checkout_allowed_payment_method_types

*No description provided.*

```php
apply_filters("wu_stripe_checkout_allowed_payment_method_types")
```

Location: inc/gateways/class-stripe-checkout-gateway.php:195

---
### wu_ipn_post

*No description provided.*

```php
apply_filters("wu_ipn_post")
```

Location: inc/gateways/class-paypal-gateway.php:739

---
### wu_{$key}_render_attributes

*No description provided.*

```php
apply_filters("wu_{$key}_render_attributes")
```

Location: inc/managers/class-field-templates-manager.php:64

---
### wu_register_field_templates

*No description provided.*

```php
do_action("wu_register_field_templates")
```

Location: inc/managers/class-field-templates-manager.php:138

---
### wu_checkout_field_templates

Our APIs to add new field templates hook into here.

Do not use this filter directly. Use the wu_register_field_template() function instead.

Added in 2.0.0

```php
apply_filters("wu_checkout_field_templates", array $field_templates)
```

Location: inc/managers/class-field-templates-manager.php:151

#### Arguments
* `$field_templates` (_array_) 

#### Expected Return
(_array_) No description provided.

---
### wu_should_log_webhook_calls

*No description provided.*

```php
apply_filters("wu_should_log_webhook_calls")
```

Location: inc/managers/class-webhook-manager.php:324

---
### wu_flush_known_caches

Hook to additional cleaning

```php
do_action("wu_flush_known_caches")
```

Location: inc/managers/class-visits-manager.php:179

---
### wu_register_gateways

*No description provided.*

```php
do_action("wu_register_gateways")
```

Location: inc/managers/class-gateway-manager.php:102

---
### wu_{$gateway}_process_webhooks

*No description provided.*

```php
do_action("wu_{$gateway}_process_webhooks")
```

Location: inc/managers/class-gateway-manager.php:136

---
### wu_{$gateway_id}_process_webhooks

*No description provided.*

```php
do_action("wu_{$gateway_id}_process_webhooks")
```

Location: inc/managers/class-gateway-manager.php:214

---
### wu_hide_notifications_exclude_list

*No description provided.*

```php
apply_filters("wu_hide_notifications_exclude_list")
```

Location: inc/managers/class-notification-manager.php:63

---
### wu_exclude_transitions_keys

*No description provided.*

```php
apply_filters("wu_exclude_transitions_keys")
```

Location: inc/managers/class-event-manager.php:106

---
### wu_event

Loop changed data.

```php
do_action("wu_event")
```

Location: inc/managers/class-event-manager.php:291

---
### wu_event_{$slug}

*No description provided.*

```php
do_action("wu_event_{$slug}")
```

Location: inc/managers/class-event-manager.php:293

---
### wu_register_all_events

Domain Mapping Added

```php
do_action("wu_register_all_events")
```

Location: inc/managers/class-event-manager.php:477

---
### wu_events_threshold_days

*No description provided.*

```php
apply_filters("wu_events_threshold_days")
```

Location: inc/managers/class-event-manager.php:492

---
### wu_limitations_get_object_type

*No description provided.*

```php
apply_filters("wu_limitations_get_object_type")
```

Location: inc/managers/class-limitation-manager.php:272

---
### wu_limitations_get_sites_fields

*No description provided.*

```php
apply_filters("wu_limitations_get_sites_fields")
```

Location: inc/managers/class-limitation-manager.php:811

---
### wu_limitations_plugin_exclusion_list

*No description provided.*

```php
apply_filters("wu_limitations_plugin_exclusion_list")
```

Location: inc/managers/class-limitation-manager.php:924

---
### wu_limitations_theme_exclusion_list

*No description provided.*

```php
apply_filters("wu_limitations_theme_exclusion_list")
```

Location: inc/managers/class-limitation-manager.php:938

---
### wu_system_emails_after_register

*No description provided.*

```php
do_action("wu_system_emails_after_register")
```

Location: inc/managers/class-email-manager.php:434

---
### wu_notes_options_section_fields

*No description provided.*

```php
apply_filters("wu_notes_options_section_fields")
```

Location: inc/managers/class-notes-manager.php:230

---
### wu_register_forms

*No description provided.*

```php
do_action("wu_register_forms")
```

Location: inc/managers/class-form-manager.php:52

---
### wu_form_scripts

*No description provided.*

```php
do_action("wu_form_scripts")
```

Location: inc/managers/class-form-manager.php:85

---
### wu_form_scripts

*No description provided.*

```php
do_action("wu_form_scripts")
```

Location: inc/managers/class-form-manager.php:124

---
### wu_delete_form_get_object_{$model}

The handler is supposed to send a wp_json message back.

However, if it returns a WP_Error object, we know something went wrong and that we should display the error message.

```php
apply_filters("wu_delete_form_get_object_{$model}")
```

Location: inc/managers/class-form-manager.php:354

---
### wu_form_fields_delete_{$model}_modal

*No description provided.*

```php
apply_filters("wu_form_fields_delete_{$model}_modal")
```

Location: inc/managers/class-form-manager.php:364

---
### wu_form_attributes_delete_{$model}_modal

*No description provided.*

```php
apply_filters("wu_form_attributes_delete_{$model}_modal")
```

Location: inc/managers/class-form-manager.php:406

---
### wu_before_render_delete_{$model}_modal

*No description provided.*

```php
do_action("wu_before_render_delete_{$model}_modal")
```

Location: inc/managers/class-form-manager.php:421

---
### wu_delete_form_get_object_{$model}

*No description provided.*

```php
apply_filters("wu_delete_form_get_object_{$model}")
```

Location: inc/managers/class-form-manager.php:477

---
### wu_before_delete_{$model}_modal

*No description provided.*

```php
do_action("wu_before_delete_{$model}_modal")
```

Location: inc/managers/class-form-manager.php:488

---
### wu_after_delete_{$model}_modal

*No description provided.*

```php
do_action("wu_after_delete_{$model}_modal")
```

Location: inc/managers/class-form-manager.php:498

---
### wu_data_json_success_delete_{$model}_modal

*No description provided.*

```php
apply_filters("wu_data_json_success_delete_{$model}_modal")
```

Location: inc/managers/class-form-manager.php:500

---
### wu_bulk_actions_{$model}_{$action}

*No description provided.*

```php
apply_filters("wu_bulk_actions_{$model}_{$action}")
```

Location: inc/managers/class-form-manager.php:526

---
### wu_bulk_actions_{$action}_form

*No description provided.*

```php
apply_filters("wu_bulk_actions_{$action}_form")
```

Location: inc/managers/class-form-manager.php:560

---
### wu_handle_bulk_action_form_{$model}_{$action}

*No description provided.*

```php
do_action("wu_handle_bulk_action_form_{$model}_{$action}")
```

Location: inc/managers/class-form-manager.php:594

---
### wu_handle_bulk_action_form

*No description provided.*

```php
do_action("wu_handle_bulk_action_form")
```

Location: inc/managers/class-form-manager.php:596

---
### wu_register_field_types

*No description provided.*

```php
do_action("wu_register_field_types")
```

Location: inc/managers/class-signup-fields-manager.php:79

---
### wu_checkout_field_types

Our APIs to add new field types hook into here.

Do not use this filter directly. Use the wu_register_field_type() function instead.

Added in 2.0.0

```php
apply_filters("wu_checkout_field_types", array $field_types)
```

Location: inc/managers/class-signup-fields-manager.php:92

#### Arguments
* `$field_types` (_array_) 

#### Expected Return
(_array_) No description provided.

---
### wu_search_and_replace_on_duplication

*No description provided.*

```php
apply_filters("wu_search_and_replace_on_duplication")
```

Location: inc/managers/class-site-manager.php:419

---
### mucd_string_to_replace

In order to be backwards compatible here, we'll have to do some crazy stuff, like overload the form session with the meta data saved on the pending site.

```php
apply_filters("mucd_string_to_replace")
```

Location: inc/managers/class-site-manager.php:483

---
### wp_ultimo_load

Triggers when all the dependencies were loaded

Allows plugin developers to add new functionality. For example, support to new Hosting providers, etc.

Added in 2.0.0

```php
do_action("wp_ultimo_load")
```

Location: inc/class-wp-ultimo.php:231

#### Arguments
*None.*

---
### wp_ultimo_admin_pages

Runs a number of checks and instructs users coming from the previous version about what steps they need to take to finish the upgrade to version 2.

 Links to the installer, if version 2 was not properly activated; Unloads incompatible add-ons, offering explanations when available; Re-adds the updater for add-ons that have new versions available. 

Added in 2.0.5

```php
do_action("wp_ultimo_admin_pages")
```

Location: inc/class-wp-ultimo.php:743

#### Arguments
*None.*

---
### wu_admin_notices

Allow developers to filter admin notices added by WP Ultimo.

Added in 2.0.0

```php
apply_filters("wu_admin_notices", array $notices, array $all_notices, string $panel, string $filter, array $dismissed_messages)
```

Location: inc/class-admin-notices.php:132

#### Arguments
* `$notices` (_array_) List of notices for that particular panel.
* `$all_notices` (_array_) List of notices added, segregated by panel.
* `$panel` (_string_) Panel to retrieve the notices.
* `$filter` (_string_) If the dismissable notices have been filtered out.
* `$dismissed_messages` (_array_) List of dismissed notice keys.

#### Expected Return
(_array_) No description provided.

---
### wu_page_rollback_after_title

Allow plugin developers to add

Added in 1.8.2

```php
do_action("wu_page_rollback_after_title")
```

Location: views/rollback/rollback.php:49

#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wu_page_wizard_after_title

Allow plugin developers to add additional buttons to list pages

Added in 1.8.2

```php
do_action("wu_page_wizard_after_title")
```

Location: views/base/settings.php:49

#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wu_page_wizard_footer

Allow plugin developers to add scripts to the bottom of the page

Added in 1.8.2

```php
do_action("wu_page_wizard_footer")
```

Location: views/base/settings.php:297

#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wu_page_edit_after_title

Allow plugin developers to add additional buttons to edit pages

Added in 1.8.2

```php
do_action("wu_page_edit_after_title")
```

Location: views/base/edit.php:52

#### Arguments
* `` (_object_) Object holding the information
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wu_page_edit_redirect_handlers

Allow plugin developers to add additional handlers to URL query redirects

Added in 2.0.0

```php
do_action("wu_page_edit_redirect_handlers", \WP_Ultimo\Admin_Pages\Base_Admin_Page $page)
```

Location: views/base/edit.php:81

#### Arguments
* `$page` (_\WP_Ultimo\Admin_Pages\Base_Admin_Page_) The page object.

---
### wu_edit_page_after_title_input

Allow plugin developers to add additional information below the text input

Added in 1.8.2

```php
do_action("wu_edit_page_after_title_input")
```

Location: views/base/edit.php:118

#### Arguments
* `` (_object_) Object holding the information
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wu_edit_{$screen->id}_after_normal

Allow developers to add additional elements after the modals are printed.

Added in 2.0.0

```php
do_action("wu_edit_{$screen->id}_after_normal")
```

Location: views/base/edit.php:194

#### Arguments
* `` (_object_) Object being edited right now

---
### wu_page_edit_footer

Allow plugin developers to add scripts to the bottom of the page

Added in 1.8.2

```php
do_action("wu_page_edit_footer")
```

Location: views/base/edit.php:246

#### Arguments
* `` (_object_) Object holding the information
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wu_page_addon_after_title

Allow plugin developers to add additional buttons to list pages

Added in 1.8.2

```php
do_action("wu_page_addon_after_title")
```

Location: views/base/addons.php:56

#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wu_page_addon_footer

Allow plugin developers to add scripts to the bottom of the page

Added in 1.8.2

```php
do_action("wu_page_addon_footer")
```

Location: views/base/addons.php:370

#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wu_page_centered_after_title

Allow plugin developers to add additional buttons to list pages

Added in 1.8.2

```php
do_action("wu_page_centered_after_title")
```

Location: views/base/centered.php:51

#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wu_centered_before_metaboxes

You can filter the get_title_link using wu_page_list_get_title_link, see class-wu-page-list.php

Added in 1.8.2

```php
do_action("wu_centered_before_metaboxes")
```

Location: views/base/centered.php:66

#### Arguments
*None.*

---
### wu_dashboard_display_widgets

*No description provided.*

```php
apply_filters("wu_dashboard_display_widgets")
```

Location: views/base/centered.php:68

---
### wu_centered_content

Allow plugin developers to add additional buttons to list pages

Added in 1.8.2

```php
do_action("wu_centered_content")
```

Location: views/base/centered.php:148

#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wu_centered_right

Allow plugin developers to add additional buttons to list pages

Added in 1.8.2

```php
do_action("wu_centered_right")
```

Location: views/base/centered.php:165

#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wu_page_wizard_after_title

Allow plugin developers to add additional buttons to list pages

Added in 1.8.2

```php
do_action("wu_page_wizard_after_title")
```

Location: views/base/wizard.php:53

#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wu_page_wizard_footer

Allow plugin developers to add scripts to the bottom of the page

Added in 1.8.2

```php
do_action("wu_page_wizard_footer")
```

Location: views/base/wizard.php:167

#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wu_page_list_after_title

Allow plugin developers to add additional buttons to list pages

Added in 1.8.2

```php
do_action("wu_page_list_after_title")
```

Location: views/base/list.php:49

#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wu_page_list_redirect_handlers

Allow plugin developers to add additional handlers to URL query redirects

Added in 2.0.0

```php
do_action("wu_page_list_redirect_handlers", \WP_Ultimo\Admin_Pages\Base_Admin_Page $page)
```

Location: views/base/list.php:68

#### Arguments
* `$page` (_\WP_Ultimo\Admin_Pages\Base_Admin_Page_) The page object.

---
### wu_page_list_footer

Allow plugin developers to add scripts to the bottom of the page

Added in 1.8.2

```php
do_action("wu_page_list_footer")
```

Location: views/base/list.php:114

#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wu_page_dash_after_title

Allow plugin developers to add additional buttons to list pages

Added in 1.8.2

```php
do_action("wu_page_dash_after_title")
```

Location: views/base/dash.php:49

#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wu_dash_before_metaboxes

You can filter the get_title_link using wu_page_list_get_title_link, see class-wu-page-list.php

Added in 1.8.2

```php
do_action("wu_dash_before_metaboxes")
```

Location: views/base/dash.php:56

#### Arguments
*None.*

---
### wu_dashboard_display_widgets

*No description provided.*

```php
apply_filters("wu_dashboard_display_widgets")
```

Location: views/base/dash.php:58

---
### wu_dash_after_full_metaboxes

Print Advanced Metaboxes

Allow plugin developers to add new metaboxes

Added in 1.8.2

```php
do_action("wu_dash_after_full_metaboxes")
```

Location: views/base/dash.php:82

#### Arguments
* `` (_object_) Object being edited right now

---
### wu_footer_left

*No description provided.*

```php
do_action("wu_footer_left")
```

Location: views/ui/branding/footer.php:58

---
### wu_header_left

Allow plugin developers to add more elements on left header container.

Added in 2.0.0

```php
do_action("wu_header_left", \WP_Ultimo\Admin_Pages\Base_Admin_Page $page)
```

Location: views/ui/branding/header.php:29

#### Arguments
* `$page` (_\WP_Ultimo\Admin_Pages\Base_Admin_Page_) WP Ultimo admin page instance.

---
### wu_header_right

Allow plugin developers to add more elements on right header container.

Added in 2.0.0

```php
do_action("wu_header_right", \WP_Ultimo\Admin_Pages\Base_Admin_Page $page)
```

Location: views/ui/branding/header.php:54

#### Arguments
* `$page` (_\WP_Ultimo\Admin_Pages\Base_Admin_Page_) WP Ultimo admin page instance.

---
### wu_jumper_options

Allow plugin developers to add new opt-groups.

Added in 2.0.0

```php
do_action("wu_jumper_options")
```

Location: views/ui/jumper.php:84

#### Arguments
*None.*

---
### wu_selectize_templates

Allow plugin developers to add more selectize templates.

Added in 2.0.0

```php
do_action("wu_selectize_templates")
```

Location: views/ui/selectize-templates.php:342

#### Arguments
*None.*

---
### wu_tax_rates_screen_additional_actions

Let developers print additional buttons to this screen Our very on EU VAT functions hook on this to display our VAT helper button

Added in 2.0.0

```php
do_action("wu_tax_rates_screen_additional_actions")
```

Location: views/taxes/list.php:282

#### Arguments
*None.*

---
### wu_checkout_errors

Display possible errors with the checkout.

```php
do_action("wu_checkout_errors")
```

Location: views/checkout/form.php:20

---
### wu_checkout_{$checkout_form_name}_after_form

Renders additional things after the form ios over.

```php
do_action("wu_checkout_{$checkout_form_name}_after_form")
```

Location: views/checkout/form.php:67

---
### wu_checkout_after_form

Allow to add after our checkout form.

```php
do_action("wu_checkout_after_form")
```

Location: views/checkout/form.php:72

---
### wu_checkout_gateway_fields

Load Gateway fields

Added in 2.0.0

```php
do_action("wu_checkout_gateway_fields")
```

Location: views/checkout/fields/field-payment-methods.php:75

#### Arguments
*None.*

---
### wu_featured_plan_label

Featured tag.

```php
apply_filters("wu_featured_plan_label")
```

Location: views/checkout/templates/pricing-table/legacy.php:116

---
### wu_plan_contact_us_price_line

Case Free

```php
apply_filters("wu_plan_contact_us_price_line")
```

Location: views/checkout/templates/pricing-table/legacy.php:164

---
### wu_step_template_display_header

Allow developers to hide the title.

```php
apply_filters("wu_step_template_display_header")
```

Location: views/checkout/templates/template-selection/legacy.php:54

---
### wu_edit_placeholders_screen_additional_actions

Let developers print additional buttons to this screen Our very on EU VAT functions hook on this to display our VAT helper button

Added in 2.0.0

```php
do_action("wu_edit_placeholders_screen_additional_actions")
```

Location: views/sites/edit-placeholders.php:223

#### Arguments
*None.*

---
### wu_thank_you_before_info_blocks

*No description provided.*

```php
do_action("wu_thank_you_before_info_blocks")
```

Location: views/dashboard-widgets/thank-you.php:218

---
### wu_thank_you_site_block

*No description provided.*

```php
do_action("wu_thank_you_site_block")
```

Location: views/dashboard-widgets/thank-you.php:242

