# JSR 358 IP Working Group Meeting Minutes  
for June 6 2013

## Date

Thursday 6 June 2013, 1:00-2:00 pm PDT

## Location

Teleconference

## Agenda

*   Review [minutes of last meeting](https://java.net/downloads/jsr358/Meeting%20Materials/JSR-358-IPWG-Minutes-May-30-2013.md)
*   [Hub-and-spoke](http://jcp.org/aboutJava/communityprocess/ec-public/materials/2012-10-16/Hub-and-Spoke-Alternative.pdf)
*   Next steps

## Attendees

*   Patrick Curran
*   Don Deutsch
*   Scott Jameson
*   Mike DeNicola
*   Werner Keil
*   Anish Karmarkar
*   Steve Harris
*   Scott Stark

## Minutes

Reviewed minutes. Patrick pointed out (as Gil had done) that for each of the three artifacts (Spec, RI, and TCK) we must consider how IP flows in as well as how it is licensed out.

Similar language to what we discussed for the outbound license needs to be incorporated into the JSPA: I grant my IP to implementors, distributors, and users (the Spec Lead is just an implementor.)

Anish: the Spec Lead - as an aggregator - is a Spoke - this is not a flat IP flow.

Scott: the rights flow through the Spec Lead.

Patrick: we need an IPR that specifies the terms under which IP is **contributed** and the terms under which it will be **distributed** (licensed)

SteveH: agrees - contributors must grant rights and the artifact(s) produced must be licensed to others.

Now consider RI and TCK. Each will have inbound IP grants and outbound licenses. We have specified open-source licenses for outbound but we also need to define the characteristics of the commercial RI and TCK licenses.

First, consider inbound.

The JSPA IP language must grant the right to implement (in the form of the RI) and also the right to incorporate IP as necessary into the TCK.

What about those who do not sign the JSPA? Two cases:

*   Casual contributions of "ideas" through collaborative software (mailing list, bug-tracking system, Wiki, whatever)

*   Should be covered by standard Terms of Use

*   More formal contributions to the RI-development project

*   Are the IPR policies of, eg, Eclipse and Apache sufficient to make the necessary IP grants or do we need a supplemental Contributor Agreement
*   Don Deutsch: different standards bodies very often have IPR policies that are not completely compatible with each other. Collaboration may require negotiating a Memorandum of Understanding, but direct incorporation of the output of one body into the work of another may not need such an agreement.
*   Scott: agrees that in the latter case this may not be necessary, particularly when FOSS projects are concerned.

Patrick: are we ready to request drafts of the commercial RI and TCK licenses? Is the hub-and-spoke v. flat question relevant?

ScottJ: it depends on whether the Spec Lead is the entity making the grants or whether the necessary rights have flowed directly from the contributors.

Patrick: how is this different from any commercial implementation of a JSR? The implementor (Spec Lead or otherwise) is the entity who grants the license.

SteveH: present the lawyers with the use-case example. Participants made "flat grants" of IP, RI may incorporate artifacts developed collaboratively through eg, Apache or Eclipse, take these into consideration.

Patrick: it's not just a matter of Oracle's commercial RI license(s). We all create commercial implementations of Java technologies.

ScottS: yes, but we are talking about approving a particular commercial license.

Patrick: are we ready to draft a Term Sheet?

Yes - approve the overall shape of it at next Tuesday's EC meeting.