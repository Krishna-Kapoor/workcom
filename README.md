HOME RENTAL SYSTEM

SOFTWARE REQUIREMENT SPECIFICATIONS

SCOPE
The Home Rental system allows people of this fast paced world to find credible homes easily from any part of the world according to their requirements. This also provides a platform for the renters to showcase their properties easily. This saves time and effort of both renters and users. 
OBJECTIVE
The main objective of this project is to develop a home rental system. It helps users to find and rent homes from a variety of credible renters online. The search for homes can be filtered according to their preferences. Booking can also be done online.
Due to the various rating and reviews, each property can be evaluated thoroughly.

SOFTWARE REQUIREMENTS
Operating System : Any
User Interface : Angular
Client-side scripting : Javascript
Programming Language : Java
Database : MongoDB


MODULES DETAILS
1.	USER MODULE
2.	ADMIN MODULE
3.	RENTER MODULE
4.	CATALOG MODULE
5.	BOOKING MODULE

1       USER MODULE	
1.1	    USER REGISTRATION 
1.2	    USER LOGIN
1.3	    USER PROFILE
1.3.1	FILTER 
1.3.2	REVIEW AND RATINGS
1.3.3	HISTORY OF PREVIOUS BOOKING

2	    ADMIN MODULE
2.1	    ADMIN LOGIN
2.2	    ADMIN PROFILE
2.2.1	VERIFICATION OF RENTERS
2.2.2	ADMIN DASHBOARD

3	RENTER MODULE
3.1	RENTER REGISTRATION
3.2	RENTER LOGIN
3.3	PROPERTY DETAILS
3.4	BOOKING DETAILS
3.5	BOOKING DATE UNIT

4	CATALOG MODULE
4.1	LOCATION DETAILS
4.2	PHOTOS
4.3	RENT AND DOWN PAYMENT
4.4	FACILITIES

5	BOOKING MODULE
5.1	RENT PERIOD
5.2	PAYMENT METHODS
5.3	PAYMENT

MODULE DESCRIPTION

User 
This module is operated by the user who is the tenant of the property and wants to take it on rent. The tenant should register, which will be authorized by the ADMIN. The tenant can search and book room according to dates of his choice. Once the tenant is done with the payment he can go through his profile, transactions.

Login/Registration
In this module the user goes through the login process if he is already a user or else can register 
Registration
	First Name
	Last Name
	Phone No
	Email ID

Room Searching 
in this module the user will search the area in which he wants to book the room and then go through the various properties available within that particular area.
Room Search
City 
Locality/Pincode 
Rooms

Select Room
Select property
Select sharing 
Book Room
Payments 


USER HOME
Roof Care   Ticket generation for any problem/housekeeping/complaints
In this section user can raise various issues facing by him so that admin can came to know about that and can resolve them as soon as possible

Profile 
In this section the user has his profile can update and view his or her details
	Personal details
	Professional details
	Emergency contact
	Documents submitted
Transactions
In this the user can see the upcoming and previous payments details.
	Upcoming payment
Previous payments




ADMIN MODULE
This Module is operated by the Admin User . The main function of the Admin is to ensure verification of properties listed by the Renters . The Admin has to sign in using his/her credentials at the Login page and will be directed to his profile page where he can take various actions .

1 ADMIN LOGIN
There will be no registration for Admin as it will be done at the back-end .The Login page will have a Username and Password field which the user must enter .On successful authentication ,this page directs to the profile page.

2 ADMIN PROFILE
A Standard profile page is displayed with Admin Details at one side and Notifications on another. Notifications area will have two tabs ;Verified and Not Verified .The Centre of the page will have an email like layout showing different verification requests. This section will change according to the tab selected; i.e. Verified or Not Verified.
2.1 VERIFICATION TABS
a)The Verified tab shows all the properties that has been verified and listed till date. Upon clicking an item ,it expands to reveal more details about the property like date of verification ,name of seller, contact number etc.
b)The Not Verified tab shows pending requests for verification .On clicking an item ,it expands to display options like Confirm Verification  and reject .

