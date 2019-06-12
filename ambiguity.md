# Resolving Contractual Ambiguity in Open Source Licenses
{:.no_toc}

* Table of Contents
{:toc}

## Introduction {#introduction}

When disputes arise over the exact meanings of terms in open source licenses,
community members often look to the authors of the contract for additional
insight into what those particular terms mean. Is that how ambiguity in these
licenses should be resolved?

This chapter examines how United States contract law applies to open source
licenses, and how contract law principles could be used by courts to determine
the meaning of ambiguous license terms.[^nickname] Regardless of what state or
federal commercial contract laws apply, courts are certain to turn to the
traditional sources of evidence to resolve the meaning of disputed ambiguous
terms: the express terms of the agreement, evidence of the parties' course of
performance, evidence of the parties' course of dealing, and trade usage of the
term. These sources of evidence are assigned different weights and some prevail
over others. These concepts will be discussed at in the context of open source
license terms.

[^nickname]: State contract law will often be discussed based on the Restatement
    (Second) of Contracts (1981), which summarizes the prevailing
    common law principles, and has continued to influence the
    development of state contract law for many decades. Some of the
    excerpted cases will discuss specific state contract case law. For
    further discussion of open source licenses being treated as
    contracts under U.S. law, refer to the discussion of _Jacobsen v.
    Katzer_, 535 F.3d 1373 (Fed. Cir. 2008) in Dashiell Renaud &
    Maxwell Sills, _Contract and Copyright Remedies Available under
    Open Source Licenses_, Google Open Source Casebook,
    https://opensource.google.com/docs/casebook/remedies/ (last visited
    Nov. 27, 2018).

## Ambiguous Contract Terms {#ambiguous-contract-terms}

A contract may have a term which is unclear or ambiguous. A term is ambiguous if
it could have more than one meaning.[^meanings]

