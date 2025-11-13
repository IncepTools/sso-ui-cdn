# IncepTools SSO UI CDN

This repository hosts the **public CDN assets** for the **IncepTools SSO OAuth UI**.

## 📦 Usage (via jsDelivr)

- **Latest release**
  ```html
  <script src="https://cdn.jsdelivr.net/gh/IncepTools/sso-ui-cdn/latest/app.js"></script>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/IncepTools/sso-ui-cdn/latest/app.css">
  ```

* **Specific version**

  ```html
  <script type="module" crossorigin src="https://cdn.jsdelivr.net/gh/IncepTools/sso-ui-cdn/v1.0.0/app.js"></script>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/IncepTools/sso-ui-cdn/v1.0.0/app.css">
  ```

## 🔄 Versioning

Each tagged release from the **private admin panel repo** publishes:

* `/{version}/` folder (e.g., `1.0.0/`)
* `/latest/` folder (always points to newest release)

## 🚫 Source Code

This repo **does not contain source code**.
It is **only for CDN delivery** of compiled assets.
