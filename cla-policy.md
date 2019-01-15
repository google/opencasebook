# Model CLA Policy and Rationale
{:.no_toc}

* Table of Contents
{:toc}

## Introduction

Technology companies frequently receive and use code from outsiders; this
outside code may be important to core products. Outside code can be a tremendous
resource, but it also carries responsibility. This document spells out corporate
best practices for accepting code contributed by third parties and explains the
basis for these practices in agency law. These best practices consist of three
components: an Apache-type Contributor License Agreement (CLA), a procedure for
accepting CLA signatures, and a procedure for accepting code submitted under the
agreement.

This document will summarize the legal framework around code ownership, laying
out the rationale for employing an Apache-type CLA, and then discuss the
specific laws and operational concerns attendant to each part of the CLA signing
and code acceptance process.

## Overview

Under international copyright law, copyright attaches automatically in the
creation of creative works, such as software.[^1] The moment a work of
sufficiently original software is fixed in a tangible medium, it is protected by
copyright. Domestic copyright laws often place copyright ownership in the hands
of a creator's employer.[^2] When a programmer submits code to a company, that
code may be owned by the programmer's employer. To ensure that a company is
granted the permissions necessary to utilize the code it receives, Contributor
License Agreements (CLAs) should generally be obtained from every organization
whose employees contribute code. The language of the Apache CLA, and the best
practices for accepting CLAs, serve two interrelated aims: First, to ensure that
the company is granted permission to use the code. Second, to ensure that the
CLA effectively binds the signee’s organization.

The language of the Apache CLA protects companies by clarifying the ownership
and permissions of intellectual property created and used in the course of the
code contribution relationship.[^3] Section 2 of the agreement grants the
receiving company a "perpetual, worldwide, non-exclusive, no-charge,
royalty-free, irrevocable[^4] copyright license" to the organization's
contributions. The "no-charge, royalty-free" language permits the receiving
company to use the code without incurring expense. The "non-exclusive" language
reserves the organization freedom to use the code itself, or to license the code
to others under different terms. Section 3 spells out patent license terms,
granting the receiving company and downstream users a perpetual license to any
patents implicated by the contributed software. Section 3 also incorporates a
litigation-deterring license-termination mechanism.[^5] Sections 4 and 8 require
the signee to certify that they wield the requisite authority to enter into the
CLA on behalf of their organization. These clauses alert the signee that proper
authority is required to enter into the agreement on behalf of their
organization. It also places the responsibility on the signee to ensure that
such authority is secured.

In addition to the terms of the CLA itself, an effective CLA acceptance
procedure consists of three protective measures to ensure that the CLA binds the
signee's organization. First, authentication, such as email verification through
a document signing service, should be used to verify the identity of the signee.
This provides assurance that the signee is a real person and a representative of
the contracting organization. Second, signees’ professional titles should be
reviewed, and submissions should be rejected if the signee's title is not one
that generally confers authority to contract on behalf of an organization.

For example, a software engineer usually does not have the authority to sign
documents for their company, though they may try. This is done to ensure that
the company’s reliance on the authority of these signees is reasonable.[^6]

Third, all employees of the contributing organization should be individually
appointed to contribute under the agreement by an established point of contact
before making contributions. Funnelling all contributors from a given
organization through a single point of contact prevents contributions from being
made without the contributing organization’s knowledge, and prevents
misunderstanding.

## Discussion

This discussion will first delve into the legal and operational considerations
underpinning the language of the Apache CLA, then lay out best practices for CLA
submission and code contribution acceptance procedures with an eye to the
particular fact patterns that may be relevant for receiving companies.

### CLA

#### Standard inbound license

Using one standard inbound license that grants the receiving company broad
permission to use contributed code in products is beneficial to the company and
downstream users alike.

Technology companies will of course want to make productive use of any code made
available to them. However, if all of the code being received by a company was
subject to various inbound licenses with conflicting terms, the bureaucracy for
authorizing use of any specific third-party code for any specific purpose would
be cumbersome. Whenever contributed code were to be used, the particular license
terms for every single file would need to be reviewed to ascertain whether the
application would be permitted under the terms of that code’s specific
license.[^7] This would require considerable human resources and would slow down
the engineers trying to utilize the code.

