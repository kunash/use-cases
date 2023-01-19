# Use Case 1

## 1. User opens Tinkercad page 341

User

## 2. User clicks "Sign up with email"

User

System redirects to sign-in page

## 3. Do somethin

User

## 4. Identity displays sign-in form

Tinkercad

## 5. User submits sign-in form's step 1

Identity

Input data: Country, DateOfBirth

## 6. User types his username

Identity

System checks the username availability

## 7. User submits sign-in form's step 2

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

## 8. Identity redirects to the requesting app

User

redirect is performed using ReturnUrl
