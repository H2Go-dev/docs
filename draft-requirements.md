# H2Go: Water Bottle Delivery Subscription Platform

# 1. Overview

H2Go is a subscription-based water as a service (Waas) application that brings large water bottles directly to customers homes. The platform allows users to browse and subscribe to local water providers, choose from different bottle sizes, and schedule recurring or on-demand deliveries.

# 2. User Roles

## Admin
1. Get all Users (provider/user).
1. Approve provider accounts.
1. Remove provider From the system.

## Provider
1. Register for a provider account.
1. List water bottle sizes/prices.
1. User subscription approval.
1. User order approval.
1. Cancel user subscription.

## User
1. View local water providers.
1. Subscribe to local providers.
1. Make One time order.
1. Make a recurring Order.
1. View Order history and profile.


# 3. Fucntional Requirements

## 3.1 Authentication and User Management 

### User Registeration
- User provides: name, email, phone, password, profile picture (optional).

### Provider Registeration
- Provider provides: business name, email, phone, location.
- Status: "pending" until admin approves.

### Profile Management 
- Users can update name, email, phone, profile picture, password, delivery addresses.
- Provides can update: business name, email, location, pricing.


## 3.2 Product Management

### List Products (Proivder)
- Add bottle sizes.
- Set price per bottle.
- set quantity.

### Browse Products (User)
- View providers in his location.
- see available products from a provider.


## 3.3 Subscription Management 

### Subscribe to provider (user)
- Subscribe to provider.
- Status: "pending" until provider approve.

### Approve Subscription (provider)
- View pending subscription.
- Approve or reject with reason.
  - reasons might be something like 

### Cancel subscription 
- User can cancel anytime
- Provider can unsubscribe users. (user will be notified)

## 3.4 Order Management 

### Place One-time Order (user)
- select provider, bottle size, quantity.
- choose delivery date and address.
- Status: "pending" till approved.

### Place a recurring Order (user)
- same as before but choose repeat (daily, weekly, biweekly, monthly, custom).

### Approve Order (provider)
- View pending orders.
- Approve or reject orders.

### Track Orders (User)
- View order status: ("pending", "Confirmed", "Out for delivery", "Delievered") 

## 3.5 Admin 

### View all users
### Approve providers
### Remove Providers
