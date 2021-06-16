# Getting Started with Create React App
# Install Visual Studio
# Install Ganache
# Add metamask Wallet
# Install React-Js and required libraries(specified in package.json file).


# Import accounts from ganache to metamask
Here we copy the private key and import the required no of accounts and connect the required account.

## Available Scripts
# open Visual Studio.
Open commandline ,
Use Truffle compile- to compile the contracts.
Use Truffle migrate - to migrate the contracts.
Now do npm start- to run the app.

In the project directory, you can run:
# Running Application
Read the insteuctions.
## Signup
All actors should signup by providing the required  generalized credentials.
1) Firstname
2) Lastname
3) Address
4) email
5) password
6) Document(PDF only)
7) Public key
8) Contact no
## Additional Details  for few actors:
Agro-Consultant
  1) Specialization
  2) qualification 
  3) College name

Transporter
  1) Price per kg
  2) Price per km
  3) 
# Approval of actors from Governing Authority
Governing authority will login and checks all credentials and verifies the documents.

# Login:
## Two step user Verification:

For any actor to log in to the application apart from the governing authority, a two-step verification process has to be carried out. The two steps are:
1) Application and document verification
    Governing Authority will verifiy all the documents of the actors;If the credentials are correct then the status is changed to "verified".
2) Metamask account verification
    The Public key in username should be same as the connected account's primary key.


# For all the below mentioned actors,the metamask notification will pop-up to confirm the transaction.

# Farmer:

## Book Agro-Consultant

A farmer will be provided with the list of Agro-Consultants and he can choose and book one from the list. Booking a consultant is followed with the transfer of payment. And the farmer will be provided with a key and he should use this key while adding the crop.

## Add Security Deposit

If the farmer wants public funding functionality in their crops they have to start by depositing a certain amount of ethers as a security deposit.  The security deposit shall be used when the sales on the crop return losses. Farmers can request a maximum of 50\% of the security deposit they have invested in the application for their crops as public funds across all crops, which most likely increases their productivity by 33\%. Farmers can increase or decrease the security deposit on their account, based on the number of active fundings on the crops yet to be sold and have availed for funding.

## Propose new crop

The prerequisite for creating a new crop is that farmers should get a contract with the agricultural consultant. This contract will issue codes to both farmers and agricultural consultants. The code issued to farmers has to be added to the new crop along with the user ID of the agricultural consultant to connect the contract to the new crop being created. A new crop requires the following details: 

1)  Crop ID
2)  Crop variant
3)  Crop type
4)  Crop duration
5)  Agricultural consultant user ID
6)  Contract code
7)  If chosen yes, a maximum amount of funding required

## Buy Supplies

Farmers can view the list of all the suppliers available for a particular product. The application will list the quantities and the price of each product against the seller’s name and details. All the required products can be brought from the supplier and they will make payment through ethers.
# Investor:
 Investor Displays funding status of crops i.e. Funding Activated or Waiting for Funding.
 ## Activate Funding:
For all the crops whose investment has not reached maximum amount over crop duration, investor activates the funding by making investment of his choice. Transfer of ethers take place from investor to farmer
## Returns back to Investor: 
Investor will get back money, in which he might gain profit or incur loss depending on the  selling price. 

# Transporter:

## Transport Goods:
Transporter transports the goods to the concerned retailer based on his requirements.Retailer makes a request to distributor to supply goods to his location.Distributor takes all required information from the retailer like the crop he want to buy,the type of storage he needs ,the distance of his location and the quantity of crops he needs(in kg).These requirements are validated by distributor and he sends the transportation request to the list of transporters available.

## Accept or Reject Request:
The Transporter accepts the request the  moment the required amount is transferred  to  his  account.The transporter  may  reject the request if the amount has not been transferred to his account or if he is unavailable for transporting goods in that particular location.


# Agro Consultant:

## Consultation

Consultation from an agricultural consultant refers to the consultation that farmers book for their crops.

## Rate Crop

At each stage like Pre-Harvest, Harvest and Post-Harvest, the Agro-Consultant can rate the crops. For rating the crop he just need to answer some questions.

## Rate Farmer

After, the consultant completes all the stages of crop ratings. He/she will give a final rating for the farmer for the process followed in the production of quality of the product produced during the crop. This rating process contains 10 questions, each question having multiple choice answers. Each multiple choice has five options ranging from one to five.


# Supplier

## Add Commodity

The Supplier will be able to add the new commodities like seeds, pesticides, insecticides, fertilisers, etc.
For adding commodities the supplier has to provide the below details:
  1) Commodity name
  2) price per kg in ETH

## Edit Commodity

After adding the available commodity, he can also edit the commodity list like increasing or decreasing the availability of the commodity by clicking on the + or - button provided, removing the commodity form the list of available commodities by clicking on Remove Commodity button.


## Sell Commodity

In order to sell the available commodity he should get the request from the farmer. Farmer orders the materials or commodities to supplier and the order has to be less than the availability of the commodity. 

# Distributor

## Buy Goods

When the Agro Consultant submitting the rating for the post-harvesting stage for a particular crop, that will set the status of that crop to "Ready To Sell". After this the crops will be available to the distributor to buy.Then the distributor order the crops by clicking on the Buy Goods button, and then buy the crops from the farmer followed with payment transfer. 

## Hire Transporter

After buying the crops from the farmer, he has to transport these materials and sell it to the Retailers. So he has to hire some retailer. This can be done by selecting a retailer, that is whoever he is comfortable with the prices from the list of retailers.


 





