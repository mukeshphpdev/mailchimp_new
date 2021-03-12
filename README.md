Mailchimp Skill Challenge
==========================================
Welcome to the Mailchimp Skill Challenge! The purpose of this to authenticate mailchimp account using Oauth 2.0 and get access_token from mailchimp, using this access_token we can call for api's of mailchimp.  

## The Task
Your task is to create a laravel authentication for mailchimp and there is audience which means list and all contact will be synced in that particular selected list.
https://login.mailchimp.com/oauth2/metadata using this API call , will get metadata of account, this API json response contain key name "api_endpoint" (url prefix which using other API call)

You can get list of mailchimp lists using this API "https://us7.api.mailchimp.com/3.0/lists" 

