# Download WP pro plugins with composer

Downloads the `pro` versions of common WP plugins from the [WPackagist](https://wpackagist.org/) repository.

## `auth.json` example

```json
{
  "http-basic": {
    "connect.advancedcustomfields.com": {
      "username": "xxx",
      "password": "xxx"
    }
  },
  "bearer": {
    "composer.admincolumns.com": "xxx"
  }
}
```

---

## Advanced Custom Fields Pro

Read & follow the instructions on the [ACF Pro](https://www.advancedcustomfields.com/resources/installing-acf-pro-with-composer/) website

---

## Admin Columns Pro + Addons

Read & follow the instructions on the [Admin Columns Pro](https://docs.admincolumns.com/article/95-installing-via-composer) website

Addons:

```json5
{
  "admin-columns/ac-addon-acf": "*",
  "admin-columns/ac-addon-woocommerce": "*",
  "admin-columns/ac-addon-buddypress": "*",
  "admin-columns/ac-addon-events-calendar": "*",
  "admin-columns/ac-addon-jetengine": "*",
  "admin-columns/ac-addon-pods": "*",
  "admin-columns/ac-addon-metabox": "*",
  "admin-columns/ac-addon-types": "*",
  "admin-columns/ac-addon-yoast-seo": "*",
  "admin-columns/ac-addon-gravityforms": "*",
}
```

---

## WP All Import / Export PRO + Addons

Download the latest All Import / Export Plugins and extentions from official [wpallimport playground](https://www.wpallimport.com/try)

Available plugins List:


```json5
[
  "wp-all-export-pro",
  "wp-all-import-pro",
  "wpae-acf-add-on",
  "wpae-gravity-forms-export-addon",
  "wpae-user-add-on-pro",
  "wpae-woocommerce-add-on",
  "wpai-acf-add-on",
  "wpai-gravity-forms-import-addon",
  "wpai-linkcloak-add-on",
  "wpai-toolset-types-addon",
  "wpai-user-add-on",
  "wpai-woocommerce-add-on"
]
```
