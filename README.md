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

