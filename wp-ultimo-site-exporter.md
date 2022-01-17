### wp_ultimo_site_exporter_activation

Let other parts of the plugin attach their routines for activation

Added in 1.9.6

```php
do_action("wp_ultimo_site_exporter_activation")
```

Location: inc/class-hooks.php:85

#### Arguments
*None.*

#### Expected Return
(_void_) No description provided.

---
### wp_ultimo_site_exporter_deactivation

Let other parts of the plugin attach their routines for deactivation

Added in 1.9.6

```php
do_action("wp_ultimo_site_exporter_deactivation")
```

Location: inc/class-hooks.php:105

#### Arguments
*None.*

#### Expected Return
(_void_) No description provided.

---
### wp_ultimo_site_exporter_load

Triggers when all the dependencies were loaded

Allows plugin developers to add new functionality. For example, support to new Hosting providers, etc.

Added in 1.0.0

```php
do_action("wp_ultimo_site_exporter_load")
```

Location: inc/class-wp-ultimo-site-exporter.php:111

#### Arguments
*None.*

---
### wu_site_exporter_plugin_exclusion_list

Add admin pages

```php
apply_filters("wu_site_exporter_plugin_exclusion_list")
```

Location: inc/class-wp-ultimo-site-exporter.php:154

---
### mu-migration/all_posts/default_args

Filters the default args for querying posts in the all_posts method.

Added in 0.2.0

```php
apply_filters("mu-migration/all_posts/default_args", array $default_args)
```

Location: inc/mu-migration/includes/commands/class-mu-migration-base.php:69

#### Arguments
* `$default_args` (_array_) 

---
### mu_migration/export/user/headers

*No description provided.*

```php
apply_filters("mu_migration/export/user/headers")
```

Location: inc/mu-migration/includes/commands/class-mu-migration-export.php:45

---
### mu_migration/export/user/data

Filters the default set of user data to be exported/imported.

Added in 0.1.0

```php
apply_filters("mu_migration/export/user/data", \WP_User $user)
```

Location: inc/mu-migration/includes/commands/class-mu-migration-export.php:327

#### Arguments
* `` (_array_) 
* `$user` (_\WP_User_) The user object.

---
### mu_migration/import/user/custom_data_before

Fires before exporting the custom user data.

Added in 0.1.0

```php
do_action("mu_migration/import/user/custom_data_before", array $user_data, \WP_User $user)
```

Location: inc/mu-migration/includes/commands/class-mu-migration-import.php:140

#### Arguments
* `$user_data` (_array_) The $user_data array.
* `$user` (_\WP_User_) The user object.

---
### mu_migration/export/user/data

Filters the default set of user data to be exported/imported.

Added in 0.1.0

```php
apply_filters("mu_migration/export/user/data", \WP_User $user)
```

Location: inc/mu-migration/includes/commands/class-mu-migration-import.php:150

#### Arguments
* `` (_array_) 
* `$user` (_\WP_User_) The user object.

---
### mu_migration/import/user/custom_data_after

Fires after exporting the custom user data.

Added in 0.1.0

```php
do_action("mu_migration/import/user/custom_data_after", array $user_data, \WP_User $user)
```

Location: inc/mu-migration/includes/commands/class-mu-migration-import.php:168

#### Arguments
* `$user_data` (_array_) The $user_data array.
* `$user` (_\WP_User_) The user object.

---
### retrieve_password_title

Filters the subject of the password reset email.

Added in 2.8.0

```php
apply_filters("retrieve_password_title", string $title, string $user_login, \WP_User $user_data)
```

Location: inc/mu-migration/includes/commands/class-mu-migration-users.php:135

#### Arguments
* `$title` (_string_) Default email title.
* `$user_login` (_string_) The username for the user.
* `$user_data` (_\WP_User_) WP_User object.

---
### retrieve_password_message

Filters the message body of the password reset mail.

Added in 2.8.0

```php
apply_filters("retrieve_password_message", string $message, string $key, string $user_login, \WP_User $user_data)
```

Location: inc/mu-migration/includes/commands/class-mu-migration-users.php:148

#### Arguments
* `$message` (_string_) Default mail message.
* `$key` (_string_) The activation key.
* `$user_login` (_string_) The username for the user.
* `$user_data` (_\WP_User_) WP_User object.

---
### wu_page_added

Allow plugin developers to run additional things when pages are registered.

Unlike the wu_page_load, which only runs when a specific page is being seen, this hook runs at registration for every admin page being added using WP Ultimo code.

Added in 2.0.0

```php
do_action("wu_page_added", string $this->id)
```

Location: inc/admin-pages/class-base-admin-page.php:199

#### Arguments
* `$this->id` (_string_) The ID of this page.

#### Expected Return
(_void_) No description provided.

---
### wu_page_load

Allow plugin developers to add additional hooks to our pages.

Added in 1.8.2

```php
do_action("wu_page_load", string $this->id)
```

Location: inc/admin-pages/class-base-admin-page.php:298

#### Arguments
* `$this->id` (_string_) The ID of this page.

#### Expected Return
(_void_) No description provided.

---
### wu_page_{$this->id}_load

Allow plugin developers to add additional hooks to our pages.

Added in 1.8.2

```php
do_action("wu_page_{$this->id}_load", string $this->id)
```

Location: inc/admin-pages/class-base-admin-page.php:307

#### Arguments
* `$this->id` (_string_) The ID of this page.

#### Expected Return
(_void_) No description provided.

---
### wu_page_before_render

Allow plugin developers to add additional content before we print the page.

Added in 1.8.2

```php
do_action("wu_page_before_render", string $this->id)
```

Location: inc/admin-pages/class-base-admin-page.php:362

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

Location: inc/admin-pages/class-base-admin-page.php:371

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

Location: inc/admin-pages/class-base-admin-page.php:385

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

Location: inc/admin-pages/class-base-admin-page.php:394

#### Arguments
* `$this->id` (_string_) The id of this page

#### Expected Return
(_void_) No description provided.

---
### wu_enqueue_extra_hooks

Allow plugin developers to add additional hooks

Added in 1.8.2

```php
do_action("wu_enqueue_extra_hooks")
```

Location: inc/admin-pages/class-base-admin-page.php:630

#### Arguments
* `` (_string_) 

---
### wu_page_get_title_links

Allow plugin developers, and ourselves, to add action links to our edit pages

Added in 1.8.2

```php
apply_filters("wu_page_get_title_links", \WP_Ultimo_Site_Exporter\Admin_Pages\WU_Page_Edit $this)
```

Location: inc/admin-pages/class-base-admin-page.php:667

#### Arguments
* `$this` (_\WP_Ultimo_Site_Exporter\Admin_Pages\WU_Page_Edit_) This instance

#### Expected Return
(_array_) No description provided.

---
### inpsyde.search_and_replace.error

*No description provided.*

```php
do_action("inpsyde.search_and_replace.error")
```

Location: inc/database/class-replace.php:410

---
### wp_ultimo_site_exporter_url

*No description provided.*

```php
apply_filters("wp_ultimo_site_exporter_url")
```

Location: inc/class-helper.php:46

---
### wp_ultimo_site_exporter_get_option

*No description provided.*

```php
apply_filters("wp_ultimo_site_exporter_get_option")
```

Location: inc/class-helper.php:119

