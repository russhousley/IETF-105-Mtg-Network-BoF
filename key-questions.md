# IETF-105-Mtg-Network-BoF
Ideas for a BoF at IETF 105 on IETF meeting network requirements

Name: IETF Meeting Network Requirements

Description: The IETF meeting network costs are significant. This BoF will discuss the network requirements to makes sure that money is not being spent to provide capabilities that few attendees care about.

Status: NOT WG Forming 

Responsible AD: Alissa Cooper 

BoF proponents: Jason Livingood <Jason_Livingood@comcast.com>, Russ Housley <housley@vigilsec.com>

BoF chairs: Russ Housley <housley@vigilsec.com> 

Number of people expected to attend: 75

Length of session (1, 1.5, 2, or 2.5 hours): 2 hours 

Conflicts to avoid (whole Areas and/or WGs): lamps suit quic perc saag sidrops sipbrandy mls tls ipwave stir acme secdispatch teep cfrg dprive

Agenda

- Talk about the existing requirements used by the NOC to build the IETF meeting network
- Ask questions to confirm that the network requirements align with the needs of the attendees
  - Are there things that we are providing that few people care about?
  - Are there things that are not being provided that many people care about?
  - Are there things that would make experiments easier to conduct without impacting the ability of other people to do their work?

Background:

All IETF participants want a perfect network that is always available with unlimited bandwidth in every possible location, even while others are conducting many experiments with buggy implementations, or even purposely broken implementations.  The real requirements seem to include:

- A highly-reliable network that allows people to get their work done.
- It needs to be "real Internet", supporting both IPv4 and IPv6, and no filtering.
- Provide a terminal room and/or lounge where people can colaborate and have excellent connectivity.
- A network that works well throughout the meeting venue. It is nice to have access to the network in the main hotel and overflow hotels too, especially when the main hotel is not big enough to accomodate most of the IETF participants.  Priotiy:
  - Meeting rooms, common areas, plenary room, Secretariat office, NomCom office, and so on.
  - Main hotel common areas and guest rooms.
  - Overflow hotel common areas and guest rooms.
- A network that permits various kinds of experiments:
  - on alternative SSIDs;
  - provide places where some protocols can run and places where not; and
  - measurements of the experiments can be done.
- It is nice to have insight into attacks that take place on the meeting network, and then share this information with the whole community.

The requirement have been fairly stable for 10 years.  See https://www.ietf.org/how/meetings/admin/meeting-network-requirements/.

In 2018, the IETF meeting network cost about $360,000 per meeting.  See "NOC Support" line in the budget at https://www.ietf.org/documents/246/IETF_2019_Budget_Public_2018-12-19.pdf.

Key questions about the meeting network that this BoF should explore:

1. Can we simplify, evolve, or eliminate any network requirements? 
2. Should the network offer private IPv4 addresses?
3. Are there any network functions that could be delivered virtually rather than physically on-site?
4. Are there new requirements to support the hackathon or other new technical initiatives?
5. How much redundency do we need?
6. Can we prioritize key network requirements/functions into MUST and SHOULD and MAY?
7. Do any NOC functions change based on the evolution of the network requirements?

Key questions about the hotel network that this BoF should explore:

1. Do we need to manage connectivity for guest rooms?
2. Does ietf-hotel really work better than the hotel-provided network?
3. Could we live with NAT in the rooms? Could we live without IPv6 in the rooms?

Mailing List: https://www.ietf.org/mailman/listinfo/ietf

Draft charter: N/A
