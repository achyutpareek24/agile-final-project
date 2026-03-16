## User Story

**As a** product manager  
**I need** the ability to manage products in the catalog  
**So that** users can create, retrieve, update, and delete product information.

---

## Acceptance Criteria

**Scenario 1: Create product**

Given the product catalog service is running  
When a user submits a valid product creation request  
Then the product should be saved in the catalog database

**Scenario 2: Retrieve product**

Given a product exists in the catalog  
When a user requests the product by ID  
Then the system should return the product details

**Scenario 3: Update product**

Given a product exists in the catalog  
When a user updates the product information  
Then the updated product should be stored in the catalog

**Scenario 4: Delete product**

Given a product exists in the catalog  
When a user deletes the product  
Then the product should be removed from the catalog