The benefits to the company under the standard inbound license pass to
downstream recipients as well. Explicit patent permissions and disclaimers of
obligations and warranties clarify the recipients rights and duties; the broad
grant of rights provides code recipients opportunities to make productive use of
the software; adherence to a single standard license promotes consistency and
common understanding for all participants.

#### Grant of patent license

Section 3 of the Apache CLA operates to clarify that the agreement controls all
aspects of the intellectual property interest in the software. Having patent
license terms clearly and explicitly stated protects all parties’ interests.

#### Origin of works

Sections 5 and 7 require the signee to represent that all contributions under
the agreement are the “original creations” of the contributing organization.
This is done to protect the receiving company (and downstream users), because
the CLA may not shield recipients from claims by owners of code that is
submitted to them by a third party. Requiring CLA signatories to certify that
their code contributions are their original creations - hence copyrighted works
that they actually own - gives recipients some recourse against those
signatories if their contributed code turns out to have been improperly obtained
from a third party.

#### Works made for hire

A benefit of the Corporate CLA is that it protects receiving companies from
termination of transfers. As works made for hire are ineligible for termination
of transfers,[^8] receiving companies are assured that their license to use the
code will not be threatened by termination if the code is contributed through
the engineer’s employer’s CLA, as this establishes that the code is a work made
for hire, which is subsequently properly licensed.

#### Individual CLA

For circumstances where the code being contributed is not done within the scope
of the contributor’s employment,[^9] contributors should be required to sign a
CLA in their individual capacity.

### Procedure

#### Signatures

As discussed in the overview, copyright ownership is a complex animal. Because
copyright ownership is complex, the execution of an agreement that licenses
rights to copyrighted material is a complex matter as well.

For instance, sometimes employees are not aware of the ramifications of
exectuing an agreement on behalf of their employer, which is why having clear
policies in place to account for such situations is essential.

This section will highlight the particular fact patterns that may be relevant to
a company employing a CLA, and then detail the legal framework underpinning the
issue of unauthorized signees.

##### Fraudulent signee

To illustrate what a fraudulent CLA submission might look like, let’s say an
engineer named Alice contacts B Corp to say that she represents A Corp and wants
to sign B Corp’s CLA on A Corp’s behalf. Alice signs the CLA and proceeds with
submitting code to B Corp. B Corp proceeds with using that code in products
across the company. It is later discovered that the code Alice submitted wasn’t
actually owned by either Alice or A Corp - in fact, Alice doesn’t even work for
A Corp and her name isn’t actually Alice. B Corp just recklessly incorporated
and utilized code that belongs to a completely unrelated third party, and now
that third party may have a cause of action against B Corp. This fact pattern
demonstrates the value of authentication (such as email verification), as it
ensures that the people signing a CLA are who they say they are.

#### Unauthorized signee

An unauthorized signee could be an engineer employed by an organization signing
a CLA on the organization's behalf, where the engineer is confused about the
need for special authority to enter into such an agreement. Suppose the engineer
proceeds with signing the agreement and contributes code, but then the
organization discovers this errant engineer's actions and revokes the agreement.
This could require that the receiving company isolate and remove all of the code
contributed by the engineer (and by other employees of the organization). This
unauthorized signee scenario is a realistic fact pattern in the world of code
collaboration, and is one reason why measures should to be taken to ensure that
CLA signees are authorized.

#### Corporate signing authority

Under American corporate law, officers of a company generally only have
authority to enter into contractual agreements on behalf of the company if the
company's board of directors explicitly bestows such permission.[^10]
Traditionally, "C-level" executives like CEOs or CTOs are each explicitly
granted a degree of signing authority in the company’s bylaws, but there could
be a narrower or broader designation of authority as the board sees fit.

