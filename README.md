# Osclass Advanced CAPTCHA plugin

![Advanced CAPTCHA Cover Image](https://placehold.it/1024x768?text=Advanced%20CAPTCHA)

### OVERVIEW
Various CAPTCHA types: reCAPTCHA V3, math, text and Q&A CAPTCHA.
Login, register, forgotten password, contact, post item, edit item and add comment forms.
reCAPTCHA V3 is fully invisible.
Requires small theme mods in some cases. Described in admin settings page.

### INSTALLATION
Two options:
- a) Download zip from GitHub - click on releases tab - download latest zip - import in oc-admin.
- b) TO BE DUE Download zip from Market - https://market.osclasscommunity.com/index.php?page=item&id= - import in oc-admin.

### THEME MODS
Login form:
- a) Open user-login.php in _oc-content/themes/your_theme_ and
- b) add `<?php osc_run_hook('advcaptcha_hook_login'); ?>` where you want the CAPTCHA to be shown (somewhere above the `</form>` tag)

Forgotten password form:
- a) Open user-recover.php in _oc-content/themes/your_theme_ and
- b) add `<?php osc_run_hook('advcaptcha_hook_recover'); ?>` where you want the CAPTCHA to be shown (somewhere above the `</form>` tag)

Add item form:
- a) Open item-post.php in _oc-content/themes/your_theme_ and
- b) add `<?php osc_run_hook('advcaptcha_hook_item'); ?>` where you want the CAPTCHA to be shown (somewhere above the `</form>` tag)

Edit item form:
- a) Open item-post.php in _oc-content/themes/your_theme_ and
- b) add `<?php osc_run_hook('advcaptcha_hook_item'); ?>` where you want the CAPTCHA to be shown (somewhere above the `</form>` tag)

Add comment form:
- a) Open item.php/item-sidebar.php in _oc-content/themes/your_theme_ and
- b) add `<?php osc_run_hook('advcaptcha_hook_comment'); ?>` where you want the CAPTCHA to be shown (somewhere above the `</form>` tag)

### TRANSLATION
.pot translation template is provided. Translate using POedit or similar software.

### CHANGELOG
- [1.0.0] 16/02/2020 - Initial stable release.

### SCREENSHOTS
TO BE DUE ![Some page](https://placehold.it/1024x768?text=Some%20photo)
