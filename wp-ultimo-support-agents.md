### wp_ultimo_support_agents_activation

Let other parts of the plugin attach their routines for activation

Added in 1.9.6

```php
do_action("wp_ultimo_support_agents_activation")
```

Location: inc/class-hooks.php:85

#### Arguments
*None.*

#### Expected Return
(_void_) No description provided.

---
### wp_ultimo_support_agents_deactivation

Let other parts of the plugin attach their routines for deactivation

Added in 1.9.6

```php
do_action("wp_ultimo_support_agents_deactivation")
```

Location: inc/class-hooks.php:105

#### Arguments
*None.*

#### Expected Return
(_void_) No description provided.

---
### wp_ultimo_support_agents_registered_capabilities

*No description provided.*

```php
apply_filters("wp_ultimo_support_agents_registered_capabilities")
```

Location: inc/class-permission-control.php:562

---
### wp_ultimo_support_agents_registered_default_wordpress_capabilities

*No description provided.*

```php
apply_filters("wp_ultimo_support_agents_registered_default_wordpress_capabilities")
```

Location: inc/class-permission-control.php:918

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
### wp_ultimo_support_agents_load

Triggers when all the dependencies were loaded

Allows plugin developers to add new functionality. For example, support to new Hosting providers, etc.

Added in 1.0.0

```php
do_action("wp_ultimo_support_agents_load")
```

Location: inc/class-wp-ultimo-support-agents.php:111

#### Arguments
*None.*

---
### wu_support_agents_url

*No description provided.*

```php
apply_filters("wu_support_agents_url")
```

Location: inc/class-helper.php:70

---
### wp_ultimo_support_agents_view_override

Only allow templating for emails and signup for now

```php
apply_filters("wp_ultimo_support_agents_view_override")
```

Location: inc/class-helper.php:118

---
### wp_ultimo_support_agents_get_option

*No description provided.*

```php
apply_filters("wp_ultimo_support_agents_get_option")
```

Location: inc/class-helper.php:232

