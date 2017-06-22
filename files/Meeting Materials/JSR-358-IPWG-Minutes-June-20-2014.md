# JSR 358 IP Working Group Meeting Minutes  
for June 20 2014

## Date

Friday 20 June 2014, 11:00-12:00 pm PDT

## Location

Teleconference

## Agenda

*   Discussion of the UPL with lawyers present

## Attendees

*   Patrick Curran (PMO)
*   Jim Wright (Oracle)
*   Michael Gelblum (Oracle)
*   Paul Manfrini (ARM) - no lawyer
*   Gil Tene and John Pampuch (Azul) - no lawyer
*   Steve Harris (CloudBees) - no lawyer
*   Susanne Cech (Credit Suisse) plus lawyer
*   Mike Milinkovich (Eclipse) - no lawyer
*   Maulin Patel (Freescale) - no lawyer
*   Mike DeNicola (Fujitsu) - no lawyer
*   Scott Jameson (HP) - plus lawyers
*   Steve Wolfe (IBM) plus lawyer
*   Anish Karmarkar (Oracle)
*   Scott Stark (RedHat) plus lawyer
*   Prasad Yendluri (Software AG) - no lawyer  

## **Minutes**

**HP**  

Is concerned generally about license proliferation. Fears that UPL may encourage "downstream" license proliferation due to its perceived defects.  
1\. Explicit patent grants are fine, but the UPL is far too broad.  
2\. Lack of defensive termination.  
3\. "Future versions" language is potentially problematic depending on what is in the Larger Works file  
Assumes that the right to opt-out of patent grants will be specified in the JSPA.  

What problem are we trying to solve?  

Patrick provided a quick summary: we're looking for a license that will permit Oracle to incorporate "third-party RIs" into the platform and then re-license both commercially and under GPL.  

We noted that Eclipse projects would have to be dual-licensed under EPL and UPL.  
Dual-licensing would also be required for RIs developed at Apache.  

**IBM**  

Agrees with all of HP's concerns re broad patent grants  
Happy to contribute to conformant implementations, but are concerned about broader grants.  

Need to discuss not just whether UPL is a good license...  
Is it an appropriate license for the JCP?We're hoping to implement a flat IP flow  
Will Oracle license RIs under UPL?  

Patrick: Oracle will continue to license RIs under GPL + ClassPath Exception  
Jim: Oracle does intend to use it to license other items  

The goal was to have a single license that everyone would use  
Would Oracle be comfortable contributing under this license?  

What will be in the Larger Works file?  
If it says "Java SE" then all Oracle's patents would be "open"  

Nobody within the JCP would be able to assert a patent.  
This is potentially a good thing.  
However, it does nothing to protect JCP members against third parties who assert against us.  

**Red Hat**  

Concerned that this license will not encourage open-source RI projects  
Want multiple participants in those projects. An unfamiliar license (with very broad patent grants) might discourage participation.  
Wouldn't be too concerned if Oracle also used this license but it seems they won't.  
If Larger Works says "Java, now and in the future" that would be extremely broad.  
"Java" is open to interpretation.  

**Software AG** Want to see specific examples of contents of Larger Works file.  

**Azul** Wants a flat model (inbound/outbound)  
Summarizes current grants (in JSPA)  
People seem to be comfortable with Royalty Free grants for contributions.  
Larger Works file should specify just the RI being worked on.  
Should not be modifiable in future.  
Jim: we don't expect that it can be modified.  

Larger Works file should say "compatible implementations of JSR X"  
Should not go beyond what the JSPA says today.  
Whatever we come up with should incorporate compatibility requirements  

UPL has very broad patent grant.  
Seems to extend to derivative works.  

**CloudBees** How can OS projects evolve/be forked in context of Larger Works (unknown - could get very messy)  
Question for Oracle Legal: please explain why Apache license is unacceptable to you  

* * *

Request: please provide responses in email before next week's meeting where possible.  

## **Next meeting**

Friday June 27 2014 at 11:00 am PDT.