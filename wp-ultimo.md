### wu_jumper_options
Allow plugin developers to add new opt-groups.
```php
do_action("wu_jumper_options")
```

Location: views/ui/jumper.php:84
#### Arguments
### wu_header_left
Allow plugin developers to add more elements on left header container.
```php
do_action("wu_header_left", \WP_Ultimo\Admin_Pages\Base_Admin_Page $page)
```

Location: views/ui/branding/header.php:29
#### Arguments
* `$page` (_\WP_Ultimo\Admin_Pages\Base_Admin_Page_) WP Ultimo admin page instance.
### wu_header_right
Allow plugin developers to add more elements on right header container.
```php
do_action("wu_header_right", \WP_Ultimo\Admin_Pages\Base_Admin_Page $page)
```

Location: views/ui/branding/header.php:54
#### Arguments
* `$page` (_\WP_Ultimo\Admin_Pages\Base_Admin_Page_) WP Ultimo admin page instance.
### wu_footer_left

```php
do_action("wu_footer_left")
```

Location: views/ui/branding/footer.php:58
### wu_selectize_templates
Allow plugin developers to add more selectize templates.
```php
do_action("wu_selectize_templates")
```

Location: views/ui/selectize-templates.php:342
#### Arguments
### wp_ultimo_registration_step_{$signup->step}
Prints each of our fields using a helper function
```php
do_action("wp_ultimo_registration_step_{$signup->step}")
```

Location: views/legacy/signup/steps/step-default.php:45
### wu_signup_form_nav_links
Get Navigational Links
```php
apply_filters("wu_signup_form_nav_links")
```

Location: views/legacy/signup/signup-nav-links.php:30
#### Arguments
### wu_pricing_table_plan
Set plan attributes
```php
apply_filters("wu_pricing_table_plan")
```

Location: views/legacy/signup/pricing-table/plan.php:39
#### Arguments
### wu_featured_plan_label

```php
apply_filters("wu_featured_plan_label")
```

Location: views/legacy/signup/pricing-table/plan.php:47
### wu_plan_contact_us_price_line

```php
apply_filters("wu_plan_contact_us_price_line")
```

Location: views/legacy/signup/pricing-table/plan.php:63
### wu_plan_select_button_attributes
Loop and Displays Pricing Table Lines
```php
apply_filters("wu_plan_select_button_attributes")
```

Location: views/legacy/signup/pricing-table/plan.php:115
### wu_plan_select_button_label

```php
apply_filters("wu_plan_select_button_label")
```

Location: views/legacy/signup/pricing-table/plan.php:117
### wu_checkout_scripts

```php
do_action("wu_checkout_scripts")
```

Location: views/legacy/signup/signup-main.php:21
### wu_signup_page_title

```php
apply_filters("wu_signup_page_title")
```

Location: views/legacy/signup/signup-main.php:32
### signup_header

```php
do_action("signup_header")
```

Location: views/legacy/signup/signup-main.php:36
### login_enqueue_scripts

```php
do_action("login_enqueue_scripts")
```

Location: views/legacy/signup/signup-main.php:37
### wu_signup_enqueue_scripts

```php
do_action("wu_signup_enqueue_scripts")
```

Location: views/legacy/signup/signup-main.php:38
### admin_print_scripts

```php
do_action("admin_print_scripts")
```

Location: views/legacy/signup/signup-main.php:39
### admin_print_styles

```php
do_action("admin_print_styles")
```

Location: views/legacy/signup/signup-main.php:40
### admin_print_footer_scripts
We also need to print the footer admin scripts, to make sure we are enqueing some of the scripts dependencies our scripts need in order to function properly
```php
do_action("admin_print_footer_scripts")
```

Location: views/legacy/signup/signup-main.php:49
### wu_signup_header
Fires right after the start body tag is printed
```php
do_action("wu_signup_header")
```

Location: views/legacy/signup/signup-main.php:71
#### Arguments
### wu_before_signup_form
Fires before the site sign-up form.
```php
do_action("wu_before_signup_form")
```

