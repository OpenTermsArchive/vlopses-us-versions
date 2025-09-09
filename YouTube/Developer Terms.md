YouTube API Services - Developer Policies

Stay organized with collections Save and categorize content based on your preferences.


===================================================================================================================================

**Note:** [Complying with the YouTube Developer Policies](https://developers.google.com/youtube/terms/developer-policies-guide) provides guidance and examples to help you ensure that your API clients follow specific portions of the YouTube API Services [Terms](https://developers.google.com/youtube/terms/api-services-terms-of-service) and [Policies](https://developers.google.com/youtube/terms/developer-policies) (API TOS). The guide offers insight into how YouTube enforces certain aspects of the API TOS, but it does not replace any existing documents.

This document (the "**YouTube API Services Policies**" or "**Policies**") sets out the policies that you need to follow when accessing or using [YouTube API Services](#definition-youtube-api-services) in your service, product, or application. These Policies help you access and use [YouTube API Services](#definition-youtube-api-services) in ways that are consistent with YouTube's interests and that respect and foster the growth of YouTube's community of creators, viewers, content rights holders, and advertisers.

In addition to defining policies, this document explains some of the underlying principles that YouTube followed in creating these Policies. It also offers examples that demonstrate how these Policies would apply in practice.

Please note that this is a legal document and that these Policies are a component of the [Agreement](#definition-agreement), so you must comply with them. YouTube reserves the right to change these Policies, and your continued access to, or use of, [YouTube API Services](#definition-youtube-api-services) constitutes your agreement to and acceptance of any such changes. Policy changes, like changes to the YouTube API Services [Terms of Service](#definition-terms-of-service), will be documented in the [Terms of Service Revision History](https://developers.google.com/youtube/terms/revision-history), and you can subscribe to the [RSS feed](https://developers.google.com/static/youtube/terms/feeds/api-services-terms-of-service-revision-history.xml) for that revision history to be notified of any such changes.

I. Terminology and style
------------------------

This is a legal document that specifies policies about allowed or prohibited actions. As such, it uses certain terms to specifically indicate whether you can or cannot do something. With that in mind, the following terms are used to explain your requirements as related to these Policies:

1. The terms **must** and required refer to absolute requirements.
2. The term **must not** refers to an absolute prohibition.
3. The terms **should**, **should not**, **recommend**, and **recommended** indicate that the statement describes a general best practice. While these terms suggest certain actions or behaviors, they acknowledge that you might decide to follow a different course based on specific aspects of your use case.
4. The term **may** indicates that an action is optional and left entirely to your discretion or, depending on the context in which it is used, to YouTube's discretion.

In addition, the [Definitions](#iv.-definitions) section that concludes this document identifies other terms that have a very specific meaning when used in this document. For your convenience, this document uses a special style for those terms to so that you can easily identify them in context and link to their definitions.

II. Software Development Principles
-----------------------------------

These principles underlie many of the policies in this document. Even though they might not cover every policy, if you violate or your [API Clients](#definition-api-client) violate any of these principles, you are likely also violating the terms of the [Agreement](#definition-agreement). That said, if local law requires you to do something other than what is stated in these policies -- for example, to store data for a particular length of time -- you should comply with that law.

1. **Build high-quality applications and maintain them.**
    
    Build stable, easy-to-use, feature-rich [API Clients](#definition-api-client) that bring significant additional value to the YouTube ecosystem and its users. Promptly update [API Clients](#definition-api-client) as the features offered in [YouTube API Services](#definition-youtube-api-services) change.
    
2. **Be honest and transparent.**
    
    This principle applies to all facets of [API Clients](#definition-api-client) and the way that they interact with users as well as with YouTube. In keeping with this principle, be clear about who you are and what your [API Client](#definition-api-client) does. Don't engage in any deceptive activity or messaging related to your identity, your data collection, storage, sharing, use and deletion practices, actions that your [API Client](#definition-api-client) takes on users' behalf, or anything else. Be honest and do not mislead or confuse users in the way you use and present data.
    
3. **Give users control.**
    
    Building on the importance of transparency, this principle dictates that users must be aware of and have actively consented to the actions that an [API Client](#definition-api-client) takes on their behalf. It means that users know about and have final authority over any actions the [API Client](#definition-api-client) takes to insert, share, update, or delete their data. It also means that each [API Client](#definition-api-client) must provide a privacy policy that clearly informs users about the information that the [API Client](#definition-api-client) accesses, collects, stores, shares, and otherwise uses.
    
4. **Respect users' privacy.**
    
    Make sure that your data collection, storage, use, security, and deletion policies and practices protect users. Don't allow unauthorized access to, or use of, user data. Don't store user data indefinitely, and provide a clear, straightforward process for them to delete data in your possession. Finally, don't, and do not make attempts to, request, collect, or store users' YouTube login credentials.
    
5. **Be a good citizen.**
    
    Don't create [API Clients](#definition-api-client) that encourage or enable people to abuse, threaten, or harass each other. Don't use, distribute, or promote viruses, spyware, malware, or other bad stuff. Don't break the law or encourage or enable others to do so. Hopefully, this is all common sense.
    

III. General Developer Policies
-------------------------------

### A. API Client Terms of Use and Privacy Policies

1. [API Clients](#definition-api-client) must display a link to YouTube's Terms of Service ([https://www.youtube.com/t/terms](https://www.youtube.com/t/terms)), and they must also state in their own terms of use that, by using those [API Clients](#definition-api-client), users are agreeing to be bound by the YouTube Terms of Service.
    
2. Each [API Client](#definition-api-client) must require users to agree to a privacy policy before users can access the [API Client's](#definition-api-client) features and functionality. The privacy policy must:
    
    1. be prominently displayed and easily accessible to users at all times,
        
    2. notify users that the [API Client](#definition-api-client) uses [YouTube API Services](#definition-youtube-api-services),
        
    3. reference and link to the Google Privacy Policy at http://www.google.com/policies/privacy,
        
    4. clearly and comprehensively explain to users what user information, including [API Data](#definition-api-data) relating to users, the [API Client](#definition-api-client) accesses, collects, stores and otherwise uses,
        
    5. clearly and comprehensively explain how the [API Client](#definition-api-client) uses, processes, and shares the user information described in section (III.A.2.e), including how the information is shared with either internal or external parties,
        
    6. disclose, if it does so, that the [API Client](#definition-api-client) allows third parties to serve content, including advertisements,
        
    7. disclose, if it does so, that the [API Client](#definition-api-client) stores, accesses or collects (or allows third parties to do so) information directly or indirectly on or from users' devices, including by placing, accessing or recognizing cookies or similar technology on users' devices or browsers,
        
    8. if the [API Client](#definition-api-client) accesses or uses [Authorized Data](#definition-authorized-data), explain that, in addition to the [API Client's](#definition-api-client) normal procedure for deleting stored data, users can revoke that [API Client's](#definition-api-client) access to their data via the Google security settings page at [https://security.google.com/settings/security/permissions](https://security.google.com/settings/security/permissions), and
        
    9. if the [API Client](#definition-api-client) uses [Authorized Data](#definition-authorized-data), explain how users can contact the [API Client](#definition-api-client) owner or developer with questions or complaints about the [Client's](#definition-api-client) privacy practices.
        

### B. Maintainability and Deprecation

1. [API Clients](#definition-api-client) must use the most recent versions of [YouTube API Services](#definition-youtube-api-services). This means that you must be able to update [API Clients](#definition-api-client) when newer versions of [YouTube API Services](#definition-youtube-api-services) are released. Non-website [API Clients](#definition-api-client), like mobile apps or installed applications, must be capable of being remotely updated to use the most recent versions of [YouTube API Services](#definition-youtube-api-services). You must update your [API Clients](#definition-api-client) to the most recent versions of the [YouTube API Services](#definition-youtube-api-services) within a specified time period if required by YouTube from time to time (e.g. for critical updates).
    
2. When YouTube intends to make backward incompatible changes to the [YouTube API Services](#definition-youtube-api-services), such changes will be documented in the [Terms of Service Revision History](https://developers.google.com/youtube/terms/revision-history), and you can subscribe to the [RSS feed](https://developers.google.com/static/youtube/terms/feeds/api-services-terms-of-service-revision-history.xml) for that revision history to be notified of any such changes.
    
3. You must promptly update non-deprecated [API Clients](#definition-api-client) to use newer versions of [YouTube API Services](#definition-youtube-api-services) as those versions are released.
    
4. You must update deprecated versions of your [API Clients](#definition-api-client) to clearly indicate to users that some functions or features of [YouTube API Services](#definition-youtube-api-services) might stop working due to the [API Clients'](#definition-api-client) deprecated status.
    

### C. Implementing YouTube Features

1. [API Clients](#definition-api-client) must also comply with the [Requirements for Minimum Functionality for YouTube API Services](https://developers.google.com/youtube/terms/required-minimum-functionality) ("**RMF**"). In addition, [API Clients](#definition-api-client) must not place any limitations on the YouTube functionality required by the RMF.
    
    For example, the RMF states that an [API Client](#definition-api-client) that enables users to upload videos to YouTube must enable those users to set a title for each uploaded video. YouTube's video title field has a maximum length of 100 characters, and an [API Client](#definition-api-client) must not set a shorter maximum length for that field.
    
2. Any [API Client](#definition-api-client) feature that initiates a user action related to a YouTube resource must be:
    
    1. clearly and unequivocally identifiable as a YouTube action,
    2. distinct and not mixed with your [API Client's](#definition-api-client) functionality, and
    3. clearly initiated by the user.
    
    Examples of YouTube resources include videos, channels, playlists, playlist items, and subscriptions. Examples of actions include playing a video, liking a video, adding a video to a playlist, and subscribing to a channel.
    
3. [API Clients](#definition-api-client) that perform write operations may suggest parameter or property values, but users must have final control over the data that will be published to [YouTube Applications](#definition-youtube-applications). Similarly, [API Clients](#definition-api-client) must not modify user-provided values before sending them to YouTube by truncating, appending, or otherwise altering those values unless the user has explicitly consented to such changes.
    
    [API Clients](#definition-api-client) that suggest values for text fields, like video titles or descriptions, must incorporate relevant keywords into those values. For example an [API Client](#definition-api-client) that suggests video titles should not generate the same default titles for all users.
    
    These examples illustrate how this policy would apply to an [API Client](#definition-api-client) that uploads videos to YouTube:
    
    1. The [API Client](#definition-api-client) may suggest a video description or pre-populate the video description. However, it must not add information to the video description after it is submitted by the user and before it is sent without the user's prior consent. For example, the [API Client](#definition-api-client) must not append the recording date, [API Client](#definition-api-client) name, or any other text unless the user has explicitly consented to such changes.
        
    2. An [API Client](#definition-api-client) may provide an option to translate a video title to other languages. However, the [API Client](#definition-api-client) must not add any such translations without the user's consent. In addition, if the [API Client's](#definition-api-client) default behavior is to enable the option to translate the video title, it must clearly present to the user an easy way to disable that behavior.
        
4. [API Clients](#definition-api-client) must clearly indicate how user-provided data will be used on YouTube.
    
    This policy is particularly relevant for [API Clients](#definition-api-client) that interface with multiple services and platforms since there may be functional or labeling differences between those services and platforms.
    
    For example, an [API Client](#definition-api-client) enables users to add comments about videos to multiple platforms, including YouTube. Each platform uses a different name to refer to the comment text. So, if the [API Client](#definition-api-client) labels the field "Feedback" in its comment form, it needs to clearly indicate that that value corresponds to the comment text on YouTube.
    
5. [API Clients](#definition-api-client) that use search functionality provided by [YouTube API Services](#definition-youtube-api-services) must not modify or replace the text, images, information, or other content of, the search results returned by those Services.
    
    For example, [API Clients](#definition-api-client) must not merge or intermix results from sources other than YouTube and present them as YouTube search results.
    
6. An [API Client](#definition-api-client) should not limit or reduce the functionality of a YouTube feature unless that limitation is a core aspect (as described in the examples below) of the [API Client](#definition-api-client) itself and that YouTube feature is not required by the RMF ("**Permitted Feature Limitation**").
    
    1. **Example 1: Permitted Feature Limitation**
        
        The YouTube Data API service allows a video uploader to provide translations of a video's title. Generally speaking, an [API Client](#definition-api-client) that implements this feature should allow uploaders to translate video titles to any language that YouTube supports. However, an [API Client](#definition-api-client) that is specifically designed to teach users to speak French and that offers a range of features specific to French translations might be justified in only offering users the option to upload French translations of video titles.
        
    2. **Example 2: Non-permitted Feature Limitation**
        
        A second [API Client](#definition-api-client) supports video uploading to YouTube and two other platforms, and all of those platforms allow the uploader to provide translations of the video's title. However, while YouTube supports more than 70 languages, the other two platforms each support half that number, and the three platforms support 25 languages in common. If the [API Client](#definition-api-client) supports only those 25 languages for translation, then that is a non-permitted feature limitation because the limited set of language options is not a core aspect of the [API Client](#definition-api-client). Instead, the [API Client](#definition-api-client) must offer the full range of languages that YouTube supports.
        
7. [API Clients](#definition-api-client) with Permitted Feature Limitations must explain to users why each limitation is in place and make clear that the limitation is not imposed by YouTube. In many, if not all, cases, there are different ways that an [API Client](#definition-api-client) could provide that information, and you should choose an appropriate method for your [API Client](#definition-api-client). Within this explanation, an [API Client](#definition-api-client) should provide a mechanism for users to access the full feature (such as linking to YouTube Creator Studio or providing an expandable menu within the API Client).
    
    In the example 1 above, the [API Client](#definition-api-client) could explain that video uploaders can add translations for other languages in the YouTube Creator Studio and provide a link to that functionality.
    
8. [API Clients](#definition-api-client) that offer features sourced from multiple services and platforms should offer feature parity to the extent that it exists across those sources, providing user choice. When [API Clients](#definition-api-client) include features that are supported on YouTube and on other platforms, [API Clients](#definition-api-client) must not consistently present YouTube features in a detrimental way (e.g., by only providing those features from other platforms).
    
    For example, suppose an [API Client](#definition-api-client) allows users to upload videos to YouTube and three other platforms, and all of those platforms support the ability to upload captions. If the [API Client](#definition-api-client) also supports caption uploading, then it must support that feature for YouTube.
    

### D. Accessing YouTube API Services

1. API Credentials
    
    To access or use some [YouTube API Services](#definition-youtube-api-services), you must first use the [Google Developers Console](https://console.cloud.google.com/) ([https://console.cloud.google.com/](https://console.cloud.google.com/)) to create [API Credentials](#definition-api-credentials) for your [API Project](#definition-api-project). Those credentials enable Google and YouTube to link API activity to a particular [API Project](#definition-api-project) and [API Client](#definition-api-client).
    
    In addition to creating [API Credentials](#definition-api-credentials), the Developers Console might require you to provide certain other information, such as identification or contact details, before you can access or use the [YouTube API Services](#definition-youtube-api-services) associated with those credentials. YouTube reserves the right to require you to provide additional information to continue to access or use [YouTube API Services](#definition-youtube-api-services).
    
    If you need to create [API Credentials](#definition-api-credentials) to access or use a specific YouTube API service, the documentation for that service explains how to create those credentials. For example, the [YouTube Data API service](https://developers.google.com/youtube/registering_an_application), [YouTube Reporting API service](https://developers.google.com/youtube/reporting/guides/registering_an_application), [YouTube Analytics API service](https://developers.google.com/youtube/reporting/guides/registering_an_application), and [YouTube embedded player](https://developers.google.com/youtube/terms/required-minimum-functionality#embedded-player-api-client-identity) all document steps for creating [API Credentials](#definition-api-credentials). Those steps generally differ slightly from one API service to another. For example:
    
    * Some services only support authorized API requests, while others support authorized and non-authorized requests.
        
    * Services often support multiple access scopes. Each scope specifies the resources that an [API Client](#definition-api-client) can retrieve, insert, update, or delete on the user's behalf. Scopes enable [API Clients](#definition-api-client) to only request access to the resources they need, and scopes also enable users to control the amount of access that they grant to those Clients.
        
    
    The following policies also apply to access and use of [YouTube API Services](#definition-youtube-api-services):
    
    1. You must not mask or misrepresent your identity or your [API Client's](#definition-api-client) identity when accessing or using [YouTube API Services](#definition-youtube-api-services) or when creating an [API Project](#definition-api-project) or [API Credentials](#definition-api-credentials).
        
    2. You must only use [API Credentials](#definition-api-credentials) assigned to you and to your [API Project](#definition-api-project) to access [YouTube API Services](#definition-youtube-api-services). Similarly, you must not use any other means to mask or misrepresent your [API Client's](#definition-api-client) access to, or usage of, [YouTube API Services](#definition-youtube-api-services).
        
    3. If your [API Client](#definition-api-client) needs to create [API Credentials](#definition-api-credentials) to access or use [YouTube API Services](#definition-youtube-api-services), you must create exactly one (1) [API Project](#definition-api-project) for that [API Client](#definition-api-client). Those [API Credentials](#definition-api-credentials) are intended to be used exclusively by the associated API Client, which means that you must not use that one (1) [API Project](#definition-api-project) for multiple [API Clients](#definition-api-client).
        
    4. You may share your [API Credentials](#definition-api-credentials) with agents operating solely on your behalf and under a written duty of confidentiality. However, you must not share or disclose your [API Credentials](#definition-api-credentials) to any other third party, allow access to or use of your [API Credentials](#definition-api-credentials) by any other third party, or embed your [API Credentials](#definition-api-credentials) in open source projects.
        
2. User Authentication and Authorization
    
    Authentication and authorization refer to the process by which users identify themselves and consent to allow an [API Client](#definition-api-client) to access certain user-specific data. Some [YouTube API Services](#definition-youtube-api-services) do not support access to user-specific data and therefore, do not require any authorization, others require authorization for some requests or data, and still others require authorization for all requests. For example:
    
    * The YouTube IFrame Player API service, which lets you embed videos in a website, does not require authorization just as users do not need to log in to the YouTube website to watch a video.
    * The YouTube Data API service requires authorization for some actions. For example, an [API Client](#definition-api-client) can search for public videos but does not need user authorization to do so. However, an [API Client](#definition-api-client) does need user authorization to upload a video to the user's YouTube channel.
    * The YouTube Analytics API service and YouTube Reporting API service require authorization for all actions.
    
    1. Authentication
        
        1. [API Clients](#definition-api-client) must not (and must not attempt to) obtain, proxy, request, collect, modify, cache, store, or use any information that the user provides or that YouTube displays to the user during authentication processes, including YouTube user account login credentials like usernames and passwords.
            
        2. [API Clients](#definition-api-client) must obtain user consent in accordance with the applicable laws and only request access to authorization scopes that they currently use. The access that an [API Client](#definition-api-client) requests should have a direct and transparent benefit to users of that Client. Do not try to future-proof your access to data by asking for permissions that would enable features that you have not yet built.
            
            For example, the YouTube Data API service supports one authorization scope that grants access to read data and another that grants access to read and write data. If a user granted an [API Client](#definition-api-client) access to the first scope, that [API Client](#definition-api-client) would be able to retrieve information about the current user's YouTube channel. However, if a user granted the [API Client](#definition-api-client) access to the second scope, the [API Client](#definition-api-client) could also upload a video to that channel.
            
            In this scenario, an [API Client](#definition-api-client) that does not support YouTube uploads (or other write-based actions) only needs to request access to the first authorization scope, which is more limited in the privileges it grants. Even if the [API Client's](#definition-api-client) developer plans to eventually introduce support for write-based actions, the developer cannot future-proof the [API Client](#definition-api-client) by requesting access to the authorization scope for writing data before the [Client](#definition-api-client) actually supports features that require that scope.
            
        3. [API Clients](#definition-api-client) should request access to authorization scopes in context whenever possible. By requesting access to user data in context, via incremental authorization, an [API Client](#definition-api-client) enables users to more easily understand why it needs access to that data.
            
    2. API Client Identification and Representation
        
        1. [API Clients](#definition-api-client) must clearly and accurately identify to the user the entity or product that is requesting access to user data and the reason for requesting that access;
            
        2. [API Clients](#definition-api-client) must not mislead users when requesting access to data so that users can make an informed decision about whether to grant access to those Clients. Users should be able to readily understand both the value of providing the data that an [API Client](#definition-api-client) requests access to and the consequences of sharing that data.
            
        3. [API Clients](#definition-api-client) must clearly and comprehensively identify to users the purposes for which they access and use user data. [API Clients](#definition-api-client) must not use user data for secondary purposes that are not clearly disclosed to users.
            
            Users should not be surprised to learn that an [API Client](#definition-api-client) contains hidden features, services, or actions that are inconsistent with the [Client's](#definition-api-client) marketed purposes.
            
    3. Revocation
        
        1. Every [API Client](#definition-api-client) must provide a clearly explained and easy way for users to revoke any authorization consent they have provided to an [API Client](#definition-api-client) to access [YouTube API Services](#definition-youtube-api-services).
            
            When a user revokes consent through this mechanism, the [API Client](#definition-api-client) must programmatically revoke that token right away to communicate the change in permissions to Google. For example, an [API Client](#definition-api-client) could use a Google API Client Library to revoke the token.
            
            In addition, following revocation of consent through this mechanism, you and your [API Clients](#definition-api-client) must delete all [Authorized Data](#definition-authorized-data) that was accessed or stored pursuant to that consent. That deletion should happen as soon as possible and must take place within 7 calendar days of the revocation.
            
        2. As noted in section (III.A.2.i), every [API Client](#definition-api-client) must include in its Privacy Policy a link to Google's security settings page ([https://security.google.com/settings/security/permissions](https://security.google.com/settings/security/permissions)). When a user revokes consent through that page, you and your [API Clients](#definition-api-client) must also delete all [API Data](#definition-api-data) related to that user that was accessed or stored pursuant to such consent. To comply with this policy, your [API Clients](#definition-api-client) will need to periodically reconfirm that its authorization tokens are still valid and delete [API Data](#definition-api-data) associated with users whose authorization tokens cannot be refreshed.
            
            Based on the requirements defined in section (III.E.4) regarding stored data, all such deletions should happen as soon as possible and must take place within 30 calendar days of that revocation.
            
3. Usage and Quotas
    
    YouTube may use quotas and place use restrictions to ensure that [YouTube API Services](#definition-youtube-api-services) are accessed and used as intended and that you and your [API Clients](#definition-api-client) do not reduce service quality or limit access for others.
    
    If your [API Client](#definition-api-client) reaches the quota limit for a service, you can apply for a quota extension by completing an [API Compliance Audit](https://support.google.com/youtube/contact/yt_api_form) where you must specify the use case for which you need the extension. If you have been audited in the past 12 months and have been marked compliant by YouTube API Services team, you can apply for an [additional quota extension](https://support.google.com/youtube/contact/yt_api_audited_developer_requests_form).
    
    If YouTube approves the application, you must use the additional quota granted only for the approved use case. If your [API Client's](#definition-api-client) use case changes, to use any allocated quota for the new use case, you must notify YouTube of the change by resubmitting an [API Compliance Audit](https://support.google.com/youtube/contact/yt_api_form) and receive approval for the application.
    
    If YouTube rejects the application, you can [file an appeal](https://support.google.com/youtube/contact/yt_api_appeals).
    
4. Inactivity
    
    YouTube reserves the right to disable or curtail your access to, or use of, specific [YouTube API Services](#definition-youtube-api-services) if your [API Project](#definition-api-project) has been inactive for 90 consecutive days. For example, YouTube could revoke your [API Credentials](#definition-api-credentials), or reduce (or eliminate) your [API Project's](#definition-api-project) quotas for specific [YouTube API Services](#definition-youtube-api-services). If your [API Client's](#definition-api-client) quota is reduced or eliminated, you may reapply for quota or a quota extension, and YouTube will review that application based on YouTube's determination of your expected use of the [YouTube API Services](#definition-youtube-api-services).
    
5. Contact Information
    
    YouTube's primary means of contacting you about your [API Project](#definition-api-project) or [API Client](#definition-api-client) is the email address that is associated with the Google Account that you use to log in to the Google Developers Console. You must comply to any communication that YouTube sends you regarding compliance issues relating to your [API Clients](#definition-api-client).
    
    If users of your [API Client](#definition-api-client) have questions about your privacy practices, and you do not have a contact address in your [API Client's](#definition-api-client) privacy policy as discussed in section (A.2.i), YouTube may share your primary email address with those users.
    
6. Prohibited Access
    
    You are prohibited from accessing or attempting to access [YouTube API Services](#definition-youtube-api-services) via any means if your [API Credentials](#definition-api-credentials) are suspended, revoked, or terminated, or if the Google Account you used to create those credentials is suspended or terminated, for any reason. In that case, you must not access or attempt to access [YouTube API Services](#definition-youtube-api-services) via any means, including by creating or using a proxy to create new Google Accounts, [API Credentials](#definition-api-credentials) or [API Projects](#definition-api-project).
    
7. Undocumented Services
    
    You must not use undocumented APIs without express permission. You must access data from YouTube API services only according to the means stipulated in the authorized documentation of that YouTube API service.
    
    You must not reverse engineer undocumented YouTube API services or otherwise attempt to derive the underlying source code of these API services.
    

### E. Handling YouTube Data and Content

Aside from the permissions and rights granted in this section, you and your [API Clients](#definition-api-client) have no further permissions or rights to [API Data](#definition-api-data), including to temporarily stored [API Data](#definition-api-data).

1. Audiovisual Content
    
    You and your [API Clients](#definition-api-client) must not, and must not encourage, enable, or require others to:
    
    1. download, import, backup, cache, or store copies of YouTube audiovisual content without YouTube's prior written approval,
    2. make content available for offline playback, or
    3. use any aspect of the [YouTube API Services](#definition-youtube-api-services) to facilitate or promote copyright infringement or the exploitation of copyright-infringing materials.
2. Data Aggregation
    
    1. Do not aggregate [API Data](#definition-api-data) except that you may only aggregate [API Data](#definition-api-data) relating to YouTube channels that are under the same content owner as recognized by YouTube pursuant to content licensing agreement(s) between YouTube and such content owner. Such aggregated [API Data](#definition-api-data) must only be viewable by that content owner.
        
    2. Do not aggregate [API Data](#definition-api-data) or otherwise use [API Data](#definition-api-data) or [YouTube API Services](#definition-youtube-api-services) to gain insights into YouTube's usage, revenue, or any other aspects of YouTube's business.
        
        For example, suppose that two different content owners recognized by YouTube have each authorized an [API Client](#definition-api-client) to retrieve [API Data](#definition-api-data) on their behalf for their respective viewing. That [API Client](#definition-api-client) may separately aggregate [API Data](#definition-api-data) retrieved for each content owner's channels provided that such aggregation per content owner does not provide insights into YouTube's usage, revenue or any other aspects of YouTube's business. The [API Client](#definition-api-client) must not combine [API Data](#definition-api-data) from the different content owners.
        
3. Authorized Data Usage
    
    These policies relate to your use of [Authorized Data](#definition-authorized-data). They are relevant for any [API Client](#definition-api-client) that writes data via an API request or retrieves data that can only be accessed via a properly authorized API request. For example, these policies apply to any [API Client](#definition-api-client) that enables a user to upload videos, retrieve the user's list of uploaded videos, create playlists, or comment on videos.
    
    1. [API Clients](#definition-api-client) must be honest and transparent about the types of user data and the purposes for which they collect, store, delete, share, safeguard, and otherwise use that data.
        
    2. [API Clients](#definition-api-client) must not display or allow access to [Authorized Data](#definition-authorized-data) to anyone other than the authorizing user or agents expressly approved by that user.
        
    3. [API Clients](#definition-api-client) must only access, collect and use [Authorized Data](#definition-authorized-data) in accordance with the scope of its privacy policy and user consent obtained in accordance with Section 2.
        
        This means that an [API Client](#definition-api-client) must prompt users to re-accept its privacy policy if the [Client](#definition-api-client) starts to access, collect, or use [API Data](#definition-api-data) in a way or for purposes that were not covered in the privacy policy that the user originally accepted.
        
    4. [API Clients](#definition-api-client) must clearly identify any actions that they take to insert, share, update, or delete data or content on the authorizing user's behalf. In addition, the user must expressly consent to those actions prior to their actual execution.
        
    5. [API Clients](#definition-api-client) must clearly identify the YouTube channel or content owner that is associated with any request that requires user authorization.
        
    6. [API Clients](#definition-api-client) must clearly identify any content visibility settings that will be set or modified by any authorized user action. In addition, [API Clients](#definition-api-client) must not modify existing content visibility settings unless the authorizing user has expressly instructed the [API Clients](#definition-api-client) to do so.
        
        For example, in the YouTube Data API service, a video's privacy status can be set to `public`, `private`, or `unlisted`. If an [API Client](#definition-api-client) supports video uploads, the [Client](#definition-api-client) must clearly display an option for the user to choose one of those values. Similarly, if an [API Client](#definition-api-client) supports edits to a video's metadata, the [API Client](#definition-api-client) cannot change a video's privacy status without the user's express consent.
        
4. Refreshing, Storing, and Displaying API Data
    
    Developers often need to balance the benefits of storing or caching data, such as improved performance or resource usage, with the desire to always retrieve the freshest data, which provides the best user experience possible. With that in mind, the following policies explain your requirements as well as your options in terms of storing, updating, and displaying YouTube [API Data](#definition-api-data).
    
    1. [API Clients](#definition-api-client) may store authorization tokens for as long as is necessary provided that those tokens are used only for purposes consistent with the specific consent granted by an active user according to the applicable law.
        
    2. [API Clients](#definition-api-client) may store the following types of [Authorized Data](#definition-authorized-data) for as long as is necessary provided that the data is used for purposes consistent with the specific consent granted by an active user according to the applicable laws:
        
        1. data retrieved through the YouTube Analytics API service,
        2. data provided through the YouTube Reporting API service, or
        3. statistics provided through other YouTube API services, such as the number of views for a video, the number of channels for a subscriber, or the number of videos in a playlist. (All of those statistics can be retrieved via the YouTube Data API service.)
        
        Note that even though an [API Client](#definition-api-client) may store this data for more than 30 days, the [Client](#definition-api-client) must still ensure every 30 days that it is still authorized by the user to access that data.
        
        For example, an [API Client](#definition-api-client) may store view counts for a video for more than 30 days, but it must still verify every 30 days that its authorization to access the video uploader's data has not been revoked. The [API Client](#definition-api-client) must also verify, every 30 days, that the video has not been deleted.
        
        To be clear, an [API Client](#definition-api-client) must not store statistics retrieved as [Non-Authorized Data](#definition-non-authorized-data) for more than 30 days. For example, an [API Client](#definition-api-client) must not store the subscriber count for a YouTube channel for more than 30 days without authorization from the channel owner.
        
    3. [API Clients](#definition-api-client) may store all other types of [Authorized Data](#definition-authorized-data) not identified in section (III.E.4.b) for as long as is necessary for the purposes of the specific consent granted by an active user and for no longer than 30 calendar days. After 30 calendar days, the [API Client](#definition-api-client) must either delete or refresh the stored data.
        
    4. [API Clients](#definition-api-client) may temporarily store limited amounts of [Non-Authorized Data](#definition-non-authorized-data) for as long as is necessary for the purposes of the [API Client](#definition-api-client) but not longer than 30 calendar days. As in section (III.E.4.c) immediately above, this means that after 30 calendar days, the [API Client](#definition-api-client) must either delete or refresh the stored data.
        
    5. In all cases, [API Clients](#definition-api-client) must use reasonable efforts to ensure that their stored [API Data](#definition-api-data) is consistent with the current data available through [YouTube API Services](#definition-youtube-api-services). For example, [API Clients](#definition-api-client) should reflect metadata changes and viewcount updates as quickly as possible.
        
    6. [API Clients](#definition-api-client) must display the most updated [API Data](#definition-api-data) available in their user-facing presentations, including in user interfaces, although [API Clients](#definition-api-client) may display historical [API Data](#definition-api-data) provided that it is presented accurately in context of time.
        
    7. Your [API Clients](#definition-api-client) that access or use user data must provide a way for a user to request that you delete stored data related to that user. For example, your [API Client](#definition-api-client) could display a button to delete stored data. If the user indicates that you should delete that data, you must then delete it as soon as possible and within 7 calendar days.
        
        The method for deleting stored data must make clear that deleting the data stored by the [API Client](#definition-api-client) does not, in any way, affect data stored by YouTube and that to delete data on YouTube, the user needs to use a YouTube Application or an authorized [API Client](#definition-api-client) that supports the ability to delete that data.
        
        Similarly, [API Clients](#definition-api-client) must respect any other means by which a user expresses an intent to prevent those Clients from accessing user data related to that user. For example, if a user deletes his account from your API Client, you must also delete any user data you have stored related to that user as soon as possible and within 7 calendar days.
        
    8. Your [API Clients](#definition-api-client) must not (i) replace [API Data](#definition-api-data) with similar, independently calculated data, or (ii) access or use [API Data](#definition-api-data) to create new or derived data or metrics.  To the extent your [API Clients](#definition-api-client) display any information, data or metrics not based on [API Data](#definition-api-data) alongside [API Data](#definition-api-data), your [API Clients](#definition-api-client) must include a clear and prominent disclosure there that such information, data and metrics are not from YouTube and are part of your own product.
        
        For example, when displaying the number of likes for a video, your [API Client](#definition-api-client) must use the number returned in the [API Data](#definition-api-data). You must not substitute a different number to represent likes, such as the number of users of your [API Client](#definition-api-client) that liked the video. Similarly, you are not permitted to use the number of likes returned in the [API Data](#definition-api-data) to calculate other metrics, such as the percentage of total likes that were made through your [API Client](#definition-api-client) or a score that factors in likes, total views, or any other [API Data](#definition-api-data). However, you are permitted, for example, to display the number of likes that were made through your [API Client](#definition-api-client) as long as that number is displayed alongside the total likes returned in the [API Data](#definition-api-data) and as long as your [API Client](#definition-api-client) clearly communicates that the [API Client](#definition-api-client) calculates the additional metric independently of YouTube [API Data](#definition-api-data).
        
    9. When your [API Client](#definition-api-client) loads, it collects and shares some basic user data with YouTube via the YouTube embedded player to render the video thumbnail and title, determine playability and content restrictions, and for fraud and abuse reasons. Additional data is collected and shared by your [API Client](#definition-api-client) upon video playback to customize the player on your [API Client](#definition-api-client) and third party sites and apps. Remember that if you enable Autoplay, playback will occur without any user interaction with the player; playback data collection and sharing will therefore occur upon page load. You can limit the data shared with YouTube before a user interacts with the YouTube embedded player by setting Autoplay to `false`. As noted in the [YouTube API Services Terms of Service](https://developers.google.com/youtube/terms/api-services-terms-of-service), you and your [API Clients](#definition-api-client) must comply with all applicable laws, rules, and regulations, including privacy laws and regulations.
        
    10. [API Clients](#definition-api-client) must look up the Made For Kids status of each YouTube video that it embeds on its site or app by following the instructions in [this guide](https://developers.google.com/youtube/v3/guides/made_for_kids_status). For each video that is designated Made For Kids, [API Clients](#definition-api-client) must turn off tracking and make sure that all data collection with respect to that player is compliant with applicable law(s) including the U.S. Children's Online Privacy (COPPA) and E.U. General Data Protection Regulation (GDPR)). See the [YouTube Help Center](https://support.google.com/youtube/answer/9528076) for more information on determining content as Made for Kids.
        
5. Security
    
    You and your [API Client](#definition-api-client) must:
    
    1. maintain appropriate administrative, organisational, technical, and physical controls to ensure the privacy, security, and confidentiality of user data and [API Data](#definition-api-data);
    2. use only industry-standard transport encryption;
    3. protect [API Data](#definition-api-data) and any other data used in your [API Client](#definition-api-client) from unauthorized access, use, or disclosure.
6. Scraping
    
    You and your [API Clients](#definition-api-client) must not, and must not encourage, enable, or require others to, directly or indirectly, scrape [YouTube Applications](#definition-youtube-applications) or [Google Applications](#definition-google-applications), or obtain scraped YouTube data or content. Public search engines may scrape data only in accordance with YouTube's robots.txt file or with YouTube's prior written permission.
    

### F. User Experience

1. YouTube Look and Feel
    
    Innovative user experiences and user interface designs are among the most valuable contributions that [API Clients](#definition-api-client) can provide to the YouTube community. That said, YouTube's designers and engineers put a lot of thought into designing [YouTube Applications](#definition-youtube-applications) to ensure that those Applications provide a great user experience.
    
    Taking both of those points into account, your [API Clients](#definition-api-client) must not change or interfere with user interfaces in [YouTube Applications](#definition-youtube-applications) unless you have obtained YouTube's prior written approval. You can request that approval at [this form](https://support.google.com/youtube/contact/yt_api_form).
    
2. Branding
    
    1. Any [API Client](#definition-api-client) page or feature that displays YouTube content – including, without limitation, search results, YouTube videos, channels, playlists, thumbnails, and YouTube players – must make clear to the viewer that YouTube is the source of the relevant content by displaying [YouTube Brand Features](#definition-youtube-brand-features) in accordance with the requirements below and the YouTube Branding Guidelines ([https://developers.google.com/youtube/terms/branding-guidelines](https://developers.google.com/youtube/terms/branding-guidelines)).
        
        In some cases, an [API Client](#definition-api-client) might need to display [YouTube Brand Features](#definition-youtube-brand-features) next to multiple individual content elements to make the attribution clear to the viewer. For example, an [API Client](#definition-api-client) that displays search results from YouTube and from other sources on the same page needs to clearly identify YouTube as the source of only the search results from YouTube, including text, images, and other information pertaining to YouTube search results. The [API Client](#definition-api-client) cannot provide one general set of attribution for all search results from various sources.
        
    2. Content that does not originate from YouTube must not be shown in a way that suggests that the content is originating from YouTube or in a way that can cause confusion as to the origin of that content.
        
    3. You and your [API Clients](#definition-api-client) must not, and must not encourage, enable or require others to, directly or indirectly, interfere with or obscure any attribution provided by YouTube, including attribution provided via or shown in embedded YouTube players. Your [API Clients](#definition-api-client) must display applicable [YouTube Brand Features](#definition-youtube-brand-features) and any other YouTube-provided attribution on all types of devices.
        
3. Playback Integrity
    
    Playback integrity refers to the ability to determine and measure how content and ads are served, how video playback is initiated and implemented, and how users interact with YouTube features in your [API Client](#definition-api-client). Playback integrity is critical to the YouTube platform, as it helps protect creators' interests, including their ability to monetize their content and develop their audience.
    
    YouTube believes that playback integrity is contingent on a user choosing to watch a video, and [API Clients](#definition-api-client) are prohibited from providing incentives for watching videos as follows:
    
    1. [API Clients](#definition-api-client) must not charge users to watch content in an embedded YouTube player.
        
    2. [API Clients](#definition-api-client) must not otherwise gate access to a video by requiring a user to take an action other than clicking the play button to view or continue playing YouTube audiovisual content. For example, [API Clients](#definition-api-client) must not require a user to subscribe to a channel or like a video to continue watching YouTube audiovisual content.
        
        For clarity, if your [API Client's](#definition-api-client) normal functionality requires a certain action that is not specific to [YouTube API Services](#definition-youtube-api-services), such as login or age verification, that functionality is allowed.
        
    3. [API Clients](#definition-api-client) must not offer or provide incentives, rewards, or other compensation to users for engaging with [YouTube Applications](#definition-youtube-applications) (directly or indirectly) by performing actions like viewing content, liking content, sharing content, subscribing to channels, adding comments. For example, [API Clients](#definition-api-client) must not offer features or services that trade video views for a fee or that trade video views in return for other YouTube-related or non-YouTube-related actions.
        

### G. Distribution and Commercial Use

You may distribute or sell [API Clients](#definition-api-client) subject to the restrictions defined in the "Prohibited Actions" subsection below and, of course, to the other terms of the [Agreement](#definition-agreement).

In addition, you may distribute and display YouTube audiovisual content and accompanying metadata to users through your [API Clients](#definition-api-client) as long as those Clients comply with the [Agreement](#definition-agreement) and, specifically, do not engage in any of the prohibited actions listed immediately below.

1. Prohibited Actions
    
    For specific policies in the following list that require YouTube's prior written approval, you can request that approval at [this form](https://support.google.com/youtube/contact/yt_api_form).
    
    You and your [API Clients](#definition-api-client) must not, and must not encourage, enable, or require others to:
    
    1. sell, purchase, lease, lend, convey, redistribute, or sublicense all or any portion of [YouTube API Services](#definition-youtube-api-services), including YouTube audiovisual content;
        
    2. sell [YouTube API Services](#definition-youtube-api-services) or access to any components of [YouTube API Services](#definition-youtube-api-services) unless you obtain YouTube's prior written approval;
        
    3. sell advertising, sponsorships, or promotions that are placed on or within YouTube audiovisual content or the YouTube player without YouTube's prior written approval; or
        
    4. sell advertising, sponsorships, or promotions on any page or screen that contains [YouTube API Data](#definition-api-data) unless other data, content, or material not obtained from YouTube appears on the same page and offers enough independent value to justify such sales if the [YouTube API Data](#definition-api-data) were removed.
        
2. Permitted Actions
    
    All of the following commercial use cases are permitted subject to your and Your [API Clients](#definition-api-client)' compliance with all other terms of the [Agreement](#definition-agreement), including the prohibited actions detailed in the previous section:
    
    1. Selling an API Client;
        
    2. Promoting your own business or artistic enterprise by uploading original audiovisual content to YouTube or maintaining channel(s) on YouTube;
        
    3. Developing ad-enabled [API Clients](#definition-api-client), such as an ad-enabled blog or website, that use [YouTube API Services](#definition-youtube-api-services) subject to compliance with all other terms of the Agreement, including the restrictions in section III.G.1.d;
        
    4. Placing your own branding in an [API Client](#definition-api-client) as long as that branding complies with the [YouTube Branding Guidelines](https://developers.google.com/youtube/terms/branding-guidelines) and does not interfere with YouTube audiovisual content playback or any [YouTube Brand Features](#definition-youtube-brand-features);
        
    5. Selling or distributing devices that contain or run an API Client;
        

### H. Monitoring and Audits

YouTube reserves the right to survey, monitor, and/or audit your access to or use of [YouTube API Services](#definition-youtube-api-services) to ensure quality, to improve YouTube products and services, and to verify your compliance with the [Agreement](#definition-agreement). To that end, YouTube may survey users of your [API Clients](#definition-api-client).

You and those acting on your behalf must:

1. not interfere with such surveys, monitoring efforts, or audits;
2. not obscure or conceal from YouTube your access to or use of [YouTube API Services](#definition-youtube-api-services); and
3. upon request, and within the timeframe stated in that request, provide YouTube with account(s) necessary to access all features or functions of the current, in-production version(s) of your [API Clients](#definition-api-client), so that YouTube may review those [API Clients](#definition-api-client) for compliance with the [Agreement](#definition-agreement).

YouTube may use any technical means to overcome non-compliance with these provisions.

### I. Additional Prohibitions

The policies in this section identify additional things that [API Clients](#definition-api-client) must not do. Actions contrary to these policies would be harmful to YouTube, to the YouTube community as a whole, or to individuals or groups of individuals within that community. These policies focus on the need for you and your [API Clients](#definition-api-client) to treat members of the YouTube community honestly and respectfully as well as on your need to respect the integrity of YouTube's services, content, and interests.

You and your [API Clients](#definition-api-client) must not, and must not encourage, enable, or require others to:

1. use [YouTube API Services](#definition-youtube-api-services) to create, offer, or act as a substitute for, or substantially similar service to, any [YouTube Applications](#definition-youtube-applications). [API Clients](#definition-api-client) must not mimic or replicate YouTube's core user experiences by recreating features or process flows unless they add significant independent value or functionality that improves users' interactions with YouTube. For example, an [API Client](#definition-api-client) must not recreate the browse experience from any YouTube Application without adding significant independent value to that flow.
    
2. misuse [YouTube API Services](#definition-youtube-api-services) or engage in abusive behaviors related to those Services. For example, you must not automate or trigger views, uploads, comments, likes, dislikes, or other actions without the user's prior specific and express consent;
    
3. interfere, or attempt to interfere, in any way with the proper workings of any aspect of [YouTube API Services](#definition-youtube-api-services), [YouTube Applications](#definition-youtube-applications), or [Google Applications](#definition-google-applications), including interference or disruption of the servers or networks that provide those Services or Applications;
    
4. modify, interfere with, replace, or otherwise disable any functionality, data, or content made available as part of, or in connection with, [YouTube API Services](#definition-youtube-api-services). For example, you must not remove, obscure, alter, or disable any links that appear in YouTube players or in [API Data](#definition-api-data).
    
5. modify, interfere with, replace, or block advertisements placed or served by YouTube or by [YouTube API Services](#definition-youtube-api-services) including in [API Data](#definition-api-data), YouTube audiovisual content, or YouTube players;
    
6. modify, build upon, or block any portion or functionality of a YouTube player;
    
7. separate, isolate, or modify the audio or video components of any YouTube audiovisual content made available as part of, or in connection with, [YouTube API Services](#definition-youtube-api-services). For example, you must not apply alternate audio tracks to videos;
    
8. promote separately the audio or video components of any YouTube audiovisual content made available as part of, or in connection with, the [YouTube API Services](#definition-youtube-api-services);
    
9. create, include, or promote features that play content, including audio or video components, from a background player, meaning a player that is not displayed in the page, tab, or screen that the user is viewing;
    
10. adversely affect the functionality or performance of any aspect of [YouTube API Services](#definition-youtube-api-services), [YouTube Applications](#definition-youtube-applications), or [Google Applications](#definition-google-applications), including actions that interfere with or disrupt [YouTube API Services](#definition-youtube-api-services) or the servers or networks that provide those Services;
    
11. confuse, deceive, defraud, mislead, misrepresent, defame, abuse, stalk, threaten, spam, surprise, or harass anyone;
    
12. introduce, or attempt to introduce, any viruses, worms, defects, Trojan horses, malware, spyware, adware, or other items of a destructive nature to [YouTube API Services](#definition-youtube-api-services), [YouTube Applications](#definition-youtube-applications), [Google Applications](#definition-google-applications), or YouTube users and the devices they use to access those services and properties;
    
13. circumvent, interfere with, or render ineffective, any geographical restrictions, including IP address-based restrictions imposed by YouTube or [YouTube API Services](#definition-youtube-api-services);
    
14. use any technology other than [YouTube API Services](#definition-youtube-api-services) to access or retrieve [API Data](#definition-api-data), including to access any portion of any YouTube audiovisual content;
    
15. offer an API service that allows users to access any data or functionality directly or indirectly provided by the [YouTube API Services](#definition-youtube-api-services);
    
16. modify, translate, create derivative works of, reverse engineer or otherwise attempt to extract the underlying source code from any [YouTube API Services](#definition-youtube-api-services) or from any software related to those Services;
    
17. use [YouTube API Services](#definition-youtube-api-services) for any purpose or activity where the use or failure of those Services could lead to death, personal injury, or environmental damage, such as in the operation of nuclear facilities, air traffic control systems, or life support systems;
    
18. infringe copyrights or exploit copyright-infringing materials;
    
19. engage in, promote or facilitate unlawful online gambling;
    
20. create, display, promote or facilitate disruptive commercial messages or advertisements; or
    
21. situate the YouTube player in a nested or hierarchical iframe lineage to circumvent YouTube policies or otherwise obfuscate the source of use.
    

### J. Child-Directed API Clients

1. If your API Client (or any part thereof) targets or directs itself to children (as defined under applicable law(s) including the U.S. Children's Online Privacy (COPPA) and E.U. General Data Protection Regulation (GDPR)) (referred to herein as a "**Child-Directed API Client**"), you and your Child-Directed API Client must:
    
    1. ensure that your Child-Directed API Client, including its access to and use of any YouTube API Services, is compliant with COPPA, GDPR, and any other applicable laws or regulations at all times;
        
    2. notify Google of the child directed nature of your Child-Directed API Client using the tools provided in [here](https://support.google.com/policies/answer/9664901). Each Child-Directed API Client notified to Google using such tools or otherwise is referred to herein as a "**Known Child-Directed API Client**"; and
        
    3. not use personalized ads (including remarketing) to target past or current activity by any user of your Child-Directed API Client.
        
2. 1. **For You and Your Child-Directed API Client.** You and your Child-Directed API Client will not, and must not attempt to, take any YouTube API Services write-based actions to YouTube websites, applications, services or products via your Child-Directed API Client.
        
    2. Notwithstanding Section III.D.1.c (API Credentials) above which requires exactly one (1) [API Project](#definition-api-project) for each [API Client](#definition-api-client), you can upload your own videos to your own official YouTube channel(s) via the YouTube Data API Service (not via your Child-Directed API Client or anyone else's API Client) by creating a new API Project ("**Upload Project**").
        
        1. To upload your own videos to your own official YouTube channel(s) via YouTube Data API Service, you must (A) create one (1) new [API Project](#definition-api-project) using the [Google Developers Console](https://console.developers.google.com/) ([https://console.developers.google.com/](https://console.developers.google.com/)) (an "**Upload Project**") prior to uploading, (B) append _mfk110_ as a prefix in the ID of your Upload Project, and (C) only upload from your non-Child-Directed API Client (not from your Child-Directed API Client or anyone else's API Client); and
            
        2. Only you can use the Upload Project, and the Upload Project must only be used to upload your own videos to your own official YouTube channel(s) via the YouTube Data API Service from your non-Child-Directed API Client (not from your Child-Directed API Client or anyone else's API Client). If you are uploading a Made for Kids video via the YouTube Data API Service from your non-Child-Directed API Client (not from your Child-Directed API Client or anyone else's API Client), you must designate the YouTube Data API Service Made for Kids parameter as "true". See here for more information on determining if content is [Made for Kids](https://support.google.com/youtube/answer/9528076).
            
    3. **For You and Users of Your Child-Directed API Client.** You and your Child-Directed API Client must not enable, encourage or require, users of your Child-Directed API Client to take YouTube API Services write-based actions (such as, but not limited to, uploading content, commenting and creating/sharing playlists). YouTube API Services write-based actions taken by users of Known Child-Directed API Clients will not be implemented on YouTube websites, applications, services and products. This means that, notwithstanding [Section 9.1 (Required Notice) of the YouTube API Services Terms of Service](https://developers.google.com/youtube/terms/api-services-terms-of-service) pursuant to which users of your API Client may upload content to their YouTube channels or your YouTube channel(s), uploads from users of Known Child-Directed API Clients will not be implemented on YouTube websites, applications, services and products.
        
3. You and your API Client's access to, or use of, YouTube API Services can be suspended or terminated by YouTube for non-compliance with the YouTube API Services Terms of Service and Policies including non-compliance with this Section III.J.
    

### K. Reporting Noncompliance

If you are aware of anyone accessing or using [YouTube API Services](#definition-youtube-api-services) in a manner that is not compliant with these policies or any other part of the [Agreement](#definition-agreement), you may contact the YouTube API Services team to escalate the issue [using this form](https://support.google.com/youtube/contact/yt_api_form).

IV. Definitions
---------------

"**Agreement**" means the legal documents defined and referenced in Section 2 (The Agreement) of the YouTube API Services [Terms of Service](#definition-terms-of-service) currently located at [https://developers.google.com/youtube/terms/api-services-terms-of-service](https://developers.google.com/youtube/terms/api-services-terms-of-service).

"**API Client**" means a website or software application (including a mobile application) developed by you that accesses or uses the [YouTube API Services](#definition-youtube-api-services).

"**API Credentials**" means the credentials assigned by YouTube or Google via the Google Developer Console that each [API Project](#definition-api-project) authenticates with to access and use the [YouTube API Services](#definition-youtube-api-services).

"**API Data**" is defined within the definition of "[YouTube API Services](#definition-youtube-api-services)" later in this Definitions section.

"**API Project**" means the project created in the Google Developer Console that is required for API Client(s) to access and use the [YouTube API Services](#definition-youtube-api-services).

"**Authorized Data**" means [API Data](#definition-api-data) that an active user expressly authorizes an [API Client](#definition-api-client) to access or otherwise use via [User Credentials](#definition-user-credentials).

"**Google Applications**" means Google websites, applications, services, products, pages, and other properties.

"**Non-Authorized Data**" means [API Data](#definition-api-data) accessible by an [API Client](#definition-api-client) without [User Credentials](#definition-user-credentials).

"**Terms of Service**" means the YouTube API Services Terms of Service currently located at [https://developers.google.com/youtube/terms/api-services-terms-of-service](https://developers.google.com/youtube/terms/api-services-terms-of-service).

"**User Credentials**" means the credentials issued to users that users can authenticate with to permit API Client(s) to perform operations on their behalf that require authorization.

"**YouTube API Services**" means (i) the YouTube API services (e.g., YouTube Data API service and YouTube Reporting API service) made available by YouTube including those YouTube API services made available on the YouTube Developer Site (as defined below), (ii) documentation, information, materials, sample code and software (including any human-readable programming instructions) relating to YouTube API services that are made available on [https://developers.google.com/youtube](https://developers.google.com/youtube) or by YouTube, (iii) data, content (including audiovisual content) and information provided to [API Clients](#definition-api-client) (as defined above) through the YouTube API services (the "[API Data](#definition-api-data)"), and (iv) the credentials assigned to you and your API Client(s) by YouTube or Google.

"**YouTube Applications**" means YouTube websites, applications, services, products, pages, and other properties, including **https://www.youtube.com**, **m.youtube.com**, mobile applications like the YouTube Gaming application, and so forth, but excluding [YouTube API Services](#definition-youtube-api-services).

"**YouTube Brand Features**" means the trade names, trademarks, service marks, logos, domain names, and other distinctive brand features of YouTube.

YouTube API Services Terms of Service

Stay organized with collections Save and categorize content based on your preferences.


===============================================================================================================================

**Note:** [Complying with the YouTube Developer Policies](http://developers.google.com/youtube/terms/developer-policies-guide) provides guidance and examples to help you ensure that your API clients follow specific portions of the YouTube API Services [Terms](http://developers.google.com/youtube/terms/api-services-terms-of-service) and [Policies](http://developers.google.com/youtube/terms/developer-policies) (API TOS). The guide offers insight into how YouTube enforces certain aspects of the API TOS, but it does not replace any existing documents.

The following YouTube API Services Terms of Service is a legal document you must follow when accessing or using the YouTube API Services. Please read it often, and make sure you understand it. You can subscribe to the [RSS feed](http://developers.google.com/static/youtube/terms/feeds/api-services-terms-of-service-revision-history.xml) for the revision history to be notified of any such changes to the YouTube API Services Terms of Service. When reviewing the following YouTube API Services Terms of Service below, and accessing and using YouTube API Services, please keep the following in mind:

Respecting and fostering the growth of the YouTube community of creators, viewers, content rights holders and advertisers is very important to us. We provide the YouTube API Services to enable developers to create experiences that bring additional value to the YouTube ecosystem and its users. If your implementation is in breach of the YouTube API Services Terms of Service or has a negative impact on the YouTube community, we may impose limitations and prohibitions on your access to, and use of, the YouTube API Services.

Thank you,  
—The YouTube API Services Team

YouTube API Services Terms of Service
-------------------------------------

Thank you for your interest in the YouTube API Services. The YouTube API Services (as defined below) are provided to you by YouTube LLC located at 901 Cherry Ave., San Bruno CA 94066 (referred to as "**YouTube**", "**we**", "**us**", or "**our**"). This YouTube API Services Terms of Service ("**Terms of Service**") is a legal document you must comply with at all times when accessing or using the YouTube API Services. The "**YouTube API Services**" means (i) the YouTube API services (e.g., YouTube Data API service and YouTube Reporting API service) made available by YouTube including those YouTube API services made available on the YouTube Developer Site (as defined below), (ii) documentation, information, materials, sample code and software (including any human-readable programming instructions) relating to YouTube API services that are made available on the YouTube Developer Site or by YouTube, (iii) data, content (including audiovisual content) and information provided to API Clients (as defined below) through the YouTube API services (the "**API Data**"), and (iv) the credentials assigned to you and your API Client(s) by YouTube or Google. By accessing and using the YouTube API Services, and in return for receiving the benefits of the YouTube API Services provided to you by YouTube, you agree to be bound by the Agreement (as defined below).

1. 1\. Definitions
    ---------------
    
    **Definitions.** These defined terms will have the following meanings:
    
    1. **Affiliates** means any entity that directly or indirectly controls, is controlled by, or is under common control with, YouTube, including Google Inc.
    2. **API Client** means a website or software application (including a mobile application) developed by you that accesses, or uses, the YouTube API Services.
    3. **Developer Policies** means the policies relating to the YouTube API Services currently located at [https://developers.google.com/youtube/terms/developer-policies](http://developers.google.com/youtube/terms/developer-policies) that you and your API Client(s) are required to comply with in addition to all other terms of the Agreement when accessing, or using, the YouTube API Services.
    4. **YouTube Brand Features** means the trade names, trademarks, service marks, logos, domain names, and other distinctive brand features of YouTube.
    5. **YouTube Branding Guidelines** means the YouTube API Services Branding Guidelines currently located at [https://developers.google.com/youtube/terms/branding-guidelines](https://developers.google.com/youtube/terms/branding-guidelines).
    6. **YouTube Confidential Information** means any information of YouTube or its Affiliates provided to you in connection with your access to, or use of, the YouTube API Services, but excluding information that you independently developed, that was rightfully given to you by a third party without confidentiality obligation, or that becomes public through no fault of your own.
    7. **YouTube Developer Site** means the YouTube developer website including the webpages currently located at [https://developers.google.com/youtube](https://developers.google.com/youtube).
    8. **YouTube Guidelines** means the guidelines and other documentation published on the YouTube Developer Site including the YouTube Branding Guidelines.
    9. **YouTube Terms** means the YouTube Terms of Service currently located at [https://www.youtube.com/t/terms](https://www.youtube.com/t/terms).
2. 2\. The Agreement.
    ------------------
    
    **The Agreement.**
    
    2.1 **Components of the Agreement.** The Agreement is comprised of the following:
    
    1. these Terms of Service;
    2. the Developer Policies;
    3. the YouTube Guidelines;
    4. the credentials assigned to you and your API Client(s) by YouTube or Google;
    5. the Google Software Principles currently located at [http://www.google.com/corporate/software\_principles.html](http://www.google.com/corporate/software_principles.html); and
    6. the YouTube Terms.
    
    2.2 **Condition of Use.** Before you access or use the YouTube API Services, please read the documents comprising the Agreement carefully and make sure you understand them. If you disagree with any aspect of the Agreement, you do not have our permission to, and you must not, access or use any of the YouTube API Services.
    
    2.3 **Modification of the Agreement.** YouTube may modify the Terms of Service or any of the other documents comprising the Agreement at any time. YouTube will provide notice of changes to the Terms of Service by posting the changes at [https://developers.google.com/youtube/terms/revision-history](http://developers.google.com/youtube/terms/revision-history) (or any successor URL), emailing the email address associated with the credentials assigned to you or your API Client(s) by YouTube or Google, or otherwise notifying you. The changes will not apply retroactively, and will become effective no sooner than 30 calendar days after posting. However, changes specific to new functionality or changes made for legal reasons may be effective immediately upon notice. You or your API Client(s)’ continued access to, or use of, the YouTube API Services, including your continued development activities in connection with any YouTube API Services and your API Client(s)’ interaction with any YouTube API Services after the changes to the Agreement takes effect, will be deemed your agreement to and acceptance of such changes. If you do not agree to any changes to the Agreement, you must terminate the Agreement.
    
    2.4 **Precedence.** If there is any contradiction between these Terms of Service and other documents comprising the Agreement in connection with the YouTube API Services, then these Terms of Service will take precedence.
    
3. 3\. Permitted Access and Use of the YouTube API Services.
    ---------------------------------------------------------
    
    **Permitted Access and Use of the YouTube API Services.**
    
    3.1 **Compliance with the Agreement.** You and your API Client(s) will (i) comply with the Agreement at all times when accessing or using the YouTube API Services; (ii) only access (or attempt to access) the YouTube API Services to develop and operate your API Client(s) by the means described in the Agreement, including in accordance with the documentation for the specific YouTube API Services you access; and (iii) if your API Client is a software application, you and your API Client will also comply with the Google Software Principles. YouTube may suspend or terminate your access to, or use of, any aspect of the YouTube API Services (including any credentials assigned to you or your API Client(s)), impose additional requirements and restrictions, or terminate the Agreement between you and YouTube, for any violation of the Agreement by you, your API Client(s) or those acting on your behalf.
    
    3.2 **Unauthorized Persons.** You must not accept the Agreement, or access or use the YouTube API Services, if (i) you are not of legal age to form a binding contract with us, or (ii) you are a person barred from using or receiving the YouTube API Services under the applicable laws of the United States, the country in which you reside, or the countries from which you or your API Client(s) access or use the YouTube API Services.
    
    3.3 **Accepting on Behalf of Others.** If you are using the YouTube API Services on behalf of someone else (such as your employer), you represent and warrant that you have authority to bind that person or entity to the Agreement and by accepting the Agreement, you are doing so on behalf of that person or entity (and all references to "you" in the Agreement refers to that person or entity).
    
4. 4\. Registration
    ----------------
    
    **Registration.** To access and use the YouTube API Services you may be required to provide certain information (such as identification or contact details) as part of the registration process, or as part of your continued access to, or use of, the YouTube API Services. We may retain this information until it is no longer needed by us, including for contractual and integrity purposes. Our Privacy Policy currently located at [https://www.google.com/policies/privacy/](https://www.google.com/policies/privacy/) explains how we treat your personal data and protect your privacy when you provide your personal data in connection with your access and use of the YouTube API Services.
    
5. 5\. Compliance with Laws
    ------------------------
    
    **Compliance with Laws.** You and your API Client(s) will, and you will require those acting on your behalf and your users to, (i) comply with all applicable laws, rules, and regulations, and (ii) not access or use the YouTube API Services in a manner that violates such laws, rules, and regulations, or in a manner that is deceptive, unethical, false, or misleading. Without limiting the foregoing, you will not distribute, or provide access, to your API Client(s) in contravention of U.S. export control or trade laws.
    
6. 6\. API Clients and Monitoring
    ------------------------------
    
    **API Clients and Monitoring.** YouTube may monitor, review and inspect your API Client(s), and monitor and audit your access to and use of the YouTube API Services, at any time and without further notice to you, to ensure quality, improve our products and services, and verify your compliance with the Agreement.
    
7. 7\. User Privacy and API Clients
    --------------------------------
    
    **User Privacy and API Clients.** Without limiting Section 5 (Compliance with Laws), you will comply with all applicable privacy laws and regulations, including those applying to personal data ("**Personal Data**"). Each API Client will provide and adhere to a published privacy policy that clearly and accurately describes to its users what user information you and your API Client access, collect and store, and how and why you and your API Client use, process, and share such information (including for advertising) with us and other third parties.
    
8. 8\. Security
    ------------
    
    **Security.** To the extent you and your API Client(s) are permitted to access or use data, you and your API Client(s) will, and will require those acting on your behalf to, maintain reasonable and appropriate administrative, organizational, technical and physical controls designed to ensure the privacy, security, and confidentiality of YouTube data (including API Data), YouTube Confidential Information and user data collected by your API Client(s) (including Personal Data) to protect from accidental or unauthorized destruction, access or use.
    
9. 9\. Notices to Users
    --------------------
    
    **Notices to Users.**
    
    9.1 **Required Notice.**
    
    1. If your API Client(s) uses any YouTube API Services to permit users to upload videos to YouTube websites, applications, services or products, the screen or window in which the end user clicks the "upload" button must display the following warning in the language(s) available on your API Client(s):
        
        "By clicking 'upload,' you certify that the content you are uploading complies with the YouTube Terms of Service (including the YouTube Community Guidelines) at **\[select and insert appropriate URL from following paragraph\]**. Please be sure not to violate others' copyright or privacy rights."
        
        If the upload is performed on a personal computer or other non-mobile device, the appropriate URL is [https://www.youtube.com/t/terms](https://www.youtube.com/t/terms). If the upload is performed on a mobile device, the appropriate URL is [http://m.youtube.com/terms](http://m.youtube.com/terms).
        
    2. Subject to this Sections 9.1(iii) and (iv) below, API Client(s) that enable users to upload videos to YouTube websites, applications, services or products must provide each user the option to upload the videos to the user's own YouTube channel(s). If your API Client(s) also allow users to upload videos to your YouTube channel, it must (i) provide clear notice of the terms of your license to those videos including a clear notice to users that you will now either own or have rights to such videos, and (ii) ensure that the option to upload to the user's YouTube channel is featured at least as prominently as the option to upload videos to your YouTube channel.
        
    3. If your API Client (or any part thereof) targets or directs itself to children (as defined under applicable law(s) including the U.S. Children's Online Privacy (COPPA) and E.U. General Data Protection Regulation (GDPR)) (referred to herein as a "**Child-Directed API Client**"), (a) you and your API Client must comply with [Section III.J (API Clients Directed to Children) of the Developer Policies](http://developers.google.com/youtube/terms/developer-policies#j.-child-directed-api-clients) including notifying Google of the child-directed nature of your API Client; each Child-Directed API Client notified to Google as provided in Section III.J.2.b of the Developer Policies or otherwise is referred to herein as a "**Known Child-Directed API Client**", and (b) no YouTube API Services write-based actions (such as, but not limited to, uploading content, commenting and creating/sharing playlists) taken by users of Known Child-Directed API Client will be implemented on YouTube websites, applications, services and products pursuant to Section III.J (API Clients Directed to Children) of the Developer Policies. Please see Section III.J (API Clients Directed to Children) of the Developer Policies for more information.
        
    4. If your API Client is **not** a Child-Directed API Client, you must implement **one** of the following: (a) enable users of your non-Child-Directed API Client to designate their content as Made for Kids via your API Client **before** they can upload their content to YouTube websites, applications, services or products; or (b) notify users of your non-Child-Directed API Client **within** such API Client that if they upload content to YouTube websites, applications, services or products that is Made for Kids, then they must immediately go to YouTube on desktop to declare their content as Made for Kids. See here for more information on determining content as [Made for Kids](https://support.google.com/youtube/answer/9528076).
        
    
    9.2 **Notice to EU Users.** For users in the European Union, you and your API Client(s) must comply with the EU User Consent Policy currently located at [http://www.google.com/about/company/user-consent-policy.html](http://www.google.com/about/company/user-consent-policy.html).
    
10. 10\. Brand Features and Attribution
    -----------------------------------
    
    **Brand Features and Attribution.**
    
    10.1 **License Grant.** YouTube grants you a personal, non-transferable, non-assignable, non-sublicensable, non-exclusive, revocable and limited license to display YouTube Brand Features that are specified in the YouTube Branding Guidelines on or through your API Client(s) only in accordance with the YouTube Branding Guidelines and these Terms of Service.
    
    10.2 **Restrictions.** All use of the YouTube Brand Features (including any associated goodwill) will inure to YouTube’s benefit. You irrevocably assign and will assign to YouTube any right, title, and interest that you obtain in any of the YouTube Brand Features. You will not, at any time, challenge or assist others to challenge the validity of the YouTube Brand Features or their registration (except to the extent you cannot give up that right by law) and you will not attempt to register any trade names, trademarks, service marks, logos or domain names confusingly similar to the YouTube Brand Features.
    
    10.3 **Attribution.** All API Clients must provide proper attribution in accordance with the YouTube Branding Guidelines and these Terms of Service (where applicable) when using the YouTube Brand Features. YouTube reserves the right to determine whether your attribution(s) and display of the YouTube Brand Features comply with the YouTube Branding Guidelines and these Terms of Service. YouTube reserves the right to terminate your license to display the YouTube Brand Features at any time.
    
11. 11\. Proprietary Rights Notices
    -------------------------------
    
    **Proprietary Rights Notices.** You will not remove, obscure, or alter any YouTube or Google terms of service or any links to or notices of those terms, or any copyright, trademark, or other proprietary rights notices; or falsify or delete any author attributions, legal notices, or other labels of the origin or source of material. Where such notices do not appear on, or are not provided through, the YouTube API Services, you agree to display such notices in accordance with the YouTube Branding Guidelines as applicable.
    
12. 12\. Third-Party Rights
    -----------------------
    
    **Third-Party Rights.** You and your API Client(s) will not, and you will require those acting on your behalf and your users to not, infringe or violate third-party rights, including intellectual property rights and other proprietary right, confidentiality, privacy right, or right of publicity.
    
13. 13\. Publicity
    --------------
    
    **Publicity.** YouTube may use your company or organization name (or personal name if an individual), product names or logos in presentations, marketing materials, customer lists, financial reports, website listings of customers, research and marketing case studies, and other marketing-related activities, including producing and distributing incidental depictions such as screenshots, video, or other content from your API Client(s). You grant to YouTube and its Affiliates a non-exclusive, irrevocable, royalty-free, worldwide license to display your company or organization name (or personal name if an individual), product name or logos for the above purposes. You must not make any public statements regarding your access to, or use of, the YouTube API Services that suggests partnership with, or sponsorship or endorsement by, YouTube without YouTube’s prior review and written approval.
    
14. 14\. Modification to the YouTube API Services
    ---------------------------------------------
    
    **Modification to the YouTube API Services.**
    
    14.1 **Right to Modify.** YouTube is constantly innovating and as part of this continuing innovation, YouTube may alter or discontinue any aspect of the YouTube API Services (including any specifications, protocols, or methods of accessing any aspect of the YouTube API Services) as applied to any specific YouTube API Services user or API Client, category of users or API Clients, or all users or API Clients, at any time and without notice or announcement. YouTube will try to give you reasonable advance notice or to make a prior announcement.
    
    14.2 **Backward Incompatible Changes.** When YouTube intends to make backwards incompatible changes to the YouTube API Services, YouTube will announce such change on the YouTube Developer Site and try to continue to maintain the software code for the impacted version(s) of the YouTube API Services for six (6) months from the date such backwards incompatible changes are announced, in its reasonable determination.
    
    14.3 **Special Terms.** Special terms apply to specific versions of the YouTube API Services that are identified as "**Subject API Services**" at [https://developers.google.com/youtube/terms/subject-api-services](http://developers.google.com/youtube/terms/subject-api-services). YouTube will use reasonable efforts to continue to maintain the software code for the Subject API Services for one year from February 10, 2017,
    
    1. unless YouTube is required by law, court order, or third-party relationship (including changes in law or relationships) to make those changes earlier;
    2. unless doing so could create a privacy, security or other risk, or substantial economic or material technical burden; or
    3. except for any features included in the Subject API Services that are not, or no longer, available on, or through, the YouTube products, services, applications or websites (e.g., www.youtube.com, YouTube mobile application) excluding the YouTube API Services.
    
    After February 10, 2018, YouTube may alter or discontinue the Subject API Services in accordance with Sections 14.1 and 14.2 above.
    
15. 15\. Usage and Quotas
    ---------------------
    
    **Usage and Quotas.** YouTube may set a quota on usage of any YouTube API Services at any time as applied to any specific YouTube API Services user or API Client, category of users or API Clients, or all users or API Clients. You and your API Client(s) will not, and will not attempt to, exceed or circumvent use or quota restrictions. YouTube may specify additional requirements relating to use or quotas including in the Developer Policies.
    
16. 16\. No Implied Rights
    ----------------------
    
    **No Implied Rights.**
    
    16.1 **Ownership.** As between you and YouTube, YouTube, its Affiliates, and its and their licensors and suppliers, retain all rights in, title to, interest in, and ownership of (including all intellectual property rights (e.g., all patent, trademark, copyright, trade secret, and other proprietary rights) in and to) all YouTube API Services (including all API Data), YouTube Brand Features, the YouTube Developer Site, the Agreement, YouTube Confidential Information, all YouTube websites, applications, products and services, all underlying technology and computer programming, and all derivative works of any of the foregoing ("**YouTube Property**"). As between you and YouTube, you retain all rights in, title to, interest in and ownership of your API Client(s), excluding any YouTube Property.
    
    16.2 **No Other Rights.** Except for the express rights contained in the Agreement, YouTube grants you no other rights or licenses (whether express, implied, by virtue of estoppel or exhaustion, or otherwise) to the YouTube Property or any of YouTube’s or its Affiliates’ intellectual property rights.
    
    16.3 **No Licenses or Rights to Patents or Content.** Without limiting the generality of the foregoing, no rights or licenses are granted under any patents owned or controlled by YouTube or its Affiliates, and no rights or licenses are granted to reproduce or distribute audiovisual content or make audiovisual content available in any manner other than through the use of the YouTube API Services in accordance with the Agreement. All rights not expressly granted to you are reserved by YouTube.
    
17. 17\. Non-exclusive
    ------------------
    
    **Non-exclusive.** The Agreement is a non-exclusive agreement. You acknowledge and agree that YouTube and its Affiliates may be developing, and may develop in the future, websites, applications, products or services that compete with the YouTube API Services, your API Client(s), or any other products or services, and YouTube and its Affiliates have no obligation to make any of these products or services available to you.
    
18. 18\. Confidentiality
    --------------------
    
    **Confidentiality.** YouTube’s communications to you and the YouTube API Services may contain YouTube Confidential Information. If you receive any YouTube Confidential Information, then you will keep it confidential, not use it except in connection with your permitted use of the YouTube API Services under the Agreement, and not disclose it to any third party without YouTube’s prior written consent; however, you may disclose YouTube Confidential Information when compelled to do so by law if you provide YouTube reasonable prior written notice, unless a court of competent jurisdiction orders that YouTube not receive prior notice.
    
19. 19\. Exclusion of Warranties
    ----------------------------
    
    **Exclusion of Warranties.**
    
    19.1 **No Warranties.** NO CONDITIONS, WARRANTIES OR OTHER TERMS APPLY TO ANY SERVICE, SOFTWARE, OR OTHER GOODS OR SERVICES SUPPLIED BY YOUTUBE, ITS AFFILIATES OR ANY OF ITS AND THEIR RESPECTIVE OFFICERS, DIRECTORS, EMPLOYEES, AGENTS, SHAREHOLDERS, SUPPLIERS, LICENSORS, LICENSEES, ASSIGNS, OR SUCCESSORS ("**RELATED PARTIES**") UNDER THE AGREEMENT UNLESS EXPRESSLY STATED SET OUT IN THE AGREEMENT.
    
    19.2 **As Available.** YOU EXPRESSLY UNDERSTAND AND AGREE THAT YOUR AND YOUR API CLIENT(S)’ ACCESS TO, AND USE OF, THE YOUTUBE API SERVICES IS AT YOUR SOLE RISK AND THAT THE YOUTUBE API SERVICES ARE PROVIDED "AS IS" AND "AS AVAILABLE."
    
    19.3 **Additional Disclaimers.** TO THE EXTENT PERMITTED BY APPLICABLE LAW, YOUTUBE, ITS AFFILIATES AND RELATED PARTIES FURTHER EXPRESSLY DISCLAIM ALL WARRANTIES AND CONDITIONS OF ANY KIND, WHETHER EXPRESS, IMPLIED OR STATUTORY, INCLUDING ANY IMPLIED WARRANTIES AND CONDITIONS OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NON-INFRINGEMENT. ADDITIONALLY, YOUTUBE, ITS AFFILIATES AND RELATED PARTIES DO NOT REPRESENT OR WARRANT TO YOU THAT:
    
    1. THE YOUTUBE API SERVICES WILL MEET YOUR REQUIREMENTS;
    2. THE YOUTUBE API SERVICES WILL BE UNINTERRUPTED, TIMELY, SECURE, OR ERROR-FREE;
    3. THE YOUTUBE API SERVICES WILL BE ACCURATE, RELIABLE, COMPLETE, CONTINUE TO EXIST, OR OTHERWISE VALID; OR
    4. DEFECTS IN THE OPERATION OR FUNCTIONALITY OF ANY ASPECT OF THE YOUTUBE API SERVICES, INCLUDING ANY SOFTWARE, CODE, CONTENT (INCLUDING AUDIOVISUAL CONTENT), DATA, SUPPORT OR ANYTHING ELSE PROVIDED TO YOU AND YOUR API CLIENT(S) AS PART OF, OR IN CONNECTION WITH, THE YOUTUBE API SERVICES, WILL BE CORRECTED.
    
    19.4 **No External Warranties.** NO ADVICE OR INFORMATION, WHETHER ORAL OR WRITTEN, OBTAINED BY YOU FROM YOUTUBE, ITS AFFILIATES OR RELATED PARTIES, OR AS PART OF, OR IN CONNECTION WITH, THE YOUTUBE API SERVICES, WILL CREATE ANY WARRANTY NOT EXPRESSLY STATED IN THE AGREEMENT.
    
    19.5 **API Data Content.** THE CONTENT PROVIDED AS PART OF API DATA INCLUDES VIDEOS, AUDIO, GRAPHICS, PHOTOS, TEXT, INTERACTIVE FEATURES, SOFTWARE, AND OTHER MATERIALS, INCLUDING MUSIC, SOUNDS, COMMENTS, SCRIPTS, AND AUDIOVISUAL COMBINATIONS. YOUTUBE IS A PROVIDER OF HOSTING SERVICES FOR CONTENT AND YOUTUBE IS NOT RESPONSIBLE FOR THE AVAILABILITY, ACCURACY, USEFULNESS, SAFETY, OR LEGALITY OF SUCH CONTENT, INCLUDING CONTENT THAT MAY BE OFFENSIVE, INDECENT, DEFAMATORY, OBJECTIONABLE, OR THAT MAY VIOLATE THIRD-PARTY RIGHTS OR APPLICABLE LAWS OR REGULATIONS. ANY API DATA IS OBTAINED BY YOU AND YOUR API CLIENT(S) AT YOUR OWN DISCRETION AND RISK AND YOU WILL BE SOLELY RESPONSIBLE FOR ANY DAMAGE TO YOUR OR YOUR USERS’ COMPUTER SYSTEM(S) OR DEVICE(S), LOSS OF DATA, OR ANY OTHER DAMAGE OR INJURY THAT RESULTS FROM ANY ASPECT OF THE YOUTUBE API SERVICES.
    
    19.6 **Third-Party Services.** THE YOUTUBE API SERVICES MAY CONTAIN LINKS TO THIRD PARTY WEBSITES AND ONLINE SERVICES THAT ARE NOT OWNED OR CONTROLLED BY YOUTUBE. YOUTUBE HAS NO CONTROL OVER, AND ASSUMES NO RESPONSIBILITY FOR, SUCH WEBSITES AND ONLINE SERVICES.
    
20. 20\. Limitation of Liability
    ----------------------------
    
    **Limitation of Liability.**
    
    20.1 **Limitations.**
    
    1. TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, YOUTUBE, ITS AFFILIATES AND RELATED PARTIES ARE NOT RESPONSIBLE FOR LOST PROFITS, REVENUES, OR DATA, FINANCIAL LOSSES OR DIRECT, INDIRECT, SPECIAL, CONSEQUENTIAL, EXEMPLARY, OR PUNITIVE DAMAGES, OR OTHER LIABILITY, WHETHER IN AN ACTION IN CONTRACT, TORT (INCLUDING NEGLIGENCE) OR OTHERWISE.
        
    2. TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, YOUTUBE, ITS AFFILIATES AND RELATED PARTIES ARE NOT LIABLE FOR ANY LOSS OR DAMAGE WHETHER OR NOT YOUTUBE, ITS AFFILIATES AND RELATED PARTIES HAVE BEEN ADVISED OF OR SHOULD HAVE BEEN AWARE OF THE POSSIBILITY OF ANY SUCH LOSSES OR DAMAGES. TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, YOUTUBE’S TOTAL AGGREGATE LIABILITY UNDER OR ARISING OUT OF THE AGREEMENT IS LIMITED TO THE AMOUNT PAID BY YOU TO YOUTUBE TO ACCESS OR USE THE YOUTUBE API SERVICES FOR THE SIX MONTHS PRIOR TO THE EVENT GIVING RISE TO THE LIABILITY OR US$1,000.00, WHICHEVER IS HIGHER.
        
    
    20.2 **Additional Limitations.** TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, YOUTUBE, ITS AFFILIATES AND RELATED PARTIES ARE NOT LIABLE FOR ANY DAMAGES THAT MAY RESULT FROM:
    
    1. PROVIDING, REMOVING, MODIFYING, SUSPENDING OR TERMINATING ANY ASPECT OF THE YOUTUBE API SERVICES (INCLUDING FEATURES, FUNCTIONS, SUPPORT FOR YOUTUBE API SERVICES (IF ANY), API DATA, AND ANY CONTENT INCLUDING AUDIO VISUAL CONTENT (IN WHOLE OR IN PART)), OR THE AGREEMENT (IN WHOLE OR IN PART), WITH RESPECT TO ANY SPECIFIC YOUTUBE API SERVICES USER OR API CLIENT, CATEGORY OF USERS OR API CLIENTS, OR ALL USERS, OR API CLIENTS; OR
        
    2. CONTENT SUBMITTED TO YOUTUBE WEBSITES, APPLICATIONS, SERVICES AND PRODUCTS BY USERS OR OTHER THIRD PARTIES, OR FOR THE DEFAMATORY, OFFENSIVE, OR ILLEGAL CONDUCT OF ANY SUCH PERSONS OR ENTITIES.
        
21. 21\. Indemnification
    --------------------
    
    **Indemnification.** You will indemnify, defend (at YouTube’s option) and hold YouTube, its Affiliates, and Related Parties harmless against any claim, costs, losses, damages, liabilities, judgments, fees (including reasonable fees of attorneys and other professionals), and expenses arising out of or in connection with any claim, action or proceeding (any and all of which are "**Claims**") by a third party arising out of (i) access to, or any use of any YouTube API Services by you, those acting on your behalf, your API Client(s), or any of your users; (ii) actual or alleged violation of the Agreement (or any portion thereof) by you, those acting on your behalf, your API Client(s), or any of your users, including actual or alleged infringement of any third-party right (including any intellectual property or other proprietary right, confidentiality, privacy right, or right of publicity) by you, those acting on your behalf, your API Client(s), or any of your users; or (iii) any content, data, technology or materials provided or contributed by, or through, you, those acting on your behalf, your API Client(s), or any of your users, and not by YouTube, its Affiliates and Related Parties.
    
    YouTube may, at its sole discretion, elect for you to assume control of the defense of the Claim for which you are required to indemnify YouTube and Related Parties under this Section 21. If the defense or settlement is assumed by you, YouTube may at any time thereafter elect to appoint its own counsel (at its own expense); or YouTube may take over control of the defense and settlement of such Claim. You will not settle any Claim without YouTube’s prior written consent. Both parties will provide reasonable assistance to the other as may be required in order to defend any relevant Claim.
    
22. 22\. Injunctive Relief
    ----------------------
    
    **Injunctive Relief.** You acknowledge that the limitations and restrictions in the Agreement are necessary and reasonable to protect YouTube, and expressly agree that monetary damages may not be a sufficient remedy for your breach of the Agreement. Accordingly, you agree that YouTube will be entitled to seek temporary or permanent injunctive relief against any violation or threatened violation of such limitations or restrictions in any court of competent jurisdiction.
    
23. 23\. Non-assert
    ---------------
    
    **Non-assert.** To the extent permitted by applicable law, during the Agreement, and for three (3) years after any termination or expiration of the Agreement by you or YouTube, you agree not to assert, or authorize, assist or encourage any third party to assert, any patent infringement claim against YouTube, its Affiliates, or any Related Parties, to the extent such claims relate to any of the YouTube API Services that you or your API Client(s) accessed or used. Notwithstanding the foregoing, should YouTube or Google Inc. first file a patent infringement claim in a lawsuit against you (excluding a patent infringement claim brought by YouTube or Google Inc. in response to a lawsuit, for example, as a cross-claim or counterclaim), then the non-assert provision in the first sentence of this Section will be suspended only for the duration of YouTube’s or Google Inc’s first patent infringement claim against you (for example, until such patent infringement claim is settled, withdrawn, dismissed, or otherwise disposed of).
    
24. 24\. Termination
    ----------------
    
    **Termination.**
    
    24.1 **Termination by You.** You may terminate your legal agreement with YouTube by terminating your access to and use of the YouTube API Services (including discontinuing access to and use by your API Client(s) and those acting on your behalf) at any time. You do not need to specifically inform YouTube when you stop using and accessing the YouTube API Services unless otherwise required by YouTube.
    
    24.2 **Termination by YouTube.** Notwithstanding anything to the contrary, YouTube reserves the right to (i) suspend or terminate access to, or use of, any aspects of the YouTube API Services by you, your API Client(s) and those acting on your behalf), and (ii) terminate the Agreement (or any portion thereof), as applied to any specific user or API Client, category of users or API Clients, or all users or API Clients at any time. For example, we may need to exercise such rights in instances of your breach of this Agreement, court order, when we believe there to have been misconduct or conduct which may create potential liability for YouTube or its Affiliates. Although we will try to give you reasonable notice, we have no obligation to do so.
    
    24.3 **Effect of Termination.** Upon any suspension, notice of any discontinuance, or termination (whether by you or YouTube), you will immediately stop accessing and using all YouTube Property and delete all YouTube API Services (including all API Data) and YouTube Confidential Information in your possession or control, including from your servers. At YouTube’s request, you will certify your deletion of all YouTube API Services (including all API Data) and YouTube Confidential Information in your possession or control in writing that is signed by your authorized representative who has the authority to bind you. YouTube may independently communicate with any account owner whose account(s) are associated with credentials assigned to you or your API Client(s) to provide notice of both the suspension or termination of your access to, or use of, the YouTube API Services and the display of any advertisements associated with your API Client(s) (where applicable).
    
    24.4 **Termination of Support or Modification Efforts.** If YouTube elects to provide you or your API Client(s) with support or modification for the YouTube API Services, this support or modification may be suspended or terminated by YouTube at any time without notice to you, as applied to any specific YouTube API Services user or API Client, category of users or API Clients, or all users or API Clients.
    
    24.5 **No Obligation to Provide.** YouTube is under no obligation to provide the YouTube API Services. It is solely your responsibility at all times to be prepared to conduct your business and operate your API Client(s) without access to any aspect of the YouTube API Services.
    
    24.6 **Survival.** The following Sections of these Terms of Service will continue to apply indefinitely even upon any termination or expiration of the Agreement as applied to any specific user or API Client, category of users or API Clients, or all users or API Clients at any time: 1 (Definitions), 2.1, 2.3 and 2.4 (The Agreement), 3.3 (Permitted Access and Use of the YouTube API Services), 8 (Security) to the extent applicable data is in the process of deletion upon termination or expiration of the Agreement, 10.2 (Brand Features and Attribution), 13 (Publicity), 16 (No Implied Rights), 17 (Non-exclusive), 18 (Confidentiality), 19 (Exclusion of Warranties), 20 (Limitation of Liability), 21 (Indemnification), 22 (Injunctive Relief), 24 (Termination), and 25 (General Legal Terms).
    
25. 25\. General Legal Terms
    ------------------------
    
    **General Legal Terms.**
    
    25.1 **Entire Agreement.** The Agreement controls the relationship between you and YouTube and constitutes the entire agreement between such parties with respect to the subject matter hereof.
    
    25.2 **Third-Party Beneficiary.** Each Affiliate of YouTube is a third-party beneficiary under the Agreement and is entitled to directly rely on and enforce any right or benefit provided to it under the Agreement. There are no other third-party beneficiaries under the Agreement.
    
    25.3 **No Waiver.** YouTube will not be treated as having waived any rights by not exercising (or delaying the exercise of) any rights under the Agreement. A waiver will be effective only if YouTube expressly states in writing signed by an authorized representative that YouTube is waiving a specified term of the Agreement.
    
    25.4 **Severability.** If it turns out that a particular provision of the Agreement is found to be not enforceable, that provision will be modified by the court of competent jurisdiction to the extent necessary to create an enforceable provision that reflects the parties' intention as closely as possible. If that is not possible, it will be deemed deleted and the rest of the Agreement will continue in force unaffected.
    
    25.5 **Requesting Agreement Modifications.** You may grant approvals, permissions and consents to YouTube by email, but any modifications requested by you to the Agreement must be made in writing (not including email) and signed by both YouTube and your authorized representative who has the authority to bind you (and only if YouTube agrees to such modification).
    
    25.6 **Notices.** All notices to YouTube must be in the English language, in writing, and sent to our corporate headquarters address listed on our website via first class or air mail or overnight courier, and are deemed given upon receipt.
    
    25.7 **Assignment of the Agreement.** YouTube may transfer or assign the Agreement, including any rights and licenses granted under it, to a third party, but you may not.
    
    25.8 **Relationship of the Parties.** You are not YouTube’s legal partner or agent; the parties are independent contractors.
    
    25.9 **Change of Control.** If you or any party operating your API Client(s) on your behalf experience a change of control (for example, through a stock purchase or sale, merger or other form of corporate transaction), you will provide to YouTube a written notice detailing the change of control within 15 calendar days after the change of control via [this form](https://support.google.com/youtube/contact/yt_api_change_of_control_form). YouTube will review the completed form and if it is not approved within 45 calendar days after the change of control, your project ID will automatically terminate.
    
    25.10 **YouTube Approvals.** YouTube may deny or grant any consents, approvals, or permissions that are expressly contemplated under the Agreement or otherwise requested by you at our discretion.
    
    25.11 **Governing Law and Venue.** The laws of California, U.S.A., excluding California’s conflict of laws rules, will apply to any disputes arising out of or relating to the Agreement or the YouTube API Services. Subject to Section 22 (Injunctive Relief), all claims arising out of or relating to the Agreement or the YouTube API Services will be litigated exclusively in the federal or state courts of Santa Clara County, California, U.S.A., and you and YouTube consent to personal jurisdiction in those courts.
    
    25.12 **Limitation on Actions.** TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, YOU AND YOUTUBE AGREE THAT ANY CAUSE OF ACTION ARISING OUT OF OR RELATED TO THE YOUTUBE API SERVICES MUST COMMENCE WITHIN ONE YEAR AFTER THE CAUSE OF ACTION ACCRUES. OTHERWISE, SUCH CAUSE OF ACTION IS PERMANENTLY BARRED.
    
    25.13 **Translations.** Any local language translation (where applicable) exists for reference purposes only, and only the English version will be legally binding. If there is any inconsistency between the two versions, the English version shall control.