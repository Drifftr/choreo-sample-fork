# COVID-19 Statistics to Email
## Use case
It is important to be aware about the COVID-19 situation in a specific country. We may need to get information about 
the reported COVID-19 cases in that country. This sample can be used to email the COVID-19 cases per million in a specific country of interest.

## Configuration
Create a file called `Config.toml` at the root of the project.

### Config.toml
```
[<ORG_NAME>.covid19_statistics_to_email]
country = "<COUNTRY_CODE>"
emailAddress = "<RECIPIENT_EMAIL_ADDRESS>"
```
* COUNTRY_CODE - Code of the country (e.g: AFG, ALB, LKA) of interest.
* RECIPIENT_EMAIL_ADDRESS - Email address of the recipient to receive generated email. 

## Testing
Run the Ballerina project created by the integration sample by executing `bal run` from the root.

Once successfully executed, an email will be received to the email specified with requested statistics.
