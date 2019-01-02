# Account Credentials

This guide will cover the different credentials for use with [Bandwidth's Dashboard](https://dashboard.bandwidth.com).

Specific information for finding your credentials can be found [here](https://support.bandwidth.com/hc/en-us/articles/360014110974).


## Assumptions

* You have a [Voice and Messaging](https://app.bandwidth.com) account
* You have a [Phone Number](https://dashboard.bandwidth.com) account

## Credential overview

| Credential Name                        | Description                                                                                                                                                                                                                                                                                          | Example                              |
|:---------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------|
| `username`                             | Your **username** to *log in* to the [Bandwidth Dashboard](https://dashboard.bandwidth.com)                                                                                                                                                                                                          |  `jdoe`                               |
| `password`                             | Your **password** to *log in* to the [Bandwidth Dashboard](https://dashboard.bandwidth.com)                                                                                                                                                                                                          |  `correct-horse-battery-staple`       |
| `accountId`                            | Your unique account **id**.  The `accountId` is used as part of the url to make API requests. <br> Ex: `https://dashboard.bandwidth.com/api/accounts/{accountId}/`                                                                                                                                   |  `920012`                             |
| `subAccountId` <br> -or- <br> `siteId` | Any **id** for any sub-account.  The `subAccountId` is used as part of the url to make some API requests. <br> Ex: `https://dashboard.bandwidth.com/api/accounts/{accountId}/sites/{sideId}` <br><br> ℹ️ *Sub-accounts* are also known as *sites* <br> ℹ️ An *account* can have multiple *sub-accounts*|  `13606`                              |
| `userId`                               | Your Bandwidth Account ID. The `userId` is used as part of the url to make API requests. This may be the same value as your accountId. <br> EX: `https://api.catapult.inetwork.com/v2/users/{userId}/messages` <br><br> ⚠️ This **IS NOT** the same as your log in! ⚠️                                                                                |  `u-sd89g93epa2nb4euazd83kv8` OR `920012` |
| `apiToken`                             | Your unique api token.  The `apiToken` is used as the **username** to authenticate to the API as part of the basic auth scheme                                                                                                                                                                       |  `t-df83jkbv89aokuoxllf833c`          |
| `apiSecret`                            | Your unique api secret.  The `apiSecret` is used as the **password** to authenticate to the API as part of the basic auth scheme                                                                                                                                                                     |  `j54935lddasl837592356aasdf8359hlo3` |