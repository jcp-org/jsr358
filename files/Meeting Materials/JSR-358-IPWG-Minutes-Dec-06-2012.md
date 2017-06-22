# JSR 358 IP Working Group Meeting Minutes  
for December 6 2012

## **Date**

*   December 6, 2012

## Location

*   Teleconference

## **Agenda**

*   [Hub-and-spoke IP grants](http://jcp.org/aboutJava/communityprocess/ec-public/materials/2012-10-16/Hub-and-Spoke-Alternative.pdf)
*   [Essential Patent alternatives and standard licenses](http://jcp.org/aboutJava/communityprocess/ec-public/materials/2012-11-20/Patent-Altenatives-and-Standard-Licenses.pdf)
*   Next steps

## Attendees

*   Patrick Curran
*   Steve Wolfe
*   Scott Jameson
*   John Rizzo
*   Gil Tene
*   Anish Karmarkar

## Minutes

We had time only to discuss the Hub-and-Spoke proposal.

Steve summarized the goal: IP grants should go directly from contributors to implementers/end users rather than through the Spec Lead.

We reviewed the roles listed in the presentation and agreed that two roles are missing:

*   Distributors - those who (re)distribute what implementers produce.
*   Non JCP-members who make casual contributions to the work of an Expert Group via online collaborative tools such as discussion forums, mailing lists, and issue-trackers.
    *   This is likely to be covered not by the JSPA but by the proposed standard Terms of Use for collaborative JSR projects, but nevertheless should be listed for completion.

We agreed that it was important to list all roles even if - as we hope - the grants by/to several of these will be identical. Listing all will help to assure ourselves and others that we've considered all possibilities.

We had a brief discussion about the role of the RI. Patrick maintained that the term is overloaded - we use it to refer to a "gold standard" against which an implementation can be measured and as the work of the Spec Lead from which derivative works can be created. (We have an issue to track this: [http://java.net/jira/browse/JSR358-29](https://github.com/jcp-org/jsr358/issues/24).)

Steve pointed out that doesn't matter who is the user/consumer or where they are in the value-chain - rights are granted to any _**compatible implementation**_

Anish argued that the Spec Lead gets special rights today and pointed out that we need to ensure that rights granted for version 1 of a technology (defined in JSR x) will also permit the Spec Lead to incorporate IP from that JSR into version 2 of the technology (defined in JSR y.) Several members argued that this should not be a problem since "by definition" version 2 of a technology is also _Compatible_ with version 1\. Patrick argued that on the contrary version 2 is "by definition" **not Compatible** with version 1 (it supersets it.) Later inspection of the JSPA revealed that in section 4.A.I.a copyrights and trade secrets are granted for inclusion "into current and future versions of the Output," which seems to take care of this issue. However, there is no equivalent language in section 4.A.II which covers patent grants. An issue has been logged to track this ([http://java.net/jira/browse/JSR358-44](https://github.com/jcp-org/jsr358/issues/38))

Gil Tene argued that reciprocity must be mandated. We agreed that this was not central to the current discussion. An issue has been logged ([http://java.net/jira/browse/JSR358-45](https://github.com/jcp-org/jsr358/issues/39).)

We began to review the contents of slide 5 line by line.

Gil Tene noted that under the current JSPA the Spec Lead plays an aggregator role in the case of RAND grants. After "flattening" this would be lost. Scott Jameson argued that experience with other standards bodies showed that such aggregation is a bad idea.

Patrick noted that the presentation seemed to suggest that those who make Contributions have the right to opt-out of essential patent grants. He suggested that this is not what the current JSPA says.

We ran out of time for further discussion.

Anish Karmarkar agreed to draft an expanded version of slide 5 in table form, for further discussion. We agreed to meet weekly to continue our work.