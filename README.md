Welcome, below will be the steps to follow to set up the codebase locally and to deploy the Them App extension


Prerequisites

1) A Shopify Partners account - https://www.shopify.com/partners
2) A development store - https://help.shopify.com/en/partners/dashboard/managing-stores/development-stores
3) Install Gadget CLI and the Shopify CLI locally. 
- Gadget CLi - npm install -g ggt
- shopify CLI - npm install -g @shopify/cli@latest


Setting up the Gadget Development Environment

1) Create a Development environment in the Gadget App, by selecting the Product Quiz App as a template - https://app.gadget.dev/auth/team?fork-app=product-quiz-template.gadget.app

Connect to the Shopify Partner Account
1) Go to the Shopify Partner dashboard and create a new app - https://partners.shopify.com/organizations?redirect_to=%2Fcurrent

2) Click Create app manually and name your app
3) Copy the Client ID and Client secret back to Gadget. You can + Add App Credentials to the Development environment in Gadget, then click Confirm 
4) Copy the App URL and Redirection URL back to the Shopify Partners dashboard. These can be pasted on the Configuration page of your Partners app
5) Go back to the Overview page of your Partners app and click Select store to install on a development store
6) Navigate to the Plugins page, and click Shop Installs underneath the Shopify connection tile
Once your sync is complete, you can build your first quiz in the shop admin.







Video Demo - Adding the theme app to the Merchant website, and demo on the Quiz App
Link - https://drive.google.com/file/d/10AydGkjf3ziz7X4yZAG0iobI842ZOwj0/view?usp=sharing

App Link - https://recommendation-quiz-app.myshopify.com/