This raises the obvious concern that, without reviewing every contributor’s
company bylaws to determine whether a given officer has been granted signing
authority, a company might be authorizing CLAs that are unenforceable against
contributors. Here, Section 4 of the Apache CLA again operates to protect the
contracting parties from surprise by requiring that the signee certify their
authority to take the action on behalf of the company.

It is important to note however that, while Section 4 does place responsibility
on the signee, it is likely insufficient protection on its own should the
receiving company accept this assertion from a signee whose title belies
authority to grant the company a perpetual license to code owned by the signee’s
employer. A court might view the receiving company’s acceptance of that CLA as
unreasonable reliance upon the authority of the signee.[^11]

Fortunately, it is an established tenet of agency law that when an agent holds
actual or apparent authority to act on behalf of the agent’s principal, the
principal is bound by the agent’s actions.[^12] This tenet permits a receiving
company to accept CLA submissions with assurance that the agreement will be
effective without needing to implement an onerous procedure,[^13] but does
require that the receiving company ascertain that the signee holds actual or
apparent authority.

#### Actual authority

Actual authority represents the ideal scenario whereby an officer acting on
behalf of a company is taking an action with the company’s knowledge and
consent.[^14] Of course, a company should always endeavor to ensure that all of
its contractual agreements are entered into with actual authority. If an agent
represents themselves to speak for an organization and enters into an agreement
contrary to the organization's interests, it creates conflict that can harm both
parties to the contract.

However, ascertaining actual authority rests upon facts that are outside the
scope of what a receiving company may reasonably observe or control.[^15]

#### Apparent authority

Apparent Authority covers situations where someone transacting with an officer
of a company relies on the officer's authority to enter into that transaction
based on the company's representations that the officer wields such
authority.[^16] In other words, when a contracting party reasonably relies on
the authority of an agent of a corporation in order to bind that corporation in
an agreement, that agreement remains valid against the corporation, even if the
corporation did not actually authorize its agent to enter into the agreement.

The benefit of apparent authority is that it presents criteria that are within a
receiving company’s means to control. For this reason, while it should be a
clear aim to enter into all agreements with actual authority on the part of all
contracting parties, these best practices focus on ensuring that apparent
authority is satisfied.

In order for a receiving company to ensure that its CLAs are legally enforceable
under a theory of apparent authority, it should take care that its CLA
acceptance procedure satisfies the two criteria for apparent authority: 1) the
company must reasonably believe that the signee has authority, and 2) that
belief must be traceable to the manifestations of the contracting party (the
company or organization the signee is acting on behalf of).[^17]

The receiving company’s belief in the authority of the signee should be
reasonable in order to shield the signatory corporation from being contractually
bound by the actions of a non-executive employee. Imagine if a B Corp executive
were to wave in a C Parcel Services delivery driver and have the driver sign a
contract between B Corp and C Parcel Services for new shipping rates for B Corp
deliveries worldwide; it would be unreasonable to enforce that agreement against
C Parcel Services.

The belief should also be traceable to the manifestations of the signatory
corporation in order to shield the signatory corporation from the fraudulent
acts of third parties. If someone walked into B Corp headquarters purporting to
be an attorney acting on behalf of C Parcel Services, offering new shipping
rates for B Corp deliveries, and B Corp were to sign that agreement with the
attorney, it would similarly be unenforceable if the attorney’s claim to
represent C Parcel Services were not traceable to some manifestation on C Parcel
Services’ part.

The determinations of whether the belief in a signee's authority is reasonable
and traceable to manifestations of the company forms a very
fact-and-context-dependent inquiry; but these are helped by common-sense
considerations as to whether a given agent wields the mark of authority.

It is important to note that the corporation’s manifestation need neither be
direct nor in writing; bestowing a given title on an individual will do.[^18]
For this reason, a CLA acceptance procedure may rely heavily on consideration of
the CLA signee’s title to ensure that the role is one that reasonably carries
authority for the transaction and that this authority is conveyed by a
manifestation of the contracting corporation. This is also why receiving
companies should be careful to utilize authentication, to ensure that this
manifestation is directly traceable to the contracting corporation.

