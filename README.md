campaign-kit
=================

 [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy) 

1. Create a new instance of the app by clicking the 'Deploy to Heroku' button above, taking note of your app name. When it says 'Your app was successfully deployed', click View.
2. Create an account. Log in with the account details.
3. Visit `http://[APP NAME].herokuapp.com/import` to import some representatives, replacing [APP NAME] with your app name.
4. Return to the admin interface at `http://[APP NAME].herokuapp.com/admin`, click 'Campaigns' and create a campaign.
5. Click 'View/edit' to return to the campaign, scroll to the bottom and add some decisions (you'll probably want to use the 'Bulk create decisions' tool). Decisions are what link campaigns to representatives; a Decision implies 'this representative has to make a decision on this campaign issue', and thus the representative should be included in the postcode search for this campaign.
6. View your campaign at `http://[APP NAME].herokuapp.com/campaigns/[CAMPAIGN SLUG]`, replacing [CAMPAIGN SLUG] with your campaign slug.

Found this app useful? [Donate via Paypal](https://www.paypal.me/wordsandwriting)