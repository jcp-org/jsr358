# JSR 358 IP Working Group Meeting Minutes  
for December 14 2012

## **Date**

*   December 14, 2012

## Location

*   Teleconference

## **Agenda**

*   [Hub-and-spoke IP grants](http://jcp.org/aboutJava/communityprocess/ec-public/materials/2012-10-16/Hub-and-Spoke-Alternative.pdf)
*   [Essential Patent alternatives and standard licenses](http://jcp.org/aboutJava/communityprocess/ec-public/materials/2012-11-20/Patent-Altenatives-and-Standard-Licenses.pdf)
*   Next steps

## Attendees

*   Patrick Curran
*   Scott Jameson
*   Mike Milinkovich
*   John Rizzo
*   Gil Tene
*   Anish Karmarkar
*   Steve Wolfe
*   Steve Harris
*   Anil Kumar

## Minutes

Patrick reviewed the minutes of the last meeting.

Anish reported that he has started writing the document that he promised to develop. He hasn't made a lot of progress yet, but he did come across some isues. Patrick asked him to explain.

Anish: the Spec is owned by the Spec Lead, which means that the Spec Lead needs the right to modify contributions incorporated into the Spec, and to create "derivative works" (modifications to the original JSR, perhaps incorporated into a follow-on JSR.) We don't want to give similar rights to all implementers. If the Spec Lead does need different rights in some area(s) then is there a benefit to flattening overall?

Steve Wolfe: flattening applies only to patents. No need to do anything for copyrights.

Anish: then maybe we're on the same page.

Gil: are we proposing hub & spoke for copyright, and a flat grant for patents?

SteveW: not necessarily. Standardized licensing will address copyright in code.

Gil: consider patents and copyrights separately.

Anish: we need to keep the reciprocity language and the right to withdraw from JCP before Public Review and thereby relieve onself of the RAND obligations.

Patrick: we do have an open issue about "when and under what circumstances IP can be withdrawn"

Discussing the items line by line...

Gil: the reciprocity language in current JSPA provides powerful protection. Can we strengthen this to apply to all JSRs? If someone asserts a patent against any compatible implementation of any JSR other members would have the right to withdraw their own grants for any other JSR.

Steve Harris: this would discourage participation.

Mike Milinkovich: Eclipse and Apache licenses work this way now. If you litigate against code covered by these licenses you lose all rights to anything covered by those licenses.

Patrick asked Gil to log an issue to track this suggestion.

MikeM: this could be implemented without requiring hub&spoke.

Anish: change _**EG Members**_ to _**Contributors**_**.**

MikeM: we may want different rights for Spec, Code (RI) and TCK

Anish: must consider the rights to R&D for patents.

Patrick: don't discard copyrights. Should consider them as well as patents. Analyze the current and prefered situation.

It may be that our standard licenses will take care of all of this and we won't need to include any copyright language in the JSPA, but we should do the analysis first.

Once again, we did not have time to discuss the second presentation.