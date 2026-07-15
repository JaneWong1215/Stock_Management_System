# Stock Management System

A desktop application built using **Java** designed to efficiently manage warehouse inventory. It allows users to authenticate via a login panel, add various product categories with specific attributes, track stock counts, and view/manage full product descriptions.

Contributed by: Wong Sin Yew, Chang Joo Yee, Ng Xue En, Wong Xin Tong

## 🚀 Features

- **User Authentication:** Secure login panel (`loginPane`) capturing User ID and Username before accessing the system.
- **Dynamic Product Catalog:** Supports multi-category stock management including:
  - Smart Phones
  - Air Conditioners
  - Refrigerators
  - TVs
  - Blenders
- **Inventory Operations:**
  - **Add Products:** Input unique item numbers, unique product names, specific attributes, initial quantities, and pricing.
  - **Stock Adjustment:** Easily add to or deduct from existing stock levels.
  - **Discontinue/Activate:** Change the status of a product to handle active inventory control.
  - **Display & Filter:** View full product configurations or look at products by specific types.
- **Data Validation:** Prevents duplicate item numbers, unique name violations, and ensures non-negative entries for quantities and prices.

## 🛠️ Project Structure

```text
Stock_Management_System/
├── bin/                       # Compiled .class binaries
└── src/                       # Java Source Code
    ├── Product.java           # Abstract base class for products
    ├── Smartphone.java        # Smartphone product subclass
    ├── AirConditioner.java    # Air Conditioner product subclass
    ├── Refrigerator.java      # Refrigerator product subclass
    ├── TV.java                # TV product subclass
    ├── Blender.java           # Blender product subclass
    ├── UserInfo.java          # Handles user session data
    ├── loginPane.java         # Java Login dialog panel
    └── StockManagementGUI.java# Application entry point & primary dashboard