Location: views/legacy/signup/signup-main.php:87
### wu_after_signup_form
Fires after the sign-up forms, before signup-footer
```php
do_action("wu_after_signup_form")
```

Location: views/legacy/signup/signup-main.php:106
### wu_signup_footer
Fires right after the start body tag is printed
```php
do_action("wu_signup_footer")
```

Location: views/legacy/signup/signup-main.php:132
#### Arguments
### wu_checkout_gateway_fields
Load Gateway fields
```php
do_action("wu_checkout_gateway_fields")
```

Location: views/checkout/fields/field-payment-methods.php:75
#### Arguments
### wu_step_template_display_header
Allow developers to hide the title.
```php
apply_filters("wu_step_template_display_header")
```

Location: views/checkout/templates/template-selection/legacy.php:54
### wu_featured_plan_label
Featured tag.
```php
apply_filters("wu_featured_plan_label")
```

Location: views/checkout/templates/pricing-table/legacy.php:116
### wu_plan_contact_us_price_line
Case Free
```php
apply_filters("wu_plan_contact_us_price_line")
```

Location: views/checkout/templates/pricing-table/legacy.php:164
### wu_checkout_errors
Display possible errors with the checkout.
```php
do_action("wu_checkout_errors")
```

Location: views/checkout/form.php:20
### wu_checkout_{$checkout_form_name}_after_form
Renders additional things after the form ios over.
```php
do_action("wu_checkout_{$checkout_form_name}_after_form")
```

Location: views/checkout/form.php:67
### wu_checkout_after_form
Allow to add after our checkout form.
```php
do_action("wu_checkout_after_form")
```

Location: views/checkout/form.php:72
### wu_page_rollback_after_title
Allow plugin developers to add
```php
do_action("wu_page_rollback_after_title")
```

Location: views/rollback/rollback.php:49
#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance
### wu_tax_rates_screen_additional_actions
Let developers print additional buttons to this screen Our very on EU VAT functions hook on this to display our VAT helper button
```php
do_action("wu_tax_rates_screen_additional_actions")
```

Location: views/taxes/list.php:282
#### Arguments
### wu_edit_placeholders_screen_additional_actions
Let developers print additional buttons to this screen Our very on EU VAT functions hook on this to display our VAT helper button
```php
do_action("wu_edit_placeholders_screen_additional_actions")
```

Location: views/sites/edit-placeholders.php:223
#### Arguments
### wu_thank_you_before_info_blocks

```php
do_action("wu_thank_you_before_info_blocks")
```

Location: views/dashboard-widgets/thank-you.php:218
### wu_thank_you_site_block

```php
do_action("wu_thank_you_site_block")
```

Location: views/dashboard-widgets/thank-you.php:242
### wu_page_wizard_after_title
Allow plugin developers to add additional buttons to list pages
```php
do_action("wu_page_wizard_after_title")
```

Location: views/base/wizard.php:53
#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance
### wu_page_wizard_footer
Allow plugin developers to add scripts to the bottom of the page
```php
do_action("wu_page_wizard_footer")
```

Location: views/base/wizard.php:167
#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance
### wu_page_centered_after_title
Allow plugin developers to add additional buttons to list pages
```php
do_action("wu_page_centered_after_title")
```

Location: views/base/centered.php:51
#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance
### wu_centered_before_metaboxes
You can filter the get_title_link using wu_page_list_get_title_link, see class-wu-page-list.php
```php
do_action("wu_centered_before_metaboxes")
```

Location: views/base/centered.php:66
#### Arguments
### wu_dashboard_display_widgets

```php
apply_filters("wu_dashboard_display_widgets")
```

Location: views/base/centered.php:68
### wu_centered_content
Allow plugin developers to add additional buttons to list pages
```php
do_action("wu_centered_content")
```

Location: views/base/centered.php:148
#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance
### wu_centered_right
Allow plugin developers to add additional buttons to list pages
```php
do_action("wu_centered_right")
```

