# JSR 358 Expert Group Meeting Minutes  
for May 30 2013

## Date

Thursday 30 May 2013, 1:00-2:00 pm PDT

## Location

Teleconference

## Agenda

*   Review [Task List](http://www2.jcp.org/aboutJava/communityprocess/ec-private/materials/2013-05-1415/JSR358-TaskList.md)
*   [Hub-and-spoke](http://jcp.org/aboutJava/communityprocess/ec-public/materials/2012-10-16/Hub-and-Spoke-Alternative.pdf)
*   Next steps

## Attendees

*   Patrick Curran
*   Steve Harris
*   Steve Wolfe
*   Mike DeNicola
*   Scott Stark
*   Heather VanCura
*   Mike Milinkovich
*   Gil Tene
*   Werner Keil
*   Steve Winkler
*   Don Deutsch

## Minutes

Steve Wolfe: hub and spoke model is a carry-over from a prior era. Characteristics: agreements are 1-on-1 between members and Oracle. IP flows through the Spec Lead.

Patrick: agreements will still be between members and Oracle - can we still address concerns by modifying the language in the agreement?

Steve: yes.

Current practice: contributors retain ownership - they license to the Spec Lead.

Distinguish between Spec and RI/TCK.

Patrick asks Steve Wolfe: would a flat spec license grant rights to implementors, distributors, and users? Steve: yes

Patrick: would such a flat grant be sufficient for Oracle to meet its TLDA obligations (and/or in its role as spec lead for the platforms)? Preferable to refer - if we need to - to Umbrella JSRs rather than "Oracle".

Steve: not sure - is open to supplemental language.

Patrick: do we agree with this goal: a flat license that grants rights to implementors, distributors, and users and that doesn't contain special language for Oracle?

Yes

Gil: make sure that rights necessary to modify/evolve JSRs are granted.

Patrick: now let's talk about the RI. Does the Spec License grant necessary rights to implement (independently of any actual contribution of code) the Spec in the form of an RI?

We agree: the Spec license must grant all necessary rights for compatible Independent Implementations (whether or not this is the RI)

Can we also agree that the Spec License will also grant any rights necessary to implement the (one and only) TCK (if - as some lawyers have argued - the TCK incorporates IP from the spec)?

SteveH: this would require specific reference to the Spec Lead.

Gil: language could permit anyone to "create compatibility tests"

Patrick: we may have to dilute the "purity" of the flatness of the grant in the Spec License.

Gil: this covers outbound IP flow, but what about inbound? In order to deal with the assertion that contributions to the RI or TCK may also flow into the Spec, we could require all contributors to RI and TCK to also explicitly grant the rights necessary to flow into the Spec.

Patrick: Signing the JSPA will grant the rights to flow into the Spec. What about those who do not sign the JSPA?

MikeM: we discussed this in Zurich. There's no need for a Contributor Agreeement.

Patrick: I know this is your position. Let's not open this up again at the moment.

Patrick: does the "hub and spoke" question bear on the Commercial RI license?

Response: The draft must take into consideration the licenses under which components are licensed.