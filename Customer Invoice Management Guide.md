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
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773639424236-e00275c3-3916-49b9-96f8-e35c7a3527a2.png)  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773639672131-9ed984ad-1368-46f6-a770-db63da610160.png)  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773639790686-dc0b6d11-c676-460c-b425-42695c1e6071.png)

### Step 3: Print Customer Invoice
+ You can print the formal customer invoice document directly from the order.

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773639583468-4c19cb22-390d-4117-9fb6-6a2817f986e4.png)

> **Note on Styles:**
>
> + If the invoice is fully created, the customer invoice style will include professional formatting.
> + If not created, the document will follow a basic order-style layout.
>

**Standard Invoice Style:**  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773639907627-353d72fc-c106-4f67-8134-bc6677351b9a.png)  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773639918897-25a22c50-7949-4903-9190-c2e76fc4fa77.png)

**Un-invoiced Style:**  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773639737562-4c4ace8a-4116-47e6-a5cb-4f73518761a5.png)

---

## 2. Modify Order Quantity
### 2.1 Increase Quantity or Add Line Items
1. Click the **"Edit"** button on the Sales Order.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773640095988-58dbfa01-ed73-4116-bcf5-22bb2600ec01.png)
2. **To increase quantity**: Find the specific order line and modify the quantity.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773640117757-f667cf92-579b-4f7e-b8e3-ec2c63bc5f1b.png)
3. **To add a new product**: Click **"Add a product"** and then save.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773646057138-b6ebef29-4bdb-4c8d-8488-51fd3b99e077.png)

### 2.2 Reduce Quantity
+ If the delivery note has not been locked value, simply adjust the quantity and save.
+ If the delivery note is already locked, the system will show a warning prompt.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773646700265-3e19a01c-e6eb-4cab-b319-b31867887e61.png)

**Steps to modify a locked delivery order:**

1. Navigate to the **Delivery Order**.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773646803722-da43ec6a-69c9-479d-a0cc-cf9ff018bef5.png)
2. Click **"Edit"** and modify the **"Demand"** quantity on the **Operations** page to release inventory.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773646900883-73c04530-45a4-4871-850e-607c18203277.png)

---

## 3. Adjust Invoiced Amount
Create the invoice and confirm it to adjust the final invoiced amount, then print the "Customer Invoice" from the sale order.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773648698396-a783206d-3cf0-4963-b7bc-ba46134274d5.png)

---

## 4. Register Payment
Navigate to the **Invoices** section.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773763445588-1f3406ac-6fef-471a-8443-2625e8afeec5.png)

### Single Invoice
+ Clicking on a single invoice will redirect you to that invoice; click **"Register Payment"** and fill in the information.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773763710381-7600ad24-6fef-4291-81d0-bbc8ca6f0052.png)

### Multiple Invoices
+ If there are multiple invoices, select the relevant ones from the list view.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773763873206-67b25f0c-d6cc-44bf-8105-0acd2998a914.png)
+ **Important**: If the customer makes one payment for multiple invoices, select **"Group Payment"**.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773763915405-841f2172-62b0-42a3-8701-638993ddf8b0.png)

---

## 5. Refund (Credit Notes)
### Method 1: Add Credit Note (Recommended for Full Refunds)
+ For the invoice requiring a refund, click **"Add Credit Note"** to create a refund for the entire order.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773801677647-4445a7f4-6b09-4e6d-9a38-3165d1b21c6b.png)  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773801960940-0780b99c-d612-4031-8012-db665229f70e.png)
+ Click **"Confirm"** for a full refund, or modify quantities/prices for partial deductions before confirming.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773802070958-4c49c221-3dff-4100-9d53-9e4f50e5208c.png)

### Method 2: Modify Sales Order Quantity (Recommended for Small Partial Refunds)
+ Change the quantity of refunded products to `0` on the order page, then create an invoice.
+ If an invoice was already issued, the system will automatically generate a refund invoice.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773802217751-9d5aba34-2acb-47da-89fa-00f3112b2e3a.png)
+ Registering a refund is the same as registering a payment: click **"Register Payment"** on the refund invoice.  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/38859133/1773802358436-34292ca4-cd34-4a88-b794-390f4e5ab5b2.png)

