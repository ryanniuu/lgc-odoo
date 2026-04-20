- [1. Sales and Invocing](#1-sales-and-invocing)
  - [1.1. Create Order \& Invoice](#11-create-order--invoice)
    - [1.1.1. Step 1: Create and Confirm Order](#111-step-1-create-and-confirm-order)
    - [1.1.2. Step 2: Create and Confirm Invoice from Sale Order](#112-step-2-create-and-confirm-invoice-from-sale-order)
    - [1.1.3. Step 3: Print Customer Invoice](#113-step-3-print-customer-invoice)
  - [1.2. Use "Sale Package" feature](#12-use-sale-package-feature)
    - [1.2.1. Load Packages in Quotation/Order](#121-load-packages-in-quotationorder)
    - [1.2.2. Create Sale Packages (privileged user only)](#122-create-sale-packages-privileged-user-only)
    - [1.2.3. Create Package from Order (privileged user only)](#123-create-package-from-order-privileged-user-only)
  - [1.3. Modify Order Quantity](#13-modify-order-quantity)
    - [1.3.1. Increase Quantity or Add Line Items](#131-increase-quantity-or-add-line-items)
    - [1.3.2. Reduce Quantity](#132-reduce-quantity)
  - [1.4. Adjust Invoiced Amount](#14-adjust-invoiced-amount)
  - [1.5. Register Payment](#15-register-payment)
    - [1.5.1. Method 1: Trun to invoice](#151-method-1-trun-to-invoice)
    - [1.5.2. Single Invoice](#152-single-invoice)
    - [1.5.3. Multiple Invoices](#153-multiple-invoices)
    - [1.5.4. Method 2: Register Payment on sale order](#154-method-2-register-payment-on-sale-order)
  - [1.6. Refund (No delivery)](#16-refund-no-delivery)
    - [1.6.1. Method 1: Add Credit Note (Recommended for Full Refunds)](#161-method-1-add-credit-note-recommended-for-full-refunds)
    - [1.6.2. Method 2: Modify Sales Order Quantity (Recommended for Small Partial Refunds)](#162-method-2-modify-sales-order-quantity-recommended-for-small-partial-refunds)
  - [1.7. Refund And Return (Already delivered)](#17-refund-and-return-already-delivered)
  - [1.8. Cancel order (with posted invoices)](#18-cancel-order-with-posted-invoices)
  - [1.9. Order and Calendar Integration (Task Scheduling)](#19-order-and-calendar-integration-task-scheduling)
- [2. Purchase Process](#2-purchase-process)
- [3. Product Management](#3-product-management)
- [4. Inventory Management](#4-inventory-management)
- [5. Inter-company transfer](#5-inter-company-transfer)
- [6. Cash Management](#6-cash-management)
- [7. Meta-data Management](#7-meta-data-management)
  - [7.1. Vehicle Models](#71-vehicle-models)
  - [7.2. Packages](#72-packages)
  - [7.3. 3D parts](#73-3d-parts)
- [8. Reporting](#8-reporting)
  - [8.1. Sales Report](#81-sales-report)
  - [8.2. Margin Report](#82-margin-report)
  - [8.3. Inventory Report](#83-inventory-report)



# 1. Sales and Invocing


## 1.1. Create Order & Invoice
This section covers the standard workflow from initial sale to formal invoicing.

### 1.1.1. Step 1: Create and Confirm Order
+ Create a new Sales Order (SO) in the system and fill in the customer and product details.
+ Click the **"Confirm"** button to convert the quotation into a formal sales order.

<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image1.png)


### 1.1.2. Step 2: Create and Confirm Invoice from Sale Order
+ Click **"Create Invoice"** directly from the Sales Order and confirm the invoice.
+ Review the draft invoice and click **"Confirm"** to post it to the accounts.

<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image2.png)
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image3.png)
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image4.png)

### 1.1.3. Step 3: Print Customer Invoice
+ You can print the formal customer invoice document directly from the order.
+ If the quantity is changed to 0, then the products in this row will not be displayed.
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image5.png)

> **Note on Styles:**
>
> + If the invoice is fully created, the customer invoice style will include professional formatting.
> + If not created, the document will follow a basic order-style layout.
>

**Standard Invoice Style:**
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image6.png)
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image7.png)

**Un-invoiced Style:**
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image8.png)


> Note that if a product item (including "product discount" product) in your quotation/order has been "invoiced", do not change the pricing of that product anymore. This will create mis-alignments between quotation/order and total invoice amounts. Such operation is not allowed anymore.
>
> If you need to adjust final pricing, do it via adding another "price discount", or adding new product, or changing product quantity, but NOT changing product pricings.
>
---

## 1.2. Use "Sale Package" feature
### 1.2.1. Load Packages in Quotation/Order
When creating new Quotation/Order, select from Packages drop down list
![](images/packages/package-select.png)


Then the "Load Package" button should appear on the top, click it to load the product items included in the selected package
![](images/packages/package-load.png)


### 1.2.2. Create Sale Packages (privileged user only)
Administrators can create custom packages from scratch
Please reach out if you want to create one

### 1.2.3. Create Package from Order (privileged user only)
Administrators can create packages from existing orders
Please reach out if you want to create one

## 1.3. Modify Order Quantity
### 1.3.1. Increase Quantity or Add Line Items
1. Click the **"Edit"** button on the Sales Order.
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image9.png)
2. **To increase quantity**: Find the specific order line and modify the quantity.
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image10.png)
3. **To add a new product**: Click **"Add a product"** and then save.
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image11.png)

### 1.3.2. Reduce Quantity
+ If the delivery note has not been locked value, simply adjust the quantity and save.
+ If the delivery note is already locked, the system will show a warning prompt.
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image12.png)

**Steps to modify a locked delivery order:**

1. Navigate to the **Delivery Order**.
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image13.png)
2. Click **"Edit"** and modify the **"Demand"** quantity on the **Operations** page to release inventory.
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image14.png)

---

## 1.4. Adjust Invoiced Amount
Create the invoice and confirm it to adjust the final invoiced amount, then print the "Customer Invoice" from the sale order.
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image15.png)

---

## 1.5. Register Payment
### 1.5.1. Method 1: Trun to invoice
Navigate to the **Invoices** section.
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image16.png)
### 1.5.2. Single Invoice
+ Clicking on a single invoice will redirect you to that invoice; click **"Register Payment"** and fill in the information.
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image17.png)

### 1.5.3. Multiple Invoices
+ If there are multiple invoices, select the relevant ones from the list view.
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image18.png)
+ **Important**: If the customer makes one payment for multiple invoices, select **"Group Payment"**.
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image19.png)

### 1.5.4. Method 2: Register Payment on sale order
![](images/lgc_customer_invoice/image60.png)

## 1.6. Refund (No delivery)
### 1.6.1. Method 1: Add Credit Note (Recommended for Full Refunds)
+ For the invoice requiring a refund, click **"Add Credit Note"** to create a refund for the entire order.
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image20.png)
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image21.png)
+ Click **"Confirm"** for a full refund, or modify quantities/prices for partial deductions before confirming.
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image22.png)

### 1.6.2. Method 2: Modify Sales Order Quantity (Recommended for Small Partial Refunds)
+ Change the quantity of refunded products to `0` on the order page, then create an invoice.
+ If an invoice was already issued, the system will automatically generate a refund invoice.
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image23.png)
+ Registering a refund is the same as registering a payment: click **"Register Payment"** on the refund invoice.
<!-- 这是一张图片，ocr 内容为： -->
![](images/lgc_customer_invoice/image24.png)


## 1.7. Refund And Return (Already delivered)
+ Follow the steps in Chapter 5 to create a refund invoice and process the refund.
+ Locate the corresponding delivery order, click the "return" button, and validate it.

![](images/lgc_customer_invoice/image25.png)
![](images/lgc_customer_invoice/image26.png)

+ Enter the quantity of returned items and select the return location.
![](images/lgc_customer_invoice/image27.png)

After being returned to the warehouse, validate the returned allocation.
![](images/lgc_customer_invoice/image28.png)


## 1.8. Cancel order (with posted invoices)
+ Cancel Sale order
  The purpose of canceling an order is to automatically cancel the sales order.
![](images/lgc_customer_invoice/image29.png)

+ Add Credit Note from invoice and confirm
![](images/lgc_customer_invoice/image30.png)
![](images/lgc_customer_invoice/image31.png)

+ Register refund
![](images/lgc_customer_invoice/image32.png)


## 1.9. Order and Calendar Integration (Task Scheduling)
![](images/odoo-order-and-calendar-item-steps.gif)

[Back to Top](#1-sales-and-invocing)


# 2. Purchase Process

# 3. Product Management

# 4. Inventory Management

# 5. Inter-company transfer

# 6. Cash Management

# 7. Meta-data Management
## 7.1. Vehicle Models
## 7.2. Packages
## 7.3. 3D parts


# 8. Reporting
## 8.1. Sales Report
## 8.2. Margin Report
## 8.3. Inventory Report
