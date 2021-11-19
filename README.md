# ONLINE-BURSARY-MANAGEMENT-

helps one to get bursary notification, date of disbursement and amount deposited for every applicant.

## ONLINE BURSARY MANAGEMENT SYSTEM

This system is about bursary application web based application that will enable students to easily apply for Bursaries, get notification on their approval and tapproved certain amount of funds will be disbursed into their respective student bank accounts.

## Modules

My iBursary system has two major modules i.e User module and Admin module.

## User module

The user module contains sub modules that will guide the development of the web-based application. Sub-modules include:

### User authentication Mechanism i.e

This documentation is about implementing user's authentication mechanism for ibursary.
User Authentication is a security mechanism used to restrict unauthorized access to member only areas and tools on a given site.
Various considerations are followed when developing a user authentication mechanism.
in my project, i considered creating the mechanism by using certain sub-modules.these modules include;

1. User Registration(Sign up)
2. Login
3. Reset Password

## Registration

There are a whole bunch of new functions that I'll be using in coming up the register page(Form). Firstly, the strlen() function(string length), this returns the number of characters in a string allowing us to check how long strings are. Then the preg_match() function, this checks to see if the formatting of a string matches the formatting you specify (in this case being an email format). Finally, the mail() function, this sends an email from the server to any email of your choice, containing anything you want. This file will be saved as “register.php”

## Login

The user will be able to enter either their passwords or emails and then passwords to be granted authority to access their account. When the submit their forms, their inputs will be verified against the credentials stored in database. If username or email matches their password, they will be authorized and granted to access their site, otherwise, login attempt will be rejected.

## Reset password

A system is much better when it has a password reset feature. This I where the account holder(user) forgets the password and they are barred from accessing their accounts. The password reset feature enables them to reset their passwords by verifying the registration details in the database. A password reset utility added will be added to our login system.When the feature is used, If the user forgets their password, that is after several login attempts all fail, the system will prompt them if they want to reset password using their phone number or the email. If they use an email, the system will send them an email with a code same for the phone number. The user will then be needed to create another password that they won’t forget. The password will then be saved in the database for user login next time they want to login to the site. users can instantly reset their own passwords for their accounts.

### Home Page

1. System Name-iBursary
2. About Us
3. Apply
4. Notifications

## About us

ibursary is a computerised system that enables the online application of bursary funds to students.Due to high educational demand, education institution in Nairobi constituency have turned out to be too expensive for the ordinary peope.Some are forced to dropout of their educational career due to lack of enough money for school fees and other educational materials required.

## Apply

This bursary programme by the county government are accessed by filling an online application form or by going to a site accesible place i.e a cyber
Applicants should fully fill the application form with the help of guardians or parents.Some of tthe details required include,your full names,Name of school,Your admission number,the amount of fee you want to be paid,parents name,their identity number.
Application forms are then submitted after the full filling.The application forms would be proccesssed within a period of time,after this period,the successful applicants will be notified and have their fees paid in by the conty government.  

## Notifications

After the applicants forms are submitted,the applicants will be notified if either their bursary was approved or not,this is done by sending an sms notification through their phones.

### Admin module

1. Registration
2. Login
3. Password Reset
4. Applicant details Confirmation.
5. Notification for Eligibilty.(SMS)
6. Eligible amount for an applicant.
7. Date and time of disbursment.
8. Logout

### Registration

The administrator of the iBursary web based application is required to create an account so as to check whether an applicant(student) is eligible for the bursary award. They are required to use their credentials in order for the security mechanism to allow their access. In this case they'll require all their credentials for the system to be sure of validity and integrity of the admin.
After registration, the admin will be sent a confirmation email before being allowed to login to the site. The email will enable them to verify their account creation and also to confirm the account holder is not a robot or a schema.

### Login

The Admin is required to login to the site for full access. He/She will require to have registered first. For login they'll required thier username(email/username) and their set password. After login, they will directly be redirected to the site after the security mechanism is passed.

### Password Reset

The admin will also be able to reset their password if they have forgotten. A username will be required to reset the password. An email will be sent to their accounts to verify it is them. After integrity check, the verification message will include a system generated code that they will use to change and reset their password.

### Applicants Details Confirmation

It is the responsibility of the admin to check whether an applicant is truely in need of the funds or not. He will ensure to run a background check on the applicant to accertain their situation. If the details are complicated in that they do not match the requirememts of the qualification for the award of bursary then the applicant will be denied the award. If else, considering all conditions for the qualification, then the applicant will be awarded with the bursary allocation.
Since the list of applicants might be long, the selected candidates for qualification will be ticked with a green mark and for those not disqualified for the award, they will be marked with an (X) to make it easy for the awarding committee.

### Notification Of Eligiblity

The admin must be able to notify the applicant on the succesful application.
A Notification message using SMS format will be send to the applicants phone number notifying them using a Congratulatory message stating "Congratulations for Your Bursary application, You Have succesfully been awarded with (amount in KSH)". Then the funds will be deposited to their respective bank accounts simulataneously according to their posistion on the application list.
If by any chance the applicant does not have a bank acount, The site will run a check on their institution balances, pay the balance and the remaining amount after the fees is cleared is deposisted to their M-Pesa accounts.

### Eligible Amount for the Applicant

How much will an applicant be eligible for?
The amount for each respective applicant will de[pend with their instituition and the amount applierd for. Their details will determine their eligibilty. If an applicant requires for example ksh50,000, they will be awarded with available amount in the bursary fund allocation provided by the Treasury. If the amount is higher than that required, the applicant fees will be carried forward. If the funds are low, on their next application, they will be considered first priority and exact amount will be deposited to their bank accpounts.

### Date and time of Disbursement

The admin will communicate to the succesful applicants on the date for disbursement. To avoid anticipation among applicants, an exact date and time won't be used. The period will be communicated using weeks for example second week of March.

### Logout

After using the site, the admin will be able to logout their account to allow another admin in the same category to use the site. A logout button will vividly  be put at the end of the page. In the case the admin does not logout, after they close the site, they will be automatically be logged out to allow other user to sign in without inconviniences
