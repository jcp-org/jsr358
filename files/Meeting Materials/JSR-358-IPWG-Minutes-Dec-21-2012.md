# JSR 358 IP Working Group Meeting Minutes  
for December 21 2012

## **Date**

*   December 21, 2012

## Location

*   Teleconference

## **Agenda**

*   [Hub-and-spoke IP grants](http://jcp.org/aboutJava/communityprocess/ec-public/materials/2012-10-16/Hub-and-Spoke-Alternative.pdf)
*   [Essential Patent alternatives and standard licenses](http://jcp.org/aboutJava/communityprocess/ec-public/materials/2012-11-20/Patent-Altenatives-and-Standard-Licenses.pdf)
*   Next steps

## Attendees

*   Patrick Curran
*   Scott Jameson
*   Mike Milinkovich
*   Anish Karmarkar
*   Steve Harris
*   Scott Stark

## Minutes

We reviewed the minutes of the last meeting.

Anish introduced the early draft of the document that he volunteered to create in order to summarize IBM's presentation. He explained that he modelled the structure on similar work that he did in OSGI. The hope is that this will evolve into a Term Sheet.

He noted that Patrick had suggested a summary table and possibly also a flow-diagram.

Anish: each section of the doc deals with a type of output, and for each section there are subsections that specify for different "roles" what rights they have and from whom they acquire them. (Patrick suggested listing all roles, even if the content is "same as x"

MikeM asked for explanation of reciprocity in section 2.1.1.2 part 2 - Anish explained: if an implementer sues, then they lose their rights with respect to this JSR.

Patrick: use "tokens" as short-hand for complex notions such as reciprocity (or withdrawal)

Steve: we are addressing two audiences: input into legal process (a Term Sheet) and also "non-lawyers." At some point we should provide an English translation of our work.

Section 2.1.2

Anish: the Spec Lead is "special" when it comes to RI and TCK...

FRAND licensing of RI & TCK complicates things. MikeM: would be simpler if we eliminated this possibility. Patrick: good luck with that.

Scott: make it clear that in this section we're talking about "non-Essential" patent grants.

Scott: aren't we making this very complicated - we effectively have a dual-license model?

Anish: if all contributions to RI and TCK are Apache-licensed then Spec Lead could re-license in any way

Mike - start with requirements before we choose "standard licenses" Eg: BSD doesn't cover patents, so we could use that for copyright and leave the patent regime to the JCP

Anish: can't we just have exactly the same language for contributions to Spec, RI, and TCK?

ScottJ: they are different.. don't consider RI and TCK as the same.

Patrick: rather than talking about "flattening" we should be trying to reduce to a minimum the number of different types of input, transformations, and outputs. "Flattening" is just one way to do this (remove the "intermediaries.") Another is to restructure/rewrite so that those who play different roles have the same obligations and accrue the same rights...

**Next steps**

Move on to the discussion of Standardized (outbound) licensing. This may help us to address the RI/TCK and Copyright issues.