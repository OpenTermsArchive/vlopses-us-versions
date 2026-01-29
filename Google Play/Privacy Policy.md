User Data
=========

You must be transparent in how you handle user data (for example, information collected from or about a user, including device information). That means disclosing the access, collection, use, handling, and sharing of user data from your app, and limiting the use of the data to the policy compliant purposes disclosed. Please be aware that any handling of personal and sensitive user data is also subject to additional requirements in the "Personal and Sensitive User Data" section below. In addition to this and the other Play developer program policies, you must at all times comply with privacy and data protection laws applicable in the jurisdictions in which you offer your products or services. For example, if you offer your services to users in the European Union, note that the French Data Protection Authority (CNIL) adopted [guidance on best practices for protection of personal data](https://www.cnil.fr/en/mobile-applications-cnil-publishes-its-recommendations-better-privacy-protection) within the mobile environment that may be helpful for you to refer to.

If you include third party code (for example, an SDK) in your app, you must ensure that the third party code used in your app, and that third party’s practices with respect to user data from your app, are compliant with Google Play Developer Program policies, which include use and disclosure requirements. For example, you must ensure that your SDK providers do not sell personal and sensitive user data from your app. This requirement applies regardless of whether user data is transferred after being sent to a server, or by embedding third-party code in your app.

#### [COLLAPSE ALL](https://support.google.com/googleplay/android-developer/answer/9888076) [EXPAND ALL](#1&2&3&4&5&6&7&87&9)

#### Personal and Sensitive User Data

Personal and sensitive user data includes, but isn't limited to, personally identifiable information, financial and payment information, authentication information, phonebook, contacts, [device location](https://developer.android.com/training/location), SMS and call-related data, [health data](https://support.google.com/googleplay/android-developer/answer/12261419#health_apps), [Health Connect](https://support.google.com/googleplay/android-developer/answer/9888170#ahp) data, inventory of other apps on the device, microphone, camera, and other sensitive device or usage data. If your app handles personal and sensitive user data, then you must:

*   Limit the access, collection, use and sharing of personal and sensitive user data acquired through the app to app and service functionality and policy-conforming purposes reasonably expected by the user:
    *   Apps that extend usage of personal and sensitive user data for serving advertising must comply with Google Play’s [Ads policy](https://support.google.com/googleplay/android-developer/answer/9857753#location-data).

*   You may also transfer data as necessary to [service providers](https://support.google.com/googleplay/android-developer/answer/10787469#service-provider&zippy=%2Csharing%2Cdata-sharing) or for legal reasons such as to comply with a valid governmental request, applicable law, or as part of a merger or acquisition with legally adequate notice to users.
*   Handle all personal and sensitive user data securely, including transmitting it using modern cryptography (for example, over HTTPS).
*   Use a runtime permissions request whenever available, prior to accessing data gated by [Android permissions](https://developer.android.com/guide/topics/permissions/overview).
*   Not sell personal and sensitive user data.
    *   "Sale" means the exchange or transfer of personal and sensitive user data to a [third party](https://support.google.com/googleplay/android-developer/answer/10787469#first-and-third&zippy=%2Csharing%2Cdata-sharing) for monetary consideration.
        *   User-initiated transfer of personal and sensitive user data (for example, when the user is using a feature of the app to transfer a file to a third party, or when the user chooses to use a dedicated purpose research study app), is not regarded as sale.

#### Prominent Disclosure & Consent Requirement

In cases where your app’s access, collection, use, or sharing of personal and sensitive user data may not be within the reasonable expectation of the user of the product or feature in question (for example, if data collection occurs in the background when the user is not engaging with your app), you must meet the following requirements:

**Prominent disclosure: You must provide an in-app disclosure of your data access, collection, use, and sharing. The in-app disclosure:**

*   Must be within the app itself, not only in the app description or on a website;
*   Must be displayed in the normal usage of the app and not require the user to navigate into a menu or settings;
*   Must describe the data being accessed or collected;
*   Must explain how the data will be used and/or shared;
*   Cannot only be placed in a privacy policy or terms of service; and
*   Cannot be included with other disclosures unrelated to personal and sensitive user data collection.

**Consent and runtime permissions: Requests for in-app user consent and runtime permission requests must be immediately preceded by an in-app disclosure that meets the requirement of this policy. The app's request for consent:**

*   Must present the consent dialog clearly and unambiguously;
*   Must require affirmative user action (for example, tap to accept, tick a check-box);
*   Must not interpret navigation away from the disclosure (including tapping away or pressing the back or home button) as consent;
*   Must not use auto-dismissing or expiring messages as a means of obtaining user consent; and
*   Must be granted by the user before your app can begin to collect or access the personal and sensitive user data.

Apps that rely on other legal bases to process personal and sensitive user data without consent, such as a legitimate interest under the EU GDPR, must comply with all applicable legal requirements and provide appropriate disclosures to the users, including in-app disclosures as required under this policy.

To meet policy requirements, it’s recommended that you reference the following example format for Prominent Disclosure when it’s required:

*   “\[This app\] collects/transmits/syncs/stores \[type of data\] to enable \["feature"\], \[in what scenario\]."
*   _Example: “Fitness Funds collects location data to enable fitness tracking even when the app is closed or not in use and is also used to support advertising.”_
*   _Example: “Call buddy collects read and write call log data to enable contact organization even when the app is not in use.”_

If your app integrates third party code (for example, an SDK) that is designed to collect personal and sensitive user data by default, you must, within 2 weeks of receipt of a request from Google Play (or, if Google Play’s request provides for a longer time period, within that time period), provide sufficient evidence demonstrating that your app meets the Prominent Disclosure and Consent requirements of this policy, including with regard to the data access, collection, use, or sharing via the third party code.

Examples of common violations

*   An app collects device location but does not have a prominent disclosure explaining which feature uses this data and/or indicates the app’s usage in the background.
*   An app has a runtime permission requesting access to data before the prominent disclosure which specifies what the data is used for.
*   An app that accesses a user's inventory of installed apps and doesn't treat this data as personal or sensitive data subject to the above Privacy Policy, data handling, and Prominent Disclosure and Consent requirements.
*   An app that accesses a user's phone or contact book data and doesn't treat this data as personal or sensitive data subject to the above Privacy Policy, data handling, and Prominent Disclosure and Consent requirements.
*   An app that records a user’s screen and doesn't treat this data as personal or sensitive data subject to this policy.
*   An app that collects [device location](https://developer.android.com/training/location) and does not comprehensively disclose its use and obtain consent in accordance with the above requirements.
*   An app that uses restricted permissions in the background of the app including for tracking, research, or marketing purposes and does not comprehensively disclose its use and obtain consent in accordance with the above requirements. 
*   An app with an SDK that collects personal and sensitive user data and doesn’t treat this data as subject to this User Data Policy, access, data handling (including disallowed sale), and prominent disclosure and consent requirements.

Refer to this [article](https://support.google.com/googleplay/android-developer/answer/11150561) for more information on the Prominent Disclosure and Consent requirement.

#### **Restrictions for Personal and Sensitive Data Access**

In addition to the requirements above, the table below describes requirements for specific activities.

|     |     |
| --- | --- |
| **Activity** | **Requirement** |
| Your app handles financial or payment information or government identification numbers | Your app must never publicly disclose any personal and sensitive user data related to financial or payment activities or any government identification numbers. |
| Your app handles non-public phonebook or contact information | We don't allow unauthorized publishing or disclosure of people's non-public contacts. |
| Your app contains anti-virus or security functionality, such as anti-virus, anti-malware, or security-related features | Your app must post a privacy policy that, together with any in-app disclosures, explain what user data your app collects and transmits, how it's used, and the type of parties with whom it's shared. |
| Your app targets children | Your app must not include an SDK that is not approved for use in child-directed services. See [Designing Apps for Children and Families](https://support.google.com/googleplay/android-developer/answer/9893335) for full policy language and requirements. |
| Your app collects or links persistent device identifiers (for example, IMEI, IMSI, SIM Serial #, etc.) | Persistent device identifiers may not be linked to other personal and sensitive user data or resettable device identifiers except for the purposes of<br><br>*   Telephony linked to a SIM identity (for example, wifi calling linked to a carrier account), and<br>*   Enterprise device management apps using device owner mode.<br><br>These uses must be prominently disclosed to users as specified in the [User Data policy](https://support.google.com/googleplay/android-developer/answer/10144311).<br><br>Please [consult this resource](https://developer.android.com/training/articles/user-data-ids) for alternative unique identifiers.<br><br>Please read the [Ads policy](https://support.google.com/googleplay/android-developer/answer/9857753) for additional guidelines for Android Advertising ID. |

#### Data safety section

All developers must complete a clear and accurate Data safety section for every app detailing collection, use, and sharing of user data. The developer is responsible for the accuracy of the label and keeping this information up-to-date. Where relevant, the section must be consistent with the disclosures made in the app’s privacy policy. 

Please refer to [this article](https://support.google.com/googleplay/android-developer/answer/10787469#types) for additional information on completing the Data safety section.

#### Privacy Policy

All apps must post a privacy policy link in the designated field within Play Console, and a privacy policy link or text within the app itself. The privacy policy must, together with any in-app disclosures, comprehensively disclose how your app accesses, collects, uses, and shares user data, not limited by the data disclosed in the Data safety section. This must include: 

*   Developer information and a privacy point of contact or a mechanism to submit inquiries.
*   Disclosing the types of personal and sensitive user data your app accesses, collects, uses, and shares; and any parties with which any personal or sensitive user data is shared.
*   Secure data handling procedures for personal and sensitive user data.
*   The developer’s data retention and deletion policy.
*   Clear labeling as a privacy policy (for example, listed as “privacy policy” in title).

The entity (for example, developer, company) named in the app’s Google Play store listing must appear in the privacy policy or the app must be named in the privacy policy. Apps that do not access any personal and sensitive user data must still submit a privacy policy. 

Please make sure your privacy policy is available on an active, publicly accessible and non-geofenced URL (no PDFs) and is non-editable.

#### Account Deletion Requirement

If your app allows users to create an account from within your app, then it must also allow users to request for their account to be deleted. Users must have a readily discoverable option to initiate app account deletion from within your app and outside of your app (for example, by visiting your website). A link to this web resource must be entered in the designated URL form field within Play Console.

When you delete an app account based on a user’s request, you must also delete the user data associated with that app account. Temporary account deactivation, disabling, or “freezing” the app account does not qualify as account deletion. If you need to retain certain data for legitimate reasons such as security, fraud prevention, or regulatory compliance, you must clearly inform users about your data retention practices (for example, within your privacy policy).

To learn more about account deletion policy requirements, please review this [Help Center](https://support.google.com/googleplay/android-developer/answer/13327111) article. For additional information on updating your Data safety form, visit this [article](https://support.google.com/googleplay/android-developer/answer/10787469).

#### **Usage of App Set ID**

Android will introduce a new ID to support essential use cases such as analytics and fraud prevention. Terms for the use of this ID are below.

*   **Usage**: App set ID must not be used for ads personalization and ads measurement.
*   **Association with personally-identifiable information or other identifiers:** App set ID may not be connected to any Android identifiers (for example, AAID) or any personal and sensitive data for advertising purposes.
*   **Transparency and consent:** The collection and use of the app set ID and commitment to these terms must be disclosed to users in a legally adequate privacy notification, including your privacy policy. You must obtain users’ legally valid consent where required. To learn more about our privacy standards, please review our [User Data policy](https://support.google.com/googleplay/android-developer/answer/10144311?visit_id=637570411965975172-4240498562&rd=1).

#### **EU-U.S., UK, and Swiss Data Privacy Frameworks**

If you access, use, or process personal information made available by Google that directly or indirectly identifies an individual and that originated in the European Economic Area, United Kingdom, or Switzerland (“EU Personal Information”), then you must:

*   Comply with all applicable privacy, data security, and data protection laws, directives, regulations, and rules;
*   Access, use or process EU Personal Information only for purposes that are consistent with the consent obtained from the individual to whom the EU Personal Information relates;
*   Implement appropriate organizational and technical measures to protect EU Personal Information against loss, misuse, and unauthorized or unlawful access, disclosure, alteration and destruction; and
*   Provide the same level of protection as is required by the [Data Privacy Framework Principles](https://www.dataprivacyframework.gov/program-articles/Participation-Requirements-Data-Privacy-Framework-\(DPF\)-Principles) or the applicable transfer mechanism as described in the [Google Controller-Controller Data Protection Terms](https://business.safety.google/controllerterms/).

You must monitor your compliance with these conditions on a regular basis. If, at any time, you cannot meet these conditions (or if there is a significant risk that you will not be able to meet them), you must immediately notify us by email to [data-protection-office@google.com](mailto:data-protection-office@google.com) and immediately either stop processing EU Personal Information or take reasonable and appropriate steps to restore an adequate level of protection.

Choose a section to give feedback on

- - -

Permissions and APIs that Access Sensitive Information
======================================================

_**Disclaimer:** Policy summaries are overviews only; always refer to the full policy for compliance. The full policy takes precedence in case of conflict_

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy** **Summary**

To promote user trust, Google Play mandates that requesting permissions and APIs that access sensitive user data must be necessary for the app's core functionalities as promoted in your Google Play listing and limited to user consented purposes.  Sensitive data must never be misused, under-disclosed, or accessed unnecessarily. Request permissions and sensitive APIs incrementally, explaining each level. Use data only as consented to, and obtain new consent for other purposes. Please review the full policy to ensure compliance.

Requests for permission and APIs that access sensitive information should make sense to users. You may only request permissions and APIs that access sensitive information that are necessary to implement current features or services in your app that are promoted in your Google Play listing. You may not use permissions or APIs that access sensitive information that give access to user or device data for undisclosed, unimplemented, or disallowed features or purposes. Personal or sensitive data accessed through permissions or APIs that access sensitive information may never be sold nor shared for a purpose facilitating sale.

Request permissions and APIs that access sensitive information to access data in context (via incremental requests), so that users understand why your app is requesting the permission. Use the data only for purposes that the user has consented to. If you later wish to use the data for other purposes, you must ask users and make sure they affirmatively agree to the additional uses.

* * *

Restricted Permissions
----------------------

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy** **Summary**

To safeguard user privacy, Google Play defines restricted permissions, subjecting them to additional requirements and mandates apps to responsibly use these permissions and not to manipulate users into granting access. Respect user choices when they decline permission requests and provide alternatives. Be aware that certain restricted permissions might have further additional requirements. Please review the full policy to ensure compliance.

![](//storage.googleapis.com/support-kms-prod/9vOsGjf1MLJLdX41RAT7hMOW0TMAPDdE0cJD) **Full Policy**

In addition to the above, restricted permissions are permissions that are designated as [Dangerous](https://developer.android.com/guide/topics/permissions/overview#dangerous_permissions), [Special](https://developer.android.com/guide/topics/permissions/overview#special_permissions),  [Signature](https://developer.android.com/guide/topics/permissions/overview#signature_permissions), or as documented below. These permissions are subject to the following additional requirements and restrictions:

*   User or device data accessed through Restricted Permissions is considered as personal and sensitive user data. The requirements of the [User Data policy](https://support.google.com/googleplay/android-developer/answer/10144311?) apply.
*   Respect users’ decisions if they decline a request for a Restricted Permission, and users may not be manipulated or forced into consenting to any non-critical permission. You must make a reasonable effort to accommodate users who do not grant access to sensitive permissions (for example, allowing a user to manually enter a phone number if they’ve restricted access to Call Logs).
*   Use of permissions in violation of Google Play [malware policies](https://support.google.com/googleplay/android-developer/answer/9888380) (including [Elevated Privilege Abuse](https://support.google.com/googleplay/android-developer/answer/9888380)) is expressly prohibited.

Certain Restricted Permissions may be subject to additional requirements as detailed below. The objective of these restrictions is to safeguard user privacy. We may make limited exceptions to the requirements below in very rare cases where apps provide a highly compelling or critical feature and where there is no alternative method available to provide the feature. We evaluate proposed exceptions against the potential privacy or security impacts on users.

![](//storage.googleapis.com/support-kms-prod/9B2Sqd9OZ9ln7qXLJLiNLhqLQTHRQZKDDRpa) **Key Considerations**

|     |     |
| --- | --- |
| **Do** | **Don't** |
| If a user denies a restricted permission, your app must honor that decision without manipulation. | Don't use permissions to violate Google Play's [Malware](https://support.google.com/googleplay/android-developer/answer/9888380) policy, including [Elevated Privilege Abuse](https://support.google.com/googleplay/android-developer/answer/9888380#elevated-privilege-abuse). |
| Offer a different way to perform a function if a user denies a permission, such as allowing manual data entry. | Don't manipulate or deceive users. Never pressure or trick users into granting permissions. |
| Follow the [User Data](https://support.google.com/googleplay/android-developer/answer) policy, because all data accessed through these permissions is sensitive. | Don't deny a user a reasonable alternative if they decline a Restricted Permission; ensure the app remains functional. |
| Request dangerous permissions (for example, `READ_CALENDAR`) with a runtime request and a clear explanation. | Don't request without justification. Only request a restricted permission for a compelling, critical feature that has no alternative. |
| Direct users to the system settings page for approval of special permissions (for example, `SYSTEM_ALERT_WINDOW`). |     |

* * *

SMS and Call Log Permissions
----------------------------

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy** **Summary**

Google Play imposes strict restrictions on accessing highly sensitive SMS and Call Log data. Your app must be the designated default handler for SMS, Phone, or Assistant to request these permissions. Usage is limited _only_ to documented core app functionality that is absolutely essential for your app's primary purpose. This data must never be used for advertising or any other unapproved purpose.  Please review the full policy to ensure compliance.

![](//storage.googleapis.com/support-kms-prod/9vOsGjf1MLJLdX41RAT7hMOW0TMAPDdE0cJD) **Full Policy**

SMS and Call Log Permissions are regarded as personal and sensitive user data subject to the [Personal and Sensitive Information](https://support.google.com/googleplay/android-developer/answer/9888076#personal_sensitive) policy, and the following restrictions:

| Restricted Permission | Requirement |
| --- | --- |
| Call Log permission group (for example, `READ_CALL_LOG`, `WRITE_CALL_LOG`, `PROCESS_OUTGOING_CALLS`) | It must be actively registered as the default Phone or Assistant handler on the device. |
| SMS permission group (for example, `READ_SMS`, `SEND_SMS`, `WRITE_SMS`, `RECEIVE_SMS`, `RECEIVE_WAP_PUSH`, `RECEIVE_MMS`) | It must be actively registered as the default SMS or Assistant handler on the device. |

Apps lacking default SMS, Phone, or Assistant handler capability may not declare use of the above permissions in the manifest. This includes placeholder text in the manifest. Additionally, apps must be actively registered as the default SMS, Phone, or Assistant handler before prompting users to accept any of the above permissions and must immediately stop using the permission when they’re no longer the default handler. The permitted uses and exceptions are available on [this Help Center page](https://support.google.com/googleplay/android-developer/answer/9047303).

Apps may only use the permission (and any data derived from the permission) to provide approved core app functionality Core functionality is defined as the main purpose of the app. This may include a set of core features, which must all be prominently documented and promoted in the app’s description. Without the core feature(s), the app is “broken” or rendered unusable. The transfer, sharing, or licensed use of this data must only be for providing core features or services within the app, and its use may not be extended for any other purpose (for example, improving other apps or services, advertising, or marketing purposes). You may not use alternative methods (including other permissions, APIs, or third-party sources) to derive data attributed to Call Log or SMS related permissions.

![](//storage.googleapis.com/support-kms-prod/9B2Sqd9OZ9ln7qXLJLiNLhqLQTHRQZKDDRpa) **Key Considerations**

|     |     |
| --- | --- |
| **Do** | **Don't** |
| Submit a [declaration form](https://goo.gle/play-permission-decl-form) in your Play Console. | Don't request SMS/Call Log permissions without a core need justification. |
| Clearly document the core functionality requiring access to your users. | Don't use this data for advertising or other purposes. |
| Use policy-compliant alternatives like the [SMS Retriever API](https://developers.google.com/identity/sms-retriever/overview) where possible. | Don't store or share unnecessary SMS or Call Log data. |
| Stop accessing data immediately upon losing default handler status. | Don't attempt to derive this data using alternative methods. |
| Review the [permitted uses and exceptions](https://support.google.com/googleplay/android-developer/answer/10208820) of the SMS and Call log permissions. |     |

* * *

Location Permissions
--------------------

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy** **Summary**

To protect user privacy, the background location policy requires apps to provide a strong justification and obtain explicit user consent for access. Device location data is limited to essential functions that directly benefit the user and are central to the app's core purpose; it is never permitted solely for advertising or analytics. Minimize your requests, choosing lesser sensitive options like coarse location and foreground access whenever possible. Foreground Services access of device location must be user-initiated and temporary, while background is only for critical features. Please review the full policy to ensure compliance.

![](//storage.googleapis.com/support-kms-prod/9vOsGjf1MLJLdX41RAT7hMOW0TMAPDdE0cJD) **Full Policy**

[Device location](https://developer.android.com/training/location) is regarded as personal and sensitive user data subject to the [Personal and Sensitive Information](https://support.google.com/googleplay/android-developer/answer/9888076#personal_sensitive) policy and the [Background Location policy](https://support.google.com/googleplay/android-developer/answer/9799150?hl=en#zippy=), and the following requirements:

*   Apps may not access data protected by location permissions (for example, `ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION`, `ACCESS_BACKGROUND_LOCATION`) after it is no longer necessary to deliver current features or services in your app.
*   You should never request location permissions from users for the sole purpose of advertising or analytics. Apps that extend permitted usage of this data for serving advertising must be in compliance with our [Ads Policy](https://support.google.com/googleplay/android-developer/answer/9857753).
*   Apps should request the minimum scope necessary (for example, coarse instead of fine, and foreground instead of background) to provide the current feature or service requiring location and users should reasonably expect that the feature or service needs the level of location requested. For example, we may reject apps that request or access background location without compelling justification.
*   Background location may only be used to provide features beneficial to the user and relevant to the core functionality of the app.

Apps are allowed to access location using foreground service (when the app only has foreground access for example, "while in use") permission if the use:

*   has been initiated as a continuation of an in-app user-initiated action, and
*   is terminated immediately after the intended use case of the user-initiated action is completed by the application.

Apps designed specifically for children must comply with the [Designed for Families](https://support.google.com/googleplay/android-developer/answer/9893335#designed_for_families_prog)policy.

For more information on the policy requirements, please see [this help article](https://support.google.com/googleplay/android-developer/answer/9799150?hl=en&ref_topic=2364761).

![](//storage.googleapis.com/support-kms-prod/9B2Sqd9OZ9ln7qXLJLiNLhqLQTHRQZKDDRpa) **Key Considerations**

|     |     |
| --- | --- |
| **Do** | **Don't** |
| Comply with the [Designed for Families](https://support.google.com/googleplay/android-developer/answer/9893335?sjid=7274498547371890152-NC#designed_for_families_prog) policy for apps targeting children. | Don't use [device location](https://developer.android.com/develop/sensors-and-location/location) solely for advertising or analytics purposes. |
| Review [important permission requirements](https://goo.gle/play-help-background-location) before you submit your app for publishing. | Don't access data after it's no longer needed. |
| Complete the [Console declaration](https://goo.gle/play-permission-decl-form) for [background location](https://support.google.com/googleplay/android-developer/answer/9799150?hl=en&sjid=7274498547371890152-NC#zippy=). | Don't request device location for apps directed at children. |
|     | Don't sell device location. |

* * *

All Files Access Permission
---------------------------

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy** **Summary**

Google Play policy treats access to user files and directories as sensitive and high risk access, so we restrict use of the `` `MANAGE_EXTERNAL_STORAGE` `` permission on Android 11+. You must have essential core app functionality that requires broad access to this permission for a user-facing purpose, and never for third parties. This helps prevent unnecessary data collection and protects users' privacy. Apps requesting this permission must clearly prompt users so they can make an informed privacy decision, and get approval through Play’s app review. Please review the full policy to ensure compliance.

![](//storage.googleapis.com/support-kms-prod/9vOsGjf1MLJLdX41RAT7hMOW0TMAPDdE0cJD) **Full Policy**

Files and directory attributes on a user’s device are regarded as personal and sensitive user data subject to the [Personal and Sensitive Information](https://support.google.com/googleplay/android-developer/answer/9888076/) policy and the following requirements:

*   Apps should only request access to device storage which is critical for the app to function, and may not request access to device storage on behalf of any third-party for any purpose that is unrelated to critical user-facing app functionality.
*   Android devices running R or later, will require the [`` `MANAGE_EXTERNAL_STORAGE` ``](https://developer.android.com/reference/android/Manifest.permission#%3Ccode%3EMANAGE_EXTERNAL_STORAGE%3C/code%3E) permission in order to manage access in shared storage. All apps that target R and request broad access to shared storage (“All files access”) must successfully pass an appropriate access review prior to publishing. Apps allowed to use this permission must clearly prompt users to enable “All files access” for their app under “Special app access” settings. For more information on the R requirements, please see this [help article](https://support.google.com/googleplay/android-developer/answer/9956427).

![](//storage.googleapis.com/support-kms-prod/9B2Sqd9OZ9ln7qXLJLiNLhqLQTHRQZKDDRpa) **Key Considerations**

|     |     |
| --- | --- |
| **Do** | **Don't** |
| Prioritize using privacy-friendly alternatives instead, like [Storage Access Framework](https://developer.android.com/guide/topics/providers/document-provider) or [MediaStore API](https://developer.android.com/training/data-storage/shared/media). | Don't request the `MANAGE_EXTERNAL_STORAGE` permission for non-permitted use-cases like Media Files access or any File selection activity where the user manually selects individual files. |
| [Declare](https://goo.gle/play-permission-decl-form) this permission when you submit a declaration form in your Play Console. | Don't misrepresent the core functionality of your app. |
| Clearly define and document your app's core functionality in your app review. | Don't store or share data beyond essential and disclosed needs. |
| Clearly prompt users to enable “[All files access](https://developer.android.com/about/versions/11/privacy/storage#all-files-access)” for your app under “Special app access” settings. |     |
| Ensure you review the [Android R requirements](https://goo.gle/play-help-all-files-access) for more information. |     |

* * *

Photo and Video Permissions
---------------------------

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy****Summary**

To protect user privacy and security, Google Play requires apps that request `` `READ_MEDIA_IMAGES` `` or `` `READ_MEDIA_VIDEO` `` permissions to show strong, legitimate core use cases for persistent or frequent access to photos and videos. If your app does _not_ qualify for this access, you should remove the permissions. Instead, use a system picker like the more privacy-preserving Android Photo Picker for one-time or infrequent needs. Please review the full policy to ensure compliance.

![](//storage.googleapis.com/support-kms-prod/9vOsGjf1MLJLdX41RAT7hMOW0TMAPDdE0cJD) **Full Policy**

Photos and videos on a user’s device are regarded as personal and sensitive user data subject to Google Play's [User Data policy](https://support.google.com/googleplay/android-developer/answer/10144311?visit_id=638283094302146844-815564681&rd=1). Apps may only access photos and videos for purposes directly related to app functionality, and may not request access on behalf of any third-party for any purpose unrelated to user-facing app functionality. For a more privacy preserving experience, we encourage the use of a system picker such as the [photo picker](https://developer.android.com/training/data-storage/shared/photopicker).

Apps requiring broad access to photos and video files located in shared storage on devices must successfully pass an appropriate access review and demonstrate a core use case that requires persistent or frequent photo/video access of files located in shared storage. Apps that have a one-time or infrequent need to access these files are requested to use a system picker, such as the Android [photo picker](https://developer.android.com/training/data-storage/shared/photopicker).

Broad access to photos and videos are also subject to the following requirements:

*   Apps that target Android 13 (API level 33) or later, require the [`` `READ_MEDIA_IMAGES` ``](https://developer.android.com/reference/android/Manifest.permission#%3Ccode%3EREAD_MEDIA_IMAGES%3C/code%3E) permission or [`` `READ_MEDIA_VIDEO` ``](https://developer.android.com/reference/android/Manifest.permission#%3Ccode%3EREAD_MEDIA_VIDEO%3C/code%3E) permission in order to obtain broad access to photos or video files located in shared storage on the device. All apps that target Android 13 and above and request the `READ_MEDIA_IMAGES` or `READ_MEDIA_VIDEO` permissions must successfully pass an appropriate access review before publishing.
    *   Apps that request access to the `` `READ_MEDIA_VIDEO` `` or `` `READ_MEDIA_IMAGES` `` permission must successfully demonstrate a core use case that requires persistent or frequent need of photo/video access located in shared storage.

If your app does not require or qualify for broad access to the `` `READ_MEDIA_VIDEO` `` or `` `READ_MEDIA_IMAGES` `` permissions, you must remove it from your app’s manifest in order to successfully meet the policy review requirements.

In accordance with the [`Restricted Permissions policy`](https://support.google.com/googleplay/android-developer/answer/9888170?hl=en), you must make a reasonable effort to accommodate users who do not grant broad access to media files on their device. This includes gracefully facilitating an accommodative app experience where users can still enjoy the feature or core functionality of your app.

Apps that have a legitimate access case for photos or videos, but do not qualify for the `` `READ_MEDIA_IMAGES` `` nor `` `READ_MEDIA_VIDEO` `` permission may use a system picker such as the [photo picker](https://developer.android.com/training/data-storage/shared/photopicker). For additional information, please see this [Help Center](https://support.google.com/googleplay/android-developer/answer/14115180) article.

![](//storage.googleapis.com/support-kms-prod/9B2Sqd9OZ9ln7qXLJLiNLhqLQTHRQZKDDRpa) **Key Considerations**

|     |     |
| --- | --- |
| **Do** | **Don't** |
| Submit a [declaration form](https://goo.gle/play-permission-decl-form) in your Play Console. | Don't collect more photo or video data than necessary. |
| Use a system picker such as the [photo picker](https://developer.android.com/training/data-storage/shared/photo-picker) if you don’t need broad access. | Don't attempt to bypass or manipulate user consent. |
| Provide evidence to justify your use case during app review. | Don't block or gate functionality if a user declines a non-critical permission. Instead, use a system picker to gracefully handle the file request. |
| Clearly explain to users why your app needs these permissions. |     |
| Review the [Details on Google Play's Photo and Video Permissions policy](https://support.google.com/googleplay/android-developer/answer/14115180) for more information. |     |

* * *

Package (App) Visibility Permission
-----------------------------------

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy** **Summary**

Accessing a user's installed app inventory is sensitive data. Google Play policy strictly limits broad visibility (`` `QUERY_ALL_PACKAGES` ``), allowing it only for core app functionality that requires extensive knowledge of installed apps for interoperability. You must prioritize using finite, targeted queries to access specific apps when possible, which is more privacy-friendly. Under no circumstances can data from the installed app inventory be sold or shared for advertising or analytics monetization. Please review the full policy to ensure compliance.

![](//storage.googleapis.com/support-kms-prod/9vOsGjf1MLJLdX41RAT7hMOW0TMAPDdE0cJD) **Full Policy**

The inventory of installed apps queried from a device are regarded as personal and sensitive user data subject to the [Personal and Sensitive Information](https://support.google.com/googleplay/android-developer/answer/9888076/) policy,  and the following requirements:

Apps that have a core purpose to launch, search, or interoperate with other apps on the device, may obtain scope-appropriate visibility to other installed apps on the device as outlined below:

*   **Broad app visibility:** Broad visibility is the capability of an app to have extensive (or “broad”) visibility of the installed apps (“packages”) on a device.
    *   For apps targeting [API level 30 or later](https://developer.android.com/studio/releases/platforms), broad visibility to installed apps via the [`` `QUERY_ALL_PACKAGES` ``](https://developer.android.com/reference/kotlin/android/Manifest.permission#query_all_packages) permission is restricted to specific use cases where awareness of and/or interoperability with any and all apps on the device are required for the app to function.
        *   You may not use `` `QUERY_ALL_PACKAGES` `` if your app can operate with a more [targeted scoped package visibility declaration](https://developer.android.com/training/basics/intents/package-visibility#declare-other-apps)(for example, querying and interacting with specific packages instead of requesting broad visibility).
    *   Use of alternative methods to approximate the broad visibility level associated with `` `QUERY_ALL_PACKAGES` `` permission are also restricted to user-facing core app functionality and interoperability with any apps discovered via this method.
    *   Please see this [Help Center article](https://support.google.com/googleplay/android-developer/answer/10158779) for allowable use cases for the `` `QUERY_ALL_PACKAGES` `` permission.
*   **Limited app visibility**: Limited visibility is when an app minimizes access to data by querying for specific apps using more targeted (instead of “broad”) methods(for example, querying for specific apps that satisfy your app’s manifest declaration). You may use this method to query for apps in cases where your app has policy compliant interoperability, or management of these apps.
*   Visibility to the inventory of installed apps on a device must be directly related to the core purpose or core functionality that users access within your app.

App inventory data queried from Play-distributed apps may never be sold nor [shared](https://support.google.com/googleplay/android-developer/answer/10787469?hl=en&sjid=9328586825007120077-NA#sharing&zippy=%2Cdata-types%2Cdata-sharing) for analytics or ads monetization purposes.

![](//storage.googleapis.com/support-kms-prod/9B2Sqd9OZ9ln7qXLJLiNLhqLQTHRQZKDDRpa) **Key Considerations**

|     |     |
| --- | --- |
| **Do** | **Don't** |
| Submit a [declaration form](https://goo.gle/play-permission-decl-form) in your Play Console for `QUERY_ALL_PACKAGES` and any other high-risk permissions. | Don't request `QUERY_ALL_PACKAGES` if your need can be met with finite, targeted queries. |
| For your app review, clearly document why your app needs app visibility whether broad or more targeted. | Don't gain broad app visibility via methods not explicitly allowed by policy. |
| Access only the minimum data needed. | Don't provide false information about your app's core functionality or data needs. |
| Review the [Permitted uses of the QUERY\_ALL\_PACKAGES permission](https://support.google.com/googleplay/android-developer/answer/10158779?utm_source=android-studio#zippy=,permitted-uses-of-the-query-all-packages-permission) for allowable use cases. | Don't collect or use unnecessary data from installed app data. |

* * *

Accessibility API
-----------------

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy** **Summary**

Google Play permits the use of the AccessibilityService API across a wide range of applications. However, only services designed to help people with disabilities access their devices or overcome challenges due to their disabilities are eligible to declare themselves as accessibility tools by setting isAccessibilityTool=true in their metadata. These apps are exempt from the prominent disclosure and consent requirements. For all other uses, or if not declaring your app as an accessibility tool, you will be required to complete an accessibility declaration in Play Console and must implement a clear in-app disclosure explaining data access and use, and obtain affirmative user consent. Please review the full policy to ensure compliance.

![](//storage.googleapis.com/support-kms-prod/9vOsGjf1MLJLdX41RAT7hMOW0TMAPDdE0cJD) **Full Policy**

The Accessibility API cannot be used to:

*   Change user settings without their permission or prevent the ability for users to disable or uninstall any app or service unless authorized by a parent or guardian through a parental control app or by authorized administrators through enterprise management software; 
*   Work around Android built-in platform security controls, privacy controls and notifications; or
*   Change or leverage the user interface in a way that is deceptive or otherwise violates Google Play Developer Policies. 

The Accessibility API is not designed and cannot be requested for:

*   remote call audio recording
*   an app that autonomously initiates, plans, and executes actions or decisions

The use of the Accessibility API must be documented in the Google Play listing.

#### Guidelines for **IsAccessibilityTool**

Apps with a core functionality intended to directly support people with disabilities are eligible to use the **IsAccessibilityTool** to appropriately publicly designate themselves as an accessibility app.

Apps not eligible for **IsAccessibilityTool** may not use the flag and must meet prominent disclosure and consent requirements as outlined in the [User Data](https://support.google.com/googleplay/android-developer/answer/10144311?hl=en&ref_topic=9877467) policy as the accessibility related functionality is not obvious to the user. 

Apps must use more narrowly scoped [APIs and permissions](https://developer.android.com/privacy/best-practices#permissions) in lieu of the Accessibility API when possible to achieve the desired functionality. 

Please refer to the [AccessibilityService API](https://support.google.com/googleplay/android-developer/answer/10964491?hl=en) help center article for more information regarding prohibited use cases and guidance for using IsAccessibilityTool.

![](//storage.googleapis.com/support-kms-prod/9B2Sqd9OZ9ln7qXLJLiNLhqLQTHRQZKDDRpa) **Key Considerations**

|     |     |
| --- | --- |
| **Do** | **Don't** |
| [Declare](https://support.google.com/googleplay/android-developer/answer/9214102) `isAccessibilityTool=true` accurately if your app’s main goal is disability support in your service’s metadata file. | Don't misuse the `isAccessibilityTool` flag. Don’t use it if your app is not a disability support tool. |
| Provide a clear Play Console declaration and demo video if using AccessibilityService API. | Don't change user settings without permission, bypass privacy controls, or record remote call audio. |
| Implement clear in-app disclosure and obtain user consent if not a designated accessibility tool. | Don't use the API to autonomously initiate, plan, and execute actions or decisions. |
| Complete an accessibility declaration when you submit a [declaration form](https://support.google.com/googleplay/android-developer/answer/9214102) in your Play Console if you have not declared your app to be an accessibility tool but use the [AccessibilityService API](https://support.google.com/googleplay/android-developer/answer/10964491?utm_source=android-studio). | Don't deceive or mislead users. The API cannot be used to change or leverage the UI in a deceptive way. |
| Limit data collection and use strictly to the disclosed and declared purposes. | Don't collect unnecessary data. The data collected must be strictly limited to the disclosed purposes. |
| Use more narrowly scoped [APIs and permissions](https://developer.android.com/privacy/best-practices#permissions) in lieu of the Accessibility API when possible to achieve the desired functionality. | Don't bypass disclosure requirements. Disclosures cannot be a substitute for privacy policy or other app descriptions. |

* * *

Request Install Packages Permission
-----------------------------------

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy** **Summary**

`` `REQUEST_INSTALL_PACKAGES` `` permission allows apps to request the installation of other app packages. This permission is restricted to the app's core functionality, specifically when the primary purpose directly involves sending, receiving, or enabling user-initiated installation of app packages. Using this permission to update your app, change its functionality or bundle other APKs for silent or unauthorized installation (except enterprise management) is prohibited. All installations must be a direct, active choice by the user. Apps targeting Android 8+ must hold this permission in order to use `` `Intent.ACTION_INSTALL_PACKAGE` ``. Please review the full policy to ensure compliance.

![](//storage.googleapis.com/support-kms-prod/9vOsGjf1MLJLdX41RAT7hMOW0TMAPDdE0cJD) **Full Policy**

The [`` `REQUEST_INSTALL_PACKAGES` ``](https://developer.android.com/reference/android/Manifest.permission#%3Ccode%3EREQUEST_INSTALL_PACKAGES%3C/code%3E) permission allows an application to request the installation of app packages.​​ To use this permission, your app’s core functionality must include:

*   Sending or receiving app packages; and
*   Enabling user-initiated installation of app packages.

Permitted functionalities include:

*   Web browsing or search
*   Communication services that support attachments
*   File sharing, transfer, or management
*   Enterprise device management
*   Backup and restore
*   Device Migration/Phone Transfer
*   Companion app to sync phone to wearable or IoT device (for example, smart watch or smart TV)

Core functionality is defined as the main purpose of the app. The core functionality, as well as any core features that comprise this core functionality, must all be prominently documented and promoted in the app's description.

The `` `REQUEST_INSTALL_PACKAGES` `` permission may not be used to perform self updates, modifications, or the bundling of other APKs in the asset file unless for device management purposes. All updates or installing of packages must abide by Google Play’s [Device and Network Abuse policy](https://support.google.com/googleplay/android-developer/answer/9888379?hl=en&ref_topic=9877467) and must be initiated and driven by the user.

![](//storage.googleapis.com/support-kms-prod/9B2Sqd9OZ9ln7qXLJLiNLhqLQTHRQZKDDRpa) **Key Considerations**

|     |     |
| --- | --- |
| **Do** | **Don't** |
| Clearly and prominently document the core functionality requiring this permission in your app’s Google Play description and when you submit a [declaration form](https://goo.gle/play-permission-decl-form) in your Play Console. | Don't request this permission for a functionality that is not directly related to the primary purpose of your app. This includes Peer-to-Peer (P2P) sharing. P2P must be the primary purpose of the app in order to qualify as a permitted use. |
| Adhere strictly to the permitted functionalities including web browsing/search, file sharing / transfer / management, enterprise device management, backup/restore, device migration / phone transfer, companion app to sync phone to wearable or IoT device. | Don't request this permission when the required task can be done with a less intrusive method. |
| Ensure your app prevents background or unintended installations. All app package installations must be explicitly initiated by the user. | Don't change how your app uses this permission without first revising your Play Console declaration with updated and accurate information. Deceptive and undeclared uses of this permission are prohibited. |

* * *

Body Sensor Permissions
-----------------------

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy** **Summary**

To safeguard user privacy, Google Play mandates that access to highly sensitive body sensor data (such as heart rate, SpO2, and skin temperature) is  subject to our [User Data](https://support.google.com/googleplay/android-developer/answer/10144311) policy and [Health apps](https://support.google.com/googleplay/android-developer/answer/12261419#health_apps) policy.

Starting with Android 16, apps must migrate from the general `android.permission.BODY_SENSORS` permission to new, granular health permissions. For example, you will use `android.permission.health.READ_HEART_RATE` to access heart rate data. This change affects all apps that target Android 16 or higher across all form factors, including Wear OS. For a complete list of changes, see [Behavior changes: Apps targeting Android 16 or higher](https://developer.android.com/about/versions/16/behavior-changes-16) page. We review all requests for body sensor permissions—both legacy and new—to ensure your app's use case directly benefits the user and strictly complies with our policies.

![](//storage.googleapis.com/support-kms-prod/9vOsGjf1MLJLdX41RAT7hMOW0TMAPDdE0cJD) **Full Policy**

Access to data from sensors that measure physical parameters of the body (such as heart rate, SpO₂, and skin temperature) is considered personal and sensitive user data**.** Apps requesting access are subject to the requirements outlined in the [User Data policy](https://support.google.com/googleplay/android-developer/answer/10144311?#personal-sensitive) and the [Health apps policy](https://support.google.com/googleplay/android-developer/answer/12261419?hl=en#:~:text=laws%20and%20regulations.-,Health%20Apps,-If%20your%20app). This applies to requests for `android.permission.BODY_SENSORS` and `android.permission.BODY_SENSORS_BACKGROUND` permissions across all form factors including phones, tablets, and Wear OS devices.

Starting in Android 16, the broad `BODY_SENSORS` permission is being transitioned in favor of granular, more privacy preserving `android.permissions.health.`\* permissions for specific data types (for example, `android.permission.health.READ_HEART_RATE`, `android.permission.health.READ_OXYGEN_SATURATION`, `android.permission.health.READ_SKIN_TEMPERATURE`).

Apps targeting Android 16 or higher must use these specific permissions for APIs previously requiring `BODY_SENSORS`. See the [Behavior changes: Apps targeting Android 16 or higher](https://developer.android.com/about/versions/16/behavior-changes-16) page for full details.

All requests for body sensor permissions (both legacy and new granular permissions) will be reviewed so that the intended use of this personal and sensitive data aligns with approved use cases that directly benefit the user. Approved use cases primarily involve features for fitness and wellness tracking (for example, real-time workout monitoring), medical or condition monitoring, health research (with appropriate approvals), or enhancing wearable companion app features.

For comprehensive policy guidance, including prohibited uses, acceptable use cases, and detailed requirements, see the [Android Health Permissions: Guidance & FAQs](https://support.google.com/googleplay/android-developer/answer/12991134?sjid=16523468427823376810-EU).

|     |     |
| --- | --- |
| **Do** | **Don't** |
| Use specific granular health permissions like `android.permission.health.READ_HEART_RATE` instead of the broad `` `BODY_SENSORS` permission ``. | Don’t declare `` `BODY_SENSORS` `` when a more specific health permission is available. |
| Ensure your app has a core, user-benefiting feature (for example, for fitness tracking or health monitoring) that strictly requires the data. | Don't access data without a clear, direct user benefit. |
| Comply with the [User Data](https://support.google.com/googleplay/android-developer/answer/10144311?#personal-sensitive) and [Health apps](https://support.google.com/googleplay/android-developer/answer/12261419?hl=en#:~:text=laws%20and%20regulations.-,Health%20Apps,-If%20your%20app) policies. | Don't request or use body sensor data for unapproved purposes, such as for general advertising, analytics, or profiling users based on inferred health conditions. |
| Request only the minimum permissions necessary and the specific data required for your app's intended purpose. | Don't ignore or attempt to bypass the fundamental [User Data](https://support.google.com/googleplay/android-developer/answer/10144311?#personal-sensitive) and [Health apps](https://support.google.com/googleplay/android-developer/answer/12261419?hl=en#:~:text=laws%20and%20regulations.-,Health%20Apps,-If%20your%20app) policies. |
| Consult the [Android Health Permissions: Guidance & FAQs](https://support.google.com/googleplay/android-developer/answer/12991134?sjid=16523468427823376810-EU) for a full list of use cases and requirements. |     |

* * *

Health Connect by Android Permissions
-------------------------------------

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy** **Summary**

Access to Health Connect data is restricted to apps with approved health, fitness, medical care, or health research core use cases. You must strictly limit data access to the minimum scope necessary for these approved functions and obtain explicit user consent before sharing any health data with third parties. Transparency is key, so provide clear disclosures and a comprehensive privacy policy explaining data collection, use, management, and deletion. Secure user data against unauthorized access and comply with all applicable laws and regulations (for example, HIPAA, GDPR). Please review the full policy to ensure compliance.

![](//storage.googleapis.com/support-kms-prod/9vOsGjf1MLJLdX41RAT7hMOW0TMAPDdE0cJD) **Full Policy**

[Health Connect](https://developer.android.com/guide/health-and-fitness/health-connect) is an Android platform that allows health and fitness apps to store and share the same on-device data, within a unified ecosystem. It also offers a single place for users to control which apps can read and write health and fitness data, including health records. Health Records may include medical history, diagnoses, treatments, medications, lab results, and other clinical data, obtained from healthcare providers or institutions, or through supported third-party health platforms.

Health Connect supports reading and writing a [variety of data types](https://developer.android.com/reference/kotlin/androidx/health/connect/client/records/package-summary#classes), from steps to body temperature, to health record data.

Data accessed through Health Connect Permissions is regarded as personal and sensitive user data subject to the [User Data policy](https://support.google.com/googleplay/android-developer/answer/10144311). If your app qualifies as a health app or has health-related features and accesses health data including Health Connect data, it must also comply with the [Health apps policy](https://support.google.com/googleplay/android-developer/answer/13996823).

Please see this [Android developer guide](https://developer.android.com/health-and-fitness/guides/health-connect) on how to get started with Health Connect. To request access to Health Connect data types and other FAQs, see [Android Health Permissions: Guidance & FAQs](https://support.google.com/googleplay/android-developer/answer/12991134).

Apps distributed through Google Play must meet the following policy requirements in order to read and/or write data to Health Connect.

![](//storage.googleapis.com/support-kms-prod/9B2Sqd9OZ9ln7qXLJLiNLhqLQTHRQZKDDRpa) **Key Considerations**

|     |     |
| --- | --- |
| **Do** | **Don't** |
| Your app must comply with the [Health apps policy](https://support.google.com/googleplay/android-developer/answer/12261419) if it qualifies as a health app or has health-related features and accesses health data including [Health Connect data](https://developer.android.com/reference/kotlin/androidx/health/connect/client/records/package-summary#classes). | Don't use [Health Connect](https://developer.android.com/health-and-fitness/guides/health-connect) in high-risk apps (for example, aviation, control of life-critical systems such as pacemakers) or in apps that solely target children. |
| See [Android Health Permissions: Guidance and FAQs](https://support.google.com/googleplay/android-developer/answer/12991134) to request access to Health Connect data types and other FAQs. | Don't sell or transfer user data for advertising, creditworthiness, or data brokers. |
| Submit a [declaration form](https://goo.gle/play-permission-decl-form) in your Play Console and provide a clear and detailed justification explaining how your app will use the data to benefit the user. | Don't use with medical devices without required regulatory compliance/clearances. |
| Request only the minimum necessary data types. | Don't access [Health Connect data](https://developer.android.com/reference/kotlin/androidx/health/connect/client/records/package-summary#classes) for secondary or unapproved purposes. |
| Securely handle user data (for example, use modern cryptography). | Don't request data permissions beyond your app's core functionality. |

#### **Appropriate Access to and Use of Health Connect**

Health Connect may only be used in accordance with the applicable policies, terms and conditions, and for approved use cases as set forth in this policy. This means you may only request access to permissions when your application or service meets one of the approved use cases.

Approved use cases include: fitness and wellness, rewards, fitness coaching, corporate wellness, medical care, health research, and games. Applications granted access to these use cases may not extend its use to undisclosed or non-permitted purposes.

Only applications or services with one or more features designed to benefit users' health and fitness are permitted to request access to Health Connect Permissions. These include:

*   Applications or services allowing users **to directly journal, report, monitor, and/or analyze** their physical activity, sleep, mental well-being, nutrition, health measurements, physical descriptions, health records, and/or other health or fitness-related descriptions and measurements.
*   Applications or services allowing users **to store their physical activity, sleep, mental well-being, nutrition, health measurements, physical descriptions**, **health records,** and/or other health or fitness-related descriptions and measurements on their device, and share their data with other on-device apps that satisfy these use cases.
*   Applications or services enabling users to manage chronic conditions, medical treatments, or care support.

Access to Health Connect may not be used in violation of this policy or other applicable Health Connect terms and conditions or policies, including for the following purposes:

*   Do not use Health Connect in developing, or for incorporation into, applications, environments or activities where the use or failure of Health Connect could reasonably be expected to lead to death, personal injury, harm to individuals, or environmental or property damage (such as the creation or operation of nuclear facilities, air traffic control, life support systems, or weaponry).
*   Do not access data obtained through Health Connect using headless apps. Apps must display a clearly identifiable icon in the app tray, device app settings, notification icons, etc.
*   Do not use Health Connect with apps that sync data between incompatible devices or platforms.
*   Do not use Health Connect to connect to applications, services, or features that solely target children.
*   Take reasonable and appropriate steps to protect all applications or systems that make use of Health Connect against unauthorized or unlawful access, use, destruction, loss, alteration, or disclosure.

It is also your responsibility to ensure compliance with any regulatory or legal requirements that may apply based on your intended use of Health Connect and any data from Health Connect. For example, if you are a covered entity or business associate subject to the Health Insurance Portability and Accountability Act (HIPAA), you must comply with applicable requirements for your access and use of information from Health Connect. If you are a developer subject to the General Data Protection Regulation (GDPR) for EU users, you must similarly comply with your obligations under the GDPR. These laws and regulations may require you to execute additional agreements prior to sharing data (for example, a Business Associate Agreement or Data Processing Agreement) with the relevant entities involved in your processing activities. It is also the responsibility of app developers to determine whether their activities require such agreements. Developers must provide evidence of such agreement or compliance to Google upon request.

Except as explicitly noted in the labeling or information provided by Google for specific Google products or services, Google does not endorse the use of or warrant the accuracy of any data contained in Health Connect for any use or purpose, and, in particular, for research, health, or medical uses. Google disclaims all liability associated with use of data obtained through Health Connect.

#### **Limited Use**

When using Health Connect, data access and use must adhere to specific limitations:

*   Data use should be limited to providing or improving the appropriate use case or features visible in the application's user interface.
*   User data may only be transferred to third parties with explicit user consent: for security purposes (for example, to investigate abuse), to comply with applicable laws or regulations, or as part of mergers/acquisitions.
*   Human access to user data is restricted unless explicit user consent is obtained, for security purposes, to comply with laws, or when aggregated for internal operations as per legal requirements.
*   **All other transfers, uses, or sale of Health Connect data is prohibited, including:**
    *   Transferring or selling user data to third parties like advertising platforms, data brokers, or any information resellers.
    *   Transferring, selling, or using user data for serving ads, including personalized or interest-based advertising.
    *   Transferring, selling, or using user data to determine credit-worthiness or for lending purposes.
    *   Transferring, selling, or using user data with any product or service that may qualify as a medical device, unless the medical device app complies with all applicable regulations, including obtaining necessary clearances or approvals from relevant regulatory bodies (for example, U.S. FDA) for its intended use of Health Connect data, and the user has provided explicit consent for such use.
    *   Transferring, selling, or using user data for any purpose or in any manner involving Protected Health Information (as defined by HIPAA) unless user-initiated and in compliance with HIPAA regulations.

#### **Minimum Scope**

You must only request access to the permissions that are necessary to implementing your product's features or services. Such access requests should be specific and limited to the data which is needed.

#### **Transparent and Accurate Notice and Control**

Health Connect handles health and fitness data that includes personal and sensitive information. Developers must provide clear and accessible disclosures about their data practices through a comprehensive privacy policy. These disclosures must include:

*   Accurate representation of the identity of the application or service requesting access to user data.
*   Clear and accurate information explaining the types of data being accessed, requested, and/or collected. The data must be related to a user-facing feature or recommendation offered in your app.
*   Explanation for how the data will be used and/or shared: if you request data for one reason, but the data will also be utilized for a secondary purpose, you must disclose all use cases to users.
*   User help documentation explaining how users can manage and delete their data from the app, and what happens to the data when an account is deactivated and/or deleted.
*   Information regarding handling all personal and sensitive user data securely, including transmitting it using modern cryptography (for example, over HTTPS).

For more information on requirements for apps connecting to Health Connect, please see this [Help Center](https://support.google.com/googleplay/android-developer/answer/12991134) article.

* * *

VPN Service
-----------

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy** **Summary**

The VpnService base class allows developers to create secure VPN solutions. Google Play permits its use only for apps with core VPN functionality or those requiring a remote server for essential features such as parental control, app usage tracking, device security, network tools, web browsers, or carrier services. It is paramount that VpnService is never used to collect personal or sensitive user data without prominent disclosure and explicit consent. Furthermore, redirecting or manipulating user traffic from other apps for monetization is strictly prohibited. All apps using VpnService must clearly document this in their Google Play listing and encrypt all data from the device to the VPN tunnel endpoint. Please review the full policy to ensure compliance.

![](//storage.googleapis.com/support-kms-prod/9vOsGjf1MLJLdX41RAT7hMOW0TMAPDdE0cJD) **Full Policy**

The [VpnService](https://developer.android.com/reference/android/net/VpnService) is a base class for applications to extend and build their own VPN solutions. Only apps that use the VpnService and have VPN as their core functionality can create a secure device-level tunnel to a remote server. Exceptions include apps that require a remote server for core functionality such as:

*   Parental control and enterprise management apps
*   App usage tracking
*   Device security apps (for example, anti-virus, mobile device management, firewall)
*   Network related tools (for example, remote access)
*   Web browsing apps
*   Carrier apps that require the use of VPN functionality to provide telephony or connectivity services

The VpnService cannot be used to:

*   Collect personal and sensitive user data without prominent disclosure and consent.
*   Redirect or manipulate user traffic from other apps on a device for monetization purposes (for example, redirecting ads traffic through a country different than that of the user).

Apps that use the VpnService must:

*   Document use of the VpnService in the Google Play listing, and
*   Must encrypt the data from the device to VPN tunnel end point, and
*   Abide by all [Developer Program Policies](https://support.google.com/googleplay/android-developer/topic/9858052?hl=en) including the [Ad Fraud](https://support.google.com/googleplay/android-developer/answer/9969955#zippy=%2Cexamples-of-common-violations), [Permissions](https://support.google.com/googleplay/android-developer/answer/9888170), and [Malware](https://support.google.com/googleplay/android-developer/answer/9888380#1&2&3&4&5&6&7&87&9) policies.

|     |     |
| --- | --- |
| **Do** | **Don't** |
| Document use of the [VpnService](https://developer.android.com/reference/android/net/VpnService) clearly in the Google Play listing. | Don't use [VpnService](https://developer.android.com/reference/android/net/VpnService) for purposes other than core VPN or specified exceptions. |
| Must encrypt the data from the device to the VPN tunnel end point. | Don't collect personal and sensitive user data without prominent disclosure and consent. |
| Ensure your app's core functionality aligns with VPN use or permitted exceptions. | Don't redirect or manipulate user traffic from other apps on a device for monetization purposes (for example, redirecting ads traffic through a country different than that of the user). |
| Provide prominent in-app disclosure and obtain explicit consent for any sensitive data collection. |     |

* * *

Exact Alarm Permission
----------------------

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy** **Summary**

`USE_EXACT_ALARM` permission on Android 13+ is a highly restricted permission used only for apps whose core, user-facing functionality genuinely requires precise timing, like dedicated alarm, timer, or calendar applications with event notifications. If your app does _not_ have this specific core need, consider using `` `SCHEDULE_EXACT_ALARM` `` permission instead. It provides the same functionality but access must be granted by the user. This policy prevents misuse that impacts system resources. Please review the full policy to ensure compliance.

![](//storage.googleapis.com/support-kms-prod/9vOsGjf1MLJLdX41RAT7hMOW0TMAPDdE0cJD) **Full Policy**

A new permission, `` `USE_EXACT_ALARM` ``, will be introduced that will grant access to [exact alarm functionality](https://developer.android.com/about/versions/13/features#use-exact-alarm-permission) in apps starting with Android 13 (API target level 33). 

`` `USE_EXACT_ALARM` `` is a restricted permission and apps must only declare this permission if their core functionality supports the need for an exact alarm. Apps that request this restricted permission are subject to review, and those that do not meet the acceptable use case criteria will be disallowed from publishing on Google Play.

**Acceptable use cases for using the Exact Alarm Permission**

Your app must use the `` `USE_EXACT_ALARM` `` functionality only when your app’s core, user facing functionality requires precisely-timed actions, such as:

*   The app is an alarm or timer app.
*   The app is a calendar app that shows event notifications.

If you have a use case for exact alarm functionality that’s not covered above, you should evaluate if using `` `SCHEDULE_EXACT_ALARM` `` as an alternative is an option.

For more information on exact alarm functionality, please see this [developer guidance](https://developer.android.com/about/versions/13/features#use-exact-alarm-permission).

![](//storage.googleapis.com/support-kms-prod/9B2Sqd9OZ9ln7qXLJLiNLhqLQTHRQZKDDRpa) **Key Considerations**

|     |     |
| --- | --- |
| **Do** | **Don't** |
| Request the auto granted version of the permission, `USE_EXACT_ALARM`, only if your app's core functionality is of alarm or calendar. | Don't use this permission for non-critical features that do not directly contribute to the app's main purpose. |
| Use `SCHEDULE_EXACT_ALARM` instead if the above criteria is not met. |     |
| Complete Play Console [declaration](https://goo.gle/play-permission-decl-form) to indicate app functionality. |     |
| Review the [new permission to use exact alarms](https://developer.android.com/about/versions/13/features#use-exact-alarm-permission) for more information on exact alarm functionality. |     |

* * *

Full-Screen Intent Permission
-----------------------------

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy** **Summary**

On Android 14+, the `` `USE_FULL_SCREEN_INTENT` `` permission is auto-granted _only_ for apps whose core function is setting alarms or handling calls. For any other use case, you must obtain explicit user consent and clearly explain your need. This policy prevents the misuse of full-screen intents for non-critical purposes and requires that your use does not interfere with or disrupt the user's device, other apps, or overall usability. Please review the full policy to ensure compliance.

![](//storage.googleapis.com/support-kms-prod/9vOsGjf1MLJLdX41RAT7hMOW0TMAPDdE0cJD) **Full Policy**

For apps targeting Android 14 (API target level 34) and above, [`` `USE_FULL_SCREEN_INTENT` ``](https://developer.android.com/reference/android/app/Notification.Builder#setFullScreenIntent\(android.app.PendingIntent,%20boolean\)) is a [special apps access permission](https://developer.android.com/training/permissions/requesting-special). Apps will only be automatically granted to use the `` `USE_FULL_SCREEN_INTENT` `` permission if the core functionality of their app falls under one of the below categories that require high priority notifications:

*   setting an alarm
*   receiving phone or video calls

Apps that request this permission are subject to review, and those that do not meet the above criteria will not be automatically granted this permission. In that case, apps must request permission from the user to use `` `USE_FULL_SCREEN_INTENT` ``.

As a reminder, any usage of the `` `USE_FULL_SCREEN_INTENT` `` permission must comply with all [Google Play Developer Policies](https://play.google.com/about/developer-content-policy/?authuser=0#!?modal_active=none), including our [Mobile Unwanted Software](https://support.google.com/googleplay/android-developer/answer/9970222), [Device and Network Abuse](https://support.google.com/googleplay/android-developer/answer/9888379?hl=en), and [Ads](https://support.google.com/googleplay/android-developer/answer/9857753?hl=en&sjid=11744761627827448774-NA) policies. Full-screen intent notifications cannot interfere with, disrupt, damage, or access the user’s device in an unauthorized manner. Additionally, apps should not interfere with other apps or the usability of the device.

Learn more about the `` `USE_FULL_SCREEN_INTENT` `` permission in our [Help Center](https://support.google.com/googleplay/android-developer/answer/13392821#full_screen_intent).

![](//storage.googleapis.com/support-kms-prod/9B2Sqd9OZ9ln7qXLJLiNLhqLQTHRQZKDDRpa) **Key Considerations**

|     |     |
| --- | --- |
| **Do** | **Don't** |
| Request user consent for the permission and provide a clear explanation for the request if not auto-granted. | Don't use this permission for non-core or low-priority features. |
| Limit use to necessary high-priority notifications/alerts. | Don't use this permission to interfere with devices or other apps. |
| Submit a [declaration form](https://goo.gle/play-permission-decl-form) in your Play Console to establish pre-grant eligibility for the full-screen intent permission if targeting Android 14+ | Don't use this permission for disruptive ads or disruptive notifications. |
| Learn more about the [`` `USE_FULL_SCREEN_INTENT` `` permission](https://support.google.com/googleplay/android-developer/answer/13392821?sjid=7274498547371890152-NC#full_screen_intent) and its requirements. |     |

* * *

Age Signals API and User Data
-----------------------------

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy** **Summary**

To help protect user’s data, you may only use data provided by the Age Signals API to provide age-appropriate experiences in the app receiving this data. These guidelines ensure that you use the API strictly to meet compliance requirements and not for commercial gain or tracking.

![](//storage.googleapis.com/support-kms-prod/9vOsGjf1MLJLdX41RAT7hMOW0TMAPDdE0cJD) **Full Policy**

This policy defines the conditions for your use of the [Age Signals API](https://developer.android.com/google/play/age-signals/overview), which provides access to personal and sensitive user age and parental consent data.

You may only use the data accessed via the Age Signals API for the sole purpose of complying with [applicable legal and regulatory obligations](https://support.google.com/googleplay/android-developer/answer/16569691) such as providing age appropriate experiences within your app.

You are strictly prohibited from using this data for the following purposes, including but not limited to:

*   Advertising, marketing, or personalization purposes, including the serving of targeted ads
*   Data analytics, user profiling, or business intelligence
*   Selling, sharing, or transferring the data to any third party for any reason, except as strictly required by law

![](//storage.googleapis.com/support-kms-prod/9B2Sqd9OZ9ln7qXLJLiNLhqLQTHRQZKDDRpa) **Key Considerations**

|     |     |
| --- | --- |
| **Do** | **Don't** |
| Limit data use to regulatory compliance use cases. | Don't use this data to perform marketing or targeting advertising. |
| Check for parental consent requirements. | Don’t use this data to perform analytics or user profiling. |
| Ensure the user’s experiences match the user’s age. | Don’t share this data with a third-party for any reason except as required by law. |

Choose a section to give feedback on

- - -

Deceptive Behavior
==================

_**Disclaimer:** Policy summaries are overviews only; always refer to the full policy for compliance. The full policy takes precedence in case of conflict_

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy** **Summary**

To uphold user trust, Google Play strictly prohibits all forms of deception. Your app, including any third-party SDKs, ads, or services, must always maintain honesty, transparency, and must never mislead users or enable dishonest behaviors. All metadata, including the store listing, screenshots, and title, must precisely reflect the app's functionality. Apps are prohibited from mimicking other apps or OS warnings. Any modifications to device settings require explicit user consent and must be easily reversible. Should your app require the download of additional assets, you must prompt the user and explicitly disclose the download size first. Please review the full policy to ensure compliance.

![](//storage.googleapis.com/support-kms-prod/9vOsGjf1MLJLdX41RAT7hMOW0TMAPDdE0cJD) **Full Policy**

We don't allow apps that attempt to deceive users or enable dishonest behavior including but not limited to apps which are determined to be functionally impossible. Apps must provide an accurate disclosure, description and images/video of their functionality in all parts of the metadata. Apps must not attempt to mimic functionality or warnings from the operating system or other apps. Any changes to device settings must be made with the user's knowledge and consent and be reversible by the user.

![](//storage.googleapis.com/support-kms-prod/9B2Sqd9OZ9ln7qXLJLiNLhqLQTHRQZKDDRpa) **Key Considerations**

|     |     |
| --- | --- |
| **Do** | **Don't** |
| Ensure your app's title, icon and description accurately reflect its actual functionality. | Don't mislead users about your app's functionality or claim features that are functionally impossible. |
| Provide clear, in-app disclosures and get explicit user consent before making any changes to device settings. | Don’t impersonate other apps, brands, or government entities. |
| Test your app to ensure it performs as users would reasonably expect. | Don’t display ads that mimic system notifications or warnings, making them appear as a part of the device's OS. |

* * *

Misleading Claims
-----------------

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy** **Summary**

To maintain our commitment to a transparent and trustworthy user experience, Google Play prohibits misleading claims or information in apps. This includes misleading information in the description, title, icon and screenshots. Apps must not misrepresent their functionality, or claim impossible features, even if labeled as a joke. You must also avoid improper categorization, false content about elections, and false claims of affiliation with governments or other established entities. For example, you cannot use "Official" in a title without the necessary rights. Please review the full policy to ensure compliance.

![](//storage.googleapis.com/support-kms-prod/9vOsGjf1MLJLdX41RAT7hMOW0TMAPDdE0cJD) **Full Policy**

We don’t allow apps that contain false or misleading information or claims, including in the description, title, icon, and screenshots.

Examples of common violations

*   Apps that misrepresent or do not accurately and clearly describe their functionality:
    *   An app that claims to be a racing game in its description and screenshots, but is actually a puzzle block game using a picture of a car.
    *   An app that claims to be an antivirus app, but only contains a text guide explaining how to remove viruses.
*   Apps that claim functionalities that are not possible to implement, such as insect repellent apps, even if it is represented as a prank, fake, joke, etc.
*   Apps that are improperly categorized, including but not limited to the app rating or app category.
*   Demonstrably deceptive or false content that may interfere with voting processes, or about the outcome of elections.
*   Apps that falsely claim affiliation with a government entity or to provide or facilitate government services for which they are not properly authorized.
*   Apps that falsely claim to be the official app of an established entity. Titles like “Justin Bieber Official” are not allowed without the necessary permissions or rights.

![](//x20web.corp.google.com/teams/play-kmt/no_crawl/arhc/images/quebec_deceptive_example1.png)

(1) Apps that claim functionalities that are not possible to implement (using your phone) as a breathalyzer.

 

![](//storage.googleapis.com/support-kms-prod/9B2Sqd9OZ9ln7qXLJLiNLhqLQTHRQZKDDRpa) **Key Considerations**

|     |     |
| --- | --- |
| **Do** | **Don't** |
| Accurately describe your app's functionality in your store listing, including in the description, title, icon, and screenshots. | Don't misrepresent your app’s core purpose or functionality. |
| Ensure your app's category and rating are correct. | Don't make false claims about functionalities that are not possible to implement. |
| Get all necessary permissions and rights before claiming to be an "official" app. | Don't falsely claim affiliation with a government or an established entity when not properly authorized to do so. |

* * *

Deceptive Device Settings Changes
---------------------------------

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy** **Summary**

Google Play prohibits apps from making changes to a user's device settings or features outside the app without explicit user consent. Even with consent, any changes your app makes must be easily reversible. Modifying settings as a service for third parties or for advertising is also prohibited. Finally, apps must not encourage or incentivize users to remove/disable third-party apps or modify device settings or features with an exception for verifiable security services. Please review the full policy to ensure compliance.

![](//storage.googleapis.com/support-kms-prod/9vOsGjf1MLJLdX41RAT7hMOW0TMAPDdE0cJD) **Full Policy**

We don’t allow apps that make changes to the user’s device settings or features outside of the app without the user’s knowledge and consent. Device settings and features include system and browser settings, bookmarks, shortcuts, icons, widgets, and the presentation of apps on the homescreen.

Additionally, we do not allow:

*   Apps that modify device settings or features with the user’s consent but do so in a way that is not easily reversible.
*   Apps or ads that modify device settings or features as a service to third parties or for advertising purposes.
*   Apps that mislead users into removing or disabling third-party apps or modifying device settings or features.
*   Apps that encourage or incentivize users into removing or disabling third-party apps or modifying device settings or features unless it is part of a verifiable security service.

![](//storage.googleapis.com/support-kms-prod/9B2Sqd9OZ9ln7qXLJLiNLhqLQTHRQZKDDRpa) **Key Considerations**

|     |     |
| --- | --- |
| **Do** | **Don't** |
| Obtain explicit user consent before changing any device settings or features. | Don't modify device settings or features without the user's clear knowledge and consent. |
| Clearly explain what your app will change and why. | Don't mislead or incentivize users to disable or remove other apps. |
| Ensure all user consented changes are easily reversible by the user. | Don't modify device settings or features as a service to third parties or for advertising purposes. |

* * *

Enabling Dishonest Behavior
---------------------------

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy** **Summary**

Google Play prohibits apps from deceiving or enabling users to deceive or mislead others, such as by generating fake IDs, passports, diplomas, social security numbers or credit cards. Your app itself must provide accurate disclosures, titles and descriptions about its functionality and must perform as reasonably and accurately expected by the user. Claiming an app is a "prank" or "for entertainment purposes" does not exempt it from these policies. Please review the full policy to ensure compliance.

![](//storage.googleapis.com/support-kms-prod/9vOsGjf1MLJLdX41RAT7hMOW0TMAPDdE0cJD) **Full Policy**

We don't allow apps that help users to mislead others or are functionally deceptive in any way, including, but not limited to: apps that generate or facilitate the generation of ID cards, social security numbers, passports, diplomas, credit cards, bank accounts, and driver's licenses. Apps must provide accurate disclosures, titles, descriptions, and images/video regarding the app's functionality and/or content and should perform as reasonably and accurately expected by the user.

Additional app resources (for example, game assets) may only be downloaded if they are necessary for the users' use of the app. Downloaded resources must be compliant with all Google Play policies, and before beginning the download, the app should prompt users and clearly disclose the download size.

Any claim that an app is a "prank", "for entertainment purposes" (or other synonym) does not exempt an app from application of our policies.

Examples of common violations

*   Apps that mimic other apps or websites to trick users into disclosing personal or authentication information.
*   Apps that depict or display unverified or real world phone numbers, contacts, addresses, or personally identifiable information of non-consenting individuals or entities.
*   Apps with different core functionality based on a user’s geography, device parameters, or other user-dependent data where those differences are not prominently advertised to the user in the store listing.
*   Apps that change significantly between versions without alerting the user (for example, [‘what’s new’ section](https://support.google.com/googleplay/android-developer/answer/7159011?hl=en)) and updating the store listing.
*   Apps that attempt to modify or obfuscate behavior during review.
*   Apps with content delivery network (CDN) facilitated downloads that fail to prompt the user and disclose the download size prior to downloading.

![](//storage.googleapis.com/support-kms-prod/9B2Sqd9OZ9ln7qXLJLiNLhqLQTHRQZKDDRpa) **Key Considerations**

|     |     |
| --- | --- |
| **Do** | **Don't** |
| Provide an honest and accurate app description, title, and images about its functionality. | Don't generate or facilitate the generation of fake documents. |
| Ensure the app performs as reasonably and accurately expected by the user. | Don't mimic other apps to trick users into disclosing personal and sensitive  information. |
| Alert users and update your store listing  when the app functionality changes. | Don't have different core functionality based on user data or geography without disclosure. |
| Prompt users and explicitly disclose the download size first, if the app requires the download of additional assets. | Don't show different functionality based on user geography or device parameters, or other user-dependent data without prominently advertising it. |

* * *

Manipulated Media
-----------------

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy** **Summary**

To protect users, Google Play prohibits apps from creating, facilitating or promoting false or misleading media, such as images, videos, or audio. This includes apps that perpetuate misleading media that could cause harm regarding sensitive events, politics, or other matters of public concern. Exceptions may be made for obvious satire, parody, or content with clear watermarks or disclaimers, and must comply with existing Google Play developer policies, including prohibiting disallowed content under the [**Restricted Content**](https://support.google.com/googleplay/android-developer/topic/9877466?sjid=4697247637550754979-NC) policies. Please review the full policy to ensure compliance.

![](//storage.googleapis.com/support-kms-prod/9vOsGjf1MLJLdX41RAT7hMOW0TMAPDdE0cJD) **Full Policy**

We don't allow apps that promote or help create false or misleading information or claims conveyed through imagery, audio, videos and/or text. We disallow apps determined to promote or perpetuate demonstrably misleading or deceptive imagery, videos and/or text, which may cause harm pertaining to a sensitive event, politics, social issues, or other matters of public concern.

Exceptions may be provided for public interest, clearly artificial images, manipulated media with user-facing disclaimers or watermarks, or obvious satire or parody.

Manipulated media must comply with existing Google Play developer policies, including prohibiting disallowed content under the [restricted content](https://support.google.com/googleplay/android-developer/topic/9877466) policies.

Examples of common violations

*   Apps using public figures or media from a sensitive event to advertise media altering capability within an app's store listing.
*   Apps that alter media clips to mimic a news broadcast by including names or logos of real news outlets without clear disclaimers or watermarks.
*   Apps with the sole purpose of creating misleading media.
    
    ![](//lh3.googleusercontent.com/mRVacICnbXaC5GPY0SNdp9hKiBxYK0tHUsrSCZ70WK2i2F5kd5g65CD_1-cFFO00w2k=w311)
    
    (1) This app provides functionality to alter media clips to mimic a news broadcast, and add famous or public figures to the clip without a watermark.
    

![](//storage.googleapis.com/support-kms-prod/9B2Sqd9OZ9ln7qXLJLiNLhqLQTHRQZKDDRpa) **Key Considerations**

|     |     |
| --- | --- |
| **Do** | **Don't** |
| Review and comply with all other Google Play policies, especially the [**Restricted Content**](https://support.google.com/googleplay/android-developer/topic/9877466?sjid=4697247637550754979-NC) policy, for any media your app creates or promotes. | Don't create, promote, or help users create demonstrably false or misleading media that could cause harm. |
| Apply clear, visible, and user-facing watermarks or disclaimers to all media (imagery, audio, video, text) that your app manipulates. | Don’t manipulate media related to sensitive events, politics, or social issues in a way that is deceptive or harmful. |
| Ensure any content intended as satire or parody is obvious to the user. | Don’t alter media clips to impersonate or mimic real news broadcasts (for example, by using their logos, names, or branding) unless you include a clear watermark or disclaimer stating it is not. |
| Make sure your app has a clear, legitimate purpose beyond simply creating manipulated media (for example, creative tools, artistic filters). | Don't use a sensitive event or public figures to advertise media alteration capabilities in your app. |

* * *

Behavior Transparency
---------------------

![](//storage.googleapis.com/support-kms-prod/mnzFjyenPky9CIQLLOjVINm80frPgduvyrWP)**Policy** **Summary**

To help ensure user safety and system integrity, Google Play prohibits apps from containing any hidden, dormant, or undocumented features. Your app’s functionality should be reasonably clear to your users. This policy also prohibits any techniques used to evade Google Play’s app reviews. Please review the full policy to ensure compliance.

![](//storage.googleapis.com/support-kms-prod/9vOsGjf1MLJLdX41RAT7hMOW0TMAPDdE0cJD) **Full Policy**

Your app’s functionality should be reasonably clear to users; don't include any hidden, dormant, or undocumented features within your app. Techniques to evade app reviews are not allowed. Apps may be required to provide additional details to ensure user safety, system integrity, and policy compliance.

![](//storage.googleapis.com/support-kms-prod/9B2Sqd9OZ9ln7qXLJLiNLhqLQTHRQZKDDRpa) **Key Considerations**

|     |     |
| --- | --- |
| **Do** | **Don't** |
| Ensure your app's functionality is "what you see is what you get." All features available to the user should be clear and documented in your store listing. | Don't include undocumented or hidden features that are designed to be activated remotely or after a certain amount of time. |
| Make sure your app behaves identically for a regular user and for a Google Play reviewer. | Don't dynamically download and execute code from a remote source that introduces features or functionality not present during the app review. |
| Be prepared to provide Google with a detailed explanation of your app's features and code if they request it for a review. | Don't use techniques to detect the app review environment and change your app's behavior to hide non-compliant features. |
| Ensure all code in your app, including third-party SDKs, is directly related to the app's stated purpose. | Don't intentionally obfuscate code specifically to conceal policy-violating behavior from reviewers. |

Choose a section to give feedback on