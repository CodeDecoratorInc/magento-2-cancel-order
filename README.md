# Magento 2 Cancel Order Extension

## Introduction
The **Magento 2 Cancel Order Extension** allows customers to cancel their orders effortlessly from the frontend before they are processed. This feature enhances user experience and reduces unnecessary support requests. With this extension, store owners can define cancellation rules and streamline order management efficiently.

## How It Works
The **Magento 2 Cancel Order Extension** integrates seamlessly with your store, enabling customers to cancel orders directly from the My Orders section. The store admin can configure specific order statuses that allow cancellation. Once a customer cancels an order, the admin receives a notification, and the order status is updated accordingly. Additionally, the extension ensures a smooth refund process, improving customer satisfaction.

## Key Features
- Allow customers to cancel orders before processing.
- Configure eligible order statuses for cancellation.
- Admin notifications for order cancellations.
- Automatic status update upon order cancellation.

## Instant Order Cancellation
Customers can cancel their orders directly from the My Orders page, saving time and improving user experience.

## Configurable Order Statuses
Admins can define which order statuses are eligible for cancellation, preventing unnecessary disruptions in order processing.

## Admin Notifications
Receive real-time notifications when an order is canceled, allowing for quick response and further actions.

## Seamless Refund Process
Ensures smooth order cancellation and refund handling, enhancing customer trust and retention.

## Extension Installation
To install the Magento 2 Cancel Order extension, follow these steps:

### Step 1: Install the extension using Composer
```bash
composer require vendor/magento2-cancel-order
```
For a specific version:
```bash
composer require vendor/magento2-cancel-order:version
```
*Note: You may need authentication keys from the vendor or Magento Marketplace.*

### Step 2: Run the following Magento commands
```bash
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
php bin/magento cache:flush
```

## How to Configure Magento 2 Cancel Order Extension

### Step 1: Navigate to Admin Panel
Go to **Stores** > **Configuration** > **Sales** > **Cancel Order Settings**.

### Step 2: Enable the Extension
Set **Enable Cancel Order** to **Yes**.

### Step 3: Define Eligible Order Statuses
Select the order statuses that can be canceled by customers.

### Step 4: Save Configuration
Click **Save Config** and refresh the cache.

## Download Our [Magento 2 Cancel Order](https://codedecorator.com/magento-2-cancel-order.html) Extension
