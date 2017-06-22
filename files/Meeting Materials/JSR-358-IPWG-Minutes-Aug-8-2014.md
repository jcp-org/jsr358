# JSR 358 IP Working Group Meeting Minutes  
for August 8 2014

## Date

Friday 8 August 2014, 11:00-12:00 pm PDT

## Location

Teleconference

## Agenda

*   Review [minutes](https://java.net/downloads/jsr358/Meeting%20Materials/JSR-358-IPWG-Minutes-July-25-2014.md) of last meeting
*   Discussion of open-source and compatibility in preparation for next week's EC meeting

## Attendees

*   Patrick Curran (PMO)
*   Werner Keil
*   Steve Harris (CloudBees)
*   John Pampuch (Azul)
*   Mike Milinkovich (Eclipse)
*   Steve Wolfe (IBM)
*   Scott Stark (RedHat)
*   Anish Karmarkar (Oracle)
*   Prasad Yendluri (Software AG)
*   Heather Vancura (PMO)
*   Mike Marzo (Goldman Sachs)
*   Anil Kumar (Intel)

## **Minutes**

After reviewing the minutes of the last meeting Patrick introduced the subject. He noted that <font face="Times New Roman, Times, serif">our high-level goals for JSR 358, as we reported them most recently at the [public EC meeting in December 2013](https://jcp.org/aboutJava/communityprocess/ec-public/materials/2013-11-12/JSR-358-Progress-November-2013.pdf)</font>, include the following:

*   <font face="Times New Roman, Times, serif">Maintain compatibility guarantees.</font>

*   All JSRs will be covered by a standard Spec license that includes strong compatibility requirements.
*   <font face="Times New Roman, Times, serif">All implementations must pass the TCK.</font>

*   Embrace open-source licensing and development processes.

*   <font face="Times New Roman, Times, serif">Reference Implementations must be developed through open-source projects and released under open-source licenses.</font>

He noted that there is a fundamental tension between these goals, which cannot be (completely) reconciled since open-source licenses, by definition, cannot impose restrictions on what licensees may do with the licensed code. Licensees are therefore free to create incompatible derivatives of open-sourced RIs. He pointed out that these tensions exist today since most RIs not led by Oracle are licensed under Apache, while Oracle licenses the Java SE and Java EE platforms under GPL.

He argued that despite these tensions our current licensing model is reasonably successful at maintaining compatibility and we should not eliminate the compatibility requirements from existing licenses.  

On the other hand, he suggested that we should not create a new "open-source" license such as the UPL and attach compatibility requirements to it since doing so would render it "not open-source".

Scott reported that RedHat's lawyer had said that although it would definitely be unusual to incorporate compatibility requirements into an open-source license that would not necessarily be impossible. Mike agreed that it would certainly be difficult to do so - the language would have to be very general, with no mention of Java.

John Pampuch and Scott Stark pointed out that if the open-source license we adopt for RIs contains any ambiguity about the extent of the IP rights it grants, then implementers would have an incentive to pass the TCK in order to explicitly gain all the rights they need, which would be granted to them via the Spec License.

The group then discussed the possibility of using either BSD or MIT for RIs.

Anish noted that if we did this it would mean that derivatives of the RI would be in the same situation with respect to patent grants as independent implementations are. Both would only have "implicit" patent rights unless they passed the TCK and thereby gained explicit patent rights through the Spec License.

Patrick reminded the group that our primary goal on Tuesday will not be to propose a solution to the RI-licensing issue, but simply to establish whether the EC is in agreement on the overall approach. He suggested that we try to reach agreement on the following principles:

*   Compatibility is important, and the Spec License and the TCK process are the mechanisms we should use to encourage/enforce compatibility.  

*   RIs should be distributed under open-source licenses.
*   We recognize that there is a tension between these two goals: open-source licenses cannot impose compatibility requirements. Consequently, people will be free to create incompatible derivatives of open-sourced RIs.
*   If we create a new RI license (UPL, for example) we should not try to incorporate compatibility requirements into it.  

*   We want to provide an incentive for people who create implementations based on open-sourced RIs to voluntarily comply with the compatibility requirements in the Spec License.

Patirck asked whether those present at this meeting agreed with these principles. There was no dissent.�He agreed to incorporate this outline into the PMO presentation for discussion at next Tuesday's EC meeting.

## **Next meeting**

Friday August 15 at 11:00 am PDT.

## �