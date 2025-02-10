# catatan

repo ini berisi tentang berbagai kemudahan dalam pengertian kode kode dan tiap element dalam bahasa pemrograman apapun walupun baru sedikit saya berusaha agar menambahkan berbagi bahasa pemrograman lain nya


```cari inspirasi desain```    ```cari kemudahan dalam pembuatan web```  ```hal-hal yang memudahkan anda dalam seputar programing```


# Ukuran Layar Umum untuk Desain Web

Dalam desain web, ukuran layar yang sering digunakan untuk **laptop/desktop** dan **smartphone (HP)** adalah:

## 1. Laptop/Desktop
- **1366 × 768 px** → Ukuran paling umum untuk laptop standar.
- **1920 × 1080 px** → Full HD, sering digunakan di layar yang lebih besar.

## 2. Smartphone (HP)
- **375 × 667 px** → Ukuran patokan untuk banyak desain responsif (contoh: iPhone 6/7/8).
- **414 × 896 px** → Ukuran lebih besar untuk ponsel modern (contoh: iPhone XR).

## 3. Tabel Ukuran Layar Berdasarkan Perangkat

| **Kategori**       | **Perangkat Contoh**          | **Width (px)** | **Height (px)** |
|--------------------|----------------------------|---------------|---------------|
| **Extra Small (XS)** | iPhone SE (lama)            | 320px         | 568px         |
|                    | iPhone 6/7/8                 | 375px         | 667px         |
|                    | iPhone X/11 Pro              | 375px         | 812px         |
|                    | iPhone 12/13 Mini            | 360px         | 780px         |
|                    | Android Kecil (Galaxy A01)   | 360px         | 640px         |
| **Small (SM)**     | iPhone Plus Series (8+, XR)  | 414px         | 736px         |
|                    | Galaxy S20/S21/S22           | 412px         | 915px         |
|                    | Pixel 5                      | 393px         | 851px         |
| **Medium (MD)**    | iPad (portrait)              | 768px         | 1024px        |
|                    | iPad Mini (portrait)         | 768px         | 1024px        |
|                    | Samsung Tab A                | 800px         | 1280px        |
| **Large (LG)**     | iPad (landscape)             | 1024px        | 768px         |
|                    | Surface Pro (tablet mode)    | 1280px        | 800px         |
|                    | MacBook Air/Pro 13"          | 1440px        | 900px         |
| **Extra Large (XL)** | Laptop Standar 15.6"         | 1366px        | 768px         |
|                    | Monitor 1080p (Full HD)      | 1920px        | 1080px        |
|                    | Monitor 1440p (2K)          | 2560px        | 1440px        |
|                    | Monitor 4K UHD              | 3840px        | 2160px        |

## 4. Media Query CSS Berdasarkan Ukuran Layar

```css
/* Extra Small Devices (misalnya smartphone kecil) */
@media (max-width: 575.98px) {
    body {
        font-size: 14px;
    }
}

/* Small Devices (smartphone landscape) */
@media (min-width: 576px) and (max-width: 767.98px) {
    body {
        font-size: 15px;
    }
}

/* Medium Devices (tablet) */
@media (min-width: 768px) and (max-width: 991.98px) {
    body {
        font-size: 16px;
    }
}

/* Large Devices (laptop/desktop standar) */
@media (min-width: 992px) and (max-width: 1199.98px) {
    body {
        font-size: 18px;
    }
}

/* Extra Large Devices (desktop besar) */
@media (min-width: 1200px) {
    body {
        font-size: 20px;
    }
}
