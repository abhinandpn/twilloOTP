# OTP verification with Twilio and Golang
___
### Otp verification with twillio using gin frame workd in golang

>  Structure of code
  - api (structuring our API-related files)
  - cmd (structuring our application entry point)
  - data (structuring our application data)
___
 ### create a .env file and load this variable 
```d
 TWILIO_ACCOUNT_SID = "your Twilio account sid"
 TWILIO_AUTHTOKEN = "your twilio account authtoken"
 TWILIO_SERVICES_ID = "youw twilio account service id"
```
___
#### Api Request Format
___
_You can edit the Port and domain_
> Api Url : = http://localhost:8080/otp

```
{
  "PhoneNumber":"enter your number with country code"
}
```
> Api Url : = http://localhost:8080/verifyOTP
```
{
  "user":{
    "PhoneNumber":"enter your number with country code"
  },
    "code":"enter your OTP"
}
