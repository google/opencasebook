# Patents in Open Source

{:.no_toc}

* Table of Contents
{:toc}

## Introduction

The relationship between the patent system and software hasn't always been
clear. Software is a unique construction, incorporating both creative and
functional aspects. While creative aspects of software are protected under
copyright law, the functional aspects of software may be protectable via
patent law.[^PatentabilityDiscussion] The interaction between patent law 
and open source licenses is the focus of this chapter.

A patent gives its owner the right to exclude others from making, using,
and selling the claimed invention.[^35USC271abc] In contrast, open source
licenses grant broad rights to modify, compile, distribute, and use the
software. Absent explicit treatment in the license, the patent-related right
to exclude and the open-source-granted right to use are at least apparently
in tension.

A number of open source licenses[^OpenSourceLicensesWithGrants] address
this tension explicitly by including a patent grant in the text of the license.
However, just seeing the word "patent" or not in an open source license is
not enough to identify whether there is an effective grant of patent rights.
For example, the Open Source Initiative has stated its view that all open
source licenses implicitly include a patent grant, relying on the text of
elements 1 and 7 of the open source definition.[^OpenSourceDefinition1and7]
Further, even when there is an explicit patent grant, the scope of the patent
grant may not be well-defined. Finally, the distribution of open
source-licensed software may have implications for patent exhaustion.

This chapter presents materials related to four separate but related issues:

1. **Explicit licenses:** Express language in open source licenses granting
  patent licenses;
2. **Implicit Licenses:** The existence and scope of implied patent licenses
  in open source licenses;
3. **Express but Non-specific Licenses:** Express grants in open source
  licenses that do not include the term "patent;" and
4. **Patent Exhaustion:** The doctrine of patent exhaustion and its
  applicability to the distribution of open source software.


[^PatentabilityDiscussion]: The exact scope of what is patentable within a software program is subject to debate, and has changed over time. This discussion, however, assumes that there is some software, released under open source licenses, that is both patent-eligible and implicates one or more valid patent claims.

[^35USC271abc]: _See_ the text of 35 U.S.C. 271 and discussion _infra_, laying out the scope of the unique rights granted to a patent owner.

[^OpenSourceLicensesWithGrants]: _See_ the examples of explicit patent grants and discussion _infra_.

[^OpenSourceDefinition1and7]: _See The Open Source Definition - Annotated_, elements one and seven: <br />1\. _Free Redistribution_: The license shall not restrict any party from selling or giving away the software as a component of an aggregate software distribution containing programs from several different sources. The license shall not require a royalty or other fee for such sale.<br />7\. _Distribution of License_: The rights attached to the program must apply to all to whom the program is redistributed without the need for execution of an additional license by those parties. Open Source Initiative, [https://opensource.org/osd-annotated](https://opensource.org/osd-annotated) (Open Source Definition-Annotated) (CC-BY 4.0)

## Statutory Law

Each area of intellectual property law reserves particular rights to the
owner of the corresponding intellectual property. The exclusive rights
granted under copyright law are different than the exclusive rights
granted under patent law.

--------------------------------------------------------------------------------
### 17 U.S.C. § 106 - Exclusive rights in copyrighted works

Subject to sections 107 through 122, the owner of copyright under this
title has the exclusive rights to do and to authorize any of the following:

  1. to reproduce the copyrighted work in copies or phonorecords;
  2. to prepare derivative works based upon the copyrighted work;
  3. to distribute copies or phonorecords of the copyrighted work to the
    public by sale or other transfer of ownership, or by rental, lease,
    or lending;
  4. in the case of literary, musical, dramatic, and choreographic works,
    pantomimes, and motion pictures and other audiovisual works, to perform
    the copyrighted work publicly;
  5. in the case of literary, musical, dramatic, and choreographic works,
    pantomimes, and pictorial, graphic, or sculptural works, including the
    individual images of a motion picture or other audiovisual work, to
    display the copyrighted work publicly; and
  6. in the case of sound recordings, to perform the copyrighted work
    publicly by means of a digital audio transmission.

--------------------------------------------------------------------------------
### 35 U.S.C. 271 - Infringement of patent

(a) Except as otherwise provided in this title, whoever without authority
makes, uses, offers to sell, or sells any patented invention, within the
United States, or imports into the United States any patented invention
during the term of the patent therefor, infringes the patent.

--------------------------------------------------------------------------------

Open source license analysis begins with the text of the governing statutes.
Each license grants to users one or more rights that would otherwise be
exclusive to the rightsholder. For both patents and copyrights, there are key
terms associated with each right that usually appear in the license text,
although in some cases license authors have chosen to use new terms or
imprecise language.

The function of the court system is to interpret the license texts in light of
the statutory grants to identify the extent to which a licensor has given
permission for the person receiving the code to do things that would otherwise
infringe on the applicable patent.

## Explicit Patent Licensing

### Selections from Open Source Licenses

About half of all open source licenses include express patent grants, but
the scope of those licenses may vary depending upon the language of the
grant. Below are a number of widely-used or noteworthy open source licenses
that expressly include a patent grant.

--------------------------------------------------------------------------------
#### Academic Free License 3.0
Excerpt from the Academic Free License, Version 3.0[^AFL]

**2) Grant of Patent License.** Licensor grants You a worldwide,
royalty-free, non-exclusive, sublicensable license, under patent claims
owned or controlled by the Licensor that are embodied in the Original Work
as furnished by the Licensor, for the duration of the patents, to make,
use, sell, offer for sale, have made, and import the Original Work and
Derivative Works.

