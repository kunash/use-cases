# Use Case 1

## 1. User: Open Tinkercad page

**Subject:** User

## 2. Tinkercad: Click "Sign up with email"

**Subject:** Tinkercad

System redirects to sign-in page

## 3. User: Do something

**Subject:** User

## 4. Tinkercad: Identity displays sign-in form

**Subject:** Tinkercad

## 5. Identity: User submits sign-in form's step 1

**Subject:** Identity

Input data: Country, DateOfBirth

## 6. Identity: User types his username

**Subject:** Identity

System checks the username availability

## 7. Identity: User submits sign-in form's step 2

**Subject:** Identity

Input data: UserName
Password
ModeratorEmailId
ReturnUrl
Find OAuthConsumer by consumerKey
Create domain user - UserController.MapCoppaSignUpModelToDomainUser
Create ChildAccountModerationInfo and ModeratorAuthorization records, Create Sentinel
Accept Terms and Conditions
Send approval request email to parent

## 8. User: Identity redirects to the requesting app

**Subject:** User

redirect is performed using ReturnUrl
