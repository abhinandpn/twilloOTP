
# # OTP Verification API with Go and Twilio 

Otp verification with twillio using gin frame workd in golang

> Structure of code
    - api (structuring our API-related files)
    - cmd (structuring our application entry point)
    - data (structuring our application data)

 # create a .env file and load this variable 

   | ` TWILIO_ACCOUNT_SID = "your Twilio account sid" `

   | ` TWILIO_AUTHTOKEN = your twilio account authtoken `

   | ` TWILIO_SERVICES_ID = youw twilio account service id `


# Request Info
> Otp sending
    - {
          "PhoneNumber":"enter your number with country code"
      }
> Otp verifying
    - {
          "user":{
              "PhoneNumber":"enter your number with country code"
          },
            "code":"enter your OTP"
          } 
> NB : You can change the localhost in to your host