[^AFL]: _Academic Free License, Version 3.0_, Lawrence Rosen, 2002, *available at* [https://opensource.org/licenses/AFL-3.0] (https://opensource.org/licenses/AFL-3.0)  (2002). *See also* Rosen, "OSL 3.0: A Better License for Open Source Software," (2007), *available at* [http://rosenlaw.com/OSL3.0-explained.htm](http://rosenlaw.com/OSL3.0-explained.htm)

--------------------------------------------------------------------------------
#### Apache 2.0
Excerpt from the Apache License, Version 2.0[^Apache2]

**6\. Grant of Patent License.**
Subject to the terms and conditions of this License, each Contributor hereby
grants to You a perpetual, worldwide, non-exclusive, no-charge, royalty-free,
irrevocable (except as stated in this section) patent license to make, have
made, use, offer to sell, sell, import, and otherwise transfer the Work,
where such license applies only to those patent claims licensable by such
Contributor that are necessarily infringed by their Contribution(s) alone
or by combination of their Contribution(s) with the Work to which such
Contribution(s) was submitted....

[^Apache2]: _Apache License, Version 2.0_, Apache Foundation, *available at* [https://www.apache.org/licenses/LICENSE-2.0](https://www.apache.org/licenses/LICENSE-2.0) (Jan. 2004).

--------------------------------------------------------------------------------
#### Eclipse Public License version 2.0
Excerpt from the Eclipse Public License, Version 2[^EPL2]

**2\. GRANT OF RIGHTS**
\[...\] b) Subject to the terms of this Agreement, each Contributor hereby
grants Recipient a non-exclusive, worldwide, royalty-free patent license
under Licensed Patents to make, use, sell, offer to sell, import and
otherwise transfer the Contribution of such Contributor, if any, in Source
Code or other form. This patent license shall apply to the combination of
the Contribution and the Program if, at the time the Contribution is added
by the Contributor, such addition of the Contribution causes such
combination to be covered by the Licensed Patents. The patent license shall
not apply to any other combinations which include the Contribution. No
hardware per se is licensed hereunder.

[^EPL2]: _Eclipse Public License, Version 2.0_, *available at*  [https://opensource.org/licenses/EPL-2.0] (https://opensource.org/licenses/EPL-2.0) (2017).


#### GNU General Public License 2.0
--------------------------------------------------------------------------------
Excerpt from the GNU General Public License License, Version 2.0[^GPL2]

**Preamble**

\[...\] Finally, any free program is threatened constantly by software
patents. We wish to avoid the danger that redistributors of a free program
will individually obtain patent licenses, in effect making the program
proprietary. To prevent this, we have made it clear that any patent must
be licensed for everyone's free use or not licensed at all.

\[...\]

7\. If, as a consequence of a court judgment or allegation of patent
infringement or for any other reason (not limited to patent issues),
conditions are imposed on you (whether by court order, agreement or
otherwise) that contradict the conditions of this License, they do not
excuse you from the conditions of this License. If you cannot distribute
so as to satisfy simultaneously your obligations under this License and
any other pertinent obligations, then as a consequence you may not
distribute the Program at all. For example, if a patent license would
not permit royalty-free redistribution of the Program by all those who
receive copies directly or indirectly through you, then the only way you
could satisfy both it and this License would be to refrain entirely from
distribution of the Program.


[^GPL2]: _GNU General Public License, Version 2.0_, 1991, *available at* [https://opensource.org/licenses/GPL-2.0] (https://opensource.org/licenses/GPL-2.0).

--------------------------------------------------------------------------------
#### GNU General Public License 3.0
Excerpt from the GNU General Public License License, Version 3.0[^GPL3]

**11\. Patents.**

A "contributor" is a copyright holder who authorizes
use under this License of the Program or a work on which the Program is
based. The work thus licensed is called the contributor's "contributor
version".

A contributor's "essential patent claims" are all patent claims owned
or controlled by the contributor, whether already acquired or hereafter
acquired, that would be infringed by some manner, permitted by this License,
of making, using, or selling its contributor version, but do not include
claims that would be infringed only as a consequence of further
modification of the contributor version. For purposes of this definition,
"control" includes the right to grant patent sublicenses in a manner
consistent with the requirements of this License.

Each contributor grants you a non-exclusive, worldwide, royalty-free
patent license under the contributor's essential patent claims, to make,
use, sell, offer for sale, import and otherwise run, modify and propagate
the contents of its contributor version.

In the following three paragraphs, a "patent license" is any express
agreement or commitment, however denominated, not to enforce a patent (such
as an express permission to practice a patent or covenant not to sue for
patent infringement). To "grant" such a patent license to a party means
to make such an agreement or commitment not to enforce a patent against
the party.

If you convey a covered work, knowingly relying on a patent license, and
the Corresponding Source of the work is not available for anyone to copy,
free of charge and under the terms of this License, through a publicly
available network server or other readily accessible means, then you
must either (1) cause the Corresponding Source to be so available, or
(2) arrange to deprive yourself of the benefit of the patent license for
this particular work, or (3) arrange, in a manner consistent with the
requirements of this License, to extend the patent license to downstream
recipients. "Knowingly relying" means you have actual knowledge that,
but for the patent license, your conveying the covered work in a country,
or your recipient's use of the covered work in a country, would infringe
one or more identifiable patents in that country that you have reason to
believe are valid.

If, pursuant to or in connection with a single transaction or arrangement,
you convey, or propagate by procuring conveyance of, a covered work, and
grant a patent license to some of the parties receiving the covered work
authorizing them to use, propagate, modify or convey a specific copy of
the covered work, then the patent license you grant is automatically
extended to all recipients of the covered work and works based on it.

A patent license is "discriminatory" if it does not include within the
scope of its coverage, prohibits the exercise of, or is conditioned on
the non-exercise of one or more of the rights that are specifically
granted under this License. You may not convey a covered work if you are
a party to an arrangement with a third party that is in the business of
distributing software, under which you make payment to the third party
based on the extent of your activity of conveying the work, and under
which the third party grants, to any of the parties who would receive
the covered work from you, a discriminatory patent license (a) in
connection with copies of the covered work conveyed by you (or copies made
from those copies), or (b) primarily for and in connection with specific
products or compilations that contain the covered work, unless you entered
into that arrangement, or that patent license was granted, prior to 28
March 2007.

Nothing in this License shall be construed as excluding or limiting any
implied license or other defenses to infringement that may otherwise be
available to you under applicable patent law.

[^GPL3]: _GNU General Public License, Version 3.0_, *available at* [https://opensource.org/licenses/GPL-3.0] (https://opensource.org/licenses/GPL-3.0) (2007). *See also* Smith, "A Quick Guide to GPLv3," (2007), *available at* [https://www.gnu.org/licenses/quick-guide-gplv3.html](https://www.gnu.org/licenses/quick-guide-gplv3.html) and Stallman, "Why Upgrade to GPLv3," (2007), *available at* [https://www.gnu.org/licenses/rms-why-gplv3.html](https://www.gnu.org/licenses/rms-why-gplv3.html).


--------------------------------------------------------------------------------
#### Mozilla Public License 2.0
Excerpt from the Mozilla Public License, Version 2.0[^MPL2]

**2\. License Grants and Conditions**

**2\.1\. Grants**

Each Contributor hereby grants You a world-wide, royalty-free,
non-exclusive license:

\[...\] under Patent Claims of such Contributor to make, use, sell, offer
for sale, have made, import, and otherwise transfer either its
Contributions or its Contributor Version.

\[...\]

**2\.3\. Limitations on Grant Scope**

The licenses granted in this Section 2 are the only rights granted
under this License. No additional rights or licenses will be implied
from the distribution or licensing of Covered Software under this
License. Notwithstanding Section 2.1(b) above, no patent license is
granted by a Contributor:

for any code that a Contributor has removed from Covered Software; or

for infringements caused by:

 1. Your and any other third party's modifications of Covered Software, or
 2. the combination of its Contributions with other software (except as
 part of its Contributor Version); or
 3. under Patent Claims infringed by Covered Software in the absence of its
 Contributions.

[^MPL2]: _Mozilla Public License, Version 2.0_, *available at* [https://opensource.org/licenses/MPL-2.0] (https://opensource.org/licenses/MPL-2.0) (2012).
___

#### Discussion

1. How does the wording of the grant affect its scope? For example, what
  are the substantive differences in scope between grants covering:

    - "patent claims ... embodied in the Original Work as furnished by the Licensor" (AFL3)

    - "patent claims ... that are necessarily infringed by their
  Contribution(s) alone or by combination of their Contribution(s) with
  the Work to which such Contribution(s) was submitted" (Apache2)

    - "combination of the Contribution and the Program if ... such addition of
  the Contribution causes such combination to be covered by the Licensed
  Patents" (EPL2)

    - "patent claims owned or controlled by the contributor, whether already
  acquired or hereafter acquired, that would be infringed by some manner,
  permitted by this License, of making, using, or selling its contributor
  version, but do not include claims that would be infringed only as a
  consequence of further modification of the contributor version." (GPL3)

2. How do the different open source licenses treat the licensing of
  subsequent derivative works? Can patent-claim-implementing code be
  extracted from an open source project and used in a different context?

3. How do the different licenses treat the issue of later-acquired patent
  rights?

4. The GNU General Public License, version 2, purports to condition the use
  of the code on the statement that any applicable patent "must
  be licensed for everyone's free use or not licensed at all." Is this
  language effective as a patent license?


## Implied Patent Licenses

Open source software licenses are designed to spread: They maximize the ease
of distribution and minimize the friction associated with ordinary license
negotiations. Typically, an open source license is self-executing
[^SelfExecuting], meaning that the a new license grant is automatically given
to each person receiving a copy of the covered work upon receipt. As
described in _De Forest_, this act of freely licensing the source code may
give rise to an implied patent license:[^ImpliedLicense]

> Any language used by the owner of the patent, or any conduct on his part
> exhibited to another from which that other may properly infer that the
> owner consents to his use of the patent in making or using it, or selling
> it, upon which the other acts, constitutes a license and a defense to an
> action for a tort.

[^SelfExecuting]: *See, e.g.*, section 10 of the GNU General Public License, version 3: 10. _Automatic Licensing of Downstream Recipients._ Each time you convey a covered work, the recipient automatically receives a license from the original licensors, to run, modify and propagate that work, subject to this License.

[^ImpliedLicense]: _De Forest Radio Telephone Co. v. United States_, 273 U.S. 236, 241 (1927), _available at_ https://casetext.com/case/de-forest-co-v-united-states


As you read this case and the follow-on cases that have further refined the
scope of implied licenses, think about whether any of a) the statements in
the license itself, b) the actions of the licensor in applying the open
source license and distributing copies to the public, or c) the
self-executing nature of open source licenses may reasonably give rise to an
implied patent license.

### Cases

#### De Forest Radio Telephone Co. v. United States

--------------------------------------------------------------------------------
United States Supreme Court (1927)[^DeForestHeadnote]

[^DeForestHeadnote]: _De Forest Radio Telephone Co. v. United States_, 273 U.S. 236, 47 S. Ct. 366 (1927), _available at_ [https://casetext.com/case/de-forest-co-v-united-states](https://casetext.com/case/de-forest-co-v-united-states)


MR. CHIEF JUSTICE TAFT delivered the opinion of the Court.

This is an appeal from a judgment of the Court of Claims dismissing the
petition of the appellant, on the 4th of May, 1925. This was before the
effective date of the Act of February 13, 1925, c. 229, 43 Stat. 936, by which
direct appeals from the Court of Claims under §§ 242 and 243 of the Judicial
Code were repealed and the review by certiorari was substituted.

The De Forest Radio Telephone Telegraph Company filed its petition in the Court
of Claims against the United States, seeking to recover for an alleged unlawful
use by the Government of certain patented vacuum tubes or audions, used in
radio communication. The suit was brought under the Act of June 25, 1910, c.
423, 36 Stat. 851, as amended by the Act of July 1, 1918, c. 114, 40 Stat. 704,
705\. The Act of 1910 provided that whenever an invention described in and
covered by a patent of the United States should thereafter be used by the
Government without license of the owner or lawful right to use it, the owner
could recover reasonable compensation for the use in the Court of Claims,
provided that the United States could avail itself of all defenses, general or
special, which might be pleaded by any other defendant charged with
infringement. The amending Act of 1918 enlarged the scope of the Act by
providing that the recovery by the owner should include compensation for
patented inventions used or made by or for the United States.

The petition showed, that the two patents involved in the suit were granted to
De Forest and by him were duly assigned to the appellant, the company bearing
his name, and that that company executed and delivered to the Western Electric
Company a written instrument conveying certain rights in the patents, which
were subsequently conveyed to the American Telephone Telegraph Company. This
contract was set out in the petition. In consideration of one dollar and other
good and valuable considerations, it granted a license to make, use, install,
operate and lease, and to sell or otherwise dispose of to others for sale,
installation and operation, apparatus and systems embodying or made or
operating in accordance with the invention. It purported to give this license
for the full terms of the patents and for all transferable rights of the De
Forest Company in the inventions, except such as were expressly reserved by
that company. The reservations included nonassignable rights for the purpose of
making the articles in question for, and selling them to, the United States
Government for its use. The instrument further provided that the Western
Company and the De Forest Company might respectively institute and conduct
suits against others for any of the patents within the fields in which each
respectively possessed rights, but that all such suits should be conducted at
the expense of the party bringing them, that party to retain any judgment
recovered in any such suits.

Paragraph 12 of the instrument provided that the Western Company might transfer
to others, in whole or in part, the rights granted by the instrument, and might
assign rights thereunder, or grant licenses, to various persons, firms or
corporations for the several uses to which the inventions were applicable. The
petition further alleges that the United States, being engaged in war, informed
the American Telephone Telegraph Company that it desired to have large numbers
of the audions made promptly for it by the General Electric Company and others;
and that the American Telephone Telegraph Company replied by writing to the
Chief Signal officer of the Army that it would not do anything to interfere
with the immediate manufacture of the audions, provided it were understood and
agreed that the Telephone Telegraph Company "waived none of its claims under
any patents or patent rights owned by it on account of said manufacture, and
that all claims under patent rights and all patent questions be reserved and
later investigated, adjusted and settled by the United States." The plan was
accepted by the United States, and the orders for said audions were thereafter
given by the United States to the General Electric Company and the Moorhead
Laboratories, Inc., who made them and delivered them to the Government, which
used them.

The petition further alleged, that, for the purposes of assisting the United
States to obtain said audions promptly, pursuant to the orders given, the
American Telephone Telegraph Company furnished information, drawings and
blueprints to the General Electric Company, and permitted representatives and
experts of the United States and of said General Electric Company to witness
and study the manufacture of said audions by the Telephone Telegraph Company,
all to the end that the audions might be the more promptly made and delivered
to the United States for use in the war in which it was then engaged.

After the filing of the petition in the suit, it was amended by an averment
that, after the audions were made and used by the United States, negotiations
were carried on between it and the American Telephone Company, and that the
latter company executed a release to the United States and all manufacturers
acting under its orders of all claims for compensation for the making and use
of the audions, and that the release included "all claims which had arisen or
might thereafter arise, for royalties, damages, profits or compensation for
infringement of any or all letters patent owned or controlled by the Telephone
Telegraph Company, whether expressly recited therein or not, for the
manufacture or use prior thereto, and for use by the United States occurring
thereafter."

The petition was demurred to, the demurrer was sustained and the petition
dismissed. It is conceded by the parties that, on the face of the petition,
with the contracts which were made exhibits, the De Forest Company and the
American Telephone Telegraph Company had each the right to license to the
United States the making and use of these audions, and that, if either did so
license them, it would be a complete defense to a claim by the other for
damages for the tort of infringement.

The sole question, therefore, which the Court of Claims considered, and decided
against the appellant, was whether on the facts recited in the petition the
American Telephone Telegraph Company had in fact given a license to the United
States to have made and to use these audions, covered by the patents. In other
words, was the claim which the American Telephone Telegraph Company had against
the United States for the manufacture and use of the audions, based on a
contract, or was it based on a tort? If it was the former, it was a full
defense to any claim by the De Forest Company. If it was the latter, the De
Forest Company was entitled to recover under the Act of 1918.

The appellant says that the necessary effect of the allegations of its petition
is, that the Telephone Company said to the United States, in answer to the
United States' notice that it wished to make and use the audions, "You will be
infringing my rights. I shall not stop you but I notify you that I shall hold
you for such infringement," and therefore that the subsequent acts of the
United States and its manufacturers were torts. We think a different
construction should be given the allegations. The agreement by the Telephone
Company that it would not do anything to interfere with the immediate making of
the audions for the United States, interpreted in the light of its subsequent
action in assisting the United States to a prompt making of the audions for its
use, in furnishing the needed information and drawings and blueprints for such
manufacture, and in giving to the experts of the United States and its
manufacturers the opportunity to witness and study the manufacture of audions
by the Telephone Company, to the end that the audions might be more promptly
manufactured and delivered to the United States for use in the war, made such
conduct clearly a consent to their manufacture and use, and a license, and this
without any regard to the effect of the subsequent release by the Telephone
Telegraph Company of compensation for such manufacture and use. No formal
granting of a license is necessary in order to give it effect. Any
language used by the owner of the patent, or any conduct on his part exhibited
to another from which that other may properly infer that the owner consents to
his use of the patent in making or using it, or selling it, upon which the
other acts, constitutes a license and a defense to an action for a tort.
Whether this constitutes a gratuitous license, or one for a reasonable
compensation, must of course depend upon the circumstances; but the relation
between the parties thereafter, in respect of any suit brought, must be held to
be contractual and not based on unlawful invasion of the rights of the owner.
Concede that if the owner had said, "If you go on and infringe my patent, I
shall not attempt to enjoin you, but I shall subsequently sue you for
infringement," the tort would not be waived — that is not this case. Here the
circumstances show clearly that what the Company was doing was not only fully
consenting to the making and using by the United States of the patent, but was
aiding such making and using and, in doing so, was licensing it, only
postponing to subsequent settlement what reasonable compensation, if any, it
might claim for its license. The case of _Henry v. Dick_, 224 U.S. 1, in
its main point was overruled in the _Motion Picture Patents Company v.
Universal Film Company_, 243 U.S. 502; but that does not shake the authority
of the language of the Court in the following passage (p. 24):

"If a licensee be sued, he can escape liability to the patentee for the use of
his invention by showing that the use is within his license. But if his use be
one prohibited by the license, the latter is of no avail as a defense. As a
license passes no interest in the monopoly, it has been described as a mere
waiver of the right to sue by the patentee," citing Robinson on Patents, §§ 806
and 808.

In this case the language used certainly indicated the purpose of the Telephone
Company not to seek an injunction against infringement, and not to sue for
damages therefor, but only to sue or seek for an amicable settlement by payment
of just compensation. Such action by the Telephone Company was a license, and
constituted a complete defense against a suit for infringement by the De Forest
Company.

*Judgment affirmed.*

#### Wang Laboratories, Inc. v. Mitsubishi Electonics America, Inc.

--------------------------------------------------------------------------------
_Wang Labs., Inc. v. Mitsubishi Elecs. Am., Inc._, Fed. Cir. 1997 [^WangHeadnote]

[^WangHeadnote]: _Wang Labs., Inc. v. Mitsubishi Elecs. Am., Inc._, 103 F.3d 1571, 1583 (Fed. Cir. 1997), _available at_ [https://caselaw.findlaw.com/us-federal-circuit/1201198.html](https://caselaw.findlaw.com/us-federal-circuit/1201198.html)

**BACKGROUND**

James Clayton, the named inventor in the patents in suit, joined Wang
Laboratories in the fall of 1982. At the time, computer memory components
remained relatively large, expensive, and difficult to upgrade. In the
spring of 1983, Clayton developed the SIMM as a smaller, lower cost,
replaceable form of computer memory. On September 2, 1983, Clayton, with
Wang as assignee, applied for a patent on the SIMM invention, application
serial number 528,817.

\[...\]

Mitsubishi first met with Wang regarding SIMMs in December 1983. In their
meetings, Wang supplied drawings and other details to Mitsubishi and
repeatedly requested that Mitsubishi manufacture SIMMs. Mitsubishi
researched the possibility of producing SIMMs for Wang, but did not proceed
with the project at that time. After Mitsubishi began making 256K memory
chips, however, Mitsubishi decided to assemble 256K SIMMs, incorporating the
new chips into a SIMM similar to Wang's, for sale to Wang and others.
Mitsubishi declined to assess engineering costs to Wang, contrary to its
asserted practice when creating a custom product exclusively for a particular
purchaser.

In 1985 meetings, in the context of ongoing contacts between the two
companies, Mitsubishi and Wang discussed Mitsubishi's new 256K SIMMs.
[Footnote Omitted] In one meeting, Clayton suggested that Mitsubishi modify
its SIMM by placing the decoupling capacitors on the same side of the substrate
with the chips, as in the original Wang design. Mitsubishi complied.
Mitsubishi went on to mass produce 256K SIMMs; and in 1987, Wang began
buying Mitsubishi SIMMs. Wang never informed Mitsubishi of its patent
applications, patents, or of any intent to execute a license or receive
royalties until a December 22, 1989 letter accusing Mitsubishi of infringing
the '605 and '513 patents, which had issued in 1987 and 1988 respectively.

Wang sued Mitsubishi for infringement on June 4, 1992, in the United States
District Court for the Eastern District of Virginia. Wang argued that
Mitsubishi literally infringed the '513 patent and infringed the '605 patent
under the doctrine of equivalents. Mitsubishi had the case transferred to
the United States District Court for the Central District of California and
filed counterclaims seeking a declaratory judgment of invalidity,
non-infringement, and unenforceability, as well as alleging assorted state
and federal antitrust violations. Mitsubishi also asserted several
affirmative defenses, including the defense that Wang's conduct created an
implied license.

\[...\]

...Wang and Mitsubishi fought over the formulation of the implied license
instruction to the jury. Wang submitted legal estoppel language; Mitsubishi
objected and offered equitable estoppel or estoppel by conduct as the basis
of its license. The final instruction merged the parties' competing proposals
into one instruction which read as follows:

> One who owns a patent as patentee or assignee, having the right to exclude
> others from making, using, or selling what is claimed, may agree to let
> another do one or more of those acts. This is called a license, and the
> person allowed to do the set of acts is a licensee.
>
> An implied license is a form of implied-in-fact contract. In order to
> proved [sic] the defense of implied license, [\Mitsubishi] must
> establish by a preponderance of the evidence that (1) there was an
> existing relationship between Wang and [Mitsubishi]; (2) within
> that relationship, Wang transferred a right to use SIMM invention to
> [Mitsubishi]; (3) the right was transferred for valuable
> consideration; and (4) Wang has now denied the existence of the right
> it transferred to [Mitsubishi].
>
> In deciding whether [Mitsubishi has] proved the existence of an implied
> license, you may consider statements and conduct of Wang from which one
> would reasonably infer Wang's consent to Mitsubishi's making, using, or
> selling products to persons other than Wang under the patents.
>
> If you find that a right to make, use, or sell the SIMM invention
> granted to [Mitsubishi] then you should find and [sic] implied
> license was granted to [Mitsubishi] by Wang.

The relevant question to the jury on the Special Verdict Form read, "Has
Mitsubishi proven by a preponderance of the evidence that Wang licensed
Mitsubishi to make, use, or sell the subject matter of the '513 patent?.
The jury answered "Yes." \[...\]

After the verdict, the court held a hearing on Mitsubishi's equitable
defenses, then directed Wang to draft a proposed judgment and findings of
fact and conclusions of law adopting the jury's determinations on the
equitable defenses, which Wang did. Mitsubishi objected to Wang's drafts
and protested that, although the findings and conclusions did not cover the
implied license, Wang wrote findings on other issues which contradicted and
undermined the jury's implied license verdict. Furthermore, Wang had
written that the jury found an implied license, "under the doctrine of legal
estoppel.. Notwithstanding Mitsubishi's objections, the court entered both
the Judgment and the Findings of Fact and Conclusions of Law.

On March 6, 1995, the parties argued six motions to the district court.
Wang's motions addressed the implied license defense. First, Wang moved
for Rule 50(b) JMOL because Wang believed that no reasonable jury could find
Mitsubishi provided valuable consideration for a license, as required by
Wang's formulation of implied license elements based on legal estoppel.
Second, Wang sought a partial new trial on the implied license defense.
Third, Wang moved to amend the judgment based on its theory that the implied
license conclusion mandated a finding that an implied contract existed and
that, assuming an absence of other consideration, Mitsubishi must have
promised royalties to Wang.

\[...\]

**ANALYSIS**

Wang appeals the partial summary judgment of non-infringement of the '605
patent based on prosecution history estoppel, and the resolution of the
implied license issue to negate infringement of the '513 patent.
Mitsubishi cross-appeals from the judgment on best mode, nonobviousness,
and infringement.

\[...\]

**The '513 Patent: Implied License**

Mitsubishi argued at trial that Wang's conduct had created an implied
license to it under the '513 patent. The parties agreed to submit
Mitsubishi's implied license defense to the jury and the jury found an
implied license to exist. The district court entered judgment on the
verdict, and added the rationale that the implied license arose "under the
doctrine of legal estoppel. Focusing on the legal estoppel rationale,
Wang moved for JMOL or a new trial on the implied license issue because,
according to Wang, a reasonable jury could not have found facts to support
legal estoppel and because the court misapplied the law of legal estoppel.
See Fed.R.Civ.P. 50(b) and 59(a). Wang also moved the court to infer
contract terms requiring Mitsubishi to pay royalties to Wang as part of the
implied license. See Fed.R.Civ.P. 59(e). The district court denied the
motions. Wang now seeks a reversal of the judgment or new trial on the
implied license defense. In an appeal from a judgment following denial of
JMOL, we must affirm factual findings that are supported by substantial
evidence, we then review legal conclusions to determine whether the factual
findings can bear them. _Railroad Dynamics, Inc. v. A. Stucki Co._ 727 F.2d
1506, 1512, 220 USPQ 929, 935-36 (Fed.Cir.1984); _Perkin-Elmer Corp. v.
Computervision Corp._, 732 F.2d 888, 893, 221 USPQ 669, 672-73
(Fed.Cir.1984). We review the denial of a motion for a new trial for abuse
of discretion. *Railroad Dynamics*, 727 F.2d at 1512, 220 USPQ at 935-36.

Because the second step of this review will require us to determine whether
the factual findings support the conclusion of law, we must first ascertain
what facts the jury found relating to Mitsubishi's implied license defense.
*Id*. The Special Verdict Form asked the jury to answer only the ultimate
question of whether an implied license exists, so the jury instructions
serve as our most direct guide to what the jury decided.3  See _Newell Cos.,
Inc. v. Kenney Mfg. Co._, 864 F.2d 757, 765, 9 USPQ2d 1417, 1423
(Fed.Cir.1988) (we accept factual findings presumed from jury verdict,
subject to substantial evidence test). In order to arrive at its
affirmative answer on the implied license question, the jury necessarily
found that (1) a relationship existed between Wang and Mitsubishi, (2)
within that relationship, Wang granted to Mitsubishi a right to use its SIMM
inventions, (3) Wang received valuable consideration for that grant of right,
(4) Wang denied that Mitsubishi had an implied license, and (5) Wang's
statements and conduct created the impression that Wang consented to
Mitsubishi making, using, or selling Wang's patented inventions, including
sales to consumers other than Wang. Separately, the jury found that
Mitsubishi made, used, or sold several versions of SIMMs that would infringe
the '513 patent but for the license.

With regard to the factual component of our review, Wang challenges only the
finding of valuable consideration. Before we can apply the substantial
evidence test to this finding, however, it becomes necessary to look beyond
the jury instructions and verdict to discover what the jury understood to
constitute "valuable consideration.. The district court's order denying
Wang's motion for JMOL identified three benefits conferred on Wang: (1) by
agreeing to manufacture and sell SIMMs, Mitsubishi contributed to a "high
volume supply and downward pressure on [the] price" of SIMMs, which
benefited Wang as a purchaser of SIMMs; (2) Mitsubishi absorbed development
and tooling costs; and, (3) Mitsubishi redesigned its SIMMs to conform to
Wang's preferred design. The district court ruled that each form of
consideration was supported by substantial evidence.

Looking to the record in search of substantial evidence, Wang's own
statements show that when the company introduced its SIMM design in June
1983, Wang intended to buy SIMMs from other producers rather than produce
SIMMs itself. Eventually, Wang hoped to "get the advantage of the cost
reduction because of the volumes involved.. The evidence indicates that Wang
considered lower prices and a larger market to be of value to it, as they
obviously were as a large user of SIMMs. In time, JEDEC adopted Wang's SIMM
design as a standard in what became a multi-billion dollar market. The
market grew; prices dropped. The record contains evidence that Mitsubishi
contributed to this advantageous outcome. Clayton's notes about Mitsubishi,
for example, contain references to prices "dropping to mid-teens.. Wang
introduced evidence that dozens of producers have participated in making the
SIMM market, and that Mitsubishi sold $361 million worth of SIMMs between
April 1985 and March 1994. A reasonable person could conclude from the
evidence that Mitsubishi supplied consideration to Wang by helping Wang
achieve the market scenario it sought and valued.

Substantial evidence of the second and third benefits also appears on the
record. Mitsubishi personnel testified that they made design changes to
accommodate Wang's needs: specifically, moving the capacitors onto the same
side of the substrate as the memory chips. Similarly, testimony indicated
that Mitsubishi declined to assess development and tooling charges to Wang
because it understood Wang was permitting Mitsubishi to sell SIMMs to other
customers. Clayton's notes reveal that, from the first meeting onward, he
closely followed Mitsubishi's development and tooling of SIMMs with 64K or
256K chips in PLCCs. Clayton clearly wanted Mitsubishi to make 64K SIMMs,
which Mitsubishi decided against, but Clayton also sought "to open
[communication with] Japan for us on a 256K X9 SIMM. All the while, Wang
and Mitsubishi exchanged designs and samples. A reasonable person could
conclude that Wang received something it valued because Mitsubishi was
persuaded to follow Wang's design suggestions, but was led to believe the
resultant SIMMs were not custom products for Wang and did not assess
charges. Although Wang points to contrary evidence, we cannot reevaluate
credibility or substitute our choices for those of the jury. *Perkin-Elmer*,
732 F.2d at 893, 221 USPQ at 672-73. Therefore, these findings survive the
substantial evidence test.

With the findings of fact firmly in hand, we now turn to the legal
conclusion that an implied license exists. See _Met-Coil Sys. Corp. v.
Korners Unltd., Inc._, 803 F.2d 684, 687, 231 USPQ 474, 476 (Fed.Cir.1986)
(implied license is question of law). In patent law, an implied license
merely signifies a patentee's waiver of the statutory right to exclude
others from making, using, or selling the patented invention. _Spindelfabrik
Suessen-Schurr Stahlecker & Grill GmbH v. Schubert & Salzer Maschinenfabrik
Aktiengesellschaft_, 829 F.2d 1075, 1081, 4 USPQ2d 1044, 1048
(Fed.Cir.1987). In the words of the Supreme Court,

> No formal granting of a license is necessary in order to give it effect.
> Any language used by the owner of the patent, or any conduct on his part 
> exhibited to another from which that other may properly infer that the
> owner consents to his use of the patent in making or using it, or selling
> it, upon which the other acts, constitutes a license and a defense to an
> action for a tort.

_De Forest Radio Tel. Co. v. United States_, 273 U.S. 236, 241, 47 S.Ct. 366,
367, 71 L.Ed. 625 (1927). Since *De Forest*, this court and others have
attempted to identify and isolate various avenues to an implied license.
As a result, courts and commentators relate that implied licenses arise by
acquiescence, by conduct, by equitable estoppel (estoppel in pais), or by
legal estoppel. See _AMP, Inc. v. United States_, 182 Ct.Cl. 86, 389 F.2d
448, 452 nn. 4-5, 156 USPQ 647, 649 nn. 4-5 (1968); Robert L. Harmon,
Patents and the Federal Circuit § 6.2(c) (3d ed. 1994 & Supp.1996); 6 Ernest
B. Lipscomb III, Walker on Patents § 20:14-20:17 (3d ed. 1987 & Supp.1995).
These labels describe not different kinds of licenses, but rather different
categories of conduct which lead to the same conclusion: an implied license.
The label denotes the rationale for reaching the legal result.

One of our predecessor courts observed that "courts generally have first
looked for facts which give rise to an estoppel in the process of concluding
that there is an implied license."  *AMP*, 389 F.2d at 452, 156 USPQ at 649.
The opinions that hew most closely to the *De Forest* language and the "entire
course of conduct" analysis rely on the doctrine of equitable estoppel,
because *De Forest* requires that conduct of the patentee led the other to
act. _Bandag, Inc. v. Al Bolser's Tire Stores, Inc._, 750 F.2d 903, 925-26,
223 USPQ 982, 998-99 (Fed.Cir.1984); _Stickle v. Heublein, Inc._, 716 F.2d
1550, 1559, 219 USPQ 377, 383 (Fed.Cir. 1983). In *Bandag*, we reversed a
conclusion of implied license because the infringer failed to show an
awareness of the conduct which supposedly created the license. *Bandag*, 750
F.2d at 925-26, 223 USPQ at 998-99. In *Stickle*, we affirmed that no implied
license existed absent the required nexus between the patentee's conduct and
the infringing actions, given that the course of infringing action only began
later and distinct from the cited conduct. *Stickle*, 716 F.2d at 1559, 219
USPQ at 383-84.

Neither this court nor the Supreme Court, however, has required a formal
finding of equitable estoppel as a prerequisite to a legal conclusion of
implied license. See *AMP*, 389 F.2d at 453-54, 156 USPQ at 651. To do so would
remove all distinction between the doctrines. Rather the estoppel doctrines
serve as guidelines. See *id*. at 451-52, 182 Ct.Cl. 86, 389 F.2d 448, 156 USPQ
at 649-50. The primary difference between the estoppel analysis in implied
license cases and the analysis in equitable estoppel cases is that implied
license looks for an affirmative grant of consent or permission to make, use,
or sell: i.e., a license. See *Stickle*, 716 F.2d at 1559, 219 USPQ at 383-84.
Equitable estoppel, on the other hand, focuses on "misleading" conduct
suggesting that the patentee will not enforce patent rights. _A.C. Aukerman
Co. v. R.L. Chaides Constr. Co._, 960 F.2d 1020, 1041-44, 22 USPQ2d 1321,
1335-38 (Fed.Cir.1992). In *Aukerman*, we described a typical equitable
estoppel situation as one in which (1) the infringer knows of the patent, (2)
the patentee objects to the infringer's activities, (3) but the patentee does
not seek relief until much later, (4) thereby misleading the infringer to
believe the patentee will not act. *Id*. at 1042-43, 960 F.2d 1020, 22 USPQ2d
at 1335-36. Thus, the two doctrines are not conterminous. Illustratively,
both the jury, in its advisory capacity, and the district court decided
against Mitsubishi on the defense of equitable estoppel per se, with
misleading conduct as a required component of that defense.

Legal estoppel refers to a narrower category of conduct encompassing
scenarios where a patentee has licensed or assigned a right, received
consideration, and then sought to derogate from the right granted.
*Spindelfabrik*, 829 F.2d at 1080, 4 USPQ2d at 1048; AMP 389 F.2d at 452, 156
USPQ at 649-50. In *AMP*, for example, a patentee granted a license to, and
received payment from, the United States for use of an "idea" which later
became the subject matter of its patent. *Id*. at 453-54, 182 Ct.Cl. 86, 389
F.2d 448, 156 USPQ at 651. The patentee then discovered a preexisting patent
covering an aspect of the invention. *Id*. at 451, 182 Ct.Cl. 86, 389 F.2d
448, 156 USPQ at 648. After acquiring the preexisting patent, the patentee
sued the government for infringement of the preexisting patent. *Id*. The
Court of Claims held that an implied license barred patentee from using the
preexisting-but-after-acquired patent to derogate from the express license
negotiated under the other patent. *Id*. at 454, 182 Ct.Cl. 86, 389 F.2d 448,
156 USPQ at 651.

We review issues of law, like the implied license defense, de novo.
_Guinn v. Kopf_, 96 F.3d 1419, 1421, 40 USPQ2d 1157, 1159 (Fed.Cir.1996). In
this process, we review judgments rather than opinions. See, e.g., _Baxter
Healthcare Corp. v. Spectramed, Inc._, 49 F.3d 1575, 1582, 34 USPQ2d 1120,
1125 (Fed.Cir.), cert. denied, 516 U.S. 906, 116 S.Ct. 272, 133 L.Ed.2d
194 (1995). Moreover, we may affirm a district court's action where the
record offers a route to affirm that neither expands nor contracts the rights
established for either party by the judgment. _Consolidated Aluminum Corp.
v. Foseco Int'l Ltd._, 910 F.2d 804, 815, 15 USPQ2d 1481, 1489 (Fed.Cir.
1990). Here, we agree with the district court that the factual findings
support the jury's legal conclusion on the implied license defense, although
we do not necessarily agree with all of the district court's reasoning. The
jury's findings may support an implied license in the nature of legal
estoppel given the transfer of a right for consideration and the subsequent
suit for infringement, but we instead follow the lead of our predecessor, the
United States Court of Claims, and focus on an alternative form of estoppel.
See *AMP*, 389 F.2d at 452, 156 USPQ at 650 (rejected equitable estoppel and
affirmed based on legal estoppel).

Although judicially implied licenses are rare under any doctrine, Mitsubishi
proved that the "entire course of conduct" between the parties over a
six-year period led Mitsubishi to infer consent to manufacture and sell the
patented products. See *De Forest*, 273 U.S. at 241, 47 S.Ct. at 367.
Furthermore, the level of interaction between the parties while Mitsubishi
designed and made SIMMs distinguishes this scenario from *Bandag* where the
infringer based its failed defense on conduct unknown to the infringer when
the infringement occurred. See *Bandag*, 750 F.2d at 925-26, 223 USPQ at
998-99. The record shows that Wang tried to coax Mitsubishi into the SIMM
market, that Wang provided designs, suggestions, and samples to Mitsubishi,
and that Wang eventually purchased SIMMs from Mitsubishi, before accusing
Mitsubishi years later of infringement. We hold, as a matter of law, that
Mitsubishi properly inferred consent to its use of the invention of Wang's
patents.

The findings that Wang bestowed "a right to use the SIMM invention" and that
Mitsubishi supplied valuable consideration to Wang, support our holding that
Wang's conduct created a license. This falls short of the express licenses or
assignments usually discussed in conjunction with legal estoppel, but it
constitutes part of a course of conduct that transcends "unilateral
expectations ..․ of one party."  *Stickle*, 716 F.2d at 1559, 219 USPQ at 383.
Wang not only led Mitsubishi to infer consent, Wang obtained payment. Wang
publicly announced its desired compensation. Wang also manifested this desire
in other ways, for example, by Wang's efforts at JEDEC to have its SIMM
designated a standard. With the contributions of Mitsubishi and others, Wang
received exactly the remuneration it desired: Wang's design is an industry
standard, and the benefits of a large market and lower prices for SIMMs
redound to this day. In sum, Wang consented to Mitsubishi's use of the
invention, granted the right to make, use, or sell the patented SIMMs without
interference from Wang, and received consideration. Therefore, we agree with
the district court's determination, reiterated in denying Wang's motion to
amend the judgment, that Mitsubishi possesses an irrevocable royalty-free
license under the '513 patent.

Because the jury's findings of fact are supported by substantial evidence and
the jury reached the correct legal conclusion based on its findings, we
affirm the judgment regarding Mitsubishi's implied license defense. In
reaching this result, we hold that Mitsubishi's implied license is in the
nature of equitable rather than legal estoppel, because the license arose
from an accord implicit in the entire course of conduct between the parties
as discussed in *De Forest* and subsequent cases relying on equitable estoppel
as a guideline. We further hold that the district court did not abuse its
discretion by denying Wang a partial new trial on this issue.

#### A. C. Aukerman Co. v. R. L. Chaides Construction Co

--------------------------------------------------------------------------------

Excerpt from _A. C. Aukerman Co. v. R. L. Chaides Constr. Co._, Fed. Cir. 1992[^AukermanHeadnote]

[^AukermanHeadnote]: _A. C. Aukerman Co. v. R. L. Chaides Constr. Co._, 960 F.2d 1020, 1041-1043 (1992), *reversed on other grounds*, _available at_ [https://law.justia.com/cases/federal/appellate-courts/F2/960/1020/350110/](https://law.justia.com/cases/federal/appellate-courts/F2/960/1020/350110/)

An [equitable] estoppel case ... has three important elements. [1]
The actor, who usually must have knowledge of the true facts,
communicates something in a misleading way, either by words, conduct or
silence. [2] The other relies upon that communication. [3] And the
other would be harmed materially if the actor is later permitted
to assert any claim inconsistent with his earlier conduct.

\[...\]

The first element of equitable estoppel concerns the statements or
conduct of the patentee which must "communicate something in a misleading
way." The "something" with which this case, as well as the vast majority
of equitable estoppel cases in the patent field is concerned, is that the
accused infringer will not be disturbed by the plaintiff patentee in the
activities in which the former is currently engaged.  The patentee's
conduct must have supported an inference that the patentee did not intend
to press an infringement claim against the alleged infringer. It is
clear, thus, that for equitable estoppel the alleged infringer cannot be
unaware--as is possible under laches--of the patentee and/or its patent.
The alleged infringer also must know or reasonably be able to infer that
the patentee has known of the former's activities for some time....

The second element, reliance... is essential to equitable estoppel. The
accused infringer must show that, in fact, it substantially relied on the
misleading conduct of the patentee in connection with taking
some action....

Finally, the accused infringer must establish that it would be materially
prejudiced if the patentee is now permitted to proceed.

#### Discussion

1. The *De Forest* court found that the patent owner's statements and ongoing
  conduct implied a license even when the patent owner indicated that royalties
  might later be assessed. What kind of common actions by companies releasing
  code under an open source license might similarly give rise to an implied
  patent license?

2. The *Wang* court lays out different circumstances under which a court may
  infer a patent license. One of those is "an affirmative grant of consent or
  permission to make, use, or sell." Is distribution of source code, that,
  when compiled, implements a patented method or embodies a patented system
  an affirmative grant to "make" or "use" that method or system?
 
3. Another fact pattern identified by the *Wang* court is legal estoppel:
  "scenarios where a patentee has licensed or assigned a right, received
  consideration, and then sought to derogate from the right granted." In the
  context of open source, rights are licensed to recipients via the open
  source license. Does the use of the code by others provide the necessary
  consideration to support a theory of legal estoppel? (*Cf.* the
  establishment of the SIMM as a standard in *Wang*, and the following in
  _Jacobsen v. Katzer_: "The lack of money changing hands in open source
  licensing should not be presumed to mean that there is no economic
  consideration, however.   There are substantial benefits, including
  economic benefits, to the creation and distribution of copyrighted
  works under public licenses that range far beyond traditional license
  royalties." _Jacobsen v. Katzer_, 535 F.3d 1373, 1379). 
 
4. "Equitable estoppel... focuses on "misleading" conduct suggesting that
  the patentee will not enforce patent rights." (*Wang* at 1271). Is
  distribution of source code or binaries under an open source license
  the sort of conduct that suggests non-enforcement of patent rights?
  Is the name of the copyright holder on the license enough to make the
  user of the open source aware "of the patentee and/or its patent"?
  (*Aukerman* at 1042)

 
### Limitations on Implicit Patent Licenses

The general rule is that the existence of an explicit patent clause in an
agreement will foreclose the finding of any implied license with a
broader grant.

The following cases discuss the scope of patent grants when there is
ambiguous express language dealing with the issue. Think about how these
cases might apply to the GPL version 2, which discusses patents but does not
include specific grant language.

#### State Contracting & Engineering Corp. v. Florida

--------------------------------------------------------------------------------

_State Contr. & Eng'g Corp. v. Florida_, Fed. Cir. 2001 [^StateContrHeadnote]

[^StateContrHeadnote]: _State Contr. & Eng'g Corp. v. Florida_, 258 F.3d 1329 (2001), _available at_ [https://caselaw.findlaw.com/us-federal-circuit/1215827.html](https://caselaw.findlaw.com/us-federal-circuit/1215827.html)


... The contract in question was drafted by the State of Florida, and
was lengthy. It incorporated what are known as value engineering provisions --
designed to encourage contractors to develop better methods of doing the
job. As noted above, the contract provided for additional payments to the
contractor if it developed such methods and allowed the state to use these
methods on the contract and on option contracts free of charge.

The relevant portion of the contract, section 4-3.5.8 of the FDOT Standard
Specifications, entitled "Department's Future Rights to a VECP," provided:

> In the event of acceptance of a VECP, the Contractor hereby grants to
> the Department *all rights to use, duplicate or disclose*, in whole or in
> part, in any manner and for any purpose whatsoever, and to have or to
> permit others to do so, *data* reasonably necessary to fully utilize such
> proposal *on this and any other Department contract*.

(emphases added [in original]). These provisions were not limited to the
contract in question, but extended to all future State of Florida use. The
district court found this language to be unambiguous and held that
"Plaintiffs agreed in the VECP to allow FDOT to utilize their then
unpatented data, without any agreement to compensate Plaintiffs for future
use, beyond the instant contract savings and any optional work included in
the original contract." Final Order, slip op. at 12-13. While we agree with
the district court that this language is unambiguous, we disagree with the
district court's interpretation of this language. We conclude that the
contract does not provide a license for patent rights to the private
contractors.

Whether express or implied, a license is a contract 'governed by ordinary
principles of state contract law.'" _McCoy v. Mitsuboshi Cutlery, Inc._, 67
F.3d 917, 920 36 U.S.P.Q.2D (BNA) 1289, 1291 (Fed. Cir. 1995) (quoting
_Power Lift, Inc. v. Weatherford Nipple-Up Sys., Inc._, 871 F.2d 1082, 1085,
10 U.S.P.Q.2D (BNA) 1464, 1466 (Fed. Cir. 1989)). Although we apply Florida
law in construing the contract, it is significant that the Supreme Court has
recognized that patent rights and trade secret rights are quite distinct,
and that a contract may provide for different treatment of the two. For
example, in _Aronson v. Quick Point Pencil Co._, 440 U.S. 257, 262, 59 L.
Ed. 2d 296, 99 S. Ct. 1096 (1979), the Supreme Court held that even though a
patent application had not issued, the parties' agreement for the payment of
a royalty for the use of proprietary technology was valid, because "state
law is not displaced merely because the contract relates to intellectual
property which may or may not be patentable." So too in _Kewanee Oil Co. v.
Bicron Corp._, 416 U.S. 470, 474, 491-93, 40 L. Ed. 2d 315, 94 S. Ct. 1879
(1974), the Supreme Court held that Ohio's law protecting trade secrets was
not preempted by the federal patent laws because the trade secret law did
not clash with the objectives of the federal patent law.

The right to use State Contracting's proprietary technology on the original
contract was covered by the supplemental VECP agreement itself as discussed
above. The only rights that the state acquired for future contracts were by
virtue of section 4-3.5.8. To be sure, the provision apparently contemplated
that State Contracting's "proposal" would be used on "other Department
contracts." But that section only conveyed rights to use "data" in future
contracts, and did not in terms convey the right to manufacture the sound
barriers using plaintiffs' design or to use plaintiffs' manufacturing
method. Most significantly the section did not explicitly convey any patent
rights, require the contractor to surrender its rights to the technology, or
bar the contractor from securing a patent on the invention.

The contract's failure to explicitly provide for the licensing of patent
rights is a glaring omission, particularly where, as here, the contracting
parties clearly contemplated that there might be relevant patents. Section
7-3 of the FDOT Standard Specifications, entitled "Patented Devices,
Materials and Processes," provides: "It is agreed that, without exception,
contract prices are to include all royalties and costs arising from patents,
trademarks, and copyrights, in any way involved in the work." The provision
for licensing of patents is limited to work under the contract and does not
convey any license to future use of the patented technology. The existence
of this provision shows that, if the parties had intended to convey other
patent rights, they would have done so explicitly.

Under these circumstances we think it clear that the contract did not in
fact provide a license for patent rights to the private contractors under
future contracts. The State of Florida drafted the contract, and Florida law
requires that it be construed against the drafter. _Golden Door Jewelry
Creations, Inc. v. Lloyds Underwriters Non-Marine Ass'n_, 117 F.3d 1328
(11th Cir. 1997). Therefore, we vacate the district court's grant of
summary judgment to the private contractors on the patent infringement
counts (counts III and VII), and remand for proceedings consistent with this
opinion.

#### Hilgraeve Corp. v. Symantec Corp.

--------------------------------------------------------------------------------

_Hilgraeve Corp. v. Symantec Corp._, 265 F.3d 1336, Fed. Cir. 2001 [^HilgraeveHeadnote]

[^HilgraeveHeadnote]: _Hilgraeve Corp. v. Symantec Corp._, 265 F.3d 1336 (2001), _available at_ [https://caselaw.findlaw.com/us-federal-circuit/1040027.html](https://caselaw.findlaw.com/us-federal-circuit/1040027.html)

\[...\]

IV. *Symantec's Licensing Defense*

Symantec urges that even if we vacate the district court's grant of summary
judgment of non-infringement, the judgment can be affirmed on an alternative
ground, namely that Symantec was licensed to practice the patent. We cannot
agree.

The district court held that Symantec had no license defense for the period
prior to March 2, 1999, because the purported transfer of patent rights from
Delrina (Delaware) to Delrina (Canada) under the June 30, 1993 SDCS
agreement was ineffective. While the district court appears to have been
correct, we believe that there is a more fundamental defect in Symantec's
license defense argument - Delrina (Delaware) itself never acquired a
transferable license to practice the '776 patent, and Delrina (Delaware)
therefore could not sub-license the '776 patent either before March 2, 1999,
or thereafter.

Unless the '776 patent was licensed under the June 30, 1993 Agreement,
Symantec agrees that it could not acquire a license. Symantec also admits
that there is no express language in the June 30, 1993 Technology Transfer
Agreement licensing or transferring rights to the '776 patent or any other
Hilgraeve patent. Instead, Symantec points to language in the paragraph 2.1
of the Agreement providing that "HILGRAEVE sells, conveys, assigns and
transfers to DELRINA DELAWARE and to HILGRAEVE, as joint tenants and not as
tenants in common, all copyright rights in the Software, " and that
Hilgraeve acknowledged in paragraph 9.1 that as part of the transfer
"HILGRAEVE  has also agreed to transfer the necessary know-how and technical
expertise to DELRINA DELAWARE with respect to the Software." On the basis of
this language, Symantec urges us to find that:

> 'Software' is more than source code and object code. . . . When read in
> conjunction with the . . . 'know-how' and 'technical expertise'
> transferred to Delrina (Delaware), Delrina (Delaware) essentially acquired
> Hilgraeve's entire knowledge base with respect to [Hilgraeve's] products.
> Since the Software included in-transit anti-virus features, Delrina
> acquired Hilgraeve's knowledge base with respect to those in-transit
> anti-virus features and could use that knowledge base as it pleased."

In summary, Symantec urges us to find that "the Technology Transfer
Agreement covered the technology in this case, which is allegedly covered by
the '776 Patent."

Whatever the definition of "knowledge base" proposed by Symantec, we cannot
conclude that rights to the '776 patent were transferred by the Technology
Transfer Agreement. Under Ontario law, "effect must first be given to
the intention of the parties,  to be gathered from the words they have used
. . . ." _Consol. Bathurst Exp. Ltd. v. Mut. Boiler & Mach. Ins. Co._, 1 S.C.R
888, 888 (Can. 1980). When the language of a contract is clear and
unambiguous, only the contract is considered for interpretation, not
extrinsic evidence. _Indian Molybdenum v. The King_, 3 D.L.R. 497, 502 (Can.
1951). Here, the contract provided for Hilgraeve to transfer "all copyright
rights in the Software," but failed to mention the transfer of patent
rights. From the terms of the contract we cannot conclude that the parties
intended to transfer any patent rights. Symantec relies on _Allan v. Bushnell
T.V. Co., Ltd._, 1 D.L.R. (3d) 534, 539 (Ont. High Ct. 1968) for the
proposition that "unexpressed terms [are implied] to implement [the]
parties' presumed intention." Allan, however, stated that

> the presumption is against the adding to contracts of terms which the
> parties have not expressed. The general presumption is that the parties
> have expressed every material term . . . . But . . . there may be cases
> where obviously some term must be implied if the intention of the parties
> is not to be defeated, some term of which it can be predicated that 'it
> goes without saying', some term not expressed but necessary to give to the
> transaction such business efficacy as the parties must have intended.

*Id*. Allan was a case involving a contract between a broadcasting company
and a news service in which the unexpressed term which was implied in the
contract was that the news to be supplied to the company by the service had
to be "accurate." Here, we cannot say (and it does not "go without saying")
that where the contract provided for the transfer of copyrights in the
software, but failed to mention the transfer of patent rights, that we must
imply such a term to the contract. The contract has a business efficacy
without adding this unexpressed term to it.

Moreover, in the subparagraph immediately following the paragraph 2.1
pertaining to the transfer of copyrights, the contract refers to other
intellectual property rights. In paragraph 2.2, the parties agreed that
Hilgraeve "shall not assert against DELRINA DELAWARE, any other intellectual
property right, including patent rights, it has or may have in the future,
with respect to the production, copying, licensing of the Software, or the
exercise by DELRINA DELAWARE of any rights transferred hereunder." Since the
contract specifically mentions patent rights in paragraph 2.2, we cannot say
that the omission of mention of patent rights in paragraph 2.1, which
transferred rights to  copyrights in the Software, was accidental or that
the transfer of patent rights is implicit anywhere the contract. *Cf.* _State
Contracting & Eng'g Corp. v. Florida_, 258 F.3d 1329, 59 U.S.P.Q.2D (BNA)
1498 (Fed. Cir. 2001) (applying Florida law to construe an agreement).

Symantec also contends that the covenant not to sue for patent infringement
in paragraph 2.2 is equivalent to a freely transferable license to the
patent. This court has stated that "licenses are considered as nothing
more than a promise by the licensor not to sue the licensee." _Jim Arnold
Corp. v. Hydrotech Sys., Inc._, 109 F.3d 1567, 1577, 42 U.S.P.Q.2D (BNA) 1119,
1127 (Fed. Cir. 1997). The covenant not to sue in paragraph 2.2 does not
grant a transferable license to the patent.

#### Discussion

1. A typical rule of interpretation is that contracts are "construed against
  the drafter," and that "effect must first be given to the intention of the
  parties." How might these rules apply in the context of open source
  licenses, where the party that drafted the license is probably not the
  party using the license to release code, and there might not be a unity of
  interest between the licensor and licensee?

2. The court in  _State Contracting_ found that there was licensing of both
  trade secrets and patents, but only the future use of trade secrets was
  contemplated under the contract. To what extent is it relevant that the
  contract in _State Contracting_ "only conveyed rights to use 'data' in
  future contracts," as opposed to language that implied patentable elements
  like processes?

3. Is it significant that the contract in _Hilgraeve_ provided for the
  *transfer* of copyrights, as opposed to the licensing of the copyrights?
  Would a court be more likely to find that the repeated granting of a
  license, such as occurs in open source licensing, to support an implied
  right to use any implicated patents?


## Express but Non-Specific Licenses

One issue that comes up in the context of open source licenses is license
ambiguity. Many open source licenses were not written by people with
legal training, and other licenses were written at a time when software
was not widely believed to be patentable. As a result, many open source
licenses are ambiguous relative to the question of patent rights: The
licenses include express language that suggests the existence of a patent
right, such as the term "use," but the specific terms "patent" or
"patent license" are not part of the text of the license.

As discussed above,[^LimitationsOnImplicit] the existence of some patent
language in a license will usually prevent the finding of an implicit
patent license. But an express grant with ambiguous scope may constitute
an express patent license.

[^LimitationsOnImplicit]: *See generally* the section on "Limitations on Implicit Patent Licenses," *supra.*


### Selected Open Source Licenses

The licenses below are some of the shortest and most permissive open source
licenses available. As you read the licenses below, note any use of language
that may implicate the reserved rights under patent law (to make, use, offer
to sell, sell, and import).


#### The BSD License
The 2-Clause BSD License[^BSD4], 1999.

*Note: The "original" BSD License had four clauses. The 4-clause version
was superseded by 3-Clause and 2-Clause BSD licenses, each removing one of
the original conditions. The preamble has remained the same in all versions
of the license.*

Copyright (c) \<year\>, \<copyright holder\>
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.
2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

[^BSD4]: _The 2-Clause BSD License_, Regents of the University of California, *available at* [https://opensource.org/licenses/BSD-2-Clause] (https://opensource.org/licenses/BSD-2-Clause) (1999).

--------------------------------------------------------------------------------
#### Fair License
The Fair License[^Fair]

\<Copyright Information\>

Usage of the works is permitted provided that this instrument is retained with
the works, so that any entity that uses the works is notified of this
instrument.

DISCLAIMER: THE WORKS ARE WITHOUT WARRANTY.

[^Fair]: _The Fair License_, *available at*  [https://opensource.org/licenses/Fair] (https://opensource.org/licenses/Fair) (2004).

--------------------------------------------------------------------------------
#### Free Public License 1.0.0
The Free Public License, Version 1.0[^0BSD]

Copyright (c) \<year\>, \<copyright holder\>

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

[^0BSD]: _Free Public License, Version 1.0_, Rob Landley, *available at* [https://opensource.org/licenses/FPL-1.0.0](https://opensource.org/licenses/FPL-1.0.0) (2006). Also called the "Zero Clause BSD License."

--------------------------------------------------------------------------------
#### MIT License
The MIT License[^MIT]

Copyright \<year\>, \<copyright holder\>

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.


[^MIT]: _The MIT License_, Massachusetts Institute of Technology, *available at* [https://opensource.org/licenses/MIT](https://opensource.org/licenses/MIT) (1988).

#### Discussion

1. The licenses above all include the permission to "use" the software. Is
  that a patent grant or verbal shorthand for "create copies of the software
  in a computer memory and interpret the copy by means of a processor"?
  Could it be both?

2. To what extent does the right the "distribute [the] software ... with
  or without fee" implicate the patent-reserved right to "sell" or "offer
  to sell" the patented item?

3. Software has both expressive (copyright-protected) and functional
  (patent-protected) elements inextricably bound together. In the case
  of a "mixed" work such as software, does the copyright-denominated
  license to "copy" or "make derivative works" *necessarily* implicate
  the patent-denominated right to "make" the patented item?

4. As noted before, it is a standard rule of contract interpretation to
  construe the terms of the license against the drafter. But typically, the
  open source licensor is not the same person as the license drafter.
  Further, open source licenses are *fixed*, and not subject to negotiation.
  Organizations choose to use particular open source licenses for many reasons.
  Can the use of a license that was not drafted by the licensor be construed
  against the licensor?

### Cases

The discussion in the previous section was focused on license terms that
specifically reflect or at least implicate reserved rights under patent
law. A careful review of the language, however, shows that there are also
*broad, but unspecific* grants of rights in many open source licenses.
For example, the MIT license:

> Permission is hereby granted, free of charge, to any person obtaining a
> copy of this software... to deal in the Software without restriction...

The GNU GPL, version 2:

> Activities other than copying, distribution and modification are not
> covered by this License; they are outside its scope. The act of running
> the Program is not restricted...

As you read the following cases, think about whether these statements may
act as express patent licenses granted to recipients of the open source
software.

#### A. Natterman & CIE GmBH v. Bayer Corp.

--------------------------------------------------------------------------------
_A. Natterman & CIE GmBH v. Bayer Corp._, 428 F. Supp. 2d 253, E.D.Pa, 2006. [^NattermanHeadnote]

[^NattermanHeadnote]: _A. Natterman & CIE GmBH v. Bayer Corp._, 428 F. Supp. 2d 253, E.D.Pa, (2006), _available at_ [https://www.leagle.com/decision/2006681428fsupp2d2531659](https://www.leagle.com/decision/2006681428fsupp2d2531659)

**MEMORANDUM AND ORDER**

*ANITA B. BRODY, District Judge.*

In this patent infringement action, Plaintiffs A. Nattermann & Cie GmbH
("Nattermann") and Aventis Behring L.L.C. bring suit against Defendants Bayer
Corporation and Bayer Healthcare LLC for alleged infringement of U.S. Patent
No. 5,565,427 ("the '427 patent"). Defendants bring counterclaims against
Plaintiffs and Counterclaim Defendant Aventis Behring
GmbH.[^NattermanFNOmitted] Plaintiff Nattermann is the owner of the '427
patent, Counterclaim Defendant Aventis Behring GmbH has a non-exclusive
license to the patent, and Plaintiff Aventis Behring L.L.C. has a sublicense.
The '427 patent involves a drug used in the treatment of hemophilia. Plaintiffs
claim that an anti-hemophilila drug marketed by Defendants under the name
KOGENATE® FS infringes the '427 patent. Defendants bring counterclaims against
Plaintiffs for, inter alia, breach of a 1998 Supply Agreement entered into by
Bayer and Centeon L.L.C., a predecessor of Plaintiff Aventis Behring L.L.C.,
under which Bayer was to manufacture its KOGENATE® product for Centeon L.L.C.

[^NattermanFNOmitted]: Some footnotes and cites to the record have been omitted.

Before me is Defendants' motion for summary judgment on their fourth
affirmative defense of license under the '427 patent. Defendants claim that
the 1998 Supply Agreement between Bayer and Centeon L.L.C. granted Defendants
an express license under the '427 patent and that this license is a complete
defense to the instant patent infringement suit. Also before me is
Plaintiffs' motion for summary judgment on Defendants' affirmative defense of
license and Defendants' third counterclaim for breach of contract. Plaintiffs
seek a judgment that Defendants have no express or implied license under the
'427 patent and that, as a result, Defendants' counterclaim for breach of
contract fails as a matter of law. For the reasons that follow, I will deny
both motions.

**I. FACTUAL BACKGROUND**

For purposes of the instant motions, the relevant undisputed facts are as
follows.

A. *The 1993 Patent Settlement Agreement*

In 1993, Defendants' predecessor Miles Inc. ("Miles") and Rhône Poulenc Rorer
Inc. ("RPR"), parent company of Centeon L.L.C.'s predecessor Armour
Pharmaceutical Co. ("Armour"), signed an agreement ("the 1993 Patent Settlement
Agreement") settling their previous patent litigation. As a result of the
1993 Patent Settlement Agreement, Bayer AG, the parent company of Miles,
received an express license to certain patents, known as the "Scripps patents,"
involving recombinant factor VIII technology used in the treatment of
hemophilia.

B. *The 1994 Supply Agreement*

As part of the 1993 Patent Settlement Agreement, Miles and Armour, the
predecessors of Bayer and Centeon L.L.C. respectively, entered into the 1994
Supply Agreement. The 1994 Supply Agreement obligated Bayer to supply Centeon
L.L.C. "with certain defined quantities of recombinant factor VIII (the
'Product' as further defined below). . . ." The "Product" of the 1994 Supply
Agreement consisted of Bayer AG's first-generation KOGENATE 0 product.
Under the 1994 Supply Agreement, Bayer supplied Centeon L.L.C. with KOGENATE®,
and Centeon L.L.C. sold this product under its own HELIXATE® trade-name.

Section 9 of the 1994 Supply Agreement states:

> No license, express or implied, is granted by one party to the other
> hereunder, save for those purposes which permit performance, by each party,
> of its obligations under this Agreement.

C. *The 1998 Supply Agreement*

From 1997 to 1998, Bayer and Centeon L.L.C. renegotiated the 1994 Supply
Agreement and formed the 1998 Supply Agreement. Bayer and Centeon L.L.C.
renegotiated the Supply Agreement, in part, so that each party could secure
continued access to future recombinant factor VIII products. Under the 1998
Supply Agreement, Bayer agreed to "continue to provide quantities of human
recombinant Factor VIII to Centeon under the terms and conditions specified
herein. . . ." The 1998 Supply Agreement was to be "considered part of
the Settlement Agreement between Bayer AG and Armour just as the 1994
Agreement was part of said Settlement Agreement." The parties incorporated
Section 9 of the 1994 Agreement into Section 10 of the 1998 Agreement.

D. *KOGENATE® FS and the 1998 Supply Agreement*

When the parties negotiated and signed the 1998 Supply Agreement, Bayer was
marketing its first-generation KOGENATE® product, which does not infringe the
'427 patent. The 1998 Supply Agreement provides that Centeon L.L.C. and its
successors would receive access to later improvements of Bayer's KOGENATE®
product. One such contemplated improvement that was specifically contemplated
in the Agreement was called KOGENATE® II. KOGENATE® II was defined in the 1998
Supply Agreement as "an antihemophilic Factor VIII (Recombinant) protein to be
formulated as a sterile, stable, purified, freezedried concentrate, purified
and formulated without the use of albumin." Bayer has assigned the trademark
KOGENATE® FS to the KOGENATE® II Product referenced in the 1998 Supply
Agreement. At the time Bayer and Centeon L.L.C signed the 1998 Supply
Agreement, Bayer had not provided Centeon L.L.C. with full specifications for
any future recombinant factor VIII product in development, including
KOGENATE® FS.

\[...\]

**III. DISCUSSION**

Defendants move for summary judgment on the affirmative defense of express
license under the '427 patent. Plaintiffs cross-move for summary judgment on
Defendants' affirmative defense of license, seeking judgment as a matter of law
that Defendants have no license to the '427 patent, either express or implied.
Plaintiffs also move for summary judgment on Defendants' third counterclaim
(breach of the 1998 Supply Agreement), which they assert is dependent on a
finding that the Agreement created a license to the '427 patent. All of these
issues boil down to the single question of whether Defendants were licensed
under the '427 patent.

A. *Background*

A license, whether express or implied, is a defense to patent infringement.
[FN8] *See* _Carborundum Co. v. Molten Metal Equip. Innovations_, 72 F.3d
872, 878 (Fed. Cir.1995). The alleged infringer has the burden of establishing
this affirmative defense. *Id*. It has been observed that:

> [n]o formal granting of a license is necessary in order to give it
> effect. Any language used by the owner of the patent, or any conduct on his
> part exhibited to another from which that other may properly infer that the
> owner consents to his use of the patent in making or using it, or selling it,
> upon which the other acts, constitutes a license and a defense to an action
> for a tort.

_Wang Labs., Inc. v. Mitsubishi Electronics Am., Inc._, 103 F.3d 1571, 1580
(Fed.Cir. 1997) (quoting _De Forest Radio Tel. & Tel. Co. v. United States_,
273 U.S. 236, 241, 47 S.Ct. 366, 71 L.Ed. 625 (1927)). Defendants claim that
the 1998 Supply Agreement between Plaintiffs' predecessor Centeon L.L.C. and
Bayer gave Defendants an express license to manufacture KOGENATE® FS, the drug
that Plaintiffs allege infringes the '427 patent. The determination of whether
there is an express license or an implied license to a patent is "governed by
ordinary principles of state contract law." _State Contracting & Eng'g Corp.
v. Florida_, 258 F.3d 1329, 1339 (Fed. Cir.2001) (quoting _McCoy v. Mitsuboshi
Cutlery, Inc._, 67 F.3d 917, 920 (Fed.Cir. 1995)).

Here, the parties agree that Connecticut law applies to the interpretation of
the 1998 Supply Agreement upon which Defendants' claim of express license is
based. Under Connecticut law, "[a]lthough ordinarily the question of
contract interpretation, being a question of the parties' intent, is a
question of fact, where there is definitive contract language, the
determination of what the parties intended by their contractual commitments is
a question of law." _Hanks v. Powder Ridge Restaurant Corp._, 276 Conn. 314,
885 A.2d 734, 739 (2005) (internal citations omitted).

B. *Defendants' Motion for Summary Judgment*

Defendants do not dispute that no license to the '427 patent is explicitly
mentioned in the 1998 Supply Agreement or any of its precursors. However,
Defendants claim that Section 10 of the 1998 Supply Agreement created an
express license to the '427 patent:

> **No Express or Implied License**
>
> No license, express or implied, is granted by one party to the other
> hereunder, *save for those purposes which permit performance, by each
> party, of its obligations under this Agreement.*

(Defs.' Mot. Summ. J. Ex. A at 27 (emphasis added).) Defendants claim that
the plain meaning of Section 10 is to create express licenses to such patents
as "permit performance, by each party, of its obligations under this
Agreement." Defendants claim that because a license to the '427 patent was
essential to Bayer's performance of the contract, this provision creates an
express license to that patent. They cite various other provisions of the
Supply Agreement in support of the contention that Bayer required a license
to the '427 patent in order to perform its obligations under the Agreement.

In order for Defendants to obtain summary judgment on the question of express
license, it would have to be clear from the four corners of the 1998 Supply
Agreement that Section 10 grants Bayer an express license to the '427 patent.
The fact that the provision is entitled "No Express or Implied License" and
provides, in part, that "[n]o license, express or implied, is granted by one
party to the other hereunder" is at least enough to raise sufficient ambiguity
to preclude summary judgment for Defendants.

C. *Plaintiffs' Motion for Summary Judgment*

Plaintiffs raise several arguments for why summary judgment for Defendants
is improper and why, in fact, summary judgment should be granted in Plaintiffs'
favor: (1) Centeon L.L.C. never had the right to license the '427 patent to
Bayer in the first place; (2) even if it did, the plain terms of the 1998
Supply Agreement foreclose any express or implied license to the '427 patent;
and (3) even if the Supply Agreement were construed to grant an express or
implied license to patents necessary to the performance of the parties'
contractual obligations, the '427 patent would not fall within the scope of
such a license. An absence of genuine issues of material fact as to any one of
these three issues might entitle Plaintiffs to summary judgment. Thus, I will
address each argument in turn.

\[...\]


2\. *Whether the 1998 Supply Agreement forecloses any license to the
'427 patent*

Plaintiffs also argue that the plain terms of the 1998 Supply Agreement
unambiguously negate the existence of any license to the '427 patent, express
or implied. Under Connecticut law, contract interpretation is a question of
fact for the jury unless the parties' intent is "clear and unambiguous" from
the four corners of the contract, in which case it becomes a question of law
for the court. _Peter-Michael, Inc. v. Sea Shell Assocs._, 244 Conn. 269, 709
A.2d 558, 562 (1998); see also _McCann Real Equities Series XXII, LLC v. David
McDermott Chevrolet, Inc._, 93 Conn.App. 486, 890 A.2d 140, 153 (2006) ("When
only one interpretation of a contract is possible, the court need not look
outside the four corners of the contract."). The parties' intent is not clear
and unambiguous from the four corners of the 1998 Supply Agreement with
respect to whether the Agreement grants licenses to patents necessary for the
performance of the parties' contractual obligations.

Section 10 of the 1998 Supply Agreement provides:

> No license, express or implied, is granted by one party to the other
> hereunder, save for those purposes which permit performance, by each
> party, of its obligations under this Agreement.

In order to grant summary judgment for Plaintiffs on this question, I would
have to find that the language of Section 10 clearly and unambiguously
forecloses any express or implied license to the '427 patent. Section 10's
plain terms do not do this. Plaintiffs would have me read this provision as
stating simply that "no license, express or implied, is granted by one party
to the other hereunder." Such a statement would indeed have been an
unambiguous expression that the contract foreclosed any express or implied
licenses.

Yet Section 10 does not say that; rather it states that the Agreement
creates no express or implied licenses "*save* for those purposes which permit
performance, by each party, of its obligations under this Agreement." A
plausible reading of this provision would thus be that it *does* grant such
licenses as are necessary to the performance of the 1998 Supply Agreement.

At the very least, Section 10 does not clearly and unambiguously rule out
an implied license to the '427 patent. [FN12] To the contrary, the provision
seems to contemplate the possibility that one or more patent licenses would
be necessary to the performance of the Agreement, and carves out such licenses
from the general statement that "no license, express or implied, is granted by
one party to the other hereunder." Thus, Plaintiffs are not entitled to
summary judgment because the 1998 Supply Agreement does not, as a matter of
law, foreclose the possibility of a license to the '427 patent. There is a
genuine issue of material fact as to this question.

Plaintiffs also argue that, read as a whole, the 1998 Supply Agreement cannot
be interpreted to create a license to the '427 patent, because it incorporates
express licenses to other patents while making no mention of the '427 patent.
Plaintiffs rely on the principle of *expressio unius est exclusio alterius*,
under which the express mention of one thing (such as the grant of a license)
in a written document is presumed to exclude another that is not mentioned.
The problem with this argument is that nowhere does the 1998 Supply Agreement
expressly grant any patent rights to either party. Plaintiffs claim that
because the 1998 Supply Agreement was considered part of the 1993 Patent
Settlement Agreement settlement between RPR and Miles, predecessors of
Plaintiffs and Defendants respectively, the 1998 Supply Agreement incorporates
the express license to the Scripps patents that was included in the 1993
settlement. The failure to mention the '427 patent explicitly in the 1998
Agreement, Plaintiffs argue, coupled with the express license of the Scripps
patents in 1993, creates a presumption that the 1998 Agreement creates no new
licenses.

If the 1998 Supply Agreement itself had explicitly mentioned a license to the
Scripps patents, or to some other patent, and conspicuously omitted any
mention of the '427 patent, Plaintiffs' argument might have some force.
See, e.g., *State Contracting*, 258 F.3d at 1340 ("The provision for licensing
of patents is limited to work under the contract and does not convey any
license to future use of the patented technology. The existence of this
provision shows that, if the parties had intended to convey other patent
rights, they would have done so explicitly."); _Hilgraeve Corp. v. Symantec
Corp._, 265 F.3d 1336, 1345 (Fed.Cir.2001) ("Here, the contract provided for
Hilgraeve to transfer `all copyright rights in the Software,' but failed to
mention the transfer of patent rights. From the terms of the contract we cannot
conclude that the parties intended to transfer any patent rights."). However,
because the 1998 Supply Agreement is completely silent on the issue of licenses
to intellectual property (aside from Section 10, which I have already found to
be ambiguous), Plaintiffs' argument fails.

There are genuine issues of material fact as to whether the 1998 Supply
Agreement was intended to create a license to the '427 patent as a patent
necessary to the performance of the parties' contractual obligations.

3\. *Whether a license to the '427 patent was necessary to Bayer's
performance of its obligations under the 1998 Supply Agreement*

Finally, Plaintiffs argue that even if the 1998 Agreement granted express or
implied licenses to those patents necessary to the performance of the parties'
obligations, the '427 patent was not such a patent. The parties devote much of
the briefing of the instant motions to debating whether Bayer could have
fulfilled its obligations under the Agreement without infringing the '427
patent. This question presents genuine issues of material fact.

**IV. CONCLUSION**

Because there are genuine issues of material fact precluding summary judgment
to either party on the issues raised in the instant motions, I will deny both
parties' motions for summary judgment.

____

*Selected footnotes from A. Natterman & CIE GmBH v. Bayer Corp:*

[FN8]: An express license is merely "[o]ne which is granted in direct
terms." Black's Law Dictionary 920 (6th ed.1990). The definition of "implied
license" in this context is slightly more nuanced. In patent law, the term
"implied license" has been used to refer to "different categories of conduct
which lead to the same conclusion," namely, "a patentee's waiver of the
statutory right to exclude others from making, using, or selling the patented
invention." _Wang Labs., Inc. v. Mitsubishi Electronics Am., Inc._, 103 F.3d
1571, 1580 (Fed.Cir.1997). "[C]ourts and commentators relate that implied
licenses arise by acquiescence, by conduct, by equitable estoppel (estoppel in
pais), or by legal estoppel." *Id*. These distinctions as to implied licenses
are not relevant for purposes of the instant motions.

[FN12]: Plaintiffs "move for summary judgment of no license—either express
or implied." Because I find that the plain terms of the 1998 Supply Agreement
do not, as a matter of law, necessarily foreclose an implied license to the
'427 patent, I do not address whether they foreclose an express license to the
patent.

#### In re Davidson Hydrant Techs., Inc.

--------------------------------------------------------------------------------
_In re Davidson Hydrant Techs., Inc._, 2012 Bankr. LEXIS 1120, (Bankr. N.D. Ga.  2012).[^DavidsonHeadnote]

[^DavidsonHeadnote]: _In re Davidson Hydrant Techs., Inc._, 2012 Bankr. LEXIS 1120, (Bankr. N.D. Ga.  2012), _available at_ [https://www.leagle.com/decision/inbco20120327726](https://www.leagle.com/decision/inbco20120327726)

**ORDER**

W. H. DRAKE, Bankruptcy Judge

Before the Court is the Motion to Reject Exclusive Marketing Agreement with
Windsor Distribution Corporation, filed by Davidson Hydrant Technologies, Inc.
(hereinafter the "Debtor"). Windsor Technologies Corporation, f/k/a Windsor
Distribution Corporation (hereinafter "Windsor") objects to the Motion.
Windsor asserts that section 365(n)(1) of the Bankruptcy Code applies to
permit Windsor to retain certain rights allegedly provided under the agreement
between the parties. This matter is a core proceeding, pursuant to
28 U.S.C. § 157(b)(2)(A), over which this Court has subject matter
jurisdiction. See 28 U.S.C. § 1334.

**BACKGROUND AND PROCEDURAL HISTORY**

Debtor owns patents in fire hydrant technology and manufactures and sells the
patented products to both end-users and manufacturers. Debtor signed marketing
agreements in 2003 and 2005 with Windsor before entering into the current
marketing agreement in 2007 (hereinafter the "Agreement"). By its terms, the
Agreement will last through December 2018, with a five-year right of renewal
granted to Windsor at the end of the stated term.

The pertinent aspects of the Agreement are as follows:

> * Davidson hereby engages Windsor, and Windsor hereby accepts such
>   engagement, to market and promote the Products, Davidson's training, and
>   installation services within the Territory, all strictly in accordance
>   with the terms and conditions of this Agreement. Subject to Section 10,
>   Davidson engages Windsor on an exclusive basis within the Territory during
>   the Term.
>   Agreement, § 2A.

\[...\]

...Essentially, the parties disagree over whether Windsor is a licensee of a
right to Debtor's intellectual property, either expressly under the Agreement,
or by virtue of an implied license arising from the parties' conduct.

Debtor argues that Windsor's sole duty and right under the Agreement was to
market and promote Debtor's products and services, which did not require or
result in a license of a right to use, sell, or offer to sell Debtor's
intellectual property. In support of its position, Debtor states that the
Agreement provided Debtor the right to accept or reject any purchase order
submitted by Windsor, and the Agreement only provided Windsor with a license
to use Debtor's trademarks, which are excluded from the Bankruptcy Code's
definition of intellectual property. The Debtor further submits that no
implied license to offer the products for sale arose because Debtor lacked the
requisite intent to grant Windsor a license and Windsor gave no consideration
for the alleged implied license.

In response, Windsor argues that the Agreement grants Windsor a right to use
intellectual property because it permits Windsor to offer for sale Debtor's
products and gives Windsor the right to use and create works of authorship
owned by Debtor. In the alternative, Windsor submits that the parties mutually
departed from the written terms of the Agreement, thus resulting in a modified
contract, under which Windsor had the authority to directly sell products to
customers, or that Debtor's conduct gave rise to an implied license of the
right to offer for sale and sell Debtor's products.

\[...\]

The Bankruptcy Code does not define the terms "licensor" or "license."
According to federal law applicable to patents, a "license" is essentially
permission to use, make, or sell intellectual property and a "promise by the
licensor not to sue the licensee." _A. Natterman & CIE Gmbh v. Bayer Corp._,
428 F.Supp.2d 253, 258 (E.D. Pa. 2006); _In re Spansion, Inc._, 2011
3268084, * 7 (D. Del. July 26, 2011). Under the Bankruptcy Code, "intellectual
property" includes a trade secret; invention, process, design, or plant
protected under title 35; patent application; plant variety; work of
authorship protected under title 17; or mask work protected under chapter 9 of
title 17, "to the extent protected by applicable nonbankruptcy law."
11 U.S.C. § 101(35A). Accordingly, a "licensor of a right to intellectual
property" within the meaning of section 365(n)(1), is a party who has been
authorized to use, make, or sell a trade secret, a patented invention, process,
design, or plant, a plant variety, a copyrighted work of authorship, or a mask
work. *Spansion*, 2011 WL 3268084 at *7.

Further, under federal patent law, a patent is considered to be a "bundle of
rights." See _Carborundum Co. v. Molten Metal Equip. Innovations_, 72 F.3d 872,
878 (Fed. Cir. 1995). Each "stick" in the bundle can be licensed to another
party. Here, Windsor asserts that the right to offer for sale a patented
product is such a "stick" in the bundle of rights. This assertion is
consistent with patent law, which permits the holder of a patent to sue a
party for patent infringement if the party offers to sell a product using the
patent holder's patent without authorization. See 35 U.S.C. § 271(a).

Windsor contends that the Agreement permits Windsor to offer Debtor's products
for sale. If so, the authorization to offer the products for sale without
being subject to suit for infringement of Debtor's patent constitutes the
license of a right in the patent. For purposes of determining whether
particular conduct constitutes an "offer to sell," the term "offer to sell" is
"interpreted according to its ordinary meaning in contract law, as revealed by
traditional sources of authority." _Rotec Indus., Inc. v. Mitsubishi Corp._,
215 F.3d 1246 (Fed. Cir. 2000)....

**B. Whether the Agreement Grants a License of Intellectual Property**

Under federal patent law, a license of intellectual property can be either
express or implied. See Bayer Corp., 428 F.Supp. at 258. "An express
license is merely '[o]ne which is granted in direct terms.'" *Id, n.8
(quoting BLACK'S LAW DICTIONARY 920 (6th ed. 1990)). Whether a contract
includes a license to intellectual property is a matter of contract
interpretation. _Wisconsin AlumniResearch Foundation v. Intel Corp._, 656 F.Supp.2d 898, 910 (W.D. Wis. 2009)
(citing _State Contracting & Engineering Corp. v. Florida_, 258 F.3d 1329, 1339
(Fed. Cir. 2001)). Here, the parties agree that Georgia contract law applies.

Under Georgia law, "the cardinal rule of contract interpretation is to
determine the intent of the parties. . . ." _Flynt v. Life of the South Ins.
Co._, 2011 WL 5305431, *4 (Ga. App. 2011) (citations omitted). To ascertain
the intent of the parties, the Court must first determine "'if the contract
language is unambiguous, and if so the court enforces the contract's clear
terms.'" _NW Parkway, LLC v. Lemser_, 709 S.E.2d 858, 861 (Ga. App. 2011)
(quoting _Eckerd Corp. v. Alterman Properties, Ltd._, 589 S.E.2d 660 (Ga. App.
2003)). In determining a contract's nature, a court looks at the plain meaning
of the contract provisions. *Id*. (quoting _Ga. Real Estate Properties, v.
Lindwall_, 692 S.E.2d 690 (Ga. App. 2010)). "'[A]ll the contract terms must
be considered together in arriving at the construction of any part, and a
construction upholding the contract in whole and every part is preferred.'"
*Flynt*, 2011 WL 5305431 at *4 (citations omitted). "'Words generally bear
their usual and common signification; but technical words, words of art, or
words used in a particular trade or business will be construed, generally, to
be used in reference to this peculiar meaning. The local usage or understanding
of a word may be proved in order to arrive at the meaning intended by the
parties[.]'" NW Parkway, 709 S.E.2d at 861 (quoting O.C.G.A. § 13-2-2(2)).

The plain language of the Agreement does not grant a license of intellectual
property protected under section 365(n)(1). Windsor first asserts that the
Agreement includes an express license of a right to intellectual property,
either in the form of a right to offer for sale and to sell a patented product,
or the right to use works of authorship. While the Agreement expressly grants
to Windsor a non-exclusive license to use Debtor's trademarked name and logo,
it is silent as to a right to use Debtor's patents or patents pending.

The Agreement authorizes Windsor "to market and promote" Debtor's products.
Windsor asserts that the use of the word "market" is the grant of an
authorization to offer for sale Debtor's products. Windsor submits that the
terms "market" and "promote" must have different meanings in order for each
term in the Agreement to have meaning. Thus, relying on one dictionary
definition of the verb "to market," Windsor asserts that "to promote" means to
advertise and "to market" means to sell or offer for sale. However, the verb
"to market" is also defined as "to expose for sale in a market." WESBTER'S
THIRD NEW INTERNATIONAL DICTIONARY, Merriam-Webster (1993). Exposing a product
for sale is more akin to advertising than to offering a product for sale. Read
as whole, the Agreement suggests a more synonymous meaning for the words
"market" and "promote," as if they form one phrase — to make the products known
to customers in the market for the purchase of Debtor's products.

This interpretation is supported by the rights actually granted to Windsor
under the Agreement. Every provision of the Agreement suggests Debtor intended
to engage Windsor for the sole purpose of generating interest in the product
and finding customers, rather than concluding sales on Debtor's behalf. If the
parties intended Windsor to have the right to sell or offer the products for
sale, one would expect Windsor to have the right to bind Debtor to the sale. To
the contrary, the Agreement does not give Windsor authority to bind Debtor to
any sales. Furthermore, customers were on notice of this relationship, as
Debtor's Term Sheet, which was provided to Debtor's customers, expressly states
that "[a] Purchase Order will be binding on [Debtor] only after accepted
in writing . . . by [Debtor]." Agreement, Exhibit B, § 1. Therefore, under
Georgia contract law and general principles of patent law, Windsor could not
offer the products for sale....

#### XimpleWare, Inc. v. Versata Software, Inc

--------------------------------------------------------------------------------
_XimpleWare, Inc. v. Versata Software, Inc_, 2014 U.S. Dist. LEXIS 68515 (N.D.Cal 2014).[^XimplewareHeadnote]

The GNU General Public License, version 2, is unique in that it mentions patents
but does not include a specific patent grant. In this holding from the
*Ximpleware* court, the court evaluates whether the GNU GPL, version 2's
also includes a patent license.

[^XimplewareHeadnote]: _XimpleWare, Inc. v. Versata Software, Inc_, 2014 U.S. Dist. LEXIS 68515 (N.D.Cal 2014), _available at_ [https://advance.lexis.com/api/permalink/e29c4c06-bb22-4928-a9e6-5eb36f910ca2/?context=1000516](https://advance.lexis.com/api/permalink/e29c4c06-bb22-4928-a9e6-5eb36f910ca2/?context=1000516)

Opinion by: PAUL S. GREWAL

**Opinion**

**ORDER GRANTING-IN-PART DEFENDANTS' MOTIONS TO DISMISS**

Think of the millions of lines of source code licensed in this country and
around the world under the terms of version 2 of Richard Stallman's GNU General
Public License. And yet it appears that only one court has yet to weigh in on
an elementary question arising from the license: what does it mean to
distribute? Before the court are four motions to dismiss that place that
question front-and-center. The motions are brought by Defendants: (1)
Ameriprise Financial, Inc. and Ameriprise Financial Services, Inc.; (2) United
HealthCare Services, Inc.; (3) Pacific Life Ins. Co., the Prudential Ins. Co.
of America, Wellmark, Inc. and Aviva USA Corp., and (4) Versata Software, Inc.,
Trilogy Development Group, Inc. and Aurea Software, Inc. Plaintiff XimpleWare,
Inc. opposes each motion, and the parties appeared for a hearing.5Link to the
text of the note After considering the arguments, both at the hearing and in
the papers, the court adopts in its entirety Judge Ilston's recent conclusion
that the kind of source code distribution alleged here can establish a breach
of the GPL sufficient to render the use of code unlicensed. But distribution by
one customer is not distribution by all. The motions are therefore GRANTED, but
only IN-PART.

**I. BACKGROUND**

**A. The Parties**

Plaintiff XimpleWare is a California corporation based in Milpitas engaged in
the design, development and distribution of computer software. XimpleWare spent
over a decade developing and fine-tuning its copyrighted software product,
known as "VTD-XML" or "VTD XML Extended" (collectively, the "Product"), which
reads and parses XML code more efficiently and faster than alternative XML
parsers. Efficiency and speed are critical in many applications of XML,
especially in large scale enterprise data interchange applications where entire
server computers are dedicated to handling streams of XML data. If XML data can
be processed faster, then fewer servers are needed, less leased space in data
centers is needed for those servers, and less energy is required to power those
servers—altogether greatly reducing computing needs and costs.

XimpleWare made the business decision to license the Product and related source
code under an "open source" license known as the GNU General Public License
version 2. The GPL requires, among other things, that: (1) any changes made to
the code carry notices stating that the files were changed, and the dates of
all changes; (2) any code created or derived from GPL-protected code must also
be licensed under the GPL; (3) copyright notices must print or display when the
code is run; and (4) when distributed, the program must be accompanied by the
complete machine-readable source code. All four conditions must be met, and the
GPL requires strict compliance.

XimpleWare is the owner of all right, title, and interest in various patents
related to the Product and related source code, including U.S. Patent Nos. 7,
133,857, 7620,652, and 7,761,459. The first patent at issue (the '857 Patent),
filed in 2002 and issued in 2006, is titled "Processing Structured Data," and
contains 43 claims (including 7 independent claims) covering methods,
apparatuses, and program storage devices for "efficiently processing a
structured data file" or "efficiently processing structured data"—including
XML. The '652 Patent, filed in 2006 and issued in 2009, contains 35 claims
(including 8 independent claims) for methods, apparatuses, and program storage
devices, and focuses on efficiently processing structured data like XML. The
'459 Patent, filed in 2006 and issued in 2010, contains 24 claims (including 4
independent claims) for methods, apparatuses, hardware devices, and program
storage devices, and again focuses on efficiently processing structured data
like XML....

**B. XimpleWare's Patent Infringement Claims**

This case spawned from earlier litigation between Versata and Ameriprise.
During that litigation, Ameriprise reached out to XimpleWare to support its
defense of the pending litigation and informed XimpleWare that it had
discovered XimpleWare VTM-XML source code throughout Versata's DCM product.
In violation of Versata's license under the GNU. XimpleWare then filed this
suit against the Versata Defendants, Ameriprise and other Versata customers.
XimpleWare's complaint asserts claims for (1) direct infringement of the
'857, '459 and '652 patents under 35 U.S.C. § 271(a) against all defendants;
(2) inducement under 35 U.S.C. § 271(b) against Versata and its corporate
parents Aurea and Trilogy; and (3) declaratory relief that the asserted
patents are valid and enforceable.

\[...\]

**III. DISCUSSION**

**A. The Versata Customers' Motions to Dismiss**

The court starts with the customers' motions challenging XimpleWare's
allegations of direct infringement [of Ximpleware's patents] pursuant
to Section 271(a).

Because an express license is a defense to patent infringement, XimpleWare's
direct infringement claims against Versata's customers turn on whether the
customers' distribution is licensed under the GPL. The reason is that the GPL
provides that even if the original licensee — here, one of the Versata entities
— breaches its license for whatever reason, third-party customers of that
original license retain the right to use XimpleWare's software so long as the
customer does not itself breach the license by "distributing" XimpleWare's
software without satisfying an attendant conditions. Because XimpleWare has
plainly alleged that the customers did not satisfy these attendant
conditions, the only real issue to resolve is whether XimpleWare has
sufficiently alleged that its software was "distributed" by the customers when
they shared the software with their independent contractors, franchisees, and
producers.

The customers marshal two primary arguments against such a conclusion. First,
the customers argue that any independent contractor or the like working for the
customers has no need for the software because the software is designed to
calculate the commissions owed by the customers on various financial
transactions. In short, there is no need in the field to use what is back
office software. Second, the complaint does not allege Versata's customers
shared the software with independent contractors who then themselves copied,
distributed or used it, and sharing the software with independent contractors
working with the customers alone does not constitute distribution. Put another
way, this is effectively internal distribution, and internal distribution is
not enough to breach the GPL.

The customers, or rather certain customers, are correct: XimpleWare's
allegation that the Versata customers distributed XimpleWare's software without
specificity is insufficient. The bundling of customer defendants into a
conclusory statement does not in any way provide adequate notice. This is
classic Iqbal and Twombly territory. Because XimpleWare has not sufficiently
alleged the customers other than Ameriprise distributed the Versata software to
any unrelated third party, no distribution-related conditions were triggered.

With respect to Amerirprise, XimpleWare has alleged enough to clear the bar set
by Rule 8. To understand why, one need only look to Judge Illston's recent
decision in a parallel copyright infringement case between XimpleWare and
Ameriprise. As Judge Illston explains, "[a]ccepting as true the facts alleged
in the amended complaint and drawing all reasonable inferences in favor of
XimpleWare, as it must, the Court finds that XimpleWare has alleged Ameriprise
reproduced and distributed the software outside of Ameriprise and to
non-employees, thereby acting outside the scope of the GPL. XimpleWare has
therefore stated a claim of copyright infringement." While Ameriprise has cited
two Fifth Circuit cases suggesting that sharing code with contractors is not
distribution, neither case was before the court on a motion to dismiss, when
all allegations must be accepted as true. In sum, Paragraph 85 of the amended
complaint fails to state a claim for patent infringement against any Versata
customer, except as to Ameriprise.


#### In re Spansion, Inc.

--------------------------------------------------------------------------------
Excerpt from _In re Spansion, Inc._, 507 F. App'x 125, 128 (3d Cir. 2012),
internal citations omitted.[^SpansionHeadnote]

[^SpansionHeadnote]: _In re Spansion, Inc._, 507 F. App'x 125, 128 (3d Cir. 2012), _available at_ [http://www.ca3.uscourts.gov/opinarch/113323np.pdf](http://www.ca3.uscourts.gov/opinarch/113323np.pdf)

"[A] license ... [is] a mere waiver of the right to sue by the patentee."
A license need not be a formal grant, but is instead a "consent[] to [the]
use of the patent in making or using it, or selling it ... and a defense to
an action for a tort." The Court of Appeals for the Federal Circuit
explained that the inquiry focuses on what the agreement authorizes, not
whether the language is couched in terms of a license or a covenant not
to sue; effectively the two are equivalent.
___

#### Discussion

1. As noted by both the *Natterman* and *Davidson* courts, the existence of
  a patent grant given ambiguous language is interpreted according to state
  contract law. Does that mean that the existence of a patent license may
  vary from state to state?
 
2. The *Davidson* court found that there was no express patent license
  because Windsor did not have the power to bind the patent owner. The
  rights granted by open source licenses, however, are intentionally broad.
  Would the rule described by the *Spansion* court (look to "what the
  agreement authorizes") make a court more likely to find an express
  patent grant?
 
3. The *Ximpleware* court found that because internal use by the Defendant
  was licensed under the GPL version 2, that internal use was also subject
  to an "express license" to the associated patents. On what basis do you
  think that the judge found the express license?
___

## Patent Exhaustion

Patent exhaustion is a U.S. common law doctrine limiting the scope of control
that a patent holder can have after the "authorized sale" of a patented object.
Under the doctrine, an authorized sale "exhausts" and thus entirely removes
the ability of the patent older to use the threat of patent infringement to
control the use and sale of the sold object. The purchaser is free to *use* or
*resell* the patented object without restrictions based in patent law.[^Repair]
This right to use and resell the object extends to subsequent purchasers, even
those that acquire the patented object from a third party rather than from the
patent holder herself.

Patent exhaustion is different than licensing. "Exhaustion doctrine, following
the common-law limitation on servitudes on chattels, creates an implied-in-law
property right based on an authorized acquisition, beyond what an
implied-in-fact analysis would support under 'implied license'
principles."[^HelferichFN] A license can be limited in scope, so that acting
beyond the bounds contemplated in the license is an infringement on the
rights of the patent owner. However, as soon as an object "embodying" the
patent claims is sold by the patent holder or an authorized licensee,
the exhaustion doctrine prevents lawsuits against any subsequent users
"downstream" in the stream of commerce.

The law regarding patent exhaustion has been substantially clarified in
recent years by the Supreme Court, writing in both _Quanta Computer, Inc. v.
LG Electronics, Inc._ ("Quanta") and _Impression Products, Inc. v. Lexmark
International,Inc._ ("Lexmark"). As you read the following cases, consider both
how computer code might partially or fully "embody" a patented system or
method, and how distribution occurs in an open source context, where code is
freely passed from person to person.

[^Repair]: But note, under the repair and reconstruction doctrine, an authorized sale does not automatically grant the ability for purchasers to "make" the patented object. A new making can occur in the context of extensive reconstruction or repair, or due to the result of self-replicating technology (such as patented plants). *See, e.g.* _Aro Mfg. Co. v. Convertible Top Replacement Co._, 377 U.S. 476 (1964); _Aro Mfg. Co. v. Convertible Top Replacement Co._, 365 U.S. 336 (1961); _Morgan Envelope Co. v. Albany Perforated Wrapping Paper Co._, 152 U.S. 425 (1894); _Cotton-Tie Co. v. Simmons_, 106 U.S. 89 (1882). *See also* _Bowman v. Monsanto Co._, 569 U.S. 278 (2013) for a discussion of the exhaustion doctrine relative to plants. However, the right to make can be granted via license; *see* discussion, *infra.*

[^HelferichFN]: _Helferich Patent Licensing, Ltd. Liab. Co. v. N.Y. Times Co._, 778 F.3d 1293, 1311 (Fed. Cir. 2015).

### Cases

#### Quanta Computer, Inc. v. LG Electronics, Inc.

--------------------------------------------------------------------------------
United States Supreme Court (2008)[^QuantaHeadnote]

[^QuantaHeadnote]:_Quanta Comput., Inc. v. LG Elecs., Inc._, 553 U.S. 617, 128 S. Ct. 2109 (2008), _available at_ [https://supreme.justia.com/cases/federal/us/553/617/](https://supreme.justia.com/cases/federal/us/553/617/)

*Justice Thomas delivered the opinion of the Court.*

For over 150 years this Court has applied the doctrine of patent exhaustion to
limit the patent rights that survive the initial authorized sale of a patented
item. In this case, we decide whether patent exhaustion applies to the sale of
components of a patented system that must be combined with additional
components in order to practice the patented methods. The Court of Appeals for
the Federal Circuit held that the doctrine does not apply to method patents at
all and, in the alternative, that it does not apply here because the sales were
not authorized by the license agreement. We disagree on both scores. Because
the exhaustion doctrine applies to method patents, and because the license
authorizes the sale of components that substantially embody the patents in
suit, the sale exhausted the patents.

**I**

Respondent LG Electronics, Inc. (LGE), purchased a portfolio of computer
technology patents in 1999, including the three patents at issue here: U. S.
Patent Nos. 4,939,641 ('641); 5,379,379 ('379); and 5,077,733 ('733)
(collectively LGE Patents)....

LGE licensed a patent portfolio, including the LGE Patents, to Intel
Corporation (Intel). The cross-licensing agreement (License Agreement) permits
Intel to manufacture and sell microprocessors and chipsets that use the LGE
Patents (the Intel Products). The License Agreement authorizes Intel to
"'make, use, sell (directly or indirectly), offer to sell, import or otherwise
dispose of'" its own products practicing the LGE Patents. Brief for
Petitioners 8 (quoting App. 154).[^QuantaFNOmitted] Notwithstanding this
broad language, the License Agreement contains some limitations. Relevant
here, it stipulates that no license

> "'is granted by either party hereto … to any third party for the combination
> by a third party of Licensed Products of either party with items, components,
> or the like acquired … from sources other than a party hereto, or for the use,
> import, offer for sale or sale of such combination.'"
> (quoting App. 164).

[^QuantaFNOmitted]: Some footnotes and cites to the record have been omitted.

The License Agreement purports not to alter the usual rules of patent
exhaustion, however, providing that, "'[n]otwithstanding anything to the
contrary contained in this Agreement, the parties agree that nothing herein
shall in any way limit or alter the effect of patent exhaustion that would
otherwise apply when a party hereto sells any of its Licensed Products.'"
(quoting App. 164).

In a separate agreement (Master Agreement), Intel agreed to give written notice
to its own customers informing them that, while it had obtained a broad license
"'ensur[ing] that any Intel product that you purchase is licensed by LGE and
thus does not infringe any patent held by LGE,'" the license "'does not extend,
expressly or by implication, to any product that you make by combining an Intel
product with any non-Intel product.'" (emphasis deleted)
(quoting App. 198). The Master Agreement also provides that "'a breach of this
Agreement shall have no effect on and shall not be grounds for termination of
the Patent License.'" (quoting App. 176).

Petitioners, including Quanta Computer (collectively Quanta), are a group of
computer manufacturers. Quanta purchased microprocessors and chipsets from
Intel and received the notice required by the Master Agreement. Nonetheless,
Quanta manufactured computers using Intel parts in combination with non-Intel
memory and buses in ways that practice the LGE Patents. Quanta does not modify
the Intel components and follows Intel's specifications to incorporate the
parts into its own systems.

LGE filed a complaint against Quanta, asserting that the combination of the
Intel Products with non-Intel memory and buses infringed the LGE Patents. The
District Court granted summary judgment to Quanta, holding that, for purposes
of the patent exhaustion doctrine, the license LGE granted to Intel resulted in
forfeiture of any potential infringement actions against legitimate purchasers
of the Intel Products. _LG Electronics, Inc. v. Asustek Computer, Inc._,
65 USPQ 2d 1589, 1593, 1600 (ND Cal. 2002). The court found that, although the
Intel Products do not fully practice any of the patents at issue, they have no
reasonable noninfringing use and therefore their authorized sale exhausted
patent rights in the completed computers under _United States v. Univis Lens
Co._, 316 U. S. 241 (1942). *Asustek*, *supra*, at 1598–1600. In a subsequent
order limiting its summary judgment ruling, the court held that patent
exhaustion applies only to apparatus or composition-of-matter claims that
describe a physical object, and does not apply to process, or method, claims
that describe operations to make or use a product. _LG Electronics, Inc. v.
Asustek Computer, Inc._, 248 F. Supp. 2d 912, 918 (ND Cal. 2003). Because each
of the LGE Patents includes method claims, exhaustion did not apply.

The Court of Appeals for the Federal Circuit affirmed in part and reversed in
part. It agreed that the doctrine of patent exhaustion does not apply to method
claims. In the alternative, it concluded that exhaustion did not apply because
LGE did not license Intel to sell the Intel Products to Quanta for use in
combination with non-Intel products. 453 F. 3d, at 1370.

We granted certiorari, 551 U. S. ___ (2007).

**II**

The longstanding doctrine of patent exhaustion provides that the initial
authorized sale of a patented item terminates all patent rights to that item.
This Court first applied the doctrine in 19th-century cases addressing patent
extensions on the Woodworth planing machine. Purchasers of licenses to sell and
use the machine for the duration of the original patent term sought to continue
using the licenses through the extended term. The Court held that the extension
of the patent term did not affect the rights already secured by purchasers who
bought the item for use "in the ordinary pursuits of life." _Bloomer v.
McQuewan_, 14 How. 539, 549 (1853); see also *ibid*. ("[W]hen the machine
passes to the hands of the purchaser, it is no longer within the limits of the
monopoly"); _Bloomer v. Millinger_, 1 Wall. 340, 351 (1864). In _Adams v.
Burke_, 17 Wall. 453 (1873), the Court affirmed the dismissal of a patent
holder's suit alleging that a licensee had violated postsale restrictions on
where patented coffin-lids could be used. "[W]here a person ha[s] purchased
a patented machine of the patentee or his assignee," the Court held, "this
purchase carrie[s] with it the right to the use of that machine so long as it
[is] capable of use." *Id*., at 455.

Although the Court permitted postsale restrictions on the use of a patented
article in _Henry v. A. B. Dick Co._, 224 U. S. 1 (1912),[FN2] that decision
was short lived. In 1913, the Court refused to apply *A. B. Dick* to uphold
price-fixing provisions in a patent license. See _Bauer & Cie v. O'Donnell_,
229 U. S. 1, 14–17 (1913). Shortly thereafter, in _Motion Picture Patents Co.
v. Universal Film Mfg. Co._, 243 U. S. 502, 518 (1917), the Court explicitly
overruled *A. B. Dick*. In that case, a patent holder attempted to limit
purchasers' use of its film projectors to show only film made under a patent
held by the same company. The Court noted the "increasing frequency" with which
patent holders were using *A. B. Dick*-style licenses to limit the use of their
products and thereby using the patents to secure market control of related,
unpatented items. 243 U. S., at 509, 516–517. Observing that "the primary
purpose of our patent laws is not the creation of private fortunes for the
owners of patents but is 'to promote the progress of science and useful arts,'"
id., at 511 (quoting U. S. Const., Art. I, §8, cl. 8), the Court held that "the
scope of the grant which may be made to an inventor in a patent, pursuant to
the [patent] statute, must be limited to the invention described in the
claims of his patent." 243 U. S., at 511. Accordingly, it reiterated the rule
that "the right to vend is exhausted by a single, unconditional sale, the
article sold being thereby carried outside the monopoly of the patent law and
rendered free of every restriction which the vendor may attempt to put upon
it." *Id*., at 516.

This Court most recently discussed patent exhaustion in *Univis*,
316 U. S. 241, on which the District Court relied. Univis Lens Company, the
holder of patents on eyeglass lenses, licensed a purchaser to manufacture lens
blanks by fusing together different lens segments to create bi- and tri-focal
lenses and to sell them to other Univis licensees at agreed-upon rates.... The
Court granted certiorari to determine whether Univis' patent monopoly survived
the sale of the lens blanks by the licensed manufacturer and therefore shielded
Univis' pricing scheme from the Sherman Act.

The Court assumed that the Univis patents containing claims for finished lenses
were practiced in part by the wholesalers and finishing retailers who ground
the blanks into lenses, and held that the sale of the lens blanks exhausted the
patents on the finished lenses. *Univis*, 316 U. S., at 248–249. The Court
explained that the lens blanks "embodi[ed] essential features of the patented
device and [were] without utility until … ground and polished as the finished
lens of the patent." *Id*., at 249. The Court noted that:

> "where one has sold an uncompleted article which, because it embodies
> essential features of his patented invention, is within the protection of his
> patent, and has destined the article to be finished by the purchaser in
> conformity to the patent, he has sold his invention so far as it is or may be
> embodied in that particular article." *Id*., at 250–251.

In sum, the Court concluded that the traditional bar on patent restrictions
following the sale of an item applies when the item sufficiently embodies the
patent—even if it does not completely practice the patent—such that its only
and intended use is to be finished under the terms of the patent.

With this history of the patent exhaustion doctrine in mind, we turn to the
parties' arguments.

**III**

**A**

LGE argues that the exhaustion doctrine is inapplicable here because it does
not apply to method claims, which are contained in each of the LGE Patents. LGE
reasons that, because method patents are linked not to a tangible article but
to a process, they can never be exhausted through a sale. Rather, practicing
the patent—which occurs upon each use of an article embodying a method
patent—is permissible only to the extent rights are transferred in an
assignment contract. Quanta, in turn, argues that there is no reason to
preclude exhaustion of method claims, and points out that both this Court and
the Federal Circuit have applied exhaustion to method claims. It argues that
any other rule would allow patent holders to avoid exhaustion entirely by
inserting method claims in their patent specifications.

Quanta has the better of this argument. Nothing in this Court's approach to
patent exhaustion supports LGE's argument that method patents cannot be
exhausted. It is true that a patented method may not be sold in the same way as
an article or device, but methods nonetheless may be "embodied" in a product,
the sale of which exhausts patent rights. Our precedents do not differentiate
transactions involving embodiments of patented methods or processes from those
involving patented apparatuses or materials. To the contrary, this Court has
repeatedly held that method patents were exhausted by the sale of an item that
embodied the method. In _Ethyl Gasoline Corp. v. United States_, 309 U. S. 436,
446, 457 (1940), for example, the Court held that the sale of a motor fuel
produced under one patent also exhausted the patent for a method of using the
fuel in combustion motors. Similarly, as previously described, *Univis* held
that the sale of optical lens blanks that partially practiced a patent
exhausted the method patents that were not completely practiced until the
blanks were ground into lenses. 316 U. S., at 248–251.

These cases rest on solid footing. Eliminating exhaustion for method patents
would seriously undermine the exhaustion doctrine. Patentees seeking to avoid
patent exhaustion could simply draft their patent claims to describe a method
rather than an apparatus.[FN5] Apparatus and method claims "may approach each
other so nearly that it will be difficult to distinguish the process from the
function of the apparatus." _United States ex rel. Steinmetz v. Allen_, 192 U.
S. 543, 559 (1904). By characterizing their claims as method instead of
apparatus claims, or including a method claim for the machine's patented method
of performing its task, a patent drafter could shield practically any patented
item from exhaustion.

This case illustrates the danger of allowing such an end-run around exhaustion.
On LGE's theory, although Intel is authorized to sell a completed computer
system that practices the LGE Patents, any downstream purchasers of the system
could nonetheless be liable for patent infringement. Such a result would
violate the longstanding principle that, when a patented item is "once lawfully
made and sold, there is no restriction on [its] use to be implied for the
benefit of the patentee." *Adams*, 17 Wall., at 457. We therefore reject LGE's
argument that method claims, as a category, are never exhaustible.

**B**

We next consider the extent to which a product must embody a patent in order to
trigger exhaustion. Quanta argues that, although sales of an incomplete article
do not necessarily exhaust the patent in that article, the sale of the
microprocessors and chipsets exhausted LGE's patents in the same way the sale
of the lens blanks exhausted the patents in *Univis*. Just as the lens blanks
in *Univis* did not fully practice the patents at issue because they had not
been ground into finished lenses, Quanta observes, the Intel Products cannot
practice the LGE Patents—or indeed, function at all—until they are combined
with memory and buses in a computer system. If, as in *Univis*, patent rights
are exhausted by the sale of the incomplete item, then LGE has no postsale
right to require that the patents be practiced using only Intel parts. Quanta
also argues that exhaustion doctrine will be a dead letter unless it is
triggered by the sale of components that essentially, even if not completely,
embody an invention. Otherwise, patent holders could authorize the sale of
computers that are complete with the exception of one minor step—say, inserting
the microprocessor into a socket—and extend their rights through each
downstream purchaser all the way to the end user.

LGE, for its part, argues that *Univis* is inapplicable here for three reasons.
First, it maintains that *Univis* should be limited to products that contain
all the physical aspects needed to practice the patent. On that theory, the
Intel Products cannot embody the patents because additional physical components
are required before the patents can be practiced. Second, LGE asserts that in
*Univis* there was no "patentable distinction" between the lens blanks and the
patented finished lenses since they were both subject to the same patent. Brief
for Respondent 14 (citing *Univis*, *supra*, at 248–252). In contrast, it
describes the Intel Products as "independent and distinct products" from the
systems using the LGE Patents and subject to "independent patents." Brief for
Respondent 13. Finally, LGE argues that *Univis* does not apply because the
Intel Products are analogous to individual elements of a combination patent,
and allowing sale of those components to exhaust the patent would impermissibly
"ascrib[e] to one element of the patented combination the status of the
patented invention in itself." _Aro Mfg. Co. v. Convertible Top Replacement
Co._, 365 U. S. 336, 344–345 (1961).

We agree with Quanta that *Univis* governs this case. As the Court there
explained, exhaustion was triggered by the sale of the lens blanks because
their only reasonable and intended use was to practice the patent and because
they "embodie[d] essential features of [the] patented invention." 316 U.S.,
at 249–251. Each of those attributes is shared by the microprocessors and
chipsets Intel sold to Quanta under the License Agreement.

First, *Univis* held that "the authorized sale of an article which is capable
of use only in practicing the patent is a relinquishment of the patent monopoly
with respect to the article sold." *Id*., at 249. The lens blanks in *Univis*
met this standard because they were "without utility until [they were] ground
and polished as the finished lens of the patent." *Ibid*. Accordingly, "the
only object of the sale [was] to enable the [finishing retailer] to grind and
polish it for use as a lens by the prospective wearer." *Ibid*. Here, LGE has
suggested no reasonable use for the Intel Products other than incorporating
them into computer systems that practice the LGE Patents.[FN6] Nor can we can
discern one: A microprocessor or chipset cannot function until it is connected
to buses and memory. And here, as in *Univis*, the only apparent object of
Intel's sales to Quanta was to permit Quanta to incorporate the Intel Products
into computers that would practice the patents.

Second, the lens blanks in *Univis* "embodie[d] essential features of [the]
patented invention." *Id*., at 250–251. The essential, or inventive, feature of
the Univis lens patents was the fusing together of different lens segments to
create bi- and tri-focal lenses. The finishing process performed by the
finishing and prescription retailers after the fusing was not unique. As the
United States explained:

> "The finishing licensees finish Univis lens blanks in precisely the same
> manner as they finish all other bifocal lens blanks. Indeed, appellees have
> never contended that their licensing system is supported by patents covering
> methods or processes relating to the finishing of lens blanks. Consequently,
> it appears that appellees perform all of the operations which contribute any
> claimed element of novelty to Univis lenses." Brief for United States in
> _United States v. Univis Lens Co._, O. T. 1941, No. 855 et al., p. 10 \
> (footnote and citations omitted).

While the Court assumed that the finishing process was covered by the patents,
*Univis*, *supra*, at 248–249, and the District Court found that it was
necessary to make a working lens, _United States v. Univis Lens Co._, 41 F.
Supp. 258, 262–263 (SDNY 1941), the grinding process was not central to the
patents. That standard process was not included in detail in any of the patents
and was not referred to at all in two of the patents. Those that did mention
the finishing process treated it as incidental to the invention, noting, for
example, that "[t]he blank is then ground in the usual manner," U. S. Patent
No. 1,876,497, p. 2, or simply that the blank is "then ground and polished," U.
S. Patent No. 1,632,208, p. 1, Tr. of Record in _United States v. Univis Lens
Co._, O. T. 1941, No. 855 et al., pp. 516, 498.

Like the *Univis* lens blanks, the Intel Products constitute a material part of
the patented invention and all but completely practice the patent. Here, as in
*Univis*, the incomplete article substantially embodies the patent because the
only step necessary to practice the patent is the application of common
processes or the addition of standard parts. Everything inventive about each
patent is embodied in the Intel Products. They control access to main and cache
memory, practicing the '641 and '379 patents by checking cache memory against
main memory and comparing read and write requests. They also control priority
of bus access by various other computer components under the '733 patent.
Naturally, the Intel Products cannot carry out these functions unless they are
attached to memory and buses, but those additions are standard components in
the system, providing the material that enables the microprocessors and
chipsets to function. The Intel Products were specifically designed to function
only when memory or buses are attached; Quanta was not required to make any
creative or inventive decision when it added those parts. Indeed, Quanta had no
alternative but to follow Intel's specifications in incorporating the Intel
Products into its computers because it did not know their internal structure,
which Intel guards as a trade secret. Intel all but practiced the patent
itself by designing its products to practice the patents, lacking only the
addition of standard parts.

We are unpersuaded by LGE's attempts to distinguish *Univis*. First, there is
no reason to distinguish the two cases on the ground that the articles in
*Univis* required the removal of material to practice the patent while the
Intel Products require the addition of components to practice the patent. LGE
characterizes the lens blanks and lenses as sharing a "basic nature" by virtue
of their physical similarity, while the Intel Products embody only some of the
"patentably distinct elements and steps" involved in the LGE Patents. Brief for
Respondent 26–27. But we think that the nature of the final step, rather than
whether it consists of adding or deleting material, is the relevant
characteristic. In each case, the final step to practice the patent is common
and noninventive: grinding a lens to the customer's prescription, or connecting
a microprocessor or chipset to buses or memory. The Intel Products embody the
essential features of the LGE Patents because they carry out all the inventive
processes when combined, according to their design, with standard components.

With regard to LGE's argument that exhaustion does not apply across patents, we
agree on the general principle: The sale of a device that practices patent A
does not, by virtue of practicing patent A, exhaust patent B. But if the device
practices patent A while substantially embodying patent B, its relationship to
patent A does not prevent exhaustion of patent B. For example, if the *Univis*
lens blanks had been composed of shatter-resistant glass under patent A, the
blanks would nonetheless have substantially embodied, and therefore exhausted,
patent B for the finished lenses. This case is no different. While each Intel
microprocessor and chipset practices thousands of individual patents, including
some LGE patents not at issue in this case, the exhaustion analysis is not
altered by the fact that more than one patent is practiced by the same product.
The relevant consideration is whether the Intel Products that partially
practice a patent—by, for example, embodying its essential features—exhaust
that patent.

Finally, LGE's reliance on *Aro* is misplaced because that case dealt only with
the question whether replacement of one part of a patented combination
infringes the patent. First, the replacement question is not at issue here.
Second, and more importantly, *Aro* is not squarely applicable to the
exhaustion of patents like the LGE Patents that do not disclose a new
combination of existing parts. *Aro* described combination patents as
"cover[ing] only the totality of the elements in the claim [so] that no
element, separately viewed, is within the grant." 365 U. S., at 344; see also
_Mercoid Corp. v. Mid-Continent Investment Co._, 320 U. S. 661, 667–668 (1944)
(noting that, in a combination patent, "the combination is the invention and it
is distinct from any" of its elements). *Aro*'s warning that no element can be
viewed as central to or equivalent to the invention is specific to the context
in which the combination itself is the only inventive aspect of the patent. In
this case, the inventive part of the patent is not the fact that memory and
buses are combined with a microprocessor or chipset; rather, it is included in
the design of the Intel Products themselves and the way these products access
the memory or bus.

**C**

Having concluded that the Intel Products embodied the patents, we next consider
whether their sale to Quanta exhausted LGE's patent rights. Exhaustion is
triggered only by a sale authorized by the patent holder. *Univis*, 316 U. S.,
at 249.

LGE argues that there was no authorized sale here because the License Agreement
does not permit Intel to sell its products for use in combination with
non-Intel products to practice the LGE Patents. It cites _General Talking
Pictures Corp. v. Western Elec. Co._, 304 U. S. 175 (1938), and _General
Talking Pictures Corp. v. Western Elec. Co._, 305 U. S. 124 (1938), in which
the manufacturer sold patented amplifiers for commercial use, thereby breaching
a license that limited the buyer to selling the amplifiers for private and home
use. The Court held that exhaustion did not apply because the manufacturer had
no authority to sell the amplifiers for commercial use, and the manufacturer
"could not convey to petitioner what both knew it was not authorized to sell."
General Talking Pictures, supra, at 181. LGE argues that the same principle
applies here: Intel could not convey to Quanta what both knew it was not
authorized to sell, i.e., the right to practice the patents with non-Intel
parts.

LGE overlooks important aspects of the structure of the Intel-LGE transaction.
Nothing in the License Agreement restricts Intel's right to sell its
microprocessors and chipsets to purchasers who intend to combine them with
non-Intel parts. It broadly permits Intel to "'make, use, [or] sell'"
products free of LGE's patent claims. To be sure, LGE did require Intel to
give notice to its customers, including Quanta, that LGE had not licensed
those customers to practice its patents. But neither party contends that
Intel breached the agreement in that respect. In any event, the provision
requiring notice to Quanta appeared only in the Master Agreement, and LGE
does not suggest that a breach of that agreement would constitute a breach
of the License Agreement. Hence, Intel's authority to sell its products
embodying the LGE Patents was not conditioned on the notice
or on Quanta's decision to abide by LGE's directions in that notice.

LGE points out that the License Agreement specifically disclaimed any license
to third parties to practice the patents by combining licensed products with
other components. But the question whether third parties received implied
licenses is irrelevant because Quanta asserts its right to practice the patents
based not on implied license but on exhaustion. And exhaustion turns only on
Intel's own license to sell products practicing the LGE Patents.

Alternatively, LGE invokes the principle that patent exhaustion does not apply
to postsale restrictions on "making" an article. But this is simply a
rephrasing of its argument that combining the Intel Products with other
components adds more than standard finishing to complete a patented article. As
explained above, making a product that substantially embodies a patent is, for
exhaustion purposes, no different from making the patented article itself. In
other words, no further "making" results from the addition of standard
parts—here, the buses and memory—to a product that already substantially
embodies the patent.

The License Agreement authorized Intel to sell products that practiced the LGE
Patents. No conditions limited Intel's authority to sell products substantially
embodying the patents. Because Intel was authorized to sell its products to
Quanta, the doctrine of patent exhaustion prevents LGE from further asserting
its patent rights with respect to the patents substantially embodied by those
products.[FN7]

**IV**

The authorized sale of an article that substantially embodies a patent exhausts
the patent holder's rights and prevents the patent holder from invoking patent
law to control postsale use of the article. Here, LGE licensed Intel to
practice any of its patents and to sell products practicing those patents.
Intel's microprocessors and chipsets substantially embodied the LGE Patents
because they had no reasonable noninfringing use and included all the inventive
aspects of the patented methods. Nothing in the License Agreement limited
Intel's ability to sell its products practicing the LGE Patents. Intel's
authorized sale to Quanta thus took its products outside the scope of the
patent monopoly, and as a result, LGE can no longer assert its patent rights
against Quanta. Accordingly, the judgment of the Court of Appeals is reversed.

It is so ordered.

*Selected footnotes from Quanta Computer, Inc. v. LG Electronics, Inc:*

[FN2]: The A. B. Dick Company sold mimeograph machines with an attached
license stipulating that the machine could be used only with ink, paper, and
other supplies made by the A. B. Dick Company. The Court rejected the notion
that a patent holder “can only keep the article within the control of the
patent by retaining the title,” *A. B. Dick*, 224 U. S., at 18, and held that
"any … reasonable stipulation, not inherently violative of some substantive
law" was "valid and enforceable," *id*., at 31. The only requirement, the Court
held, was that "the purchaser must have notice that he buys with only a
qualified right of use," so that a sale made without conditions resulted in
"an unconditional title to the machine, with no limitations upon the use."
*Id*., at 26.

[FN5]: One commentator recommends this strategy as a way to draft patent
claims that "will survive numerous transactions regarding the patented good,
allowing the force of the patent to intrude deeply into the stream of
commerce." Thomas, *Of Text, Technique, and the Tangible: Drafting Patent
Claims Around Patent Rules*, 17 J. Marshall J. Computer & Info. L. 219, 252
(1998); see also *id*., at 225–226 (advocating the conversion of apparatus
claims into method claims and noting that "[e]ven the most novice claims
drafter would encounter scant difficulty in converting a patent claim from
artifact to technique and back again").

[FN6]: LGE suggests that the Intel Products would not infringe its patents if
they were sold overseas, used as replacement parts, or engineered so that use
with non-Intel Products would disable their patented features. Brief for
Respondent 21–22, n. 10. But *Univis* teaches that the question is whether the
product is "capable of use only in *practicing* the patent," not whether those
uses are infringing. 316 U.S., at 249 (emphasis added). Whether outside the
country or functioning as replacement parts, the Intel Products would still be
practicing the patent, even if not infringing it. And since the features
partially practicing the patent are what must have an alternative use,
suggesting that they be disabled is no solution. The disabled features would
have no real *use*.

[FN7]: We note that the authorized nature of the sale to Quanta does not
necessarily limit LGE's other contract rights. LGE's complaint does not include
a breach-of-contract claim, and we express no opinion on whether contract
damages might be available even though exhaustion operates to eliminate patent
damages. *See* _Keeler v. Standard Folding Bed Co._, 157 U. S. 659, 666 (1895)
("Whether a patentee may protect himself and his assignees by special contracts
brought home to the purchasers is not a question before us, and upon which we
express no opinion. It is, however, obvious that such a question would arise as
a question of contract, and not as one under the inherent meaning and effect of
the patent laws").


#### Impression Products v. Lexmark International

--------------------------------------------------------------------------------
United States Supreme Court (2017)[^LexmarkHeadnote]

[^LexmarkHeadnote]:_Impression Prods. v. Lexmark Int'l, Inc._, 137 S. Ct. 1523 (2017), _available at_ [https://caselaw.findlaw.com/us-supreme-court/15-1189.html](https://caselaw.findlaw.com/us-supreme-court/15-1189.html)

*Chief Justice Roberts delivered the opinion of the Court.*

A United States patent entitles the patent holder (the "patentee"), for a
period of 20 years, to "exclude others from making, using, offering for sale,
or selling [its] invention throughout the United States or importing the
invention into the United States." 35 U. S. C. §154(a). Whoever engages in one
of these acts "without authority" from the patentee may face liability for
patent infringement. §271(a).

When a patentee sells one of its products, however, the patentee can no longer
control that item through the patent laws--its patent rights are said to
"exhaust." The purchaser and all subsequent owners are free to use or resell
the product just like any other item of personal property, without fear of an
infringement lawsuit.

This case presents two questions about the scope of the patent exhaustion
doctrine: First, whether a patentee that sells an item under an express
restriction on the purchaser's right to reuse or resell the product may enforce
that restriction through an infringement lawsuit. And second, whether a
patentee exhausts its patent rights by selling its product outside the United
States, where American patent laws do not apply. We conclude that a patentee's
decision to sell a product exhausts all of its patent rights in that item,
regardless of any restrictions the patentee purports to impose or the location
of the sale.

**I**

The underlying dispute in this case is about laser printers-or, more
specifically, the cartridges that contain the powdery substance, known as
toner, that laser printers use to make an image appear on paper. Respondent
Lexmark International, Inc. designs, manufactures, and sells toner cartridges
to consumers in the United States and around the globe. It owns a number of
patents that cover components of those cartridges and the manner in which they
are used.

When toner cartridges run out of toner they can be refilled and used again.
This creates an opportunity for other companies-known as remanufacturers-to
acquire empty Lexmark cartridges from purchasers in the United States and
abroad, refill them with toner, and then resell them at a lower price than the
new ones Lexmark puts on the shelves.

Not blind to this business problem, Lexmark structures its sales in a way that
encourages customers to return spent cartridges. It gives purchasers two
options: One is to buy a toner cartridge at full price, with no strings
attached. The other is to buy a cartridge at roughly 20-percent off through
Lexmark's "Return Program." A customer who buys through the Return Program
still owns the cartridge but, in exchange for the lower price, signs a contract
agreeing to use it only once and to refrain from transferring the empty
cartridge to anyone but Lexmark. To enforce this single-use/no-resale
restriction, Lexmark installs a microchip on each Return Program cartridge that
prevents reuse once the toner in the cartridge runs out.

Lexmark's strategy just spurred remanufacturers to get more creative. Many kept
acquiring empty Return Program cartridges and developed methods to counteract
the effect of the microchips. With that technological obstacle out of the way,
there was little to prevent the re-manufacturers from using the Return Program
cartridges in their resale business. After all, Lexmark's contractual
single-use/no-resale agreements were with the initial customers, not with
downstream purchasers like the remanufacturers.

Lexmark, however, was not so ready to concede that its plan had been foiled. In
2010, it sued a number of remanufacturers, including petitioner Impression
Products, Inc., for patent infringement with respect to two groups of
cartridges. One group consists of Return Program cartridges that Lexmark sold
within the United States. Lexmark argued that, because it expressly prohibited
reuse and resale of these cartridges, the remanufacturers infringed the Lexmark
patents when they refurbished and resold them. The other group consists of all
toner cartridges that Lexmark sold abroad and that remanufacturers imported
into the country. Lexmark claimed that it never gave anyone authority to import
these cartridges, so the remanufacturers ran afoul of its patent rights by
doing just that.

Eventually, the lawsuit was whittled down to one defendant, Impression
Products, and one defense: that Lexmark's sales, both in the United States and
abroad, exhausted its patent rights in the cartridges, so Impression Products
was free to refurbish and resell them, and to import them if acquired abroad.
Impression Products filed separate motions to dismiss with respect to both
groups of cartridges. The District Court granted the motion as to the domestic
Return Program cartridges, but denied the motion as to the cartridges Lexmark
sold abroad. Both parties appealed.

The Federal Circuit considered the appeals en banc and ruled for Lexmark with
respect to both groups of cartridges....

We granted certiorari to consider the Federal Circuit's decisions with respect
to both domestic and international exhaustion, 580 U. S. ___ (2016), and now
reverse.

**II**
**A**

First up are the Return Program cartridges that Lexmark sold in the United
States. We conclude that Lexmark exhausted its patent rights in these
cartridges the moment it sold them. The single-use/no-resale restrictions in
Lexmark's contracts with customers may have been clear and enforceable under
contract law, but they do not entitle Lexmark to retain patent rights in an
item that it has elected to sell.

The Patent Act grants patentees the "right to exclude others from making,
using, offering for sale, or selling [their] invention[s]." 35 U. S. C.
§154(a). For over 160 years, the doctrine of patent exhaustion has imposed a
limit on that right to exclude. See _Bloomer v. McQuewan_, 14 How. 539 (1853).
The limit functions automatically: When a patentee chooses to sell an item,
that product "is no longer within the limits of the monopoly" and instead
becomes the "private, individual property" of the purchaser, with the rights
and benefits that come along with ownership. *Id*., at 549-550. A patentee is
free to set the price and negotiate contracts with purchasers, but may not, "by
virtue of his patent, control the use or disposition" of the product after
ownership passes to the purchaser. _United States v. Univis Lens Co._,
316 U. S. 241, 250 (1942) (emphasis added). The sale "terminates all patent
rights to that item." _Quanta Computer, Inc. v. LG Electronics, Inc._,
553 U. S. 617, 625 (2008).

This well-established exhaustion rule marks the point where patent rights yield
to the common law principle against restraints on alienation. The Patent Act
"promote[s] the progress of science and the useful arts by granting to
[inventors] a limited monopoly" that allows them to "secure the financial
rewards" for their inventions. *Univis*, 316 U. S., at 250. But once a patentee
sells an item, it has "enjoyed all the rights secured" by that limited
monopoly. _Keeler v. Standard Folding Bed Co._, 157 U. S. 659, 661 (1895).
Because "the purpose of the patent law is fulfilled . . . when the patentee has
received his reward for the use of his invention," that law furnishes "no basis
for restraining the use and enjoyment of the thing sold." *Univis*,
316 U. S., at 251.

We have explained in the context of copyright law that exhaustion has "an
impeccable historic pedigree," tracing its lineage back to the "common law's
refusal to permit restraints on the alienation of chattels." _Kirtsaeng v. John
Wiley & Sons, Inc._, 568 U. S. 519, 538 (2013). As Lord Coke put it in the 17th
century, if an owner restricts the resale or use of an item after selling it,
that restriction "is voide, because . . . it is against Trade and Traffique,
and bargaining and contracting betweene man and man." 1 E. Coke, Institutes of
the Laws of England §360, p. 223 (1628); see J. Gray, Restraints on the
Alienation of Property §27, p. 18 (2d ed. 1895) ("A condition or conditional
limitation on alienation attached to a transfer of the entire interest in
personalty is as void as if attached to a fee simple in land").

This venerable principle is not, as the Federal Circuit dismissively viewed it,
merely "one common-law jurisdiction's general judicial policy at one time
toward anti-alienation restrictions." 816 F. 3d, at 750. Congress enacted and
has repeatedly revised the Patent Act against the backdrop of the hostility
toward restraints on alienation. That enmity is reflected in the exhaustion
doctrine. The patent laws do not include the right to "restrain[ ] . . .
further alienation" after an initial sale; such conditions have been "hateful
to the law from Lord Coke's day to ours" and are "obnoxious to the public
interest." _Straus v. Victor Talking Machine Co._, 243 U. S. 490, 501 (1917).
"The inconvenience and annoyance to the public that an opposite conclusion
would occasion are too obvious to require illustration." *Keeler*, 157 U. S.,
at 667.

But an illustration never hurts. Take a shop that restores and sells used cars.
The business works because the shop can rest assured that, so long as those
bringing in the cars own them, the shop is free to repair and resell those
vehicles. That smooth flow of commerce would sputter if companies that make the
thousands of parts that go into a vehicle could keep their patent rights after
the first sale. Those companies might, for instance, restrict resale rights and
sue the shop owner for patent infringement. And even if they refrained from
imposing such restrictions, the very threat of patent liability would force the
shop to invest in efforts to protect itself from hidden lawsuits. Either way,
extending the patent rights beyond the first sale would clog the channels of
commerce, with little benefit from the extra control that the patentees retain.
And advances in technology, along with increasingly complex supply chains,
magnify the problem. *See* Brief for Costco Wholesale Corp. et al. as Amici
Curiae 7-9; Brief for Intel Corp. et al. as Amici Curiae 17, n. 5 ("A generic
smartphone assembled from various high-tech components could practice an
estimated 250,000 patents").

This Court accordingly has long held that, even when a patentee sells an item
under an express restriction, the patentee does not retain patent rights in
that product. In _Boston Store of Chicago v. American Graphophone Co._, for
example, a manufacturer sold graphophones--one of the earliest devices for
recording and reproducing sounds--to retailers under contracts requiring those
stores to resell at a specific price. 246 U. S. 8, 17-18 (1918). When the
manufacturer brought a patent infringement suit against a retailer who sold for
less, we concluded that there was "no room for controversy" about the result:
By selling the item, the manufacturer placed it "beyond the confines of the
patent law, [and] could not, by qualifying restrictions as to use, keep
[it] under the patent monopoly." Id., at 20, 25.

Two decades later, we confronted a similar arrangement in United States v.
Univis Lens Co. There, a company that made eyeglass lenses authorized an agent
to sell its products to wholesalers and retailers only if they promised to
market the lenses at fixed prices. The Government filed an antitrust lawsuit,
and the company defended its arrangement on the ground that it was exercising
authority under the Patent Act. We held that the initial sales
"relinquish[ed] . . . the patent monopoly with respect to the article[s]
sold," so the "stipulation . . . fixing resale prices derive[d] no support
from the patent and must stand on the same footing" as restrictions on
unpatented goods. 316 U. S., at 249-251.

It is true that Boston Store and Univis involved resale price restrictions
that, at the time of those decisions, violated the antitrust laws. But in both
cases it was the sale of the items, rather than the illegality of the
restrictions, that prevented the patentees from enforcing those resale price
agreements through patent infringement suits. And if there were any lingering
doubt that patent exhaustion applies even when a sale is subject to an express,
otherwise lawful restriction, our recent decision in _Quanta Computer, Inc. v.
LG Electronics, Inc._ settled the matter. In that case, a technology
company-with authorization from the patentee-sold microprocessors under
contracts requiring purchasers to use those processors with other parts that
the company manufactured. One buyer disregarded the restriction, and the
patentee sued for infringement. Without so much as mentioning the lawfulness of
the contract, we held that the patentee could not bring an infringement suit
because the "authorized sale . . . took its products outside the scope of the
patent monopoly." 553 U. S., at 638.

Turning to the case at hand, we conclude that this well-settled line of
precedent allows for only one answer: Lexmark cannot bring a patent
infringement suit against Impression Products to enforce the
single-use/no-resale provision accompanying its Return Program cartridges. Once
sold, the Return Program cartridges passed outside of the patent monopoly, and
whatever rights Lexmark retained are a matter of the contracts with its
purchasers, not the patent law.

**B**

The Federal Circuit reached a different result largely because it got off on
the wrong foot. The "exhaustion doctrine," the court believed, "must be
understood as an interpretation of" the infringement statute, which prohibits
anyone from using or selling a patented article "without authority" from the
patentee. 816 F. 3d, at 734 (quoting 35 U. S. C. §271(a)). Exhaustion reflects
a default rule that a patentee's decision to sell an item "presumptively
grant[s] 'authority' to the purchaser to use it and resell it." 816 F. 3d,
at 742. But, the Federal Circuit explained, the patentee does not have to hand
over the full "bundle of rights" every time. *Id*., at 741 (internal quotation
marks omitted). If the patentee expressly withholds a stick from the
bundle-perhaps by restricting the purchaser's resale rights-the buyer never
acquires that withheld authority, and the patentee may continue to enforce its
right to exclude that practice under the patent laws.

The misstep in this logic is that the exhaustion doctrine is not a presumption
about the authority that comes along with a sale; it is instead a limit on "the
scope of the patentee's rights."_ United States v. General Elec. Co._,
272 U. S. 476, 489 (1926) (emphasis added). The right to use, sell, or import
an item exists independently of the Patent Act. What a patent adds-and grants
exclusively to the patentee-is a limited right to prevent others from engaging
in those practices. See _Crown Die & Tool Co. v. Nye Tool & Machine Works_,
261 U. S. 24, 35 (1923). Exhaustion extinguishes that exclusionary power. See
*Bloomer*, 14 How., at 549 (the purchaser "exercises no rights created by the
act of Congress, nor does he derive title to [the item] by virtue of the . . .
exclusive privilege granted to the patentee"). As a result, the sale transfers
the right to use, sell, or import because those are the rights that come along
with ownership, and the buyer is free and clear of an infringement lawsuit
because there is no exclusionary right left to enforce.

The Federal Circuit also expressed concern that preventing patentees from
reserving patent rights when they sell goods would create an artificial
distinction between such sales and sales by licensees. Patentees, the court
explained, often license others to make and sell their products, and may place
restrictions on those licenses. A computer developer could, for instance,
license a manufacturer to make its patented devices and sell them only for
non-commercial use by individuals. If a licensee breaches the license by
selling a computer for commercial use, the patentee can sue the licensee for
infringement. And, in the Federal Circuit's view, our decision in
_General Talking Pictures Corp. v. Western Elec. Co._, 304 U. S. 175,
aff'd on reh'g, 305 U. S. 124 (1938), established that-when a patentee grants a
license "under clearly stated restrictions on post-sale activities" of those
who purchase products from the licensee-the patentee can also sue for
infringement those purchasers who knowingly violate the restrictions.
816 F. 3d, at 743-744. If patentees can employ licenses to impose post-sale
restrictions on purchasers that are enforceable through infringement suits, the
court concluded, it would make little sense to prevent patentees from doing so
when they sell directly to consumers.

The Federal Circuit's concern is misplaced. A patentee can impose restrictions
on licensees because a license does not implicate the same concerns about
restraints on alienation as a sale. Patent exhaustion reflects the principle
that, when an item passes into commerce, it should not be shaded by a legal
cloud on title as it moves through the marketplace. But a license is not about
passing title to a product, it is about changing the contours of the patentee's
monopoly: The patentee agrees not to exclude a licensee from making or selling
the patented invention, expanding the club of authorized producers and sellers.
*See* *General Elec. Co.*, 272 U. S., at 489-490. Because the patentee is
exchanging rights, not goods, it is free to relinquish only a portion of its
bundle of patent protections.

A patentee's authority to limit licensees does not, as the Federal Circuit
thought, mean that patentees can use licenses to impose post-sale restrictions
on purchasers that are enforceable through the patent laws. So long as a
licensee complies with the license when selling an item, the patentee has, in
effect, authorized the sale. That licensee's sale is treated, for purposes of
patent exhaustion, as if the patentee made the sale itself. The result: The
sale exhausts the patentee's rights in that item. See _Hobbie v. Jennison_, 149
U. S. 355, 362-363 (1893). A license may require the licensee to impose a
restriction on purchasers, like the license limiting the computer manufacturer
to selling for non-commercial use by individuals. But if the licensee does
so-by, perhaps, having each customer sign a contract promising not to use the
computers in business-the sale nonetheless exhausts all patent rights in the
item sold. See _Motion Picture Patents Co. v. Universal Film Mfg. Co._,
243 U. S. 502, 506-507, 516 (1917). The purchasers might not comply with the
restriction, but the only recourse for the licensee is through contract law,
just as if the patentee itself sold the item with a restriction.

General Talking Pictures involved a fundamentally different situation: There, a
licensee "knowingly ma[de] . . . sales . . . outside the scope of its
license." 304 U. S., at 181-182 (emphasis added). We treated the sale "as if no
license whatsoever had been granted" by the patentee, which meant that the
patentee could sue both the licensee and the purchaser-who knew about the
breach-for infringement. _General Talking Pictures Corp. v. Western Elec. Co._,
305 U. S. 124, 127 (1938). This does not mean that patentees can use licenses
to impose post-sale restraints on purchasers. Quite the contrary: The licensee
infringed the patentee's rights because it did not comply with the terms of its
license, and the patentee could bring a patent suit against the purchaser only
because the purchaser participated in the licensee's infringement. *General
Talking Pictures*, then, stands for the modest principle that, if a
patentee has not given authority for a licensee to make a sale, that sale
cannot exhaust the patentee's rights.

In sum, patent exhaustion is uniform and automatic. Once a patentee decides to
sell-whether on its own or through a licensee--that sale exhausts its patent
rights, regardless of any post-sale restrictions the patentee purports to
impose, either directly or through a license.

**III**

Our conclusion that Lexmark exhausted its patent rights when it sold the
domestic Return Program cartridges goes only halfway to resolving this case.
Lexmark also sold toner cartridges abroad and sued Impression Products for
patent infringement for "importing [Lexmark's] invention into the United
States." 35 U. S. C. §154(a). Lexmark contends that it may sue for infringement
with respect to all of the imported cartridges-not just those in the Return
Program--because a foreign sale does not trigger patent exhaustion unless the
patentee "expressly or implicitly transfer[s] or license[s]" its rights.
Brief for Respondent 36-37. The Federal Circuit agreed, but we do not. An
authorized sale outside the United States, just as one within the United
States, exhausts all rights under the Patent Act.

\[...\]

Exhaustion does not arise because of the parties' expectations about how sales
transfer patent rights. More is at stake when it comes to patents than simply
the dealings between the parties, which can be addressed through contract law.
Instead, exhaustion occurs because, in a sale, the patentee elects to give up
title to an item in exchange for payment. Allowing patent rights to stick
remora-like to that item as it flows through the market would violate the
principle against restraints on alienation. Exhaustion does not depend on
whether the patentee receives a premium for selling in the United States, or
the type of rights that buyers expect to receive. As a result, restrictions and
location are irrelevant; what matters is the patentee's decision to make a sale.

\*  \*  \*

The judgment of the United States Court of Appeals for the Federal Circuit is
reversed, and the case is remanded for further proceedings consistent with this
opinion.

It is so ordered.

--------------------------------------------------------------------------------
The cases above dealt with "authorized sales," which don't always occur in an
open source context. Usually, open source code is simply downloaded for free,
either directly from the licensor or (more frequently) from a third party
distributor or aggregator of open source code. The following two cases present
situations analogous to many situations that occur when using open source
code.

#### Lifescan Scotland, Ltd. v. Shasta Technologies

--------------------------------------------------------------------------------

Excerpt from _LifeScan Scot., Ltd. v. Shasta Techs., LLC._, 734 F.3d 1361, 1374-1375 (Fed. Cir. 2013), some internal citations omitted.[^LifeScanHeadnote]

[^LifeScanHeadnote]: _LifeScan Scot., Ltd. v. Shasta Techs., LLC._, 734 F.3d 1361, 1374-1375 (Fed. Cir. 2013), _available at_ [https://www.leagle.com/decision/infco20131104107](https://www.leagle.com/decision/infco20131104107)

LifeScan's final argument is that even if its meters substantially embody the
asserted claims, patent exhaustion is nevertheless inapplicable to the 60% of
its meters that are not sold but instead distributed for free. LifeScan asserts
that it received no "reward" for distributing them (because they were
distributed without charge), and that the district court therefore properly
found that patent exhaustion did not apply. We are therefore asked to decide,
as a matter of first impression, whether patent exhaustion applies to a product
distributed for free. We conclude that, in the case of an authorized and
unconditional transfer of title, the absence of consideration is no barrier to
the application of patent exhaustion principles.

Although the Supreme Court has often discussed exhaustion in terms of a "sale"
and a "purchaser," see, e.g., _Bowman v. Monsanto Co._, 133 S. Ct. 1761, 1766,
185 L. Ed. 2d 931 (2013); *Adams*, 84 U.S. at 456, the Court has never confined
the application of patent exhaustion to that context. The Court explained the
rationale underlying the doctrine of patent exhaustion in _Bloomer v.
McQuewan_, 55 U.S. (14 How.) 539, 14 L. Ed. 532 (1853). See also *Quanta*,
553 U.S. at 625. *McQuewan* involved the effect of a patent term extension on
patent licensees holding licenses to use the patented planing machine during
the original patent term. The Court held that "the purchaser of the . . .
machine for the purpose of using it in the ordinary pursuits of life" was
entitled to continue using the machine during the extended term. The Court
explained that

> when the machine *passes to the hands* of the purchaser, it is no longer
> within the limits of the [patent] monopoly. It passes outside of it, and is
> no longer under the protection of the act of Congress. . . . The implement or
> machine *becomes [the purchaser's] private, individual property*, not
> protected by the laws of the United States, but by the laws of the State in
> which it is situated.

*Id*. at 549-50 (emphases added). In other words, the patentee's transfer of
the right to use the machines "exhaust[ ed]" his rights as to those machines.
See *Univis*, 316 U.S. at 250 (citing *McQuewan*, 55 U.S. (14 How.) at 549-50).

Thus, despite frequent references to "sales" and "purchasers," the Court has
more fundamentally described exhaustion as occurring when the patented product
"passes to the hands" of a transferee and when he "legally acquires a title"
to it. *Millinger*, 68 U.S. (1 Wall.) at 351 ("legally acquires a title");
_Chaffee v. Boston Belting Co._, 63 U.S. (22 How.) 217, 223,
16 L. Ed. 240 (1859) ("passes to the hands," "legally acquires a title");
*McQuewan*, 55 U.S. (14 How.) at 549-50 ("passes to the hands"). Similarly, the
Court has stated that exhaustion can occur by a transfer "from any other person
. . . authorized [by the patentee] to convey it." Millinger, 68 U.S. (1 Wall.)
at 351 (emphasis added); Chaffee, 63 U.S. (22 How.) at 223 (same); see Black's
Law Dictionary 273 (1st ed. 1891) (defining "convey" to mean "[t]o pass or
transmit the title to property from one to another"). So too, in *Univis*, the
Court stated that the patentee's "monopoly remains so long as he *retains the
ownership* of the patented article." 316 U.S. at 250 (emphasis added). Each of
these formulations is broad enough to include a transfer of title that does not
amount to a sale. A "sale" limitation would indeed be inconsistent with the
Supreme Court's decision in *McQuewan*, where the particular machines at issue
had never been sold, but had instead been manufactured by the accused infringer
with the permission of the patentee. See 55 U.S. (14 How.) at 548. Yet that
lack of a "sale" was no barrier to the application of patent exhaustion.
See *id*. at 549-50. Because the machines had been constructed with the
patentee's authorization and were the "private, individual property" of the
accused infringer, they were "no longer under the protection of" the Patent
Act. *Id*. The narrow application of patent exhaustion urged by LifeScan would
be inconsistent with the doctrine's underlying rationale—to permit the owner of
an item who received it in an authorized transfer to use it.

LifeScan relies on language in Supreme Court exhaustion decisions mentioning
the receipt of "consideration" or "reward" by the patentee as supporting
exhaustion. See, e.g., *Univis*, 316 U.S. at 251 ("[T]he patentee has received
his reward for the use of the invention by the sale of the article . . . .");
*Adams*, 84 U.S. (17 Wall.) at 456 ("[W]hen the patentee . . . sells a machine
. . . whose sole value is in its use, he receives the consideration for its use
and he parts with the right to control that use."). But none of the cases cited
by LifeScan involved any suggestion that exhaustion could be avoided by showing
the absence or inadequacy of the patentee's reward in a transfer by gift.

At bottom, a patentee has a choice as to how to secure its reward. A patentee
may "demand[]" a particular price in exchange for an "article and the invention
which it embodies." See *Univis*, 316 U.S. at 251; see also *McQuewan*, 55 U.S.
(14 How.) at 552. Alternately, a patentee may choose to give that article away
for free in the hope of obtaining a future benefit, as LifeScan did here. But a
patentee cannot evade patent exhaustion principles by choosing to give the
article away rather than charging a particular price for it. Where a patentee
unconditionally parts with ownership of an article, it cannot later complain
that the approach that it chose results in an inadequate reward and that
therefore ordinary principles of patent exhaustion should not apply.

\[...\]

In summary, we hold that patent exhaustion principles apply equally to all
authorized transfers of title in property, regardless of whether the particular
transfer at issue constituted a gift or a sale. We further conclude that
LifeScan's OneTouch Ultra meters substantially embody the methods claimed in
the '105 patent and that their distribution therefore exhausts LifeScan's
patent rights. We therefore reverse the district court's grant of a preliminary
injunction and remand for further proceedings consistent with this opinion.

#### Cascades Computer Innovation, LLC v. Samsung Electronics Co.

--------------------------------------------------------------------------------

Excerpt from _Cascades Computer Innovation, LLC v. Samsung Elecs. Co._, 70 F. Supp. 3d 863 (N.D.Ill, 2014)[^CascadesHeadnote]

[^CascadesHeadnote]: _Cascades Computer Innovation, LLC v. Samsung Elecs. Co._, 70 F. Supp. 3d 863 (N.D.Ill, 2014), _available at_ [https://www.casemine.com/judgement/us/5914fa77add7b049349a8497](https://www.casemine.com/judgement/us/5914fa77add7b049349a8497)

Under the doctrine of patent exhaustion, the initial authorized sale of a
patented item terminates the patent holder's rights to that item, and the
patent holder may not sue a downstream user of the item for infringement.
Patent exhaustion also applies to method patents. If the holder of a method
patent authorizes another to practice the patented method, the patent holder
cannot successfully sue for infringement those who acquire from the
authorized user a product that substantially embodies the patented method.

In these cases, Cascades Computer Innovation LLC has sued Samsung
Electronics Co. Ltd. and HTC Corporation for infringement of U.S. Patent
7,065,750 (the '750 patent). Cascades contends that defendants manufacture
and sell products that practice the method claimed in the patent. Samsung
and HTC have moved for summary judgment. They contend that Cascades
authorized Google to practice the patented method in its Android operating
system and that their claimed infringement arises from their use of that
same operating system, which they acquired from Google. Thus, Samsung and
HTC contend, the doctrine of patent exhaustion bars Cascades's claims
against them.

**Background**

Because the defendants have moved for summary judgment, the Court
"constru[es] all facts and reasonable inferences in the light most
favorable to the nonmoving party," in this case, Cascades.
_Ellis v. DHL Exp. Inc._, 33 F.3d 522, 525 (7th Cir.2011).

The '750 patent is entitled "Method and Apparatus for Preserving Precise
Exceptions in Binary Translated Code." Pl.'s Third Am. Compl. ¶ 11. In
general terms, it describes a method for efficiently executing on one system
architecture computer programming code that is intended for a different
architecture. Until 2014, Cascades was an exclusive licensee under the '750
patent, with an exclusive right to sue for the patent's past, present, and
future infringement.

In 2011, Cascades filed patent infringement suits against certain parties,
including Samsung and HTC. Cascades contends that Samsung and HTC infringe
the '750 patent by manufacturing and selling smartphones and tablets that
use the Dalvik JIT Compiler, which is part of the Android operating system
distributed by Google. According to Cascades, "[t]he claimed method is
performed when a user of the cellular phones operates the device for their
intended purpose using the Android operating system, e.g., allowing the
Dalvik Virtual Machine to optimize the byte code for each application."
*Id*. ¶ 14.

On January 29, 2014, Cascades entered into a settlement and license
agreement with Google, the parent of Motorola Mobility LLC, previously a
defendant in one of Cascades's suits. In exchange for a one-time fee,
Cascades granted Google:

> a worldwide, non-exclusive, fully paid up and perpetual and irrevocable
> license under Cascades Patents to practice and undertake any of and all of
> the rights granted a patent owner under 35 U.S.C. 101, et seq., and under
> their counterparts, under the laws of foreign jurisdictions including, but
> not limited to, the right to make, have made, use, sell, offer to sell,
> export, import, and otherwise practice and/or have practiced for Google or
> a Google Affiliate, any and all claims of the Cascades Patents *in any
> Google Product.*

Defs.' Ex. 1 at 2 (emphasis added). The license agreement provides that the
term "Google Products" includes "products of Google, Motorola and/or Google
Affiliates, including all Motorola and Nexus devices, but ... excludes
mobile devices manufactured by third parties and running the Android OS
except any Nexus-branded devices." *Id*.

As indicated earlier, Cascades's claims of infringement focus on the use
of a feature of the Android operating system called the Dalvik JIT Compiler.
Cascades has identified no other feature of the defendants' devices or the
operating system they use that infringes the '750 patent. The quoted term of
the license agreement between Cascades and Google entitles Google to use,
sell, or practice the patented method in any "Google Product." It is
undisputed that the Android operating system is a Google product; no
reasonable fact finder could find otherwise. The same is true of the Dalvik
JIT Compiler. Thus the license agreement authorized Google, from that day
forward, to convey the Android operating system—including the Dalvik JIT
Compiler—without fear of a claim of infringement by Cascades. The
agreement's definition of "Google products," however, purported to limit
this to certain types of devices, *not* including those made by Samsung and
HTC.

The settlement and license agreement between Cascades and Google also
included a release and a covenant not to sue. The release provides that
Cascades

> releases and discharges Google, Motorola, Google Affiliates, Google
> Partners ... from any and all claims, demands, debts, liabilities, actions,
> causes of actions or suits of whatever kind of nature, asserted or not
> asserted, known or unknown, arising out of the claims or matters that have
> been or could have been asserted by Cascades in the Actions relating to
> the same facts and circumstances therein, provided that such release and
> discharge shall not extend to any other defendant in the Actions.

Defs.' Ex. 1 at 4. The covenant not to sue states that Cascades covenants
not to sue Google, Motorola, Google Affiliates and/or Google Partners for
any infringement or any other violation of the Cascades Patents based upon
any licensed activity, permitted pursuant to this Section, related to any
Google Product; provided this covenant does not extend to any other
defendant in the Patent Suit. *Id*. at 3.

Google provides the Android open source code to all sorts of device
manufacturers, including Samsung and HTC. Samsung and HTC make and sell
devices that use the Android operating system. As indicated, that operating
system embodies the allegedly infringing Dalvik JIT Compiler.

Samsung and HTC contend that by virtue of the license agreement between
Cascades and Google, the doctrine of patent exhaustion bars Cascades from
pursuing its patent infringement claims against them. They contend that
despite the license agreement's limitations regarding its scope, Cascades's
grant to Google of a license to convey the Android operating system to
others enables those who so acquire the operating system to use it as they
wish, without risk of liability for infringement of the '750 patent. Samsung
and HTC contend that Cascades's agreement with Google—specifically, the
release and/or the covenant not to sue—also bars Cascades from suing them
for past infringement.

**Discussion**

Summary judgment is appropriate "if the movant shows that there is no
genuine dispute as to any material fact and the movant is entitled to
judgment as a matter of law." Fed. R. Civ. P. 56(a). "Patent exhaustion is
an affirmative defense to a claim of patent infringement ... and like other
issues in which there are no disputed factual questions, may be properly
decided on summary judgment." _Keurig, Inc. v. Sturm, Foods, Inc._,
732 F.3d 1370, 1373 (Fed.Cir.2013).

As the Court has indicated, the doctrine of patent exhaustion "provides that
the initial authorized sale of a patented item terminates all patent rights
to that item." _Quanta Computer Inc. v. LG Elecs., Inc._, 553 U.S. 617, 625,
128 S.Ct. 2109, 170 L.Ed.2d 996 (2008). The rationale behind this doctrine
is that the sale of a patented device "exhausts the patentee's right to
control the purchaser's use of that item ... because the patentee has
bargained for and received full value for the goods." *Keurig*, 732 F.3d at
1373. In short, the doctrine of patent exhaustion prevents a patent holder
from benefitting multiple times from a single conveyance by claiming that
downstream users infringe the patent when they use the item they acquired.

Application of the doctrine of patent exhaustion does not depend on the
existence of a sale for consideration. In _LifeScan Scotland, Ltd. v. Shasta
Technologies, LLC_, 734 F.3d 1361, 1377 (Fed.Cir.2013), the Federal Circuit
concluded that patent exhaustion applied even though plaintiff had given
away the items at issue rather than sold them. The court noted that "in the
case of an authorized and unconditional transfer of title, the absence of
consideration is no barrier to the application of patent exhaustion
principles." *Id*. at 1374. Thus the fact that Google gives away the Android
operating system is no barrier to application of the doctrine of patent
exhaustion.

Patent exhaustion applies to patented methods just as it applies to patented
devices. *Quanta*, 553 U.S. at 621, 128 S.Ct. 2109; _United States v. Univis
Lens Co._, 316 U.S. 241, 250–51, 62 S.Ct. 1088, 86 L.Ed. 1408 (1942). A
method claim is exhausted by an authorized sale of an item—even an
unpatented item—"that substantially embodies the [patented] method if the
item (1) has no reasonable noninfringing use and (2) includes all inventive
aspects of the claimed method." *Keurig*, 732 F.3d at 1373. And "alternative
uses are relevant to the exhaustion inquiry under *Quanta* only if they are
both reasonable and intended by the patentee or its authorized licensee."
*LifeScan Scotland*, 734 F.3d at 1369 (internal quotation marks omitted).

**A. Effect of the limitations in the license agreement**

As the Court has indicated, Samsung and HTC argue that via the settlement
and license agreement, Cascades gave Google the right to convey the Android
operating system (including the Dalvik JIT Compiler) to others, leaving
Google free to provide the technology to whomever it chose, including
Cascades and HTC. Cascades and HTC argue that they were then free to use the
technology in whichever way they chose, free from any claim of infringement
of Cascades's patent.

In response, Cascades relies on the principle that "[e]xhaustion is
triggered only by a sale authorized by the patent holder." *Quanta*,
553 U.S. at 636, 128 S.Ct. 2109 (citing *Univis*, 316 U.S. at 249, 62 S.Ct.
1088). It argues that the plain language of the license agreement clearly
"excludes Android as it is used in Defendants' devices."
Pl.'s Resp. Br. at 5. Cascades argues, in other words, that the conveyance
of the Android operating system by Google to Samsung and HTC was not an
"authorized" sale that exhausted Cascades's patent rights in the operating
system. Specifically, Cascades says, "[e]ven accepting for the sake of
argument that Android is a product made by Google, the definition of
'Products' in the Motorola Agreement was modified by the definition of
'Google Product'...." *Id*. at 6. Samsung and HTC maintain that the
agreement's exclusion of their products is ineffective, because "Cascades'
license to Google creates exhaustion with respect to Defendants' downstream
products that incorporate Google's licensed products."
Defs.' Opening Br. at 10.

\[...\]

By way of its license agreement with Cascades, Google was authorized to
convey to others, including Samsung and HTC, products—including the Android
operating system—that practiced Cascades's patents. As a result, Cascades
could no longer assert patent rights with respect to those products. As was
the case in *Quanta*, use of the restriction in the Cascades/Google license
agreement to limit how those who thereafter acquired the Android operating
system from Google could use it would in effect allow Cascades to circumvent
the patent exhaustion doctrine and reap multiple gains from a single sale.
See *Keurig*, 732 F.3d at 1374. The license authorized Google to convey the
Android operating system to others, and thus the conveyance of the operating
system to Samsung and HTC was an authorized sale. The agreement's attempt to
carve out downstream users' own mobile devices is ineffective under *Quanta*.

For these reasons, the Court concludes that Samsung and HTC have established
that there was an authorized sale of the Android operating system (and the
Dalvik JIT Compiler) to them; no reasonable fact-finder could determine
otherwise. The Court therefore proceeds to consider whether Samsung and HTC
have met the remaining requirements for patent exhaustion.

**B. Substantial embodiment and reasonable noninfringing uses**

As the Court has indicated, to establish their patent exhaustion defense,
Samsung and HTC must show that the Android operating system as it was
conveyed to them "substantially embodies" Cascades's patented method in that
the operating system "(1) has no reasonable noninfringing use and (2)
includes all inventive aspects of the claimed method."
*Keurig*, 732 F.3d at 1373.

Cascades maintains that the Android operating system does not substantially
embody the '750 patent because it has a reasonable noninfringing use. It
argues that "[t]he Kit Kat version of Android [which Samsung purportedly
uses in its devices] does not require the use of the JIT compiler and
instead allows a user to switch runtimes from the JIT default to ART
(Android Run Time)." Pl.'s Resp. Br. at 6. Cascades also says that one can
"remove the claimed inventions from the Accused Devices" by" redesign[ing]
and modify[ing] the JIT Compiler to use a Kelly-style method of handling
precision exceptions." *Id*. at 10. Cascades says these should be considered
intended uses, because "the Accused Devices ... would likely still function
with unchanged performance...." *Id*. (internal quotation marks omitted).

The question, however, is whether there is a reasonable alternative
noninfringing use of the Dalvik JIT Compiler—itself a "Google product" under
the Cascades–Google agreement—not whether defendants could avoid liability
by enabling its non-use. As defendants argue, this argument is foreclosed by
*Quanta*, in which the Court noted that evidence that patented features of
certain products could be disabled did not show a reasonable noninfringing
use of those features, because "[t]he disabled features would have no real
*use*." *Quanta*, 553 U.S. at 632 n.6, 128 S.Ct. 2109.

That aside, Cascades has offered no admissible evidence from which a
reasonable finding could be made that a user's ability to enable Android Run
Time rather than the Dalvik JIT Compiler constitutes a *reasonable*
noninfringing use. One of Cascades's experts reports that "the official
Android website warns its KitKat users about the risks of running ART:
*Important: Dalvik must remain the default runtime or your risk breaking
your Android implementations and third-party applications.*"
Defs.' Ex. 21 ¶ 141. The same expert reports that "Android suggests that
Dalvik remains as the default runtime against the risk of malfunctioning
regarding Android implementations." Id. ¶ 52 (internal quotation marks
omitted). It is difficult to see how purported noninfringing uses that run
this sort of a risk could be considered reasonable.

For these reasons, the Court concludes that defendants have established that
the Cascades–Google license brings the doctrine of patent exhaustion into
play; no reasonable fact finder could determine otherwise. Defendants are
therefore entitled to summary judgment on infringement from the date of the
Cascades–Google agreement forward.

#### Intel Corp. v. ULSI System Technology, Inc.

--------------------------------------------------------------------------------

Excerpt from _Intel Corp. v. ULSI System Technology, Inc._, 995 F. 2d 1566  (Fed. Cir. 1993)[^IntelHeadnote].

[^IntelHeadnote]: _Intel Corp. v. ULSI System Technology, Inc._, 995 F. 2d 1566  (Fed. Cir. 1993), _available at_ [https://scholar.google.com/scholar_case?case=2822821090682871319](https://scholar.google.com/scholar_case?case=2822821090682871319)

**BACKGROUND**

Intel is the assignee of U.S. Patent Re. 33,629 to John F. Palmer, et al.,
entitled "Numerical Data Processor."[^IntelFNOmitted] The claims of the '629
patent are directed to the design and operation of a floating-point arithmetic
processor capable of mixed precision calculations, mixed mode arithmetic
calculations, and rounding operations. Intel has developed a line of math
coprocessors covered by the patent, including the Intel 8087, 80287, and 80387
coprocessors.

On January 10, 1983, Intel and the Hewlett-Packard Company (HP) entered into a
cross-licensing agreement to "increase their freedom of design by obtaining a
license under present and future patents and patent applications owned or
controlled by the other." Under that agreement, Intel and HP each granted to
the other an "irrevocable, retroactive, nonexclusive, world-wide, royalty-free
license" under all patents and patent applications "having an effective filing
date prior to January 1, 2000, said license to be effective until the
expiration of said patents."

ULSI sells a math coprocessor known as the US83C87 ('C87 coprocessor) which is
compatible with the Intel 80386 microprocessor and competes commercially with
the Intel 80387 coprocessor. Since September 22, 1989, ULSI has purchased the
'C87 coprocessors from HP under an agreement entered into on August 2, 1988, in
which HP agreed to manufacture the coprocessors for ULSI. As is apparently
common in such "foundry" arrangements in the semiconductor industry, ULSI
supplied HP with proprietary design specifications and HP then manufactured and
shipped completed coprocessor chips to ULSI, which resold them as ULSI products.

Intel first became aware of ULSI's 'C87 coprocessor sales on February 4, 1991.
On July 29, 1991, Intel brought an action in the U.S. District Court for the
District of Oregon alleging infringement of the '629 patent by ULSI's "making
and selling, and inducing others to make, sell and use, the 'US83C87'
[coprocessor]."

\[...\]

**DISCUSSION**

\[...\]

In opposition to the motion, ULSI maintained that HP was permitted under the
licensing agreement to act as a foundry for ULSI and that the sale of the
coprocessors by HP to ULSI was a "first sale" that extinguished Intel's patent
rights with respect to those products. The district court, however, rejected
ULSI's argument because it determined that the licensing agreement did not
grant HP the "power to sublicense" the '629 patent. On appeal, ULSI claims that
the district court erred in concluding that the "patent exhaustion" or "first
sale" doctrine did not shield ULSI from Intel's claim of infringement.

The law is well settled that an authorized sale of a patented product places
that product beyond the reach of the patent. See _Bloomer v. Millinger_, 68
U.S. (1 Wall.) 340, 350-51, 17 L.Ed. 581 (1864). The patent owner's rights with
respect to the product end with its sale, _United States v. Univis Lens Co._,
316 U.S. 241, 252, 62 S.Ct. 1088, 1094, 86 L.Ed. 1408, 53 USPQ 404, 408 (1942),
and a purchaser of such a product may use or resell the product free of the
patent, *id*. at 250, 62 S.Ct. at 1093, 53 USPQ at 408. This longstanding
principle applies similarly to a sale of a patented product manufactured by a
licensee acting within the scope of its license. See _Unidisco, Inc. v.
Schattner_, 824 F.2d 965, 968, 3 USPQ2d 1439, 1441 (Fed.Cir.1987), cert.
denied, 484 U.S. 1042, 108 S.Ct. 774, 98 L.Ed.2d 860 (1988).

In the instant case, the issue as to whether ULSI is free from infringement
liability turns on whether there was a sale of 'C87 coprocessors by HP to ULSI.
Intel argues that the "patent exhaustion" doctrine does not apply because HP
never sold a product to ULSI. Although Intel claims, as it must, that the 'C87
coprocessor infringes the '629 patent, it maintains that what was actually sold
by HP under the foundry agreement was its fabrication services with an
ancillary sale of wafers and chemicals. Intel asserts that HP could not have
sold a product covered by the '629 patent because HP never had or retained any
ownership rights in the 'C87 coprocessors. Thus, according to Intel, no sale
ever took place that could support ULSI's "first sale" defense. That argument
is incorrect.

Interpretation of a contract is a question of law which we review *de novo*.
*See* _Interstate Gen. Gov't Contractors, Inc. v. Stone_, 980 F.2d 1433, 1434
(Fed.Cir.1992). After reviewing the HP-ULSI contract, we cannot accept Intel's
characterization of that agreement as one in which HP merely provided
fabrication services to ULSI. That agreement, entitled "Terms and Conditions of
Sale," is replete with references to the sale of semiconductor wafers (i.e.,
chips) that incorporate the 'C87 coprocessor design. For example, the section
of the agreement headed "Section 2: Production Fabrication" provided that HP
"will sell CMOS34 wafers to" ULSI. That section recites prices for the chips
and includes a delivery schedule for shipments of the chips to ULSI. Although
the agreement also includes a section delineating the "engineering services" to
be provided by HP, the agreement clearly involved the sale of chips, not merely
the sale of fabrication services.

Nor, as Intel contends, must the licensed seller of a patented product own
intellectual property rights to the product in order for there to be a sale.
Intel makes much of the fact that the 'C87 chip was based on a design provided
by ULSI. Intel confuses the issue of design origin with the issue of sale. Who
designed the chip and whether it embodies inventions other than Intel's have no
bearing on the controlling issue whether the 'C87 coprocessors were sold by HP
to ULSI and thus extinguished Intel's patent rights relating to those products.

That ULSI, rather than HP, might have owned any existing intellectual property
rights to the chips was a matter between ULSI and HP, and did not concern
Intel. Intel does not dispute that HP was authorized under the broad terms of
the licensing agreement to sell the chips at issue. To the extent that Intel
had a patent covering the chips, HP's conceded right to sell the chips deprives
Intel of any claim of infringement, as long as HP sold the chips. If it had not
granted that license or if the license had been limited in some relevant way,
that would be a different case from the one before us. Intel might thereby have
retained its right to proceed against those who entered into foundry agreements
such as the present one. While Intel may not in retrospect be pleased with the
deal that it made permitting HP to make unrestricted sales, it nevertheless
granted HP that right in 1983, presumably for consideration it believed to be
of value at that time. It cannot now renege on that grant to avoid its
consequences.

\[...\]

Relatedly, we do not agree with the district court's conclusion that the sale
of chips by HP to ULSI was not a "first sale" because HP was not authorized to
sublicense ULSI to design products covered by the '629 patent. That HP did not
have the authority to sublicense the '629 patent to ULSI is irrelevant. The
agreement between HP and ULSI was not a sublicense, but a contract for the
manufacture and sale of chips. Thus, HP did not grant a sublicense; it sold a
product, albeit one designed by its purchaser. ULSI is immune from
infringement, not because it was a sublicensee, which it was not, but because
HP was a licensed and therefore legitimate source of the chips. Moreover, ULSI
was not required to be sublicensed in order to provide its chip design to HP.

___

#### Discussion

1. The *Quanta* court notes that "methods ... may be 'embodied' in a product,
  the sale of which exhausts patent rights." To what extent does software
  "embody" possible patent claims, including claims for systems that may
  involve the use of many different components?

2. The *Lexmark* court draws a distinction between agreements to license
  alone as opposed to distributions of goods: "Because the patentee is
  exchanging rights, not goods, it is free to relinquish only a portion of
  its bundle of patent protections." (*Lexmark* at 1539.) Does the common
  practice of including the license grant (the "rights") *with* the code
  itself (the "goods") imply that every distribution of the source code implicates exhaustion?

3. As discussed above, open source has *self-executing* licenses: Anybody
  who receives a copy of the code automatically is licensed for the use of
  that code by the applicable upstream licensor. In the context of patent
  exhaustion, is there a logical distinction between licenses received
  through a direct download from a licensor, and those that are received via
  a third party? Does the rule from *General Talking Pictures* ("if a
  patentee has not given authority for a licensee to make a sale, that sale
  cannot exhaust the patentee's rights") mean that someone receiving a
  non-compliant distribution of source code is in a different situation
  than someone receiving a compliant distribution?

4. On occasion, companies have distributed source code subject to an
  open source license accompanied by an explicit disclaimer of a patent
  license. For example *see* the PARC CCNS3Sim License, below.[^PARC]
  Even assuming that the explicit disclaimer of patent rights prevents the
  automatic grant of a patent license (explicit or implict), does the
  distribution of the source code exhaust any applicable patents regardless of
  the disclaimer?
  ___
  > LICENSE
  >
  > Copyright (c) 2016, Xerox Corporation (Xerox) and
  > Palo Alto Research Center, Inc (PARC)
  > All rights reserved.
  >
  > Redistribution and use in source and binary forms, with or without
  > modification, are permitted provided that the following conditions
  > are met:
  >
  > * Redistributions of source code must retain the above copyright
  >   notice, this list of conditions and the following disclaimer.
  > * Redistributions in binary form must reproduce the above copyright
  >   notice, this list of conditions and the following disclaimer in the
  >   documentation and/or other materials provided with the distribution.
  >
  > THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS
  > IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO
  > THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
  > PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL XEROX OR PARC BE LIABLE FOR ANY
  > DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
  > DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS
  > OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
  > HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT,
  > STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN
  > ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
  > POSSIBILITY OF SUCH DAMAGE.
  >
  >
  > \#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#
  >
  > PATENT NOTICE
  > 
  > This software is distributed under the BSD 2-clause License (see LICENSE
  > file).  This BSD License does not make any patent claims and as such,
  > does not act as a patent grant.  The purpose of this section is for each
  > contributor to define their intentions with respect to intellectual
  > property.
  >
  > Each contributor to this source code is encouraged to state their patent
  > claims and licensing mechanisms for any contributions made. At the end of
  > this section contributors may each make their own statements. 
  > Contributor's claims and grants only apply to the pieces (source code,
  > programs, text, media, etc) that they have contributed directly to this
  > software.
  >
  > There is no guarantee that this section is complete, up to date or
  > accurate. It is up to the contributors to maintain their section in
  > this file up to date and up to the user of the software to verify any
  > claims herein.
  >
  > Do not remove this header notification.  The contents of this section
  > must be present in all distributions of the software.  You may only
  > modify your own intellectual property statements.  Please provide
  > contact information.
  >
  > - Palo Alto Research Center, Inc
  >   This software distribution does not grant any rights to patents
  >   owned by Palo Alto Research Center, Inc (PARC). Rights to these
  >   patents are available via various mechanisms. As of January 2016 PARC
  >   has committed to FRAND licensing any intellectual property used by its
  >   contributions to this software. You may contact PARC at cipo@parc.com
  >   for more information or visit http://www.ccnx.org
 ___
 
5. The *Cascades* court identified the code that should be evaluated as having
  a significant noninfringing use as being the exact code implementing the
  claimed function (e.g. the JIT in Dalvik), not the project as a whole
  (e.g. "Android"). Given this analysis, how likely is it that any code that
  implicates a patent would be found to have a significant noninfringing use?

6. The *Intel* court states that "Who designed the chip and whether it
  embodies inventions other than Intel's have no bearing on the controlling
  issue whether the 'C87 coprocessors were sold by HP to ULSI and thus
  extinguished Intel's patent rights relating to those products." Under this
  analysis, any authorized sale or distribution of a product will exhaust
  implicated patents, even if the patent owner is not the source of the
  product. How might this analysis affect incidental distribution of open
  source code from third parties by a patent owner?


[^IntelFNOmitted]: Some footnotes and cites to the record have been omitted.

[^PARC]: CCNx Module for NS3 License text, *available at* [https://github.com/PARC/ccns3Sim](https://github.com/PARC/ccns3Sim).


### Industry Agreements

When considering patent exhaustion, it isn't just the action of the patent
holder that needs to be considered - it is also the acts of any licensees.
As the *Lexmark* court noted: "a license is not about passing title to a
product, it is about changing the contours of the patentee's monopoly:
The patentee agrees not to exclude a licensee from making or selling
the patented invention, *expanding the club of authorized producers and
sellers.* (*Lexmark* at 1534, emphasis added)

While there aren't any industry agreements that affect *all* open source,
a large number of open source packages are covered by the patent
license agreement provided by the [Open Invention Network](https://www.openinventionnetwork.com/) ("OIN").

The Open Invention Network is a shared defensive patent pool with the mission
to protect Linux. Launched in 2005, OIN includes (as of October 2018) 2747
participating licensees [^OINLicensees]. Based upon the number of patents
publicly owned by participants in OIN, the patent pool includes more than
100,000 active patents cross-licensed on a royalty-free basis, making it
the largest patent pool in any industry.

The patent pool maintained by OIN covers what is described as the "Linux
System." The Linux System is substantially broader than just the underlying
operating system. It also includes a number of standard packages that are
included with most Linux distributions

[^OINLicensees]: The current list of OIN licensees is maintained at [https://www.openinventionnetwork.com/community-of-licensees/](https://www.openinventionnetwork.com/community-of-licensees/).

The OIN Linux System is defined as follows:[^OINLinuxSystem]

  > "Linux Environment Component" shall mean any of the software packages
  > whose released source code shall be identified on the OIN website,
  > including bug fixes and error corrections thereto, or a Predecessor
  > Release or Successor Release of any of such packages.
  >
  > "Linux System" shall mean a Linux Environment Component or any combination
  > of such components to the extent each such component is (i) generally
  > available under an Open Source License or in the public domain (and the
  > source code for such component is generally available) and (ii) Distributed
  > with, or for use with, the Linux Kernel (or is the Linux Kernel).


Also see the the tables listing applicable standards[^OINTable0] and
current list of packages.[^OINTable8]

[^OINLinuxSystem]: The official definition of the Linux System is defined by the definition at [https://www.openinventionnetwork.com/joining-oin/linux-system/](https://www.openinventionnetwork.com/joining-oin/linux-system/) and

[^OINTable0]: *See* Table 0 at [https://www.openinventionnetwork.com/joining-oin/linux-system/linux-system-table/?cat_id=2&type=table](https://www.openinventionnetwork.com/joining-oin/linux-system/linux-system-table/?cat_id=2&type=table))

[^OINTable8]: *See* the most recent list of packages in Table 8 at [https://www.openinventionnetwork.com/joining-oin/linux-system/linux-system-table/?cat_id=14&type=table](https://www.openinventionnetwork.com/joining-oin/linux-system/linux-system-table/?cat_id=14&type=table)

One of the unique aspects of the OIN patent pool is that it grows in scope
over time. Periodically the trustees of the Open Invention Network will
propose a new set of packages to be added to the Linux System. If individual
companies object to the inclusion of the new components, they can exercise
a "Limitation Election" to stop participating in the pool before the new
components are added - but all previously licensed components remain licensed.

--------------------------------------------------------------------------------
#### The Open Invention Network Agreement
Excerpt from the Open Invention Network License Agreement:[^OINLicense]

[^OINLicense]: _OIN License Agreement_, *available at* [https://www.openinventionnetwork.com/joining-oin/oin-license-agreement/](https://www.openinventionnetwork.com/joining-oin/oin-license-agreement/).

**SECTION 1. Licenses.**

1\.1    Subject to Section 1.2(b), OIN, grants to You and Your Subsidiaries
a royalty-free, worldwide, nonexclusive, non-transferable license under OIN
Patents to make, have made, use, import, and Distribute any products or
services. In addition to the foregoing and without limitation thereof, with
respect only to the Linux System, the license granted herein includes the
right to engage in activities that in the absence of this Agreement would
constitute inducement to infringe or contributory infringement (or
infringement under any other analogous legal doctrine in the applicable
jurisdiction).

1\.2    Subject to Section 2.2 and in consideration for the license granted
in Section 1.1, You, on behalf of yourself and your Affiliates, (a) grant
to each Licensee and its Subsidiaries that are Subsidiaries as of the
Eligibility Date a royalty-free, worldwide, nonexclusive, non-transferable
license under Your Patents for making, having made, using, importing, and
Distributing any Linux System; and (b) represent and warrant that (i) You
have the full right and power to grant the foregoing licenses and the
release in Section 1.4 and that Your Affiliates are and will be bound by
the obligations of this Agreement; and (ii) neither You nor any of Your
Affiliates has a Claim pending against any Person for making, having made,
using, importing, and Distributing any Linux System. Notwithstanding
anything in another Company Licensing Agreement to the contrary, You and
your current and future Subsidiaries do not and shall not receive, and
hereby disclaim and waive, any license from a Licensee and its current and
future Affiliates pursuant to a Company Licensing Agreement for
implementations of Linux Environment Components as specified in such
Company Licensing Agreement to the extent that You and your current and
future Affiliates are excepting any such implementations of Linux
Environment Component from your license to a Licensee and its current and
future Subsidiaries. The previous sentence is for the express benefit of
the Members of OIN, OIN, and OIN's Licensees.

1\.3     Subject to Section 1.2(b), OIN irrevocably releases You and Your
Subsidiaries from claims of infringement of the OIN Patents to the extent
such claims are based on acts prior to the Agreement Date that, had they
been performed after the Agreement Date, would have been licensed under
this Agreement.

1\.4     You, on behalf of Yourself and Your Affiliates, irrevocably
releases and shall release each Licensee and its Subsidiaries that are
Subsidiaries on the Amendment Date and their respective Channel Entities
and Customers that are Channel Entities and Customers, respectively, on or
before the Amendment Date from any and all claims of infringement of Your
Patents to the extent such claims are based on acts prior to the Amendment
Date that, had they been performed after the Amendment Date, would have
been licensed under this Agreement. As used herein, a Licensee's "Amendment
Date" shall mean the later of the date an amendment becomes effective under
Section 2.1 and the date such Licensee becomes a Licensee.

\[...\]

**Definitions:**

"Affiliate" shall mean, with respect to any specified Person, any other
Person that now or in the future (i) is a Subsidiary of the specified
Person, (ii) is a parent of the specified Person or (iii) is a Subsidiary
of a parent of the specified Person. In each of the foregoing cases, such
other Person shall be deemed to be an Affiliate only during the time such
relationship as a Subsidiary or parent exists.

#### Discussion

1. How does the OIN License Agreement change in scope over time? What
  is the effect of the wording around a person "that now or in the future"
  is an Affiliate?

2. How significant is the OIN patent pool? Many of the technologies used
  in the Linux System are more than twenty years old, and so are out of
  scope for any enforceable patents. On the other hand, many new
  technologies are being developed in open source *first,* and only later
  commercialized. Which effect predominates?

3. The OIN License Agreement contains an explicit patent license, thus
  "expanding the club" of authorized users of the code. But as discussed
  above, open source licenses may imply or contain a broad but non-specific
  patent grant. Can patent owner rights be exhausted through the actions of
  implicit licensees? What about through the actions of those who have
  received a broad right to "use... without restriction"?
 

<!-- Footnotes themselves at the bottom. -->

## Notes

