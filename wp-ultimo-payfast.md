### wp_ultimo_payfast_activation

Let other parts of the plugin attach their routines for activation

Added in 1.9.6

```php
do_action("wp_ultimo_payfast_activation")
```

Location: inc/class-hooks.php:85

#### Arguments
*None.*

#### Expected Return
(_void_) No description provided.

---
### wp_ultimo_payfast_deactivation

Let other parts of the plugin attach their routines for deactivation

Added in 1.9.6

```php
do_action("wp_ultimo_payfast_deactivation")
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
### wp_ultimo_payfast_load

Triggers when all the dependencies were loaded

Allows plugin developers to add new functionality. For example, support to new Hosting providers, etc.

Added in 1.0.0

```php
do_action("wp_ultimo_payfast_load")
```

Location: inc/class-wp-ultimo-payfast.php:86

#### Arguments
*None.*

---
### wu_payfast_form_extra_parameters

*No description provided.*

```php
apply_filters("wu_payfast_form_extra_parameters")
```

Location: inc/gateways/class-payfast-gateway.php:321

---
### wu_payfast_redirect

Renew Membership and Save.

```php
apply_filters("wu_payfast_redirect")
```

Location: inc/gateways/class-payfast-gateway.php:769

---
### wu_payfast_form_before

*No description provided.*

```php
do_action("wu_payfast_form_before")
```

Location: inc/gateways/class-payfast-gateway.php:795

---
### wu_payfast_redirect_text

Redirect text

```php
apply_filters("wu_payfast_redirect_text")
```

Location: inc/gateways/class-payfast-gateway.php:804

---
### wu_payfast_form_parameters

*No description provided.*

```php
do_action("wu_payfast_form_parameters")
```

Location: inc/gateways/class-payfast-gateway.php:826

---
### wu_payfast_form_after

*No description provided.*

```php
do_action("wu_payfast_form_after")
```

Location: inc/gateways/class-payfast-gateway.php:845

