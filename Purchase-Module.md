# Purchase Module

This page shows the Purchase module workflow and configuration in Odoo for HomeCraft Furniture.

## Purchase Order Workflow

### 1. Create a Request for Quotation (RFQ)
Create a new RFQ and select the vendor.
![Create RFQ](screenshots/po-01-create-rfq.png)

### 2. Add products
Add the required products and quantities to the RFQ.
![Add products](screenshots/po-02-add-products.png)

### 3. Send the RFQ to the vendor
Click Send RFQ, then send the email with the RFQ PDF attached.
![Send RFQ](screenshots/po-03-send-rfq.png)
![Send email](screenshots/po-03-send-email.png)

### 4. Confirm the order
Confirm the RFQ to convert it into a Purchase Order.
![Confirm order](screenshots/po-04-confirm-order.png)

### 5. Receive the products
Click Receive to open the receipt created automatically for the order.
![Receive](screenshots/po-05-receive.png)

### 6. Validate the receipt
Validating the receipt updates the stock and marks the receipt as Done.
![Validate receipt](screenshots/po-06-validate-receipt.png)
![Receipt done](screenshots/po-07-receipt-done.png)

> After receiving the products, the vendor bill is created and posted in the Accounting module.

## Purchase Agreement (Blanket Order)

A blanket order is an agreement with a vendor for a defined period. It records the vendor, the validity dates, and the products with the agreed quantity and unit price. Purchase orders can be created from the agreement, and the ordered quantity is tracked against the agreed quantity.

![Blanket order BO00001](screenshots/purchase-agreement-detail.png)

The purchase order created from the agreement shows the agreement reference and uses the agreed unit price.

![Order linked to the agreement](screenshots/purchase-agreement-linked-order.png)


## Module Screenshots

### Vendors
![Vendors](screenshots/purchase-vendors.png)

### Products
![Products](screenshots/purchase-products.png)

### Requests for Quotation
![RFQ](screenshots/purchase-rfq.png)

### Purchase Agreements
![Agreements](screenshots/purchase-agreements.png)

### Product Categories
![Categories](screenshots/purchase-categories.png)

### Attributes
![Attributes](screenshots/purchase-attributes.png)

### Purchase Analysis
![Analysis](screenshots/purchase-analysis.png)
