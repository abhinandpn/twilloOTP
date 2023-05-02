# One-Time-Password(OTP) Verification API with Go and Twilio 
# Simple API 

1. Structure 
    - api (structuring our API-related files)
    - cmd (structuring our application entry point)
    - data (structuring our application data)

 ## create a .env file and load this variable 

   | ` TWILIO_ACCOUNT_SID = "your Twilio account sid" `

   | ` TWILIO_AUTHTOKEN = your twilio account authtoken `

   | ` TWILIO_SERVICES_ID = youw twilio account service id `


   # Request info
   - OTP sending  http://"localhost":8080/otp
      > {
          "PhoneNumber":"enter your number with country code"
        }
   - Verify OTP   http://"localhost":8080/verifyOTP
      > {
          "user":{
              "PhoneNumber":"enter your number with country code"
          },
            "code":"enter your OTP"
          }  

  NB : You can change the localhost in to your host