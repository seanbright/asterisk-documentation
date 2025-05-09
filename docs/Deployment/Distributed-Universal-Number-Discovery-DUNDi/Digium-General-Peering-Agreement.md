---
title: Digium General Peering Agreement
pageid: 4259957
---

```

 DIGIUM GENERAL PEERING AGREEMENT (TM)
 Version 1.0.0, September 2004
 Copyright (C) 2004 Digium, Inc.
 445 Jan Davis Drive, Huntsville, AL 35806 USA

 Everyone is permitted to copy and distribute complete verbatim copies
 of this General Peering Agreement provided it is not modified in any
 manner.

 ------------------------------------------------------

 DIGIUM GENERAL PEERING AGREEMENT

 PREAMBLE

 For most of the history of telecommunications, the power of being able
to locate and communicate with another person in a system, be it across
a hall or around the world, has always centered around a centralized
authority -- from a local PBX administrator to regional and national
RBOCs, generally requiring fees, taxes or regulation. By contrast,
DUNDi is a technology developed to provide users the freedom to
communicate with each other without the necessity of any centralized
authority. This General Peering Agreement ("GPA") is used by individual
parties (each, a "Participant") to allow them to build the E164 trust
group for the DUNDi protocol.

 To protect the usefulness of the E164 trust group for those who use
it, while keeping the system wholly decentralized, it is necessary to
replace many of the responsibilities generally afforded to a company or
government agency, with a set of responsibilities implemented by the
parties who use the system, themselves. It is the goal of this document
to provide all the protections necessary to keep the DUNDi E164 trust
group useful and reliable.

 The Participants wish to protect competition, promote innovation and
value added services and make this service valuable both commercially
and non-commercially. To that end, this GPA provides special terms and
conditions outlining some permissible and non-permissible revenue
sources.

 This GPA is independent of any software license or other license
agreement for a program or technology employing the DUNDi protocol. For
example, the implementation of DUNDi used by Asterisk is covered under a
separate license. Each Participant is responsible for compliance with
any licenses or other agreements governing use of such program or
technology that they use to peer.

 You do not have to execute this GPA to use a program or technology
employing the DUNDi protocol, however if you do not execute this GPA,
you will not be able to peer using DUNDi and the E164 context with
anyone who is a member of the trust group by virtue of their having
executed this GPA with another member.

The parties to this GPA agree as follows:

 0. DEFINITIONS. As used herein, certain terms shall be defined as
follows:

 (a) The term "DUNDi" means the DUNDi protocol as published by
 Digium, Inc. or its successor in interest with respect to the
 DUNDi protocol specification.

 (b) The terms "E.164" and "E164" mean ITU-T specification E.164 as
 published by the International Telecommunications Union (ITU) in
 May, 1997.

 (c) The term "Service" refers to any communication facility (e.g.,
 telephone, fax, modem, etc.), identified by an E.164-compatible
 number, and assigned by the appropriate authority in that
 jurisdiction.

 (d) The term "Egress Gateway" refers an Internet facility that
 provides a communications path to a Service or Services that may
 not be directly addressable via the Internet.

 (e) The term "Route" refers to an Internet address, policies, and
 other characteristics defined by the DUNDi protocol and
 associated with the Service, or the Egress Gateway which
 provides access to the specified Service.

 (f) The term "Propagate" means to accept or transmit Service and/or
 Egress Gateway Routes only using the DUNDi protocol and the
 DUNDi context "e164" without regard to case, and does not apply
 to the exchange of information using any other protocol or
 context.

 (g) The term "Peering System" means the network of systems that
 Propagate Routes.

 (h) The term "Subscriber" means the owner of, or someone who
 contracts to receive, the services identified by an E.164
 number.

 (i) The term "Authorizing Individual" means the Subscriber to a
 number who has authorized a Participant to provide Routes
 regarding their services via this Peering System.

 (j) The term "Route Authority" refers to a Participant that provides
 an original source of said Route within the Peering System.
 Routes are propagated from the Route Authorities through the
 Peering System and may be cached at intermediate points. There
 may be multiple Route Authorities for any Service.

 (k) The term "Participant" (introduced above) refers to any member
 of the Peering System.

 (l) The term "Service Provider" refers to the carrier (e.g.,
 exchange carrier, Internet Telephony Service Provider, or other
 reseller) that provides communication facilities for a
 particular Service to a Subscriber, Customer or other End User.

 (m) The term "Weight" refers to a numeric quality assigned to a
 Route as per the DUNDi protocol specification. The current
 Weight definitions are shown in Exhibit A.

 1. PEERING. The undersigned Participants agree to Propagate Routes
with each other and any other member of the Peering System and further
agree not to Propagate DUNDi Routes with a third party unless they have
first have executed this GPA (in its unmodified form) with such third
party. The Participants further agree only to Propagate Routes with
Participants whom they reasonably believe to be honoring the terms of
the GPA. Participants may not insert, remove, amend, or otherwise
modify any of the terms of the GPA.

 2. ACCEPTABLE USE POLICY. The DUNDi protocol contains information
that reflect a Subscriber's or Egress Gateway's decisions to receive
calls. In addition to the terms and conditions set forth in this GPA,
the Participants agree to honor the intent of restrictions encoded in
the DUNDi protocol. To that end, Participants agree to the following:

 (a) A Participant may not utilize or permit the utilization of
 Routes for which the Subscriber or Egress Gateway provider has
 indicated that they do not wish to receive "Unsolicited Calls"
 for the purpose of making an unsolicited phone call on behalf of
 any party or organization.

 (b) A Participant may not utilize or permit the utilization of
 Routes which have indicated that they do not wish to receive
 "Unsolicited Commercial Calls" for the purpose of making an
 unsolicited phone call on behalf of a commercial organization.

 (c) A Participant may never utilize or permit the utilization of any
 DUNDi route for the purpose of making harassing phone calls.

 (d) A Party may not utilize or permit the utilization of DUNDi
 provided Routes for any systematic or random calling of numbers
 (e.g., for the purpose of locating facsimile, modem services, or
 systematic telemarketing).

 (e) Initial control signaling for all communication sessions that
 utilize Routes obtained from the Peering System must be sent
 from a member of the Peering System to the Service or Egress
 Gateway identified in the selected Route. For example, 'SIP
 INVITES' and IAX2 "NEW" commands must be sent from the
 requesting DUNDi node to the terminating Service.

 (f) A Participant may not disclose any specific Route, Service or
 Participant contact information obtained from the Peering System
 to any party outside of the Peering System except as a
 by-product of facilitating communication in accordance with
 section 2e (e.g., phone books or other databases may not be
 published, but the Internet addresses of the Egress Gateway or
 Service does not need to be obfuscated.)

 (g) The DUNDi Protocol requires that each Participant include valid
 contact information about itself (including information about
 nodes connected to each Participant). Participants may use or
 disclose the contact information only to ensure enforcement of
 legal furtherance of this Agreement.

 3. ROUTES. The Participants shall only propagate valid Routes, as
defined herein, through the Peering System, regardless of the original
source. The Participants may only provide Routes as set forth below,
and then only if such Participant has no good faith reason to believe
such Route to be invalid or unauthorized.

 (a) A Participant may provide Routes if each Route has as its
 original source another member of the Peering System who has
 duly executed the GPA and such Routes are provided in accordance
 with this Agreement; provided that the Routes are not modified
 (e.g., with regards to existence, destination, technology or
 Weight); or

 (b) A Participant may provide Routes for Services with any Weight
 for which it is the Subscriber; or

 (c) A Participant may provide Routes for those Services whose
 Subscriber has authorized the Participant to do so, provided
 that the Participant is able to confirm that the Authorizing
 Individual is the Subscriber through:

 i. a written statement of ownership from the Authorizing
 Individual, which the Participant believes in good faith
 to be accurate (e.g., a phone bill with the name of the
 Authorizing Individual and the number in question); or

 ii. the Participant's own direct personal knowledge that the
 Authorizing Individual is the Subscriber.

 (d) A Participant may provide Routes for Services, with Weight in
 accordance with the Current DUNDi Specification, if it can in
 good faith provide an Egress Gateway to that Service on the
 traditional telephone network without cost to the calling party.

 4. REVOCATION. A Participant must provide a free, easily accessible
mechanism by which a Subscriber may revoke permission to act as a Route
Authority for his Service. A Participant must stop acting as a Route
Authority for that Service within 7 days after:

 (a) receipt of a revocation request;

 (b) receiving other notice that the Service is no longer valid; or

 (c) determination that the Subscriber's information is no longer
 accurate (including that the Subscriber is no longer the service
 owner or the service owner's authorized delegate).

 5. SERVICE FEES. A Participant may charge a fee to act as a Route
Authority for a Service, with any Weight, provided that no Participant
may charge a fee to propagate the Route received through the Peering
System.

 6. TOLL SERVICES. No Participant may provide Routes for any Services
that require payment from the calling party or their customer for
communication with the Service. Nothing in this section shall prohibit
a Participant from providing routes for Services where the calling party
may later enter into a financial transaction with the called party
(e.g., a Participant may provide Routes for calling cards services).

 7. QUALITY. A Participant may not intentionally impair communication
using a Route provided to the Peering System (e.g. by adding delay,
advertisements, reduced quality). If for any reason a Participant is
unable to deliver a call via a Route provided to the Peering System,
that Participant shall return out-of-band Network Congestion
notification (e.g. "503 Service Unavailable" with SIP protocol or
"CONGESTION" with IAX protocol).

 8. PROTOCOL COMPLIANCE. Participants agree to Propagate Routes in
strict compliance with current DUNDi protocol specifications.

 9. ADMINISTRATIVE FEES. A Participant may charge (but is not required
to charge) another Participant a reasonable fee to cover administrative
expenses incurred in the execution of this Agreement. A Participant may
not charge any fee to continue the relationship or to provide Routes to
another Participant in the Peering System.

 10. CALLER IDENTIFICATION. A Participant will make a good faith effort
to ensure the accuracy and appropriate nature of any caller
identification that it transmits via any Route obtained from the Peering
System. Caller identification shall at least be provided as a valid
E.164 number.

 11. COMPLIANCE WITH LAWS. The Participants are solely responsible for
determining to what extent, if any, the obligations set forth in this
GPA conflict with any laws or regulations their region. A Participant
may not provide any service or otherwise use DUNDi under this GPA if
doing so is prohibited by law or regulation, or if any law or regulation
imposes requirements on the Participant that are inconsistent with the
terms of this GPA or the Acceptable Use Policy.

 12. WARRANTY. EACH PARTICIPANT WARRANTS TO THE OTHER PARTICIPANTS THAT
IT MADE, AND WILL CONTINUE TO MAKE, A GOOD FAITH EFFORT TO AUTHENTICATE
OTHERS IN THE PEERING SYSTEM AND TO PROVIDE ACCURATE INFORMATION IN
ACCORDANCE WITH THE TERMS OF THIS GPA. THIS WARRANTY IS MADE BETWEEN
THE PARTICIPANTS, AND THE PARTICIPANTS MAY NOT EXTEND THIS WARRANTY TO
ANY NON-PARTICIPANT INCLUDING END-USERS.

 13. DISCLAIMER OF WARRANTIES. THE PARTICIPANTS UNDERSTAND AND AGREE
THAT ANY SERVICE PROVIDED AS A RESULT OF THIS GPA IS "AS IS." EXCEPT FOR
THOSE WARRANTIES OTHERWISE EXPRESSLY SET FORTH HEREIN, THE PARTICIPANTS
DISCLAIM ANY REPRESENTATIONS OR WARRANTIES OF ANY KIND OR NATURE,
EXPRESS OR IMPLIED, AS TO THE CONDITION, VALUE OR QUALITIES OF THE
SERVICES PROVIDED HEREUNDER, AND SPECIFICALLY DISCLAIM ANY
REPRESENTATION OR WARRANTY OF MERCHANTABILITY, SUITABILITY OR FITNESS
FOR A PARTICULAR PURPOSE OR AS TO THE CONDITION OR WORKMANSHIP THEREOF,
OR THE ABSENCE OF ANY DEFECTS THEREIN, WHETHER LATENT OR PATENT,
INCLUDING ANY WARRANTIES ARISING FROM A COURSE OF DEALING, USAGE OR
TRADE PRACTICE. EXCEPT AS EXPRESSLY PROVIDED HEREIN, THE PARTICIPANTS
EXPRESSLY DISCLAIM ANY REPRESENTATIONS OR WARRANTIES THAT THE PEERING
SERVICE WILL BE CONTINUOUS, UNINTERRUPTED OR ERROR-FREE, THAT ANY DATA
SHARED OR OTHERWISE MADE AVAILABLE WILL BE ACCURATE OR COMPLETE OR
OTHERWISE COMPLETELY SECURE FROM UNAUTHORIZED ACCESS.

 14. LIMITATION OF LIABILITIES. NO PARTICIPANT SHALL BE LIABLE TO ANY
OTHER PARTICIPANT FOR INCIDENTAL, INDIRECT, CONSEQUENTIAL, SPECIAL,
PUNITIVE OR EXEMPLARY DAMAGES OF ANY KIND (INCLUDING LOST REVENUES OR
PROFITS, LOSS OF BUSINESS OR LOSS OF DATA) IN ANY WAY RELATED TO THIS
GPA, WHETHER IN CONTRACT OR IN TORT, REGARDLESS OF WHETHER SUCH
PARTICIPANT WAS ADVISED OF THE POSSIBILITY THEREOF.

 15. END-USER AGREEMENTS. The Participants may independently enter
into agreements with end-users to provide certain services (e.g., fees
to a Subscriber to originate Routes for that Service). To the extent
that provision of these services employs the Peering System, the Parties
will include in their agreements with their end-users terms and
conditions consistent with the terms of this GPA with respect to the
exclusion of warranties, limitation of liability and Acceptable Use
Policy. In no event may a Participant extend the warranty described in
Section 12 in this GPA to any end-users.

 16. INDEMNIFICATION. Each Participant agrees to defend, indemnify and
hold harmless the other Participant or third-party beneficiaries to this
GPA (including their affiliates, successors, assigns, agents and
representatives and their respective officers, directors and employees)
from and against any and all actions, suits, proceedings,
investigations, demands, claims, judgments, liabilities, obligations,
liens, losses, damages, expenses (including, without limitation,
attorneys' fees) and any other fees arising out of or relating to (i)
personal injury or property damage caused by that Participant, its
employees, agents, servants, or other representatives; (ii) any act or
omission by the Participant, its employees, agents, servants or other
representatives, including, but not limited to, unauthorized
representations or warranties made by the Participant; or (iii) any
breach by the Participant of any of the terms or conditions of this GPA.

 17. THIRD PARTY BENEFICIARIES. This GPA is intended to benefit those
Participants who have executed the GPA and who are in the Peering
System. It is the intent of the Parties to this GPA to give to those
Participants who are in the Peering System standing to bring any
necessary legal action to enforce the terms of this GPA.

 18. TERMINATION. Any Participant may terminate this GPA at any time,
with or without cause. A Participant that terminates must immediately
cease to Propagate.

 19. CHOICE OF LAW. This GPA and the rights and duties of the Parties
hereto shall be construed and determined in accordance with the internal
laws of the State of New York, United States of America, without regard
to its conflict of laws principles and without application of the United
Nations Convention on Contracts for the International Sale of Goods.

 20. DISPUTE RESOLUTION. Unless otherwise agreed in writing, the
exclusive procedure for handling disputes shall be as set forth herein.
Notwithstanding such procedures, any Participant may, at any time, seek
injunctive relief in addition to the process described below.

 (a) Prior to mediation or arbitration the disputing Participants
 shall seek informal resolution of disputes. The process shall be
 initiated with written notice of one Participant to the other
 describing the dispute with reasonable particularity followed
 with a written response within ten (10) days of receipt of
 notice. Each Participant shall promptly designate an executive
 with requisite authority to resolve the dispute. The informal
 procedure shall commence within ten (10) days of the date of
 response. All reasonable requests for non-privileged information
 reasonably related to the dispute shall be honored. If the
 dispute is not resolved within thirty (30) days of commencement
 of the procedure either Participant may proceed to mediation or
 arbitration pursuant to the rules set forth in (b) or (c) below.

 (b) If the dispute has not been resolved pursuant to (a) above or,
 if the disputing Participants fail to commence informal dispute
 resolution pursuant to (a) above, either Participant may, in
 writing and within twenty (20) days of the response date noted
 in (a) above, ask the other Participant to participate in a one
 (1) day mediation with an impartial mediator, and the other
 Participant shall do so. Each Participant will bear its own
 expenses and an equal share of the fees of the mediator. If the
 mediation is not successful the Participants may proceed with
 arbitration pursuant to (c) below.

 (c) If the dispute has not been resolved pursuant to (a) or (b)
 above, the dispute shall be promptly referred, no later than one
 (1) year from the date of original notice and subject to
 applicable statute of limitations, to binding arbitration in
 accordance with the UNCITRAL Arbitration Rules in effect on the
 date of this contract. The appointing authority shall be the
 International Centre for Dispute Resolution. The case shall be
 administered by the International Centre for Dispute Resolution
 under its Procedures for Cases under the UNCITRAL Arbitration
 Rules. Each Participant shall bear its own expenses and shall
 share equally in fees of the arbitrator. All arbitrators shall
 have substantial experience in information technology and/or in
 the telecommunications business and shall be selected by the
 disputing participants in accordance with UNCITRAL Arbitration
 Rules. If any arbitrator, once selected is unable or unwilling
 to continue for any reason, replacement shall be filled via the
 process described above and a re-hearing shall be conducted. The
 disputing Participants will provide each other with all
 requested documents and records reasonably related to the
 dispute in a manner that will minimize the expense and
 inconvenience of both parties. Discovery will not include
 depositions or interrogatories except as the arbitrators
 expressly allow upon a showing of need. If disputes arise
 concerning discovery requests, the arbitrators shall have sole
 and complete discretion to resolve the disputes. The parties and
 arbitrator shall be guided in resolving discovery disputes by
 the Federal Rules of Civil Procedure. The Participants agree
 that time of the essence principles shall guide the hearing and
 that the arbitrator shall have the right and authority to issue
 monetary sanctions in the event of unreasonable delay. The
 arbitrator shall deliver a written opinion setting forth
 findings of fact and the rationale for the award within thirty
 (30) days following conclusion of the hearing. The award of the
 arbitrator, which may include legal and equitable relief, but
 which may not include punitive damages, will be final and
 binding upon the disputing Participants, and judgment may be
 entered upon it in accordance with applicable law in any court
 having jurisdiction thereof. In addition to award the
 arbitrator shall have the discretion to award the prevailing
 Participant all or part of its attorneys' fees and costs,
 including fees associated with arbitrator, if the arbitrator
 determines that the positions taken by the other Participant on
 material issues of the dispute were without substantial
 foundation. Any conflict between the UNCITRAL Arbitration Rules
 and the provisions of this GPA shall be controlled by this GPA.

 21. INTEGRATED AGREEMENT. This GPA, constitutes the complete
integrated agreement between the parties concerning the subject matter
hereof. All prior and contemporaneous agreements, understandings,
negotiations or representations, whether oral or in writing, relating to
the subject matter of this GPA are superseded and canceled in their
entirety.

 22. WAIVER. No waiver of any of the provisions of this GPA shall be
deemed or shall constitute a waiver of any other provision of this GPA,
whether or not similar, nor shall such waiver constitute a continuing
waiver unless otherwise expressly so provided in writing. The failure
of either party to enforce at any time any of the provisions of this
GPA, or the failure to require at any time performance by either party
of any of the provisions of this GPA, shall in no way be construed to be
a present or future waiver of such provisions, nor in any way affect the
ability of a Participant to enforce each and every such provision
thereafter.

 23. INDEPENDENT CONTRACTORS. Nothing in this GPA shall make the
Parties partners, joint venturers, or otherwise associated in or with
the business of the other. Parties are, and shall always remain,
independent contractors. No Participant shall be liable for any debts,
accounts, obligations, or other liabilities of the other Participant,
its agents or employees. No party is authorized to incur debts or other
obligations of any kind on the part of or as agent for the other. This
GPA is not a franchise agreement and does not create a franchise
relationship between the parties, and if any provision of this GPA is
deemed to create a franchise between the parties, then this GPA shall
automatically terminate.

 24. CAPTIONS AND HEADINGS. The captions and headings used in this GPA
are used for convenience only and are not to be given any legal effect.

 25. EXECUTION. This GPA may be executed in counterparts, each of which
so executed will be deemed to be an original and such counterparts
together will constitute one and the same Agreement. The Parties shall
transmit to each other a signed copy of the GPA by any means that
faithfully reproduces the GPA along with the Signature. For purposes of
this GPA, the term "signature" shall include digital signatures as
defined by the jurisdiction of the Participant signing the GPA.

 Exhibit A

Weight Range Requirements

0-99 May only be used under authorization of Owner

100-199 May only be used by the Owner's service
 provider, regardless of authorization.

200-299 Reserved -- do not use for e164 context.

300-399 May only be used by the owner of the code under
 which the Owner's number is a part of.

400-499 May be used by any entity providing access via
 direct connectivity to the Public Switched
 Telephone Network.

500-599 May be used by any entity providing access via
 indirect connectivity to the Public Switched
 Telephone Network (e.g. Via another VoIP
 provider)

600- Reserved-- do not use for e164 context.

 Participant Participant

Company:

Address:

Email:

 _________________________ _________________________
 Authorized Signature Authorized Signature

Name:

END OF GENERAL PEERING AGREEMENT

------------------------------------------------

How to Peer using this GPA If you wish to exchange routing information
with parties using the e164 DUNDi context, all you must do is execute
this GPA with any member of the Peering System and you will become a
member of the Peering System and be able to make Routes available in
accordance with this GPA.

DUNDi, IAX, Asterisk and GPA are trademarks of Digium, Inc.

```
