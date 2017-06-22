# JSR 358 Working Group Meeting Minutes  
for March 5 2015

## Date

Thursday 5 March 2015, 9:00-10:00 PM PST

## Location

Teleconference

## Agenda

*   Review [minutes of last week's meeting](https://java.net/downloads/jsr358/Meeting%20Materials/JSR-358-IPWG-Minutes-Feb-26-2015.md)
    *   Flat IP flow
        *   Definition
        *   Use-cases

        *   Transferring IP from one Spec Lead to another while a JSR is in progress (perhaps because the original Spec Lead loses interest and the JSR goes dormant).
        *   Transferring IP from one Spec Lead to another after a JSR is completed (for example due to bankruptcy as in the Siemens, BenQ, Qisda case several years ago).
        *   Incorporating work developed elsewhere without the need to create "side-letters" (see JSRs 235 and 236), making it easier to implement _then standardize_ rather than - as today - _standardize then implement_.

    *   Prep for March 10 EC meeting
    *   Next steps

## Attendees

*   Patrick Curran (PMO)
*   Heather Vancura (PMO)
*   Scott Stark (Red Hat)
*   Mike DeNicola (Fujitsu)
*   Steve Wolfe (IBM)
*   Mike Milinkovich (Eclipse)
*   Prasad Yendluri (Software AG)

## **Minutes**

We reviewed the minutes of last week's meeting.

We then discussed use-cases and justifications for a flat IP-flow. We agreed on one: it would simplify the transfer of Spec Lead responsibilities since the "new" Spec Lead would automatically have the IP rights they need to pick up the old work and continue with it. (Under the current JSPA they could not do so unless they negotiated a transfer of rights from the old Spec Lead, and if the JSR was not final they would need to contact everyone who had contributed to the JSR in order to negotiate a transfer of IP rights.)

Steve, MikeM, Patrick believe that we can word the JSPA in such a way (IP is granted for inclusion in conformant implementations of this and future revisions of this JSR) such that IP would automatically be granted to a successor Spec Lead without the need for an explicit transfer. We also agreed that it would be preferable to that the JSPA does **not** refer to to the Process Doc (which is not a "legal" document in the same sense).

Patrick asked Mike Milinkovich to review the JSPA looking for language that would inhibit or prohibit the release of interim implementations of non-final JSRs. Patrick agreed to follow up with Don Smith (Oracle) on Eclipse's immediate concerns about implementing support for Java SE 9's modularity prior to the Final Release of the platform JSR.

Steve Wolfe suggested another possible use-case. If someone litigates against JCP member X, the hub-and-spoke IP model might make it difficult for X to apply defensive termination to the litigator since X got their rights from the Spec Lead. Steve promised write this up in more detail.

Another justification (not a use-case): we want an IPR policy that is "friendly" and "familiar" to the younger developer community who have grown up in an "open source world".

The other use-case we came up with during our earlier discussions related to the incorporation of standards developed in external organizations into the JCP. (How could JSR development be synchronized with external standards development that operates on a different schedule?)

We wondered whether this still a concern. (When we revisited this matter - the so-called "Purple JSRs - during the first phase of JSR 358 EC members expressed little interest in pursuing it.) Would immediate-vesting of IP solve the problem or do we need an additional change, and if so would flattening the IP flow help to resolve this?

We decided that we couldn't think of further use-cases but agreed that we should ask the full EC to do so during next week's meeting.

Our immediate goals for the EC meeting and after are to confirm that we have agreement on the IP-flow document and to develop the the use-cases/justifications for Oracle Legal. We would then take the document to Legal and and ask them to draft a new version of the JSPA.

Patrick asked whether we need to have specified all of our requirements before we approach Legal to re-draft. We agreed that we do not, but since turnaround is slow we should incorporate as many of our requirements as possible. Patrick pointed out that there are two major areas where we expect to want to change the JSPA: a flat IP-flow and the handling of patents. Since both of these are addressed in the IP-flow document, if we can agree on its contents then that would be a good time to request a re-draft.

We should therefore also discuss our patent proposal with the full EC. We should also ask whether members favor a non-assert or a Royalty-Free grant (either would work with the defensive-termination proposal we drafted earlier). Patrick suggested that the best way to take soundings on this would be a Doodle poll (members would be unlikely/unwilling to offer an opinion during an EC meeting, but instead would need to consult with their lawyers).

Finally, we agreed to schedule our JSR 358 discussions during the first hour of next week's EC meeting in order to accommodate members who may need to leave early. We also agreed to skip next week's Working Group meeting and to resume the following week.