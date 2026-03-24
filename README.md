# PostgreSQL_Sales_Analysis_Project_PartA

### Objectives:
This project is focused on extracting insights related to various sales patterns, which are:
- Determining customer purchasing behavior
- Product performance
- Sales trends
- Inventory management

### Database Structure:
The Database consists of 4 different tables:

- **Customers** containing all the customer details and membership statuses

- **Products** containing the product catalogue and pricing

- **Sales** containing transactional sales data(products purchased, total amounts, customer details, etc)

- **Inventory** containing stock levels of the products in the catalogue

### Assumptions Made:
No duplicated values in the transactional sales datasets

### Key Findings:
- The most expensive product is in the 'Electronics' category. Most of the affordable products are in the Accessories category
- Customers who purchased high quantities/units of the products bought from the accessories category (the most affordable category)

### Recommendations:
- Focus marketing and stock high inventory in high-performing categories to generate more revenue for the business
- Implement automatic stock alerts and restocking thresholds, especially for products in the accessories section, with the tendency to sell more than 1 unit in one sale
- Offer discounts to reward loyalty for the customers (Make this tier-based.) This would capture the impulse buyers due to high discounts, and additionally help with sales from tier to tier within the membership_status bands
- Consider promotions for the slow-moving products/categories
- Consider pricing reviews + discounts for the slow-moving products
