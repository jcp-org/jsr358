# JSR 358 IP Working Group Meeting Minutes  
for January 11 2013

## **Date**

*   January 11, 2012

## Location

*   Teleconference

## **Agenda**

*   Review meeting minutes
*   [IPR goals](/files/Meeting%20Materials/JSR358-IPRGoals-Draft003-1.pdf)
*   [Essential Patent alternatives and standard licenses](http://jcp.org/aboutJava/communityprocess/ec-public/materials/2012-11-20/Patent-Altenatives-and-Standard-Licenses.pdf)
*   [Hub-and-spoke IP grants](http://jcp.org/aboutJava/communityprocess/ec-public/materials/2012-10-16/Hub-and-Spoke-Alternative.pdf)
*   Next steps

## Attendees

*   Patrick Curran
*   Scott Jameson
*   Anish Karmarkar
*   Mike Milinkovich
*   Steve Harris
*   Steve Wolfe
*   Scott Stark
*   Mike Marzo
*   Werner Keil

## Minutes

We reviewed the minutes of the last meeting.

Patrick summarized (from the minutes) the two alternatives discussed last week:

1.  Inbound grants should be made under whatever terms the Spec Lead has chosen for the outbound license.
2.  A single set of inbound terms could be constructed that would be flexible enough to enable all possible outbound licenses.

He asked how (whether) these proposals would deal with the situation when the Spec Lead wanted to release the RI or TCK under a commercial license with associated fees?

Steve Harris: inbound Apache would permit the Spec lead to use any license terms they wish, including charging fees.

Anish: contributors could make direct (RF) grants to all licenseess, while the Spec Lead would license FRAND to licensees

Steve Wolfe: why would the Spec Lead grant more restrictice licenses than contributors?

Steve Wolfe: the complexity of the JSPA inhibits innovation, and is out of sync with modern licensing methods.

SteveW: we should pick a set of standard licenses - I suggest Apache, Eclipse, GPL.

Patrick: are you excluding FRAND (more specifically, commercial licenses)?

SteveW: I've proposed special additional grants (rights) for Oracle. They must be able to monetize their investment. Do we need to permit **all** Spec Leads to charge for TCKs?

Scott Stark: There are other ways for Oracle to recover costs than charging for access to TCKs.

SteveW: Oracle is already releasing TCKs "for free" through OpenJDK.

ScottJ: "Cost recovery" is much more common in Java ME

Patrick: we have two proposals:

1) SteveW: Nobody but Oracle must be able to charge for TCKs (for Cost Recovery)

2) ScottS: Nobody including Oracle must be able to charge for access to TCKs. Oracle could charge for branding, trademark usage, etc.

SteveH: new JSRs would be subject to the requirements of the new JSPA with regard to standardized licensing. Oracle can use closed source (for the platform.) With new stuff they can take it and pass it on "free" or not take it.

SteveW: I meant to ask on the mailing list how many TCKs developed **outside** Sun/Oracle charge for access? Patrick responded with a response that addressed Oracle-developed TCKs.

SteveW: take a look at the OpenJDK TCK license.

Patrick: that applies only to implementations substantially derived from the OpenJDK source-code, and that will therefore be licensed under the GPL.

MikeM: you must admit that the GPL terms are not acceptable for commercial entities.

Patrick/ScottS: discussed Scott's proposal for "free access to TCKs" with all cost-recovery being associated with branding.

SteveH to ScottS: if you're suggesting that Oracle license all its TCKs under the Apache license and that they should recover their costs elsewhere, that won't fly.  

Werner Keil: ME and SE are harmonizing. Does that mean that their licenses would be harmonized?

SteveW: does the EC believe it's necessary for Spec Leads to be able to do cost recovery for TCKs? Discuss this at the f2f.

Adjourned: discussion to be continued during the f2f meeting next week.