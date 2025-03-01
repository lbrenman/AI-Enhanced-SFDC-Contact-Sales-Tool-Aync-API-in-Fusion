# Amplify Fusion Enhanced Contacts Aync API

Enhanced contact Async API created in Amplify Fusion that demonstrates how to leverage the OpenAI API in a sales operation example. New contacts are retrieved from Salesforce using Fusion's Salesforce connector's Push Topic feature and enhanced using the OpenAI API and a prompt that provides the contact details including contact name, account name and industry and recent activity for the contact. Currently the recent activity is retrieved from the contact's description field. In a real work example, you can look at the contacts activity and other related data in Salesforce. The prompt provides the data and requests insights, talking points and next steps as illustrated below:

![Imgur](https://i.imgur.com/WMmnzuf.png)

* You can read more about how the prompt was engineered as well as the details of the OpenAI API call and response [here](https://gist.github.com/lbrenman/67ee78c716210448cb2605c8f5d6b2b7).
* The Open API Specification used to create the API in Fusion is in this repo in the file `NewContactEnhanced.yaml` [here]().
* You can see the use case in action in a Nodejs Web app [here](https://github.com/lbrenman/new-enhanced-contact-ayncapi-nodejs-webapp)
* Some screen shots from the Fusion project are shown below:
![Imgur](https://i.imgur.com/ECPvkRX.png)
![Imgur](https://i.imgur.com/RNEJlkm.png)
![Imgur](https://i.imgur.com/8PQ9zq3.png)