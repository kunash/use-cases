# Use Case 1

## User opens Tinkercad page 3415

User

## User clicks "Sign up with email"

User

System redirects to sign-in page

## Identity displays sign-in form

Tinkercad

## User submits sign-in form's step 1

Identity

Input data: Country, DateOfBirth

## User types his username

Identity

System checks the username availability

## User submits sign-in form's step 2

Identity

Input data: UserName
Password
ModeratorEmailId
ReturnUrl
Find OAuthConsumer by consumerKey
Create domain user - UserController.MapCoppaSignUpModelToDomainUser
Create ChildAccountModerationInfo and ModeratorAuthorization records, Create Sentinel
Accept Terms and Conditions
Send approval request email to parent

## Identity redirects to the requesting app

User

redirect is performed using ReturnUrl
