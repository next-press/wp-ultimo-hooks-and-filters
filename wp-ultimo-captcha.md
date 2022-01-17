### wp_ultimo_captcha_activation

Let other parts of the plugin attach their routines for activation

Added in 1.9.6

```php
do_action("wp_ultimo_captcha_activation")
```

Location: inc/class-hooks.php:85

#### Arguments
*None.*

#### Expected Return
(_void_) No description provided.

---
### wp_ultimo_captcha_deactivation

Let other parts of the plugin attach their routines for deactivation

Added in 1.9.6

```php
do_action("wp_ultimo_captcha_deactivation")
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

Location: inc/class-requirements.php:248

#### Arguments
*None.*

#### Expected Return
(_bool_) No description provided.

---
### wu_score_threshold

*No description provided.*

```php
apply_filters("wu_score_threshold")
```

Location: inc/class-security-captcha.php:155

---
### wu_score_threshold

*No description provided.*

```php
apply_filters("wu_score_threshold")
```

Location: inc/class-security-captcha.php:182

---
### wp_ultimo_captcha_manager_url

*No description provided.*

```php
apply_filters("wp_ultimo_captcha_manager_url")
```

Location: inc/class-helper.php:46

---
### wp_ultimo_captcha_load

Triggers when all the dependencies were loaded

Allows plugin developers to add new functionality. For example, support to new Hosting providers, etc.

Added in 1.0.0

```php
do_action("wp_ultimo_captcha_load")
```

Location: inc/class-wp-ultimo-captcha.php:91

#### Arguments
*None.*

