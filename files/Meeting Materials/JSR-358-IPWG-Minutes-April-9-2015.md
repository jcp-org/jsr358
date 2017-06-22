# JSR 358 Working Group Meeting Minutes  
for April 9 2015

## Date

Thursday 2 April 2015, 9:00-10:00 PM PST

## Location

Teleconference

## Agenda

*   Review [minutes of last week's meeting](https://java.net/downloads/jsr358/Meeting%20Materials/JSR-358-IPWG-Minutes-April-2-2015.md)
*   Review [Action Items](https://java.net/jira/issues/?filter=12421)
*   Review the Doodle polls
*   Review [open Issues](https://java.net/jira/issues/?filter=11400)
*   Next steps

## Attendees

*   Patrick Curran (PMO)
*   Steve Wolfe (IBM)
*   Heather Vancura (PMO)
*   Mike DeNicola (Fujitsu)
*   Scott Stark (Red Hat)
*   Anish Karmarkar (Oracle)
*   Don Deutsch (Oracle)
*   Mike Milinkovich (Eclipse)

## **Minutes**

We reviewed the minutes of last week's meeting, the Action Items, and the Doodle poll results. Re the polls, in the absence of a significant majority of Yes votes we should make no changes. Neither poll meets this criterion, so both - for now - are non-starters.

We reviewed open issues:

[JSR358-72](https://java.net/jira/browse/JSR358-72): Clarify what is appropriate for a MR and what should go into a new JSR

Patrick: extreme case - any change to defined APIs should be forbidden. If the sig-test would fail, you need a new JSR

MikeM: if a change to RI or TCK is required, need a new JSR.

Heather: don't take away the right to fix bugs...

EC has right to flag a change as "too big".

Scott: EG can speak up too, and they do...

[JSR358-37](https://java.net/jira/browse/JSR358-37): Collaboration with other Standards-Setting Organizations

Patrick: nothing to do? To the extent that our IPR policy is compatible with others, we should be OK. Two cases: others adopt our standards, and we build on theres.

MikeM: inbound is more significant.

Not much to suggest here.

Don: collaboration (joint projects) is not typically possible due to differing IPR policies. Anything to prevent others from normatively referencing our standards? Patrick: no.

[JSR358-34](https://java.net/jira/browse/JSR358-34): End of Life for JSRs

Variants: 1) the technology is dead and 2) an earlier version of the JSR has been superceeded.

Mike: when the Spec Lead says "no longer supported"

Patrick: should be an EC decision?

Mike: yes. look at the inactive JSRs. PMO could periodically review.

Scott: some companies may want to support earlier versions - if they can't get the TCK that could be a problem.

Patrick: should we have a responsibility to respond to test challenges on an architecture that doesn't exist today. What if the TCK will not run at all? Does the Spec Lead have an obligation to provide a functioning TCK.

Scott: what rights does the implementing company have with regard to TCK?

Mike: ISO reviews existing standards every five years: asks the originator "are you still willing to maintain this standard? If not, we will withdraw it."

Don: Yes - ISO reviews all existing standards every five years, and vote on whether spec should be revised, continued in its current state, or withdrawn. Practically speaking it's almost impossible to withdraw anything. Even the punch-paper tape standard couldn't be withdrawn because someone said "we're still using it"!

Mike: when a standard is withdrawn, the IP rights go away.

We agreed that we will discuss the IP-flow document and review open issues during next week's EC meeting. The Working Group will not meet next week, but will meet again the following week.

## Next meeting

During the EC teleconference: Tuesday April 14 2015, from 7:00 am to 9:00 am PDT.