A statute from the California civil code spells out the overarching principle at
work in this apparent authority determination, and it provides a helpful lens
for evaluating whether apparent authority may be satisfied:

> "Where one of two innocent persons must suffer by the act of a third, he, by
> whose negligence it happened, must be the sufferer."[^19]

This dynamic formula can operate in one of two ways in the context of honoring
contractual agreements. The first, relying on the notion that a principal must
take care in appointing and monitoring its agents,[^20] would have the contract
be enforceable against the party who did not exercise care in monitoring its
apparently-authorized agent's activity (signing the CLA and submitting code
under it). The second application, turning on reasonable reliance, would make
the contract unenforceable by the party who accepted an agreement signed by a
low-level employee on behalf of an entire company.[^21] This critical lever
underscores the importance of considering the title of every CLA signee before
accepting CLA submissions.

Additionally, this lever highlights the value of funneling all contributors from
a given organization through a single, authorized contact. CLA signees, by
requirement, should hold an office of authority at their organization, and
should assume the responsibility of designating a Point of Contact for managing
the code contribution relationship.[^22] This shields the receiving company from
arguments that a rogue engineer contributed code unaware of the CLA. Moreover,
by funneling contributors through a point of contact at their own organization,
it creates the opportunity for that organization to exercise reasonable care in
apprising itself of the activities of its employees.

#### Multiple signatures

In addition to maintaining a single version of the CLA that is used for all
contributors, another best practice for maintaining CLAs is to only accept a
single CLA from a given contributing organization. There are three reasons for
this: First, there could otherwise be a problem at the code contribution stage.
If code were to be contributed by an engineer who was covered under multiple
CLAs, an additional layer of review would be required to determine under which
CLA the code was contributed.[^23]

Second, if the terms of the company’s CLA were ever to change, there could be
confusion as to which terms were controlling if multiple CLAs with different
terms were executed. Third, accepting multiple CLAs from different officers at a
given company could undermine the validity of all of the CLAs signed by that
company. The receiving company would have trouble arguing that it reasonably
relied upon the authority of a CLA signee if the company were to ignore evidence
that the signee’s organization had multiple officers each declaring themselves
to be the single designated authority at the organization responsible for
managing the CLA relationship.

### Vetting code contributions

Above, it was noted that copyright law often operates to place ownership of
creative works in the hands of one’s employer, but that is not always the case.
In this regard, ensuring that all contributors from a given organization are
funneled through a responsible contact serves another important purpose. Suppose
an engineer whose employer has signed B Corp’s CLA submits code to B Corp. But
let’s say that the engineer had written that code before going to work for that
employer. If this engineer has not signed the B Corp CLA in her individual
capacity, and if she is not certifying that the code is being contributed as
property of the engineer’s organization (by coordinating through the point of
contact assigned to the agreement), then B Corp does not have a license to use
that engineer’s code. Funneling contributors through a single point of contact
helps to ensure that the engineers’ submissions will be considered property of
the engineers’ employers.

#### GitHub

Under the Apache CLA, the definition of contribution requires that the
contribution be intentional. Under any circumstance where code is not submitted
through a formal process, the intentionality of that contribution is put in
question. Accordingly, a uniform code contribution process should be employed,
which usually, but not always, takes the form of pull requests through GitHub.

Generally, as part of a contribution process, a contributor company will create
a fork of the repository being contributed to, make edits and additions to the
repository, and then submit a pull request to update the canonical version. Such
a procedure entails two roles: someone who initiates the pull request
(submitter), and one or more people who have authored the actual content of the
pull request (commit authors).

Often times the submitter and commit author may be the same person. However, it
may also be the case that multiple employees at the contributor company will
have made edits to the fork, in which case the submitter would only be one of
the authors of the commits being submitted. In order to accept the pull request,
it should be verified that the submitter and commit authors are all covered by a
CLA.[^24] In certain cases the submitter and commit authors may be covered by
different CLAs, in which case it’s helpful to have a procedure in place to
determine intentionality on the part of the commit authors.

