### wp_ultimo_affiliatewp_load

Triggers when all the dependencies were loaded

Allows plugin developers to add new functionality. For example, support to new Hosting providers, etc.

Added in 1.0.0

```php
do_action("wp_ultimo_affiliatewp_load")
```

Location: inc/class-wp-ultimo-affiliatewp.php:88

#### Arguments
*None.*

---
### affwp_recurring_calc_referral_amount

Fires when the amount of a recurring referral is calculated.

Added in 1.1.2

```php
apply_filters("affwp_recurring_calc_referral_amount", float $referral_amount, int $affiliate_id, float $amount)
```

Location: inc/class-recurring.php:76

#### Arguments
* `$referral_amount` (_float_) The referral amount.
* `$affiliate_id` (_int_) The affiliate ID.
* `$amount` (_float_) The full transaction amount.

---
### wp_ultimo_affiliatewp_activation

Let other parts of the plugin attach their routines for activation

Added in 1.9.6

```php
do_action("wp_ultimo_affiliatewp_activation")
```

Location: inc/class-hooks.php:85

#### Arguments
*None.*

#### Expected Return
(_void_) No description provided.

---
### wp_ultimo_affiliatewp_deactivation

Let other parts of the plugin attach their routines for deactivation

Added in 1.9.6

```php
do_action("wp_ultimo_affiliatewp_deactivation")
```

Location: inc/class-hooks.php:105

#### Arguments
*None.*

#### Expected Return
(_void_) No description provided.

