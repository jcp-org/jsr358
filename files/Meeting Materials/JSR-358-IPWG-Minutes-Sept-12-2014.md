# JSR 358 IP Working Group Meeting Minutes  
for September 12 2014

## Date

Friday 12 September 2014, 11:00-12:00 pm PDT

## Location

Teleconference

## Agenda

*   Further discussion of open-source RI licensing

## Attendees

*   Patrick Curran (PMO)
*   Don Deutsch (Oracle)
*   Scott Stark (RedHat)
*   Steve Wolfe (IBM)
*   Steve Harris (CloudBees)
*   Mike DeNicola (Fujitsu)
*   Anish Karmarkar (Oracle)
*   Heather Vancura (PMO)

## **Minutes**

**Patrick:** we have feedback from the lawyers on the UPL and also (coming soon - after exec approval) drafts of the three JSR 364 membership agreements. Don will provide the Oracle Legal feedback.

**Don:**

Oracle is responsible for licensing the platforms. For reasons that we've discussed in earlier meetings Oracle's Open Source Officer has decided that except for special circumstances (for example, an update to a JSR that was previously licensed under Apache) our intention is that from now on we will not incorporate Apache-licensed code into the Java platform.

The UPL was crafted to permit us to incorporate OS-licensed RIs into the platform; please use it. (As Jim Wright suggested at a recent meeting, we can tweak the contents of the Larger Works file to address your concerns about the license's reach.)

As an alternative to the UPL we can accept MIT or BSD-licensed code into the platform so long as contributors have signed a JSP membership agreement (JSPA or Affiliate) and indicate their intention to contribute to an RI project. This requirement will make sure that all contributors have made the necessary IP commitments, including explicit patent grants. We expect the Spec Leads to enforce this requirement.

We therefore propose that all RIs be offered under one of four possible licenses: UPL, BSD, MIT, and GPL. We will accept UPL-licensed RIs into the platform unconditionally. MIT and BSD-licensed RIs will be acceptable if the Spec Lead can confirm to Oracle that all contributors have signed a membership agreement. GPL-licensed code cannot be incorporated into platform due to Oracle's commitment to dual-license under commercial and GPL terms.

Oracle's current plans are to continue to license its own RIs (including the platform RIs) under GPL v2 (plus Classpath Exception). Oracle will be happy to contribute to RI projects where the outbound license is UPL, MIT, or BSD.

Comments/questions?

**Scott Stark:** any changes to the UPL since we last saw it?

**Don:** Jim suggested some changes but then the discussion got derailed. **Patrick** confirms.

**Steve Harris**: HP had some concerns about the breadth of the patent grant.

**Don:** I don't think we discussed these in depth, nor resolved them.

**Patrick:** let's assume that UPL can be tweaked to address concerns about breadth.

**SteveH** provided a [reference to a recent blog](http://h30499.www3.hp.com/t5/HP-Software-Solutions-Blog/Use-Oracle-s-UPL-Abandon-Your-Intellectual-Property/ba-p/6485626) from HP's CTO Martin Fink and suggested that this summarized HP's concerns.

**SteveH** wondered whether Eclipse dual-licensed under EPL and BSD, together with the Eclipse Foundation's contribution policies, would suffice?

**Patrick:** are you asking whether in this case Oracle would waive the requirement that all contributors must have signed a JCP membership agreement? If so, the answer is "no". He wondered whether the requirement that all contributors be JCP members would be considered a "side agreement" or an alternative to Eclipse's standard contributor agreement, and suggested that we need an opinion from Mike Milinkovich.

**Scott Stark** said that he would need to consult with RedHat's lawyer to figure out whether they can accommodate UPL.

**Steve Wolfe** argued that MIT and BSD are very radical licenses with very broad rights. IBM hasn't encountered them widely in the commercial world (they are used more in academic world). If the JCP rejects the Apache license we will significantly limit the number of potential contributors

**SteveH** agreed, reiterating that Apache is the license of choice for open-source development processes.

**Mike DeNicola** agreed with the concerns about not accepting Apache.

**Patrick:** anything more to discuss? Obviously we need feedback from HP and Eclipse...

**SteveW:** please clarify - the proposal is that only these four licenses are permitted for RIs?

**Patrick:** yes. **Don** agreed.

Someone then pointed out that Java EE is licensed under both GPL and CDDL. Members discussed whether the Spec Lead is permitted to license under multiple licenses.

**Patrick:** Our original intent was that the Spec Lead **must** offer the RI under one of the "approved" open-source licenses, but **may** also offer other licenses (e.g. additional open-source licenses or commercial licenses).

**Don/SteveW:** if something is licensed under both a restrictive and a liberal license it might be difficult to enforce the more restrictive license terms.

**Scott:** does Jim still intend to get UPL approved by OSI?

**Don/Patrick:** yes

We agreed that further discussion is needed and that we need input from more EC members.

**Next steps:** We will meet again next Friday. Patrick will ncourage other EC members to attend that meeting.

## **Next meeting**

Friday September 19 at 11:00 am PDT.