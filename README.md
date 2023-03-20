# Shopify TML Blocks
<p align="center">
  <img src="https://user-images.githubusercontent.com/29617424/191084315-61b6f2df-f39b-4cbe-988e-aa14dacb4b3e.png" alt="drawing" width="200"/>
</p>
Create a set of ThoughtSpot visualizations based on Shopify data hosted in Snowflake. Analyze orders, product margins, customer lifetime value, and customer segments based on RFM scores. Optionally, include popular advertising platforms such as Google and Facebook Ads to gain marketing insight.

# Artifacts 

## Keboola Use Case Template
- view details of the code here: https://github.com/keboola/keboola-as-code-templates/tree/main/thoughtspot-ecommerce-shopify/v1/src

## SpotApp Creation Tool
- Automatically update the TML files with your own `database` and `schema` [using this 🎈 Streamlit App](https://jordanrburger-ts-keboola-spotapps-streamlit-app-7svhq2.streamlitapp.com/) (or, run the app locally by [cloning this repository](https://github.com/jordanrburger/TS-Keboola-SpotApps))


# Worksheets
- Primary Worksheet
- Customers
- CLV By Order Count
- CLV By Time Since Previous Order
- Marketing Campaign Costs

# Liveboards Included
- Shopify - Overview
- Shopify - Customers
- Shopify - Orders
- Shopify - Products
- Shopify - Marketing Costs

# Setup Instructions

## 1. Create the template inside of Keboola 

To get started, follow this link - https://www.keboola.com/lp/spotapps to sign up for a free account from Keboola if you don't have one already. 

- After logging into Keboola, select the menu option called "Templates"
- From the list of available Templates, select "Shopify Analytics for Thoughtspot"
- Be sure to read through the details section for any special instructions that need to be followed. 
  - if you plan on using a Keboola-provisioned Snowflake, select keboola provided DWH, and follow instructions in keboola.
- Click on "Use Template" and give it a name
- A new template will be created and populated with the necessary components.
- In the editor, authorize your Shopify account using an API token
  - Optionally, authorize any additional advertising platforms in order to include marketing insights
- Choose your destination
- Run your flow!

This video provides a step-by-step guide for how to work with Keboola Use Case Templates using Google Analytics as an example. 

[![Data Templates Video](https://i9.ytimg.com/vi/tRIepqMa770/mq2.jpg?sqp=CPyXrJkG&rs=AOn4CLC8i3PleDt0Kg6pbQ_35rlMpEPxIg)](http://www.youtube.com/watch?v=tRIepqMa770 "Data Templates")

## 2. Connect to ThoughtSpot & Import the TML

- Navigate to ThoughtSpot and add a new connection
- Enter the credentials of the destination chosen in the Flow
- Automatically update the TML files with your own `database` and `schema` [using this 🎈 Streamlit App](https://jordanrburger-ts-keboola-spotapps-streamlit-app-7svhq2.streamlitapp.com/) (or, run the app locally by [cloning this repository](https://github.com/jordanrburger/TS-Keboola-SpotApps))
- Upload the resulting `.zip` file to ThoughtSpot

# Liveboard Screenshots

![ThoughtSpot shopify customers screenshot](https://user-images.githubusercontent.com/29617424/191553557-001e10d8-ba49-4fb3-b437-6d75eaa43cac.png)

![ThoughtSpot  shopify overview screenshot](https://user-images.githubusercontent.com/29617424/191551934-6f7ebde2-c385-4576-adfd-e238e0ad9db4.png)



