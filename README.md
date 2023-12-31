# [PYTHON] RFM Analysis
## I. Introduction
### 1. About RFM Analysis
### Why RFM?
- RFM is a marketing analysis technique that stands for Recency, Frequency, and Monetary Value.
  - **Recency**: measures how recently a customer has made a purchase.
  - **Frequency**: measures how often a customer has made purchases.
  - **Monetary Value**: measures the total amount of money a customer has spent on purchases.
- RFM is used to identify and categorize customers based on their purchasing behavior and how recently and frequently they have made purchases, as well as the monetary value of those purchases.
### How?
- In RFM analysis, customers are scored based on three factors (Recency - how recently, Frequency - how often, Monetary - how much), then labeled based on the combination of RFM scores
### Reference
- [RFM Analysis For Successful Customer Segmentation](https://www.putler.com/rfm-analysis)

### 2. Business Questions
- The Marketing Department is tasked with categorizing customer segments in order to tailor specific marketing programs for each group.
- The Marketing Director has put forth a proposal to implement the RFM model using Python for customer segmentation. The aim is to initiate marketing campaigns to express gratitude to loyal customers for their ongoing support and to tap into the potential customer base with the goal of fostering loyalty.
- Recommendations have been made to the Marketing and Sales teams regarding the company's retail model, highlighting the key question of which of the three indicators - R, F, and M - should be given the highest priority and attention.






## II. Data Visualization with Python
- **Seaborn Countplot of Frequency**

![image](https://user-images.githubusercontent.com/101726623/235647773-ca8207b8-5d53-4f5d-95dc-29b3ebc04b46.png)
- **Treemap of customer segmentation**

![newplot](https://user-images.githubusercontent.com/101726623/235647501-226fcecb-9db0-4996-85c6-f4238c421cc0.png)
- **Seaborn Countplot of customer segmentation**

![image](https://user-images.githubusercontent.com/101726623/235648007-108121f0-d6cf-4353-885c-2bf76d01cadb.png)
- **Pie chart of Channel**

![image](https://user-images.githubusercontent.com/101726623/235648595-b7c00066-2130-4386-9991-dacc50db4a1c.png)
- **Pie chart of Ship mode**

![image](https://user-images.githubusercontent.com/101726623/235648619-d43a2aaa-054a-4170-8708-2c8c53f17ba5.png)
- **Pie chart of Category**

![image](https://user-images.githubusercontent.com/101726623/235648648-bc05d567-d755-4b8a-b227-ec0a3bf9753b.png)
- **Pie chart of Sub-category**

![image](https://user-images.githubusercontent.com/101726623/235648663-667f65f9-4628-4554-9774-17950f7771c0.png)
- **Bar plot: Total Sales by Segmentation**

![image](https://user-images.githubusercontent.com/101726623/235648968-31eef44e-4154-4f82-90d3-a34866fa5b73.png)
- **Bar plot: Total Profit by Segmentation**

![image](https://user-images.githubusercontent.com/101726623/235649043-469a6a43-56e1-46db-a87b-ed32d0719b06.png)
- **Bar plot: Total Sales by Region**

![image](https://user-images.githubusercontent.com/101726623/235649234-3f7b712b-93a0-4469-b696-2efab733a2ea.png)
- **Treemap of State by Orders**

![newplot (1)](https://user-images.githubusercontent.com/101726623/235649382-7105ded5-388e-4f6a-9a52-e44ffcc25891.png)
## III. Insights
- 1. The most important index of the 3 indicators that the SuperStore company needs to pay attention to is F, then R: because the rate of customers buying once and twice is very high. Very few customers make long-term purchases like 8-9 times or more.
     -> That shows that the customer retention rate at the company is still low.
     
- 2. About Customer Segmentation: The company is mainly "New Customers" >"Hibernating customers">"Lost customers".
    -> This again shows that we need to pay attention to the index F.
  
- 3. Revenue and profit from "New Customers" is the highest.

- 4. The revenue in the East region is the lowest compared to the other 3 regions.

- 5. California, Texas, Illinois vs Florida are the states with the most orders.

- 6. The company's main customers are Consumers accounting for 52%, Corporate: 30%, and finally Home Office.

- 7. The categories with the most orders are "Office Supplies" up to 60%, then "Furniture".

- 8. The main subcategory are: Paper(14%), Binders(15%), Art(9%), Phones and Storage (8%).
## IV. Recommendations
- The company needs to have policies to:
  - **Retaining new customers**:
      - Extend a warm welcome to new customers who have recently made a purchase by sending them a personalized email expressing gratitude for their patronage and motivating them to revisit our business.

      - Engage customers who have completed a single purchase through targeted email marketing campaigns, nurturing their connection with our brand and motivating them to make a second purchase.

      - Provide an exclusive discount or promotional offer as an enticing incentive for their return.

      - Express appreciation to customers who have made significant, high-value purchases and introduce them to our loyalty program, designed to reward their ongoing loyalty with exclusive benefits.
  - **Promoting hibernating customers**:
      - Reach out to hibernating customers who haven't made a recent purchase by sending them a reactivation email or an enticing offer aimed at rekindling their engagement with our brand.
      - Craft a unique discount or promotional deal that aligns with their previous buying habits.
      - Target repeat customers who have lapsed in recent purchases with personalized email campaigns that spotlight our latest offerings and services tailored to their preferences.
      - Extend a personalized email or offer to our valued patrons who've been absent from our store, showcasing new products or services that cater to their interests, and provide them with an exclusive discount or promotion tailored to their past shopping history.
- Need to have a marketing strategy to focus on the segment: Consumer -> Office Supplies segment in states like California, Texas, and Illinois vs Florida.
