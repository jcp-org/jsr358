# JSR 358 IP Working Group Meeting Minutes  
for June 13 2013

## Date

Thursday 13 June 2013, 1:00-2:00 pm PDT

## Location

Teleconference

## Agenda

*   Next week's meeting (Patrick cannot make it on Thursday)
*   Review [minutes of last meeting](https://java.net/downloads/jsr358/Meeting%20Materials/JSR-358-IPWG-Minutes-June%206-2013.md)
*   [Spec IP-flow](https://java.net/projects/jsr358/downloads/download/Meeting%20Materials/IP-flow-v1.pdf) (working towards a term-sheet)
*   Next steps

## Attendees

*   Patrick Curran
*   Mike DeNicola
*   Steve Harris
*   Scott Jameson
*   Heather Vancura
*   Anish Karmarkar
*   Anil Kumar
*   Mike Milinkovich
*   Werner Keil
*   Steve Wolfe
*   Steve Winkler

## Minutes

We discussed the IP-flow document. Several members pointed out that if the copyright in the Spec (and RI and TCK) vests in the Spec Lead then this is not "flat." As for the Spec, we eventually agreed that the copyright in the "collected work" (the actual Spec document) can vest in the Spec Lead even though the actual copyright grants for the IP described in the Spec (and incorporated into the RI and TCK) will be defined separately.

SteveH: where there is an established organization with an effective CLA we need to be able to accommodate that (need an approval process.) Our "rules" are for when there isn't...

Patrick: I'm having trouble making the IP-flow "flat". I think the problem is what appears to be a contradiction between having a flat grant of rights from contributors to "consumers" (implementers and users - and possibly also distributors) and having outbound licenses. There must be a licensor for those outbound licenses, and that is the Spec Lead. To be sure, things are considerably "flatter" in the case of Independent Implementations (those not derived from the RI), but even there the Spec License should still apply. (In which case we seem to have two flows of IP: one directly from contributor to consumer and one via the Spec Lead and the Spec License.)

If we consider the Spec Lead as just another contributor then don't they contribute "flat" just like everyone else?

SteveH: If I consume under the Apache license I don't have to go to anybody else (the Spec Lead or anyone else) for permission. I get all the rights I need (to implement, redistribute, etc.)

Patrick: haven't you just cut the Spec License out of the picture?

MikeM: are you just saying that because the Oracle lawyers <cite>insist</cite> that the Spec RI and TCK all require the same IP regime?

MikeM: an independent implementation gets IP rights only if compatible (since they can only flow through the Spec license.)

SteveW: think of changes to an open-sourced RI as equivalent to an independent implementation - if they are incompatible then they won't get the IP rights via the Spec. Their changes are at risk...

Anish: consider copyrights and patents separately. Copyrights flow through the spec lead but patents are granted directly.

Patrick: contributors license copyrights directly to "consumers" The Spec Lead owns the copyright in the collected work.

Anish via IM: In terms of copyrights and spec, the contributors would have to grant "special" rights to the spec lead that they don't grant to the users. From that POV, i don't know what flat-model buys us when it comes to spec copyrights.

Patrick and Anish continued this discussion privately after the meeting. We noted that the Spec Lead must have the right to make derivative works from contributions, but we don't give that right to other implementers. (We certainly don't want to give that right to end-users.) Given this, what is the advantage of a flat model with regard to the spec? It seems that the Spec Lead is in some way(s) special. Isn't it simpler to understand (and wouldn't the Spec License be simpler to write) if everything flowed through the Spec Lead rather than directly from contributors to users?