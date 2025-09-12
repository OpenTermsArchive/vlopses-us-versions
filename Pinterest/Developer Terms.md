Developer guidelines


========================

Our mission
===========

At Pinterest, our mission is to bring everyone the inspiration to create a life they love. As a developer, you can play an important role in making that happen. These are the guidelines for what we do and don’t allow when building applications and services with the Pinterest Materials. We require developers to follow these guidelines as well as our other terms and policies, such as our [Developer and API Terms of Service](https://developers.pinterest.com/terms/) and our [Community Guidelines](http://policy.pinterest.com/community-guidelines).

If we remove your app for violating our guidelines, we will notify you. If you come across a developer application that is in violation of our guidelines, please [let us know](https://help.pinterest.com/contact).  
  

The basics
==========

No matter what your application will do, you must follow these fundamental principles:

* Be honest and transparent with Pinterest and with your end users about the functions and features of your service. Don’t confuse, mislead, or surprise anyone.
* Except for campaign analytics information accessed about your account, you may not store any information accessed through any Pinterest Materials including the API. Instead, call the API each time you need to access information.
* Only access someone's account with authorization, for example by using an access token. Do not solicit or collect login credentials or use login credentials to access other people’s accounts or take actions on their behalf.
* Only use information from someone’s account to provide services to that person.
* Don't combine someone's account information with information from other people's accounts or with information from other services.
* Don't share or sell information from our API with a third party, including another advertising service. (It's okay to share information with the person from whose account that information came.)
* Keep your API access credentials private. Do not use someone else’s API credentials, and do not allow anyone else to use yours.
    * End users may request API access credentials for use with a “bring-your-own-key” application, as long as the application stores the end user’s API credentials locally (not server-side) and the application complies with all other policies and guidelines. For example, the application must not solicit Pinterest user passwords, session cookies, etc.
* Don’t try to evade our policy enforcement systems. For example, if we remove your app, don’t try to reconnect the same or a substantially similar app using a different account or under a different name.
* Follow any instructions in our technical documentation.
* You must have a privacy policy that’s consistent with all applicable laws. You’ll need to include a link to your privacy policy when you apply for API access.

What to do
==========

Acceptable uses of the Pinterest Materials such as our developer tools and APIs include building integrations such as:

* Advertising tools, like apps for managing campaigns across multiple channels
* Audience tools, which help advertisers use advanced targeting features
* Content marketing tools, like Pin schedulers
* Creative tools, like apps for designing images or editing video
* Creator platforms, like those that facilitate collaboration between Creators and brands
* Dynamic creative tools, like apps that automate the creation of content
* Feed management tools, which help end users optimize their product listings
* Merchant platforms, like those that host ecommerce stores
* Measurement tools, which can help advertisers understand the effectiveness of their campaigns
* Shoppable experience tools, like those that allow users to purchase items shown in your content

You can browse our [Partners site](https://business.pinterest.com/pinterest-partners/) to learn more about some of the existing integrations that developers have built on the Pinterest Platform. Our [Developers site](https://developers.pinterest.com/) contains documentation to help you get started as well as best practices for working with the Pinterest Platform.  
  

What not to do
==============

Unacceptable uses of the Pinterest Materials such as our developer tools and APIs include:

* Creating or providing an app for the purpose of violating Pinterest policies.
* Taking actions on behalf of end users without their specific knowledge and consent. This includes but is not limited to actions like: modifying Pinner profiles; creating, saving and editing Pins; following and unfollowing; sending messages; and making comments.
* Offering features that enable end users to automatically initiate actions without specifically considering each action.
    * For example, if your app allows end users to schedule Pin publishing, the end user must choose each Pin to be published. Similarly, if your app allows end users to follow accounts on Pinterest, the end user must choose each account to follow.
    * Put simply, end users are responsible for the actions that they take on Pinterest, and we want those actions to be genuine—so don't build automations that could lessen the authenticity of engagement on Pinterest or lead end users to perform an action that they didn't understand or intend.
* Attempting or claiming to provide platform insights, benchmarking, or competitor research features unless you have explicit written authorization from Pinterest. For example, don’t make statements about Pinterest’s overall performance related to a competitor or to industry benchmarks, and don’t do the same for brands or accounts.
* Using any automated means or form of scraping or data extraction to access information from Pinterest, except as expressly permitted by Pinterest.
* Misrepresenting your relationship with Pinterest or your level of access to the Pinterest Materials.
* Using information from Pinterest to target people with advertising outside of Pinterest, whether directly or bundled with third-party data. For example, do not bundle or sell content or data from Pinterest on other advertising networks, via data brokers, or through any other advertising or monetization service.
* Using your API access or developer tools to test Pinterest’s rate limits or other abuse prevention systems without specific authorization from Pinterest.
* Offering any feature to circumvent Pinterest restrictions. For example, don’t offer a feature that would allow end users in a region to access content that Pinterest has restricted from that region (a.k.a. geoblocked).
* Requiring or incentivizing engagement. For example, don’t require end users to create or save a Pin to a certain website, or to save a certain Pin in exchange for a benefit.
* Attempting to evade our consent mechanisms but gathering your own user consent for API-provided information.
* Apps intended for children under the age of 13 are not permitted.  
      
    

Publishing content
==================

If your app publishes content from Pinterest, you must:

* Link Pins back to their source on Pinterest (e.g. https://www.pinterest.com/pin/424605071126047814/), and make sure it’s clear that the content comes from Pinterest.
* Not cover or obscure content from Pinterest. For example, don’t apply filters to Pins.
* Not create new content from Pins that can be distributed on your app or service.  
      
    

Audience & advertiser services
==============================

If you provide audience onboarding, you must comply in particular with the user consent obligations and data restrictions in the [Ad Data Terms](https://policy.pinterest.com/ad-data-terms) and [Advertising Guidelines](https://policy.pinterest.com/advertising-guidelines).

If advertisers will use data you’ve provided to them for online behavioral advertising, you also need to:

* Give clear and prominent notice to everyone you collect data from letting them know that their information will be shared with third parties for online behavioral advertising, and gather any necessary consents.
* Give instructions on how to opt out of the use of their information for online behavioral advertising, for example through the AdChoices website optout.aboutads.info.
* Not send Pinterest information about people who've opted out or not opted in.
* Regularly update data to remove people who've opted out.

If you use information from any Pinterest API to provide an advertising service, you must comply with our [Ad Data Terms](https://policy.pinterest.com/ad-data-terms) and [Advertising Guidelines](https://policy.pinterest.com/advertising-guidelines), and also do the following:

* If you report last-click attribution metrics, next to them with equal prominence you must show multi-touch metrics that divide attribution equally among each attributed service.
* Clearly and separately show the fees you charge for Pinterest advertising and the fees that Pinterest charges (both the absolute amount and by billing metrics, like CPM or CPC), and don't combine your fees with ours.
* Don't use information from our API except to serve and evaluate the performance of ads on Pinterest.  
      
    

Regarding app abuse
===================

We want developer applications to help everyone find the inspiration to create a life they love. Apps created for abuse (for example, apps created to spread spam) are not permitted. In addition, we expect developers to be responsible partners in abuse prevention and to take steps to mitigate the risk of their app being used in harmful ways by end users. This includes, for example, not offering features that facilitate spamming Pinterest or other users. We may remove apps in order to protect Pinners at any time.