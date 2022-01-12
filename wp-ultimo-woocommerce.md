### wp_ultimo_woocommerce_load

Triggers after all the add-on dependencies were loaded.

Allows plugin developers to add new functionality.

Added in 2.0.0

```php
do_action("wp_ultimo_woocommerce_load")
```

Location: inc/class-wp-ultimo-woocommerce.php:90

#### Arguments
*None.*

---
### wp_ultimo_woocommerce_checkout_fields_to_clean

Allows developers to filter default WooCommerce billing address fields.

Since WP Ultimo has billing address fields, it might make sense to remove the default fields displayed by WooCommerce on the checkout form. By default, no value is passed to this list, so all fields configured on WooCommerce to be displayed are kept.

Added in 2.0.0

```php
apply_filters("wp_ultimo_woocommerce_checkout_fields_to_clean")
```

Location: inc/gateways/class-woocommerce-gateway.php:193

#### Arguments
*None.*

#### Expected Return
(_array_) The list of fields to remove. Available values include billing_first_name, billing_last_name, billing_company, billing_country, billing_address_1, billing_address_2, billing_city, billing_state, billing_postcode, billing_email, and billing_phone.

---
### wp_ultimo_woocommerce_should_use_subscriptions

Allow developers to force the use of WooCommerce Subscriptions.

By default the add-on checks if (1) WooCommerce Subscriptions is present, then (2) checks the setting enabling WooCommerce Subscriptions usage.

More Info: [wuc_is_woocommerce_subscriptions_active()]("inc/functions/woo.php")

```php
apply_filters("wp_ultimo_woocommerce_should_use_subscriptions", bool $enable_woocommerce_subscription_integration, \WP_Ultimo_WooCommerce\Gateways\WooCommerce_Gateway $woo_gateway)
```

Location: inc/gateways/class-woocommerce-gateway.php:290

#### Arguments
* `$enable_woocommerce_subscription_integration` (_bool_) If we currently need to use Woo Subs.
* `$woo_gateway` (_\WP_Ultimo_WooCommerce\Gateways\WooCommerce_Gateway_) The current object.

#### Expected Return
(_bool_) true to use WooCommerce Subs, false to not use it.

---
### wu_woocommerce_line_item_params

Filter the parameters used to create the line items on the WooCommerce Cart, before redirecting the customer to the WooCommerce checkout.

Added in 2.0.0

```php
apply_filters("wu_woocommerce_line_item_params", array $line_item_params, \WP_Ultimo\Checkout\Line_Item $wu_line_item, \WC_Product $wc_product)
```

Location: inc/gateways/class-woocommerce-gateway.php:436

#### Arguments
* `$line_item_params` (_array_) The cart line item parameters.
* `$wu_line_item` (_\WP_Ultimo\Checkout\Line_Item_) The WP Ultimo line item instance.
* `$wc_product` (_\WC_Product_) The WooCommerce product.

#### Expected Return
(_array_) The modified line item parameters.

---
### wp_ultimo_skip_network_active_check

Allow for developers to short-circuit the network activation check.

This is useful when using composer-based and other custom setups, such as Bedrock, for example, where using plugins as mu-plugins are the norm.

Added in 2.0.0

```php
apply_filters("wp_ultimo_skip_network_active_check", bool $skip_network_activation_check)
```

Location: inc/class-requirements.php:302

#### Arguments
* `$skip_network_activation_check` (_bool_) If we should skip the check or not, defaults to false.

#### Expected Return
(_bool_) true if you wish to skip the check, false otherwise.

---
### wp_ultimo_woocommerce_activation

Let other parts of the plugin attach their routines for activation.

Added in 1.9.6

```php
do_action("wp_ultimo_woocommerce_activation")
```

Location: inc/class-hooks.php:84

#### Arguments
*None.*

---
### wp_ultimo_woocommerce_deactivation

Let other parts of the plugin attach their routines for deactivation.

Added in 1.9.6

```php
do_action("wp_ultimo_woocommerce_deactivation")
```

Location: inc/class-hooks.php:103

#### Arguments
*None.*

