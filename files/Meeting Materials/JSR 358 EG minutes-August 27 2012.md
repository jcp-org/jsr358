# JSR 358 Expert Group Meeting Minutes  
for 27 August 2012

_version 0.1: August 29, 2012_

## **Date**

August 27, 2012

## Location

Teleconference.

## **Agenda**

*   Interpreting the JSPA
*   [JSR 358 summary presentation](/files/Meeting%20Materials/JSR358-July31-2012.pdf)
*   Next steps/next meeting

## Attendance

*   Patrick Curran
*   Don Deutsch
*   Scott Jameson
*   Lakshmi Dontamsetti
*   Paul Manfrini
*   Martijn Verburg
*   Ed Lynch
*   Scott Stark
*   Mike DeNicola
*   Steve Wolfe
*   Calinel Pasteanu
*   Werner Keil
*   Anish Karmarkar
*   Gil Tene
*   Steve Winkler
*   VanRiper

## Minutes

Patrick apologized for not having completed a "translation" of the existing JSPA and suggested that instead we review [Scott Stark's summary](JSPA-ScottStark.md).

Gil Tene asked whether the only problem we are currently trying to solve that related to Section 6\. Scott Jameson suggested that the hub and spoke IP-flow is another. Patrick added the topic of when IP should vest, pointing out that currently it doesn't vest until the JSR completes. This is a problem for open-source projects that release "early and often." Also, he suggested that we should consider whether compatibility should be tied to licensing IP, noting that Scott Stark seems to have suggested that compatibility testing should be separated from IP licensing. Scott responded that he was talking more about RI and TCK licensing. Gil responded that these are completely separate issues - what counts is how IP is granted, and how it flows.

Gil stated that tying IP grants to compatibility is a cornerstone of the JCP - modifying this would be a major change.

Steve Wolfe responded that TCK licensing is linked to IP flow, since the Spec License requires that you license the TCK. Werner Keil asked whether we have different licenses. Steve responded yes, of course - part of our problem is the multitude of licenses.

Gil suggested starting with inbound IP flow. IP associated with contributions flows only to compatible implementations. IP rights are granted to the Spec Lead, who can re-license them.

Patrick pointed out that individuals do not bind their employers to essential patent grants.

Steve Wolfe suggested that he would still like to see an English-language summary of the JSPA. Patrick asked whether Scott's document was sufficient and Steve responded that it wasn't since it simply extracted the JSPA. Steve also pointed out that members have the option to opt-out from essential patent grants, saying that this was heavily-negotiated when the current version of the JSPA was defined. He suggested that the new transparency requirements should make it much easier to do the research to determine what patents you may be obliged to license. Gil responded that this is still a significant burden.

Patrick reminded members that the Doodle poll had asked whether the obligation to license essential patents should be restricted to those who are members of the EG. Most people who responded said we should discuss this further. He asked what people thought about this suggestion. Mike DeNicola responded that he thinks this obligation should be restricted to members of the EG. Don Deutsch rephrased the question: does anyone think that we should retain the broad obligation? Steve Wolfe responded that creating a new JSPA that would increase the risk of "unkown IP claims" would be a dangerous step backward. He said that he didn't think that anyone has ever exercised their right to opt-out. Gil Tene agreed with Steve. Nobody else offered an opinion.

Steve Wolfe suggested that we consider simpler IP regimes.

Patrick suggested that taking a top-down approach (starting from what we would like a new JSPA to say) might be better than a bottom-up approach (analyzing the existing JSPA.) He asked Steve to discuss his concern with the "hub-and-spoke" model.

Steve responded that all IP flows to the Spec Lead, who then relicenses it to implementors. He suggested that instead the grants could go directly to "the community." Where there is a need for broader grants - eg to Oracle to fulfil TLDA obligations - these could be granted in a manner similar to that used in OpenJDK.

Patrick asked whether he was suggesting that instead of IP being granted to the Spec Lead, who would then sublicense it, IP would be licensed directly to implementors. Steve agreed, noting that any kind of license (liberal or restrictive) could be used in this model.

Scott Stark asked how "the community" would be defined. Patrick suggested anyone who implements the spec.

Anish Karmarkar asked whether this model would also cover essential patents. Patrick responded that under the current model essential patents already flow directly to implementors.

Mike DeNicola said that he likes the idea of a direct IP flow, suggesting that the model should be more like OpenJDK. Gil Tene suggested that all implementors should have similar rights as the Spec Lead. Martijn Verburg agreed that making the model more like OpenJDK would be desirable.

Gil noted that the Oracle Contributor Agreement (which OpenJDK contributors must sign) makes much broader IP grants than JSPA - in particular it makes very broad grants to Oracle. This would be too much for the JSPA. He suggested that not all Spec Leads should be given equally broad rights.

Scott Jameson said that just because we want to use OpenJDK as a model doesn't necessarily mean that we would start with the OCA.

Steve Wolfe agreed, noting that we wouldn't necessarily want to model our IPR language on the OCA - rather we should define a broad, common inbound license with supplemental rights to Oracle.

Patrick asked how we should move the discussion forward. He pointed out that we should spend a full day on JSR 358 during our Prague meeting, and suggested that we would need volunteers to lead discussion on various topics.

Martijn Verburg agreed to volunteer for something. Gile Tene volunteered to lead a discussion on Independent Implementations. Patrick sresponded that we will need four or five volunteers for Prague and he agreed to follow up by email.

Steve Wolfe argued that the JSR 358 Expert Group session should not be bound by the EC Standing Rules requirement that all participants be present in person, and asked whether the phone line could be opened up for two-way communication during this portion of the meeting.

Patrick agreed that this was a reasonable request and promised to discuss it with the full EC at the start of the Prague meeting.