### wp_ultimo_vat_activation

Let other parts of the plugin attach their routines for activation

Added in 1.9.6

```php
do_action("wp_ultimo_vat_activation")
```

Location: inc/class-hooks.php:86

#### Arguments
*None.*

#### Expected Return
(_void_) No description provided.

---
### wp_ultimo_vat_deactivation

Let other parts of the plugin attach their routines for deactivation

Added in 1.9.6

```php
do_action("wp_ultimo_vat_deactivation")
```

Location: inc/class-hooks.php:106

#### Arguments
*None.*

#### Expected Return
(_void_) No description provided.

---
### wu_eu_vat_enable

*No description provided.*

```php
apply_filters("wu_eu_vat_enable")
```

Location: inc/tax/class-eu-vat.php:70

---
### wu_get_eu_vat_tax_rates

Loop the results and return the array with contents

```php
apply_filters("wu_get_eu_vat_tax_rates")
```

Location: inc/tax/class-eu-vat.php:430

---
### wu_get_eu_vat_country_prefixes

*No description provided.*

```php
apply_filters("wu_get_eu_vat_country_prefixes")
```

Location: inc/tax/class-eu-vat.php:657

---
### wu_eu_country_codes

*No description provided.*

```php
apply_filters("wu_eu_country_codes")
```

Location: inc/tax/class-eu-vat.php:843

---
### wp_ultimo_vat_load

Triggers when all the dependencies were loaded

Allows plugin developers to add new functionality. For example, support to new Hosting providers, etc.

Added in 1.0.0

```php
do_action("wp_ultimo_vat_load")
```

Location: inc/class-wp-ultimo-vat.php:96

#### Arguments
*None.*

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
### wp_ultimo_vat_url

*No description provided.*

```php
apply_filters("wp_ultimo_vat_url")
```

Location: inc/class-helper.php:46

