# JSR 358 IP Working Group Meeting Minutes  
for January 25 2013

### Meeting details

*   Date & Time
    *   January 25, 2013\. 1:00-2:00 pm PST

*   Location
    *   Teleconference

### Agenda

*   Review [meeting minutes](/files/Meeting%20Materials/JSR-358-EG-Minutes-Jan-16-2013.md) from f2f session
*   Follow up and next steps

## Attendees

*   Patrick Curran
*   Scott Jameson
*   Mike Milinkovich
*   Scott Stark
*   Anil Kumar
*   Steve Harris
*   Steve Wolfe
*   Werner Keil

## Minutes

We reviewed the minutes of the last meeting.

Steve Harris restated a position he has recently outlined in email and asked how we could reach closure on this:

> My position is that the umbrella specs, Oracle being the lead by definition, are different and should be treated as an exceptional case. FWIW, I still would rather see the simple list of open source licenses and an official JCP statement that this is what is requires for all NEW JSRs for both TCK and RI. For the umbrella specs, we can deal with it separately. For new specs that Oracle wants to include in an umbrella spec, Oracle can simply choose to include RI and TCK under these open source terms, or not include the JSR in the umbrella. For NEW JSRs Oracle would do, the standalone TCK should be one of the three open source licenses.

SteveH: In summary, can't we just omit the commercial license option from the list of "permissible licenses?"

MikeM: are you OK with GPL+classpath with commercial licensing on the backend or do you want to ban all commercial licensing from the Java ecosystem?

Steve: we would not be forcing Oracle to do anything, but would be putting a stake in the ground that over time if things are going to show up in the umbrella spec then it would be under one of the three licenses.

Mike: if we say all RIs and TCKs must be under one of these three licenses and stop there, nothing would prevent Oracle from commercially licensing IP for which it has OCAs in place.

Steve: we should agree as an org that things should be simple. Don and Patrick should ask the Oracle lawyers whether they can live with this.

Patrick: how is this different from what we have today?

Clarification: TCKs must be made available under one of the three open-source licenses.

Scott: the devil is in the details. People may think that everything is available under open-source if the JSPA doesn't call this out explicitly. When Oracle charges money they will be "surprised."

SteveH: Permit the Spec Lead to add any kind of contributor agreement. Write this in to the JSPA.

Patrick: Oracle's insistance that they have the right to include a FOU clause in TCK license contradicts the proposal for standardized TCK licenses.

SteveH: TCKs for umbrella specs are different.

Patrick: The terms _Umbrella Spec_ and _Platform Spec_ are not typically used in Java ME.

ScottJ: Anybody should be able to create an "aggregation."

SteveH: the Process Document explicitly states that Oracle is the Spec Lead for Platform Specs.

SteveH: Don't worry too much about Java ME. Also, Platform Specs are becoming less important over time.

Patrick: Doesn't the commitment to compatibility requirements complicate things?

Response: Not necessarily - that language belongs in the Spec license. Right to use the TCK doesn't necessarily confer right to certify as compatible (other conditions may need to be met.)

#### Next Steps

*   Steve Harris will draft proposal on standardized licensing for discussion. After we have discussed this, Patrick and Don will take it to Oracle Legal for comment.
*   As recorded in the minutes of the last meeting Steve Wolfe, Scott Jameson, and Mike Milinkovich will get together to develop a more specific proposal on essential patents (factoring in the conditions under which grants might be terminated.)
*   As recorded in the minutes of the last meeting Bruno Souza will develop a discussion document on individual membership.
*   If necessary, at next week's Working Group meeting we will review the high-level list of issues (in presentation and/or Issue Tracker form) to see if there's another topic that we should pursue in addition to these.