## Guidance

### Instructions

As described throughout this document, having a procedure for accepting CLA
submissions plays a vital role in the aims of validating the agreement and
avoiding any potential problems. As a best practice, this procedure should
consist of: a check to see if the contracting party has already submitted a CLA,
verification of the signee’s email address to ensure that it is a company
address, and evaluation of the signee’s title to ensure that the signee wields
signing authority.

### Titles that confer authority

Per the discussion of apparent authority above, the act of conferring a given
title upon an employee constitutes a “manifestation” that may be “reasonably”
relied upon for establishing apparent authority. When evaluating a CLA signee's
title, the following positions are regarded as wielding the requisite authority
to execute the agreement:

**President/CEO**: presidents hold broad authority to take executive action on
behalf of their company and will be considered to have authority to execute
virtually any agreement.[^25]

**Vice-President**: there have been cases where a vice-president was found to
lack apparent authority to sign on behalf of a company, but this turned on the
contracting party’s knowledge that the vice-president lacked this authority[^26]
or where the agreement concerned matters outside the vice-president's scope of
employment.[^27] Generally, a vice-president will be found to wield authority to
execute an agreement of significant import, such as a CLA.

**General Manager**: though an uncommon title in the context of software
engineering and CLA execution, general managers are regarded as having broad
authority to act on behalf of their company in the ordinary course of the
company's business.[^28]

**Chief Technology Officer/Director of Engineering**: a "chief" officer or
"director" holds significant executive authority, but this authority is
generally confined to a specific function. Chief or director positions in
departments that are related to software engineering can provide strong
assurance of CLA signing authority.

**Counsel**: attorneys employed by a company may potentially be subject to
heightened fiduciary obligations to the company, just as its officers and board
of directors are. Absent evidence to the contrary, an action taken by counsel
could be treated as a decision made with the company’s full knowledge and
consent.

### Titles that likely lack authority

If a corporate CLA were submitted by an individual with a title other than one
of those listed above, it should be evaluated carefully. Accepting a signature
from an employee with an irregular title might be appropriate after discussion
to clarify the nature of the signee’s authority, but without such assurance it
should likely be rejected. The following positions represent the most common
titles of corporate CLA signees that should be regarded circumspectly:

**Software Engineer**: companies must be wary of engineers attempting to sign
corporate CLAs, as they may be acting independently of the organization they
work for, and likely do not wield signing authority to bind the organization.

**Chief Financial Officer, Director of Sales, Product Manager**: as a
counterpoint to the examples concerning chief officers and directors above,
“chief,” “director,” or “manager” roles that are not natured to be
external-facing, or which do not concern themselves directly with software
engineering or external collaboration could be found to lack the authority
needed to enter into the agreement.[^29]

**Legal Assistant**: Whereas counsel for a company may hold the authority to
make representations and warranties on behalf of the company, and can bear
responsibility for ensuring that their actions are undertaken with the full
knowledge and consent of the company, the same would not necessarily apply to a
legal assistant. Sometimes companies employ paralegal “contract managers”
specifically responsible for managing licensing relationships, but this
constitutes the sort of case where a discussion for clarification is advised.

### Minimal information collection from corporations and individuals

Minimizing the collection of signee personally identifiable information (PII)
reduces maintenance costs and protects signees’ privacy, but a certain amount of
information collection is indispensable. One should be able to trace title from
a given submission to a known human being or entity. The two pieces of
information that should always be collected from CLA signees are email address
and name. For corporate CLAs, the name of the corporation and the signee’s
corporate title should also be collected.

Email address verification serves three critical purposes: identity
verification, company employee status verification, and means of contact.

Obtaining the name of the signee is indispensable for identity verification, but
is also necessary for substantiating the agreement.

In the case of corporate CLAs, the collection of this information not only
furnishes evidence of the agreement in the event of suit, it provides the
criteria for establishing apparent authority. The email address establishes that
the signee really is an employee of the company they represent and are acting in
their capacity as an agent of the company. The title establishes whether the
company has conferred authority upon the signee to execute the agreement.

