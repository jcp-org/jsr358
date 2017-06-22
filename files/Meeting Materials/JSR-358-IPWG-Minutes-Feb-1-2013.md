# JSR 358 IP Working Group Meeting Minutes  
for February 1 2013

### Meeting details

*   Date & Time
    *   February 1, 2013\. 1:00-2:00 pm PST

*   Location
    *   Teleconference

### Agenda

*   Review [meeting minutes](/files/Meeting%20Materials/JSR-358-IPWG-Minutes-Jan-25-2013.md) from last meeting
*   [Steve Harris's proposal on RI and TCK licensing](/files/Meeting%20Materials/RITCKLicensingProposal-v1.1.pdf)
*   Review issues from [Issue Tracker](http://java.net/jira/secure/IssueNavigator.jspa?mode=hide&requestId=11399)
*   Follow up and next steps

## Attendees

*   Patrick Curran
*   Scott Jameson
*   Steve Harris
*   Anish Karmarkar
*   Steve Wolfe

## Minutes

We reviewed the minutes of the last meeting.

**The RI/TCK licensing proposal**

Slide 2: SteveH - don't include a commercial license. Instead handle the umbrella JSRs separately.

Slide 3: Scott: Contributor agreements are addressed here. SteveH: yes, but let's try to avoid digging into the details.

Slide 4: Scott: cost recovery now appears to be primarily Oracle's concern, but historically it hasn't been only Oracle. SteveH: at the f2f the sense seeemed to be that nobody but Oracle had serious concerns with the open-source model. If someone new comes in and wants to make money from JSRs maybe we should tell them "that's no longer the way we do stuff." Scott: suggest removing "Oracle" from this bullet.

Slide 5: SteveH: the definition of "new" may need to be expanded (what if a "new" JSR is logically an extension of an existing one?)

Slides 6 and 9: Patrick: Why would somebody choose the more restrictive license rather than the open-source version? SteveH: the open-source licenses say nothing about how the branding process works. It would have to be handled elsewhere. Out of scope for this presentation. Patrick: what is "the TCK" (as defined in the JSPA) for compatibility-related purposes? Is it whatever the Spec Lead says it is? It's the open-source licensed TCK unless it isn't? Scott: we need to redefine the coupling between the compatibility requirements and the TCK.

SteveW: I prefer to use the term Platform JSR rather than Umbrella JSRs, and believe that these would be the ones that you use for certification. SteveH: I was using the terms interchangably.

**Note:** neither the JSPA nor the Process document defines the term _Platform JSR_. The Process Document defines an _Umbrella JSR_ as "A JSR that defines or revises a Platform Edition or Profile Specification." (Profiles are included because these are considered to be fundamental _platform-like_ constructs in the Java ME space.)

SteveH: The spec license is what imposes the compatibility obligations.

Anish: IP rights flow only to those who pass "the TCK?"

SteveW: you can't claim compatibility by passing a derived TCK.

Scott: I will get IP rights via the Apache license on the RI. The Spec License is irrelevant under these circumstances.

Anish: The Spec license says that IP rights flow only to compatible implementations (those that pass "the official TCK.")

Scott: That's true if your implementation is independent. But if I derive from the RI I can do whatever I want.

SteveW: Scott's argument suggests that we can't use open-source licenses and maintain compatibility. That's not true. If you take the RI code and create a derivative work you don't get IP rights and you can't call your implementation Java. If you infringe my IP I can sue you.

SteveH: Do the Specification licensing limitations alone (with the associated IP grants) provide sufficient legal structure and incentive to achieve the JCP goal of compatibility when the RI and TCK are both available under open source licenses? Could IBM explain their belief that open-source licensing of the RI and TCK does not undermine the way in which compatibility can be maintained through the Spec License.?

SteveW: yes, I can do that. Hint - the value of the logo drives compatibility.

A follow-on question articulated by SteveH in response to concerns raised by Patrick and Anish: to what extent do we need to clarify the definition of TCK in Spec licenses or the JSPA to have confidence that the availability of an open source version does undermine the compatibility goals and cause ambiguity as to whether or not an implementation of the Spec is compatible?

SteveH empasized that the compatibility logo would be associated with the umbrella (platform) JSRs, which are exempt from the requirement to release an open-source RI and TCK. He noted that existing JSRs, and possibly also new JSRs that are substantially derived from existing JSRs, could remain closed-source. He wondered whether these exemptions would be sufficient to address Oracle's concerns from a business standpoint? Will Oracle agree to open-source new component JSR RIs and TCKs like everyone else?

Patrick promised to take these questions to Oracle's execs and to get an answer as soon as possible.