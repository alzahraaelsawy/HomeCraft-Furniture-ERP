# Sales Module

This page shows the Sales module workflow and configuration in Odoo for HomeCraft Furniture.

## Sales Order Workflow

### 1. Create a quotation and select the customer
![Select customer](screenshots/so-01-select-customer.png)

### 2. Choose a quotation template
Templates provide ready-made furniture packages.
![Select template](screenshots/so-02-select-template.png)

### 3. Apply a pricelist
Choose the pricelist that gives the customer the right discount.
![Select pricelist](screenshots/so-03-select-pricelist.png)
![Pricelist applied](screenshots/so-04-pricelist-applied.png)

### 4. Send the quotation to the customer
The quotation is sent by email with the PDF attached.
![Send quotation](screenshots/so-05-send-quotation.png)
![Quotation sent](screenshots/so-06-quotation-sent.png)

### 5. Customer portal preview
![Customer preview](screenshots/so-07-customer-preview.png)

### 6. Confirm the order
Confirming the quotation creates the sales order and the delivery.
![Sales order](screenshots/so-08-sales-order.png)

### 7. Deliver the products
Validating the delivery updates the stock and marks it as Done.
![Delivery ready](screenshots/so-09-delivery-ready.png)
![Delivery done](screenshots/so-10-delivery-done.png)

### 8. Create and confirm the customer invoice
After delivery, the invoice is created from the sales order and posted.
![Ready to invoice](screenshots/so-11-ready-to-invoice.png)
![Create invoice](screenshots/so-12-create-invoice.png)
![Draft invoice](screenshots/so-13-draft-invoice.png)
![Invoice posted](screenshots/so-14-invoice-posted.png)

> Payment of the customer invoice is covered in the Accounting module.

## Pricelist Setup

Pricelists apply automatic discounts to quotation lines.

**Seasonal Discount:** gives a 5% discount on all products for a defined period and is linked to the Egypt country group. This is the pricelist used in the sales order workflow above.

![Seasonal Discount pricelist](screenshots/sales-pricelist-seasonal.png)

**VIP Pricelist:** gives a 5% discount from 5 units and a 15% discount from 7 units.

![VIP pricelist rules](screenshots/sales-pricelist-rules.png)
![Pricelist rule detail](screenshots/sales-pricelist-rule-detail.png)

## Quotation Template Setup

Quotation templates store ready-made furniture packages with their products and quantities. A template also defines the quotation validity, online signature and online payment options, and can include optional products for the customer to choose from.

![Master Bedroom Package template](screenshots/sales-template-lines.png)

## Sales to Purchase Link

When the sales order is confirmed, Odoo automatically creates a request for quotation in the Purchase module for the product that needs to be purchased. The sales order shows a Purchase button that opens the linked request, and the request keeps the sales order as its source.

![Purchase button on the sales order](screenshots/link-01-sales-order-purchase-button.png)
![Linked request for quotation](screenshots/link-02-linked-rfq.png)

## Module Screenshots

### Customers
![Customers](screenshots/sales-customers.png)

### Quotations
![Quotations](screenshots/sales-quotations.png)

### Sales Orders
![Sales Orders](screenshots/sales-orders.png)

### Pricelists
![Pricelists](screenshots/sales-pricelists.png)

### Quotation Templates
![Quotation Templates](screenshots/sales-quotation-templates.png)

### Commission Plans
![Commission Plans](screenshots/sales-commission-plans.png)

### Sales Analysis
![Sales Analysis](screenshots/sales-analysis.png)
