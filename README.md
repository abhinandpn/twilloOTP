<h1 class="code-line" data-line-start=1 data-line-end=2 ><a id="_OTP_Verification_API_with_Go_and_Twilio_1"></a># OTP Verification API with Go and Twilio</h1>
<p class="has-line-data" data-line-start="3" data-line-end="4">Otp verification with twillio using gin frame workd in golang</p>
<blockquote>
<p class="has-line-data" data-line-start="5" data-line-end="9">Structure of code<br>
- api (structuring our API-related files)<br>
- cmd (structuring our application entry point)<br>
- data (structuring our application data)</p>
</blockquote>
<h1 class="code-line" data-line-start=10 data-line-end=11 ><a id="create_a_env_file_and_load_this_variable_10"></a>create a .env file and load this variable</h1>
<p class="has-line-data" data-line-start="12" data-line-end="13">| <code>TWILIO_ACCOUNT_SID = &quot;your Twilio account sid&quot;</code></p>
<p class="has-line-data" data-line-start="14" data-line-end="15">| <code>TWILIO_AUTHTOKEN = your twilio account authtoken</code></p>
<p class="has-line-data" data-line-start="16" data-line-end="17">| <code>TWILIO_SERVICES_ID = youw twilio account service id</code></p>
<h1 class="code-line" data-line-start=19 data-line-end=20 ><a id="Request_Info_19"></a>Request Info</h1>
<blockquote>
<p class="has-line-data" data-line-start="20" data-line-end="32">Otp sending<br>
{<br>
“PhoneNumber”:“enter your number with country code”<br>
}<br>
Otp verifying<br>
{<br>
“user”:{<br>
“PhoneNumber”:“enter your number with country code”<br>
},<br>
“code”:“enter your OTP”<br>
}<br>
NB : You can change the localhost in to your host</p>
</blockquote>