[^meanings]: _Black's Law Dictionary_ 33-34 (3rd Pocket ed. 2006) ("ambiguity,
    _n._ An uncertainty of meaning or intention, as in a contractual
    term or statutory provision. -- ambiguous, _adj_. _latent
    ambiguity._ An ambiguity that does not readily appear in the
    language of the document, but instead arises from a collateral
    matter when the document's terms are applied or executed ("the
    contract contained a latent ambiguity: the shipping terms stated
    that the goods would arrive on the _Peerless_, but two ships have
    that name"). _patent ambiguity._ An ambiguity that clearly appears
    on the face of a document, arising from the language itself ("the
    nonperformance was excused because the two different prices
    expressed in the contract created a patent ambiguity.").

If the term is nonmaterial, then the uncertainty about that term does not affect
the enforceability of the contract. However, if a term is so "material" that
without it a court cannot determine what the parties agreed to or even whether
the parties agreed to enter into a contract, then the uncertainty about that
term may negate the existence of a contract for being "indefinite."[^indefinite]

[^indefinite]: U.C.C. § 2-204(3) (2002), _available at_
    https://www.law.cornell.edu/ucc/2/2-204 ("(3) Even though one or
    more terms are left open a contract for sale does not fail for
    indefiniteness if the parties have intended to make a contract
    and there is a reasonably certain basis for giving an appropriate
    remedy."); Restatement (Second) of Contracts § 33 (1981)
    ("Certainty (1) Even though a manifestation of intention is
    intended to be understood as an offer, it cannot be accepted so
    as to form a contract unless the terms of the contract are
    reasonably certain. (2) The terms of a contract are reasonably
    certain if they provide a basis for determining the existence of
    a breach and for giving an appropriate remedy. (3) The fact that
    one or more terms of a proposed bargain are left open or
    uncertain may show that manifestation of intention is not
    intended to be understood as an offer or as an acceptance.");
    _Black's Law Dictionary_ 711 (3rd Pocket ed. 2006) ("material
    term. A contractual provision dealing with a significant issue
    such as subject matter, price, payment, quantity, quality,
    duration, or the work to be done."); _compare Genest v. John
    Glenn Corp._, 298 Ore. 723 (1985) (Court refused to enforce
    specific performance of standard form real estate contract
    because too many material terms were missing. Purchase price was
    fixed, but terms regarding interest and existing liens remained
    unsettled), _with Oglebay Norton Co. v. Armco, Inc._, 52 Ohio
    St.3d 232 (1990) (Court upheld imposing specific performance and
    resolved a reasonable purchase price, concluding that the parties
    manifested an adequate intent to be bound by the terms of the
    agreement and so the contract did not fail for indefiniteness
    even if the pricing terms failed.)

The Uniform Commercial Code and the Restatement (Second) of Contracts indicate
that if the language of an agreement is adequate to establish a reasonable
intent to contract, a basis for finding a breach, and a means of providing a
remedy, then the court should resolve the uncertainty regarding the material
term.[^material] Courts also routinely resolve ambiguous nonmaterial terms if
they are central to a dispute.

[^material]: U.C.C. § 2-204(3) (2002) ("(3) Even though one or more terms are
    left open a contract for sale does not fail for indefiniteness if
    the parties have intended to make a contract and there is a
    reasonably certain basis for giving an appropriate remedy.");
    Restatement (Second) of Contracts § 33 (1981) ("Certainty (1) Even
    though a manifestation of intention is intended to be understood as
    an offer, it cannot be accepted so as to form a contract unless the
    terms of the contract are reasonably certain. (2) The terms of a
    contract are reasonably certain if they provide a basis for
    determining the existence of a breach and for giving an appropriate
    remedy. (3) The fact that one or more terms of a proposed bargain
    are left open or uncertain may show that manifestation of intention
    is not intended to be understood as an offer or as an
    acceptance."); _Black's Law Dictionary_ 711 (3rd Pocket ed. 2006)
    ("Material term. A contractual provision dealing with a significant
    issue such as subject matter, price, payment, quantity, quality,
    duration, or the work to be done."); _compare Genest v. John Glenn
    Corp._, 298 Ore. 723 (1985) (Court refused to enforce specific
    performance of standard form real estate contract because too many
    material terms were missing. Purchase price was fixed, but terms
    regarding interest and existing liens remained unsettled), _with
    Oglebay Norton Co. v. Armco, Inc._, 52 Ohio St.3d 232 (1990) (Court
    upheld imposing specific performance and resolved a reasonable
    purchase price, concluding that the parties manifested an adequate
    intent to be bound by the terms of the agreement and so the
    contract did not fail for indefiniteness even if the pricing terms
    failed.)

The rest of this chapter examines the sources of law and evidence that instruct
a court in resolving uncertain terms.

**Discussion**

1.  What would be the material terms of a software license that are necessary
    for a court to find adequate intent to contract, a basis for finding a
    breach, and means of providing a remedy? If a term in an open source license
    failed but a court found that the licensor and licensee manifested adequate
    intention to be bound by the contract, how might a court enforce specific
    performance of the remaining terms?
1.  Under an analysis of materials terms and the intent of the parties to be
    bound, would the WTFPL be considered a contract?[^wtfpl] The terms of the
    WTFPL license are, in their entirety (redacted for obscenity):

        DO WHAT THE F*CK YOU WANT TO PUBLIC LICENSE

        Version 2, December 2004

        Copyright (C) 2004 Sam Hocevar <sam@hocevar.net>

        Everyone is permitted to copy and distribute verbatim or modified copies of
        this license document, and changing it is allowed as long as the name is
        changed.

        DO WHAT THE F*CK YOU WANT TO PUBLIC LICENSE

        TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

        0. You just DO WHAT THE F*CK YOU WANT TO.

    What about the also-short MIT License? \

        Copyright <YEAR> <COPYRIGHT HOLDER>

        Permission is hereby granted, free of charge, to any person obtaining a
        copy of this software and associated documentation files
        (the "Software"), to deal in the Software without restriction,
        including without limitation the rights to use, copy, modify, merge,
        publish, distribute, sublicense, and/or sell copies of the Software,
        and to permit persons to whom the Software is furnished to do so,
        subject to the following conditions:

        The above copyright notice and this permission notice shall be included
        in all copies or substantial portions of the Software.

        THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
        OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
        MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
        IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
        CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
        TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
        SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

1.  What types of open source license terms might be nonmaterial, but possibly
    central to a legal dispute such that a court would need to resolve their
    ambiguity? Consider the term "user" in the AGPL v3.[^agpl] In paragraph 13,
    the AGPL v3 states,

        Notwithstanding any other provision of this License, if you modify the
        Program, your modified version must prominently offer all users
        interacting with it remotely through  a computer network (if your
        version supports such interaction) an opportunity to receive the
        Corresponding Source of your version by providing access to the
        Corresponding Source from a network server at no charge, through some
        standard or customary means of facilitating copying of software. The
        Corresponding Source shall include the Corresponding Source for any
        work covered by version 3 of the GNU General Public License that is
        incorporated pursuant to the following paragraph . . .

    Could the term "user" be considered ambiguous? If AGPL licensed software is
    only used internally for employee use, could employees be considered "users"
    who can exercise rights under the AGPL v3?

[^wtfpl]: _Do What the F*ck You Want to Public License (WTFPL)_,
    [http://www.wtfpl.net/](http://www.wtfpl.net/) (last visited Nov. 27,
    2018).

[^agpl]: _Affero General Public License v3_, _available at_
    https://www.gnu.org/licenses/agpl-3.0.en.html (last visited Nov. 27,
    2018).

## Does the U.C.C. or State Common Law Apply to Open Source Licenses? {#u-c-c-or-state-common-law-apply-to-open-source-licenses}

Different contract laws apply to a contract depending on whether it is a
contract for goods or for services. Service contracts are governed by state
contract laws,[^service] while Article 2 of the Uniform Commercial Code (the
"UCC") governs contracts for the sale of goods. Every state has implemented the
UCC and where the UCC applies, it preempts state common law.[^preempt] The UCC's
definition of "goods" specifically contemplates movable goods.[^movable]

[^service]: For the purposes of this chapter, we will look to the Restatement
    (Second) of Contracts (1981) for its summary of prevailing state
    contract law. _See_ Edward A. Pisacreta et al., _Intellectual
    Property Licensing: Forms and Analysis_ § 2.01 (Law Journal Press
    2011) ("In the United States, the common law is the primary source
    for the law of contracts. In order to summarize the common law of
    contracts in an organized and systematic manner, the American Law
    Institute published the _Restatement of Contracts_ in 1932, and
    revised it in 1980. Although the Restatements do not have the force
    of law, they have been very influential in both the litigation and
    transactional aspects of United States contract law.").

[^preempt]: _See_ _Uniform Commercial Code_, Wikipedia,
    [https://en.wikipedia.org/wiki/Uniform_Commercial_Code](https://en.wikipedia.org/wiki/Uniform_Commercial_Code)
    (last visited Nov. 23, 2018) (CC-BY-SA 3.0) ("The Uniform Commercial
    Code (UCC), first published in 1952, is one of a number of uniform
    acts that have been put into law with the goal of harmonizing the
    law of sales and other commercial transactions across the United
    States of America (U.S.) through UCC adoption by all 50 states, the
    District of Columbia, and the U.S. territories."); _Uniform
    Commercial Code_, Inc.com,
    [https://www.inc.com/encyclopedia/uniform-commercial-code-ucc.html](https://www.inc.com/encyclopedia/uniform-commercial-code-ucc.html)
    ("Currently, all 50 states, the District of Columbia, and the U.S.
    Virgin Islands have adopted the UCC as state law, although some have
    not adopted every single provision contained within the code.");
    _see also Fariba v. Dealer Servs. Corp._, 178 Cal.App.4th 157 (4th
    Dist. 2009) ("Case law from other jurisdictions applying our
    Commercial Code, the Uniform Commercial Code, or the uniform code of
    other states, is considered good authority in litigation arising
    under the California Act."); _Reading Co-Op. Bank v. Suffolk Constr.
    Co._, 464 Mass. 543 (2013) ("We note that authority from other
    jurisdictions is especially relevant in the context of the UCC,
    which seeks to 'make uniform the law among the various
    jurisdictions[.]'").

[^movable]: U.C.C. § 2-105 (2002), _available at_
    https://www.law.cornell.edu/ucc/2/2-105 ("'Goods' means all things
    (including specially manufactured goods) which are movable at the
    time of identification to the contract for sale other than the money
    in which the price is to be paid, investment securities (Article 8)
    and things in action. 'Goods' also includes the unborn young of
    animals and growing crops and other identified things attached to
    realty as described in the section on goods to be severed from
    realty (Section 2-107).").

Open source licenses are contracts for software. Currently courts are divided on
whether the UCC applies to software transactions.[^divided] Although transferred
software may not be a tangible, movable good as contemplated by the UCC, many
courts acknowledge that the drafters of Article 2 could not have contemplated
software as we now know. However, many of these courts also value the certainty
brought by applying UCC.[^certainty] Numerous federal circuits and state courts
have applied the UCC to software contracts.[^applyUCC] Many other courts have
held that the UCC does not govern contracts for software.[^applyRestatement]
Although many courts and practitioners often bemoan the lack of certainty about
whether state contract law or Article 2 of the UCC will apply, none of the
efforts to resolve this to date have been successful.[^unsuccessful] For the
time being there is no bright line guidance on whether software may be
considered a "good" for the purposes of the application of the UCC.

[^divided]: _See_ Am. Law Inst., _Principles of the Law: Software Contracts_
    §1.12 (2010) (Relation to Outside Law); _see also_ Stacy-Ann Elvy,
    _Hybrid Transactions and the INTERNET of Things: Goods, Services, or
    Software?_, 74 Wash. & Lee L. Rev. 77 (2017),
    https://scholarlycommons.law.wlu.edu/cgi/viewcontent.cgi?article=4530&context=wlulr
    at 79 ("Article 2 of the UCC governs transactions in goods. However,
    despite the goals of certainty and uniformity, one of the thorniest
    issues in sale of goods transactions is how best to determine
    whether Article 2 applies to transactions involving the provision of
    goods and non-goods, such as services or software.") _citing_
    Richard Raysman & Peter Brown, _Applicability of the UCC to Software
    Transactions_; Technology Today, N.Y. L.J. ONLINE (Mar. 8, 2011)
    (acknowledging that Article 2 does not explicitly mention software).

[^certainty]: _See_ Am. Law Inst., _Principles of the Law: Software Contracts_
    §1.12 (2010) (Relation to Outside Law).

[^applyUCC]: _Id._ _citing_ _Sys. Design & Mgmt. Info., Inc. v. Kansas City Post
    Office Employees Credit Union_, 788 P.2d 878 (Kan. Ct. App. 1990)
    ("The test . . . [is] whether [the] predominant factor . . . [or]
    purpose [of the contract] . . . is the rendition of service[s],
    with goods incidentally involved.'") (quoting _Bonebrake v. Cox_,
    499 F.2d 951, 960 (8th Cir. 1974)); _VMark Software v. EMC Corp_.,
    642 N.E. 2d 587, 590 n.1 (Mass. App. Ct. 1994) (accepting
    presumption that software is a good under the U.C.C.); _Colonial
    Life Ins. Co. of Am. v. Elec. Data Sys. Corp._, 817 F.Supp. 235 (D.
    N.H. 1993) (U.C.C. applies where software was the predominant
    factor); _Advent Sys. Ltd. v. Unisys Corp._, 925 F.2d 670 (3d Cir.
    1991) (software treated as a good under the U.C.C., because
    although a program is copyrightable, once it is placed on a disc or
    other format, it is a tangible product capable of being sold in the
    marketplace); _Wachter Mgmt. Co. v. Dexter & Chaney, Inc._, 144
    P.3d 747, 748 (Kan. 2006) ("Computer software is considered to be
    goods subject to the Uniform Commercial Code (UCC) even though
    incidental services are provided along with the sale of
    software.").

[^applyRestatement]: _Id._ _citing_ _Pearl Invs., LLC v. Std. I/O, Inc._, 257
    F.Supp.2d 326, 353 (D. Me. 2003) (custom software primarily
    a service); _Wharton Mgmt. Group v. Sigma Consultants,
    Inc._, 1990 WL 18360, at *3 (Del. Super. Ct.) (Article 2
    does not apply to customized computer software because "it
    was [transferor's knowledge, skill and ability for which
    transferee bargained"), _aff'd_, 582 A.2d 936 (Del. 1990);
    _Micro-Managers, Inc. v. Gregory_, 434 N.W.2d 97 (Wis. Ct.
    App. 1998) (where contract for custom software is paid on
    basis of time, at stated rates, and materials, the services
    aspect of the contract is its predominant purpose.).

[^unsuccessful]: The American Law Institute and the Uniform Law Commission have
    repeatedly tried to resolve the uncertainty regarding the
    applicable law for software contracts. In the 1990s, the ALI
    and the ULC sought to draft an Article 2B to the UCC to address
    software contracts, but that effort failed. In 1999, the ULC
    drafted the notorious Uniform Computer Information Transactions
    Act (UCITA), which was only enacted into law in two states,
    while several other states enacted "bomb shelter" laws to
    prevent the UCITA from ever coming into force in those states.
    Most recently, in 2009 the ALI published the _Principles of the
    Law of Software Contracts_ simply as a resource for lawyers,
    judges, and legislators. The _Principles_ acknowledge the
    inconsistency in the application of Article 2 but do not
    attempt to resolve it. _See_ Am. Law Inst., _Principles of the
    Law of Software Contracts_ (2010).

This analysis is further complicated by factual scenarios where contracts for
software may be related to a conveyance of hardware or services, although hybrid
contracts for goods and services are not a new issue in contract law. If a
contract concerns both goods and services, courts must determine how to apply
the law of contracts to the hybrid contract. Most courts have adopted a
predominant purpose test for determining whether the UCC or the common law
should apply to a particular contract.[^predominant] A court evaluates whether
the predominant purpose of the transaction is for the provision of goods or
services. The factors used to evaluate this vary, and courts reach opposite
conclusions based on similar facts.[^facts] Recent cases suggest that software
licenses that do not convey ownership rights to the software may be governed by
the common law rather than the UCC because there is no "sale" of goods at issue,
but this is far from being consistent guidance.[^sale]

[^predominant]: Stacy-Ann Elvy, _Hybrid Transactions and the INTERNET of Things:
    Goods, Services, or Software?_, 74 Wash. & Lee L. Rev. 77
    (2017),
    [https://scholarlycommons.law.wlu.edu/cgi/viewcontent.cgi?article=4530&context=wlulr](https://scholarlycommons.law.wlu.edu/cgi/viewcontent.cgi?article=4530&context=wlulr)
    at n.112 ("See Abby J. Hardwick, Note, _Amending the Uniform
    Commercial Code: How Will a Change in Scope Alter the Concept of
    Goods?_, 82 WASH. U. L.Q. 275, 280 (2004) ("The test most
    commonly used by the courts was the predominant purpose test.");
    _see also_ E. Allan Farnsworth, _Farnsworth on Contracts_ § 1.9
    at 44 (3d ed. 2004) ("Courts usually determine whether a
    transaction is one in goods, services, or land by looking for
    the 'predominant factor' of the contract.")).

[^facts]: _Id._ at 106-107.

[^sale]: _See, e.g._, _SAS Inst., Inc. v. World Programming Ltd._, No.
    5:10-25-FL, 2016 U.S. Dist LEXIS 79230, at *31-33, 2016 WL 3435196 at
    *10 (E.D.N.C. June 17, 2016) ("As this court has noted before, the
    applicability of the Uniform Commercial Code to software is a question
    that has confounded courts in the digital age. For every court that
    finds that "[t]he weight of authority favors application of common law
    and not the UCC with regard to software licenses," another finds that
    "courts nationally have consistently classified the sale of a software
    package as the sale of a good for UCC purposes." _Compare Attachmate
    Corp. v. Health Net, Inc._, No. C09-1161 MJP, 2010 U.S. Dist. LEXIS
    114445, 2010 WL 4365833, at *2 (W.D. Wash. Oct 26, 2010) with _Rottner
    v. AVG Techs. United States, Inc._, 943 F. Supp. 2d 222, 230 (D. Mass.
    2013). With respect to the software license at issue in this case . . .
    . In this case, the parties entered into a license, rather than a sale
    of goods because title for the Learning Edition software did not pass
    to defendant. First and foremost, plaintiff terms the agreement as a
    'license agreement,' rather than a 'purchase agreement.' _See._ Pl.'s
    Exh. 58 at 3. This license agreement explicitly referred to a "license
    grant" and expressly stated "The Software is copyrighted. Title to the
    Software and all other rights remain with SAS or its licensors at all
    times." _Id._ at 3, 4. The agreement specifically prohibited defendant
    from transferring or assigning the license to anyone else and gave a
    specific expiration date for the license. _Id._ at 3. . . . Because the
    Learning Edition license agreement did not transfer title to the
    software to the defendant, the transaction was not a sale and Article
    Two of the UCC does not apply.")

Regardless of whether the UCC or state common law of contracts governs, courts
will look to the same sources of evidence in the same order of priority when
interpreting ambiguous contract terms.[^governs] For the purposes of this
chapter, we will examine both the approach of both the UCC and Second
Restatement of Contracts to resolving ambiguity in contract terms.

[^governs]: _See_ textual discussion Sources of Evidence Used in Interpretation
    infra.

## Two Pathways to Resolving Ambiguity: Extrinsic Evidence & _Contra Proferentem_ {#two-pathways}

Before examining how extrinsic sources of evidence may be considered in
resolving ambiguity it is necessary to understand whether those sources of
evidence can be considered at all. The parol evidence rule prevents the
admission of extrinsic evidence in some circumstances, while the application of
_contra proferentem_ would make extrinsic evidence irrelevant. The following
sections address these potential barriers before we delve further into the
nuances of resolving ambiguity through the traditional sources of evidence.

### Admissibility of Extrinsic Evidence: the Parol Evidence Rule {#admissibility-of-extrinsic-evidence}

The parol evidence rule is a common law doctrine that limits how the parties to
a written contract can admit extrinsic evidence to explain a written
term.[^parol] The rule restricts evidence of written or oral discussions or
agreements that occurred prior to or contemporaneously with the final agreement.

[^parol]: _Black's Law Dictionary_ 522 (3rd Pocket ed. 2006) ("parol-evidence
    rule. _Contracts_. The common-law principle that a writing intended by
    the parties to be a final embodiment of their agreement cannot be
    modified by evidence of earlier or contemporaneous agreements that
    might add to, vary, or contradict their writing").

This rule would be relevant if parties to an open source license wished to
introduce evidence of discussions or agreements that occurred prior to the
existence of a contract (the license) in order to clarify the meaning of an
ambiguous term in the license. For instance, if an open source licensee believed
that there were relevant discussions regarding the meaning of a particular term
prior to importing code under the terms of a particular license, the evidence of
those discussions would be admissible only if permitted under the parol evidence
rule.

The Restatement has simplified the common law approach to applying the parol
evidence rule:[^simplified]

    Effect of Integrated Agreement on Prior Agreements (Parol Evidence Rule)
    (1) A binding integrated agreement discharges prior agreements to the extent
    that it is inconsistent with them. \
    (2) A binding completely integrated agreement discharges prior agreements
    to the extent that they are within its scope. \
    (3) An integrated agreement that is not binding or that is voidable and
    avoided does not discharge a prior agreement. But an integrated agreement,
    even though not binding, may be effective to render inoperative a term

[^simplified]: Restatement (Second) of Contracts § 213 (1981).

In plainer language, an "integrated agreement" simply means that there is a
writing accepted by both parties as the final expression of the terms of the
agreement.[^integrated] A court must first determine whether an integrated
agreement exists between the parties.[^first] When an integrated agreement
exists, evidence of prior negotiations or agreements is generally
inadmissible.[^inadmissible]

[^integrated]: _Id._ § 209(2) ("An integrated agreement is a writing or writings
    constituting a final expression of one or more terms of an
    agreement.").

[^first]: _Id._ § 210(3) ("Whether an agreement is completely or partially
    integrated is to be determined by the court as a question preliminary
    to determination of a question of interpretation or to application of
    the parol evidence rule.").

[^inadmissible]: _Id._ § 215.

Exceptions to the parol evidence rule exist. One of these exceptions is that
parol evidence or extrinsic evidence may be evaluated in order to resolve
ambiguities.[^may] If the extrinsic evidence would be consistent with the
integrated agreement (not contradictory) then the evidence may be admissible to
supplement the understanding of the ambiguous term.[^supplement]

[^may]: _Id._ §§ 214-16; _see also_ _Bone v. Refco, Inc._, 774 F.2d 235 (8th
    Cir. 1985) ("In a written contract . . . a court must give effect to the
    intent manifested by the plain meaning of the language used by the
    parties. _Id._ However, extrinsic or parol evidence is admissible to
    explain or help ascertain the intent of the parties when ambiguity,
    either patent or latent, exists in the written agreement."), _citing
    Press Machinery Corp. v. Smith R.P.M. Corp._, 727 F.2d 781, 784 (8th
    Cir. 1984) (applying Missouri law); _United States v. Haas & Haynie
    Corp._, 477 F.2d 568, 572 (9th Cir. 1978) (applying general contract
    principles).

[^supplement]: _See_ _Restatement (Second) of Contracts_ § 213(1) (1981); U.C.C.
    § 2-202 (2002).

The UCC incorporated a parallel parol evidence rule:[^uccper] * (a) by course of
dealing or usage of trade (Section 1-205) or by course of performance (Section
2-208); and * (b) by evidence of consistent additional terms unless the court
finds the writing to have been intended also as a complete and exclusive
statement of the terms of the agreement.

    Final Written Expression: Parol or Extrinsic Evidence.

    Terms with respect to which the confirmatory memoranda of the parties
    agree or which are otherwise set forth in a writing intended by the
    parties as a final expression of their agreement with respect to such
    terms as are included therein may not be contradicted by evidence of
    any prior agreement or of a contemporaneous oral agreement but may be
    explained or supplemented

In many instances there will be no evidence of prior or contemporaneous
discussion or agreements between an open source licensor and licensee, and so
the parol evidence rule will not apply.

[^uccper]: U.C.C. § 2-202 (2002).

### Standard Form Contracts and _Contra Proferentem_ {#standard-form-contracts-and-contra-proferentem}

Open source licenses are similar in some ways to pre-printed standard agreements
in that the terms are not negotiated for individual parties. Standard form
agreements have been a growing trend in many industries for decades.

In response to the rise of non-negotiated form agreements and the unjust
appearance of bargaining power imbalances the courts developed the common law
doctrine of _contra proferentem_, or "against the offeror."[^offeror] Under
_contra proferentem_, where an ambiguous term exists in a contract of adhesion
and is open to two possible meanings, a court will interpret the term against
the author of the standard form agreement in order to make up for the unequal
bargaining power of the party who was unable to negotiate the terms.[^unequal]

[^offeror]: _Contra Proferentem_, Wex Cornell Law School Dictionary,
    https://www.law.cornell.edu/wex/contra_proferentem ("A Latin term
    used in contract law referring to the principle that a judge will
    construe an ambiguous term against the party that imposed the
    inclusion of the term in the contract during negotiation or
    drafting." Captured in the Restatement (Second) of Contracts § 206
    (1981) as "Interpretation Against the Draftsman: In choosing among
    the reasonable meanings of a promise or agreement or a term thereof,
    that meaning is generally preferred which operates against the party
    who supplies the words or from whom a writing otherwise proceeds."

[^unequal]: _See Black's Law Dictionary_ 143 (3rd Pocket ed. 2006) ("adhesion
    contract. A standard-form contract prepared by one party, to be
    signed by another party in a weaker position, usu. a consumer, who
    adheres to the contract with little choice about the terms.").

It would be a stretch to apply the doctrine of _contra proferentem_ to the
popular standard open source licenses endorsed by the Open Source
Initiative.[^osilicenses] Traditionally _contra proferentem_ has been applied by
courts in the context of individuals signing contracts drafted entirely by the
legal team of a large corporation, such as insurance contracts. However, open
source licenses are fundamentally different in nature: they are not drafted by
and for the benefit of only one party. The popular, OSI-endorsed open source
licenses are drafted in the spirit of fairness, and with consideration to both
the licensor and the licensee. The intended fairness to all sides is beneficial
to both promoting adoption of open source licenses by licensors and the use of
open source software by licensees, thereby promoting the open source software
movement. There are a variety of open source licenses from which to choose and
each has differing emphasis and benefits, but open source licenses are
fundamentally intended to be an ethical multilateral contract that deliver on
the promise of software freedom.[^osifaq]

[^osilicenses]: Licenses & Standards, Open Source Initiative,
    https://opensource.org/licenses.

[^osifaq]: _See Which Open Source license is best?_, Open Source Initiative FAQ,
    [https://opensource.org/faq#which-license](https://opensource.org/faq#which-license)
    ("Unlike bilateral copyright licenses, which are negotiated between
    two parties and embody a truce between them for business purposes,
    multilateral copyright licenses — of which open source licenses are a
    kind — are "constitutions of communities", as Eben Moglen and others
    have observed. They express the consensus of how a community chooses
    to collaborate. They also embody its ethical assumptions, even if
    they are not explicitly enumerated. When that consensus includes
    giving permission to all to use, study improve and share the code
    without prejudice, the license is an open source license. The
    [Open Source Definition](https://opensource.org/definition) provides
    an objective test of evaluating that such a license is indeed an open
    source license and delivers the software freedom we all expect. Since
    licenses are the consensus of communities, it is natural that
    different communities will have different licenses, that communities
    with different norms will find fault with the licenses used by
    others, and that all will regard their way as optimum. The arguments
    over this will be as deep as the gulf between the philosophical
    positions of the communities involved. Ultimately, there is no
    license that is right for every community. Use the one that best
    aligns with your community's objectives and ethos."); _see also_
    Steven Weber, _The Success of Open Source_ at 84 (2004) ("The
    principal goal of the open source intellectual property regime is to
    maximize the ongoing use, growth, development, and distribution of
    free software. To achieve that goal, this regime shifts the
    fundamental optic of intellectual property rights away from
    protecting the prerogatives of an author toward protecting the
    prerogatives of generations of users.").

### Case Law {#case-law}

In the following case, _Cent. Stone Co. v. Warning_, a state court of appeals
evaluates the admissibility of prior extrinsic evidence to supplement a standard
form lease agreement.[^wyoming] The court considered the renter's argument for
_contra proferentum_ but as the lease failed to meet the "unconscionably unfair"
standard, the court upheld the trial court's consideration of parol evidence
when resolving the ambiguous term.

[^wyoming]: _Cent. Stone Co. v. Warning_, 412 S.W.3d 908 (Mo. Ct. App. 2013),
    _available at_ https://www.leagle.com/decision/inmoco20131105206.

#### _Cent. Stone Co. v. Warning_, 412 S.W.3d 908 (Mo. Ct. App. 2013) {#cent-stone-co-v-warning-412-s-w-3d-908-mo-ct-app-2013}

Daniel Warning ("Tenant") appeals from the judgment of the trial court awarding
$51,100 in damages to Central Stone Company ("Landlord") on its breach of
contract claim following a bench trial. Tenant contends that the trial court
improperly considered parol evidence in construing the lease executed on May 3,
2010 ("May 2010 Lease"). In the alternative, Tenant argues that if the May 2010
Lease is ambiguous, the trial court failed to construe it against the drafting
party, Landlord.

[ . . . . ]

This Court reviews the language of a lease de novo in order to determine the
parties' intent. _Brittany Sobery Family Ltd. P'ship v. Coinmach Corp._, 392
S.W.3d 46, 50 (Mo. App. 2013). When interpreting leases, this Court applies the
rules of construction governing contracts. _Id_. First we examine the plain and
ordinary meaning of the language used in the lease to determine if it clearly
addresses the disputed matter. _Id_. An ambiguity must come from within the four
corners of the contract; it cannot be created by the use of extrinsic, or parol,
evidence. _ATC Co., Inc. v. Myatt_, 389 S.W.3d 732, 735 (Mo. App. 2013).

The parol evidence rule is a substantive rule of law and not a rule of evidence.
_See Missouri Department of Transportation ex rel. PR Developers, Inc. v. Safeco
Insurance Company of America_, 97 S.W.3d 21, 32 (Mo. App. 2002). The parol
evidence rule does not prevent the admission of relevant evidence, but rather
prohibits the trier of fact from using such evidence to contradict, vary, or
alter the terms of an integrated written contract. _Id_. (quoting _State ex rel.
Missouri Highway and Transportation Commission v. Maryville Land Partnership_,
62 S.W.3d 485, 489 (Mo. App. 2011)). However, if the language of a lease is
ambiguous, courts will look to the language in the context of the entire lease
and parol evidence to ascertain the parties' intent. Coinmach, 392 S.W.3d at 50.
A contract is ambiguous or unclear if its language is reasonably susceptible to
more than one interpretation giving the words their plain and ordinary meaning
as understood by the average, reasonable person. _Id_. Once an ambiguity is
determined to exist, the parties' intent can be ascertained through the use of
extrinsic evidence. ATC Co., 389 S.W.3d at 735-36. Resolution of an ambiguity
through the use of extrinsic evidence is a question of fact. _Id_. at 736. Only
where there is no evidence showing the intent of the parties will we construe an
ambiguity against the party who drafted it. _Id_. If the contract is not an
adhesion contract, this Court will construe the contract against the drafting
party as a last resort, and only if there is no evidence of the parties' intent.
_Id_. at 737.

At first glance the May 2010 Lease would appear to be unambiguous about the date
of cash rent payment. It provides that "The cash rent shall be paid each year in
the following method: By April 1 of each year of the contract." However, the
opening paragraph of the May 2010 Lease states that:

    This lease is entered into May 3, 2010 between CENTRAL STONE COMPANY,
    Lessors at 46445 Sweetbay Lane, Hannibal, MO 63401 and DANIEL WARNING,
    Lessee at 32351 280th St., LaGrange MO 63448.

It also provided that the term of the lease was from January 1, 2010 to December
31, 2012.

Tenant argues that there is no ambiguity. We disagree. Looking within the four
corners of the May 2010 Lease, it is readily apparent that there is an inherent
ambiguity regarding when the cash rent is to paid for the first year of the
lease. The plain and ordinary language states that it is due on April 1 of each
year of the May 2010 Lease, but the agreement was entered into on May 3, 2010,
and it was to be effective from January 1, 2010. A payment date before the
execution of the contract is an impossibility. Hence there is some ambiguity
about when the cash rental for 2010 was due. The most likely payment date would
be when the lease was executed, given that the payment date was April 1, 2010,
as the first available date for it to be due would be May 3, 2010.[^payday]
Alternatively, it is also a reasonable interpretation that rent for 2010 was due
on December 31, 2010.[^due] At common law in Missouri, in the absence of any
agreement between the landlord and the tenant as to when rent is due and
payable, it is payable at the end of the year. _See Bashor v. Turpin_, 506
S.W.2d 412, 421 (Mo. 1974); _Ridgley v. Stillwell_, 27 Mo. 128 (1858); _Ostner
v. Lynn_, 57 Mo. App. 187 (1894). The trial court did not err in considering
evidence extrinsic to the May 2010 Lease regarding the issue of when the cash
rent was due for 2010.

[^payday]: Drafters of leases wherein the effective date and the specified date
    for annual payment are prior to the actual execution date of the
    lease could resolve the issue of the timing of the first lease
    payment by including a clause that specifies that the initial payment
    is due upon execution of the lease or some specific date thereafter.
    Such a specific contractual provision avoids ambiguity and/or
    defaulting to the common law regarding leases.

[^due]: Tenant's interpretation that no rent was due for 2010 because the
    payment date for that year was April 1, 2010, is unreasonable. Tenant
    was in possession of Oyster Farm from January 1, 2010 through December
    31, 2010. He did some preparation to farm the property. As of May 3,
    2010, when Tenant and Landlord executed the May 2010 Lease, he still
    planned to farm it. While he did not, in fact, plant crops on Oyster
    Farm in 2010, under his interpretation of the May 2010 Lease he still
    would not have owed rent even if he had successfully farmed the land.

Testimony at trial indicated that the intent of the parties was that the cash
rent payment for 2010 was due at the time of execution of the May 2010 Lease.
Sivill stated that it was a management decision not to ask Tenant for the rent
at the time of execution of the lease. Harsell testified that Tenant repeatedly
indicated throughout 2010 that he owed Landlord the cash rent for Oyster Farm
and needed to send Landlord a check. The trial court did not make a finding of
fact on this issue, and it would not affect the outcome if the trial court had
found that the cash rent was not due until the end of the year. Whether the rent
for 2010 was due on May 3, 2010 or on December 31, 2010, Tenant had not paid it
as of April 13, 2011.

Tenant argues in the alternative that the trial court erred in failing to
construe the ambiguity in the May 2010 Lease against the interest of the
drafter, Landlord, and interpret from the language of the May 2010 Lease that no
rent was due for 2010. Assuming arguendo that the May 2010 Lease was an adhesion
contract, the trial court did not err.[^err] Even with an adhesion contract, the
courts, as with all contracts,

    ...seek to enforce the reasonable expectations of the parties garnered
    not only from the words of a standardized form imposed by its proponent,
    but from the totality of the circumstances surrounding the transaction.
    Only such provisions of the standardized form which fail to comport with
    such reasonable expectations and which are unexpected and unconscionably
    unfair are held to be unenforceable. Because standardized contracts
    address the mass of users, the test for "reasonable expectations" is
    objective, addressed to the average member of the public who accepts
    such a contract, not the subjective expectations of an individual
    adherent.

[^err]: While the May 2010 Lease was based on a standardized lease form used by
    Landlord, it had been customized somewhat for Tenant. The evidence at
    trial suggests that the terms of the May 2010 Lease had been the subject
    of negotiations rather than presented to Tenant on a take it or leave it
    basis that is the essence of an adhesion contract. In early 2010 Tenant
    approached Landlord about extending the lease for Oyster Farm, due to
    terminate in 2010. Sivill told him that if he wanted to extend the
    lease, rent would have to be raised and the extension would be for
    another three years. The parties agreed to these terms.

_Hartland Computer Leasing Corp., Inc. v. Insurance Man, Inc._, 770 S.W.2d 525,
527 (Mo. App. 1989) (internal citations omitted). In the present case, the trial
court could have found, at best, that the cash rent was due at the end of the
year, as it had been under the prior lease and as it would have been under
common law. Such a finding would not have changed the judgment of the trial
court that awarded Landlord $51,100 for nonpayment of rent under the May 2010
Lease. Point denied.

The judgment of the trial court is affirmed.

**Discussion questions**

1.  Paragraph 7 of the
    [GNU General Public License v3](https://www.gnu.org/licenses/gpl-3.0.en.html)
    expressly states the types of additional terms that may be added to
    supplement the license. Except as expressly permitted, the GPL v3 prohibits
    the addition of "further restrictions" and states that any other additional
    terms will be unenforceable: "If the Program as you received it, or any part
    of it, contains a notice stating that it is governed by this License along
    with a term that is a further restriction, you may remove that term." The
    [Commons Clause](https://commonsclause.com/) exists to amend open source
    licenses to prohibit the commercial sale of the licensed
    software.[^commonsclause] If a licensor applying the GPL v3 adds a further
    restriction, such as the Commons Clause, how would a court determine the
    full text of the agreement? It is possible that the licensor and the
    licensee may have different understandings of whether the Commons Clause can
    be added to the text of the GPL v3. Would the GPL v3 and the Commons Clause
    be read together as a fully integrated agreement?

1.  Would a court potentially consider a corporate-authored rider to an open
    source license a contract of adhesion? Consider the power differential
    between the licensor and potential licensees, the lack of negotiation of the
    terms, the necessity of the software (or lack thereof), and whether the
    terms are "unconscionably unfair." For instance, consider the now-retired
    react PATENTS clause, which contained an attempt to deter patent lawsuits:
    "The license granted hereunder will terminate, automatically and without
    notice, if you (or any of your subsidiaries, corporate affiliates or agents)
    initiate directly or indirectly, or take a direct financial interest in, any
    Patent Assertion: (i) against Facebook or any of its subsidiaries or
    corporate affiliates, (ii) against any party if such Patent Assertion arises
    in whole or in part from any software, technology, product or service of
    Facebook or any of its subsidiaries or corporate affiliates, or (iii)
    against any party relating to the Software."[^fbpatents] What about the
    Crockford License, which was drafted solely by Douglas Crockford to release
    his JSMin software?[^jsmin] Crockford added the requirement that "the
    Software shall be used for Good, not Evil" to the open source MIT License,
    leaving complete ambiguity as to what the licensor or licensees may consider
    good or evil. Strictly speaking it is not an open source license because it
    discriminates by purpose and it does not appear in the list of OSI-endorsed
    open source licenses.[^good]

[^commonsclause]: The Commons Clause, License Condition v1.0,
    [https://commonsclause.com/](https://commonsclause.com/). For
    contrasting opinions on the Commons Clause, _compare_ Bradley
    M. Kuhn, _Software Freedom Ensures the True Software Commons_,
    Software Freedom Conservancy Blog,
    [https://sfconservancy.org/blog/2018/aug/22/commons-clause/](https://sfconservancy.org/blog/2018/aug/22/commons-clause/)
    (Aug. 22, 2018) (criticizing the Commons Clause), _with_ Salil
    Deshpande, _Commons Clause stops open-source abuse_,
    TechCrunch,
    [https://techcrunch.com/2018/09/07/commons-clause-stops-open-source-abuse/](https://techcrunch.com/2018/09/07/commons-clause-stops-open-source-abuse/)
    (Sept. 7, 2018).

[^fbpatents]: [https://web.archive.org/web/20170310090807/https://github.com/facebook/react/blob/master/PATENTS](https://web.archive.org/web/20170310090807/https://github.com/facebook/react/blob/master/PATENTS)

[^jsmin]: _See, e.g._, The JSON License,
    [https://www.json.org/license.html](https://www.json.org/license.html)
    ("The Software shall be used for Good, not Evil.").

[^good]: Open source licenses cannot discriminate as to the purposes the
    software may be used for. _See The Open Source Definition_, The Open
    Source Initiative ("6. No Discrimination Against Fields of Endeavor:
    The license must not restrict anyone from making use of the program in
    a specific field of endeavor. For example, it may not restrict the
    program from being used in a business, or from being used for genetic
    research.); _see also Licenses & Standards_, Open Source Initiative,
    https://www.json.org/license.html.

## Sources of Evidence Used in Interpretation {#sources-of-evidence-used-in-interpretation}

Under both the UCC and the Restatement (Second) of Contracts, a court will look
to the express terms the agreement to resolve an unclear or ambiguous term.
Historically courts were reluctant to look beyond the "four corners" of the
agreement.[^reluctant] However, contract law has evolved to admit other sources
of evidence to provide additional context.

[^reluctant]: The traditional "four corners" principle historically restrained
    courts from looking beyond the terms of an agreement in order to
    interpret its meaning. _See Black's Law Dictionary_ 299 (3rd
    Pocket ed. 2006) ("four corners rule. 1. The principle that a
    document's meaning is to be gathered from the entire document and
    not from its isolated parts. 2. The principle that no extraneous
    evidence should be used to interpret an unambiguous document.").

Courts give different weight to each of these sources of evidence. The greatest
weight is still given to the plain meaning of the words in the agreement itself
and contextual clues or definitions within the same document. Under both the UCC
and the Restatement, the language of the agreement is the first source of
evidence that a court will look to regardless of the existence of other
contextual evidence.[^contextual] If necessary, under both the UCC and the
Restatement a court may look to sources of evidence extrinsic to the agreement.
These sources include evidence of course of performance between the parties,
evidence of course of dealing between the parties, and lastly, evidence of trade
usage of the term. When the sources of evidence conflict, weight is assigned to
each of those sources in that same order.[^lastly]

[^contextual]: Restatement (Second) of Contracts § 203(b) (1981); U.C.C. §
    1-103(e) (2001); U.C.C. § 2-208 (2002).

[^lastly]: _See_ Restatement (Second) of Contracts § 203(b) (1981) ("Standard of
    Preference in Interpretation: In the interpretation of a promise or
    agreement or a term thereof, the following standards of preference
    are generally applicable: … (b) express terms are given greater
    weight than course of performance, course of dealing, and usage of
    trade, course of performance is given greater weight than course of
    dealing or usage of trade, and course of dealing is given greater
    weight than usage of trade . . . ."); U.C.C. § 1-303(e) (2001)
    ("Except as otherwise provided in subsection (f), the express terms
    of an agreement and any applicable course of performance, course of
    dealing, or usage of trade must be construed whenever reasonable as
    consistent with each other. If such a construction is unreasonable:
    (1) express terms prevail over course of performance, course of
    dealing, and usage of trade; (2) course of performance prevails over
    course of dealing and usage of trade; and (3) course of dealing
    prevails over usage of trade."); U.C.C. § 2-208(2) (2002) ("The
    express terms of the agreement and any such course of performance, as
    well as any course of dealing and usage of trade, shall be construed
    whenever reasonable as consistent with each other; but when such
    construction is unreasonable, express terms shall control course of
    performance and course of performance shall control both course of
    dealing and usage of trade. . . ").

### 1. Express Terms of the Agreement {#express-terms-of-the-agreement}

Courts first look to the words of the parties' written integrated agreement as
the source of truth for what the parties intended. If possible, a court will
view both the terms of the agreement and other sources of evidence as being
consistent with each other when resolving ambiguous terms. If the plain terms of
the agreement are not consistent with other sources of evidence, under both the
UCC and the Restatement, the language of the agreement is the most important
source of evidence.[^plainness] Courts examine both the ordinary, dictionary
meaning of the terms as well as contextual evidence from other terms within the
same document. In one famous case, _Frigaliment Imp. Co. v. B.N.S. Int'l Sales
Corp._, a court considered multiple sources of evidence in interpreting a
disputed term.[^frichickens] In determining the intent of the parties at the
time of contracting, the court gave the most weight to the evidence from the
agreement itself: the plain, dictionary meaning of the word "chicken," along
with the contextual evidence found within the rest of the agreement. Determining
that the word "chicken" standing alone in this contract was ambiguous, the court
found clues that the parties may have intended two different qualities of
chicken were contemplated at the time of contracting, because the two prices for
different amounts of chicken indicated that some of the chickens would be
cheaper than the others. However, the plaintiff's burden of proof and the
consistency of the evidence with the terms of the agreement factored into
whether the court considered this evidence when resolving ambiguity. The court
held that since the plaintiff's belief was not consistent with the plain
language of the agreement or the dictionary definition of "chicken," it did not
meet its burden of proof in establishing that the contract was for the higher
quality chicken.

[^plainness]: _See_ Restatement (Second) of Contracts § 203(b) (1981)
    ("[E]xpress terms are given greater weight than course of
    performance, course of dealing, and usage of trade . . ."); U.C.C.
    § 1-303(e) (2001) ("[E]xpress terms prevail over course of
    performance, course of dealing, and usage of trade").

[^frichickens]: _Frigaliment Imp. Co. v. B.N.S. Int'l Sales Corp._, 190 F.
    Supp. 116 (S.D.N.Y. 1960), _available at_
    https://cyber.harvard.edu/bridge/Cases/frigaliment.txt.htm.

#### _Frigaliment Imp. Co. v. B.N.S. Int'l Sales Corp._, 190 F. Supp. 116 (S.D.N.Y. 1960) {#frigaliment-imp-co-v-b-n-s-int'l-sales-corp-190-f-supp-116-s-d-n-y-1960}

The issue is, what is chicken? Plaintiff says "chicken" means a young chicken,
suitable for broiling and frying. Defendant says "chicken" means any bird of
that genus that meets contract specifications on weight and quality, including
what it calls "stewing chicken" and plaintiff pejoratively terms "fowl".
Dictionaries give both meanings, as well as some others not relevant here. To
support its, plaintiff sends a number of volleys over the net; defendant essays
to return them and adds a few serves of its own. Assuming that both parties were
acting in good faith, the case nicely illustrates Holmes' remark "that the
making of a contract depends not on the agreement of two minds in one intention,
but on the agreement of two sets of external signs—not on the parties' having
meant the same thing but on their having said the same thing." The Path of the
Law, in Collected Legal Papers, p. 178. I have concluded that plaintiff has not
sustained its burden of persuasion that the contract used "chicken" in the
narrower sense.

The action is for breach of the warranty that goods sold shall correspond to the
description, New York Personal Property Law, McKinney's Consol. Laws, c. 41, §
95. Two contracts are in suit. In the first, dated May 2, 1957, defendant, a New
York sales corporation, confirmed the sale to plaintiff, a Swiss corporation, of

    US Fresh Frozen Chicken, Grade A, Government Inspected,
    Eviscerated 2 1/2-3 lbs. and 1 1/2-2 lbs. each all chicken individually
    wrapped in cryovac, packed in secured fiber cartons or wooden boxes,
    suitable for export 75,000 lbs. 2 1/2-3 lbs.... §$ 33.00 25,000 lbs.
    1 1/2-2 lbs....§$ 36.50 per 100 lbs. FAS New York scheduled May 10, 1957
    pursuant to instructions from Penson & Co., New York.

[^inspected]

[^inspected]: The Court notes the contract provision whereby any disputes are to
    be settled by arbitration by the New York Produce Exchange; it
    treats the parties' failure to avail themselves of this remedy as
    an agreement eliminating that clause of the contract.

The second contract, also dated May 2, 1957, was identical save that only 50,000
lbs. of the heavier 'chicken' were called for, the price of the smaller birds
was $ 37 per 100 lbs., and shipment was scheduled for May 30. The initial
shipment under the first contract was short but the balance was shipped on May
17. When the initial shipment arrived in Switzerland, plaintiff found, on May
28, that the 2 1/2-3 lbs. birds were not young chicken suitable for broiling and
frying but stewing chicken or 'fowl'; indeed, many of the cartons and bags
plainly so indicated. Protests ensued. Nevertheless, shipment under the second
contract was made on May 29, the 2 1/2-3 lbs. birds again being stewing chicken.
Defendant stopped the transportation of these at Rotterdam.

This action followed. Plaintiff says that, notwithstanding that its acceptance
was in Switzerland, New York law controls under the principle of _Rubin v.
irving Trust Co._, 1953, 305 N.Y. 288, 305, 113 N.E.2d 424, 431; defendant does
not dispute this, and relies on New York decisions. I shall follow the apparent
agreement of the parties as to the applicable law.

Since the word 'chicken' standing alone is ambiguous, I turn first to see
whether the contract itself offers any aid to its interpretation. Plaintiff says
the 1 1/2-2 lbs. birds necessarily had to be young chicken since the older birds
do not come in that size, hence the 2 1/2-3 lbs. birds must likewise be young.
This is unpersuasive -- a contract for 'apples' of two different sizes could be
filled with different kinds of apples even though only one species came in both
sizes. Defendant notes that the contract called not simply for chicken but for
'US Fresh Frozen Chicken, Grade A, Government Inspected.' It says the contract
thereby incorporated by reference the Department of Agriculture's regulations,
which favor its interpretation; I shall return to this after reviewing
plaintiff's other contentions.

The first hinges on an exchange of cablegrams which preceded execution of the
formal contracts. The negotiations leading up to the contracts were conducted in
New York between defendant's secretary, Ernest R. Bauer, and a Mr. Stovicek, who
was in New York for the Czechoslovak government at the World Trade Fair. A few
days after meeting bauer at the fair, Stovicek telephoned and inquired whether
defendant would be interested in exporting poultry to Switzerland. Bauer then
met with Stovicek, who showed him a cable from plaintiff dated April 26, 1957,
announcing that they 'are buyer' of 25,000 lbs. of chicken 2 1/2-3 lbs. weight,
Cryovac packed, grade A Government inspected, at a price up to 33 cents per
pound, for shipment on May 10, to be confirmed by the following morning, and
were interested in further offerings. After testing the market for price, Bauer
accepted, and Stovicek sent a confirmation that evening. Plaintiff stresses
that, although these and subsequent cables between plaintiff and defendant,
which laid the basis for the additional quantities under the first and for all
of the second contract, were predominantly in German, they used the English word
'chicken'; it claims this was done because it understood 'chicken' meant young
chicken whereas the German word, 'Huhn,' included both 'Brathuhn' (broilers) and
'Suppenhuhn' (stewing chicken), and that defendant, whose officers were
thoroughly conversant with German, should have realized this. Whatever force
this argument might otherwise have is largely drained away by Bauer's testimony
that he asked Stovicek what kind of chickens were wanted, received the answer
'any kind of chickens,' and then, in German, asked whether the cable meant
'Huhn' and received an affirmative response. Plaintiff attacks this as contrary
to what Bauer testified on his deposition in March, 1959, and also on the ground
that Stovicek had no authority to interpret the meaning of the cable. The first
contention would be persuasive if sustained by the record, since Bauer was free
at the trial from the threat of contradiction by Stovicek as he was not at the
time of the deposition; however, review of the deposition does not convince me
of the claimed inconsistency. As to the second contention, it may well be that
Stovicek lacked authority to commit plaintiff for prices or delivery dates other
than those specified in the cable; but plaintiff cannot at the same time rely on
its cable to Stovicek as its dictionary to the meaning of the contract and
repudiate the interpretation given the dictionary by the man in whose hands it
was put. _See Restatement of the Law of Agency_, 2d, § 145; 2 Mecham, Agency §
1781 (2d ed. 1914); _Park v. Moorman Mfg. co._, 1952, 121 Utah 339 241 P.2d 914,
919, 40 A.L.R.2d 273; _Henderson v. Jimmerson_, Tex.Civ.App.1950, 234 S.W.2d
710, 717-718. Plaintiff's reliance on the fact that the contract forms contain
the words 'through the intermediary of: ', with the blank not filled, as
negating agency, is wholly unpersuasive; the purpose of this clause was to
permit filling in the name of an intermediary to whom a commission would be
payable, not to blot out what had been the fact.

Plaintiff's next contention is that there was a definite trade usage that
'chicken' meant 'young chicken.' Defendant showed that it was only beginning in
the poultry trade in 1957, thereby bringing itself within the principle that
'when one of the parties is not a member of the trade or other circle, his
acceptance of the standard must be made to appear' by proving either that he had
actual knowledge of the usage or that the usage is 'so generally known in the
community that his actual individual knowledge of it may be inferred.' 9
Wigmore, Evidence (3d ed. § 1940) 2464. Here there was no proof of actual
knowledge of the alleged usage; indeed, it is quite plain that defendant's
belief was to the contrary. In order to meet the alternative requirement, the
law of New York demands a showing that 'the usage is of so long continuance, so
well established, so notorious, so universal and so reasonable in itself, as
that the presumption is violent that the parties contracted with reference to
it, and made it a part of their agreement.' _Walls v. Bailey, 1872_, 49 N.Y.
464, 472-473.

Plaintiff endeavored to establish such a usage by the testimony of three
witnesses and certain other evidence. Strasser, resident buyer in New York for a
large chain of Swiss cooperatives, testified that 'on chicken I would definitely
understand a broiler.' However, the force of this testimony was considerably
weakened by the fact that in his own transactions the witness, a careful
businessman, protected himself by using 'broiler' when that was what he wanted
and 'fowl' when he wished older birds. Indeed, there are some indications,
dating back to a remark of _Lord Mansfield, Edie v. East India Co._, 2 Burr.
1216, 1222 (1761), that no credit should be given 'witnesses to usage, who could
not adduce instances in verification.' 7 Wigmore, Evidence (3d ed. 1940), §
1954; _see McDonald v. Acker, Merrall & Condit Co._, 2d Dept.1920, 192 App. Div.
123, 126, 182 N.Y.S. 607. While Wigmore thinks this goes too far, a witness'
consistent failure to rely on the alleged usage deprives his opinion testimony
of much of its effect. Niesielowski, an officer of one of the companies that had
furnished the stewing chicken to defendant, testified that 'chicken' meant 'the
male species of the poultry industry. That could be a broiler, a fryer or a
roaster', but not a stewing chicken; however, he also testified that upon
receiving defendant's inquiry for 'chickens', he asked whether the desire was
for 'fowl or frying chickens' and, in fact, supplied fowl, although taking the
precaution of asking defendant, a day or two after plaintiff's acceptance of the
contracts in suit, to change its confirmation of its order from 'chickens,' as
defendant had originally prepared it, to 'stewing chickens.' Dates, an employee
of Urner-Barry Company, which publishes a daily market report on the poultry
trade, gave it as his view that the trade meaning of 'chicken' was 'broilers and
fryers.' In addition to this opinion testimony, plaintiff relied on the fact
that the Urner-Barry service, the Journal of Commerce, and Weinberg Bros. & Co.
of Chicago, a large supplier of poultry, published quotations in a manner which,
in one way or another, distinguish between 'chicken,' comprising broilers,
fryers and certain other categories, and 'fowl,' which, Bauer acknowledged,
included stewing chickens. This material would be impressive if there were
nothing to the contrary. However, there was, as will now be seen.

Defendant's witness Weininger, who operates a chicken eviscerating plant in New
Jersey, testified 'Chicken is everything except a goose, a duck, and a turkey.
Everything is a chicken, but then you have to say, you have to specify which
category you want or that you are talking about.' Its witness Fox said that in
the trade 'chicken' would encompass all the various classifications. Sadina, who
conducts a food inspection service, testified that he would consider any bird
coming within the classes of 'chicken' in the Department of Agriculture's
regulations to be a chicken. The specifications approved by the General Services
Administration include fowl as well as broilers and fryers under the
classification 'chickens.' Statistics of the Institute of American Poultry
Industries use the phrases 'Young chickens' and 'Mature chickens,' under the
general heading 'Total chickens.' and the Department of Agriculture's daily and
weekly price reports avoid use of the word 'chicken' without specification.

Defendant advances several other points which it claims affirmatively support
its construction. Primary among these is the regulation of the Department of
Agriculture, 7 C.F.R. § 70.300-70.370, entitled, 'Grading and Inspection of
Poultry and Edible Products Thereof.' and in particular 70.301 which recited:

    Chickens. The following are the various classes of chickens:
    (a) Broiler or fryer . . . (b) Roaster . . . (c) Capon . . . (d) Stag . . .
    (e) Hen or stewing chicken or fowl . . . (f) Cock or old rooster . . .

Defendant argues, as previously noted, that the contract incorporated these
regulations by reference. Plaintiff answers that the contract provision related
simply to grade and Government inspection and did not incorporate the Government
definition of 'chicken,' and also that the definition in the Regulations is
ignored in the trade. However, the latter contention was contradicted by
Weininger and Sadina; and there is force in defendant's argument that the
contract made the regulations a dictionary, particularly since the reference to
Government grading was already in plaintiff's initial cable to Stovicek.

Defendant makes a further argument based on the impossibility of its obtaining
broilers and fryers at the 33 cents price offered by plaintiff for the 2 1/2-3
lbs. birds. There is no substantial dispute that, in late April, 1957, the price
for 2 1/2-3 lbs. broilers was between 35 and 37 cents per pound, and that when
defendant entered into the contracts, it was well aware of this and intended to
fill them by supplying fowl in these weights. It claims that plaintiff must
likewise have known the market since plaintiff had reserved shipping space on
April 23, three days before plaintiff's cable to Stovicek, or, at least, that
Stovicek was chargeable with such knowledge. It is scarcely an answer to say, as
plaintiff does in its brief, that the 33 cents price offered by the 2 1/2-3 lbs.
'chickens' was closer to the prevailing 35 cents price for broilers than to the
30 cents at which defendant procured fowl. Plaintiff must have expected
defendant to make some profit -- certainly it could not have expected defendant
deliberately to incur a loss.

Finally, defendant relies on conduct by the plaintiff after the first shipment
had been received. On May 28 plaintiff sent two cables complaining that the
larger birds in the first shipment constituted 'fowl.' Defendant answered with a
cable refusing to recognize plaintiff's objection and announcing 'We have today
ready for shipment 50,000 lbs. chicken 2 1/2-3 lbs. 25,000 lbs. broilers 1 1/2-2
lbs.,' these being the goods procured for shipment under the second contract,
and asked immediate answer 'whether we are to ship this merchandise to you and
whether you will accept the merchandise.' After several other cable exchanges,
plaintiff replied on May 29 'Confirm again that merchandise is to be shipped
since resold by us if not enough pursuant to contract chickens are shipped the
missing quantity is to be shipped within ten days stop we resold to our
customers pursuant to your contract chickens grade A you have to deliver us said
merchandise we again state that we shall make you fully responsible for all
resulting costs.'[^germanchicken] Defendant argues that if plaintiff was sincere
in thinking it was entitled to young chickens, plaintiff would not have allowed
the shipment under the second contract to go forward, since the distinction
between broilers and chickens drawn in defendant's cablegram must have made it
clear that the larger birds would not be broilers. However, plaintiff answers
that the cables show plaintiff was insisting on delivery of young chickens and
that defendant shipped old ones at its peril. Defendant's point would be highly
relevant on another disputed issue -- whether if liability were established, the
measure of damages should be the difference in market value of broilers and
stewing chicken in New York or the larger difference in Europe, but I cannot
give it weight on the issue of interpretation. Defendant points out also that
plaintiff proceeded to deliver some of the larger birds in Europe, describing
them as 'poulets'; defendant argues that it was only when plaintiff's customers
complained about this that plaintiff developed the idea that 'chicken' meant
'young chicken.' There is little force in this in view of plaintiff's immediate
and consistent protests.

[^germanchicken]: These cables were in German; "chicken", "broilers" and, on
    some occasions, "fowl," were in English.

When all the evidence is reviewed, it is clear that defendant believed it could
comply with the contracts by delivering stewing chicken in the 2 1/2-3 lbs.
size. Defendant's subjective intent would not be significant if this did not
coincide with an objective meaning of 'chicken.' Here it did coincide with one
of the dictionary meanings, with the definition in the Department of Agriculture
Regulations to which the contract made at least oblique reference, with at least
some usage in the trade, with the realities of the market, and with what
plaintiff's spokesman had said. Plaintiff asserts it to be equally plain that
plaintiff's own subjective intent was to obtain broilers and fryers; the only
evidence against this is the material as to market prices and this may not have
been sufficiently brought home. In any event it is unnecessary to determine that
issue. For plaintiff has the burden of showing that 'chicken' was used in the
narrower rather than in the broader sense, and this it has not sustained.

This opinion constitutes the Court's findings of fact and conclusions of law.
Judgment shall be entered dismissing the complaint with costs.

**Discussion**

1.  Where a contract does not capture the intent of two parties bound by the
    agreement, is the contextual logic of _Frigaliment_ as relevant? For
    instance, if a downstream licensee developer builds on GPL-licensed
    software, would a court still look to the plain text meaning of an agreement
    as the clearest indicator of the parties' intent? How relevant is the
    original intent when the downstream developer did not participate in the
    drafting or selection of the license?

### 2. Course of Performance & Waiver {#course-of-performance-&-waiver}

A court may look to consistent evidence of the parties' behavior after the
formation of the agreement, also known as "course of performance" evidence, in
order to supplement the understanding of the express terms of the
agreement.[^performancechickens] When course of performance evidence is
inconsistent with the express terms of the agreement, the terms of the agreement
will prevail. When course of performance evidence is inconsistent with course of
dealing or trade usage evidence, course of performance evidence is given more
weight.[^chickenbalance]

[^performancechickens]: U.C.C. § 1-103(a) (2001) ("A 'course of performance' is
    a sequence of conduct between the parties to a
    particular transaction that exists if: (1) the agreement
    of the parties with respect to the transaction involves
    repeated occasions for performance by a party; and (2)
    the other party, with knowledge of the nature of the
    performance an opportunity for objection to it, accepts
    the performance or acquiesces in it without
    objection."); U.C.C. § 1-103(e) (2001); U.C.C. § 2-208
    (2002); Restatement (Second) of Contracts § 202(4)
    (1981) ("Where an agreement involves repeated occasions
    for performance by either party with knowledge of the
    nature of the performance and opportunity for objection
    to it by the other, any course of performance accepted
    or acquiesced in without objection is given great weight
    in the interpretation of the agreement.").

[^chickenbalance]: _See_ Restatement (Second) of Contracts § 203(b) (1981)
    ("[C]ourse of performance is given greater weight than course
    of dealing or usage of trade . . ."); U.C.C. § 1-303(e)
    (2001) ("[C]ourse of performance prevails over course of
    dealing and usage of trade.").

Course of performance evidence is based on the assumption that the accepting
behavior indicates what must have been intended by the parties' use of a term at
the time of contracting.

For instance, if Party A performs a contract according to one possible meaning
of an ambiguous term, and Party B does not object, then that would be considered
evidence that both parties understood the ambiguous term to have Party A's
meaning when they signed the agreement.

The concept of course of performance evidence applies awkwardly to interpreting
open source licenses. Open source licensors and licensees are generally
performing contracts that they had no hand in drafting. Licensees initiate the
binding contract by performing under the terms of the stated license and it is
unlikely that the licensor is having any discussion with the licensees about the
license terms when they begin copying or using the open source software. Thus
the logic of course of performance evidence is warped here, and evidence of
licensees' performance would fail to indicate any shared understanding of an
ambiguous term at the time of contracting.

However, the related concepts of waiver and course of performance also come into
play when examining a party's performance of a contract. In the following case,

_Nanakuli Paving & Rock Co. v. Shell Oil Co._, a court applies the UCC and
examines the application of the waiver and course of performance evidence to an
obligation outside of the express terms of the agreement itself.[^nanakuli]
While course of performance evidence illuminates what was intended by the
parties at the time of contracting, post-agreement conduct can also constitute a
waiver or modification of the contract.[^aloha] The _Nanakuli_ court extensively
discussed the UCC's more lenient treatment of parol evidence to discern the
intent of the parties, citing _Cosmopolitan Financial Corp. v. Runnels_ for the
proposition that "we think that expansion of the liberal approach toward the
receipt of extrinsic evidence, in the face of the proliferation of standard form
contracts and commercial paper, gives the courts a wider insight into the real
intent of the parties."[^hawaii] As you read the following case, consider
whether this logic applies to the interpretation of ambiguous terms in open
source licenses.

[^nanakuli]: _Nanakuli Paving & Rock Co. v. Shell Oil Co._, 664 F.2d 772 (9th
    Cir. 1982), _available at_
    https://law.resource.org/pub/us/case/reporter/F2/664/664.F2d.772.78-2670.78-2667.html.

[^aloha]: _See_ Brian A. Blum, _Examples and Explanations: Contracts_ 315 n.11
    (5th ed. 2011) ("It can be difficult to distinguish a course of
    performance, which casts light on what the parties meant at the time
    of contracting, from post-formation conduct that is either a waiver of
    rights or a modification of the contract.").

[^hawaii]: _Id._ _citing_ _Cosmopolitan Financial Corp. v. Runnels_, 29 P.2d 390
    (1981); _see also Hunt Foods, Inc. v. Doliner_, 26 App.Div.2d 41, 270
    N.Y.S.2d 937 (1966); _Zwierzycki v. Owens_, 499 P.2d 996 (Wyo. 1972);
    _General Equipment Manufacturers v. Bible Press, Inc._, 10 Mich. App.
    676, 160 N.W.2d 370 (1968); _Golden Gate Corporation v. Barrington
    College_, 98 R.I. 35, 199 A.2d 586 (1974).

#### _Nanakuli Paving & Rock Co. v. Shell Oil Co., 664 F.2d 772_ (9th Cir. 1982) {#nanakuli-paving-&-rock-co-v-shell-oil-co-664-f-2d-772-9th-cir-1982}

Appeal from the United States District Court for the District of Hawaii.

Before BROWNING, Chief Judge, and KENNEDY, Circuit Judge, and HOFFMAN, District
Judge.

HOFFMAN, District Judge:

Appellant Nanakuli Paving and Rock Company (Nanakuli) initially filed this
breach of contract action against appellee Shell Oil Company (Shell) in Hawaiian
State Court in February, 1976.[^appellee] Nanakuli, the second largest asphaltic
paving contractor in Hawaii, had bought all its asphalt requirements from 1963
to 1974 from Shell under two long-term supply contracts; its suit charged Shell
with breach of the later 1969 contract.[^longterm] The jury returned a verdict
of $220,800 for Nanakuli on its first claim, which is that Shell breached the
1969 contract in January, 1974, by failing to price protect Nanakuli on 7200
tons of asphalt at the time Shell raised the price for asphalt from $44 to
$76.[^asphalt] Nanakuli's theory is that price-protection, as a usage of the
asphaltic paving trade in Hawaii, was incorporated into the 1969 agreement
between the parties, as demonstrated by the routine use of price protection by
suppliers to that trade, and reinforced by the way in which Shell actually
performed the 1969 contract up until 1974. Price protection, appellant claims,
required that Shell hold the price on the tonnage Nanakuli had already committed
because Nanakuli had incorporated that price into bids put out to or contracts
awarded by general contractors and government agencies. The District Judge set
aside the verdict and granted Shell's motion for judgment n. o. v., which
decision we vacate. We reinstate the jury verdict because we find that, viewing
the evidence as a whole, there was substantial evidence to support a finding by
reasonable jurors that Shell breached its contract by failing to provide
protection for Nanakuli in 1974. _Quichocho v. Kelvinator Corp._, 546 F.2d 812,
813 (9th Cir. 1976). We do not believe the evidence in this case was such that,
giving Nanakuli the benefit of all inferences fairly supported by the evidence
and without weighing the credibility of the witnesses, only one reasonable
conclusion could have been reached by the jury. _Cockrum v. Whitney_, 479 F.2d
84, 85-86 (9th Cir. 1973).

[^appellee]: Shell removed the suit to United States District Court for the
    District of Hawaii on March 2 of that year

[^longterm]: The parties agree this act is governed by the Uniform Commercial
    Code, as enacted in Hawaii Rev.Stat. § 490:1-101 et seq.

[^asphalt]: Although the jury found for Nanakuli on its price protection claim,
    it denied Nanakuli recovery on its other two claims: that Shell
    should have paid commissions and discounts on asphalt Nanakuli was
    forced to buy elsewhere when Shell did not fulfill its needs and
    that Shell should be made to reimburse Nanakuli for profits lost
    when Nanakuli had to forego contracts already signed because Shell
    did not supply enough asphalt in 1974

Nanakuli offers two theories for why Shell's failure to offer price protection
in 1974 was a breach of the 1969 contract. First, it argues, all material
suppliers to the asphaltic paving trade in Hawaii followed the trade usage of
price protection and thus it should be assumed, under the U.C.C., that the
parties intended to incorporate price protection into their 1969 agreement. This
is so, Nanakuli continues, even though the written contract provided for price
to be "Shell's Posted Price at time of delivery," F.O.B. Honolulu. Its proof of
a usage that was incorporated into the contract is reinforced by evidence of the
commercial context, which under the U.C.C. should form the background for
viewing a particular contract. The full agreement must be examined in light of
the close, almost symbiotic relations between Shell and Nanakuli on the island
of Oahu, whereby the expansion of Shell on the island was intimately connected
to the business growth of Nanakuli. The U.C.C. looks to the actual performance
of a contract as the best indication of what the parties intended those terms to
mean. Nanakuli points out that Shell had price protected it on the two occasions
of price increases under the 1969 contract other than the 1974 increase. In 1970
and 1971 Shell extended the old price for four and three months, respectively,
after an announced increase. This was done, in the words of Shell's agent in
Hawaii, in order to permit Nanakuli's to "chew up" tonnage already committed at
Shell's old price.[^chew]

[^chew]: Price protection was practiced in the asphaltic paving trade by either
    extending the old price for a period of time after a new one went into
    effect or charging the old price for a specified tonnage, which
    represented work committed at the old price. In addition, several
    months' advance notice was given of price increases

Nanakuli's second theory for price protection is that Shell was obliged to price
protect Nanakuli, even if price protection was not incorporated into their
contract, because price protection was the commercially reasonable standard for
fair dealing in the asphaltic paving trade in Hawaii in 1974. Observance of
those standards is part of the good-faith requirement that the Code imposes on
merchants in performing a sales contract. Shell was obliged to price protect
Nanakuli in order to act in good faith, Nanakuli argues, because such a practice
was universal in that trade in that locality.

Shell presents three arguments for upholding the judgment n. o. v. or, on cross
appeal, urging that the District Judge erred in admitting certain evidence.
First, it says, the District Court should not have denied Shell's motion in
limine to define trade, for purposes of trade usage evidence, as the sale and
purchase of asphalt in Hawaii, rather than expanding the definition of trade to
include other suppliers of materials to the asphaltic paving trade. Asphalt, its
argument runs, was the subject matter of the disputed contract and the only
product Shell supplied to the asphaltic paving trade.[^product] Shell protests
that the judge, by expanding the definition of trade to include the other major
suppliers to the asphaltic paving trade, allowed the admission of highly
prejudicial evidence of routine price protection by all suppliers of
aggregate.[^prejudicial] Asphaltic concrete paving is formed by mixing paving
asphalt with crushed rock, or aggregate, in a "hot-mix" plant and then pouring
the mixture onto the surface to be paved. Shell's second complaint is that the
two prior occasions on which it price protected Nanakuli, although representing
the only other instances of price increases under the 1969 contract, constituted
mere waivers of the contract's price term, not a course of performance of the
contract. A course of performance of the contract, in contrast to a waiver,
demonstrates how the parties understand the terms of their agreement. Shell
cites two U.C.C. Comments in support of that argument: (1) that, when the
meaning of acts is ambiguous, the preference is for the waiver interpretation,
and (2) that one act alone does not constitute a relevant course of performance.
Shell's final argument is that, even assuming its prior price protection
constituted a course of performance and that the broad trade definition was
correct and evidence of trade usages by aggregate suppliers was admissible,
price protection could not be construed as reasonably consistent with the
express price term in the contract, in which case the Code provides that the
express term controls.

[^product]: Shell's argument would, in effect, eliminate all trade usage
    evidence. First, it argues that its own acts were irrelevant as mere
    waivers, not acts in the course of the performance of the contract.
    Second, it contends that all acts of price protection by the only
    other asphalt supplier in Hawaii, Chevron, the marketing division of
    Standard Oil Company, were irrelevant to prove trade usage because
    Chevron at one time owned all or part of the paving company it
    supplied and routinely price protected Hawaiian Bitumuls (H.B.). The
    court correctly refused to bar that evidence since the one-time
    relationship between the two went to the weight, not the
    admissibility, of the evidence. Nanakuli was given permission to
    offer evidence in rebuttal that Chevron price protected other
    customers in California with whom it had no such relationship in the
    event Shell tried to impeach that evidence

[^prejudicial]: The judge excluded evidence of price protection usage by
    suppliers of cement because cement was too infrequently used in
    the production of asphaltic paving and, when used, formed too
    small a percentage of the finished product

We hold that the judge did not abuse his discretion in defining the applicable
trade, for purposes of trade usages, as the asphaltic paving trade in Hawaii,
rather than the purchase and sale of asphalt alone, given the unusual, not to
say unique, circumstances: the smallness of the marketplace on Oahu; the
existence of only two suppliers on the island; the long and intimate connection
between the two companies on Oahu, including the background of how the
development of Shell's asphalt sales on Oahu was inextricably linked to
Nanakuli's own expansion on the island; the knowledge of the aggregate business
on the part of Shell's Hawaiian representative, Bohner; his awareness of the
economics of Nanakuli's bid estimates, which included only two major materials,
asphalt and aggregate; his familiarity with realities of the Hawaiian
marketplace in which all government agencies refused to include escalation
clauses in contract awards and thus pavers would face tremenduous losses on
price increases if all their material suppliers did not routinely offer them
price protection; and Shell's determination to build Nanakuli up to compete for
those lucrative government contracts with the largest paver on the island,
Hawaiian Bitumuls (H.B.), which was supplied by the only other asphalt company
on the islands, Chevron, and which was routinely price protected on materials.
We base our holding on the reading of the Code Comments as defining trade more
broadly than transaction and as binding parties not only to usages of their
particular trade but also to usages of trade in general in a given locality.
This latter seems an equitable application of usage evidence where the usage is
almost universally practiced in a small market such as was Oahu in the 1960's
before Shell signed its 1969 contract with Nanakuli.[^oahu] Additionally, we
hold that, under the facts of this case, a jury could reasonably have found that
Shell's acts on two occasions to price protect Nanakuli were not ambiguous and
therefore indicated Shell's understanding of the terms of the agreement with
Nanakuli rather than being a waiver by Shell of those terms.[^jury]

[^oahu]: We uphold the court's ruling to admit evidence of trade usage after
    1969 to show that Nanakuli's expectation that Shell would go along with
    that usage was justified, given the continued practice of price
    protection by all suppliers after 1969. We decline to decide whether
    the Code allows such admission under normal circumstances, a practice
    which may well lead to confusion of the issue, but we uphold the ruling
    as harmless error given the admissibility of evidence of post-1969
    price protection by Shell and Chevron as evidence of good faith by
    Shell in 1974 and the harmless nature of the minimal evidence of price
    protection by aggregate suppliers after 1969. See textual discussion
    infra

[^jury]: In addition, Shell's Bohner volunteered on direct for Shell that Shell
    price protected Nanakuli again after 1974 on the only two occasions of
    later price increases in 1977 and 1978. Although not constituting a
    course of performance, since the occasions took place under different
    contracts, these two additional instances of price protection could
    have reinforced the jury's impression that Shell's earlier actions were
    a carrying out of the price term

Lastly we hold that, although the express price terms of Shell's posted price of
delivery may seem, at first glance, inconsistent with a trade usage of price
protection at time of increases in price, a closer reading shows that the jury
could have reasonably construed price protection as consistent with the express
term. We reach this holding for several reasons. First, we are persuaded by a
careful reading of the U.C.C., one of whose underlying purposes is to promote
flexibility in the expansion of commercial practices and which rather
drastically overhauls this particular area of the law. The Code would have us
look beyond the printed pages of the contract to usages and the entire
commercial context of the agreement in order to reach the "true understanding"
of the parties. Second, decisions of other courts in similar situations have
managed to reconcile such trade usages with seemingly contradictory express
terms where the prior course of dealings between the parties, trade usages, and
the actual performance of the contract by the parties showed a clear intent by
the parties to incorporate those usages into the agreement or to give to the
express term the particular meaning provided by those usages, even at times
varying the apparent meaning of the express terms. Third, the delineation by
thoughtful commentators of the degree of consistency demanded between express
terms and usage is that a usage should be allowed to modify the apparent
agreement, as seen in the written terms, as long as it does not totally negate
it. We believe the usage here falls within the limits set forth by commentators
and generally followed in the better reasoned decisions. The manner in which
price protection was actually practiced in Hawaii was that it only came into
play at times of price increases and only for work committed prior to those
increases on non-escalating contracts. Thus, it formed an exception to, rather
than a total negation of, the express price term of "Shell's Posted Price at
time of delivery." Our decision is reinforced by the overwhelming nature of the
evidence that price protection was routinely practiced by all suppliers in the
small Oahu market of the asphaltic paving trade and therefore was known to
Shell; that it was a realistic necessity to operate in that market and thus
vital to Nanakuli's ability to get large government contracts and to Shell's
continued business growth on Oahu; and that it therefore constituted an intended
part of the agreement, as that term is broadly defined by the Code, between
Shell and Nanakuli.

[ . . . . ]

III

Shell's Course Of Performance Of The 1969 Contract

The Code considers actual performance of a contract as the most relevant
evidence of how the parties interpreted the terms of that contract. In 1970 and
1971, the only points at which Shell raised prices between 1969 and 1974, it
price protected Nanakuli by holding its old price for four and three months,
respectively, after announcing a price increase. In the late summer of 1970,
Shell had announced a price increase from $35 to $40 a ton effective September
1, 1970. When Nanakuli protested to Bohner that it should be price protected on
work already committed, Blee wrote Bohner an in-house memo that, if Bohner could
not "convince" Nanakuli to go along with the price increase on September 1, he
should try to "bargain" to get Nanakuli to accept the price raise by at least
the first of the year, which was what was finally agreed upon. During that
four-month period, Nanakuli bought 3,300 tons. Shell announced a second increase
in October, 1970, from $40 to $42 effective December 31st. Before that increase
went into effect, on November 25 Shell increased the raise to $4, making the
price $44 as of the first of the year.[^raise] Shell again agreed to price
protect Nanakuli by holding the price at $40, which had been the official price
since September 1, for three months from January to March, 1971. Shell did not
actually raise prices again until January, 1974, but at several points it
believed that increases would be necessary and gave several months' advance
notice of those possible increases. Those actions were in accord with Shell's
own policy, as professed by Bohner, and that of other asphalt and aggregate
suppliers: to give at least several months' advance notice of price increases.
On January 14, 1971, Shell wrote its asphalt customers that the maximum 1971
increase would be to $46. On July 9, 1971, another letter promised the price
would not go over $50 in 1972. In addition, Bohner volunteered on direct the
information that Shell price protected Nanakuli on the only two occasions of
price increases after 1974 by giving 6 months' advance notice in 1977 and 3 or 4
months' advance notice in 1978, a practice he described as "in effect carryover
pricing," his term for price protection. By its actions, Bohner testified, Shell
allowed Nanakuli time to make arrangements to buy up tonnage committed at the
old price, that is, to "chew up" tonnage bid or contracted. Shell apparently
offered this testimony to impress the jury with its subsequent good faith toward
Nanakuli. In fact, it also may have reinforced the impression of the
universality of price protection in the asphaltic paving trade on Oahu and, by
showing Shell's adherence to that practice on every relevant occasion except
1974, have highlighted for the jury what was the commercially reasonable
standard of fair dealing in effect on Oahu in 1974.

[^raise]: That November letter also announced a "new pricing policy" of Shell,
    setting out a requirement that firm contractual commitments be made
    with Shell within 15 days of accepting a bid

IV

Shell-Nanakuli Relations, 1973-74

Two important factors form the backdrop for the 1974 failure by Shell to price
protect Nanakuli: the Arab oil embargo and a complete change of command and
policy in Shell's asphalt management. The jury was read a page or so from the
World Book about the events and effect of the partial oil embargo, which
shortened supplies and increased the price of petroleum, of which asphalt is a
byproduct. The federal government imposed direct price controls on petroleum,
but not on asphalt. Despite the international importance of those events, the
jury may have viewed the second factor as of more direct significance to this
case. The structural changes at Shell offered a possible explanation for why
Shell in 1974 acted out of step with, not only the trade usage and commercially
reasonable practices of all suppliers to the asphaltic paving trade on Oahu, but
also with its previous agreement with, or at least treatment of, Nanakuli.

Bohner testified to a big organizational change at Shell in 1973 when asphalt
sales were moved from the construction sales to the commercial sales department.
In addition, by 1973 the top echelon of Shell's asphalt sales had retired. Lewis
and Blee, who had negotiated the 1969 contract with Nanakuli, were both
gone.[^retired] Their duties were taken over by three men: Fuller in San Mateo,
California, District Manager for Shell Sales, Lawson, and Chippendale, who was
Shell's regional asphalt manager in Houston. When the philosophy toward asphalt
pricing changed, apparently no one was left who was knowledgeable about the
peculiarities of the Hawaiian market or about Shell's long-time relations with
Nanakuli or its 1969 agreement, beyond the printed contract.

[^retired]: Lewis had left earlier, his position in New York having been taken
    over by Swanson. Later a Houston office took charge of asphalt sales
    for Nanakuli's region

Shell had begun rethinking its asphalt pricing policies several years before.
Swanson, who succeeded Lewis in New York in 1970, wrote an internal memorandum
on April 21, 1970, in which he discussed frankly the advantages and
disadvantages of price protection of its asphalt buyers. Such a practice assured
Shell of captive-volume sales, he wrote. The practice of granting carry-over
pricing at times of price increases, however, had the unfortunate side effect of
depressing prices in the asphalt market everywhere else, the memorandum
concluded. This rethinking apparently led to a November 25, 1970, letter setting
out "Shell's New Pricing Policy" at its Honolulu and Hilo terminals. The letter
explained the elimination of price protection: "In other words, we will no
longer guarantee asphalt prices for the duration of any particular construction
projects or for the specific lengths of time. We will, of course, honor any
existing prices which have been committed for specific projects for which we
have firm contractual commitments." The letter requested a supply contract be
signed with Shell within 15 days of the receipt of an award by a customer.

The District Judge based his grant of judgment n. o. v.[^judgmentnov] largely on
his belief that, had Nanakuli desired price protection, it should have complied
with Shell's request in that 1970 letter, by which we assume he meant Nanakuli
should have made a firm contractual commitment with Shell for each project on
which its bid was successful within 15 days of award.[^award] That conclusion,
however, ignores several facts. First, compliance by Nanakuli with the letter's
demand that a contract be signed within 15 days of an award would have offered
Nanakuli little, if any, protection. Nanakuli still would have been stuck with
only charging the government the price incorporated into its bid if Shell raised
its price between bid and award. The purpose of price protection was to
guarantee the price in effect when a paver made a bid because of the often
lengthy time span between bid and award. Second, if price protection was a part
of Nanakuli's 1969 agreement with Shell, Shell had no right to terminate
unilaterally that protection. Third, the letter was addressed to "Gentlemen"
with Nanakuli's name typed in at the top; it was apparently addressed to all
Shell's Hawaiian customers. Fourth, Nanakuli officials testified that they did
not believe the letter was applicable to its unusual situation of already having
a long-term contract with Shell. Smith and Lennox both testified that they did
not view the letter as applicable to that supply contract but only to sales it
might make to third parties under the distributorship contract. Shell
characterized that argument as disingenuous, given Nanakuli's infrequent, if not
nonexistent, sales to third parties. Nevertheless, the letter does assume that a
Shell customer would need to sign a contract or purchase order setting forth the
terms of sale as well as the price for any asphalt they would need to buy after
an award. Nanakuli, on the other hand, already had a supply contract with all
the terms of sales set forth, a point its two officials made repeatedly at
trial. For example, Smith testified he saw no need to notify Shell because
Bohner knew of each project and because the supply contract was a firm
contractual commitment with Shell.[^firm] Shell had added in the 1970 letter:
"All previous contractual commitments made prior to the date of this letter
will, of course, be honored." Smith's reading of this was that Nanakuli's supply
contract with Shell was a firm contractual commitment by Shell and that no
further contract was needed. "We felt that this letter was unapplicable (sic) to
our supply contract, that we already had a contractual commitment with Shell Oil
Company which was not to end before 1975." Smith said he did not discuss with
Bohner that part of the letter, which also announced the increase in asphalt
prices to $44 on January 1, because "(t)here was no need to. The price had been
protected before. He knew it. We knew it." There is an additional reason why
Nanakuli might have felt that the letter did not apply to its particular
situation. The letter announced that Shell would charge "from this date forward
... the posted selling price on the date of purchase." This was different from
the express term of Nanakuli's contract with Shell, which was the price in
effect at time of delivery. Either Shell's agreement with Nanakuli embraced
price protection, in which case Shell could not unilaterally abrogate Nanakuli's
rights by this letter, or, as Shell argues, only the words on the written
contract counted, in which case the price to Nanakuli was Shell's price at
delivery. In the latter case, Nanakuli could safely ignore any attempt by Shell
to change the price to that at purchase. Given Nanakuli's particular agreement,
as it understood the agreement to be, the jury could have believed that Nanakuli
officials reacted reasonably in believing that parts of the letter dealing with
the need to notify Shell of awards won did not apply to Nanakuli.

[^judgmentnov]: In fact, the judge did not state his reasons at the time of
    granting n. o. v., but apparently relied on the same reasons he
    had stated on denying defendant's earlier motions for summary
    judgment and later for directed verdict. The judge preferred to
    have a jury verdict in case he was reversed on appeal but, at
    the time of denying that motion, he stated that he was inclined
    to grant it because of the lack of ambiguity in the express
    price term. See note 16 supra. He also cited Nanakuli's failure
    to comply with Shell's requirement for a firm contract within 15
    days of an award. See note 21 infra & textual discussion
    accompanying

[^award]: Shell made a similar announcement in a November 15, 1973, letter but
    the testimony of Nanakuli's Smith was that, when the second letter
    came, it was too late for Nanakuli to do anything; all the projects
    that formed the basis of the price protection claim were bid well
    before that second letter arrived

[^firm]: "We already had a supply contract. Why would we need another supply
    contract?" Smith asked. "There was no need to write. We had our supply
    contract. We didn't need to enter a new contract with the Shell Oil
    Company with every successful project."

Nanakuli's strongest argument as to its failure to comply with the letter was
that there was no need to notify Shell, as Bohner already knew of each project
as it was bid and each award as it was made. Lennox testified, "The Shell Oil
representative was in our office frequently and knew what jobs we had
successfully bid." At another point Lennox said, "The Shell representative was
in the office and was fully aware of what we were doing and what jobs we had
gotten. He was familiar and was more or less a partner in this thing; he even
attended the bid openings at times. He was fully aware and congratulated us
every time we got a nice big job because it was more for Shell." Bohner kept his
principals informed of Nanakuli's projects, Lennox said. He added, "(W)e had
always been protected and our understanding was that we were protected and it
wasn't necessary to keep making notices." Smith in his deposition said that
Bohner only told him that he lacked the authority to grant price protection
"after the fact." Since he knew nothing about how Shell arrived at its pricing,
Smith assumed Bohner could carry out Shell's agreement to price protect Nanakuli
each time it was needed without consulting the mainland.

After Shell's December 31, 1973, letter arrived on January 4, 1974, Smith called
Bohner, as he had done before at times of price increases, to ask for price
protection, this time on 7200 tons. Bohner told Smith that he would have to get
in touch with the mainland, but he expected that the response would be negative.
Smith wrote several letters in January and February asking for price protection.
After getting no satisfaction, he finally flew to California to meet with
Lawson, Fuller, and Chippendale. Chippendale, from the Houston office, was
acknowledged by the other two to be the only person with authority to grant
price protection.[^chippendale] All three Shell officials lacked any
understanding of Nanakuli and Shell's long, unique relationship or of the
asphaltic trade in Oahu. They had never even seen Shell's contracts with
Nanakuli before the meeting. When apprised of the three and their seven-year
duration, Fuller remarked on the unusual nature of Nanakuli's relations with
Shell, at least within his district. Chippendale felt it was probably unique for
Shell anywhere. Smith testified that Fuller admitted to knowing nothing, beyond
the printed page of Nanakuli's agreement with Shell, of the background
negotiation or Shell's past pricing policies toward Nanakuli. Chippendale could
not understand why Nanakuli even had a distributorship contract giving it a $2
commission on sales; he thought Nanakuli had been paid "illegally." No one had
ever heard about Shell giving price protection to Nanakuli before. Instead of
asking Bohner directly, Chippendale told Fuller to search the files for
something on paper. Fuller testified that Shell would not act without written
proof of Shell's past price protection of Nanakuli. He admitted he was unable to
find anything in the files before 1972 because the departments had been
reorganized in that year, about which he informed Chippendale. Chippendale
accordingly decided to deny Nanakuli any price protection and wrote a draft of a
letter for Fuller to send Nanakuli. He wrote a note to Fuller that he should
adopt the "least said" approach with Nanakuli and check any letters with the
legal department. When asked at trial if he had ever simply asked Bohner about
Shell's past pricing practices toward Nanakuli, Fuller answered, "No, I didn't
know we had it, other than the standard policy if we had one which we
didn't."[^fuller] Chippendale told Smith in the California meeting that,
although 7200 tons represented an infinitesimal amount for Shell, it would set a
bad precedent for Shell, since price protection was not Shell's "current
policy." (emphasis supplied). Shell people told him, Smith testified from
contemporaneously made notes, that "any past practice was inapplicable at the
present time."[^contemporaneously] Smith testified from those same notes that he
had left the meeting under the impression that Shell was going out of business
in Hawaii.

[^chippendale]: Shell argues that Nanakuli's language of "request" was an
    admission that it did not feel it was enforcing its legal
    rights. Common sense argues, however, that long-term associates
    whose success has been mutually dependent are more likely to
    deal in friendly terms than to seek instant confrontation at
    each misunderstanding. Shell and Nanakuli had acted as partners
    on Oahu, and thus Smith was used to dealing cooperatively with
    Shell. He testified that this was his personal style and that of
    Nanakuli. "(J)ust in our nature of business. If you go around
    demanding things, you won't have an amicable relationship. It is
    not our company policy and not my personal policy." Nanakuli's
    January 16 letter, while polite, had an underlying premise of
    legal rights. Smith began by pointing out Shell's many years of
    good relations with Nanakuli as its major if not sole customer
    on Oahu promoting Shell's product and being loyal to Shell. He
    then added, "Therefore, we are requesting Shell to honor their
    statement and hold the November 15 price of $44.00 a ton."
    (emphasis supplied). Other letters of Smith's during that time
    frame said Nanakuli was "helpless and bewildered" at the change
    in Shell's past practices: Our bids were under the old pricing
    schedule and the increased prices as of January 1, 1974, will
    result in our sustaining losses of several hundred thousand
    dollars, unless you follow your past practices of protecting us
    on the price of Shell asphalt which we committed to sell prior
    to the increase in price .... (W)e are at a loss to understand
    Shell's drastic change in its treatment of us. In our recent
    conversations with you and Shell offices in San Francisco, we
    were informed that these changes were due to Shell policies
    specified from Houston. (emphasis supplied). Again, on February
    14, Smith wrote Chippendale, "your conduct on previous price
    increases led us to believe (it) would be afforded on subsequent
    price increases." He added, "We ask again: ... Why does Shell
    refuse to follow its previous policy of granting us price
    protection on previously contracted work?" (emphasis supplied).
    In contrast, Blee spoke in an internal Shell memo to Bohner in
    1970 as if Nanakuli had a legal right to price protection:
    "Dick-if you can't convince Nanakuli to go to the new posting
    Sept. one, perhaps you can bargain to leave prices the same for
    the balance of 1970 to compensate for existing committed work."
    (emphasis supplied.)

[^fuller]: Fuller only found out the background to the Shell-Nanakuli 1969
    agreement and Shell's past price protection of Nanakuli in an August
    11, 1974, in-house memo from Bohner. Bohner explained in that memo
    that Shell only built its two terminals in Hawaii in 1963 because of
    longtime firm commitments from Nanakuli on Oahu and James W. Glover,
    Ltd., at Hilo. Based on ten-year Shell projections of growth and
    increased asphalt participation by Nanakuli and Nanakuli's firm
    commitment to Shell, Shell invested in a half-million-dollar terminal
    on Oahu, Bohner wrote. Bohner later testified that he was not with
    Shell in 1963 but had gotten the background information from his
    predecessors in Shell's Hawaiian office

[^contemporaneously]: Other testimony by Smith was thrown out as hearsay: that
    Chippendale felt that, if Shell deviated from the rule for
    one, it would have to do so for all. He also testified
    that Chippendale had said that the loss was a transitional
    one for Shell's customers who in the future would seek
    escalation clauses. In testimony that was allowed, Smith
    testified that Chippendale told him to try to pass on the
    asphalt price increases, which Nanakuli unsuccessfully
    tried to do. Smith wrote Chippendale on February 14, "Our
    attempts ... have met with utmost resistance and threats
    of litigation." By December 1973, Nanakuli, in reaction to
    Shell's November letter, had already begun inserting
    escalation clauses in its contract bids, which were mostly
    rejected. By March, 1974, local and state governments
    allowed such clauses for paving materials, although the
    federal government still does not allow escalation clauses
    for asphalt

We conclude that the decision to deny Nanakuli price protection was made by new
Houston management without a full understanding of Shell's 1969 agreement with
Nanakuli or any knowledge of its past pricing practices toward Nanakuli. If
Shell did commit itself in 1969 to price protect Nanakuli, the Shell officials
who made the decisions affecting Nanakuli in 1974 knew nothing about that
commitment. Nor did they make any effective effort to find out. They acted
instead solely in reliance on the 1969 contract's express price term, devoid of
the commercial context that the Code says is necessary to an understanding of
the meaning of the written word. Whatever the legal enforceability of Nanakuli's
right, Nanakuli officials seem to have acted in good faith reliance on its
right, as they understood it, to price protection and rightfully felt betrayed
by Shell's failure to act with any understanding of its past practices toward
Nanakuli.

V

Scope Of Trade Usage

The validity of the jury verdict in this case depends on four legal questions.
First, how broad was the trade to whose usages Shell was bound under its 1969
agreement with Nanakuli: did it extend to the Hawaiian asphaltic paving trade or
was it limited merely to the purchase and sale of asphalt, which would only
include evidence of practices by Shell and Chevron? Second, were the two
instances of price protection of Nanakuli by Shell in 1970 and 1971 waivers of
the 1969 contract as a matter of law or was the jury entitled to find that they
constituted a course of performance of the contract? Third, could the jury have
construed an express contract term of Shell's posted price at delivery as
reasonably consistent with a trade usage and Shell's course of performance of
the 1969 contract of price protection, which consisted of charging the old price
at times of price increases, either for a period of time or for specific tonnage
committed at a fixed price in non-escalating contracts? Fourth, could the jury
have found that good faith obliged Shell to at least give advance notice of a
$32 increase in 1974, that is, could they have found that the commercially
reasonable standards of fair dealing in the trade in Hawaii in 1974 were to give
some form of price protection?

[ . . . ]

VI

Waiver Or Course Of Performance

Course of performance under the Code is the action of the parties in carrying
out the contract at issue, whereas course of dealing consists of relations
between the parties prior to signing that contract. Evidence of the latter was
excluded by the District Judge; evidence of the former consisted of Shell's
price protection of Nanakuli in 1970 and 1971. Shell protested that the jury
could not have found that those two instances of price protection amounted to a
course of performance of its 1969 contract, relying on two Code comments. First,
one instance does not constitute a course of performance. "A single occasion of
conduct does not fall within the language of this section...." Haw.Rev.Stat. §
490:2-208, Comment 4. Although the Comment rules out one instance, it does not
further delineate how many acts are needed to form a course of performance. The
prior occasions here were only two, but they constituted the only occasions
before 1974 that would call for such conduct. In addition, the language used by
a top asphalt official of Shell in connection with the first price protection of
Nanakuli indicated that Shell felt that Nanakuli was entitled to some form of
price protection. On that occasion in 1970 Blee, who had negotiated the contract
with Nanakuli and was familiar with exactly what terms Shell was bound to by
that agreement, wrote of the need to "bargain" with Nanakuli over the extent of
price protection to be given, indicating that some price protection was a legal
right of Nanakuli's under the 1969 agreement.

Shell's second defense is that the Comment expresses a preference for an
interpretation of waiver.

    3. Where it is difficult to determine whether a particular act merely sheds
    light on the meaning of the agreement or represents a waiver of a term of
    the agreement, the preference is in favor of "waiver" whenever such
    construction, plus the application of the provisions on the reinstatement
    of rights waived ..., is needed to preserve the flexible character of
    commercial contracts and to prevent surprise or other hardship.

_Id._, Comment 3. The preference for waiver only applies, however, where acts
are ambiguous. It was within the province of the jury to determine whether those
acts were ambiguous, and if not, whether they constituted waivers or a course of
performance of the contract. The jury's interpretation of those acts as a course
of performance was bolstered by evidence offered by Shell that it again price
protected Nanakuli on the only two occasions of post-1974 price increases, in
1977 and 1978.[^furtive]

[^furtive]: Bohner testified on direct for Shell at the 1978 trial that the two
    later instances of price protection occurred "this" year and "last"
    year, by which he could have meant 1976 and 1977. Bohner's testimony
    was that on those later occasions Shell gave Nanakuli six and three
    or four months' notice of an increase to allow Nanakuli to buy
    tonnage it had committed at the old price. He defined Shell's
    actions as "in effect carryover pricing." The jury's finding was
    reasonable in light of the circumstances of universal price
    protection by asphalt and aggregate suppliers, as well as by Shell
    on all price increases except 1974

VII

Express Terms As Reasonably Consistent With Usage In Course

of Performance

Perhaps one of the most fundamental departures of the Code from prior contract
law is found in the parol evidence rule and the definition of an agreement
between two parties. Under the U.C.C., an agreement goes beyond the written
words on a piece of paper. " 'Agreement' means the bargain of the parties in
fact as found in their language or by implication from other circumstances
including course of dealing or usage of trade or course of performance as
provided in this chapter (sections 490:1-205 and 490:2-208)." _Id._ §
490:1-201(3). Express terms, then, do not constitute the entire agreement, which
must be sought also in evidence of usages, dealings, and performance of the
contract itself. The purpose of evidence of usages, which are defined in the
previous section, is to help to understand the entire agreement.

(Usages are) a factor in reaching the commercial meaning of the agreement which
the parties have made. The language used is to be interpreted as meaning what it
may fairly be expected to mean to parties involved in the particular commercial
transaction in a given locality or in a given vocation or trade.... Part of the
agreement of the parties ... is to be sought for in the usages of trade which
furnish the background and give particular meaning to the language used, and are
the framework of common understanding controlling any general rules of law which
hold only when there is no such understanding.

[ . . .]

Of these three, then, the most important evidence of the agreement of the
parties is their actual performance of the contract. _Id._ The operative
definition of course of performance is as follows: "Where the contract for sale
involves repeated occasions for performance by either party with knowledge of
the nature of the performance and opportunity for objection to it by the other,
any course of performance accepted or acquiesced in without objection shall be
relevant to determine the meaning of the agreement." _Id._ § 490:2-208(1).
"Course of dealing ... is restricted, literally, to a sequence of conduct
between the parties previous to the agreement. However, the provisions of the
Act on course of performance make it clear that a sequence of conduct after or
under the agreement may have equivalent meaning (Section 2-208)." _Id._
490:1-205, Comment 2. The importance of evidence of course of performance is
explained: "The parties themselves know best what they have meant by their words
of agreement and their action under that agreement is the best indication of
what that meaning was. This section thus rounds out the set of factors which
determines the meaning of the 'agreement' ..." _Id._ § 490:2-208, Comment 1.
"Under this section a course of performance is always relevant to determine the
meaning of the agreement." _Id._, Comment 2.[^alwaysperformance]

[^alwaysperformance]: Section 2-208, much like 1-205, provides "(t)he express
    terms of the agreement and any such course of performance,
    as well as any course of dealing and usage of trade, shall
    be construed whenever reasonable as consistent with each
    other; but when such construction is unreasonable, express
    terms shall control course of performance and course of
    performance shall control both course of dealing and usage
    of trade (section 490:1-205)." _Id._ § 490:2-208(2)

Our study of the Code provisions and Comments, then, form the first basis of our
holding that a trade usage to price protect pavers at times of price increases
for work committed on nonescalating contracts could reasonably be construed as
consistent with an express term of seller's posted price at delivery. Since the
agreement of the parties is broader than the express terms and includes usages,
which may even add terms to the agreement,[^addterms] and since the commercial
background provided by those usages is vital to an understanding of the
agreement, we follow the Code's mandate to proceed on the assumption that the
parties have included those usages unless they cannot reasonably be construed as
consistent with the express terms.

[^addterms]: "The agreement of the parties includes that part of their bargain
    found in course of dealing, usage of trade, or course of
    performance. These sources are relevant not only to the
    interpretation of express contract terms, but may themselves
    constitute contract terms." White & Summers, supra, § 3-3 at 84

Federal courts usually have been lenient in not ruling out consistent additional
terms or trade usage for apparent inconsistency with express terms. The leading
case on the subject is _Columbia Nitrogen Corp. v. Royster Co._, 451 F.2d 3 (4th
Cir. 1971). Columbia, the buyer, had in the past primarily produced and sold
nitrogen to Royster. When Royster opened a new plant that produced more
phosphate than it needed, the parties reversed roles and signed a sales contract
for Royster to sell excess phosphate to Columbia. The contract terms set out the
price that would be charged by Royster and the amount to be sold. It provided
for the price to go up if certain events occurred but did not provide for price
declines. When the price of nitrogen fell precipitously, Columbia refused to
accept the full amount of nitrogen specified in the contract after Royster
refused to renegotiate the contract price. The District Judge's exclusion of
usage of the trade and course of dealing to explain the express quantity term in
the contract was reversed. Columbia had offered to prove that the quantity set
out in the contract was a mere projection to be adjusted according to market
forces. Ambiguity was not necessary for the admission of evidence of usage and
prior dealings.[^columbia] Even though the lengthy contract was the result of
long and careful negotiations and apparently covered every contingency, the
appellate court ruled that "the test of admissibility is not whether the
contract appears on its face to be complete in every detail, but whether the
proffered evidence of course of dealing and trade usage reasonably can be
construed as consistent with the express terms of the agreement." _Id._ at 9.
The express quantity term could be reasonably construed as consistent with a
usage that such terms would be mere projections for several
reasons:[^mereprojections] (1) the contract did not expressly state that usage
and dealings evidence would be excluded; (2) the contract was silent on the
adjustment of price or quantities in a declining market; (3) the minimum tonnage
was expressed in the contract as Products Supplied, not Products Purchased; (4)
the default clause of the contract did not state a penalty for failure to take
delivery; and (5) apparently most important in the court's view, the parties had
deviated from similar express terms in earlier contracts in times of declining
market. _Id._ at 9-10. As here, the contract's merger clause said that there
were no oral agreements. The court explained that its ruling "reflects the
reality of the marketplace and avoids the overly legalistic interpretations
which the Code seeks to abolish." _Id._ at 10. The Code assigns dealing and
usage evidence "unique and important roles" and therefore "overly simplistic and
overly legalistic interpretation of a contract should be shunned." _Id._ at 11.

[^columbia]: As discussed earlier, the District Judge here mistakenly equated
    ambiguity with admissibility. He said, "I think this is a close
    case. On the face of the contract it would seem to be unambiguous,"
    although acknowledging that liberal commentators on the Code would
    let in evidence of usage and performance even without ambiguity. He
    only let in usage evidence because Shell's answer to interrogatory
    11 provided some ambiguity, see note 16 supra, saying "I think if
    these can be consistently used to explain the apparently
    unambiguous terms, they should be allowed in." In fact, this court
    has ruled that ambiguity is not necessary to admit usage evidence.
    Board of Trade of San Francisco v. Swiss Credit Bank, 597 F.2d 146,
    148 (9th Cir. 1979)

[^mereprojections]: State court cases have interpreted express quantity as mere
    projections in similar circumstances. E. g., Campbell v.
    Hofstetter Farms, Inc., 251 Pa.Super. 232, 380 A.2d 463,
    466-67 (1977). (Express agreement to sell a specified number
    of bushels of corn, wheat, and soy beans was not, as a
    matter of law, inconsistent with a usage of the trade that
    amounts specified in contracts are only estimates of a
    seller-farmer's farms); Loeb & Co. v. Martin, 295 Ala. 262,
    327 So. 2d 711, 714-15 (Ala. 1976) (It was a jury question
    whether, in light of trade usage, "all cotton produced on
    400 acres" called for all cotton seller produced on 400
    acres or for 400 acres of cotton.);
    Heggblade-Marguleas-Tenneco, Inc. v. Sunshine Biscuit, Inc.,
    59 Cal. App. 3d 948, 131 Cal. Rptr. 183, 188-89 (1976)
    (Usage in the potato-processing trade that the amount
    specified in the contract was merely an estimate of buyer's
    requirements was admissible); Paymaster Oil Mill Co. v.
    Mitchell, 319 So. 2d 652, 657-58 (Miss.1975) (Additional
    term that the seller was not obliged to deliver the full
    4000 bushels of soy beans called for in the contract was
    admissible)

Usage and an oral understanding led to much the same interpretation of a
quantity term specifying delivery of 500 tons of stainless-steel solids in
Michael Schiavone & Sons, Inc. v. Securalloy Co., 312 F. Supp. 801 (Conn. 1970).
In denying summary judgment for plaintiff-buyer, the court ruled that
defendant-seller could attempt to prove that the quantity term was modified by
an oral understanding, in line with a trade usage, that seller would only supply
as many tons as he could, with 500 tons the upper limit. The court reasoned that
an additional term with a lesser effect than total contradiction or negation of
a contract term can be a consistent term and "(e)vidence that the quantity to be
supplied by defendant was orally understood to be up to 500 tons cannot be said
to be inconsistent with the terms of the written contract which specified the
quantity as '500 Gross Ton.' " _Id._ at 804.[^gross]

[^gross]: The Seventh Circuit in dicta has implied that a written contract
    calling for 36-inch wide steel could be modified by a usage in the
    steel industry that a 36-inch specification "includes by definition
    steel which actually measures 37 in width." Decker Steel Co. v.
    Exchange National Bank, 330 F.2d 82, 85 (7th Cir. 1964). That circuit
    has not been as generous in allowing modification of express terms by
    course of performance or additional terms. In V-M Corp. v. Bernard
    Distributing Co., 447 F.2d 864 (7th Cir. 1971), when the manufacturer
    sued the distributor of electronic equipment for goods delivered,
    distributor Bernard counter-claimed for breach of warranty. The
    counterclaim was dismissed because the written contract expressly
    disclaimed all but an express warranty and limited liability by
    excluding consequential or special damages, even though the course of
    performance by V-M had been to accept return of a portion of the goods
    that were not defective under the express warranty. Where the course
    of performance cannot be harmonized with the express terms, the court
    held, the express controls. _Id._ at 867-68. Although the court did
    not say so, the result might well have been different had usage
    evidence been presented to reinforce the acts constituting course of
    performance. In Luria Brothers & Co. v. Pielet Brothers Scrap Iron &
    Metal, Inc., 600 F.2d 103, 110 (7th Cir. 1979), the court upheld a
    jury verdict for plaintiff-buyer in a suit for nondelivery, affirming
    the exclusion of parol evidence of an additional term that seller's
    obligation to sell scrap metal was conditioned on its ability to
    obtain the metal from a particular supplier

The Tenth Circuit in _Amerine National Corp. v. Denver Feed Co._, 493 F.2d 1275
(10th Cir. 1974), found that the warranty that Amerine, the seller, would
provide turkeys was not breached by delivery of "H&N" turkeys instead of
"Amerine". In light of Amerine's prior dealings and a trade usage that "Amerine"
or any trade-name turkey simply meant any turkeys sold by that manufacturer, not
a particular kind or breed of turkey, any agreement to provide turkeys did not
oblige Amerine to provide only its own strain of turkeys.

The Fifth Circuit, in a carefully reasoned opinion, _Chase Manhattan Bank v.
First Marion Bank_, 437 F.2d 1040 (5th Cir. 1971), reversed the lower court's
refusal to allow usage and dealing evidence that seemingly contradicted the
express term. The standby agreement in Chase stated that none of the banks would
unilaterally demand that the debtor pay up or sell the collateral stock unless
all creditors agreed to the sale. The subordination agreement-signed after the
standby agreement, incorporated into it, and by its terms to last a maximum of
18 months-provided that the other creditor banks were subordinated to the extent
of $1 a share to Chase because of its further loan to the debtor. The usage of
the trade and the course of dealing between the parties, ruled inadmissible by
the lower court, were that the parties had not intended to limit the duration of
the subordination agreement to 18 months.[^lowercourt] The appellate court
reversed, directing that evidence of usage and dealings be admitted because it
"merely delineates a commercial backdrop for intelligent interpretation of the
agreement," without "delimit(ing) a particular party's intent, except insofar as
it reveals that some ascribed intent might be ludicrous in the commercial
world." _Id._ at 1046.[^ascribed] The court wrote, "In providing for the
admission of such evidence, the Code manifests the law's recognition of the fact
that perception is conditioned by environment: unless a judge considers a
contract in the proper commercial setting, his view is apt to be distorted or
myopic, increasing the probability of error." _Id._ The court added, "If, in
light of banking practices in problem loan situations and Chase's dealings with
First Marion, an unsecured loan to the (debtor) would have seemed unreasonable,
ambiguities arise within the subordination provision." _Id._ at 1047. Usage and
dealings evidence here would "permit analysis of the written agreement in the
proper commercial setting. Such evidence might disclose ambiguities within the
provisions of the agreement...." _Id._ For a court to use usage evidence to
better understand express terms does not mean it is allowing the written
instrument to be contradicted; the use of such evidence "simply places the court
in the position of the parties when they made the contract, and enables it to
appreciate the force of the words they used in reducing it to writing." _Id._ at
1048. "The object of rules of construction generally, and of parol evidence
particularly, is to ascertain the intention of the parties." _Id._[^reducing] It
is noteworthy that in Chase, the contradiction was total, not the partial
exception Nanakuli argues here.

[^lowercourt]: Although Section 1-202 did not apply because the contract did not
    involve the sale of goods, the court looked by analogy to the
    parol evidence rule in Article 1 of the Code as implicitly
    restricting the types of evidence that a court could exclude for
    other types of contracts

[^ascribed]: Chase had offered proof of a usage "that termination of a
    subordination agreement prior to extinction of the debt allegedly
    secured by that agreement, would be commercially unsound. (Thus) no
    bank or commercial institution would propose or countenance such
    charity." _Id._ at 1047

[^reducing]: More recently the same court has explained that the Code departs
    from the traditional parol evidence rule, which barred as
    irrelevant "the subjective intent of one ... unless it is shown
    that that intent was communicated to the other party." _Foxco
    Industries, Ltd. v. Fabric World, Inc._, 595 F.2d 976, 984 (5th
    Cir. 1979). Under the U.C.C., in contrast, the fact that the buyer
    "did not know of the industry's usage and custom or of the
    standards in question is of no moment; the parties to a contract
    such as the one in issue are presumed to have intended the
    incorporation of trade usage in striking their bargain." Therefore,
    the buyer's protest that he was not a member of the trade
    association whose standards were at issue and was unaware of their
    existence at the time, was not a valid defense. "(The
    Association's) standards would certainly qualify as trade usage,
    and thus were admissible, notwithstanding Fabric World's
    unawareness of them." _Id._ at 985. Accord, Heggblade, supra, note
    35

The Fourth Circuit has been similarly liberal in admitting parol evidence to
contradict express terms. After its pacesetting decision in Columbia Nitrogen,
supra, it held in _Brunswick Box Co. v. Coutinho, Caro & Co._, 617 F.2d 355,
360-61 (4th Cir. 1980), that "the Parol Evidence Rule is not a bar to the
introduction of extrinsic evidence as to the intention of the parties in the use
of the term 'F.A.S. Norfolk, Virginia', in the written agreement," even though
"the term, on its face, is unambiguous." The appeals court, therefore, reversed
the lower court's exclusion ruling and remanded for trial. The term "F.A.S." is
defined by the Code as meaning delivered to the buyer alongside the vessel by
the seller, which was also the usage in the port. The plaintiff-seller, however,
argued that the dealings between the parties leading to the contract, the actual
agreement of the parties, and their course of performance of the contract were
that the seller would unload on the dock area. The Code does not bar such
evidence "simply because a contract appears on its face to be complete, ..." and
therefore plaintiff-seller should have been allowed to show that the parties
agreed that the seller would unload the material on the dock area rather than
alongside the vessel. _Id._ at 359.

The Ninth Circuit's most recent reference to the U.C.C.'s parol evidence rule
was in a similar case, _Board of Trade of San Francisco v. Swiss Credit Bank_,
597 F.2d 146 (9th Cir. 1979), in which this court considered the meaning of an
express term in a letter of credit requiring presentment of a "full set clean on
board bills of lading." When the components for the electronic calculators were
sent by air, the bank protested that ocean shipment was required by the trade
usage as to the express term. Although the U.C.C.'s definition of bills of
lading includes airbills, this court upheld the bank's right to prove a trade
usage that in essence contradicted the Code's broad definition of bills of
lading by showing that only ocean bills of lading were allowable. The summary
judgment for plaintiff was reversed and the case remanded for trial on whether
the bank's dishonor of the documentary letter of credit was wrongful. The court
cited the California Supreme Court, "The test of admissibility of extrinsic
evidence to explain the meaning of a written instrument is not whether it
appears to the court to be plain and unambiguous on its face, but whether the
proffered evidence is relevant to prove a meaning to which the language of the
instrument is reasonably susceptible." _Id._ at 148-49.[^proffered]

[^proffered]: The difference between usage evidence and evidence of additional
    terms is that the former is always admissible, although not
    controlling if not reasonably consistent with the express terms,
    whereas the latter are not even admitted if the court finds the
    written contract is a complete and exclusive statement of the
    agreement's terms. Despite the added difficulty, then, of
    reconciling additional and express terms, courts have admitted
    additional terms more at variance with the writing than here. For
    example, in _Pac. Indem. Co. v. McDermott Bros._, 336 F. Supp.
    963, 969-70 (M.D. Pa. 1971), parol evidence was admissible to show
    an oral agreement for one party to purchase insurance on the
    aircraft to cover the other despite the lack of any insurance
    provision in the sales contract. Similar evidence of an oral
    agreement was admitted in _Crispin Co. v. Del. Steel Co._, 283 F.
    Supp. 574, 575 (E.D. Pa. 1968), to show whether a letter of credit
    formed a part of a total agreement, along with the sales contract,
    in which case transportation by charter-party vessel was
    prohibited and a breach of contract, although not forbidden by the
    sales contract

[ . . . . ]

Because the jury could have found for Nanakuli on its price protection claim
under either theory, we reverse the judgment of the District Court and reinstate
the jury verdict for Nanakuli in the amount of $220,800, plus interest according
to law.

REVERSED AND REMANDED WITH DIRECTIONS TO ENTER FINAL JUDGMENT.

**Discussion**

1.  For software licensors and licensees who are parties to an open source
    license drafted by neither party, is the course of performance relevant to
    interpreting ambiguity? The _Nanakuli_ court did not place much value in the
    course of performance of the Shell employees who had not seen the contracts
    prior to the 1974 meeting with Nanakuli because their interpretations of the
    contract did not bear on the parties' original intent. \
    _Nanakuli_ also noted that the UCC prefers to apply the doctrine of waiver
    where it is difficult to determine whether course of performance or waiver
    should be applied, and where the parties acts are ambiguous. \
    \
    In the context of open source licensing, where a party to an OSI-approved
    license is unlikely to have insight into the preferred meaning of an
    ambiguous term at the time of contracting, would a court instead be likely
    to look the concept of waiver?
1.  In _Nanakuli_ the court determined that the UCC governed the interpretation
    of an obligation to offer price protection that did not appear in the
    agreement at all and held that the obligation was binding. How could this be
    relevant in open source contexts? Could a court applying the UCC determine
    that licensors and licensees owe each other obligations beyond what appears
    in the plain text of the agreement based solely on trade usage and course of
    performance between the parties?

### 3. Course of Dealing {#course-of-dealing}

A court may look to evidence of the parties' conduct prior to the formation of
the agreement to supplement its understanding of the express terms of the
agreement, so long as the evidence is consistent with the express terms. This is
known as "course of dealing" evidence.[^dealers]

[^dealers]: U.C.C. § 1-303(b) (2001) ("A 'course of dealing' is a sequence of
    conduct concerning previous transactions between the parties to a
    particular transaction that is fairly to be regarded as establishing
    a common basis of understanding for interpreting their expressions
    and other conduct."); Restatement (Second) of Contracts § 202(5)
    (1981) ("Wherever reasonable, the manifestations of intention of the
    parties to a promise or agreement are interpreted as consistent with
    each other and with any relevant course of performance, course of
    dealing, or usage of trade."); _Id._ § 223 ("Course of Dealing: (1)
    A course of dealing is a sequence of previous conduct between the
    parties to an agreement which is fairly to be regarded as
    establishing a common basis of understanding which is fairly to be
    regarded as establishing a common basis of understanding for
    interpreting their expressions and other conduct. (2) Unless
    otherwise agreed, a course of dealing between the parties gives
    meaning to or supplements or qualifies their agreement."). \

Courts consider course of dealing evidence when resolving ambiguous terms
because the parties' prior dealings may indicate what was intended by that term
at the time of contracting. Recall that the parol evidence rule generally
discourages evidence of discussions and agreements prior to the fully integrated
written agreement.[^inside] For the same policy reasons encouraging
parties' to capture their final intended terms in the written agreement, courts
give less weight to course of dealing evidence than to course of performance
evidence.[^insidedealing]

[^inside]: _See supra_ discussion of parol evidence rule.

[^insidedealing]: Restatement (Second) of Contracts § 203(b) (1981) ("[E]xpress
    terms are given greater weight than course of performance,
    course of dealing, and usage of trade, course of performance
    is given greater weight than course of dealing or usage of
    trade, and course of dealing is given greater weight than
    usage of trade[.]"); U.C.C. § 1-303(e) (2001) ("(1) express
    terms prevail over course of performance, course of dealing,
    and usage of trade; (2) course of performance prevails over
    course of dealing and usage of trade; and (3) course of
    dealing prevails over usage of trade.").

Similar to the discussion of course of performance above, the nature of
contracting under open source licenses makes it difficult to infer meaning from
the course of dealing of the licensor and licensee. For one thing, the parties
to an OSI-approved open source license will not have been the parties drafting
the license. For another, it is unlikely that most open source licensors and
licensees have any prior course of dealing that would bear on a shared
understanding of the meaning of an ambiguous open source license term prior to
contracting. However, in a very small percentage of open source contracting,
there may be discussions between a licensor and licensee regarding the meaning
of an ambiguous license term and shared agreement on a particular choice of open
source license resulting from that discussion. In those instances, a court might
consider this a relevant source of evidence to supplement the meaning of the
ambiguous term.

In the following case, _SNMP Research Int'l, Inc. v. Nortel Networks Inc._, a
court finds that extrinsic facts render ambiguous the otherwise unambiguous
terms of a Schedule to a software agreement, and turned to evidence of course of
dealing (referred to in order to supplement the understanding of the ambiguous
terms.[^researchers]

[^researchers]: _SNMP Research Int'l, Inc. v. Nortel Networks Inc._, 573 B.R.
    134 (Bankr. D. Del. 2017), _available at_
    https://www.deb.uscourts.gov/sites/default/files/opinions/judge-kevin-gross/nortel-snmp-opinion-re-licensing.pdf

#### _SNMP Research Int'l, Inc. v. Nortel Networks Inc._, 573 B.R. 134 (Bankr. D. Del. 2017) {#snmp-research-int'l-inc-v-nortel-networks-inc-573-b-r-134-bankr-d-del-2017}

**I. INTRODUCTION**[^researchintro]

[^researchintro]: The Court is utilizing the findings of fact and conclusions of
    law which the parties submitted. The Court has carefully
    reviewed the record citations and legal citations to determine
    their accuracy and applicability.

The litigants in the adversary proceeding are plaintiffs SNMP Research
International, Inc. ("SNMPRI") and SNMP Research, Inc. ("SNMPR") (collectively,
"SNMP") and the defendants, Nortel Networks Inc. and affiliated entities
("Nortel"). The Court held a two-day trial on May 11 and 12, 2017 (the "Trial")
to determine whether certain software was licensed for use or distribution by
Nortel with respect to products after June 20, 2003. Adv. D.I. 540.

The issue which the Court is addressing is narrow but the parties presented
considerable evidence at the Trial. The issue (the "Schedule 1 Issue") is
"whether the SNMP software was licensed for use or distribution under Schedule
1A of the Nortel License . . . with respect to any products after June 20,
2003."[^wrt] Scheduling Order Concerning Motion to Amend Proofs of Claim and
Schedule 1 Issue. D.I. 18020, Adv. D.I. 540.

[^wrt]: Schedule 1 and Schedule 1A are the same and the Court will refer to
    "Schedule 1."

The Court has subject matter jurisdiction to consider the Schedule 1 Issue and
the issues tried during the May 11-12 hearing pursuant to 28 U.S.C. § 1334 and
venue is proper pursuant to 28 U.S.C. §§ 1408 and 1409. The matters addressed
during the Trial are core proceedings pursuant to 28 U.S.C. § 157(b)(2).

[ . . . . ]

**NORTEL'S UNDERSTANDING OF SCHEDULE 1 IS CORRECT **

**A. Schedule 1 Is Ambiguous **

Under New York law, the first step in interpreting a contract is answering "the
threshold question of whether the terms of the contract are ambiguous."
_Alexander & Alexander Servs., Inc. v. These Certain Underwriters at Lloyd's,
London_, 136 F.3d 82, 86 (2d Cir. 1998). "An ambiguity exists where the terms of
a contract could suggest 'more than one meaning when viewed objectively by a
reasonably intelligent person who has examined the context of the entire
integrated agreement and who is cognizant of the customs, practices, usages and
terminology as generally understood in the particular trade or business.'" _Id._
(_quoting Lightfoot v. Union Carbide Corp._, 110 F.3d 898, 906 (2d Cir.1997));
_see also Dev. Specialists, Inc. v. Peabody Energy Corp. (In re Coudert Bros.)_,
487 B.R. 375, 380 (S.D.N.Y. 2013) ("[I]n analyzing contractual text, a court
need not turn a blind eye to context." (citation omitted)).

"Ambiguity with respect to the meaning of contract terms can arise either from
the language itself or from inferences that can be drawn from this language.
Hence, only where the language and the inferences to be drawn from it are
unambiguous may a district court construe a contract as a matter of law . . . ."
_Alexander & Alexander Servs. Inc._, 136 F.3d at 86 (_quoting Cable Sci. Corp.
v. Rochdale Vill., Inc._, 920 F.2d 147, 151 (2d Cir.1990)) (citation omitted).
To conclude that contractual language is unambiguous, a Court must find that "it
has a definite and precise meaning, unattended by danger of misconception in the
purport of the [contract] itself, and concerning which there is no reasonable
basis for a difference of opinion." _Serdarevic v. Centex Homes, LLC_, 760 F.
Supp. 2d 322, 329 (S.D.N.Y. 2010) (alteration in original) (_quoting Hunt Ltd.
v. Lifschultz Fast Freight, Inc._, 889 F.2d 1274, 1277 (2d Cir.1989)); _see also
Marathon Asset Mgmt., LP v. Angelo Gordon & Co, LP (In re Energy Future Holdings
Corp.)_, 2017 WL 1170830, at *4 (D. Del. 2017).

Applying these principles, the Court concluded at a hearing on May 2, 2017 that
Schedule 1 is ambiguous. Order re Motion to Exclude, May 4, 2017 (Adv. D.I.
560); May 2 Tr. 120:1-130:16. The Court is therefore free to consider both the
agreement's text and "any available extrinsic evidence to ascertain the meaning
intended by the parties during the formation of the contract." _Alexander &
Alexander Servs., Inc._, 136 F.3d at 86. Because "the contract is ambiguous and
relevant extrinsic evidence as to its meaning is available, its interpretation
is a question of fact for the factfinder." _New Windsor Volunteer Ambulance
Corps, Inc. v. Meyers_, 442 F.3d 101, 111 (2d Cir. 2006).

The Court concludes that both the provisions of Schedule 1 and the available
extrinsic evidence support Nortel's understanding of the agreement. Any existing
products and any development projects originating from Bay Networks that emerged
during the three- year term of Schedule 1 would take advantage of the lifetime
royalty buy out until the products aged out of the marketplace.

**B. Schedule 1's Provisions Support Nortel **

Schedule 1 specifically refers to and incorporates the Bay Networks License.
Under New York law, a document is incorporated by reference into a contract
where (1) the contract identifies the document to be incorporated "beyond all
reasonable doubt," and (2) the parties clearly knew of and assented to the
incorporated terms. _Laureate Educ., Inc. v. Ins. Co. of Pennsylvania_, 2014 WL
1345888, at *7 (S.D.N.Y. 2014) (_quoting PaineWebber Inc. v. Bybyk_, 81 F.3d
1193, 1201 (2d Cir.1996)).[^laureate]

[^laureate]: Schedule 1's incorporation of the Bay Networks License meets both
    requirements. First, Schedule 1 identifies the Bay Networks License
    beyond reasonable doubt by listing the specific documents
    (including their titles and dates of execution) that it comprises.
    Ex. D-7C at 1. Second, that the parties knew of and assented to the
    incorporation of the Bay Networks License is evident from the plain
    text of Schedule 1: Key sections of Schedule 1 (addressing
    "Run-Time Software," "Yearly Maintenance Fee" and "Royalties") are
    comprised solely of a cross- reference to terms "described in" the
    Bay Networks License. _Id._ Thus, those sections of Schedule 1 are
    entirely dependent on the Bay Networks License and would be
    unintelligible without it. _See Sbarra v. Totolis_, 191 A.D.2d 867,
    870 (N.Y. App. Div. 1993).

Accordingly, interpreting the meaning of Schedule 1 requires consideration of
the Bay Networks License and the rights it conferred. The Bay Networks License
provided royalty buy outs for SNMPRI's EMANATE and ARL products. Bay Networks
purchased the EMANATE buy out and Nortel completed the purchase of the ARL buy
out in February 2000, more than a year after it had acquired Bay Networks. Ex.
D-4 at 3; Ex. D80 at 1; Ex. D-79A at 2, 8. By acquiring these buy outs, Bay
Networks and later Nortel obtained the right to "distribute in perpetuity an
unlimited number of binary copies" of the designated SNMPRI software. Ex. D-2 at
19; Ex. D-4 at 2; Trial Tr. 308:11-310:7.[^dd]

[^dd]: SNMPRI argues that its proposed interpretation of Schedule 1 is supported
    by a general rule against construing contracts in a way that imposes a
    lifetime obligation. SNMPRI's PreHearing Br. ¶¶ 44-45 (Adv. D.I. 566).
    The Bay Networks License itself granted lifetime rights: the royalty buy
    out conferred the right to "distribute in perpetuity an unlimited number
    of binary copies" of the licensed software. Ex. D-4 at 2; Ex. D-2 at 19;
    Trial Tr. 308:11-310:7. The Supreme Court's opinion in _M&G Polymers USA,
    LLC v. Tackett_, 135 S. Ct. 926, 937 (2015) supports upholding a lifetime
    obligation when it is expressly provided for in the agreement at issue,
    as is the case here. 135 S. Ct. at 937 ("Indeed, we have already
    recognized that a collective-bargaining agreement [may] provid[e] in
    explicit terms that certain benefits continue after the agreement's
    expiration." (alterations in original) (citations omitted)).

Schedule 1 preserved the royalty buyouts for all products and projects
originating from Bay Networks that existed when Schedule 1 was signed or that
came into existence during its three-year term. The specific provisions of
Schedule 1 that implemented this result are as follows:

*   The "Specified Product or Project" section identifies the products and
    projects that would receive this benefit as follows: "[a]ll products of
    units and projects originating from what was Bay Networks." Ex. D-7C at 1.
*   The "Development Software" and "Run-Time Software" sections refer to the Bay
    Networks License to identify the specific SNMPRI software that was covered
    by the royalty buy out under the Bay Networks License and would likewise be
    covered by Schedule 1, including EMANATE. _Id._
*   The "Royalties" section refers to the Bay Networks License, stating: "As
    described in the agreements and amendments thereto between SNMPRI and Bay
    Networks and its predecessor entities." As noted, the Bay Networks
    agreements provided for a royalty buy out as to the designated SNMPRI
    software, including EMANATE. _Id._
*   The "Additional Conditions" section states as follows: \
    This Schedule supersedes all of the prior agreements between SNMPRI and Bay
    Networks and its predecessor entities as referenced above, and all such
    agreements are hereby terminated by execution of this Schedule. This
    Schedule and the license in regard to the Development Software and Run-Time
    Software shall terminate and be of no further effect after a period of three
    years from the last date that this Schedule is executed below. _Id._ at 2.

The combined effect of these provisions is that "[a]ll products of units and
projects originating from what was Bay Networks" in existence during Schedule
1's three-year term will receive a royalty buy out in accordance with the Bay
Networks License so that they can use the designated SNMPRI software during the
lifetime of the product line. This conclusion is consistent with the fact that
Schedule 1 provides a royalty buy out for the products and projects it covers.
Schedule 1 refers to the royalty provisions of the Bay Networks License, which
provide for a royalty buy out for the designated SNMPRI software. It is
confirmed by the November 16, 1999 email by Southwood concerning Schedule 1,
which states that the parties intended Schedule 1 to provide the "lifetime
royalty buy out" to the products and projects it covers. Ex. D-76C at 1.

SNMPRI contends the result of this language is that, after three years, any
right to use the software covered by the Bay Networks License and Schedule 1 is
stripped away from the legacy Bay Networks products and projects, such that
these products' and projects' continued use of that software would become
infringing. The Court does not accept SNMPRI's interpretation. SNMPRI violates
the fundamental tenet of New York law that a contract must be considered from
the perspective of a "reasonably intelligent person who has examined the context
of the entire integrated agreement." _Alexander & Alexander Servs._, 136 F.3d at
86. SNMPRI asks the Court to disregard what Schedule 1 actually says and does in
incorporating the royalty buy out of the Bay Networks License and to read the
language in the "Additional Conditions" section without the appropriate context.

Second, SNMPRI's proposed new interpretation would lead to the unreasonable
consequence that would cause existing products and projects covered by Schedule
1 to be stripped of their right to use the SNMPRI software at the three-year
mark. They would be infringing from that point onward. This would be unworkable
for Nortel because it had incorporated the SNMPRI software into the core
codebase of the BayStack/ES/ERS switches and to extricate this software from the
core codebase would be difficult and time-consuming, just as it would be very
difficult to remove thread of a particular color from a multicolor jacket. Mead
Dep. 145:13-146:25, 230:13-231:12, 231:14-232:4, 233:4-12; Trial Tr.
420:14-422:8.

If the parties had intended Schedule 1 to strip existing products of their right
to use SNMP software, they would have included in Schedule 1 a mechanism for
extending the right to use the SNMP software in these products beyond the
three-year mark, as Razgaitis testified. Trial Tr. 426:20-427:5, 429:18-430:6.
For example, there would be a provision for an additional payment to be made to
give these products the right to use the software until they aged out of the
market, just as the Bay Networks License itself had provided. In the absence of
such a provision, Nortel would be at SNMPRI's mercy at the end of the three year
term. Trial Tr. 420:23-421:5, 421:9-12. As Razgaitis explained at trial, the
fact that Schedule 1 lacks any mechanism for extending Nortel's rights beyond
the end of its three-year term which indicates, based on industry custom and
practice, that the parties did not intend for these rights to be stripped away
at the three-year mark. Trial Tr. 429:18-430:6.

The Court agrees with Nortel that Bay Networks products and projects that were
in existence during Schedule 1's three-year term received the royalty buy out of
the Bay Networks License, so that they would be able to use the software covered
by Schedule 1 until they aged out of the market. Schedule 1 would not cover any
new project that Nortel began to develop after the three-year mark. In that
circumstance, at the beginning of such a new development project, Nortel could
decide whether it was interested in using SNMPRI software in the new
development. If so, it could discuss that possibility with SNMPRI and seek to
agree on mutually acceptable terms. If not, it could develop its own software or
choose from other vendors. Nortel's reading of Schedule 1 means that neither
party would be at the other's mercy after Schedule 1 ended. Thus, "the context
of the entire integrated agreement" from the perspective of "a reasonably
intelligent person . . . who is cognizant of the customs, practices, usages and
terminology as generally understood in the particular trade or business,"
supports Nortel's interpretation of Schedule 1. _Alexander & Alexander Servs.,
Inc._, 136 F.3d at 86 (citation omitted).

SNMPRI's reading ignores key parts of Schedule 1, in particular the
incorporation of the royalty buy out from the Bay Networks License, and would
produce a result that is both inequitable and commercially unreasonable.
SNMPRI's proposed interpretation 69 of Schedule 1 would be incompatible with the
goal of contract interpretation under New York law, which "must be to accord the
words of the contract their 'fair and reasonable meaning'" by taking into
account "not merely literal language, but whatever may be reasonably implied
therefrom." _Sutton v. E. River Sav. Bank_, 435 N.E.2d 1075, 1078 (N.Y. 1982)
(citations omitted). "[P]arties to an agreement are presumed to act sensibly in
regard to it and an interpretation that produces an absurdly harsh result is to
be avoided." _Martilet Mgmt. Servs., Inc. v. Bailey_, 2013 WL 5420966, at *3
(S.D.N.Y. 2013) (alteration in original) (citations omitted); see also Williston
on Contracts § 32.11 (4th ed. 2017) ("[I]nterpretations which render the
contract fair and reasonable are preferred to those which render the contract
harsh or unreasonable to one party."). Therefore, "[a] court will endeavor to
give the [contract] construction most equitable to both parties instead of the
construction which will give one of them an unfair and unreasonable advantage
over the other." _Metro. Life Ins. Co. v. Noble Lowndes Int'l, Inc._, 643 N.E.2d
504, 508 (N.Y. 1994) (second alteration in original) (citation omitted). Here,
the Court concludes that Nortel's explanation of Schedule 1 is "most equitable
to both parties."

**C. The Parties' Interactions Support Nortel **

Having concluded that Schedule 1 is ambiguous, the Court "may accept any
available extrinsic evidence to ascertain the meaning intended by the parties
during the formation of the contract." _Alexander & Alexander Servs., Inc._, 136
F.3d at 86. This includes evidence of (1) the parties' negotiations, _Prior v.
Innovative Commc'ns Corp._, 207 F. App'x 158, 162 (3d Cir. 2006) (applying New
York law, noting that the parties' "course of 70 negotiations" is proper
extrinsic evidence); (2) correspondence between the parties, _Compagnie
Financiere de CIC et de L'Union Europeenne v. Merrill Lynch, Pierce, Fenner &
Smith Inc._, 232 F.3d 153, 160 (2d Cir. 2000) (finding letters sent by the
parties prior to the execution of an agreement to be probative extrinsic
evidence); (3) the parties' course of performance under the contract, _Jobim v.
Songs of Universal, Inc._, 732 F. Supp. 2d 407, 416 (S.D.N.Y. 2010) (noting that
proper "extrinsic evidence includes the contracting parties' course of
performance"); _New Windsor Volunteer Ambulance Corps, Inc._, 442 F.3d at 113
(affirming the district court's reliance on "the parties' course of conduct over
the years in order to determine their intent"); and (4) expert evidence on
custom and practice in the relevant industry, _Evans v. Famous Music Corp._, 807
N.E.2d 869, 871, 873 (N.Y. 2004) (interpreting an ambiguous agreement based in
part on expert testimony that where music publishers intend to share the benefit
of foreign tax credits with songwriters, they include an express clause to that
effect); _Last Time Beverage Corp. v. F & V Distrib. Co., LLC_, 951 N.Y.S.2d 77,
81-82 (N.Y. App. Div. 2012) (relying on expert testimony that franchisors in the
soft drink industry ordinarily give exclusive rights to distributors to
distribute new soft drinks in their territory to aid in interpreting an
ambiguous agreement). The extrinsic evidence in each of these categories
confirms that Nortel's position on Schedule 1 is correct.

**1. SNMPRI Confirmed Schedule 1's Meaning And Effect Before Signing **

Southwood, SNMPRI's point person in the negotiations, expressly explained and
confirmed Schedule 1's meaning shortly before it was signed. Southwood did so in
an email to Nortel's lead negotiator, Hyslop. Southwood made clear in his email
that he understood that "everyone's expectations are [being] fixed for all
time." Ex. D-76C at 1. Referring to Schedule 1 which he described as the "final
Bay transfer to Nortel" Southwood stated the following:

    I told [the lawyer preparing Schedule 1] that the royalty buy out would
    expire in three years. . . . By expire I mean that new products/projects
    brought on line after three years would address royalties on their own
    merit. Current Bay products and development projects for the next three
    years will take advantage of the lifetime royalty buy out until their
    products have aged out of the marketplace.

_Id._

Southwood noted in his email that he had communicated the same understanding of
Schedule 1 to SNMPRI's counsel, Rick Barnes ("Barnes"), that he was providing to
Nortel. _Id._ Barnes was drafting the text of Schedule 1. Less than 48 hours
later, Southwood sent Hyslop a draft of Schedule 1, which has exactly the same
content as the final signed version. Ex. D-183.01; Ex. D-183.02. As in his
November 16 email, Southwood's November 18 email attaching the draft of Schedule
1 called it "the permanent Bay to Nortel transfer." Ex. D-183.01; Ex. D-183.02.

Southwood's email is important in two respects. First, it confirms that Schedule
1's purpose is to confer the lifetime royalty buy out on the products and
projects it covers. Southwood's email refers to the "buy out" and the "lifetime
royalty buy out." Ex. D-76C at 1. Given that Schedule 1 confers a lifetime
royalty buy out, it makes no sense for SNMPRI to contend that the products and
projects it covers would be stripped of their right to use the designated
software after three years. That is directly antithetical to the meaning and
purpose of a lifetime royalty buy out, which is to confirm a right to use the
software for the lifetime of the product line.

Second, Southwood's explanation of what it means to provide that Schedule 1 will
expire goes to the heart of SNMPRI's argument. SNMPRI contends that because
Schedule 1 says it will terminate and be of no further effect after three years,
that means that any product or project it covers will lose its right to use the
SNMPRI software after three years. SNMPRI contends that "terminate means
terminate," and so Schedule 1 must be interpreted in the way it urges.
Southwood's email, however, explicitly explains what is meant by saying that
Schedule 1 will terminate—i.e., "expire"—in three years.

Southwood first says that the parties agreed "that the royalty buy out would
expire in three years." Southwood explains what that means: "By expire I mean
that new products/projects brought on line after three years would address
royalties on their own merit. Current Bay products and development projects for
the next three years will take advantage of the lifetime royalty buy out until
their products have aged out of the marketplace." Ex. D-76C at 1.

**2. The May 2000 Email From Case To Reeves Confirms The Meaning of Schedule 1
**

Writing to Reeves in May 2000, Case referred to "Schedule 1 [as] the document
that grandfathers the Bay licenses over to the new Nortel master agreement" and
assured him "I was correct when I told you that the cost is $0." Ex. D-77.
Case's description is fully consistent with Nortel's reading of Schedule 1. It
"grandfathers the Bay licenses over to the new Nortel master agreement," so that
the BayStack/ES/ERS switches can continue using the SNMPRI software. It also
provides that there would be no additional cost.

Case's email is also important for what he did not say to Reeves. There is no
suggestion, as SNMPRI contends now, that Schedule 1 would serve to strip the
BayStack/ES/ERS switches of the right to use the SNMPRI software after three
years, and that the cost of obtaining an ongoing right to use the software would
not be zero but instead would be tens of millions of dollars. Case said no such
thing in this email. He did not say any such thing at any time, including during
the period leading up to the end of Schedule 1's three- year term. Nor did
anyone else acting for SNMPRI or SNMPR say any such thing to anyone at Nortel at
any time.

**3. SNMPRI's Repeated Renewal of The SSA Confirms Nortel's Continued Use **

SNMPRI's repeated renewal of the SSA covering the Schedule 1 software for years
after June 2003 further confirms Nortel's ongoing right to use that software.
SNMPRI claims that it was a "mistake." Trial Tr. 269:22- 270:1 (Case contending
that "we shouldn't have done it. That was a mistake."). SNMPRI's claim of a
purported mistake is not credible.

It is black letter New York law that "when resolving disputes concerning the
meaning of ambiguous contract language, unexpressed subjective views have no
proper bearing. Only the parties' objective manifestations of intent are
considered." _Nycal Corp. v. Inoco PLC_, 988 F. Supp. 296, 302 (S.D.N.Y. 1997);
see also _Faulkner v. Nat'l Geographic Soc'y_, 452 F. Supp. 2d 369, 377-78
(S.D.N.Y. 2006) ("[O]nly objective manifestations of intent are relevant under
New York law. . . . [S]tatements of subjective intention uncommunicated to the
other contracting party are immaterial in construing the terms of the contract."
(citations omitted)). Unlike the subjective intent or post hoc conclusions of
contracting parties, the parties' course of dealing throughout the life of a
contract is highly relevant to determining the meaning of the terms of the
agreement." Faulkner, 452 F. Supp. 2d at 381. In fact, "[a]s the Supreme Court
has explained, '[g]enerally speaking, the practical interpretation of a contract
by the parties to it for any considerable period of time before it comes to be
the subject of controversy is deemed of great, if not controlling, influence.'"
_Id._ (second alteration in original) (_quoting Old Colony Trust Co. v. Omaha_,
230 U.S. 100, 118 (1913)).

SNMPRI confirmed Nortel's right to use the software by repeatedly renewing the
SSA for the Schedule 1 software for years after June 2003, under which SNMPRI
provided Nortel with updated versions of the Schedule 1 software and in return
collected thousands of dollars from Nortel. The Court looks to the parties'
course of conduct.

**4. SNMPRI Confirmed That The Buy Out Gave Nortel An Ongoing Right **

SNMPRI stated in August 2003, after the end of Schedule 1's three-year term,
that Nortel had an ongoing royalty buy out under Schedule 1. This confirmation
came as part of an email exchange beginning in July 2003 between Tremblay, a
Nortel employee who was just becoming involved in the relationship with SNMPRI,
and SNMPRI employees Southwood and Hopper. Ex. D-158.01; Ex. 158.02. Tremblay
was reviewing the license agreement between Nortel and SNMPRI and its various
schedules and seeking to learn about their status. Trial Tr. 190:1-9; Tremblay
Dep. 90:18-91:1. In that context, Hopper made the following statement about
Schedule 1 in an August 2003 email to Tremblay: "According To John [Southwood],
as I understood him, BAY has a Royalty-BuyOut on EMANATE Sources on WinNT,
Solaris, and VxWorks as well as Asynchronous Request Libraries on Solaris,
HP-UX, AIX and WinNT." Ex. D-158.02 at 1. Given that this statement was made
months after the end of Schedule 1's three-year term, the reference to Schedule
1 as continuing to provide a royalty buy out is directly contrary to the
argument SNMPRI is proposing now. At Trial, Southwood contended this was yet
another "mistake," claiming that Hopper did not "understand [him] correctly."
Trial Tr. 195:11-196:1. The claim of mistake is not credible. As a legal matter,
SNMPRI's contention that it harbored a subjective understanding that was the
opposite of what it objectively manifested to Nortel is simply not relevant.
See, e.g., Faulkner, 452 F. Supp. 2d at 377-78.

[ . . . . ]

CONCLUSION

The Court recognizes SNMP's principal arguments that: (1) Schedule 1 is
unambiguous and therefore extrinsic evidence is unwarranted; (2) the merger
whereby Nortel acquired Bay Networks was a reverse triangular merger, and,
accordingly the Bay License was not transferable to Nortel without SNMPRI's
consent; and (3) Tremblay (of Nortel) testified that Schedule 1 terminated three
years after its effective date and the 86 license was thereby terminated. The
Court has rejected these arguments. First, while the individual words,
"terminate," "no further effect" and "three years" are unambiguous, the record
of the case establishes that Schedule 1 was the result of a more involved set of
facts which render Schedule 1 ambiguous. Second, whether California law impacted
Nortel's rights in a reverse triangular merger is not the point. What matters is
what SNMP and Nortel did after the merger, how they treated their respective
rights. Third, Tremblay's involvement was relatively late in the SNMPRI - Nortel
relationship. Finally, it is clear to the Court that under New York law,
SNMPRI's and Nortel's conduct establish that there was an implied-in-fact
agreement which governs the relationship between Nortel and SNMPRI and, in turn,
establish that Nortel had the right to use the software after June 2003. The
parties' relationship would otherwise be counterproductive. The Court therefore
finds in Nortel's favor.

Schedule 1 confers a lifetime royalty buy out on "[a]ll products of units and
projects originating from what was Bay Networks" that existed during its
three-year term. Competent extrinsic evidence overwhelmingly confirms this
meaning and effect. The Court will therefore rule in Nortel's favor concerning
the meaning and effect of Schedule 1. In addition, if the Court had not ruled in
Nortel's favor concerning the meaning and effect of Schedule 1, the record of
the parties' conduct and statements after June 2003 would establish an
implied-in-fact contract with the same effect.

The Court directs Nortel to prepare an Order giving effect to the foregoing
Opinion, to share the Order with SNMP, and to submit the Order under
certification.

**Discussion**

1.  The plain terms of the agreement as well as evidence of course of dealing
    and course of performance each concern objective, verifiable facts about the
    parties' words and conduct. Given this emphasis in the sources of evidence
    used in interpretation, how relevant is evidence from only one party
    regarding what they thought or believed an ambiguous term to mean? If a
    clarification is published after the contract is implemented, would that
    potentially be considered course of performance evidence or course of
    dealing evidence, depending on the timing of the contracting? Would the
    publisher need to be either a licensor or licensee in order for it to be
    considered as one of these sources of evidence?

### 4. Trade Usage {#trade-usage}

Trade usage is the least important source of evidence a court will look to when
interpreting an ambiguous term in an an agreement.[^mvp] Trade usage will not be
considered if it is inconsistent with the express terms of the agreement, the
parties' course of performance, or the parties' course of dealing.[^prevalent]

[^mvp]: U.C.C. § 1-303(c) (2001) ("A 'usage of trade' is any practice or method
    of dealing having such regularity of observance in a place, vocation, or
    trade as to justify an expectation that it will be observed with respect
    to the transaction in question. The existence and scope of such a usage
    must be proved as facts. If it is established that such a usage is
    embodied in a trade code or similar record, the interpretation of the
    record is a question of law."); Restatement (Second) of Contracts §
    202(5) (1981) ("Wherever reasonable, the manifestations of intention of
    the parties to a promise or agreement are interpreted as consistent with
    each other and with any relevant course of performance, course of
    dealing, or usage of trade."); _Id._ § 222 ("(1) A usage of trade is a
    usage having such regularity of observance in a place, vocation, or
    trade as to justify an expectation that it will be observed with respect
    to a particular agreement. It may include a system of rules regularly
    observed even though particular rules are changed from time to time. (2)
    The existence and scope of a usage of trade are to be determined as
    questions of fact. If a usage is embodied in a written trade code or
    similar writing the interpretation of the writing is to be determined by
    the court as a question of law. (3) Unless otherwise agreed, a usage of
    trade in the vocation or trade in which the parties are engaged or a
    usage of trade of which they know or have reason to know gives meaning
    to or supplements or qualifies their agreement.").

[^prevalent]: _See_ Restatement (Second) of Contracts § 203(b) (1981)
    (Stipulating that the express terms and evidence of course of
    performance and course of dealing are all given greater weight
    than trade usage); U.C.C. § 1-303(e) (2001) (Stating that express
    terms, course of performance, and course of dealing all prevail
    over usage of trade).

If a court seeks to supplement its understanding of an ambiguous term in an open
source license and it does not consider any course of performance or course of
dealing evidence, it may look to evidence of trade usage of the term. However,
the usage of trade evidence would not be considered if it contradicted the
express terms of the open source license, and trade usage must meet a high bar
of widespread adoption in an industry.

In the case _Wolf v. Superior Court of Los Angeles_ the parties to the agreement
had no recollection of the discussing the meaning of the disputed term, "gross
receipts," and so the court gave full weight to the evidence of trade usage of
"gross receipts" in order to interpret its meaning.[^direwolf]

[^direwolf]: _Wolf v. Superior Court_, 8 Cal. Rptr. 3d 649 (Cal. Ct. App. 2004),
    _available at_
    https://www.courtlistener.com/opinion/2295591/wolf-v-superior-court/.

#### Wolf v. Superior Court of Los Angeles, 8 Cal. Rptr. 3d 649 (Cal. Ct. App. 2004) {#wolf-v-superior-court-of-los-angeles-8-cal-rptr-3d-649-cal-ct-app-2004}

JOHNSON, J.

An author seeks a writ of mandate to compel the trial court to vacate its order
granting summary adjudication of issues in favor of an entertainment industry
conglomerate on its cross-claims for a declaration it was not required to pay
royalties on the value of promotional agreements with third parties for which it
received no cash. At issue is whether the term "gross receipts" as used in the
royalty agreement is reasonably susceptible to an interpretation urged by the
author to mean other valuable in-kind consideration as well as cash. The trial
court found the term "gross receipts" clearly and unambiguously meant "cash"
only, and rejected expert extrinsic evidence indicating the term in the
entertainment context meant money as well as the value of other consideration
received. We conclude the trial court erred in concluding the term "gross
receipts" was not reasonably susceptible to the interpretation urged by the
author. Accordingly, we grant the petition for writ of mandate with directions
for the trial court to vacate its order granting summary adjudication and remand
for further proceedings.

**FACTS AND PROCEEDINGS BELOW**

Gary K. Wolf and his company Cry Wolf!, Inc. (Wolf), are the petitioners in this
case. Petitioner, Gary K. Wolf, is the author of an original novel entitled, Who
Censored Roger Rabbit? In his novel Wolf created characters such as Roger
Rabbit, Jessica Rabbit, Baby Herman and Detective Eddie Valiant. Wolf's novel
also created and introduced the concept of Toontown as the place where these
cartoon characters lived.

Shortly after the book's release in 1981, real party in interest, Walt Disney
Pictures and Television (Disney), reached an agreement with Wolf to option
nearly all rights to Who Censored Roger Rabbit? Disney memorialized the terms of
the parties' oral agreement in a letter dated May 1981. According to this "deal
memo," if Disney exercised its option, Wolf would be entitled to a five percent
royalty on children's story books, children's story-telling records and on
merchandise based on the characters he had developed in Who Censored Roger
Rabbit? as well as other rights.

In 1983, Disney exercised its option to purchase the rights to Who Censored
Roger Rabbit? The parties thereafter executed a "long form" purchase agreement.
This 1983 agreement superceded the 1981 "deal memo" and expanded on the parties'
respective rights regarding motion picture rights, television series rights, and
other matters. In the 1983 agreement, Wolf also assigned to Disney the right to
exploit the characters he created in his novel.

Not one of the parties who played a role in, or who helped negotiate the terms
of, the 1983 agreement could recall any discussion they held at the time
regarding the meaning of the term "gross receipts" as used in paragraph 21
governing royalty rights to character merchandise.

Thereafter, Disney developed and co-produced the motion picture Who Framed Roger
Rabbit? with Steven Spielberg's Amblin Entertainment. Disney released the movie
in June 1988. It proved to be an extraordinarily successful feature combining
cartoon and live action actors.

By 1989 a dispute arose among the parties regarding use of Wolf characters at
theme parks and in movie cels, auditing rights, and other matters. The parties
resolved their dispute by entering into another agreement in 1989 which
clarified and/or modified certain terms of the 1983 agreement. However, Wolf's
right to a five percent royalty on merchandise depicting his characters remained
intact. Again, none of the negotiating parties to the 1989 agreement could
recall any discussion regarding the meaning of Wolf's right to a royalty on
"gross receipts" from character merchandise.

In order to promote the theatrical and home video releases of the film (and at
various times thereafter to promote and sustain the Roger Rabbit franchise),
Disney entered into alliance agreements with corporate entities such as Kodak,
Coca-Cola, and Burger King licensing them to use Roger Rabbit and Disney
characters in their advertising and promotions. The terms of Disney's
promotional agreements with these third parties varied: sometimes Disney
received money from the other company; sometimes Disney paid the other company,
and in still other situations, no cash exchanged hands. An example of this
latter type of agreement is a Disney/McDonald's agreement entered into in 1988
in connection with the picture's release. In this agreement Disney allowed
McDonald's to use Wolf as well as Disney characters in a "tie-in" promotion
between its menu items and the motion picture Who Framed Roger Rabbit? Under
this agreement McDonald's agreed to: (1) conduct a promotion featuring the
licensed characters on 18 million collector cups; (2) purchase $12 million worth
of specified advertising themed to the motion picture; and (3) place
approximately $100 worth of point-of-purchase materials at each of the
McDonald's stores throughout the United States. Disney received no cash directly
from McDonald's under this particular licensing agreement.

In 1991, Disney entered into another so-called alliance agreement with
Eckerd/Kodak. The agreement called for Eckerd Drug Company to fund and produce
television and radios ads, print ads, in-store advertisements and to undertake
other promotional efforts. The agreement required Kodak to underwrite the cost
of producing hundreds of thousands of Walt Disney World collector pins depicting
Disney as well as Roger Rabbit characters. In exchange, Disney provided six
grand prize travel packages to Walt Disney World. Disney received no cash
directly from this arrangement.

On the other hand, Disney did receive cash under its 1995 licensing agreement
with McDonald's to promote Disneyland's 40th anniversary. McDonald's Disneyland
40th Anniversary Happy Meal agreement was a licensing arrangement which allowed
McDonald's to give away eight toy car "premiums" featuring various Disney
characters, including one car which featured two of the Roger Rabbit characters.
McDonald's paid Disney $400,000 under the licensing agreement for the eight
cars. Because the Wolf characters represented one eighth of this amount Disney
reported $50,000 attributable to the Roger Rabbit characters and paid Wolf five
percent of this amount, or $2,500.

Wolf claimed he was entitled to a five percent royalty every time Disney
licensed Roger Rabbit characters for use in any merchandising venture by Disney
or through its alliance agreements. He asserted he was entitled to this royalty
based on the value of the licensing agreement to Disney from use of the Roger
Rabbit characters, whether or not Disney chose to receive the benefit in cash.
Disney countered it was not obligated to pay Wolf any royalty unless or until it
received actual cash from a licensing agreement.

Unable to resolve the dispute, Wolf filed suit against Disney in May 2001. In
March 2002, Disney filed a cross-complaint for declaratory relief, reformation,
money had and received and unjust enrichment. In October 2002, Disney moved for
summary adjudication on three of the causes of action in its cross-complaint
which sought a declaration the parties' 1983 contract only obligated it to pay a
five percent royalty on cash it received for character merchandising, and that
it had no obligation to pay a royalty on any noncash consideration it received
from licensing Wolf's characters for use in merchandise for promotional
purposes.[^fiftycent]

[^fiftycent]: Specifically, the motion for summary adjudication of issues sought
    declarations: (1) Disney had no obligation to pay Wolf anything in
    connection with the 1991 Eckerd/Kodak promotional agreement
    because neither Disney nor its subsidiaries received cash under
    this particular agreement; (2) Disney had already satisfied its
    contractual obligation to pay Wolf what it owed in connection with
    the McDonald's Disneyland 40th Anniversary Happy Meal agreement;
    and (3) Disney had no obligation to pay Wolf anything in
    connection with any third party agreement if Disney or its
    subsidiaries received, or will receive, no cash from the third
    party, because the parties' 1983 agreement specifies its
    obligation to pay royalties does not accrue unless or until monies
    are received by Disney or its subsidiaries.

In its motion Disney argued it was entitled to summary adjudication of issues
because the "clear and unambiguous meaning" of "gross receipts" in the contract
could only mean receipt of cash money. Disney claimed the contract language was
clear and unambiguous because the contract did not obligate it to account for
royalties to Wolf unless and until it had received funds in the United States.
In opposition, Wolf presented extrinsic evidence in the form of expert testimony
to refute Disney's assertion. According to Wolf's expert, the term "gross
receipts" in the entertainment industry means "money or the value of other
consideration received by the studio," when not otherwise defined or limited by
written agreement.

The trial court heard several hours of arguments on the motion over two court
days. The trial court questioned Wolf regarding his proffered extrinsic evidence
that the term "gross receipts" was interpreted in the entertainment industry to
mean cash or other valuable consideration.[^receipts] The court acknowledged
Wolf's expert's testimony created an ambiguity regarding the meaning of the term
"gross receipts." However, the court was persuaded the contract term clearly and
unambiguously meant Disney's obligation to pay Wolf royalties only arose with
actual receipt of cash in connection with the merchandising of Wolf's
characters. The trial court found the term "gross receipts" was not reasonably
susceptible to the meaning urged by Wolf and rejected his proffered extrinsic
evidence.

[^receipts]: The trial court read, and thus to this extent, "considered"
    Wolf's proffered extrinsic evidence.

In its written order the trial court ruled Disney had met its burden of showing
there were no triable issues of material fact and Wolf had failed to raise a
triable issue of material fact. The court thus granted summary adjudication in
favor of Disney on its first, fourth and seventh causes of action in its
cross-complaint. The court reasoned: "Wolfe [sic] claims entitlement to 5% of
the 'promotional value' of the two Alliance Agreements at issue, that is, monies
not actually received by Disney. However, the plain and unambiguous language of
[ ] Wolfe's [sic] contract provides that he is entitled to 5% of the monies
received by Disney. The contract at issue was negotiated at arms length between
the parties. The contract is clear and unambiguous and extrinsic evidence is not
received to interpret the contract. The contract does not require the addition
of fictional receipts, nor does it require payment to Wolfe [sic] of 5% of
monies that were never received by Disney.

"Cross-Complainants' motion for summary adjudication of issues on the first,
fourth, and seventh causes of action of Disney's cross-complaint against Wolfe
[sic], filed on March 11, 2002, is granted. Pursuant to [ ] paragraph 21 of the
1983 agreement, with regard to the July 18, 1991 Kodak agreement and the March
21, 1995 McDonald's agreement, Disney has no obligation to pay Wolfe [sic] 5% of
the gross receipts, until monies have been received by Disney. Although the
court has read all papers filed in support of and opposition to the instant
motion, extrinsic evidence is not admitted for the reasons stated. Only
admissible, non-extrinsic evidence has been considered in deciding this
motion."[^mcobligation]

Wolf filed a petition for writ of mandate to compel the trial court to vacate
its order for summary adjudication. We issued an order directing the trial court
to either vacate its order for summary adjudication and make a new and different
order denying the motion for summary adjudication, or in the alternative, to
show cause why the requested relief should not be granted. Respondent Superior
Court did not respond and we now consider the petition.

[^mcobligation]: Italics in original.

**DISCUSSION**

**I. STANDARD OF REVIEW.**

On review of an order summarily adjudicating issues, we review the record de
novo to determine whether the prevailing party has conclusively negated
necessary elements of his opponent's case or demonstrated under no hypothesis is
there a material issue of fact which requires the process of a
trial.[^hypotheses]

[^hypotheses]: _See Ann M. v. Pacific Plaza Shopping Center_ (1993) 6 Cal. 4th
    666, 673-674, 25 Cal. Rptr. 2d 137, 863 P.2d 207.

**II. THE TERM "GROSS RECEIPTS" IN PARAGRAPH 21 OF THE 1983 AGREEMENT CAN BE
REASONABLY INTERPRETED TO MEAN CASH AS WELL AS VALUABLE IN-KIND CONSIDERATION.**

The dispute in this case is over the meaning of the term "gross receipts" for
purposes of triggering Disney's obligation to pay Wolf royalties on character
merchandising. Wolf contends "gross receipts" as used in the royalty agreement
means "cash and other valuable consideration." Disney contends the agreement
clearly and unambiguously provides its obligation to pay Wolf royalties from the
exploitation of certain merchandising rights arises only upon receipt of monies.
The trial court ruled the term "gross receipts" was not ambiguous  it meant
only cash actually received by Disney. The court further found the term was not
reasonably susceptible to the meaning Wolf urged claiming the term as used in
this context included not just cash, but also other valuable consideration such
as promotions undertaken by third parties employing his characters. We disagree
with the trial court.

"Where the meaning of the words used in a contract is disputed, the trial court
must provisionally receive any proffered extrinsic evidence which is relevant to
show whether the contract is reasonably susceptible of a particular meaning.
(_Pacific Gas & E. Co. v. G.W. Thomas Drayage etc. Co._ (1968) 69 Cal. 2d 33,
39-40, 69 Cal. Rptr. 561, 442 P.2d 641; _Pacific Gas & ElectricCo. v. Zuckerman_
(1987) 189 Cal. App. 3d 1113, 1140-1141, 234 Cal. Rptr. 630.) Indeed, it is
reversible error for a trial court to refuse to consider such extrinsic evidence
on the basis of the trial court's own conclusion that the language of the
contract appears to be clear and unambiguous on its face. Even if a contract
appears unambiguous on its face, a latent ambiguity may be exposed by extrinsic
evidence which reveals more than one possible meaning to which the language of
the contract is yet reasonably susceptible. (_Pacific Gas & E. Co. v. G.W.
Thomas Drayage etc. Co., supra,_ 69 Cal.2d at p. 40 & fn. 8, 69 Cal. Rptr. 561,
442 P.2d 641; _Pacific Gas & Electric Co. v. Zuckerman, supra,_ 189 Cal.App.3d
at pp. 1140-1141, 234 Cal. Rptr. 630.)"

[^latentcy]

[^latentcy]: _Morey v. Vannucci_ (1998) 64 Cal. App. 4th 904, 912, 75 Cal. Rptr.
    2d 573.

The interpretation of a contract involves "a two-step process: 'First the court
provisionally receives (without actually admitting) all credible evidence
concerning the parties' intentions to determine "ambiguity," i.e., whether the
language is "reasonably susceptible" to the interpretation urged by a party. If
in light of the extrinsic evidence the court decides the language is "reasonably
susceptible" to the interpretation urged, the extrinsic evidence is then
admitted to aid in the second step  interpreting the contract. [Citation.]'
(_Winet v. Price_ (1992) 4 Cal. App. 4th 1159, 1165, 6 Cal. Rptr. 2d 554.) The
trial court's determination of whether an ambiguity exists is a question of law,
subject to independent review on appeal. (Ibid.) The trial court's resolution of
an ambiguity is also a question of law if no parol evidence is admitted or if
the parol evidence is not in conflict. However, where the parol evidence is in
conflict, the trial court's resolution of that conflict is a question of fact
and must be upheld if supported by substantial evidence. (_Id._ at p. 1166, 6
Cal. Rptr. 2d 554.) Furthermore, '[w]hen two equally plausible interpretations,
of the language of a contract may be made ... parol evidence is admissible to
aid in interpreting the agreement, thereby presenting a question of fact which
precludes summary judgment if the evidence is contradictory.' (_Walter E. Heller
Western, Inc. v. Tecrim Corp._ (1987) 196 Cal. App. 3d 149, 158, 241 Cal. Rptr.
677.)"[^precludes]

[^precludes]: _WYDA Associates v. Merner_ (1996) 42 Cal. App. 4th 1702, 1710, 50
    Cal. Rptr. 2d 323; _see also_, _Morey v. Vannucci, supra_, 64 Cal.
    App. 4th 904, 913, 75 Cal. Rptr. 2d 573 ["An appellate court is
    not bound by a trial court's construction of a contract where (a)
    the trial court's contractual interpretation is based solely upon
    the terms of the written instrument without the aid of extrinsic
    evidence; ..."].

The term "gross receipts" appears several times in the parties' agreement. In
the exhibit attached to the contract discussing motion picture rights, the term
appears in a separate section heading and is given a specific definition
peculiar to motion picture revenue and exclusions. "Gross receipts" also appears
as a separate section heading in the exhibit discussing television series
rights. Again, the term is defined and given a peculiar meaning tied to revenue
sources and exclusions uniquely relevant to production of a potential television
series. In the section of the contract discussing Wolf's royalty rights to
character merchandising the term "gross receipts" again appears. This time,
however, the term does not appear in a separate section heading, and "gross
receipts" is not defined. Moreover, the term is not even capitalized to suggest
it has a special or limited meaning in the merchandising context. As a result,
the term "gross receipts" must be considered in light of all the circumstances
and the overall context of the contract.

Paragraph two of the agreement describes the merchandising rights Disney
purchased:

"(h) The sole and exclusive right to make, publish and vend, throughout the
world, or to license others so to make, publish and vend, representations of the
characters created by the Seller [Wolf] which are in the work (including said
characters from the work appearing in any such motion pictures or other
adaptations), upon, in and/or in connection with articles of merchandise, or the
advertising, display or exploitation of merchandise or in connection with any
commercial activities."[^merch]

[^merch]: Disney also purchased the right to use Wolf's characters in children's
    storytelling recordings, and in various types of children's books.

Paragraph 21 of the 1983 agreement concerns Disney's obligation to pay royalties
for the merchandising of Wolf's characters. This paragraph provides:

"21. In the event that Purchaser [Disney] exercises any of the rights granted to
it in and by Subparagraph 2(h), (i) and (k) hereof, Purchaser agrees to pay to
Seller [Wolf] a sum equal to five percent (5%) of Purchaser's gross receipts
derived from the exercise of such rights, which, in the event of Purchaser's
licensing of any such rights to others, shall be composed of Purchaser's
royalties so derived from the licensee. In the event that such licensee is a
subsidiary of Purchaser, then such royalties received by Purchaser from such
subsidiary shall be deemed to be not less than five percent (5%) of such
subsidiary's gross receipts derived from the exercise of such rights.
Purchaser's obligation to pay such sums to Seller shall not accrue unless and
until monies with respect to which the same are to be paid shall have been
received within the United States of America by, and placed at the unrestricted
disposal of, Purchaser or Purchaser's subsidiary (or if restricted from being
transmitted to the United States by applicable law or regulations ('restricted
funds') then the restricted funds shall be deemed to have been so received to
the extent used by Purchaser or Purchaser's subsidiary in such territory from
which such monies would have otherwise been transmitted). So long as such monies
are so received, Purchaser shall render semi-annual statements to the Seller
within forty-five (45) days after the end of each half of the calendar year,
showing the sums of money so received during the preceding half with respect to
which the said obligation applies; and said statements shall be accompanied by
payment of the amount appearing thereby to be then due from Purchaser to Seller.
All such statements shall be mailed to Seller at the address specified for
notices herein, unless or until Purchaser is otherwise instructed in writing.
All statements and accountings furnished by Purchaser hereunder shall be
conclusively deemed correct unless the same shall be objected to within ninety
(90) days from Purchaser's rendition thereof...."[^timelyobjection]

Disney emphasizes this paragraph uses the terms "monies" and "monies so
received" and discusses "statements" for monies "so received." Based on this
language in the paragraph on royalty rights Disney argues "gross receipts"
clearly and unambiguously means only cash, and then only when actual cash is
received.

[^timelyobjection]: Italics added. The balance of paragraph 21 provides: "Purchaser's
    said obligation shall not apply to picture books or other books
    containing no text material (or containing text material averaging
    not more than two lines per page), comic strips, comic books,
    magazines or other similar types of publications, nor to or in
    connection with publication of, or sound recordings or record
    albums of, only music or lyrics, or both (as distinguished from
    children's storytelling records under Subparagraph 2(i)), from any
    of the Purchaser's versions of the work. Nothing in this paragraph
    contained shall be construed as requiring Purchaser to manufacture,
    publish or sell, or to license the manufacture, publication or sale
    of, any items which are the subject hereof. In the case of
    restricted funds, at the request and expense of Seller, and subject
    to applicable law and banking regulations, Purchaser agrees to
    cause an amount equal to the sum otherwise payable to Seller
    hereunder with respect to such restricted funds, to be deposited in
    a bank account in the territory involved in Seller's name, and such
    deposit shall constitute payment by Purchaser to Seller hereunder.
    If, other factors being equal, Purchaser has a choice between an
    interest and noninterest bearing bank account at the same bank, the
    deposit will be made in the bank account which is interest bearing.
    Purchaser shall in no event be liable for interest on sums
    deposited regardless of whether such deposit is made in an interest
    or non-interest bearing account."

In support of its argument "gross receipts" can only mean "cash received" Disney
relies on the decision in _County of Sacramento v. Pacific Gas and Electric
Company_.[^cash] There the court held the utility's gross receipts for
purposes of calculating its franchise fee did not include the value of
electricity consumed by the utility itself in generating electricity for sale to
consumers. The decision in County of Sacramento is of no assistance here. In the
context of franchise fees on public utilities, the definition of the term "gross
receipts" was dictated by statute and prior decisions interpreting the statute
at issue which excluded the monetary value of electricity consumed internally
and not sold for cash. Accordingly, the decision in County of Sacramento sheds
no light on the issue whether the term "gross receipts" may be subject to
multiple meanings in a private contract in the entertainment industry context.

[^cash]: _County of Sacramento v. Pacific Gas & Elec. Co._ (1987) 193 Cal.
    App. 3d 300, 238 Cal. Rptr. 305.

Wolf offered extrinsic evidence to show the term "gross receipts" meant not just
cash receipts but also other valuable consideration received. Wolf pointed out
the interpretation he urged was consistent with the legal definition of "gross
receipts" as defined in Black's Law Dictionary, namely, "[t]he total amount of
money or the value of other consideration received from selling property or from
performing services."[^considerations] Wolf also referred the court to an
appellate decision in which the court stated the term "gross receipts" was such
a familiar and commonplace term in accounting and taxation that when used in its
ordinary sense meant the "total amount of money or the value of other
consideration received."[^sacramento]

[^considerations]: _Black's Law Dictionary_ (6th ed.1990) page 703, 2d column.

[^sacramento]: _See County of Sacramento v. Pac. Gas & Elec. Co._, _supra_, 193
    Cal. App. 3d 300, 309, 238 Cal. Rptr. 305 ["the courts have always
    considered that gross receipts are measured by money or other
    consideration actually received by a party or paid for his
    benefit."].

Wolf argued this is the definition of "gross receipts" customarily used in the
entertainment industry when the term is not otherwise limited or defined by
written contract. Wolf thus urged the court to read paragraph 21 in the context
of custom and practice in the entertainment industry. The extrinsic evidence
Wolf offered to explain industry custom consisted of expert testimony from David
Held. Mr. Held is an attorney who has worked in the motion picture industry
since 1973. United Artists Corporation, Paramount Pictures Corporation and the
Samuel Goldwyn Company have employed him. He initially worked as an attorney in
the legal department then in such capacities as Director of Business Affairs,
Vice President of Business Affairs and was ultimately promoted to the position
of Executive Vice President in Charge of Business Affairs in Paramount's Motion
Picture Group. Since 1988, Held has been employed as a consultant in the
entertainment industry. In his 28 years of experience Held had personally
negotiated, or supervised negotiations of, thousands of agreements and also
reviewed thousands of proposals involving third party participation agreements,
film performance reports, and the like.

Held stated, from the start of his career until the present, the term "gross
receipts" in the entertainment industry "means the total amount of money or the
value of other consideration received by the studio" when not otherwise
specifically defined to limit the term's meaning.

In his declaration, Held explained the portion of paragraph 21 which uses the
terms "monies" does not purport to define the term "gross receipts." Instead, it
specifies Disney's obligation to pay royalties does not arise unless or until
potential or proposed licensing of the Wolf characters became a fait accompli
and the terms of such agreements carried out so as to ensure the studio did not
become responsible to pay royalties on failed or aborted projects. Regarding
alliance agreements in which the licensor received promotional benefits rather
than cash, Held stated industry custom for purposes of paying royalties was to
attribute a cash value to the benefits a studio received.

The trial court read Held's declaration and questioned Wolf about its meaning.
The court noted, "So where we are here is that personally I think `gross
receipts,' as the parties wrote it in paragraph 21, means`money.' But if I have
to consider that Held declaration, you win the summary judgment. There's a
disputed issue of fact. That's where we are. That's the bottom line."
Ultimately, the trial court concluded it did not need to consider Wolf's
extrinsic evidence, finding the term "gross receipts" unambiguously meant cash
money.

We find the trial court erred in its treatment of the proffered extrinsic
evidence on the issue whether the contract was ambiguous. At the very least,
this conflicting evidence exposed an ambiguity in the term's meaning. If Held's
definition is the industry norm, then the competing definitions were equally
plausible. Disney, on the other hand, argues the parties' contract did not use
the term "gross receipts" in a technical sense and for this reason the expert's
declaration of industry custom and practice was inadmissible. However, we note,
Disney did not  and does not attempt to  refute the expert's factual assertion
through independent evidence that in the entertainment industry context "gross
receipts" means not only cash, but also the value of other consideration
received. Accordingly, the trial court was not justified in rejecting this
extrinsic evidence on the ground it did not comport with the court's own view of
the contract language as unambiguous.

This case is analogous to the situation presented in _Pacific Gas and Electric
Company v. G.W. Thomas Drayage & Rigging Company_.[^drayage] In _Thomas
Drayage_, the Supreme Court considered a contract clause in which the defendant
agreed to indemnify the plaintiff for injury to property arising out of or
connected with the performance of the contract. The trial court agreed with the
defendant the clause could be read to cover only injury to the property of third
parties. The trial court nevertheless held the "plain language" of the agreement
also required defendant to indemnify plaintiff for injuries to plaintiff's
property. Once the trial court concluded the contract had a plain meaning it
refused to admit any extrinsic evidence contradicting its
interpretation.[^injurious] The Supreme Court observed, "[w]hen the court
interprets a contract on this basis, it determines the meaning of the instrument
in accordance with the '. . . extrinsic evidence of the judge's own linguistic
education and experience.' [Citation.] The exclusion of testimony that might
contradict the linguistic background of the judge reflects a judicial belief in
the possibility of perfect verbal expression...."[^beliefs]

[^drayage]: _Pacific Gas & Elec. Co. v. G.W. Thomas Drayage & Rigging Co._
    (1968) 69 Cal. 2d 33, 69 Cal. Rptr. 561, 442 P.2d 641.

[^injurious]: _Pacific Gas & Elec. Co. v. G.W. Thomas Drayage & Rigging Co._,
    _supra_, 69 Cal. 2d 33, 36, 69 Cal. Rptr. 561, 442 P.2d 641.

[^beliefs]: _Pacific Gas & Elec. Co. v. G.W. Thomas Drayage & Rigging Co._,
    _supra_, 69 Cal. 2d 33, 36-37, 69 Cal. Rptr. 561, 442 P.2d 641; _see
    also_, _Southern Pacific Transportation Co. v. Santa Fe Pacific
    Pipelines, Inc._ (1999) 74 Cal. App. 4th 1232, 88 Cal. Rptr. 2d 777
    [court erroneously refused to even consider extrinsic evidence of
    trade usage and custom in evaluating the fair market value of
    pipeline easements].

The court explained the test for admitting extrinsic evidence as an aid in
interpreting contract terms as follows: "The test of admissibility of extrinsic
evidence to explain the meaning of a written instrument is not whether it
appears to the court to be plain and unambiguous on its face, but whether the
offered evidence is relevant to prove a meaning to which the language of the
instrument is reasonably susceptible...."[^testadmit]

[^testadmit]: _Pacific Gas & Elec. Co. v. G.W. Thomas Drayage & Rigging Co._,
    _supra_, 69 Cal. 2d 33, 37, 69 Cal. Rptr. 561, 442 P.2d 641. The
    Supreme Court provided examples of how extrinsic evidence of trade
    usage or custom revealed latent ambiguities in the meaning of
    terms otherwise unambiguous on their face. Such evidence had been
    admitted to show the word "ton" in a lease meant a long ton or
    2,240 pounds and not the statutory ton of 2,000 pounds; the word
    "stubble" in a lease included not only stumps left in the ground
    but everything left on the ground after the harvest; the term
    "north" in a contract dividing mining claims indicated a boundary
    line running along the magnetic and not the true meridian; and a
    form contract for purchase and sale was actually an agency
    contract. (_Pacific Gas & Elec. Co. v. G.W. Thomas Drayage &
    Rigging Co., supra_,69 Cal. 2d 33, 39, fn. 6, 69 Cal. Rptr. 561,
    442 P.2d 641 and cases cited.)

"The fundamental goal of contractual interpretation is to give effect to the
mutual intention of the parties."[^mutualintent] "The mutual intention to which
the courts give effect is determined by objective manifestations of the parties'
intent, including the words used in the agreement, as well as extrinsic evidence
of such objective matters as the surrounding circumstances under which the
parties negotiated or entered into the contract; the object, nature and subject
matter of the contract; and the subsequent conduct of the parties. (Civ.Code, §§
1635-1656; Code Civ. Proc., §§ 1859-1861, 1864; _Hernandez v. Badger
Construction Equipment Co_.(1994) 28 Cal. App. 4th 1791, 1814, 34 Cal. Rptr. 2d
732; 1 Witkin, Summary of Cal. Law (9th ed. 1987) Contracts, §§ 688-689, pp.
621-623.)"[^witkins]

[^mutualintent]: _Bank of the West v. Superior Court_ (1992) 2 Cal. 4th 1254,
    1264, 10 Cal. Rptr. 2d 538, 833 P.2d 545; _Parsons v. Bristol
    Development Co._ (1965) 62 Cal. 2d 861, 865, 44 Cal. Rptr. 767,
    402 P.2d 839.

[^witkins]: _Morey v. Vannucci, supra,_ 64 Cal. App. 4th 904, 912, 75 Cal. Rptr.
    2d 573.

Because there is no evidence in this case of objective manifestations of the
parties' intent,[^manifestations] and because the term at issue is undefined in
the parties' contract, the only way to construe the meaning of the term "gross
receipts" is to consider the nature of the contract and the circumstances under
which the parties negotiated.[^nature] In this case, both the nature of
the contract and the circumstances involved the motion picture industry. The
offered evidence of industry custom and usage revealed the term "gross receipts"
had more than one possible meaning. Thus, the industry expert's statements of
fact were relevant and admissible to expose the latent ambiguity in the contract
language regarding the industry's customary usage of the term. Held's
declaration did not violate the parol evidence rule, as Disney
suggests.[^mickey] On the contrary, the proffered evidence regarding trade usage
and custom was relevant to prove an interpretation to which the agreements were
reasonably susceptible in the entertainment industry context.

[^manifestations]: This is distinct from evidence of the uncommunicated
    subjective intent of two of Disney's employees who
    acknowledged never discussing the term with Wolf or his
    representatives, but who testified they understood the term
    "gross receipts" to mean cash received. These employees
    could only assume Wolf and his representatives had the same
    meaning in mind. Based on these Disney employees' testimony,
    Disney invokes the rule that when a term is found to be
    ambiguous, "it must be interpreted in the sense in which the
    promisor believed, at the time of making it, that the
    promisee understood it." (Civ.Code, § 1649; _Bank of the
    West v. Superior Court_, _supra_, 2 Cal. 4th 1254,
    1264-1265, 10 Cal. Rptr. 2d 538, 833 P.2d 545.) This rule
    does not, as Disney suggests, mean the promisor's subjective
    intent controls. The rule is instead designed to override
    the promisor's subjective intent whenever necessary to
    protect the promisee's objectively reasonable expectations.
    (_Bank of the West v. Superior Court_, _supra_, 2 Cal. 4th
    1254, 1265, 10 Cal. Rptr. 2d 538, 833 P.2d 545.) As we later
    note, Wolf's objectively reasonable expectations at the time
    of negotiations remains a material triable issue of fact.

[^nature]: _See, e.g._, _General Motors Corp. v. Superior Court_ (1993)
    12 Cal. App. 4th 435, 442, 15 Cal. Rptr. 2d 622.

[^mickey]: _Compare_, _Bionghi v. Metropolitan Water Dist. of So. California_
    (1999) 70 Cal. App. 4th 1358, 83 Cal. Rptr. 2d 388 [integrated
    agreement which gave the district the right to cancel the contract on
    30 days' written notice could not be contradicted by the plaintiff's
    proposed additional condition of cancellation only with good cause];
    _General Motors Corp. v. Superior Court_, _supra_, 12 Cal. App. 4th
    435, 15 Cal. Rptr. 2d 622 [current counsel who had not negotiated
    settlement and release agreement could not offer competent testimony
    regarding the contracting parties' subjective intent when executing
    the agreement].

The Supreme Court discussed the rule regarding the admission of trade usage and
custom in _Ermolieff v. R.K.O. Radio Pictures, Inc_.[^scotus] In _Ermolieff_ the
parties were producers and distributors in the motion picture industry. The
plaintiff had reserved distribution rights in all countries not listed in an
exhibit attached to the contract. The exhibit listed the United Kingdom as an
area for which plaintiff had assigned his distribution rights. A dispute arose
over the question whether Ireland, or the "Free Irish State," was included
within the global term "United Kingdom." The plaintiff argued the plain language
of the contract made clear Ireland was excluded because it was not a part of the
United Kingdom. The studio countered including Ireland within the term "United
Kingdom" was the custom and practice in the motion picture industry and such
usage was part of the contract.[^ireland] BOTH PARTIES SOUGHT declaratory
relief.

[^scotus]: _Ermolieff v. R.K.O. Radio Pictures, Inc._ (1942) 19 Cal. 2d 543, 122
    P.2d 3.

[^ireland]: _Ermolieff v. R.K.O. Radio Pictures, Inc._, _supra_, 19 Cal. 2d 543,
    545-546, 122 P.2d 3.

At the close of the plaintiff's case the trial court ruled the evidence of trade
usage incompetent, struck the defendant's evidence, and entered judgment in
favor of the plaintiff.[^incompetent] The Supreme Court reversed. "The correct
rule with reference to the admissibility of evidence as to trade usage under the
circumstances here presented is that while words in a contract are ordinarily to
be construed according to their plain, ordinary, popular or legal meaning, as
the case may be, yet if in reference to the subject matter of the contract,
particular expressions have by trade usage acquired a different meaning, and
both parties are engaged in that trade, the parties to the contract are deemed
to have used them according to their different and peculiar sense as shown by
such trade usage. Parol evidence is admissible to establish the trade usage, and
that is true even though the words are in their ordinary or legal meaning
entirely unambiguous, inasmuch as by reason of the usage the words are used by
the parties in a different sense. [Citations.] The basis of this rule is that to
accomplish a purpose of paramount importance in interpretation of documents,
namely, to ascertain the true intent of the parties, it may well be said that
the usage evidence does not alter the contract of the parties, but on the
contrary gives the effect to the words there used as intended by the parties.
The usage becomes a part of the contract in aid of its correct
interpretation."[^aid]

[^incompetent]: _Ermolieff v. R.K.O. Radio Pictures, Inc._, _supra_, 19 Cal. 2d
    543, 546, 122 P.2d 3.

[^aid]: _Ermolieff v. R.K.O. Radio Pictures, Inc._, _supra_, 19 Cal. 2d 543,
    550, 122 P.2d 3.

In Ermolieff the trial court at least considered the proffered extrinsic
evidence throughout the plaintiff's entire case-in-chief. In the present case,
by contrast, the trial court rejected the evidence after reading the expert's
declaration and questioning Wolf on its content. Yet, this extrinsic evidence of
trade usage exposed a latent ambiguity in the contract language and presented an
alternative interpretation to which the term "gross receipts" was reasonably
susceptible in the circumstances. Accordingly, we conclude the trial court erred
in rejecting the extrinsic evidence and in concluding the term "gross receipts"
was not reasonably susceptible to the interpretation urged by Wolf that
according to industry custom and usage "gross receipts" meant cash and other
valuable consideration received.

**III. THE CONFLICTING INTERPRETATIONS OF THE CONTRACT TERM RAISE FACTUAL ISSUES
WHICH PRECLUDE A DETERMINATION AS A MATTER OF LAW.**

Having determined the contract is reasonably susceptible to the meaning given it
by Wolf, we address the second step in the analysis: the ultimate construction to
be placed on the ambiguous language. As noted, where no extrinsic evidence is
introduced or the evidence is not in conflict, an appellate court will
independently construe the contract.[^noconflict] "Where, however, a conflict in
the evidence exists, it must be resolved in the trial court, as with any
question of fact, before the court can declare the meaning of the contract as a
matter of law."[^yesconflict]

[^noconflict]: _Parsons v. Bristol Development Co._, _supra_, 62 Cal. 2d 861,
    866, 44 Cal. Rptr. 767, 402 P.2d 839.

[^yesconflict]: _Southern Cal. Edison Co. v. Superior Court_ (1995) 37 Cal. App.
    4th 839, 852, 44 Cal. Rptr. 2d 227; _see also_, _Walter E.
    Heller Western, Inc. v. Tecrim Corp._ (1987) 196 Cal. App. 3d
    149, 158, 241 Cal. Rptr. 677 ["(w)hen two equally plausible
    interpretations of the language of a contract may be made ...
    parol evidence is admissible to aid in interpreting the
    agreement, thereby presenting a question of fact which precludes
    summary judgment if the evidence is contradictory."].

From what this court has observed earlier, it is apparent triable issues of fact
remain regarding the proper meaning to be given the term "gross receipts," thus
precluding our independent interpretation of the contract as a matter of law. By
way of example only, Disney claims it receives nothing from the noncash alliance
agreements. In the alternative, Disney argues even if it derives some intrinsic
benefit from participating in joint promotions, it is not feasible for third
parties to ascribe values to these promotional activities unless Disney receives
cash. Disney thus claims under Wolf's interpretation it would be impossible to
comply with its contract obligation to provide an accounting for fictional
benefits allegedly derived from noncash alliance agreements.

Wolf, by contrast, asserts Disney and its vast enterprises receive benefits from
the third party promotions in the form of good will, increased theme part
attendance, increased merchandise sales, film attendance and the like, most of
these benefits not reflected in increased royalty payments to Wolf. For these
reasons, Wolf claims attribution of monetary values for in-kind promotional
activities is a routine matter in the entertainment industry.

The reasonableness of the competing interpretations thus must be tested in light
of these concerns.

Also as noted, neither side presented any direct or objective evidence regarding
the negotiating parties' understanding of the term "gross receipts" at the time
the parties entered into the contract. Accordingly, Wolf's and Disney's
objectively reasonable expectations regarding the scope of the term when they
agreed to the contract remain additional triable issues of material fact.

**DISPOSITION**

Let a peremptory writ issue directing the trial court to vacate its order
granting the motion for summary adjudication of the cross-complainant's first,
fourth and seventh causes of action for declaratory relief and to enter a new
and different order denying said motion. Petitioners are entitled to costs in
this proceeding.

We concur: PERLUSS, P.J., and WOODS, J.

**Discussion**

1.  In light of the court's reasoning in _Wolf_, if evidence of prevailing trade
    usage is only available from dates after a Licensee XYZ contracted under the
    terms of an open source license, would that evidence be considered in
    determining the meaning of an ambiguous term in that license with respect to
    Licensee XYZ? Or would such evidence only be considered for subsequent
    licensees likely aware of the usage of trade?
1.  Would a discussion thread on StackOverflow meet the threshold of being
    evidence of widespread trade usage? Consider the following discussion of
    what the "sublicense" permission means in the Apache 2 license:
    [https://opensource.stackexchange.com/questions/6288/can-i-change-the-copyright-license-with-this-text-in-the-cla](https://opensource.stackexchange.com/questions/6288/can-i-change-the-copyright-license-with-this-text-in-the-cla)
    \
    If a discussion thread contained unanimous agreement on the meaning of a
    particular term, would that be sufficient to establish trade usage?
1.  Similarly, consider what happens when one organization promotes its
    unilateral understanding of a license term in a blog post years after the
    open source license has gained widespread adoption. What standard of
    widespread shared understanding would this unilateral blog post need to
    reach in order to meet the standard of usage in trade evidence? Would it be
    effective retroactively, prior to the publication of the blog post?

<!-- Footnotes themselves at the bottom. -->

## Notes



