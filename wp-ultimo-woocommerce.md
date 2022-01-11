### wp_ultimo_woocommerce_load

Triggers when all the dependencies were loaded

Allows plugin developers to add new functionality. For example, support to new Hosting providers, etc.

Added in 2.0.0

```php
do_action("wp_ultimo_woocommerce_load")
```

Location: inc/class-wp-ultimo-woocommerce.php:91

#### Arguments
*None.*

---
### wp_ultimo_woocommerce_checkout_fields_to_clean

*No description provided.*

```php
apply_filters("wp_ultimo_woocommerce_checkout_fields_to_clean")
```

Location: inc/gateways/class-woocommerce-gateway.php:179

---
### wp_ultimo_woocommerce_should_use_subscriptions

*No description provided.*

```php
apply_filters("wp_ultimo_woocommerce_should_use_subscriptions")
```

Location: inc/gateways/class-woocommerce-gateway.php:263

---
### wu_woocommerce_line_item_params

*No description provided.*

```php
apply_filters("wu_woocommerce_line_item_params")
```

Location: inc/gateways/class-woocommerce-gateway.php:396

---
### wp_ultimo_woocommerce_activation

Let other parts of the plugin attach their routines for activation

Added in 1.9.6

```php
do_action("wp_ultimo_woocommerce_activation")
```

Location: inc/class-hooks.php:85

#### Arguments
*None.*

#### Expected Return
(_void_) No description provided.

---
### wp_ultimo_woocommerce_deactivation

Let other parts of the plugin attach their routines for deactivation

Added in 1.9.6

```php
do_action("wp_ultimo_woocommerce_deactivation")
```

Location: inc/class-hooks.php:105

#### Arguments
*None.*

#### Expected Return
(_void_) No description provided.

