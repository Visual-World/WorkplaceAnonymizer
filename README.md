# WorkplaceAnonymizer
## About
The anonymiser helps to clean up Workplace instances after staff deactivation from SSO. 
The Norwegian Refugee Council (NRC) is using Workplace from Facebook for internal communication with Okta as SSO, and in this configuration we have found the deactivated staff are not being automatically anonymized.
NRC has therefore built this bot, which ensures that personal details are anonymized as well as removes deactivated staff from Workplace groups.

## Limitation
Due to restrictions of the workplace API it is not possible to anonymize / delete the following information:
 - email address
 - profile pictures
 - public workplace group assignments


# License
The workplace anonyizer is published under the MIT License.
Please make sure: The usage of this tool is at your own risk. Anonymizer does not do any backups. There is no warrenty of any changes anonymizer does to your workplace profiles!

# Support
Workplace Anonymizer has been created by VISUAL WORLD for the NRC. NRC decided to make this tool open source.
If there is any assistence required or a whish of extended functionality, please contact us.
VISUAL WORLD also offers the posibility to install and configure workplace anonymizer on your workplace account incl. extended test mode via installation and monitoring. Please contact us for more details.