OWNER MODULE
This module is operated by the user who is the owner of the property and wants to give it for rent. The owner should register, which will be authorized by the ADMIN. The owner can upload room details, pictures, location, rent, amenities etc. which comes under owner module. The owner can list their properties, edit them and delete them. The owner also receives the bookings from the customers. The contact information of owner will also be provided. Once booked, the property will not be made available till its free. The owners can also view their history of bookings.

1 Owner Registration
From the Home Page, there will be a separate registration link for the renters. User can list rentals only after successful registration. While registration the following inputs will be taken 
•	Name
•	Mobile Number- will be verified by OTP
•	Email id
•	Address of Owner
•	Address Proof of Owner – to be uploaded
•	Username
•	Password
After validation, successful registration occurs.

2 Owner Login
From Home Page, owner can login by using the Login link for renters. If both username and password are correct, then successful login occurs and will be taken to the owner homepage. Forget password or username services are also provided via mobile number otp or email otp. Once otp is entered request for reset occurs. Log out facility is also provided.
Inputs – username, password

3 Property Listing
Owner can list their properties after login. For listing properties, a number of inputs must be provided like –
•	Property Address
•	Property Type – House, Apartment unit, Room
•	Property Features – Number of Bedrooms, Bathrooms, Balcony, Floors
•	Area Covered – sqft
•	Furnished status – fully, semi, none
•	Availability status – select date, immediately
•	Age of Construction
•	Monthly Rent
•	Security Deposit – set to one month’s rent
•	Lease Duration – minimum and maximum
•	Lease Terms – Electricity, trash etc
•	Description
•	Contact information
•	Amenities – A/c, Wheelchair access, wifi, garage parking, laundry, pets, any additional amenities
•	Photos and Media
•	Upload documents related to the property

After submitting the listing, it will be under screening process. During screening the admin will check and verify the property and if passes the screening, the listing occurs to other users. The screening process can take almost 48 hrs.
An owner can have more than 1 properties listed. He can edit and remove them as required.

4 Owner Profile
Owner can view all their properties, their current and future bookings. Previous bookings and the reviews and ratings can also be viewed. All details of the owner will be displayed here. It will have edit option also. If details of owner or properties are edited then it will undergo screening once again before being available for listing.

5 Booking Details
Once a customer books the home, the booking details will be displayed – duration of lease, number of people, details of the people who booked and the payment details.
All the current and future bookings will be shown separate from that of previous bookings. Payment will be received by the owner after 24-48 hrs of the house being occupied.



CATALOG MODULE:

1. Location: The tenant will enter the location by selecting city,state and entering pincode . On the basis of entered location , tenant can see available properties whoose location is same as enterd by tenant.

2.Photos:The photos are available for the properties suggested on the basis of chosen locationand other filters applied.

3.Rent and Pyment:Along with the photos information regarding rent per month and security amount information is also provided for the suggested properties.

4.Facilities: Suggestion of properties are also provided on the basis of facilities chosen by the users.The facilities include:

•	 Home Type:  Homes can be of three types- house ,apartment and bunglow.Tenant can choose the required type and can get suggestionon the basis of that.

•	BHK: Property can have 1 BHK, 2BHK,3BHK or 4BHK .User can choose from the list as per requirements.

•	Price:Tenant can choose the amount range within which they want to hire the property.

•	Parking:Tenant can choose yes or no for parking option.If they select 'yes' they will be suggested with properties having car parking available.

Tenant can choose different combination of these facilities to get their desired property.


PAYMENT AND BOOKING MODULE
Once the Buyer is done with selection of appropriate accomodation, he may proceed to payment option. Payment options will include Card payment, Netbanking and Cash Payment. Payment Amount may vary according to various factors such as Seller, ambience, facilities, duration of stay, Rating and Reviews. Certain amount needs to be paid as downpayment as per property norms. 

RENT PERIOD:
Longer the stay period, more will be rent. Once the user selects the accomodation, Buyer will have to agree to sign stay agreement with downpayment and monthly rent to be paid through various methods as listed below. 
PAYMENT METHODS:
Various payment methods may include payment through Card, Cash, App transfer or Netbanking. Monthly rent needs to be before 10th of every month. 
