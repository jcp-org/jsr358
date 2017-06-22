# JSR 358 IP Working Group Meeting Minutes  
for July 18 2013

## Date

Thursday 18 July 2013, 1:00-2:00 pm PDT

## Location

Teleconference

## Agenda

*   Review [minutes of last meeting](https://java.net/downloads/jsr358/Meeting%20Materials/JSR-358-IPWG-Minutes-July-11-2013.md)
*   Continue discussion of [Spec IP-flow](https://java.net/projects/jsr358/downloads/download/Meeting%20Materials/IP-flow-v2.pdf) (working towards a term-sheet)
*   Continue discussion of IP-related issues excluding Contributor Agreements

*   See [Task List](https://java.net/downloads/jsr358/Working%20Documents/JSR358-TaskList.md) and [Issue Tracker](http://java.net/jira/secure/IssueNavigator.jspa?mode=hide&requestId=11399)

## Attendees

*   Patrick Curran
*   Scott Jameson
*   Steve Harris
*   Scott Stark
*   Mike Milinkovich
*   Steve Wolfe
*   Steve Winkler
*   Werner Keil
*   Anish Karmarkar

## Minutes

Don't get hung up on "derivative works" - grant rights to incorporate into compatible implementations.

Reciprocity provision: grants become null if grantee initiates litigation with respect to technologies developed through the JCP (compare Common Public License and Eclipse Public License). Look at Eclipse and Apache licenses for examples. Should offenders lose all the rights they have been granted through the JCP or only the rights for the particular JSR?

IP grants may be revocable under certain circumstances. For example, the current version of the JSPA permits copyright grants to be withdrawn if the terms under with the JSR will be licensed are substantially changed after the grant is made. What if I contribute thinking on the understanding that the license will be Apache and then the Spec Lead switches to GPL? ScottJ: no - we are choosing a small set of "approved" licenses and all should be considered acceptable.

Mike: not a problem with the flat IP model for the RI. The notion of withdrawing contributions is fundamentally incompatible with open-source development processes?

So - no conditions under which IP can be withdrawn?

SteveH: you may contribute to the Spec, but if the JSR takes a direction such that you no longer wish to be involved (because it may require you to give away your "crown jewels") Can you get out of your obligation to license your essential patents? (This is not a matter of withdrawing contributions that you have already made...)

Yes - you should be able to opt-out of the commitment to license your essential patents. If so, at what point? What if the direction changes half-way through? What would be the drop-dead point beyond which you cannot withdraw. What about Public Review?

IM from Anish Karmarkar:

> I think we ought to separete things wrt IPR related to contributions v. IPR related to partcipation -- as steve is saying. We should also separate these things wrt RI/TCK and spec  
> If you contribute you cannot get out of your obligations  
> If you leave before some trigger point, your participation risk should be limited

SteveH: what about contributions to the spec?

IM from Anish Karmarkar:

> Oother orgs have mechanisms to do periodic IP capture. The idea is that you don't want to wait for 2/3 years before the trigger (say final spec) to find out that someone is going to withdraw because they have patents they don't want to license  
> Recently OMG, OSGi Alliance, OASIS added a non-assert option but there are companies that don't like non-asserts