[^1]: The Berne Convention requires that copyright rights vest automatically at
    the time of creation. WIPO-Administered Treaties: Berne Convention For The
    Protection Of Literary And Artistic Works, Article 5(2). Wipo.int. N.p.,
    2016\. Web. 24 Jun. 2016.

[^2]: “A ‘work made for hire’ is ... a work prepared by an employee within the
    scope of his or her employment.” 17 U.S.C. § 101. See Miller v. CP Chems.,
    Inc., 808 F. Supp. 1238, 1242-44 (D.S.C. 1992) (software written at home
    during off-hours, without direction or extra compensation from employer
    found to be a work-for-hire), appeal dismissed, No. 93-1045 (4th Cir.
    April 13, 1993); Genzmer v. Pub. Health Trust, 219 F. Supp. 2d 1275, 1276
    (S.D. Fla. 2002) (same).

[^3]: https://www.apache.org/licenses/cla-corporate.txt
[^4]: When employers hold copyright to the work product of their employees, this
    can benefit receiving companies and downstream users because works for
    hire are ineligible for termination of transfer. See 17 U.S.C. §203(a) (In
    the case of any work other than a work made for hire, the exclusive or
    nonexclusive grant of a transfer or license of copyright ... is subject to
    termination under [certain] conditions[.]). This means that the receiving
    company does not need to fear that the contributing organization or their
    successors in interest could attempt to terminate the license 35 years
    after granting it.

[^5]: This mechanism stipulates that the patent license between the contributor
    and any given entity terminates if the entity institutes patent
    litigation. See Clause 3 of http://www.apache.org/licenses/LICENSE-2.0.

[^6]: See e.g. Meyer v. Ford Motor Co., 275 Cal. App. 2d 90, 102 (Cal. App. 3d
    Dist. 1969) (“Although it is established that ostensible authority can be
    created only by the acts or declarations of the principal, not by those of
    the agent, the principal need not have been in direct contact with the
    third party; the manifestation of the principal may be to the community at
    large, and may consist of appointing the agent to a particular
    position.”). CLA be signed by “the chairperson of the board, the president
    or any vice president and the secretary, any assistant secretary, the
    chief financial officer or any assistant treasurer” in order to (almost)
    incontrovertibly establish the legitimacy of the agreement under
    California law. Cal. Corp. Code § 313.

[^7]: This could arise if a contributor sought to limit the use of their code to
    internal uses by the company, to limit the company’s permission to charge
    end users a fee in connection with use of the code, or by a litany of
    other possible criteria were every inbound code contribution subject to a
    negotiated license.

[^8]: See 17 U.S.C. § 203(a) (“In the case of any work other than a work made
    for hire, the exclusive or nonexclusive grant of a transfer or license of
    copyright ... is subject to termination…[.]”).

[^9]: Copyrighted works created “within the scope of one’s employment” are
    treated as works made for hire. Works created outside the scope of
    employment, such as works created prior to being employed, or works
    created by an engineer using the engineer’s own time and resources (and
    that are unrelated to the employer’s business) are owned by their specific
    author.

