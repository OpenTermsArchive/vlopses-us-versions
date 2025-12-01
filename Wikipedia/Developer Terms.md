Other languages:

*   English

|     |     |
| --- | --- |
| [![Wikimedia Foundation mark](//upload.wikimedia.org/wikipedia/commons/thumb/8/8b/Wikimedia-logo_black.svg/40px-Wikimedia-logo_black.svg.png)](https://foundation.wikimedia.org/wiki/File:Wikimedia-logo_black.svg) | **This policy or procedure is maintained by the .**  <br>Please note that in the event of any differences in meaning or interpretation between the original English version of this content and a translation, the original English version takes precedence. |

Version 1.0
-----------

Date: August 26, 2024

### API

The Wikimedia Foundation enforces limits on operators' use of certain APIs, including but not limited to the MediaWiki Action API, the MediaWiki REST API, and the RESTBase API. Some of these limits are described below. The limits in this policy exist to maintain the performance and stability of our APIs, to promote the fair allocation of server resources, and to ensure that community members can use the APIs to further the free knowledge movement. You can read .

In this policy, an "operator" is defined as any person who deploys software that causes our APIs to be called. In other words, the operator controls how often the APIs will be called. For example, this includes people who write on-wiki "gadgets" (even if they do not run them), and people who run bots (even if they did not write them). If you are reading this and looking for useful tips on how to use Wikimedia APIs, then this is probably you. If limits are imposed on an operator's use, they may not circumvent these limits. For example, operators are required to follow all instructions to delay or reduce the rate of further requests they receive in a response from an API. The specific numerical limits on any endpoint may change from time to time (for example, as current and predicted future load changes).

When using Wikimedia APIs, an operator must:

1.  Follow the ;
2.  Follow rate limiting requests (e.g., throttling notification) you may receive;
3.  Follow the requirements of the content licenses when republishing downloaded or cached data; and
4.  Follow the if your software is automatically consuming content at a large scale.

When using Wikimedia APIs, an operator must not:

1.  Send traffic via concurrent connections to Wikimedia APIs resulting in a degradation of service to others or endangering the stability of the site;
2.  Request data at a high rate, far beyond common use cases, such as in spikes or in a manner intentionally meant to circumvent this policy;
3.  Spread Wikimedia API requests over multiple user agents to hide excessive use by a single operator; or
4.  Send high traffic originating from a single source or targeting a specific wiki/resource that ends up blocking others from using or accessing that resource.

Operators should use our APIs within the guidelines described in this policy and other technical documentation for each API. For the avoidance of doubt, the existence of this policy does not require members of the Wikimedia community to get prior permission from the Wikimedia Foundation before using the APIs in a manner consistent with this policy. Rather, we want people to be aware of uses that could result in disruption of their API usage, so operators know how to use Wikimedia's shared resources properly.

If your use case might fall outside the bounds of the policy described here and you would like to receive an exception or clarification, please submit a request to legal![@](//upload.wikimedia.org/wikipedia/commons/thumb/8/88/At_sign.svg/20px-At_sign.svg.png)wikimedia.org.

In situations where a limit may affect an operator's use, the Foundation may contact the operator to discuss the nature of the limits and any exceptions that may be needed. This is only possible if the operator's scripts adhere to the User-Agent policy and include up-to-date contact information.

The Foundation reserves the right to enforce this policy through blocking API access, disabling a program, or any similar action. Any choice to take or not take an enforcement action in a given situation will not be a waiver of any future action under this policy. In situations when this policy is enforced, any action taken can be lifted at the Foundation's discretion if the requesting party takes action to reduce the harm or unfairness caused. For example:

*   Reducing the rate of the API requests being sent;
*   Implementing an exponential backoff, where a throttling notification is sent to the operator, and in response, they slow down their rate of requests automatically; or
*   Following User-Agent naming conventions, as required in the , such that you can be contacted if usage becomes problematic.

### Sub-licensing

Operators (or those acting on their behalf) may not sublicense, lease, assign, or guarantee the availability or functionality of a Wikimedia Foundation-managed API to any third party. It is not permissible to implement an API client that white labels in a manner that obscures the identity of the ultimate service provider of the APIs (the Wikimedia Foundation). For the avoidance of doubt, this term does nothing to limit the use and republication of Wikimedia content in accordance with the free licenses that content is licensed under.

### Retiring APIs

The Foundation may retire or modify APIs. Operators that use APIs beyond the announced end-of-service date should expect the API to become unavailable without further warning or to experience significant degradation in performance. It is expected that operators update to use appropriate alternatives in advance of the end-of-service date. The Foundation may provide notice regarding updates and deprecations of APIs to the contact information that is provided per the User Agent requirements.

### Modifications to this policy

This policy is a public summary of some of the current limitations that the Wikimedia Foundation imposes on operators regarding their use of the Wikimedia APIs. As such, the Wikimedia Foundation may modify the policy in its discretion to more fully describe current limits or reflect future changes.

See also
--------

*   The (August-September 2023)

![](https://foundation.wikimedia.org/wiki/Special:CentralAutoLogin/start?useformat=desktop&type=1x1&usesul3=1)

Retrieved from "[https://foundation.wikimedia.org/w/index.php?title=Policy:Wikimedia\_Foundation\_API\_Usage\_Guidelines&oldid=522696](https://foundation.wikimedia.org/w/index.php?title=Policy:Wikimedia_Foundation_API_Usage_Guidelines&oldid=522696)"

- - -

Other languages:

*   English

**Want to help translate? [Translate the missing messages](https://foundation.wikimedia.org/w/index.php?title=Special:Translate&group=agg-Terms_of_Use&filter=%21translated&action=page&language=).**

|     |     |
| --- | --- |
| [![Wikimedia Foundation mark](//upload.wikimedia.org/wikipedia/commons/thumb/8/8b/Wikimedia-logo_black.svg/40px-Wikimedia-logo_black.svg.png)](https://foundation.wikimedia.org/wiki/File:Wikimedia-logo_black.svg) | **This policy or procedure is maintained by the .**  <br>Please note that in the event of any differences in meaning or interpretation between the original English version of this content and a translation, the original English version takes precedence. |

[![](//upload.wikimedia.org/wikipedia/commons/thumb/4/42/Screenshot_of_a_map_on_Wikivoyage_displaying_San_Francisco%27s_Financial_District.png/250px-Screenshot_of_a_map_on_Wikivoyage_displaying_San_Francisco%27s_Financial_District.png)](https://foundation.wikimedia.org/wiki/File:Screenshot_of_a_map_on_Wikivoyage_displaying_San_Francisco%27s_Financial_District.png)

Screenshot of a dynamic map on English Wikivoyage displaying

### General terms

The Wikimedia Foundation hosts the infrastructure for the [Wikimedia Maps service](https://maps.wikimedia.org/) with the primary purpose of providing maps on the Wikimedia projects, like Wikipedia and Wikimedia Commons. The Wikimedia Maps service is provided openly to the public free of charge. However, we cannot represent or guarantee the truthfulness, accuracy, or reliability of any of the information in maps.

Please review the Wikimedia and . These policies apply to the Wikimedia Maps services, as well as the other Wikimedia projects. If there are any inconsistencies between those policies and this page, the terms on this page will apply.

### Using maps in third-party services

Wikimedia Maps may not be used by third-party services outside of the Wikimedia projects. We may make limited allowances for services that support the Wikimedia projects, such as community tools hosted on Wikimedia Cloud Services.

**We reserve the right to discontinue or change our service, block or limit certain users or applications, or take other measures in cases at our sole discretion at any time without notice.**

If you use the Wikimedia Maps service for your third-party project, please respect our limited services and resources. If you use the service too heavily, it could affect the service's stability for others or degrade our quality of service.

If you are developing an application that uses the Wikimedia Maps service, you must provide a valid that includes your application, version, and sufficient information to easily contact you (e.g., your email address).

The following are prohibited on the Wikimedia Maps service:

1.  Use for anything other than supporting the Wikimedia projects (for example, you may build a tool for Wikipedia editors, but you may not use it for an unrelated app or business)
2.  Excessive downloading (such as downloading significant areas of tiles for later offline usage)
3.  Accessing the service without a proper HTTP User-Agent or
4.  Using the service without compliance with any license or copyright terms

### License and copyright

If you use the Wikimedia Maps service in your third-party project or the Wikimedia projects, you are responsible for complying with the [OpenStreetMap copyright policy](https://www.openstreetmap.org/copyright) and any other terms.

### On Wikimedia projects

*   **Static images of maps:** Static maps may be embedded as part of an article page -- they are simply an image without zoom/pan controls or any other interactivity. Static images of maps can be used under a [Creative Commons Attribution-ShareAlike 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/), with attribution to [this section of the page](https://foundation.wikimedia.org/w/index.php?title=Maps_Terms_of_Use#Where_does_the_map_data_come_from.3F).
*   **Dynamic Maps:** Dynamic maps are interactive views of maps. For example, they may be displayed after you click on a static image of a map embedded in an article, or on the maps link in Commons (in the camera location section) such as this [example image](https://commons.wikimedia.org/wiki/File:%22And_Some_Fell_On_Stony_Ground%22_-_geograph.org.uk_-_184409.jpg) and [associated map](https://commons.wikimedia.org/wiki/File:%22And_Some_Fell_On_Stony_Ground%22_-_geograph.org.uk_-_184409.jpg#/maplink/0). You should keep the credit section in the lower right corner of dynamic maps.

### Disclaimers

While we aim to provide a useful service for the Wikimedia community and beyond, no software is perfect.

**Wikimedia Maps service may undergo future development, so all your use is at your sole risk. We provide Wikimedia Maps on an "as is" and "as available" basis, and we expressly disclaim all warranties of all kinds, including implied warranties of fitness for a particular purpose, merchantability, and non-infringement. We make no warranty that Wikimedia Maps will meet your requirements, be safe, secure, or uninterrupted.**

### Updates

Things naturally change over time. To ensure this policy accurately reflects our practices and the law, we reserve the right to modify it.

We will provide reasonable notice of updates to this page by sending announcements to <wikitech-l![@](//upload.wikimedia.org/wikipedia/commons/thumb/8/88/At_sign.svg/20px-At_sign.svg.png)lists.wikimedia.org> ([more info](https://lists.wikimedia.org/mailman/listinfo/wikitech-l)) and <maps-l![@](//upload.wikimedia.org/wikipedia/commons/thumb/8/88/At_sign.svg/20px-At_sign.svg.png)lists.wikimedia.org> ([more info](https://lists.wikimedia.org/mailman/listinfo/maps-l)) at least 14 days before changes are made. Please review the most recent version of this policy. You accept the new version of this policy if you use the site after we announce an update. We will save a copy of the previous versions of this policy.

Where does the map data come from?
----------------------------------

The maps shown on Wikipedia, Wikivoyage and other Wikimedia projects use data from [OpenStreetMap](https://openstreetmap.org/). OpenStreetMap is open data, created by [OpenStreetMap contributors](https://www.openstreetmap.org/copyright), and available under the [Open Data Commons Open Database License](https://opendatacommons.org/licenses/odbl/) (ODbL).

The map designs are based on the style [OSM Bright for Mapbox Studio](https://github.com/mapbox/mapbox-studio-osm-bright.tm2), available under a [Creative Commons Attribution 3.0 license](https://creativecommons.org/licenses/by/3.0/).

You may provide attribution to static map images by linking to to provide more details on the license, and by complying with the [OpenStreetMap copyright policy](https://www.openstreetmap.org/copyright).

How do I fix an error on the map?
---------------------------------

Do you see something on the map that needs editing? Log into OpenStreetMap to [fix it](https://www.openstreetmap.org/fixthemap) and help make the map better for everyone! :)

How to guides and more information
----------------------------------

Update log
----------

These Maps Terms of Use went into effect on April 5, 2021. Updates:

![](https://foundation.wikimedia.org/wiki/Special:CentralAutoLogin/start?useformat=desktop&type=1x1&usesul3=1)

Retrieved from "[https://foundation.wikimedia.org/w/index.php?title=Policy:Terms\_of\_Use\_for\_Wikimedia\_Maps&oldid=479321](https://foundation.wikimedia.org/w/index.php?title=Policy:Terms_of_Use_for_Wikimedia_Maps&oldid=479321)"

- - -

Other languages:

*   English

**Want to help translate? [Translate the missing messages](https://foundation.wikimedia.org/w/index.php?title=Special:Translate&group=agg-Terms_of_Use&filter=%21translated&action=page&language=).**

|     |     |
| --- | --- |
| [![Wikimedia Foundation mark](//upload.wikimedia.org/wikipedia/commons/thumb/8/8b/Wikimedia-logo_black.svg/40px-Wikimedia-logo_black.svg.png)](https://foundation.wikimedia.org/wiki/File:Wikimedia-logo_black.svg) | **This policy or procedure is maintained by the .**  <br>Please note that in the event of any differences in meaning or interpretation between the original English version of this content and a translation, the original English version takes precedence. |

The govern your use of . In addition:

1.  **Code to Which You Hold the Copyright**: When you submit software source code, or other material intended for inclusion in software (such as documentation or translations), to which you hold the copyright, you agree to license it under the GNU General Public License (version 2.0 or any later version). The only exception is if the software to which you are contributing requires a different license. In that case, you agree to license any text you contribute under that particular license. For example, at the publication of this version of the Phabricator Terms of Use, Visual Editor is licensed under the MIT license, so if you make contributions to Visual Editor through this site, you agree to license those contributions under the MIT license.
2.  **Importing Code**: You may import source code that you have found elsewhere or that you have co-authored with others, but in such case you warrant that the source code is available under terms that are [compatible with the GNU General Public License](https://www.gnu.org/licenses/license-list.html#GPLCompatibleLicenses) version 2.0 (or, as explained above, another license when exceptionally required by that software).
3.  **Etiquette**: You are expected to follow the to ensure that Phabricator is a productive and collaborative environment for managing bug reports and feature requests.

![](https://foundation.wikimedia.org/wiki/Special:CentralAutoLogin/start?useformat=desktop&type=1x1&usesul3=1)

Retrieved from "[https://foundation.wikimedia.org/w/index.php?title=Policy:Wikimedia\_Phabricator\_Terms\_of\_Use&oldid=457220](https://foundation.wikimedia.org/w/index.php?title=Policy:Wikimedia_Phabricator_Terms_of_Use&oldid=457220)"