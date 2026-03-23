## 1. Create Order & Invoice
This section covers the standard workflow from initial sale to formal invoicing.

### Step 1: Create and Confirm Order
+ Create a new Sales Order (SO) in the system and fill in the customer and product details.
+ Click the **"Confirm"** button to convert the quotation into a formal sales order.

<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image1.png)


### Step 2: Create and Confirm Invoice from Sale Order
+ Click **"Create Invoice"** directly from the Sales Order and confirm the invoice.
+ Review the draft invoice and click **"Confirm"** to post it to the accounts.

<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image2.png)
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image3.png)
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image4.png)

### Step 3: Print Customer Invoice
+ You can print the formal customer invoice document directly from the order.
+ If the quantity is changed to 0, then the products in this row will not be displayed.
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image5.png)

> **Note on Styles:**
>
> + If the invoice is fully created, the customer invoice style will include professional formatting.
> + If not created, the document will follow a basic order-style layout.
>

**Standard Invoice Style:**  
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image6.png)
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image7.png)

**Un-invoiced Style:**  
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image8.png)

---

## 2. Modify Order Quantity
### 2.1 Increase Quantity or Add Line Items
1. Click the **"Edit"** button on the Sales Order.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image9.png)
2. **To increase quantity**: Find the specific order line and modify the quantity.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image10.png)
3. **To add a new product**: Click **"Add a product"** and then save.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image11.png)

### 2.2 Reduce Quantity
+ If the delivery note has not been locked value, simply adjust the quantity and save.
+ If the delivery note is already locked, the system will show a warning prompt.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image12.png)

**Steps to modify a locked delivery order:**

1. Navigate to the **Delivery Order**.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image13.png)
2. Click **"Edit"** and modify the **"Demand"** quantity on the **Operations** page to release inventory.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image14.png)

---

## 3. Adjust Invoiced Amount
Create the invoice and confirm it to adjust the final invoiced amount, then print the "Customer Invoice" from the sale order.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image15.png)

---

## 4. Register Payment
### Method 1: Trun to invoice
Navigate to the **Invoices** section.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image16.png)
### Single Invoice
+ Clicking on a single invoice will redirect you to that invoice; click **"Register Payment"** and fill in the information.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image17.png)

### Multiple Invoices
+ If there are multiple invoices, select the relevant ones from the list view.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image18.png)
+ **Important**: If the customer makes one payment for multiple invoices, select **"Group Payment"**.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image19.png)

### Method 2: Register Payment on sale order
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image60.png)

## 5. Refund (No delivery)
### Method 1: Add Credit Note (Recommended for Full Refunds)
+ For the invoice requiring a refund, click **"Add Credit Note"** to create a refund for the entire order.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image20.png)
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image21.png)
+ Click **"Confirm"** for a full refund, or modify quantities/prices for partial deductions before confirming.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image22.png)

### Method 2: Modify Sales Order Quantity (Recommended for Small Partial Refunds)
+ Change the quantity of refunded products to `0` on the order page, then create an invoice.
+ If an invoice was already issued, the system will automatically generate a refund invoice.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image23.png)
+ Registering a refund is the same as registering a payment: click **"Register Payment"** on the refund invoice.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image24.png)


## 6. Refund And Return (Already delivered)
+ Follow the steps in Chapter 5 to create a refund invoice and process the refund.
+ Locate the corresponding delivery order, click the "return" button, and validate it.

![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image25.png)
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image26.png)

+ Enter the quantity of returned items and select the return location.
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image27.png)

After being returned to the warehouse, validate the returned allocation.
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image28.png)


## 7. Cancel order (with posted invoices)
+ Cancel Sale order
  The purpose of canceling an order is to automatically cancel the sales order.
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image29.png)

+ Add Credit Note from invoice and confirm
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image30.png)
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image31.png)

+ Register refund 
![](https://github.com/ryanniuu/lgc-odoo/blob/main/images/lgc_customer_invoice/image32.png)
