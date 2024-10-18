
# Django User Authentication System

This project provides a user authentication system using Django and Django REST Framework. It includes features such as user registration, login, profile management, password change, and password reset.

## Installation

- Clone the repository 
- Apply the migrations
- Create a superuser
- Run the development server

## Usage 

- User Registration
`[POST] /api/user/register/`
- User Login
`[POST] /api/user/login/`
- User Profile
 `[GET] /api/user/profile/`
- Change Password
 `[POST] /api/user/changepassword/`
- Send Password Reset Email
 `[POST] /api/user/send-reset-password-email/`
- Reset Password
 `[POST] /api/user/reset-password/<uid>/ <token>/`


## Email Configuration

To send password reset emails, you need to configure your email settings in the `settings.py` file. Make sure to set the `EMAIL_FROM` environment variable with your email address.

- EMAIL_BACKEND  
`'django.core.mail.backends.smtp.EmailBackend'`
- EMAIL_HOST  
`'smtp.your-email-provider.com'`
- EMAIL_PORT  
`587`
- EMAIL_USE_TLS  
`True`
- EMAIL_HOST_USER  
`'your-email@example.com'`
- EMAIL_HOST_PASSWORD  
`'your-email-password'`

## Register 

![Home Pages1](https://github.com/Shubh556/Django_Rest_Auth/blob/main/img/register.png?raw=true)

## Login 
![Home Pages1](https://github.com/Shubh556/Django_Rest_Auth/blob/main/img/Login.png?raw=true)

## View Profile

![Home Pages1](https://github.com/Shubh556/Django_Rest_Auth/blob/main/img/view%20profile.png?raw=true)

## Change Password

![Home Pages1](https://github.com/Shubh556/Django_Rest_Auth/blob/main/img/change%20password.png?raw=true)

## Send Reset Email

![Home Pages1](https://github.com/Shubh556/Django_Rest_Auth/blob/main/img/send%20reset%20email.png?raw=true)

## Reset Email Token 
![Home Pages1](https://github.com/Shubh556/Django_Rest_Auth/blob/main/img/reset%20email%20token.png?raw=true)

## Password Reset Successfull
![Home Pages1](https://github.com/Shubh556/Django_Rest_Auth/blob/main/img/successfull%20password%20reset%20.png?raw=true)


