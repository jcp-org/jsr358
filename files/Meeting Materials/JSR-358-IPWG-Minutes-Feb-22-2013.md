# JSR 358 Expert Group Meeting Minutes  
for February 22 2013

## **Date**

*   Friday 22 February 2013, 1:00-2:00 am PST

## Location

*   Teleconference

## **Agenda**

*   [JSR 358 summary](/files/Meeting%20Materials/JSR-358-February-2013.pdf)
*   [RedHat response on RI & TCK licensing](/files/Meeting%20Materials/RH_RI_TCK.pdf)
*   Follow up on recent discussions
*   Next steps

## Attendees

*   Patrick Curran
*   Steve Harris
*   Werner Keil
*   Anish Karmarkar
*   Scott Stark
*   Steve Wolfe
*   Mike Milinkovich
*   Regrets

*   Gil Tene
*   Scott Jameson

## Minutes

Patrick responded for the record to a question that Steve Wolfe posed in private email: when we can expect feedback from Oracle on the licensing proposals? Steve had argued that other matters are "gated" on this. Patrick responded that he thought there were several other issues (for example, the matter of Essential Patents) where we could - if we wished - make some progress independently of the licensing proposals. This discussion continued at the end of the meeting (see below.)

**RedHat's position on RI and TCK licensing**

Scott Stark gave [RedHat's response](/files/Meeting%20Materials/RH_RI_TCK.pdf) to the CloudBees proposal on RI and TCK licensing. He explained that RedHat wants faster change and argued that if we restrict the requirement to use open-source licenses only to new JSRs then change will be minimal. RedHat want all new and revised JSRs to be covered by open-source licenses **including the umbrella JSRs**.

Scott corrected slide 3: this should state that section 1.4 of the Process Document (not the JSPA) gives the right to define compatibility and branding processes. Patrick noted that this language is particularly weak (simply stating that the Spec Lead is responsible for defining a compatibility certification process) and asked whether RedHat believed that no additional language (in the JSPA, for example) was necessary. Scott responded "not necessarily."

Anish asked whether IBM could give their input on their experience with open source RIs and TCKs (since this is their routine practice.)

Steve Wolfe: "fraudulent" claims of compatibility can be dealt with but yes, people could take an open-source TCK and make perfectly legal claims about having passed the tests and met the compatibility requirements. We need a separate brand which could be protected. Whether or not you believe that open-source licensing is "compatible" with Compatibility we're past that point. The fundamental issue is cost recovery.

Scott Stark: it ought to be possible to define a process that enables people to have free access to the TCKs while still implementing a strong branding program and enabling cost recovery.

Anish: people would be able to say that they have run the TCK tests and are compatible with the specification.

Scott: we may need to add auditing to the compliance process.

Steve Harris: it would be helpful to have a use-case-based response from Oracle. What specifically are people worried about? Fundamental objections may apply to both the CloudBees and the RedHat proposal - however the CloudBees proposal attempts to minimize the risk by spreading it out over time. Patrick said he would ask for feedback to be provided in this manner.

In response to the slide _Compatibility #2_ Patrick noted that the first user could pass the TCK on to everyone else for free. Steve Harris: could we have separate licenses for use and for evaluation (R&D) as is done with Oracle Spec Licenses today?

Steve Harris: can't you add extra terms? You can get the TCK under an Apache license and meet these additional conditions. Patrick - then it's not an Apache license, it's some kind of weird hybrid. MikeM agreed and suggested that maybe the binary could be released under a different license.

Patrick: the challenge is to give people access to the TCK for evaluation purposes (to verify that it's good quality, to ensure that it meets the requirements of the Process Document) while still enabling a strong compatibility regime and cost recovery.

Slide 3\. Scott re-emphasized that we ought to be able to distinguish between "access" and "use for compatibility & branding."

Patrick asked Scott whether an evaluation license for the TCK in addition to a commercial license for branding purposes would meet his requirements. Scott said it would.

SteveW: an Open-JDK-like license might be acceptable.

**Next steps**

Patrick reiterated that although he and Don will meet with Oracle execs on Monday, it's most unlikely that they will get a formal response next week. Should we meet next week and if so, what should we discuss?

SteveW: I'm reluctant to move forward much more without knowing we're going to make real progress. It might be better for Oracle to come up with a proposal rather than making proposals when we have no idea whether they will be acceptable to Oracle.

In response to questions about Oracle's position Patrick reviewed the _[Summary Presentation](/files/Meeting%20Materials/JSR-358-February-2013.pdf)_ and pointed out that he had incorporated the responses that Don Deutsch had given last year (see the slides titled "Oracle response.") He noted that these address exactly the issues we are focusing on now.

After further discussion the consensus of those present was that we should not hold further Working Group meetings on these or other issues until we have received some solid feedback from Oracle.