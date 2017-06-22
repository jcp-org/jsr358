# JSR 358 IP Working Group Meeting Minutes  
for July 11 2013

## Date

Thursday 27 June 2013, 1:00-2:00 pm PDT

## Location

Teleconference

## Agenda

*   Contributor agreements and incorporating non-Oracle JSRs into the platform

*   With special guest Jim Wright - Oracle's Open Source Policy and Strategy Officer

## Attendees

*   Patrick Curran
*   Mike Milinkovich
*   Scott Jameson
*   Scott Stark
*   Heather Vancura
*   Steve Harris
*   Mike DeNicola
*   Werner Keil
*   Anish Karmarkar
*   Anil Kumar

## Minutes

Introductions. Patrick summarized. MikeM: it's not so much that Eclipse has a well-regulated IPR but that Apache and Eclipse have their own CLAs and it would be technically and culturally difficult for them to adopt an additional/replacement CLA at the JCP's request.

Steve Harris we want to ensure that RIs and TCKs can be developed at open-source communities. Choose a set of licenses that are familiar to people. Work with the open-source communities.

Jim: we need to maintain our ability to incorporate code into the platform. Obviously we can't take things with viral licenses.

If we take it as a given that it's a good thing to have code developed at "external" OS communities then how can that code be licensed to Oracle in a way that permits its incorporation into the platform? Provided that an open-source organization has a Contributor Agreement that permits a project license that will grant the necessary rights to Oracle then we might have a solution. Hypothetically Eclipse might have a CLA that commits to a license that meets our needs but perhaps Apache might not. Does each Forge's CLA and licensing regimen permit us to incorporate? We might need to audit each on a case by case basis. We don't want to police others so we must be able to rely on the CLAs and licenses. We don't really want to have to review each of the CLAs and to potentially have to argue with them.

MikeM: it's **necessary** for Java's success that development happens outside of Oracle. We all agree on that.

Jim: whether or not that's true we cannot accept arrangements that do not permit us to incorporate into the platform.

MikeM: we agree that you need those rights for JSRs that are incorporated into Umbrella JSRs. Perhaps we should grant the rights only when a decision is made to incorporate. Do we need a regime for all JSRs that might potentially be incorporated in the future?

Jim: is it OK to say that all JSRs must at least be **licensed** in a manner that permits us to incorporated.

SteveH: Oracle has the right not to take stuff that isn't licensed appropriately. Quotes the example of the EclipseLink RI that was developed at Eclipse and incorporated into JavaEE.

Patrick: that was dual-licensed under BSD.

MikeM: the EPL + BSD combination is fairly common for projects that potentially might be licensed under GPL. We'd be happy to use that combination for JCP.

Patrick asks Jim whether we would be OK with BSD? Jim doesn't want to answer that right now.

MikeM: There are no explicit patent grants under BSD but we generally hold that having a dual license covers us. The patent grants come in under EPL Note that the combination of BSD plus patent grants is generally equivalent to Apache. Some Eclipse projcts are licensed that way.

Jim: are you guys OK with a process that says we need to evaluate the different forges and determine whether the combination of the CLA and the licensing regime is acceptable? If they are suitable then and only then could an RI project be hosted there.

MikeM: prefer to use the term Foundation rather than forge. I expect the number of "approved" Foundations to be small. We probably won't pull random stuff from GitHub.

ScottJ: a couple of issues are being discussed. Licenses, and the IP regime (patent grants, for example). Are there other concerns?

Jim: these were the two issues that seemed most important to me. That we can incorporate the code with minimal risk and that we have assurance that the foundations have processes in place to permit development to take place there without risk. Maybe choose one or two appropriate foundations?

ScottJ: I suggest that we define the characteristics/requirements we would want and that we would use to evaluate foundations.

MikeM: would prefer that approach to imposing a separate CLA on Eclipse. Is open to a discussion of what a suitable OSI-approved license might be.

Jim: I was thinking more of a license we might offer.

SteveH: inventing yet another license is not a good idea. Wouldn't send the right message to the open-source community.

Jim: we indemnify our downstream recipients.

MikeM: the ability to indemnify will have more to do with the licenses than with the foundation's processes.

MikeM: the constraints are difficult but if your solution is that all Java development must take place at OpenJDK and under the OCA then you will kill Java.

SteveH: Oracle incorporates open-source-licensed code into their products all the time and they indemnify their customers. It's just a matter of managing the risk.

Jim: more questions for me?

SteveH: The EC will be approving all JSRs. That's a way to check that the IPR regime and licensing terms are appropriate. Oracle could devise a form for the Spec Lead to fill out (where will you host the project, how will you manage IP, etc.?) This will help the EC to decide whether or not to approve the JSR.

Jim: hmmm... not sure we should be evaluating foundation processes on the fly when a JSR is submitted rather than defining processes in advance. Don't want to have to argue each time about whether or not a particular foundation is acceptable.

MikeM: publish requirements in advance. There are several big conservative companies on the EC who will want to apply the same standards as Oracle does. It won't be all on Oracle to make the decisions.