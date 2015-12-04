# health-decision-support-tools

Tools to support people collaboratively making health decisions, especially decisions involving uncertainties and conflicts of interests

## License: Apache 2.0

## Memorial Dedication

This project is in memory of two people who pioneered collaborative decision support tools in what they each saw to be the public interest and who sadly both died young from health issues:

* Al Selvin, who co-invented the [Compendium software](https://en.wikipedia.org/wiki/Compendium_%28software%29) and died unexpectedly of heart failure at age 56 while bicycling
* Tom Armour, who managed [DARPA's Genoa project](https://w2.eff.org/Privacy/TIA/genoaII.php) and died of brain cancer at age 58

The project's long-term goals are to:
* Gather ideas from various ["tribes" of intelligence](http://p2pfoundation.net/Tribes_of_intelligence) such as Academic, Civil Society (including religions and labor unions), Commerce, Government (including local and state), Law Enforcement, Media, Military, and Non-Government/Non-Profit.
* Apply those ideas by creating software tools to help individuals and small groups collaboratively make difficult health (or other) decisions in the face of uncertainties and conflicts of interests. Those decisions might be about prevention of health issues (as might have helped Al and his family) or they might be about responses to emerging health issues (as might have helped Tom and his family after his initial diagnosis).

## Disclaimer

The material provided by this project is for strictly informational and educational purposes only. It is not meant to replace or substitute for the recommendations or advice of your physician or health care provider. The information contained in this project should not be used for diagnosing or treating a health problem or disease. If you believe you have a medical condition or problem contact your health care provider.

# Initial Audience

In the very long term, it would be fantastic if health decision support tools could support people of all sorts of backgrounds, educational levels, and skills. It would be amazing if the tools could adapt themselves to different user skill levels. It would be fabulous if such tools could tutor users in facilitating health sensemaking and decision making. It would be wonderful if the tools could flag problematical usage situations automatically and escalate them for collective review or other advanced interventions. It would be terrific if such a project defined international machine-readable semantic standards for encoding and indexing open source health information (as needed) and used such standards to encode and index all of the enormous body of existing health literature and related discussions of it for easy access and review by anyone anywhere. No doubt this wish list could be added to further. However, those are not realistic initial aspirations for all sorts of practical reasons. Such aspirations likely may never be fully achievable goals -- even if they can be guiding stars.

A more realistic initial aspiration is to create tools usable by small groups led by someone with the equivalent of a graduate education in medicine, science, engineering, or social work -- someone who already understands the scientific method and/or how communities process knowledge and conflicts of interests. This lead user would take responsibility for ensuring the ongoing collaboration goes well despite obstacles. Such lead users would in turn facilitate sensemaking and decision making by a family or team who might have less education and less skill than the team lead (but who still, initially, all have some reasonable degree of computer and other decision making skills and also some health-related background knowledge themselves). As Al Selvin discussed in his PhD thesis and other writings, facilitators (he called them practitioners) can help guide participants in creating representations of issues or ideas, such as collaborative diagrams. Currently, this facilitative process still requires practitioners have multiple skills. So, another initial requirement then for the initial software lead users is that they have such facilitative skills or are working diligently to acquire them in a setting with appropriate supervision and feedback.

What are examples of the intended initial lead users of such health decision support tools, given a high level of expectations for education and skills of initial users of these tools? An initial lead user might be someone who is already a health care professional and who is facilitating health decisions for their own parents alongside siblings with various opinions (which is a tricky situation, but one that such professionals are often asked to involve themselves in where the normal provider-patient relationship does not apply). Another example might be a person with a graduate degree in biology who has already read a variety of health-related books written from a variety of perspectives and who is supporting their own family in thinking through conflicting opinions and options from primary care physicians, specialists, and other health information sources such as about a healthy lifestyle and a healthy diet. Another possible initial lead user might be a skilled and experienced social worker who is helping coordinate care for someone in a nursing home by helping that person and their family collect and reconcile multiple opinions and options supplied from different specialists and interested parties in different areas of care who may each use their own vocabularies and perspectives (such as physical therapy, religious support, psychologists, family members, primary care physicians, nursing staff, nutritionists, recreational therapists, health aids, friends, and individual personal preferences). Other initial users might be experienced health researchers who are using these tools as part of their own collaborative research process into some specific health issue of interest based on the scientific literature and perhaps even their own scientific laboratory research.

In all these cases, it is also assumed the primary lead user of the initial software would already have a significant level of skill with both computers and health information, even as other people in the group they are facilitating (people who might interact with the software at the request of the lead user) might have a lesser degree of such skills.

It seems reasonable to predict that future versions of the tools could lower the amount of computer skills to use them by better software design. It is harder to predict whether the requirements of a lead users for skills in facilitation, the scientific method, or accessing health knowledge could be lowered any time soon.

## Initial Example

Heart disease and cancer are such complex and emotional topics they are hard to start with as motivational examples. They are just overwhelming for anyone to deal with. So, here is a simpler initial example of a health issue (a tooth ache) that the initial project committer faced and used Compendium to help make sense of and make decisions about. As long as this simple example is, it has still been somewhat simplified. If a tooth ache can cause this much confusion and stress, how much more confusing and stressful could larger and more immediately life threatening health issues like heart disease and cancer be to make sense of and decide about? The conflicts and uncertainties outlined here (including uncertainty about what health care provider to trust in what capacity) are likely typical of what many people may face when they try to interact with a health care system in an informed way with any significant health issue.

The initial project committer consulted the dentist he had been seeing regularly for about a decade in response to increasing tooth pain in a rear jaw area. That area previously had two large amalgam fillings that dentist had replaced with white fillings because that dentist said they were "breaking down" (even though they hadn't caused him any substantial pain at the time). This dentist was near retirement, had always been a tremendously nice person, and did not charge that much. This dentist was unable to determine with certainty which specific tooth of about three was the source of the pain, and said he could not find any problems with two white fillings he had placed in that area. 

Still in pain, and because he figured his dentist might retire soon, he then consulted a second dentist he had never seen before. This was a "holistic" dentist who did not like root canals. This second dentist said a specific tooth was the issue and advised an (expensive) temporary crown on a molar (without a root canal) for the tooth to see if it would heal on its own ($900 or so for temporary crown plus placing it), with a planned permanent crown to follow (over US$2000 in total for both crowns). It was unclear what that dentist would do if the temporary crown did not help. However, the second dentist could not perform the work right away because he was going to a dental conference just then. 

With continually increasing pain, and some reservations about the expensive crown suggestion, he had some inexpensive dental work done with his regular dentist to replace a questionable filling just in case in the third of that row of back teeth (but it did not help). 

Still in pain, he then decided on his own to see an endodontist (a specialist in internal tooth issues). Picking an endodontist was itself a challenge, and he then asked his first dentist for a referral to the one selected. The endodontist made a first guess that an extraction would be required from X-rays which seemed to indicate "resorption" in the tooth the second dentist had suspected, but suggested a diagnostic CBCT X-ray scan to help confirm his initial opinion. Based on the CBCT scan (itself an X-ray health risk and an additional expense and delay), in the first couple of minutes of looking at it, the endodontist suggested that the tooth could be an OK candidate for a root canal. However, while continuing to look at the CBCT scan results, the endodontist then revised that opinion after more information volunteered about a possible precipitating event before the pain of biting on a popcorn kernel. Ultimately the endodontist said he could not see a specific crack in the tooth from x-rays, but he felt a crack was likely present anyway in his experience based on the pattern of internal decay in the tooth (now thought to be decay moving upward from a cracked root and not from resorption). Because a substantial crack would mean a root canal would likely fail in under a year, the endodontist recommended a tooth extraction and provided a referral to an oral surgeon to do that. The endodontist took a dim view of the holistic dentist's advice to have a crown without a root canal in this case.

Returning to the original dentist and presenting the endodontist's finding, he heard the original dentist he had trusted for a decade suggest that he get a root canal anyway with a new white filling (not a crown) since "once a tooth is gone, it's gone". The general dentist also strongly disagreed that decay could come from the bottom of a tooth upwards, saying decay always came from the top down.

What to do with three differing opinions from three licensed dental professionals (temporary crown and then permanent, extraction, root canal with white filling)? To be clear, none of the practitioners mentioned here are being accused of anything. The point is more that the three essentially disagreed in what might be reasonable ways based on their own experiences, examinations, test results, priorities, and standards of practice (or at least could be seen to do so). 

Consulting the internet about this quandary (including considering the option to wait and see while trying home remedies to repair the tooth) led to even more uncertainty given various disagreements about root canals, crowns, fillings, implants, [dentists' lack of integrity](http://www.areturntoempathy.com/how-honest-are-dentists.html) vs. [high integrity](http://www.dentaleconomics.com/articles/print/volume-87/issue-4/departments/viewpoint/lets-review-how-readers-digest-misrepresented-us.html), general dentists vs. endodontist success rates for root canals, nutrition, oil pulling, herbal remedies, toothpastes, and more -- making a decision even harder. Talking with friends and family about the issue also led to more conflicting opinions to consider.

So, what do you do when you are in pain, have three disagreeing medical opinions, have an ocean of potentially biased non-specific conflicting background information from the internet, have conflicting advice from friends and family -- and yet also have limited time and money for getting yet more professional opinions and more test results (assuming that would really help anyway)? How do you decide which health-practitioner-recommended treatment to go with? What heuristics do you follow for weighing the different opinions? How do you think through resolving such a conflict (especially when you may be in enough pain from a health issue not to be able to easily think clearly)?

Given his previous familiarity with Compendium and IBIS, creating an IBIS map about this situation in Compendium proved useful to him to help make a decision in the face of uncertainty, costs, risks, and various conflicts-of-interest by different advice givers. The IBIS map was reviewed with a thought in mind suggested by a dental hygienist of considering who you trust the most (although that was not the only consideration). Even though he lost some work time and had some suffering from the issue and the related uncertainty, the original project committer is very thankful he has not had to make an IBIS map for dealing with a diagnosis of heart disease or cancer -- but he can see the potential value in doing that and more if needed. He hopes that reflecting on this example health issue more deeply could lead to better tools for health decision support, and that such tools could then be improved further to deal with much more challenging situations like dealing with cancer, heart disease, stroke, or other generally far more life-altering health issues (even as it is true that some tooth aches can cause death like through systemic infection and heart damage).
