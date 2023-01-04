# MERN PROJECT - OKTION
## introduction :
our project is a eCommerce website have a ability to put some order on discount stage with limitation time.however , as any eCommerce website can add , remove , update and delete on orders by Admin and this consider a CRUD operation as we getting in MERN stack.in fact, there are some of relation between a models in DB like between user if he (admin or natural user) and products.

Our platform will be a place where people can bid on any kind of items that is posted by other people who are trying to sell those items,multiple people can
bid on any item they want and the person with the highest bid will win the auction and be able to buy that item for the price they paid.

##Requirements :
1. We will create a login and registration page in order to make our users
have access to our website , the user will fill the following data to be
able to join (user name, email, phone number, password.

2. When the user is logged in the Home page will be presented and it will
show all the available bids that the user can join in .

3. The user has the ability to start a bid by clicking on the create bid button
, the user will be redirected to the create bid page where will be asked
to enter the item information such as item title, picture of the item,
starting price of the bid, category, the starting and ending dates of the
bid.

4. When the user clicks on one of the bids on the home page the user will
be redirected to that item room if the bid time was started the user will
be able to place their bid with amount more than the current price of that
item, if the bidding time was not yet started you cant place bid.

5. When the bidding ending time is over the bidding will be stopped and
the user with the highest bid will be the new owner of that item.

in our ERB digram we explain the real relationship.
<img src="https://drive.google.com/file/d/1D83EIX6baZ04ZAEJ9evYtuM-e2UlZ386/view?usp=sharing"/>
