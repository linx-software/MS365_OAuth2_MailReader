# Mail Reader for Office365 using IMAP and OAuth2

## Description
A simple solution to read mails from a Office 365 mail box using OAuth2 Authentication. The solution retrieves an access token via the Azure API and then uses that token to read mails from a specified mailbox. Please note that OAuth2 needs to be configured on your Azure/Office365 account and necessary permissions needs to be applied for this to work

## Installation
Ensure that you set up the OAuth2 configuration on your Azure/Office365 account correctly in order for this to work. you can try the [following tutorial](https://www.emailarchitect.net/eagetmail/sdk/html/object_oauth_ews_service.htm)

You will need:
- TenantID
- ClientID
- ClientSecret
- EmailAddress that has IMAP enabled and correct permissions

## Usage
Add the details into the variables declared above in the OAuth2Mail function:
- TenantID
- ClientID
- ClientSecret
- EmailAddress 

Add your logic to the function to manipulate/use the email as required. You can remove the 'YourLogicGoesHere' component as it is a placeholder.

## Contributing

For questions please ask the [Linx community](https://linx/software/community). 

## License

[MIT](https://github.com/linx-software/template-repo/blob/main/LICENSE.txt)
