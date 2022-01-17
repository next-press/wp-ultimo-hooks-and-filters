### wp_ultimo_gocardless_activation

Let other parts of the plugin attach their routines for activation

Added in 1.9.6

```php
do_action("wp_ultimo_gocardless_activation")
```

Location: inc/class-hooks.php:85

#### Arguments
*None.*

#### Expected Return
(_void_) No description provided.

---
### wp_ultimo_gocardless_deactivation

Let other parts of the plugin attach their routines for deactivation

Added in 1.9.6

```php
do_action("wp_ultimo_gocardless_deactivation")
```

Location: inc/class-hooks.php:105

#### Arguments
*None.*

#### Expected Return
(_void_) No description provided.

---
### wp_ultimo_skip_network_active_check

Allow for developers to short-circuit this check.

This is useful when using composer-based and other custom setups, such as Bedrock, for example, where using plugins as mu-plugins are the norm.

Added in 2.0.0

```php
apply_filters("wp_ultimo_skip_network_active_check")
```

Location: inc/class-requirements.php:250

#### Arguments
*None.*

#### Expected Return
(_bool_) No description provided.

---
### wp_ultimo_gocardless_load

Triggers when all the dependencies were loaded

Allows plugin developers to add new functionality. For example, support to new Hosting providers, etc.

Added in 1.0.0

```php
do_action("wp_ultimo_gocardless_load")
```

Location: inc/class-wp-ultimo-gocardless.php:96

#### Arguments
*None.*

---
### wp_ultimo_gocardless_url

*No description provided.*

```php
apply_filters("wp_ultimo_gocardless_url")
```

Location: inc/class-helper.php:58

---
### wp_ultimo_gocardless_view_override

Only allow templating for emails and signup for now

```php
apply_filters("wp_ultimo_gocardless_view_override")
```

Location: inc/class-helper.php:106

---
### wp_ultimo_gocardless_supported_currencies

*No description provided.*

```php
apply_filters("wp_ultimo_gocardless_supported_currencies")
```

Location: inc/gateways/class-gocardless-gateway.php:234

---
### wu_gocardless_redirect_flows_params

*No description provided.*

```php
apply_filters("wu_gocardless_redirect_flows_params")
```

Location: inc/gateways/class-gocardless-gateway.php:360

---
### wp_ultimo_gocardless_create_payment_params

*No description provided.*

```php
apply_filters("wp_ultimo_gocardless_create_payment_params")
```

Location: inc/gateways/class-gocardless-gateway.php:503

---
### wp_ultimo_gocardless_create_subscription_payment_params

*No description provided.*

```php
apply_filters("wp_ultimo_gocardless_create_subscription_payment_params")
```

Location: inc/gateways/class-gocardless-gateway.php:560

