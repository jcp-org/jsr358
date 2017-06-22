# JSR 358 IP Working Group Meeting Minutes  
for October 24 2013

## Date

Thursday 31 October 2013, 1:00-2:00 pm PDT

## Location

Teleconference

## Agenda

*   Review [last week's minutes](https://java.net/downloads/jsr358/Meeting%20Materials/JSR-358-IPWG-Minutes-Oct-24-2013.md)
*   Begin discussion of the following items from the [Issue List](https://java.net/jira/secure/IssueNavigator.jspa?mode=hide&requestId=11399):

*   [The role of the Reference Implementation](https://java.net/jira/browse/JSR358-29)
*   [Escrow process](https://java.net/jira/browse/JSR358-35)
*   [End of Life for JSRs](https://java.net/jira/browse/JSR358-34)
*   [Expert Group dissolution at Final Release](https://java.net/jira/browse/JSR358-32)

*   Next meeting: November 21

## Attendees

*   Patrick Curran
*   Mike DeNicola
*   Scott Jameson
*   Scott Stark
*   Werner Keil
*   Steve Harris
*   Heather Vancura

## Minutes

**Role of RI**

The direction we're taking - mandating an open-source RI - should resolve most of these concerns. We should mandate that a binary be released. We should also specify the sources from which the binary RI was built, so that implementers can build for their own platform from the exact set of sources used to build the binary RI.

**Escrow process**

Sources for the RI will be available but what about the TCKs? It could be very difficult legally for us to try to define a process to deal with what would be considered potentially valuable assets in a bankruptcy proceeding, particularly world-wide. More trouble than it's worth? Should we simply ask the Spec Lead company what their escrow process is? The EC could take this into consideration when voting.

**End of life**

Maybe not be worth worrying about. In rare cases a Spec Lead may be asked to provide a TCK for a very old JSR. Hopefully their internal engineering processes will enable them to do so. If not - deal with the consequences...

**Dissolution**

Can we distinguish between a JSR that is considered "complete" and one which is expected to evolve? In the latter case why would we not want the EG to stay alive? In the most significant cases a new JSR will be filed and a new (reconstituted) EG, but what about Maintenance Releases?

At Final Release the Spec Lead (EG) could make a statement as to whether or not they expect to continue to work on Maintenance Releases (and possibly new JSRs to evolve it). Is there a reason why we should not permit an EG to continue under these circumstances? (Ask Legal for feedback.)

**Action Item**

Patrick will incorporate the results of our discussions into the Issue Tracker.