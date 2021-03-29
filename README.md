# Vaccine Text NC
Get a text whenever a vaccine appointment becomes available in North Carolina.
Uses data aggregated by Vaccinespotter.org - credit to them for providing the API for usage!

# Parameters to Change
Twilio related
- account_sid
- auth_token 
- outphone: phone to send texts to. MUST BE VERIFIED with Twilio.
- fromphone: phone number assigned by twilio. 

General
- city_list: A list of cities to look for appointments in.
- view_times: If true, will print a list of vaccine times for each location in the console when run.
- success_sleep_mins: How many min to wait to look for new appts after finding appts
- failure_sleep_mins: How many min to wait to look for new appts after not finding appts
