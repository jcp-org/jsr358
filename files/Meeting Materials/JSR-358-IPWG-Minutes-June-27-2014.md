# JSR 358 IP Working Group Meeting Minutes  
for June 27 2014

## Date

Friday 27 June 2014, 11:00-12:00 pm PDT

## Location

Teleconference

## Agenda

*   Discussion of the UPL with lawyers present

## Attendees

*   Patrick Curran (PMO)
*   Jim Wright (Oracle)
*   Steve Harris (CloudBees) - no lawyer
*   Susanne Cech (Credit Suisse) plus lawyer (Robert Fleming)
*   Mike DeNicola (Fujitsu) - no lawyer
*   Eileen Evans and Nissa Strottman (HP lawyers)
*   Steve Wolfe (IBM) plus lawyer (Jeff Thompson)
*   Don Deutsch and Anish Karmarkar (Oracle)
*   Scott Stark (RedHat) plus lawyer (Richard ???)
*   Prasad Yendluri (Software AG) - no lawyer
*   Bruno Souza (SouJava) - no lawyer
*   Leonardo Lima (V2COM) - no lawyer  

## **Transcript**

**Jim:** apologized for not providing a written response in advance of the meeting.  
He recognizes he won't be able to address everyone's concerns, but has a proposal that he hopes will address many of them.  
Two changes:  
1) Remove reference to current and future versions from the license - this can be placed in the Larger Works (LW) file if necessary  
2) Recognizing that some have interpreted the UPL draft as granting patent rights (as well as copyright) for derivative works, he is willing to clarify (the intent was only copyright).  
He had considered Azul's suggestion that LW should include "Compatible implementations of this JSR" but is now disinclined to use this language since he believes many do not want to make patent grants to any compatible implementation, particularly with respect to non-Essential patents.  

**Eileen:** why not just use Apache? **Jim:** we're trying to solve for multiple uses. We need a purely-GPL compatible solution. Apache is not compatible.  

**Eileen:** So Apache is a non-starter? Maybe we can discuss this offline?  

**Jeff****:** What are your concerns about Apache? What makes it incompatible with GPL? We want defensive termination (DT) - and it's precisely this that makes Apache incompatible with GPL. So that problem can't be solved.  

**Jim**: the Spec License is a separate matter...  

**Jeff:** You seem to be incorporating some Spec-license-like stuff into the UPL.  

**Jim:** The LW file could say "JSR X"  

**Jeff:** That's a Spec-license type of commitment - should be covered by the JSPA.  

**Jim:** The LW could say "just the RI for JSR X" - then the grants would not extend beyond the RI.  

**Jeff:** We're happy to make patent grants with respect to our contributions. We don't want a broad commitment with respect to others' contributions (referencing our Essential or even non-Essential patents) without a DT clause.  

**Jim**: I'm more concerned about people in this room suing each other than about outsiders...  

**Jeff:**  IBM has long believed that the Essential Patent grant should be RF rather than RAND. DT is the reason we're incompatible with the GPL so you're stuck with that.  

**Jim:** Grants wouldn't extend beyond the RI to other (Independent) implementations.  
 **Jeff:** Would Oracle be willing to contribute to a project under the UPL?  

**Jim:** Yes.  
 **Eileen:**The Apache license is well established - it has a DT clause.  

**Jim:** It's not generically GPL compatible...  
 **Eileen:** What about GPL v3?  

**Jim:** We're committed to V2.  

**Jeff:** You could use BSD and make the patent licenses explicit in the JSPA.  

**Jim:** Then we wouldn't need this license at all - the JSPA would be sufficient.  

**Jeff**:You are relicensing under the GPL code that IBM contributed under terms that include DT. Are you violating the GPL? I don't think so.  

**Jim:** Hmmm...  

[More exchanges between Jim and Jeff that I didn't catch.]  

**Jim:** We considered an empty LW file but we wanted to extend the grants to the final released version of the RI (and not have them limited to the state of the project at the time of the contribution).  

**Eileen:** We'd like to see defensive termination.  

**Jim:** Very few people are hung up on defensive termination.  
 **Nissa:** Why not have people contribute under Apache with an "Exception" in which they explicitly grant permission for their contributions to be relicensed under GPL?  

**Jim:** We want something more general - must be relicensable on any terms.... We're not going to change our outbound licensing model.... We can have more offline discussions if you want.  

**Eileen:** OK.  

**Jim:** Bear in mind that there will be an "interface" between this and the JSPA.  

**Steve Harris:** Given an "interface" I don't see why you can't just accept Apache.  

**Don:** For those of you who contribute to open-source forges ... Do the contribution agreements typically have DT clauses? I see the need for them from an SSO perspective but maybe in the open source world grants are broader.  

**Jim:** It depends on the license - some OS licenses have DT, some don't.  

**Eileen:** The OS activities HP contributes to typically do have DT (eg. Open Stack, which is Apache-licensed).  

**Jeff:** For IBM also the answer is typically "yes", though we also sometimes contribute under MIT.  

**Jeff:** All the code Oracle has received under the JSPA was contributed under terms that included DT. This is functionally equivalent to accepting code under Apache.  

**Jim:** Just because we've done something less than ideal in the past that doesn't mean we will continue to do it that way in the future.  

**Jeff:** We've been doing business this way for 20 years...  

**Steve Harris:** One of our goals when we started this exercise was to use a **familar** license. Apache is the obvious way to go. We're trying to solve a problem that only Jim (Oracle) cares about.  

**Mike DeNicola:** I want to know what problem we're trying to solve...  

**Steve Harris:** Using Apache seems to be off the table from Oracle's perspective...

**Patrick:** Jim: can you clarify if that's so, and why? Also, it would be good if Jeff or someone else would write up the Apache proposal - explaining why they think it's feasible. We also need to see Jim's revised UPL proposal, and it would be helpful to have a written explanation of Oracle's objections to using Apache.  

## **Next meeting**

Friday July 11 at 11:00 am PDT.