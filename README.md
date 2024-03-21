# Credit Smart MVP Functional Specification

Credit Smart is an educational tool that allows consumers to realize the potenital of making their everyday purchases with a credit card in comparison to a debit card. You can add your transaction to see how much ypou would get back at different percentages. You can also add your transactions to get a total amount for mutliple transactions. This application is for people who are not too well educated about the benefits of credit cards and the potential they hold. 

## Pain Point
People are not aware of all the potential earnings they could be making from using a credit card wisely. The potential benefits should be something everyone knows about so they can take the most advatange of their finances. 

## Hypothesis
If a person is exposed / more educated about the benefits and potentials of making most of their everyday purchases with a credit card, then they will be more inclined to do so and will take advantage of all the benefits and perks of doing so. 

## User Story
* As a user, I want to be able to add a transaction and see how much I could potentially earn based on different percentages. 
* As a user, I want to be able to see different credit card options out there and their details
* As a user, I want to be able see multiple transactions that I have added and see a total amount that I would have earned from all of them combined.
* As a user, I want to be able to add different cards to my Favorites list


# Domain Model
### User
* id
* created_at
* updated_at
* email
* password
* username


### Transactions 
* id
* created_at 
* updated_at
* descriptiom
* amount
* user_id
* percentage_back


### Credit Cards
* id
* created_at 
* updated_at
* name
* details

### Favorites
* id
* created_at 
* updated_at 
* credit_card_id
* user_id
