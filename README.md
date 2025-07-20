🛒 Global Superstore Management – Relational Database System

📁 Project Overview
* **Purpose:** Comprehensive database for multi-channel retail operations
* **Scope:** Customer management, order processing, inventory, analytics
* **Product Categories:** Electronics, Home Essentials, Furniture, Personal Care, Clothing, Groceries

🎯 Business Requirements
* **Customer Experience:** Online registration with personal info capture
* **Order Fulfillment Options:**
   * Pickup: Pay before or at collection
   * Delivery: Payment required at order placement
   * In-store: Traditional purchase experience
* **Returns:** Drop-off location with 5-7 day refund processing
* **Employee Management:** Track ID, name, job titles, department

📋 System Assumptions
* One account per customer (no duplicates)
* Registration is required before ordering
* One delivery agent per order (agent can handle multiple orders)
* Complete returns only (no partial)
* Single payment method per transaction

🗄️ Database Architecture
* **Design:** Enhanced Entity-Relationship (EER) model
* **Key Entities:**
   * Customer (personal info, order history)
   * Orders (status, payment, delivery details)
   * Products (categories, inventory)
   * Employees (store assignment, departments)
   * Payments (multiple methods supported)
* **Database:** MongoDB implementation

💳 Payment Analytics
| Payment Method | Revenue ($) | Market Share (%) |
|----------------|------------|------------------|
| **Debit Card** | **14,906** | **26.13%** |
| Applepay | 12,891 | 22.6% |
| Credit Card | 12,688 | 22.24% |
| PayPal | 11,926 | 20.91% |
| Cash | 4,636 | 8.13% |

👥 Customer Insights
* **Top Customer:** Bette Kutch ($2,815 total spend)
* **Average Order Value:** $938.33 for high-value customers
* **Customer Behavior:** Mix of high-value single orders and frequent small purchases
* **Loyalty Program:** Target top 10 customers for Thanksgiving rewards

📊 Analytics Capabilities
* **Simple Analytics:**
   * Top performing stores
   * Most valuable customers
   * Payment method preferences
   * Employee department queries
* **Advanced Analytics:**
   * Sales trend analysis
   * Cohort analysis
   * Customer segmentation (LTR)
   * Order pattern recognition

🧰 Technology Stack
* **Database:** **MongoDB**
* **Query Language:** MongoDB aggregation framework
* **Development:** SQL-like query structure
* **Visualization:** Integrated reporting tools
* **Performance:** Optimized for retail-scale operations

✅ Key Achievements
* Designed a comprehensive EER model for retail operations
* Implemented multi-channel order fulfillment system
* Created analytics framework for business insights
* Identified payment preferences for vendor partnerships
* Enabled customer segmentation for targeted marketing

🚀 Future Enhancements
* **Real-time Analytics:** Live dashboard for store performance
* **Predictive Modeling:** Demand forecasting, inventory optimization
* **Customer Experience:** Personalized recommendations, loyalty programs
* **Integration:** POS systems, e-commerce platforms, mobile apps
* **Automation:** Inventory reordering, dynamic pricing strategies