[^10]: See, e.g., Cal Corp Code § 208(b).
[^11]: See Airline Support, Inc. v. ASM Capital II, L.P., 279 P.3d 599, 609
    (Alaska 2012) (remanded for determination of “whether a credit manager of
    a company's accounts receivable department would typically have the
    authority to sell one of the company's significant assets”).

[^12]: “Any contract or conveyance made in the name of a corporation which is
    […] done within the scope of the authority, actual or apparent, conferred
    by the board or within the agency power of the officer executing it, […]
    binds the corporation[.]” Cal Corp Code § 208(b).

[^13]: For instance, a California-based company could require that the CLA be
    signed by “the chairperson of the board, the president or any vice
    president and the secretary, any assistant secretary, the chief financial
    officer or any assistant treasurer” in order to (almost) incontrovertibly
    establish the legitimacy of the agreement under California law. Cal.
    Corp. Code § 313.

[^14]: "An agent acts with actual authority when, at the time of taking action
    that has legal consequences for the principal, the agent reasonably
    believes, in accordance with the principal's manifestations to the agent,
    that the principal wishes the agent so to act." Restat 3d of Agency §2.01
    (3rd 2006)

[^15]: An example would be if the president of a company were personally
    instructed by the company’s board not to accept a CLA, yet the president
    were to proceed with signing it anyway. The receiving company may be
    faultless for trusting in the president’s apparent authority, even though
    the president lacks actual authority due to the action of the board.

[^16]: "Apparent authority is the power held by an agent or other actor to
    affect a principal's legal relations with third parties when a third
    party reasonably believes the actor has authority to act on behalf of the
    principal and that belief is traceable to the principal's
    manifestations." Restat 3d of Agency §2.03 (3rd 2006)

[^17]: Id.
[^18]: “A principal may also make a manifestation by placing an agent in a
    defined position in an organization or by placing an agent in charge of a
    transaction or situation. Third parties who interact with the principal
    through the agent will naturally and reasonably assume that the agent has
    authority to do acts consistent with the agent's position or role unless
    they have notice of facts suggesting that this may not be so.” Restat 3d
    of Agency, § 3.03 (3rd 2006).

[^19]: Cal Civ Code § 3543.
[^20]: A principal is liable for the torts of its agent if it is negligent in
    “selecting, training, retaining, supervising, or otherwise controlling
    the agent.” Restat 3d of Agency, § 7.05 (3rd 2006).

[^21]: “Apparent authority ends when it is no longer reasonable for the third
    party with whom an agent deals to believe that the agent continues to act
    with actual authority.” Restat 3d of Agency, § 3.11(2) (3rd 2006).

[^22]: “It is your responsibility to notify the Foundation when any change is
    required to the list of designated employees authorized to submit
    Contributions on behalf of the Corporation, or to the Corporation's Point
    of Contact with the Foundation.” Section 8 of The Apache Software
    Foundation Software Grant and Corporate Contributor License Agreement, at
    https://www.apache.org/licenses/cla-corporate.txt

[^23]: This is designed to clarify situations where it is unclear whether the
    code is being submitted on behalf of an engineer’s employer as opposed to
    being submitted by the engineer in her individual capacity, but could be
    triggered by the existence of multiple CLAs for a given entity.

[^24]: All individuals under a single authorized group for a single given CLA
    are considered to be the same entity, both under the terms of a CLA and
    the law. One key measure in ensuring the intentionality of a submission
    is requiring that all of the commits authored in a given pull request are
    subject to the same CLA.

[^25]: See *Menard, Inc. v. Dage-MTI, Inc.*, 726 N.E.2d 1206 at 1216 (Ind. 2000)
    (even where president possessed neither actual nor apparent authority to
    enter agreement, corporation subject to liability due to the president’s
    inherent authority).

[^26]: The contracting party knew that the corporate vice president lacked
    authority to agree to a three-year ship charter. The contracting party
    could not reasonably rely on the vice president’s claim of authority, and
    the senior management of the company did nothing to manifest that such
    authority existed. *Armagas Ltd. v. Mundogas S.A.* 1 A.C. 717, 777-78
    (1986).

[^27]: Vice president found to lack authority to sign on behalf of company where
    the contract concerned the vice-president’s individual transactions.
    *Morris v. Griffith & W. Co.*, 69 F. 131, 137, 1895 U.S. App. LEXIS 3080,
    *17 (C.C.D. Ohio 1895).

[^28]: *Anderson v. McAllister Towing & Transp. Co.*, 17 F.Supp.2d 1280, 1289
    (S.D.Ala. 1998).

[^29]: *See Orient Overseas Container Line v. Kids Int’l Corp.*, 1999 A.M.C. 961
    (S.D.N.Y. 1998) (“Director of Imports” lacked actual authority to execute
    a guarantee on behalf of a third party to induce a shipping company to
    release merchandise absent the original bills of lading).
