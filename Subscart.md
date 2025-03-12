<div align="center"> 
<img src="/api/placeholder/800/120" alt="Subscart Logo Banner" /> 

# 🍽️ SUBSCART DOCUMENTATION

Version 1.0 | March 2025
</div>

<div style="page-break-after: always;"></div>

## 📑 Table of Contents

1. [Overview](#overview)
2. [Vendor Module](#1-vendor-module)
3. [Customer Module](#2-customer-module)
4. [Staff Module](#3-staff-module)
5. [Delivery Driver Module](#4-delivery-driver-module)
6. [Conclusion](#conclusion)

<div style="page-break-after: always;"></div>

## Overview

<div align="center">

### 🎯 Subscart Platform

![[platform_overview.jpg]]

</div>

Subscart is a cutting-edge subscription management platform designed to seamlessly connect vendors and customers in one ecosystem. From food subscriptions to flexible delivery options, we are redefining how subscriptions are created, managed, and delivered.

### Why Subscart?

![[why_subscart.jpg]]

The subscription economy is expanding rapidly, but managing subscriptions remains a complex and fragmented experience for both businesses and customers. Many vendors struggle with setting up and managing flexible subscriptions, while customers face difficulties in modifying, pausing, or customizing their plans. Subscart simplifies this process by offering an all-in-one platform that streamlines subscription management, delivery, and customer interaction.

### Market Gap & Opportunity

![[market_gap.jpg]]

<table>
<tr>
<th align="center">Challenge</th>
<th align="center">Subscart Solution</th>
</tr>
<tr>
<td align="center">1️⃣ Lack of<br>Integration</td>
<td>
• End-to-end solution for all stakeholders<br>
• Unified platform for subscription, payment, and delivery<br>
• Seamless communication between modules
</td>
</tr>
<tr>
<td align="center">2️⃣ Rigid<br>Models</td>
<td>
• Flexible subscription modifications<br>
• Pause/resume functionality<br>
• Customizable delivery options
</td>
</tr>
<tr>
<td align="center">3️⃣ High<br>Costs</td>
<td>
• Cost-effective platform for small businesses<br>
• Minimal initial investment<br>
• Scalable infrastructure
</td>
</tr>
<tr>
<td align="center">4️⃣ Poor<br>Delivery</td>
<td>
• Real-time tracking<br>
• Optimized routes<br>
• Efficient delivery management
</td>
</tr>
</table>

### Registration Process

![[registration.jpg]]

<table>
<tr>
<th align="center">👨‍🍳 Vendor Registration</th>
<th align="center">👥 Customer Registration</th>
</tr>
<tr>
<td>
1. Complete registration form<br>
2. Submit for admin approval<br>
3. Receive approval notification<br>
4. Set up outlet profile<br>
5. Configure delivery options<br>
6. Start creating subscriptions
</td>
<td>
1. Sign up with basic details<br>
2. Verify contact information<br>
3. Set delivery preferences<br>
4. Browse available outlets<br>
5. Subscribe to plans<br>
6. Manage subscriptions
</td>
</tr>
</table>

### Core Workflow

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#e1f5fe', 'primaryBorderColor': '#0288d1', 'secondaryColor': '#f3e5f5', 'secondaryBorderColor': '#7b1fa2'}}}%%
graph LR
    A[Vendors create plans] --> B[Customers subscribe]
    B --> C[Staff prepare meals]
    C --> D[Drivers deliver orders]
    
    style A fill:#e1f5fe,stroke:#0288d1,stroke-width:2px
    style B fill:#e8f5e9,stroke:#388e3c,stroke-width:2px
    style C fill:#fff8e1,stroke:#ffa000,stroke-width:2px
    style D fill:#fce4ec,stroke:#d81b60,stroke-width:2px
```

### Key Stakeholders

<div align="center">

#### 🔄 Platform Roles

![[stakeholders.jpg]]

</div>

<table>
<tr>
<th align="center">Role</th>
<th align="center">Responsibilities</th>
</tr>
<tr>
<td align="center">👨‍🍳 Vendors</td>
<td>
• Create and manage subscription plans<br>
• Handle deliveries and payments<br>
• Track customer engagement
</td>
</tr>
<tr>
<td align="center">👥 Customers</td>
<td>
• Browse and subscribe to plans<br>
• Customize delivery preferences<br>
• Manage active subscriptions
</td>
</tr>
<tr>
<td align="center">👨‍🔧 Staff</td>
<td>
• Oversee order preparation<br>
• Manage inventory<br>
• Ensure quality control
</td>
</tr>
<tr>
<td align="center">🚗 Drivers</td>
<td>
• Handle timely deliveries<br>
• Follow optimized routes<br>
• Update delivery status
</td>
</tr>
</table>

### Platform Advantages

<div align="center">

#### ✨ Key Benefits

![[advantages.jpg]]

</div>

<table>
<tr>
<th align="center">Feature</th>
<th align="center">Benefits</th>
</tr>
<tr>
<td align="center">✅ Vendor<br>Management</td>
<td>
• Effortless subscription creation<br>
• Automated payment processing<br>
• Integrated delivery tracking
</td>
</tr>
<tr>
<td align="center">✅ Customer<br>Experience</td>
<td>
• Flexible subscription control<br>
• Easy plan modifications<br>
• Reduced subscription churn
</td>
</tr>
<tr>
<td align="center">✅ Optimized<br>Logistics</td>
<td>
• Streamlined order fulfillment<br>
• Real-time delivery updates<br>
• Efficient route planning
</td>
</tr>
<tr>
<td align="center">✅ Business<br>Scalability</td>
<td>
• Cost-effective solution<br>
• Market expansion tools<br>
• Growth-ready infrastructure
</td>
</tr>
</table>

<div style="page-break-after: always;"></div>

## 1. Vendor Module

<div align="center">

### 🏪 Vendor Management System

</div>

The vendor module empowers food service providers to create, manage, and monitor subscription-based meal plans.

### Subscription Types
![[flexible.jpg]]

<table>
<tr>
<th width="50%" align="center">📋 Fixed Subscription</th>
<th width="50%" align="center">🔄 Flexible Subscription</th>
</tr>
<tr>
<td>
<ul>
<li>Meal plan remains unchanged throughout subscription</li>
<li>Same meals delivered on scheduled days</li>
<li>Simplified management</li>
<li>Predictable inventory planning</li>
</ul>
</td>
<td>
<ul>
<li>Menu can change for different delivery days</li>
<li>Adaptable to seasonal ingredients</li>
<li>Can be modified even after creation</li>
<li>Greater variety for customers</li>
</ul>
</td>
</tr>
</table>

### Subscription Creation Process
![[product.jpg]]

<table>
<tr>
<th width="5%" align="center">Step</th>
<th width="25%">Action</th>
<th width="70%">Description</th>
</tr>
<tr>
<td align="center">1</td>
<td>Choose Subscription Type</td>
<td>Select either Fixed or Flexible subscription model</td>
</tr>
<tr>
<td align="center">2</td>
<td>Name the Subscription</td>
<td>Assign a descriptive name to the subscription plan</td>
</tr>
<tr>
<td align="center">3</td>
<td>Select Delivery Days</td>
<td>Choose which days of the week meals will be delivered</td>
</tr>
<tr>
<td align="center">4</td>
<td>Assign Products</td>
<td>Select specific meals for each chosen delivery day</td>
</tr>
<tr>
<td align="center">5</td>
<td>Add Optional Add-ons</td>
<td>Configure additional items (beverages, snacks) with quantity limits</td>
</tr>
<tr>
<td align="center">6</td>
<td>Set Duration</td>
<td>Define the subscription period (e.g., 30 days, 60 days)</td>
</tr>
<tr>
<td align="center">7</td>
<td>Choose Delivery Type</td>
<td>Select from delivery options (see below)</td>
</tr>
<tr>
<td align="center">8</td>
<td>Set Preparation Time</td>
<td>Define lead time required before delivery/pickup</td>
</tr>
<tr>
<td align="center">9</td>
<td>Submit for Approval</td>
<td>Send to admin for review and approval</td>
</tr>
</table>

### Delivery Options

<table>
<tr>
<th width="20%" align="center">Option</th>
<th width="80%">Description</th>
</tr>
<tr>
<td align="center">🚚 Delivery</td>
<td>Using either Subscart's delivery service (0.5 OMR per delivery) or vendor's own delivery system</td>
</tr>
<tr>
<td align="center">🏬 Pickup</td>
<td>Customers collect their meals from the vendor's physical location</td>
</tr>
<tr>
<td align="center">🔄 Pickup & Delivery</td>
<td>Customers can choose between pickup or delivery for maximum flexibility</td>
</tr>
</table>

### Delivery Method Implementation

<div align="center">

#### 🚚 Comprehensive Delivery Solutions

</div>

Each delivery option follows a specific workflow designed to ensure reliable and efficient order fulfillment:

<table>
<tr>
<th width="25%" align="center">Method</th>
<th width="75%">Process Description</th>
</tr>
<tr>
<td align="center">📦 Subscription<br>Delivery</td>
<td>
<ol>
<li>Customer subscribes to meal plan</li>
<li>System schedules orders automatically</li>
<li>Staff notified 1 hour before delivery</li>
<li>Meals prepared and packed</li>
<li>Delivery agent delivers to registered address</li>
<li>Customer receives at scheduled time</li>
</ol>
</td>
</tr>
<tr>
<td align="center">🏪 Vendor<br>Delivery</td>
<td>
<ol>
<li>Customer places order with vendor</li>
<li>Vendor receives notification</li>
<li>Order prepared and packed</li>
<li>Delivery agent picks up order</li>
<li>Order delivered to customer</li>
<li>Customer confirms receipt</li>
</ol>
</td>
</tr>
<tr>
<td align="center">🛍️ Pickup</td>
<td>
<ol>
<li>Customer selects "Pickup" option</li>
<li>Vendor/staff receives notification</li>
<li>Order prepared and marked ready</li>
<li>Customer receives notification</li>
<li>Customer verifies with QR/ID</li>
<li>Vendor hands over order</li>
<li>Order marked complete</li>
</ol>
</td>
</tr>
<tr>
<td align="center">🔄 Pickup &<br>Delivery</td>
<td>
<ol>
<li>Customer chooses method</li>
<li>Vendor processes order</li>
<li>Order prepared</li>
<li>For pickup: Counter placement</li>
<li>For delivery: Agent assignment</li>
<li>Customer receives/collects</li>
<li>Order completion</li>
</ol>
</td>
</tr>
<tr>
<td align="center">📅 Subscription<br>P&D</td>
<td>
<ol>
<li>Customer creates subscription</li>
<li>System generates schedule</li>
<li>Staff notified before prep</li>
<li>Meals prepared and packed</li>
<li>Pickup: Counter placement</li>
<li>Delivery: Agent delivers</li>
<li>Customer collects/receives</li>
</ol>
</td>
</tr>
</table>

### Process Flowcharts

<div align="center">

#### Detailed Workflow Diagrams

</div>

##### 1. Subscription Delivery

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#e1f5fe', 'primaryBorderColor': '#0288d1', 'secondaryColor': '#f3e5f5', 'secondaryBorderColor': '#7b1fa2'}}}%%
graph LR
    A[Subscribe] --> B[Schedule Created]
    B --> C[Order Generated]
    C --> D[Staff Notified]
    D --> E[Meal Prepared]
    E --> F[Packed & Dispatched]
    F --> G[Delivered]
    
    style A fill:#e1f5fe,stroke:#0288d1,stroke-width:2px
    style B fill:#e8f5e9,stroke:#388e3c,stroke-width:2px
    style C fill:#fff8e1,stroke:#ffa000,stroke-width:2px
    style D fill:#fce4ec,stroke:#d81b60,stroke-width:2px
    style E fill:#f3e5f5,stroke:#7b1fa2,stroke-width:2px
    style F fill:#e8eaf6,stroke:#3f51b5,stroke-width:2px
    style G fill:#e0f2f1,stroke:#009688,stroke-width:2px
```

##### 2. Vendor Delivery

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#e1f5fe', 'primaryBorderColor': '#0288d1', 'secondaryColor': '#f3e5f5', 'secondaryBorderColor': '#7b1fa2'}}}%%
graph LR
    A[Order Placed] --> B[Vendor Notified]
    B --> C[Order Prepared]
    C --> D[Packed & Dispatched]
    D --> E[Delivered]
    
    style A fill:#e1f5fe,stroke:#0288d1,stroke-width:2px
    style B fill:#e8f5e9,stroke:#388e3c,stroke-width:2px
    style C fill:#fff8e1,stroke:#ffa000,stroke-width:2px
    style D fill:#fce4ec,stroke:#d81b60,stroke-width:2px
    style E fill:#f3e5f5,stroke:#7b1fa2,stroke-width:2px
```

##### 3. Pickup

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#e1f5fe', 'primaryBorderColor': '#0288d1', 'secondaryColor': '#f3e5f5', 'secondaryBorderColor': '#7b1fa2'}}}%%
graph LR
    A[Order Placed] --> B[Vendor Notified]
    B --> C[Order Prepared]
    C --> D[Ready for Pickup]
    D --> E[Customer Arrives]
    E --> F[Order Verified]
    F --> G[Order Handed Over]
    
    style A fill:#e1f5fe,stroke:#0288d1,stroke-width:2px
    style B fill:#e8f5e9,stroke:#388e3c,stroke-width:2px
    style C fill:#fff8e1,stroke:#ffa000,stroke-width:2px
    style D fill:#fce4ec,stroke:#d81b60,stroke-width:2px
    style E fill:#f3e5f5,stroke:#7b1fa2,stroke-width:2px
    style F fill:#e8eaf6,stroke:#3f51b5,stroke-width:2px
    style G fill:#e0f2f1,stroke:#009688,stroke-width:2px
```

##### 4. Pickup & Delivery Combination

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#e1f5fe', 'primaryBorderColor': '#0288d1', 'secondaryColor': '#f3e5f5', 'secondaryBorderColor': '#7b1fa2'}}}%%
graph TD
    A[Order Placed] --> B[Vendor Notified]
    B --> C[Order Processed]
    C --> D{Delivery Type}
    D -->|Pickup| E[Customer Collects]
    D -->|Delivery| F[Agent Delivers]
    E --> G[Complete]
    F --> G
    
    style A fill:#e1f5fe,stroke:#0288d1,stroke-width:2px
    style B fill:#e8f5e9,stroke:#388e3c,stroke-width:2px
    style C fill:#fff8e1,stroke:#ffa000,stroke-width:2px
    style D fill:#fce4ec,stroke:#d81b60,stroke-width:2px
    style E fill:#f3e5f5,stroke:#7b1fa2,stroke-width:2px
    style F fill:#e8eaf6,stroke:#3f51b5,stroke-width:2px
    style G fill:#e0f2f1,stroke:#009688,stroke-width:2px
```


<div style="page-break-after: always;"></div>

## 2. Customer Module

The customer module provides a streamlined interface for browsing, purchasing, and managing meal subscriptions.

### Subscription Journey

<table> <tr> <th width="33%">Discovery Phase</th> <th width="33%">Purchase Phase</th> <th width="33%">Management Phase</th> </tr> <tr> <td> <ol> <li>Browse available meal plans</li> <li>View subscription details</li> <li>Check vendor ratings</li> <li>Review meal options</li> </ol> </td> <td> <ol> <li>Select subscription type</li> <li>Choose delivery option</li> <li>Configure add-ons</li> <li>Complete payment</li> </ol> </td> <td> <ol> <li>View active subscriptions</li> <li>Pause/resume as needed</li> <li>Modify products</li> <li>Track upcoming deliveries</li> </ol> </td> </tr> </table>

### Customer Management Features

<table> <tr> <th width="25%">Feature</th> <th width="75%">Description</th> </tr> <tr> <td>Pause Subscription</td> <td>Temporarily halt deliveries without canceling the subscription, ideal for vacations or when meals aren't needed</td> </tr> <tr> <td>Modify Add-ons</td> <td>Adjust optional items within vendor-defined limits to customize the subscription experience</td> </tr> <tr> <td>Cancel Subscription</td> <td>End subscription based on vendor-defined cancellation policies</td> </tr> <tr> <td>Delivery Schedule</td> <td>View calendar of upcoming deliveries with detailed information about each meal</td> </tr> <tr> <td>Payment Management</td> <td>Update payment methods and view billing history</td> </tr> </table> <div style="page-break-after: always;"></div>

## 3. Staff Module

<div align="center">

### 👨‍🔧 Staff Operations

</div>

The dedicated Staff App streamlines meal preparation workflows for vendor employees.

### Key Features

<table>
<tr>
<th width="25%" align="center">Feature</th>
<th width="75%">Description</th>
</tr>
<tr>
<td align="center">📊 Order<br>Dashboard</td>
<td>Comprehensive view of all upcoming orders sorted by preparation deadline</td>
</tr>
<tr>
<td align="center">📅 Calendar<br>Integration</td>
<td>Visual calendar showing all scheduled preparations to facilitate resource planning</td>
</tr>
<tr>
<td align="center">📝 Preparation<br>Tracking</td>
<td>Mark orders as "In Progress" and "Prepared" to maintain workflow visibility</td>
</tr>
<tr>
<td align="center">🔔 Notification<br>System</td>
<td>Automated alerts for upcoming preparation deadlines and special instructions</td>
</tr>
<tr>
<td align="center">📦 Ingredient<br>Management</td>
<td>View required ingredients for upcoming orders to ensure adequate stock</td>
</tr>
</table>

### Staff Workflow

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#e1f5fe', 'primaryBorderColor': '#0288d1', 'secondaryColor': '#f3e5f5', 'secondaryBorderColor': '#7b1fa2'}}}%%
graph LR
    A[Receive Order] --> B[Check Inventory]
    B --> C[Prepare Meal]
    C --> D[Quality Check]
    D --> E[Pack Order]
    E --> F[Ready for Delivery]
    
    style A fill:#e1f5fe,stroke:#0288d1,stroke-width:2px
    style B fill:#e8f5e9,stroke:#388e3c,stroke-width:2px
    style C fill:#fff8e1,stroke:#ffa000,stroke-width:2px
    style D fill:#fce4ec,stroke:#d81b60,stroke-width:2px
    style E fill:#f3e5f5,stroke:#7b1fa2,stroke-width:2px
    style F fill:#e8eaf6,stroke:#3f51b5,stroke-width:2px
```

<div style="page-break-after: always;"></div>

## 4. Delivery Driver Module

<div align="center">

### 🚗 Delivery Operations

</div>

The Delivery Driver App manages the final step in the subscription fulfillment process.

### Delivery Workflow

<table>
<tr>
<th align="center">Stage</th>
<th align="center">Action</th>
<th>Details</th>
</tr>
<tr>
<td align="center">1️⃣</td>
<td align="center">📱 Notification</td>
<td>Driver receives notification when staff marks an order as prepared</td>
</tr>
<tr>
<td align="center">2️⃣</td>
<td align="center">✅ Acceptance</td>
<td>Driver reviews order details and accepts the delivery task</td>
</tr>
<tr>
<td align="center">3️⃣</td>
<td align="center">🏪 Pickup</td>
<td>Driver navigates to vendor location and confirms pickup</td>
</tr>
<tr>
<td align="center">4️⃣</td>
<td align="center">🚚 Delivery</td>
<td>Driver delivers meal to customer location using optimal route</td>
</tr>
<tr>
<td align="center">5️⃣</td>
<td align="center">✔️ Completion</td>
<td>Driver marks delivery as complete after customer receipt</td>
</tr>
<tr>
<td align="center">6️⃣</td>
<td align="center">💰 Incentive</td>
<td>Compensation is added to driver's earnings account</td>
</tr>
</table>

### Driver App Features

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#e1f5fe', 'primaryBorderColor': '#0288d1', 'secondaryColor': '#f3e5f5', 'secondaryBorderColor': '#7b1fa2'}}}%%
graph TD
    A[Driver App] --> B[Order Management]
    A --> C[Navigation]
    A --> D[Earnings]
    A --> E[Support]
    
    B --> B1[Accept Orders]
    B --> B2[View Details]
    B --> B3[Update Status]
    
    C --> C1[Route Planning]
    C --> C2[Live GPS]
    C --> C3[Traffic Updates]
    
    D --> D1[Track Earnings]
    D --> D2[View History]
    D --> D3[Incentives]
    
    E --> E1[Chat Support]
    E --> E2[Emergency Help]
    E --> E3[FAQs]
    
    style A fill:#e1f5fe,stroke:#0288d1,stroke-width:2px
    style B fill:#e8f5e9,stroke:#388e3c,stroke-width:2px
    style C fill:#fff8e1,stroke:#ffa000,stroke-width:2px
    style D fill:#fce4ec,stroke:#d81b60,stroke-width:2px
    style E fill:#f3e5f5,stroke:#7b1fa2,stroke-width:2px
```

### Key Features

<table>
<tr>
<th width="25%" align="center">Feature</th>
<th width="75%">Description</th>
</tr>
<tr>
<td align="center">📱 Real-time<br>Updates</td>
<td>Instant notifications for new orders, changes, and delivery status updates</td>
</tr>
<tr>
<td align="center">🗺️ Smart<br>Navigation</td>
<td>Optimized routing with real-time traffic updates and turn-by-turn directions</td>
</tr>
<tr>
<td align="center">💰 Earnings<br>Tracker</td>
<td>Detailed breakdown of deliveries, earnings, and incentives</td>
</tr>
<tr>
<td align="center">📊 Performance<br>Metrics</td>
<td>Track delivery times, customer ratings, and completion rates</td>
</tr>
<tr>
<td align="center">🆘 Support<br>System</td>
<td>24/7 access to customer service and emergency assistance</td>
</tr>
</table>

<div style="page-break-after: always;"></div>

<div style="page-break-after: always;"></div>

## Conclusion

<div align="center">

### 🎯 System Overview

</div>

Subscart provides a comprehensive solution for subscription-based meal delivery, integrating vendors, customers, staff, and drivers into a seamless ecosystem.

### Key Components

<table>
<tr>
<th width="25%" align="center">Module</th>
<th width="75%">Core Features</th>
</tr>
<tr>
<td align="center">🏪 Vendor</td>
<td>
• Subscription plan creation<br>
• Delivery method configuration<br>
• Order management
</td>
</tr>
<tr>
<td align="center">👥 Customer</td>
<td>
• Plan browsing and subscription<br>
• Delivery preferences<br>
• Subscription management
</td>
</tr>
<tr>
<td align="center">👨‍🔧 Staff</td>
<td>
• Order preparation<br>
• Inventory management<br>
• Quality control
</td>
</tr>
<tr>
<td align="center">🚗 Driver</td>
<td>
• Real-time order tracking<br>
• Route optimization<br>
• Delivery confirmation
</td>
</tr>
</table>

### Delivery Methods Summary

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#e1f5fe', 'primaryBorderColor': '#0288d1', 'secondaryColor': '#f3e5f5', 'secondaryBorderColor': '#7b1fa2'}}}%%
graph TD
    A[Delivery Methods] --> B[Subscription Delivery]
    A --> C[Vendor Delivery]
    A --> D[Pickup]
    A --> E[Pickup & Delivery]
    
    style A fill:#e1f5fe,stroke:#0288d1,stroke-width:2px
    style B fill:#e8f5e9,stroke:#388e3c,stroke-width:2px
    style C fill:#fff8e1,stroke:#ffa000,stroke-width:2px
    style D fill:#fce4ec,stroke:#d81b60,stroke-width:2px
    style E fill:#f3e5f5,stroke:#7b1fa2,stroke-width:2px
    style F fill:#e8eaf6,stroke:#3f51b5,stroke-width:2px
```

### System Benefits

<table>
<tr>
<th width="33%" align="center">📈 Business</th>
<th width="33%" align="center">🤝 Customer</th>
<th width="33%" align="center">🔧 Operations</th>
</tr>
<tr>
<td align="center">
• Recurring revenue<br>
• Customer retention<br>
• Market expansion
</td>
<td align="center">
• Convenience<br>
• Flexibility<br>
• Reliability
</td>
<td align="center">
• Automation<br>
• Efficiency<br>
• Scalability
</td>
</tr>
</table>

### Complete System Integration

<img src="/api/placeholder/650/350" alt="System Integration Diagram" />

### System Integration

<div align="center">

#### 🔄 End-to-End Flow

</div>

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#e1f5fe', 'primaryBorderColor': '#0288d1', 'secondaryColor': '#f3e5f5', 'secondaryBorderColor': '#7b1fa2'}}}%%
graph LR
    A[Vendor Creates Plan] --> B[Customer Subscribes]
    B --> C[Staff Prepares]
    C --> D[Driver Delivers]
    D --> E[Customer Receives]
    E --> F[Cycle Repeats]
    F --> B
    
    style A fill:#e1f5fe,stroke:#0288d1,stroke-width:2px
    style B fill:#e8f5e9,stroke:#388e3c,stroke-width:2px
    style C fill:#fff8e1,stroke:#ffa000,stroke-width:2px
    style D fill:#fce4ec,stroke:#d81b60,stroke-width:2px
    style E fill:#f3e5f5,stroke:#7b1fa2,stroke-width:2px
    style F fill:#e8eaf6,stroke:#3f51b5,stroke-width:2px
```

### Implementation Status

<table>
<tr>
<th width="25%" align="center">Phase</th>
<th width="55%" align="center">Status</th>
<th width="20%" align="center">Progress</th>
</tr>
<tr>
<td align="center">🏪 Vendor Module</td>
<td>Core functionality complete, testing ongoing</td>
<td align="center">90%</td>
</tr>
<tr>
<td align="center">👥 Customer Module</td>
<td>All features implemented and validated</td>
<td align="center">100%</td>
</tr>
<tr>
<td align="center">👨‍🔧 Staff Module</td>
<td>Final testing and optimization in progress</td>
<td align="center">85%</td>
</tr>
<tr>
<td align="center">🚗 Driver Module</td>
<td>Route optimization enhancements pending</td>
<td align="center">95%</td>
</tr>
</table>

<div align="center">

---

### 🌟 Ready for Launch

The Subscart platform is now prepared to revolutionize subscription-based meal delivery services.

</div>
