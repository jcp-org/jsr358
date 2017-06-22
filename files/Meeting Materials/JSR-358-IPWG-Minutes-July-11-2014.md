# JSR 358 IP Working Group Meeting Minutes  
for July 11 2014

## Date

Friday 11 July 2014, 11:00-12:00 pm PDT

## Location

Teleconference

## Agenda

*   Discussion of the UPL with lawyers present

## Attendees

*   Patrick Curran (PMO)
*   Jim Wright (Oracle)
*   Michael Gelblum (Oracle)
*   Steve Harris (CloudBees) - no lawyer
*   Susanne Cech (Credit Suisse) - no lawyer
*   Mike DeNicola (Fujitsu) - no lawyer
*   Scott Jameson (HP) plus lawyer (Nissa Strottman)
*   Steve Wolfe (IBM) - no lawyer
*   Don Deutsch and Anish Karmarkar (Oracle)
*   Scott Stark (RedHat) plus lawyer (Richard Fontana)
*   Prasad Yendluri (Software AG) - no lawyer
*   Bruno Souza (SouJava) - no lawyer
*   Leonardo Lima (V2COM) - no lawyer  

## **Minutes**

**Steve Wolfe:** I hoped that the IP**-**flow refactoring would make things simpler, but we now seem to be making things more complicated. We will now have three different IP license regimes: for the Spec, for the RI, and for Oracle.  

**Nissa:** Agrees with Steve. Rather than discuss the revised version of the UPL (haven't had a chance to review very closely) - let's discuss the possibility of taking an approach other than using the UPL.  

**Don:** Can we hear from someone other than HP before we decide not to talk about the UPL?  

**Jim:** We want to make it as easy as possible for everyone to consume the output.... I'd like to discuss Gil's suggestion that we add compatibility enforcement to the proposal. We could have added compatibility constraints/requirements in the Larger Works file. Could have said "the final RI and compatible implementations". That would mean that everyone would be making the broad patent grants for independent implementations.  

**Gil:** Today all compatible implementations of the spec get all necessary patent grants. We need to continue that.  

**Jim:** Do you want the broader patent grants under UPL (e.g., non-essential) to be licensed for compatible implementations?  

**Gil:** Should license only necessary patents for all compatible implementations. Incompatible implementations should not get rights.  

**Jim:** Enforcing compatibility is not "compatible" with the open-source development model.  

**Michael:** How to square the circle - reconcile open-source and compatibility?  

**Discussion of how far patent grants are licensed to incompatible implementations...  

Steve:** People understand how to contribute to "standard" open-source licenses. Now we're creating a custom license to address a different "regime" - Oracle's TLDA licensing. We haven't exhausted the "simpler" solutions yet.  

**Patrick:** The only suggestion I've heard is "use Apache".  

**Jim:** And "use BSD"...  

**Gil:** We want a flat IP licensing model. OSI approval is just a "nice to have". Compatibility should trump "open source".  

**Jim:** That's a much broader discussion. Is that what the EC wants?  

**Gil:** MIT or BSD are fine for outbound licensing. Inbound contributions should grant patent rights only to compatible implementations.

We then continued to discuss the "tensions" between the enforcement of compatibility and open-source licensing. Patrick pointed out that when we originally discussed the goals of JSR 358 we decided that strong compatibility requirements should be maintained. Scott Jameson added that he thought we had already made this decision. Nevertheless it seemed from the discussion among the EC members present at this meeting that the question might still be open. We agreed that we ought to discuss the matter once again with the full EC before continuing our discussion of the UPL.

Patrick agreed to put this topic on the agenda for the next EC meeting on August 12\. We agreed that we would need a crisp statement of the issues, and decided to work on this through email.

Patrick then suggested that in the meantime the Working Group could continue the "without lawyer" discussions on the other two open topics: the use-case analysis of a flat IP-flow, and the requirements for the "strengthened Exhibit B" (now called the _**Employer Contribution Agreement**_).  

## **Next meeting**

Friday July 18 at 11:00 am PDT.