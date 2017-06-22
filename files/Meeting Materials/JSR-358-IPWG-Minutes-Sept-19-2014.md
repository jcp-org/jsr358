# JSR 358 IP Working Group Meeting Minutes  
for September 19 2014

## Date

Friday 19 September 2014, 11:00-12:00 pm PDT

## Location

Teleconference

## Agenda

*   Review the [minutes of last meeting](https://java.net/downloads/jsr358/Meeting%20Materials/JSR-358-IPWG-Minutes-Sept-12-2014.md)
*   Further discussion of open-source RI licensing

## Attendees

*   Patrick Curran (PMO)
*   Don Deutsch (Oracle)
*   Scott Stark (RedHat)
*   Werner Keil
*   Mike DeNicola (Fujitsu)
*   Scott Jameson (HP)
*   Steve Wolfe (IBM)
*   Prasad Yendluri (Software AG)
*   Anish Karmarkar (Oracle)
*   Steve Harris (CloudBees)
*   John Pampuch (Azul)
*   Bruno Souza (SouJava)
*   Mike Milinkovich (Eclipse)

## **Minutes**

We reviewed the minutes of last week's meeting. Patrick encouraged further discussion, particularly from those who weren't present at last week's meeting.

Scott Jameson: asked Don whether we could hold another meeting with lawyers present to discuss the Apache issue again.

Don: I'm not sure it's worth discussing further. The FSF has declared Apache to be incompatible with GPL. [Note from Patrick: see http://www.apache.org/licenses/GPL-compatibility.html.] That's pretty much a show-stopper for Oracle. I'm not sure that anybody's mind would be changed by further discussion.

Scott: I share concerns that others have around MIT and BSD as the only alternatives. What about JSRs that aren't intended for inclusion in the platform? I believe that as the copyright owner Oracle would have the right to accept Apache-licensed code.

Don: Oracle indemnifies its licensees and therefore has the right to determine the terms on which it will accept code into the platform. The suggestion to accept MIT and BSD didn't come from Oracle - it was raised during one of the IP Working Group calls. Patrick and Don took the suggestion to Jim Wright and asked whether this might be a compromise that would be acceptable to both Oracle and EC members.

Patrick: I really want to hear peoples' thoughts on the suggestion that we permit MIT/BSD.

Scott: Adding MIT and BSD is better than having UPL only, but excluding Apache rules out the possibility of incorporating a large body of existing code (and code derived from it) into the Java platform.

Bruno: Apache licensed code could be relicensed.

MikeM. Not all lawyers would agree with that.

Don/Bruno: The Apache Foundation would not be willing to relicense their code under UPL.

MikeM: There's a large body of existing code under Apache - lots of innovative projects. The Apache license is probably the most popular license in the Java ecosystem. Don't shut that off.

Don: Patrick and I share your concerns. Nevertheless, do we think that adding MIT & BSD - admittedly a small step - is worth doing?

Steve Harris: Does HP have an opinion about the breadth of MIT/BSD?

MikeM: Don't assume that Eclipse will be willing to use the UPL.

Patrick: You could dual-license under EPL and BSD instead.

MikeM: The problem would be the requirement that contributors would have to sign a JCP membership agreement. That would undermine our vendor-neutral position. I'm not sure we should encourage/require people to sign a legal agreement with Oracle.

ScottS: I'm not sure that RedHat would be happy requiring a JCP membership agreement either. We are most unlikely to use UPL.

Don: What about MIT/BSD?

ScottS: Maybe - I'd have to talk to our lawyer.

ScottJ: Reconsidering - what's on the table is not just MIT/BSD, but MIT/BSD plus an Oracle contributor agreement.

MikeM: Agrees. How can we be vendor-neutral under these circumstances?

Don: Why would someone working on the RI for a JCP JSR be opposed to signing a JCP membership agreement?

Bruno: This proposal might exclude external communities from participating in Java development.

MikeM: This approach exludes the possibility that any innovation could happen elsewhere and then be incorporated into the Java platform. We'd have to reimplement everything in a clean-room manner. All future work on Java, for ever, would have to be done by Oracle. What happened to the "broad community"?

Don: Oracle is already doing 90% of the work.

Bruno: Don't we want to change that?

ScottJ: We note that Jim Wright has proposed some changes in the latest version of the UPL but we haven't yet had a chance to review this with the lawyers.

SteveW: Re UPL - I have concerns about relying on an "unverifiable text file" to manage our IP. What happens if we combine two Larger Works files with different contents? The file is designed to be modified at will.

Don: The expectation is that we we (the EC) define a specific Larger Works file and use that (and only that) for JCP RI projects.

Patrick: agrees.

SteveW: If a third-party created a Larger Works file that said "Java EE and Android" Oracle wouldn't accept it?

Patrick: What do you think?

Don: We can negotiate the contents.

MikeD: The problem with the MIT/BSD proposal is that it's MIT/BSD plus an Oracle agreement. Since Eclipse have signed the JSPA wouldn't that be enough?

Patrick: Is Eclipse Foundation the copyright holder of the output of Eclipse projects?

MikeM: No - and we're certainly not the patent-holder. So - I don't think MikeD's suggestion would work.

Patrick: Let's hear from John Pampuch since the original suggestion for MIT/BSD came from Azul.

JohnP: I understand the concerns people are raising. I don't understand why SteveW thinks that MIT/BSD are too liberal.

SteveW: The proposal for MIT & BSD was unexpected (I shouldn't have used the word "radical" last week). These licenses don't have explicit patent grants. I agree with others that excluding Apache shuts out a large ecosystem. People in the community will not understand this decision.

ScottS: You've added a secondary contributor agreement.

MikeM: Surely Oracle, as the copyright holder for all of the existing GPL-licensed code could "at the stroke of a pen" modify the Exception attached to GPL to state that co-mingling with Apache is OK...

You're requiring an additional license agreement. A unanimous vote of the Eclipse Board of Directors would be required for us to agree to this.

Patrick: There's no expectation that the Eclipse Foundation itself would impose the requirement. The Spec Lead would. This would be just another "filter" - no Open Source project permits just anybody to commit. The project lead has the right to define the conditions under which people are granted commit privileges.

MikeM: This doesn't help - you're still talking about requiring contributors to sign a contributor agreement with Oracle.

ScottS: I have a couple of questions about the UPL that came up in discussions with our lawyers:

1.  Our reading of the UPL is that the patent grants one is making are not restricted to the technology associated with the associated codebase, and as such, we don't see any entity with a nontrivial patent portfolio using the UPL. Is there a way to restrict the patent grants to the technology specified in the larger works file?
2.  If in fact our reading of the UPL scope of patent grants is unbounded, is Oracle reaffirming that they will contribute to JSRs that use the UPL?

Patrick: We're out of time. We'll continue this discussion at the F2F meeting next week (without lawyers).

## **Next meeting**

During the F2F meeting on September 25-26