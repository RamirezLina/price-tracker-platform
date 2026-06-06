Create the "Gestión de Productos" page for DermoPrice.

Important:

DermoPrice is a consumer-facing dermocosmetic price monitoring platform.

This page is not an admin dashboard.

It is a workspace where users manage the products they want to monitor.

Use clear business language.

Do not expose technical concepts such as:

* StoreProduct
* Database entities
* Backend fields
* IDs
* Status codes

Layout:

Use the same application shell as the Products page:

* Header with logo, category selector, and user profile
* Left sidebar with:

  * Productos
  * Gestión de productos

The page contains three tabs:

1. Scrapear
2. Asociar
3. Añadir

---

TAB: SCRAPEAR

Purpose:
Allow users to manually update product prices.

Include:

* Update All Products button

Filters:

* Store selector
* Product selector

Users can:

* Update all products
* Update all products from a store
* Update a specific product
* Update a specific product from a specific store

Display:

* Last execution date
* Number of products updated
* Execution status

Use friendly language such as:
"Actualizar precios"

---

TAB: ASOCIAR A MIS PRODUCTOS

Purpose:
Allow users to associate products and stores to their account.

Step 1:
Search and select a product.

Step 2:
Search and select a store.

Validation:

If the association already exists:
Show:
"This product is already available in this store."

Button:
"Agregar a mis productos"

If the association does not exist:
Ask for:

* Product URL inside the selected store

Button:
"Crear asociación"

Design the workflow as a guided experience.

---

TAB: AÑADIR

Purpose:
Allow users to request new stores or create new products.

Section A:
Add Store

Fields:

* Store Name
* Main Website URL

Button:
"Solicitar tienda"

Section B:
Add Product

Fields:

* Product Name
* Brand
* Category
* Volume
* Description

Button:
"Crear producto"

Do not expose technical fields.

---

Design Style:

* Clean
* Minimal
* Professional
* Dermatology inspired
* Friendly
* Consumer-oriented

The page should feel like a product monitoring tool rather than a management console.

Focus on simplicity and usability.
