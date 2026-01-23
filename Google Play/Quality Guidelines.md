Content Ratings
===============

Content ratings on Google Play are provided by the [International Age Rating Coalition (IARC)](https://www.globalratings.com/)and are designed to help developers communicate locally relevant content ratings to users. Regional IARC authorities maintain guidelines which are used to determine the maturity level of the content in an app. We don’t allow apps without a content rating on Google Play. Note that any ads that appear in the app must not be significantly more mature in content than the primary content within the app itself. Refer to [Inappropriate Ads](https://support.google.com/googleplay/android-developer/answer/9857753#inappropriatem/googleplay/android-developer/answer/9857753)policy for more information.

#### How content ratings are used

Content ratings are used to inform consumers, especially parents, of potentially objectionable content that exists within an app. They also help filter or block your content in certain territories or to specific users where required by law, and determine your app’s eligibility for special developer programs.

#### How content ratings are assigned

To receive a content rating, you must fill out a [rating questionnaire on the Play Console](https://support.google.com/googleplay/android-developer/answer/9859655#How%20to%20complete%20a%20rating%20questionnaire) that asks about the nature of your apps’ content. Your app will be assigned a content rating from multiple rating authorities based on your questionnaire responses. Misrepresentation of your app’s content may result in removal or suspension, so it is important to provide accurate responses to the content rating questionnaire.

To prevent your app from being listed as “Unrated”, you must complete the content rating questionnaire for each new app submitted to the Play Console, as well as for all existing apps that are active on Google Play. Apps without a content rating will be removed from the Play Store.

If you make changes to your app content or features that affect the responses to the rating questionnaire, you must submit a new content rating questionnaire in the Play Console.

The content rating assigned to your app is specific to the content within your app. It does not include other features and practices, such as consumer agreements or ads. You are responsible for informing your users of any additional age-based considerations, such as age-specific privacy practices.

For more information on the questionnaire, visit the [Help Center](https://support.google.com/googleplay/android-developer/answer/9859655) to learn about the different [rating authorities](https://support.google.com/googleplay/android-developer/answer/188189#ratings)across regions and how to complete the content rating questionnaire.

#### Rating appeals

If you do not agree with the rating assigned to your app, you can appeal directly to the IARC rating authority using the link provided in your certificate email.

- - -

Requirements related to content ratings for apps, games and the ads served on both
==================================================================================

You can communicate familiar and locally relevant content ratings to your users and help improve app engagement by targeting the right audience for your content and for the ads that appear in it. To create a good experience for your users, make sure your app’s content ratings are locally relevant and familiar to the target audience.

This article covers several critical aspects of content ratings:

*   [How apps receive content ratings](#How apps receive content ratings)
*   [How content ratings are used](#How content ratings are used)
*   [Understanding your target audience selection](#Understanding your target audience selection)
*   [How to manage target audience and app content settings](#How to manage target audience and app content settings)
*   [How to make sure ads are suitable for your app’s content rating](#How to make sure ads are suitable for your app’s content rating)
*   [How to complete a rating questionnaire](#How to complete a rating questionnaire)
*   [Understanding your content ratings results](#Understanding your content ratings results)
*   [How to appeal your content rating](#How to appeal your content rating)
*   [Exploring rating authorities and descriptions](#Exploring rating authorities and descriptions)
*   [Additional resources](#Additional Content)

How apps receive content ratings
--------------------------------

Your app’s content ratings are assigned by separate rating authorities and determined by your questionnaire responses. Because they are independent third parties, each rating authority uses its own methodology to assign ratings. (See [Rating authorities and descriptions](https://support.google.com/googleplay/android-developer/answer/9859655#ratings).)

To receive a rating for each of your apps and games, fill out a rating questionnaire in Google Play Console. Provide accurate, complete information about the nature of your app’s content. Your questionnaire responses determine the ratings assigned to your app. After you submit your information, you’ll receive a content rating from multiple rating authorities no matter where you’re located. Google Play will display that rating on your app.

You need to complete the content rating questionnaire for both your new and existing apps, including:

*   New apps submitted to Google Play Console
*   Existing apps that are active on Google Play but lack a rating
*   All app updates where there has been a change to your content or features that would affect the responses to the questionnaire

To benefit your users, include the assigned rating when advertising your app in each respective region, following these [display guidelines](https://www.globalratings.com/display.aspx).

How content ratings are used
----------------------------

App ratings are meant to do more than reflect the intended audience. They’re meant to help consumers, especially parents, identify whether the app is appropriate for what the consumers are looking for, along with other purposes, like:

*   Blocking or filtering your content in certain territories or to specific users where legally required
*   European Economic Area (EEA), UK, Switzerland, and Australia only: Blocking the acquisition and purchase of mature content for non-supervised accounts that are not confirmed adults
*   EEA, UK, Switzerland, and Australia only: Blocking or filtering mature content from Google Play search and browse pages for declared teens or "high confidence" teens, except through deep linking
*   Evaluating your app’s eligibility for special developer programs

All rating icons are protected trademarks of the respective rating authority, and their misuse may result in legal action. Find specifics about rating icon usage on each [rating authority’s website](https://www.globalratings.com/contact-us.aspx).

Understanding your target audience selection
--------------------------------------------

To better serve users, it’s important to provide accurate information about your app. In addition to filling out the [content rating questionnaire](https://support.google.com/googleplay/android-developer/answer/9859655#How%20to%20complete%20a%20rating%20questionnaire), you’ll also need to provide details about your app’s target audience and content. Depending on the target audience selections you make, your app may be subject to additional Google Play policies. For example:

|     |     |
| --- | --- |
| Your app is designed primarily for children under 13 | You must comply with Google Play [Families](https://support.google.com/googleplay/android-developer/topic/9877766#!?zippy_activeEl=families-policy#families-policy) policy requirements, including the requirement to use only [Families Self-Certified Ads SDKs](https://support.google.com/googleplay/android-developer/answer/12289447) to serve ads. |
| Your app is designed for everyone, including children | Any apps that have at least one target audience age group that includes children must comply with Google Play [Families](https://support.google.com/googleplay/android-developer/topic/9877766#!?zippy_activeEl=families-policy#families-policy) policy requirements, including the requirement to use only [Families Self-Certified Ads SDKs](https://support.google.com/googleplay/android-developer/answer/12289447) to serve ads to children and users of unknown age. |
| Your app is not designed for children | You must still meet the requirements outlined in Google Play [Developer Program policies](https://play.google.com/about/developer-content-policy/) and [Developer Distribution Agreement](https://play.google.com/intl/ALL_us/about/developer-distribution-agreement.html). |

**Note**: For more insight on this topic, see [Managing target audience and app content settings](https://support.google.com/googleplay/android-developer/answer/9867159?hl=en).

How to manage target audience and app content settings
------------------------------------------------------

If you create a new app or publish an update to an existing app, you’ll be required to declare your app’s target age group. Any apps that include children in their target audience must comply with Google Play's [Families](https://support.google.com/googleplay/android-developer/topic/9877766#!?zippy_activeEl=families-policy#families-policy) policy requirements. Before filling out the "Target audience and content" section, you must have [declared whether or not your app contains ads](https://support.google.com/googleplay/android-developer/answer/9859455#ads) and [provided instructions for app access](https://support.google.com/googleplay/android-developer/answer/9815348#app_access). You must also [add a privacy policy](https://support.google.com/googleplay/android-developer/answer/9859455).

For detailed instructions on how to declare your app’s target age group, read [Manage target audience and app content settings](https://support.google.com/googleplay/android-developer/answer/9867159?hl=en).

How to make sure ads are suitable for your app’s content rating
---------------------------------------------------------------

Ads and their associated offers (like an ad promoting the download of another app) must be appropriate for your app’s content rating. Even if all of your app-specific content complies with our policies and matches your app’s content rating, you also need to check the ads and offers shown in your app to make sure they’re appropriate for that rating. For examples of ads that don’t match an app’s content rating, review the [Inappropriate Ads](https://support.google.com/googleplay/android-developer/answer/9857753#inappropriate) policy. 

Setting your ad filters appropriately helps make sure ad services and ad content are appropriate for your app’s content rating. 

*   Check with your ad service provider to make sure the advertising campaigns you selected will only show content that matches your app’s content rating. 
*   If you use AdMob, review the [AdMob Help Center article](https://support.google.com/admob/answer/7562142?hl=en&ref_topic=7384665) for steps about how to use blocking controls and set the right ad content rating.

How to complete a rating questionnaire
--------------------------------------

Make sure to provide accurate responses to the content rating questionnaire. If you have questions about the rating assigned to your app, contact the rating authority directly using the link provided in your certificate email. Misrepresentation of your app’s content may result in its removal or suspension.

Unrated apps also may be removed from Google Play. To prevent your apps from being listed as Unrated, open Google Play Console, go to the **[App content](https://play.google.com/console/app/app-content/summary)** page, and fill out the questionnaire for each of your apps as soon as possible.

Follow these steps to take the rating questionnaire. It’s critical to provide complete and accurate responses to every question.

1.  Open Google Play Console and go to the [**App content**](https://play.google.com/console/app/app-content/summary) page (**Policy** > **App content)**.
2.  Click **Start**.
3.  Review the information about the questionnaire and enter your email address.
    *   Your email address will be used for correspondence with [International Age Rating Coalition (IARC)](https://www.globalratings.com/) .
4.  Select a category and click **Next**.
5.  Complete the questionnaire.
    *   To change any of your responses after you’ve completed a section, click **Edit**.
    *   If you’ve started taking the questionnaire and want to finish later, click **Save draft**. Each app can have one draft questionnaire at a time.
6.  Your responses will generate calculated ratings shown on the **Summary** page. Review the ratings and click **Submit**. If you don’t think the ratings accurately reflect your content, you can retake the questionnaire. Click **Start new questionnaire** on the **Content rating** page.

After you’ve submitted the calculated ratings, you can review them along with your questionnaires in the "Target audience and content" section of the **App content** page.

Understanding your content ratings results
------------------------------------------

Your app can earn different ratings in different territories because rating standards can have differences by territory, each rating authority uses its own logic when rating apps.

Rating authorities participating in IARC may change your app's rating after a review. If a rating authority overrides your app rating and you want to update your responses, you’ll need to complete the questionnaire again.

**Note**: The calculated rating shown on the **Summary** page may not be the rating shown to users on Google Play. App updates and submissions can be rejected for misrepresenting an app's content. Your questionnaire responses may be used to generate ratings for specific territories as required by local law.

How to appeal your content rating
---------------------------------

If you object to the rating assigned to your app by a participating IARC rating authority, you have the right to appeal directly using the link provided in your certificate email. If you have other questions for IARC, not related to appeals, you can [contact them on their website](https://www.globalratings.com/developer-contactus.aspx).

Exploring rating authorities and descriptions
---------------------------------------------

Rating authorities in different territories have their own content rating system.

### Rating authorities

ESRB - Americas

| Rating | Description |
| --- | --- |
| ![E](//storage.googleapis.com/support-kms-prod/A6C111610CC95266002FD60049BB2DA4ACDB) | **EVERYONE**<br><br>Content is generally suitable for all ages. May contain minimal cartoon, fantasy or mild violence and/or infrequent use of mild language. |
| ![E10](//storage.googleapis.com/support-kms-prod/184E5C8CA2C5FB4E7F065159E324B77C2306) | **EVERYONE 10+**<br><br>Content is generally suitable for ages 10 and up. May contain more cartoon, fantasy or mild violence, mild language and/or minimal suggestive themes. |
| ![T](//storage.googleapis.com/support-kms-prod/F980E24C4BFC75D3F347182CB1765D5DA1BD) | **TEEN**<br><br>Content is generally suitable for ages 13 and up. May contain violence, suggestive themes, crude humor, minimal blood, simulated gambling and/or infrequent use of strong language. |
| ![M](//storage.googleapis.com/support-kms-prod/9A13C5FF8E49B2F7AC8F7F255C57957646A1) | **MATURE**<br><br>Content is generally suitable for ages 17 and up. May contain intense violence, blood and gore, sexual content and/or strong language. |
| ![AO](//storage.googleapis.com/support-kms-prod/D5CE9BA2CCF2BE35A169D82A00B2B4F8AB72) | **ADULTS ONLY**<br><br>Content suitable only for adults ages 18 and up. May include prolonged scenes of intense violence, graphic sexual content and/or gambling with real currency. |

Learn more on the [ESRB website](http://www.esrb.org/).

Locations
---------

Antigua and Barbuda, Argentina, Bahamas, Barbados, Belize, Bolivia, Canada, Chile, Colombia, Costa Rica, Cuba, Dominica, Dominican Republic, Ecuador, El Salvador, Greenland, Grenada, Guatemala, Guyana, Haiti, Honduras, Jamaica, Mexico, Nicaragua, Panama, Paraguay, Peru, Saint Kitts and Nevis, Saint Lucia, Saint Vincent and the Grenadines, Suriname, Trinidad and Tobago, United States of America, Uruguay, and Venezuela

PEGI - Europe and the Middle East

Ratings in Europe and the Middle East are maintained by Pan European Game Information (PEGI).

### Countries

Albania, Andorra, Austria, Belgium, Bosnia and Herzegovina, Bulgaria, Croatia, Cyprus, Czech Republic, Denmark, Estonia, Finland, France, Greece, Hungary, Iceland, Ireland, Israel, Italy, Kosovo, Latvia, Liechtenstein, Lithuania, Luxembourg, Macedonia, Malta, Moldova, Monaco, Montenegro, Netherlands, Norway, Poland, Portugal, Romania, San Marino, Serbia, Slovak Republic, Slovenia, Spain, Sweden, Switzerland, Turkey, United Arab Emirates, United Kingdom, and Vatican City.

### Ratings

| Rating | Description |
| --- | --- |
| ![3](//storage.googleapis.com/support-kms-prod/4CF58C8406621D9B1E14B3515D811E5777C8) | **PEGI 3**<br><br>The content of apps with this rating is considered suitable for all age groups. Some violence in a comical context (typically cartoonlike - Bugs Bunny or Tom & Jerry - forms of violence) is acceptable. A child should not be able to associate the character on the screen with real life characters, they should be distinctly fantasy. The app should not contain any sounds or pictures that are likely to scare young children. No bad language should be heard. |
| ![7](//storage.googleapis.com/support-kms-prod/42A78F6DEF3A365800C035E329EB3B131F3E) | **PEGI 7**<br><br>Any app that would normally be rated at 3 but contains some scenes or sounds that can possibly be frightening for children may be considered suitable in this category. There can only be very mild violence in a PEGI 7 app, like implied violence or non-detailed, non-realistic violence. |
| ![12](//storage.googleapis.com/support-kms-prod/F400AFAEE8720E3DAA2081BCADD1CE0BA94E) | **PEGI 12**<br><br>Games or apps that show violence of a slightly more graphic nature towards fantasy characters, or non-graphic violence towards human-looking characters or animals would fall in this age category, as well as nudity of a slightly more graphic nature and simulated gambling. Any bad language in this category must be mild and fall short of sexual expletives. |
| ![16](//storage.googleapis.com/support-kms-prod/3F9E8FB9295A4793C5B3C0B9631D70C106CD) | **PEGI 16**<br><br>Once the depiction of violence or sexual activity reaches a stage that looks the same as would be expected in real life, this rating is applied. Stronger inappropriate language, encouraging the use of tobacco or drugs and depicting criminal activities can be content of apps that are rated 16. |
| ![18](//storage.googleapis.com/support-kms-prod/97501F873381FC5FFC86AC60E700E10E68CB) | **PEGI 18**<br><br>The adult classification is applied when the level of violence reaches a stage where it becomes a depiction of gross violence and/or includes elements of specific types of violence (motiveless killing, violence towards defenceless characters or sexual violence). It may also include graphic sexual content, discrimination or the glamorisation of illegal drugs use. |
| ![Guidance recommended](//storage.googleapis.com/support-kms-prod/DC0B7C7D02F370DD5AE0E738A2D92EDF3308) | **PARENTAL GUIDANCE RECOMMENDED**<br><br>Apps do not always have predefined content that can be classified beforehand. Certain apps function as portals (e.g. to stream content), offering a broad, variable range of content from which consumers can choose. For these apps, we use the parental guidance icon, alerting parents that the app may provide access to content that is not appropriate for their child, although other, age-appropriate content may also be available, depending on the selection of the user. |

Learn more on the [PEGI website](http://www.pegi.info/)

Locations
---------

Austria-Denmark, Belgium, Bulgaria, Cyprus, Czech Republic, Estonia, Finland, France, Greece, Hungary, Iceland, Ireland, Israel, Italy, Latvia, Lithuania, Luxembourg, Malta, Netherlands, Norway, Poland, Portugal, Romania, Slovak Republic, Slovenia, Spain, Sweden, Switzerland, and United Kingdom

Unterhaltungssoftware Selbstkontrolle (USK) - Germany

Ratings in Germany are maintained by Unterhaltungssoftware Selbstkontrolle (USK).

| Rating | Description |
| --- | --- |
| ![0](//storage.googleapis.com/support-kms-prod/5049013C84FF5F576C06FD6F6583444590DC) | **All ages**<br><br>Apps without age restriction feature contents without youth protection relevance. They can be directly aimed at children and young persons but also at an adult audience. For instance, utility programs, product catalogues or tool apps fall into this category as well as social networks in which all user-generated content is being thoroughly reviewed, filtered or moderated. |
| ![6](//storage.googleapis.com/support-kms-prod/F14F9940B3A282AB9043767BB96210FAFCAC) | **USK: Ages 6 and above**<br><br>Apps in this category can contain elements that may not be appropriate for pre-school children. They may contain occasional scary moments, a low accumulation of mild cursing or subtle erotic innuendo. If violent imageries are present they remain abstract and are not decisive for the overall product. Games in this age category can still be categorized as family-friendly but involve more exciting and competitive aspects. |
| ![12](//storage.googleapis.com/support-kms-prod/FF239E88BD5F0D950D3B5AA6C0725981E765) | **USK: Ages 12 and above**<br><br>Apps in this category can have an impairing effect on younger children through the inclusion of scary elements, shock effects, some explicit language, sexual contents or occasional violent imageries. Games in this category can feature much more of a competitive edge and hectic gameplay. Please keep in mind that in social networks or user-generated content might generally contribute to the youth protection relevance. |
| ![16](//storage.googleapis.com/support-kms-prod/F21B37D6D9C011FC2C171E9AC3DE30A13302) | **USK: Ages 16 and above**<br><br>Some realistically designed displays of violence, an accumulation of shock and horror elements, consistently explicit language or apps with an erotic or sexual focus are summarized in this category. Games frequently feature armed combat, a framework story and military missions. The genres in this categorization also include action adventures, military strategy games and first person shooter. |
| ![18](//storage.googleapis.com/support-kms-prod/21C66B99BD29B1CFDD97938EF880A6B1E4B9) | **USK: Ages 18 and above**<br><br>Among other aspects such as the unquestioned display of drug use for example, realistic and explicit violence is the most common reason for the 18+ classification of these apps. Games in this age category virtually always involve violent game concepts that are prominent in the majority of game objectives. |

Learn more on the [USK website](http://www.usk.de/iarc/)

Australian Classification Board - Australia

**Note**: Australian Classification Board ratings are only issued for games.

Ratings in Australia are maintained by the Australian Classification Board (ACB).

For Games in the Play Store in Australia, the following ratings will be used. For other apps, we'll assign ratings described in the "Other countries" category.

| Rating | Description |
| --- | --- |
| ![G](//storage.googleapis.com/support-kms-prod/405E7713F47463BA9EFEF09A8C99D42FD620) | **General**<br><br>The content is very mild in impact.<br><br>The G classification is suitable for everyone. G products may contain classifiable elements such as language and themes that are very mild in impact. However, some G-classified computer games may contain content that is not of interest to children. |
| ![PG](//storage.googleapis.com/support-kms-prod/D3FD9A3B88158C62FF6A0FDF474A80682698) | **Parental Guidance**<br><br>The content is mild in impact.<br><br>The impact of PG (Parental Guidance) classified computer games should be no higher than mild, but they may contain content that children find confusing or upsetting and may require the guidance of parents and guardians. They may, for example, contain classifiable elements such as language and themes that are mild in impact. It is not recommended for viewing or playing by persons under 15 without guidance from parents or guardians. |
| ![M](//storage.googleapis.com/support-kms-prod/F802617CC37C19E4CA26AA267165DFD10F6B) | **Mature**<br><br>The content is moderate in impact.<br><br>Computer games classified M (Mature) contain content of a moderate impact and are recommended for teenagers aged 15 years and over. Children under 15 may legally access this material because it is an advisory category. However, M classified computer games may include classifiable elements such as violence and nudity of moderate impact that are not recommended for children under 15 years. Parents and guardians may need to find out more about the computer game’s specific content, before deciding whether the material is suitable for their child. |
| ![MA15](//storage.googleapis.com/support-kms-prod/3675F67C200F503FEC0104783905B7A1F657) | **Restricted**<br><br>The content is strong in impact.<br><br>MA 15+ classified material contains strong content and is legally restricted to persons 15 years and over. It may contain classifiable elements such as sex scenes and drug use that are strong in impact.<br><br>A person may be asked to show proof of their age before hiring or purchasing an MA 15+ computer game. Children under the age of 15 may not legally watch, buy or hire MA 15+ classified material unless they are in the company of a parent or adult guardian.<br><br>The guardian must be an adult exercising parental control over the person under 15 years of age. The guardian needs to be 18 years or older. |
| ![R18](//storage.googleapis.com/support-kms-prod/54654477AA8B262C5D869084ECF1976686C6) | **Restricted**<br><br>The content is high in impact.<br><br>R 18+ material is legally restricted to adults. Such material may contain classifiable elements such as sex scenes and drug use that are high in impact. Some material classified R18+ may be offensive to sections of the adult community. A person may be asked for proof of their age before purchasing, hiring or viewing R18+ computer games. |

Learn more on the [ACB website](http://www.classification.gov.au/)

Classificação Indicativa (ClassInd) - Brazil

Ratings in Brazil are maintained by ClassInd.

| Rating | Description |
| --- | --- |
| ![L](//storage.googleapis.com/support-kms-prod/EE3B569B4FCFEEB08081AB4104702B305BA7) | **All ages**<br><br>The content is not harmful to children of any age. It may contain a little very low impact content, such as cartoon violence. |
| ![10](//storage.googleapis.com/support-kms-prod/F12DA97BCAE30FF52F4C7F22127367747A5B) | **Rated 10+**<br><br>Some low impact content, especially on younger children. It may contain mildly offensive swearing, weapons, bloodless fights, scary scenes, tobacco/alcohol references, and medicinal use of illegal drugs. |
| ![12](//storage.googleapis.com/support-kms-prod/CC1F2D9613CAAB5723648ABBF5FD087C52FA) | **Rated 12+**<br><br>Low impact content. It may contain swearing, sexual dialogs or references, wounds, bleeding, and tobacco/alcohol consumption. |
| ![14](//storage.googleapis.com/support-kms-prod/1CBF63751193C2C4F9E79935F60B66A1E548) | **Rated 14+**<br><br>Medium impact content. It may contain death, erotic settings, nudity, and inferences of illegal drug consumption. |
| ![16](//storage.googleapis.com/support-kms-prod/88B3AD2B199580C8F7DBF89CD4E72B274D6F) | **Rated 16+**<br><br>Medium impact content. It may contain frequent violence, gore, mutilation, torture, sexual relations, and the consumption of illegal drugs. |
| ![18](//storage.googleapis.com/support-kms-prod/C55EE0515641A8CBDCD06F742AFDE5281811) | **Rated 18+**<br><br>High impact content. It may contain sadism, cruelty, encouragement or glamorization of drugs/violence, and explicit sexual relations. |

Learn more on the [ClassInd website](http://www.justica.gov.br/seus-direitos/classificacao)

GRAC - South Korea

**Note**: [GRAC](http://www.grac.or.kr/english/) ratings are only issued for games. Apps use a separate [content rating system](#play).

| Rating | Description |
| --- | --- |
| ![](//lh3.googleusercontent.com/rhjLX0J_v90cDcw3zwoixzECfYuAh9Qxn1BTCbVMDJbBUJBCGc2vcSZwFCv7Y5tzVg=w24) | **For all**<br><br>Titles rated ALL have content that may be suitable for all ages. |
| ![](//lh3.googleusercontent.com/qxojeobrTQPGUuA80lcIjWjJd7JOXgdypZ6vx6AdENq_wAh1D-SGzVuMZ2-xqNA_ZFc=w24) | **Rated 12+**<br><br>Titles rated 12+ have content that may be suitable for ages 12 and older. |
| ![](//lh3.googleusercontent.com/sNVsggP1c_Pw4r68wvgAPlujjy0fdMi7YBW0Ky--PjbV75fQbQUMGl0pnF5yqyB71-xA=w24) | **Rated 15+**<br><br>Titles rated 15+ have content that may be suitable for ages 15 and older. |
| ![](//storage.googleapis.com/support-kms-prod/9htDVISL1T4w64QMK0X83DBjaNtGrklI8w5M) | **Rated 19+**<br><br>Titles rated 19+ have content that may be suitable for ages 19 and older. |

Learn more on the [GRAC website](http://www.grac.or.kr/english/)

 

In countries and territories that aren’t represented by a participating rating authority, a separate rating will suggest the age appropriateness of an app or game.

IARC Generic

Ratings in other areas are maintained by the International Age Rating Coalition (IARC).

| Rating | Description |
| --- | --- |
| ![3](//storage.googleapis.com/support-kms-prod/2416AC0CD849C365FF100CD3DB60711E53C1) | **Rated for 3+**<br><br>Suitable for all age groups. Some violence in a comical or fantasy context is acceptable. Bad language is not permitted. |
| ![7](//storage.googleapis.com/support-kms-prod/A6174F473EF2354615B3821577ED895E7B58) | **Rated for 7+**<br><br>May contain some scenes or sounds that are frightening for children. Mild violence (implied or non-realistic) is permitted. |
| ![12](//storage.googleapis.com/support-kms-prod/B8D66A748FD2CD882418879FB5D00C6D08F2) | **Rated for 12+**<br><br>Violence involving fantasy characters and/or non-graphic violence involving human-looking characters or animals is permitted. Non-graphic nudity, mild language and simulated gambling are also permitted, but sexual expletives are not. |
| ![16](//storage.googleapis.com/support-kms-prod/C3BB6F17AABC1AA7D9E0E4D342471EA00D51) | **Rated for 16+**<br><br>Realistic violence, sexual activity, strong language, use of tobacco and drugs, and the depiction of criminal activities are permitted. |
| ![18](//storage.googleapis.com/support-kms-prod/E89013782762FE41ABCCCCF4E05C7530FA53) | **Rated for 18+**<br><br>Graphic violence, including depictions lacking motive and/or directed towards defenseless characters, and sexual violence are permitted. May also include graphic sexual content, discriminatory acts and/or the glamorization of illegal drug use. |

Learn more on the [IARC site](https://www.globalratings.com/ratings-guide.aspx).

Google Play Rating - Applies in South Korea (for apps only)

The content rating system for apps (not including games) in South Korea is based on Google Play Rating system.

| Rating | Description |
| --- | --- |
| ![3](//storage.googleapis.com/support-kms-prod/3219CE948468EE70FD289F0B22ECAEEEDEED) | **Rated 3+**<br><br>Generally suitable for all audiences. Note that apps with this rating may not be specifically designed for children. |
| ![7](//storage.googleapis.com/support-kms-prod/1FD10010B4BC6C586BD13970156B5D5CB337) | **Rated 7+**<br><br>May not be suitable for children under age 7. Note that apps with this rating may not be specifically designed for children. |
| ![12](//storage.googleapis.com/support-kms-prod/93A85B58FEF95440A0AA9D0497F3F89C4250) | **Rated 12+**<br><br>May not be suitable for children under age 12. |
| ![](//lh3.googleusercontent.com/rJjri5RqUGT8M73wQPv7iFs3vEXnb93j0EDpYPL-7hawyIq1rrxZa2qKUoWlMpeLmRM=w24) | **Rated 16+**<br><br>May not be suitable for children under age 16. |
| ![18](//storage.googleapis.com/support-kms-prod/t0ZmwbTfcCVzj0Lq0Jwiq6SBwoWZFz4UEikM) | **Rated 19+**<br><br>Recommended for mature audiences only. |

Google Play Rating - Applies in Russia

**Note**: If you haven't filled out the new Content Rating questionnaire, your app(s) will be listed as Unrated.

| Rating | Description |
| --- | --- |
| ![3](//storage.googleapis.com/support-kms-prod/3219CE948468EE70FD289F0B22ECAEEEDEED) | **Rated 3+**<br><br>Generally suitable for all audiences. Note that apps with this rating may not be specifically designed for children. |
| ![7](//storage.googleapis.com/support-kms-prod/1FD10010B4BC6C586BD13970156B5D5CB337) | **Rated 7+**<br><br>May not be suitable for children under age 7. Note that apps with this rating may not be specifically designed for children. |
| ![12](//storage.googleapis.com/support-kms-prod/93A85B58FEF95440A0AA9D0497F3F89C4250) | **Rated 12+**<br><br>May not be suitable for children under age 12. |
| ![](//lh3.googleusercontent.com/rJjri5RqUGT8M73wQPv7iFs3vEXnb93j0EDpYPL-7hawyIq1rrxZa2qKUoWlMpeLmRM=w24) | **Rated 16+**<br><br>May not be suitable for children under age 16. |
| ![18](//storage.googleapis.com/support-kms-prod/5F338C1358DDEA867F364A1316E20BE9203F) | **Rated 18+**<br><br>Recommended for mature audiences only. |

### Other

Unrated

| Rating | Description |
| --- | --- |
| ![Unrated](//lh6.ggpht.com/SKdY9wVw3QjGNVhf0XVpViN3xKDzMemJIh-pJ5w_qO00-dQoexvaPoLdniRd1Z1s0A=w24) | **Unrated**<br><br>Warning - content has not yet been rated. Unrated apps may potentially contain content appropriate for mature audiences only. |

Refused classification

On a limited basis, rating authorities can refuse classification for an app distributed in their territory. This means that the distribution of the app or game is not allowed in the rating authority's territory.

If an app or game is refused classification in a territory:

*   IARC will notify the app's developer of the decision by email.
*   In place of a rating from a rating authority, ![RC](//lh3.googleusercontent.com/l-rhNNgGTriLXvnsQn2UtA7FOQUAJtlFbU9F-Vm4RlA41WULob7pkq_NT5SNMw=w16) Refused classification will be displayed in Play Console instead.
*   Google Play will remove apps and games with the "Refused classification" designation in the applicable territory only.

If one of your apps or games receives this designation and you want to file an appeal, you can appeal using the URL provided in your email notification from IARC.

 Additional resources
---------------------

### Related content

*   Learn more about Google Play Policies in [Play Academy](https://www.youtube.com/watch?v=J_mQc_nYPjk&t=450s).