Location: views/base/centered.php:165
#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance
### wu_page_addon_after_title
Allow plugin developers to add additional buttons to list pages
```php
do_action("wu_page_addon_after_title")
```

Location: views/base/addons.php:56
#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance
### wu_page_addon_footer
Allow plugin developers to add scripts to the bottom of the page
```php
do_action("wu_page_addon_footer")
```

Location: views/base/addons.php:370
#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance
### wu_page_dash_after_title
Allow plugin developers to add additional buttons to list pages
```php
do_action("wu_page_dash_after_title")
```

Location: views/base/dash.php:49
#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance
### wu_dash_before_metaboxes
You can filter the get_title_link using wu_page_list_get_title_link, see class-wu-page-list.php
```php
do_action("wu_dash_before_metaboxes")
```

Location: views/base/dash.php:56
#### Arguments
### wu_dashboard_display_widgets

```php
apply_filters("wu_dashboard_display_widgets")
```

Location: views/base/dash.php:58
### wu_dash_after_full_metaboxes
Print Advanced Metaboxes
```php
do_action("wu_dash_after_full_metaboxes")
```

Location: views/base/dash.php:82
#### Arguments
* `` (_object_) Object being edited right now
### wu_page_wizard_after_title
Allow plugin developers to add additional buttons to list pages
```php
do_action("wu_page_wizard_after_title")
```

Location: views/base/settings.php:49
#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance
### wu_page_wizard_footer
Allow plugin developers to add scripts to the bottom of the page
```php
do_action("wu_page_wizard_footer")
```

Location: views/base/settings.php:297
#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance
### wu_page_list_after_title
Allow plugin developers to add additional buttons to list pages
```php
do_action("wu_page_list_after_title")
```

Location: views/base/list.php:49
#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance
### wu_page_list_redirect_handlers
Allow plugin developers to add additional handlers to URL query redirects
```php
do_action("wu_page_list_redirect_handlers", \WP_Ultimo\Admin_Pages\Base_Admin_Page $page)
```

Location: views/base/list.php:68
#### Arguments
* `$page` (_\WP_Ultimo\Admin_Pages\Base_Admin_Page_) The page object.
### wu_page_list_footer
Allow plugin developers to add scripts to the bottom of the page
```php
do_action("wu_page_list_footer")
```

Location: views/base/list.php:114
#### Arguments
* `` (_\WU_Page_) WP Ultimo Page instance
### wu_page_edit_after_title
Allow plugin developers to add additional buttons to edit pages
```php
do_action("wu_page_edit_after_title")
```

Location: views/base/edit.php:52
#### Arguments
* `` (_object_) Object holding the information
* `` (_\WU_Page_) WP Ultimo Page instance
### wu_page_edit_redirect_handlers
Allow plugin developers to add additional handlers to URL query redirects
```php
do_action("wu_page_edit_redirect_handlers", \WP_Ultimo\Admin_Pages\Base_Admin_Page $page)
```

Location: views/base/edit.php:81
#### Arguments
* `$page` (_\WP_Ultimo\Admin_Pages\Base_Admin_Page_) The page object.
### wu_edit_page_after_title_input
Allow plugin developers to add additional information below the text input
```php
do_action("wu_edit_page_after_title_input")
```

Location: views/base/edit.php:118
#### Arguments
* `` (_object_) Object holding the information
* `` (_\WU_Page_) WP Ultimo Page instance
### wu_edit_{$screen->id}_after_normal
Allow developers to add additional elements after the modals are printed.
```php
do_action("wu_edit_{$screen->id}_after_normal")
```

Location: views/base/edit.php:194
#### Arguments
* `` (_object_) Object being edited right now
### wu_page_edit_footer
Allow plugin developers to add scripts to the bottom of the page
```php
do_action("wu_page_edit_footer")
```

Location: views/base/edit.php:246
#### Arguments
* `` (_object_) Object holding the information
* `` (_\WU_Page_) WP Ultimo Page instance
