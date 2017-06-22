# JSR 358 Working Group Meeting Minutes  
for March 19 2015

## Date

Thursday 19 March 2015, 9:00-10:00 PM PST

## Location

Teleconference

## Agenda

*   Review [minutes of last week's meeting](https://java.net/downloads/jsr358/Meeting%20Materials/JSR-358-IPWG-Minutes-March-5-2015.md)
*   Review [Action Items](https://java.net/jira/browse/JSR358-90?filter=12420)
*   Review the new [IP-Flow document](https://java.net/downloads/jsr358/Working%20Documents/IP-flow-v10.pdf)
*   Wording for Doodle polls on patent policy
*   Flat IP flow
    *   Use-cases

    *   Transferring IP from one Spec Lead to another while a JSR is in progress (perhaps because the original Spec Lead loses interest and the JSR goes dormant).
    *   Transferring IP from one Spec Lead to another after a JSR is completed (for example due to bankruptcy as in the Siemens, BenQ, Qisda case several years ago).
    *   Incorporating work developed elsewhere without the need to create "side-letters" (see JSRs 235 and 236), making it easier to _implement then standardize_ rather than - as today - _standardize then implement_.

    *   Review the [side-letter](https://jcp.org/aboutJava/communityprocess/JCP_SCLA.pdf) that was used for JSRs 235 and 236\. Is this issue still important? If so, how will a flat IPR policy help?

    *   Enable a member who is not the Spec Lead to apply defensive termination against someone who initiates litigation alleging patent infringement.

*   Next steps

## Attendees

*   Patrick Curran (PMO)
*   Michael Berg (Intel)
*   Mike DeNicola (Fujitsu)
*   Anish Karmarkar (Oracle)
*   Mike Milinkovich (Eclipse)

## **Minutes**

We reviewed the minutes of last week's meeting and the open AIs.

We had a brief discussion about Steve Wolfe's use-case, agreeing that defensive termination will be simpler if the Spec Lead is not in the middle. Patrick will remind Steve of his AI to write up this use-case.

We reviewed the new version of the IP-Flow document and discussed whether the two proposed poll questions really are (or need to be) linked. We agreed that they do not, if we re-word the first question to make it clear that we propose only to replace Royalty Free patent grants with a non-assert covenant. Michael Berg asked whether the licensor would be free to define the precise terms of the non-assert covenant. We agreed that - as with the current RF grants - the terms would be standard, and defined in (or referenced normatively from) the JSPA.

We therefore agreed to change the first question to "Should we replace explicit Royalty-Free patent grants with a JCP-standard non-assert covenant?"

This change will make it possible to answer yes to the first question and no to to the second.

For clarity, we agreed to change the second question to: "Should we remove the obligation to license on FRAND terms Essential Patents for JSRs where the patent-holder does not serve on the EG?"

Anish asked whether a non-assert policy might be considered more OS-friendly than explicit RF grants. Mike Milinkovich responded that he's not sure there's a significant difference. He did note that the Free Software Foundation has a political preference for non-asserts.

Anish: some companies prefer RF since this would in theory permit them to impose **some** conditions.

Anish: OASIS and OSGi both have non-assert IPR modes. For the past couple of years most (all?) OASIS TCs have chosen non-assert.

Anish: suggests we provide some background to help those who were not on this call understand exactly what we are referring to in each case.

Patrick agreed, suggesting that the three different grants: IP Grants from Contributors, Essential Patent grants from EG members with respect to material they did not contribute, and Essential Patent grants from non-EG members be numbered. The Doodle polls can then state that the first question refers to grants #1 and #2, while the second question refers to grant #3.

Mike Milinkovich reminded Patrick that we've agreed to also include a "don't care" option in the polls. Patrick agreed to do so, and also suggested including an "if need be" option if that is possible for multiple-choice questions.

We then moved on to a discussion of the Supplemental License Agreements ("side letters") from JSRs 235 and 236, wondering whether we will need similar language in the JSPA. We thought not, since the purpose of these agreements seems to have been to ensure that patent grants vest before the JSR goes final, and we are already planning changes to address this.

Anish reported that the SDO concept (incorporated into JSR 235) was developed in a private "consortium" in which IBM and BEA were prime movers, and was then donated to OASIS. We agreed that it would be helpful to find someone (Steve Wolfe?) who was involved in or knows about the original discussions in order to help us to understand the motivation behind these agreements (what particular IP-case was being addressed)?

Mike Milinkovich expressed the opinion that these agreements addressed a "corner case" and suggested that we probably shouldn't spend much time addressing them.

Patrick agreed, but noted that we should not "paint ourselves into a corner" by modifying the JSPA in such a way that we would be unable to incorporate an externally-developed standard into the JCP.

We agreed to add that as a goal to the IP-Flow document and to remove this particular item from the list of use-cases.

Patrick promised to initiate the Doodle polls and to update the IP-Flow document for further discussion at next week's meeting. [See the [Document Archive](https://java.net/projects/jsr358/pages/WorkingDocuments) for an updated version (v.11) of the IP-Flow document.]

## **Next meeting**

Teleconference: Thursday March 26 2015, from 9:00 am to 10:00 am PDT.