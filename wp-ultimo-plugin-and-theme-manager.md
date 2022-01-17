### wp_ultimo_plugin_and_theme_manager_load

Triggers when all the dependencies were loaded

Allows plugin developers to add new functionality. For example, support to new Hosting providers, etc.

Added in 1.0.0

```php
do_action("wp_ultimo_plugin_and_theme_manager_load")
```

Location: inc/class-wp-ultimo-plugin-and-theme-manager.php:111

#### Arguments
*None.*

---
### wp_ultimo_plugin_and_theme_manager_activation

Let other parts of the plugin attach their routines for activation

Added in 1.9.6

```php
do_action("wp_ultimo_plugin_and_theme_manager_activation")
```

Location: inc/class-hooks.php:85

#### Arguments
*None.*

#### Expected Return
(_void_) No description provided.

---
### wp_ultimo_plugin_and_theme_manager_deactivation

Let other parts of the plugin attach their routines for deactivation

Added in 1.9.6

```php
do_action("wp_ultimo_plugin_and_theme_manager_deactivation")
```

Location: inc/class-hooks.php:105

#### Arguments
*None.*

#### Expected Return
(_void_) No description provided.

---
### all_plugins

Deregister default WordPress Themes and enqueue our own code, if necessary

```php
apply_filters("all_plugins")
```

Location: inc/managers/class-plugin-and-theme-manager.php:1053

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
### wu_extension_display_author

*No description provided.*

```php
apply_filters("wu_extension_display_author")
```

Location: inc/models/class-extension.php:355

---
### wu_extension_display_version

*No description provided.*

```php
apply_filters("wu_extension_display_version")
```

Location: inc/models/class-extension.php:388

---
### wu_extension_display_details

*No description provided.*

```php
apply_filters("wu_extension_display_details")
```

Location: inc/models/class-extension.php:421

---
### wu_extension_display_other

*No description provided.*

```php
apply_filters("wu_extension_display_other")
```

Location: inc/models/class-extension.php:454

---
### wu_extension_get_all_categories

*No description provided.*

```php
apply_filters("wu_extension_get_all_categories")
```

Location: inc/models/class-extension.php:732

---
### wp_ultimo_plugin_and_theme_manager_url

*No description provided.*

```php
apply_filters("wp_ultimo_plugin_and_theme_manager_url")
```

Location: inc/class-helper.php:70

---
### wp_ultimo_plugin_and_theme_manager_view_override

Only allow templating for emails and signup for now

```php
apply_filters("wp_ultimo_plugin_and_theme_manager_view_override")
```

Location: inc/class-helper.php:118

---
### wp_ultimo_plugin_and_theme_manager_get_option

*No description provided.*

```php
apply_filters("wp_ultimo_plugin_and_theme_manager_get_option")
```

Location: inc/class-helper.php:232

---
### wp_ultimo_ptm_page_edit_after_title

Allow plugin developers to add additional buttons to edit pages

Added in 1.8.2

```php
do_action("wp_ultimo_ptm_page_edit_after_title")
```

Location: views/base/edit.php:47

#### Arguments
* `` (_object_) Object holding the information
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wp_ultimo_ptm_edit_page_after_title_input

Allow plugin developers to add additional information below the text input

Added in 1.8.2

```php
do_action("wp_ultimo_ptm_edit_page_after_title_input")
```

Location: views/base/edit.php:94

#### Arguments
* `` (_object_) Object holding the information
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wp_ultimo_ptm_page_edit_footer

Allow plugin developers to add scripts to the bottom of the page

Added in 1.8.2

```php
do_action("wp_ultimo_ptm_page_edit_footer")
```

Location: views/base/edit.php:221

#### Arguments
* `` (_object_) Object holding the information
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wp_ultimo_ptm_page_wizard_after_title

Allow plugin developers to add aditional buttons to list pages

Added in 1.8.2

```php
do_action("wp_ultimo_ptm_page_wizard_after_title")
```

Location: views/base/settings.php:22

#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wp_ultimo_ptm_page_wizard_footer

Allow plugin developers to add scripts to the bottom of the page

Added in 1.8.2

```php
do_action("wp_ultimo_ptm_page_wizard_footer")
```

Location: views/base/settings.php:165

#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wp_ultimo_ptm_page_list_after_title

Allow plugin developers to add aditional buttons to list pages

Added in 1.8.2

```php
do_action("wp_ultimo_ptm_page_list_after_title")
```

Location: views/base/list.php:46

#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wp_ultimo_ptm_page_list_footer

Allow plugin developers to add scripts to the bottom of the page

Added in 1.8.2

```php
do_action("wp_ultimo_ptm_page_list_footer")
```

Location: views/base/list.php:100

#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wp_ultimo_ptm_page_wizard_after_title

Allow plugin developers to add aditional buttons to list pages

Added in 1.8.2

```php
do_action("wp_ultimo_ptm_page_wizard_after_title")
```

Location: views/base/wizard.php:22

#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance

---
### wp_ultimo_ptm_page_wizard_footer

Allow plugin developers to add scripts to the bottom of the page

Added in 1.8.2

```php
do_action("wp_ultimo_ptm_page_wizard_footer")
```

Location: views/base/wizard.php:139

#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance

