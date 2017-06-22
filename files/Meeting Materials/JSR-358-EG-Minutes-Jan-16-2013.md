# JSR 358 Expert Group Meeting Minutes  
for January 16 2013

## **Date**

*   January 16, 2012

## Location

*   During the EC face-to-face meeting in Santa Clara, CA

## **Agenda**

*   Report from IP Working Group (Patrick Curran, Steve Wolfe, Anish Karmarkar)

*   [IBM's proposal on Patents and Standard Licensing](/files/Meeting%20Materials/Patent-Altenatives-and-Standard-Licenses.pdf)

*   [Individual members: how other standards bodies do it](/files/Meeting%20Materials/Standards-Individual_Participation.pdf) (Bruno Souza)

## Attendees

*   All EC members except ARM and Nokia were represented at the meeting

## Minutes

#### Standard licensing terms

EC members then reconvened as the JSR 358 Expert Group. Patrick provided a brief summary of the activities of the _IP Working Group_ and discussion then focused on IBM's proposals for standard licensing terms. Steve Wolfe summarized the proposal (see [the presentation](Patent-Altenatives-and-Standard-Licenses.pdf) for details.) He argued that the JSPA is too complex, and that modern software developers expect a simpler, "more open" licensing model. He noted that very few JSRs are led by anyone but Oracle, and suggested that this complexity is partly responsible for that disparity. He recognized that Oracle must be able to fulfil its commercial obligation and to monetize the "enormous investment" it has made in Java. He suggested that we try to craft a JSPA that builds on standard licenses while at the same time adding the necessary provisions to support Oracle's obligations. We should not start with the current JSPA and try to engineer the complexity out of it - rather we should start with something new and very simple, and add on whatever is necessary to support Oracle. He asked whether EC members generally supported the basic idea of defining standard licenses.

Several EC members expressed their support for this idea. Steve suggested that one of the standard licenses might be the OpenJDK TCK license.

Patrick noted that in the IP working group we had discussed two different approaches to matching inbound and outbound licensing terms:

1.  to create a single inbound license that is broad enough to cover all outputs
2.  to define several inbound licenses, each of which maps to one of the approved outbound licenses

He asked how the inbound license(s) could cover the case where the Spec Lead chooses a commercial outbound license for the RI or TCK?

Scott Jameson argued that the first approach is the cleanest and simplest.

Gil Tene pointed out that we must consider both patents and copyrights for each of the three artifacts: Spec, RI, and TCK. He argued that binary licenses for the RI and TCK would be sufficient for the needs of implementers, and noted that Azul is more concerned about the ability of implementers to access these binaries in a consistent manner.

Don Deutsch asked why the JSPA had been drawn up to give Spec Leads the choice of their own licenses. Steve Wolfe responded that in the early days Sun believed that the opportunity to monetize investment would encourage participation.

Steve asked whether EC members believed that such "license freedom" is still necessary.

Scott Stark argued for free access to RIs and TCKs. Steve Wolfe asked why we couldn't use the OpenJDK TCK license model. Gil responded that the license doesn't permit test results to be shared. Patrick noted that we wrote into JCP 2.8 a statement that TCK licenses must not prohibit such sharing and pointed to language in the license that explicitly permits sharing. Scott argued that this doesn't go far enough since it doesn't permit the sharing of the tests themselves. Patrick responded that this matter has been discussed within Oracle and that there is no intent to prohibit the free discussion of test results including exchanging whatever portions of the TCK might be necessary for that discussion.

Steve Harris asked why can't we simply offer a standard menu of licenses. Gil responded that this would be OK so long as provision was made for Oracle. Steve responded that we shouldn't complicate things by including a commercial license for Oracle. Gil noted that this is unrealistic, since most JSRs are led by Oracle [After the meeting Steve Harris submitted a [detailed proposal](/files/Meeting%20Materials/RITCKLicensingProposal-v1.1.pdf) to the IP Working Group, where it is under consideration.]

It was suggested that we simply include a "commercial license" as one of the options that any Spec Lead could choose. Steve Wolfe pointed out that while it is OK to predefine a list of licenses it would not be appropriate for the EC to "approve" or "disapprove" another member's choice of license.

Steve Wolfe suggested that Oracle could craft such a commercial license. Gil suggested that the license should permit "R&D" but need not necessarily permit certification of compatibility. Scott Stark replied the the license must permit "R&D" by any JSR contributor, but need not necessarily permit certification of compatibility.

EC members agreed that a small number of standard licenses will be defined. The Spec Lead must offer at least one of these. Implementers will be free to negotiate separate (additional) licenses with the Spec Lead if they wish.

Gil argued that one of the standard licenses should be modeled on the OpenJDK TCK license. Patrick pointed out that this license is in fact quite restrictive, since it permits use only on implementations derived from OpenJDK and that will be licensed under GPL. Gil responded that it should be more broadly formulated with a specific scope related to a particular body of open source work. He also reiterated his concern that licensees have continuity - a guarantee that they can continue to license the TCK. He noted that currently the license is renewable yearly and said that Azul needs more of a " runway."

We agreed that we will need a formal process for modifying the list of approved licenses. Since modifying the JSPA might be too time-consuming we might need a more lightweight process to add a license to the Addendum.

Patrick asked about the inbound grants. Scott Jameson said that this would depend on the outbound licenses. Mike Milinkovich argued that symmetry between inbound and outbound makes things very simple. Patrick asked what inbound license would correspond to an outbound commercial license. Mike suggested a commercial inbound license like the OCA that grants ownership.

Steve Wolfe asked how we should handle the additional grants necessary for inclusion in the platform? Should this be built in to the inbound license or should it be a supplemental grant? Mike Milinkovich argued that a supplemental license would be unmanagable given the number of contributors (too much paperwork.) This would prohibit hosting a project at Apache, for example.

We discussed the possibility of polling members to ask what licenses they wanted to include but agreed that this is not necessary right now since we seem to have broad agreement that these should include: GPL + classpath exception, Apache, EPL, "commercial," and "intended for inclusion in the platform."

Patrick suggested that as a next step Don Deutsch and he would talk to Oracle's lawyers to see if they could suggest/draft a list of sugggested licenses, and that they would report back to the EC at a future meeting.

Throughout this discussion we addressed, but did not resolve, the question of whether or not the _Essential Patent_ grants defined in Section 6 of the JSPA should be preserved or whether JCP members' obligations (to grant Essential Patents even for JSRs they are not involved with) should be relaxed. In the process of the discussion we distinguished the following conditions that must be considered:

*   If you are a member of the EG: you make essential patent rights.
*   If you are not in the EG and you make a contribution: you grant essential patent rights with respect to that contribution.
*   If you are not in the EG and you don't make a contribution: should you or should you not make essential patent grants?

Steve Wolfe, Scott Jameson, and Mike Milinkovich agreed to get together to develop a more specific proposal on essential patents (factoring in the conditions under which grants might be terminated.)

#### Individuals and IP flow

We then moved on to a discussion of the role of individuals within the JCP and how we could ensure that all contributed IP is covered by an appropriate grant. Bruno Souza presented [a summary](Standards-Individual_Participation.pdf) of how several different standards organizations handle this matter. It soon became clear that although there is no consistent "industry-wide" process for handling individual memberships, the JCP's approach - whereby individuals can accrue without charge all of the benefits that commercial organizations have - is unique. Several EC members argued that we should be more concerned about ensuring that donated IP is "secure" than with encouraging large numbers of individuals to "join" the organization when they might not in fact be willing to participate in any meaningful way. Other members expressed concern that if we change the membership rules now we might undermine our recent emphasis on transparency and participation.

On the matter of individual members acting as _agents_ of their employers we agreed that employed individuals should not be permitted to join an Expert Group unless their employer is willing to sign the JSPA. This would not necessarily amount to "free membership" for the employer since a reduced fee might be charged, and the privileges of such membership might be less than those granted to "full" members.

We suggested that we might be able to define additional categories of membership for individuals that would not involve the employer signing the JSPA (for example, an _Associate Individual_ membership.) We decided that an ad-hoc group should be formed to work on this and to come back with suggestions. As a first step, Bruno Souza agreed to produce a summary document that could be used as a starting point for discussion.

We also agreed that - following the Eclipse model - we need an _IP Provenance_ process to enable Spec Leads to judge the "IP quality" of contributions. We did not make any specific proposals for how to achieve this.