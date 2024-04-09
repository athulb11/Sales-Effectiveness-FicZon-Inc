# Sales-Effectiveness-FicZon-Inc

## Business Case:
FicZon Inc is an IT solution provider with products ranging from onpremises products to SAAS based solutions. FicZon major leads generation channel is digital and through their website.

FicZon business is majorly dependent on the sales force effectiveness. As the market is maturing and more new competitors entering the market, FicZon is experiencing the dip in sales.

Effective sales is dependent on lead quality and as of now, this is based on manual categorization and highly depended on sales staff. Though there is a quality process, which continuously updates the lead categorization, it’s value is in for post analysis, rather than conversation.

FicZon wants to explore Machine Learning to pre-categorize the lead quality and as result, expecting significant increase in sales effectiveness.

## PROJECT GOAL:
Data exploration insights – Sales effectiveness.

ML model to predict the Lead Category (High Potential , Low Potential)

## Domain Analysis
1. Created - Date and time of lead generated.

2. Product_ID - Product id of the each products

3. Source - The channel through which a lead initially discovers the company which includes website visits, live chat platforms, referrals, campaigns, and personal contacts.

4. Mobile -Mobile phone number of the customer.

5. EMAIL - EmailID of the customer.

6. Sales Agent - A person or a company that acts as a sales agent on behalf of the company, introducing its products to the leads.

Location - Locations of the leads.

Delivery_Mode - Mode of the delivery according to the location.

Status - (The target variable) The field is typically used to communicate the status of a record to both the reporting users and the sales rep who is working the lead. The reporting user wants to see explicit detail while the sales rep wants to update the record in a natural and efficient manner.

## Conclusion
The dataset contained 7421 Rows and 9 Columns. All of the data's are in object datatype.From the exploratory analysis of the data it is seen that Product 18 is mostly seen but it doesn't show a great potential while Product 19 is least in number but it shows high potential leads and product 15 has the highest value in low potential which mean it faces challenges.While checking the Source Live chat,Call,Website shows high potential aswell as low potential leads also . But customer referalls and Existing customer shows bit better outcomes.Comparing other states in India Bangalore and Chennai are better and outiside India Malaysia and Singapore shows better leads. For model creation we had used 7 models from that Support Vector Machine Algorithm shows the highest accuracy of 87%.

## Suggestion
Concentrate on those product which gives great impact.

Check the challenges faced by the most frequent product.

Take the feedback from the users and utilize it for future purchases.

Expand the accessibility of the product by increasing the locations.

Find the challenges faced by the Sales Agents who are having less leads.

Expand the Delivert mode services.

Make the enviroment of the company healthy.

## Risks
High computational time.

Low scores in some models.

Unbalanced data.
