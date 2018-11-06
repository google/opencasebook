# Patents in Open Source

[TOC]

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

This chapter presents materials related to five separate but related issues:

1. **Explicit licenses:** Express language in open source licenses granting 
  patent licenses;
2. **Implicit Licenses:** The existence and scope of implied patent licenses 
  in open source licenses;
3. **Express but Non-specific Licenses:** Express grants in open source 
  licenses that do not include the term "patent;" 
4. **Patent Exhaustion:** The doctrine of patent exhaustion and its 
  applicability to the distribution of open source software; and
5. **License Termination:** Circumstances that can lead to an ineffective
  or terminated patent grant. 


[^PatentabilityDiscussion]: The exact scope of what is patentable within a 
  software program is subject to debate, and has changed over time. This 
  discussion, however, assumes that there is some software, released under 
  open source licenses, that is both patent-eligible and implicates one or 
  more valid patent claims.

[^35USC271abc]: _See_ the text of 35 U.S.C. 271 and discussion _infra_, 
  laying out the scope of the unique rights granted to a patent owner.

[^OpenSourceLicensesWithGrants]: _See_ the examples of explicit patent grants
  and discussion _infra_.

[^OpenSourceDefinition1and7]: _See The Open Source Definition - Annotated_, elements one and seven: 
  1\. _Free Redistribution_: The license shall not restrict any party from selling or giving away the software as a component of an aggregate software distribution containing programs from several different sources. The license shall not require a royalty or other fee for such sale.
  7\. _Distribution of License_: The rights attached to the program must apply to all to whom the program is redistributed without the need for execution of an additional license by those parties. Open Source Initiative, [https://opensource.org/osd-annotated](https://opensource.org/osd-annotated) (Open Source Definition-Annotated) (CC-BY 4.0)

## Explicit Patent Licensing

### Selections from Open Source Licenses

About half of all open source licenses include express patent grants, but 
the scope of those licenses may vary depending upon the language of the 
grant. Below are a number of widely-used or noteworthy open source licenses 
that expressly include a patent grant.

--------------------------------------------------------------------------------
#### Academic Free License 3.0
Excerpt from the Academic Free License, Version 3.0[^AFL]

> **2) Grant of Patent License.** Licensor grants You a worldwide, 
> royalty-free, non-exclusive, sublicensable license, under patent claims 
> owned or controlled by the Licensor that are embodied in the Original Work
> as furnished by the Licensor, for the duration of the patents, to make, 
> use, sell, offer for sale, have made, and import the Original Work and 
> Derivative Works.

[^AFL]: _Academic Free License, Version 3.0_, Lawrence Rosen, 2002, *available at* [https://opensource.org/licenses/AFL-3.0] (https://opensource.org/licenses/AFL-3.0)  (2002). *See also* Rosen, "OSL 3.0: A Better License for Open Source Software," (2007), *available at* [http://rosenlaw.com/OSL3.0-explained.htm](http://rosenlaw.com/OSL3.0-explained.htm) 

--------------------------------------------------------------------------------
#### Apache 2.0
Excerpt from the Apache License, Version 2.0[^Apache2]

> **6\. Grant of Patent License.**
> Subject to the terms and conditions of this License, each Contributor hereby 
> grants to You a perpetual, worldwide, non-exclusive, no-charge, royalty-free, 
> irrevocable (except as stated in this section) patent license to make, have 
> made, use, offer to sell, sell, import, and otherwise transfer the Work, 
> where such license applies only to those patent claims licensable by such 
> Contributor that are necessarily infringed by their Contribution(s) alone 
> or by combination of their Contribution(s) with the Work to which such 
> Contribution(s) was submitted.... 

[^Apache2]: _Apache License, Version 2.0_, Apache Foundation, *available at* [https://www.apache.org/licenses/LICENSE-2.0](https://www.apache.org/licenses/LICENSE-2.0) (Jan. 2004).

--------------------------------------------------------------------------------
#### Eclipse Public License version 2.0
Excerpt from the Eclipse Public License, Version 2[^EPL2]

> **2\. GRANT OF RIGHTS**
> \[...\] b) Subject to the terms of this Agreement, each Contributor hereby 
> grants Recipient a non-exclusive, worldwide, royalty-free patent license 
> under Licensed Patents to make, use, sell, offer to sell, import and 
> otherwise transfer the Contribution of such Contributor, if any, in Source 
> Code or other form. This patent license shall apply to the combination of 
> the Contribution and the Program if, at the time the Contribution is added 
> by the Contributor, such addition of the Contribution causes such 
> combination to be covered by the Licensed Patents. The patent license shall 
> not apply to any other combinations which include the Contribution. No 
> hardware per se is licensed hereunder. 

[^EPL2]: _Eclipse Public License, Version 2.0_, *available at*  [https://opensource.org/licenses/EPL-2.0] (https://opensource.org/licenses/EPL-2.0) (2017). 


#### GNU General Public License 2.0
--------------------------------------------------------------------------------
Excerpt from the GNU General Public License License, Version 2.0[^GPL2]

> **Preamble** 
> 
> \[...\] Finally, any free program is threatened constantly by software 
> patents. We wish to avoid the danger that redistributors of a free program 
> will individually obtain patent licenses, in effect making the program 
> proprietary. To prevent this, we have made it clear that any patent must 
> be licensed for everyone's free use or not licensed at all. 

\[...\]

> 7\. If, as a consequence of a court judgment or allegation of patent 
> infringement or for any other reason (not limited to patent issues), 
> conditions are imposed on you (whether by court order, agreement or 
> otherwise) that contradict the conditions of this License, they do not 
> excuse you from the conditions of this License. If you cannot distribute 
> so as to satisfy simultaneously your obligations under this License and 
> any other pertinent obligations, then as a consequence you may not 
> distribute the Program at all. For example, if a patent license would 
> not permit royalty-free redistribution of the Program by all those who 
> receive copies directly or indirectly through you, then the only way you 
> could satisfy both it and this License would be to refrain entirely from 
> distribution of the Program.


[^GPL2]: _GNU General Public License, Version 2.0_, 1991, *available at* [https://opensource.org/licenses/GPL-2.0] (https://opensource.org/licenses/GPL-2.0).

--------------------------------------------------------------------------------
#### GNU General Public License 3.0
Excerpt from the GNU General Public License License, Version 3.0[^GPL3]

> **11\. Patents.** 
> 
> A “contributor” is a copyright holder who authorizes 
> use under this License of the Program or a work on which the Program is 
> based. The work thus licensed is called the contributor's “contributor 
> version”.
> 
> A contributor's “essential patent claims” are all patent claims owned 
> or controlled by the contributor, whether already acquired or hereafter 
> acquired, that would be infringed by some manner, permitted by this License, 
> of making, using, or selling its contributor version, but do not include 
> claims that would be infringed only as a consequence of further 
> modification of the contributor version. For purposes of this definition, 
> “control” includes the right to grant patent sublicenses in a manner 
> consistent with the requirements of this License.
> 
> Each contributor grants you a non-exclusive, worldwide, royalty-free 
> patent license under the contributor's essential patent claims, to make, 
> use, sell, offer for sale, import and otherwise run, modify and propagate 
> the contents of its contributor version.
> 
> In the following three paragraphs, a “patent license” is any express 
> agreement or commitment, however denominated, not to enforce a patent (such 
> as an express permission to practice a patent or covenant not to sue for 
> patent infringement). To “grant” such a patent license to a party means 
> to make such an agreement or commitment not to enforce a patent against 
> the party.
> 
> If you convey a covered work, knowingly relying on a patent license, and 
> the Corresponding Source of the work is not available for anyone to copy, 
> free of charge and under the terms of this License, through a publicly 
> available network server or other readily accessible means, then you 
> must either (1) cause the Corresponding Source to be so available, or 
> (2) arrange to deprive yourself of the benefit of the patent license for 
> this particular work, or (3) arrange, in a manner consistent with the 
> requirements of this License, to extend the patent license to downstream 
> recipients. “Knowingly relying” means you have actual knowledge that, 
> but for the patent license, your conveying the covered work in a country, 
> or your recipient's use of the covered work in a country, would infringe 
> one or more identifiable patents in that country that you have reason to 
> believe are valid.
> 
> If, pursuant to or in connection with a single transaction or arrangement, 
> you convey, or propagate by procuring conveyance of, a covered work, and 
> grant a patent license to some of the parties receiving the covered work 
> authorizing them to use, propagate, modify or convey a specific copy of 
> the covered work, then the patent license you grant is automatically 
> extended to all recipients of the covered work and works based on it.
> 
> A patent license is “discriminatory” if it does not include within the 
> scope of its coverage, prohibits the exercise of, or is conditioned on 
> the non-exercise of one or more of the rights that are specifically 
> granted under this License. You may not convey a covered work if you are 
> a party to an arrangement with a third party that is in the business of 
> distributing software, under which you make payment to the third party 
> based on the extent of your activity of conveying the work, and under 
> which the third party grants, to any of the parties who would receive 
> the covered work from you, a discriminatory patent license (a) in 
> connection with copies of the covered work conveyed by you (or copies made 
> from those copies), or (b) primarily for and in connection with specific 
> products or compilations that contain the covered work, unless you entered 
> into that arrangement, or that patent license was granted, prior to 28 
> March 2007.
> 
> Nothing in this License shall be construed as excluding or limiting any 
> implied license or other defenses to infringement that may otherwise be 
> available to you under applicable patent law.

[^GPL3]: _GNU General Public License, Version 3.0_, *available at* [https://opensource.org/licenses/GPL-3.0] (https://opensource.org/licenses/GPL-3.0) (2007). *See also* Smith, "A Quick Guide to GPLv3," (2007), *available at* [https://www.gnu.org/licenses/quick-guide-gplv3.html](https://www.gnu.org/licenses/quick-guide-gplv3.html) and Stallman, "Why Upgrade to GPLv3," (2007), *available at* [https://www.gnu.org/licenses/rms-why-gplv3.html](https://www.gnu.org/licenses/rms-why-gplv3.html).


--------------------------------------------------------------------------------
#### Mozilla Public License 2.0
Excerpt from the Mozilla Public License, Version 2.0[^MPL2]

> **2\. License Grants and Conditions**
>
> **2\.1\. Grants**
>
> Each Contributor hereby grants You a world-wide, royalty-free, 
> non-exclusive license:

> \[...\] under Patent Claims of such Contributor to make, use, sell, offer 
> for sale, have made, import, and otherwise transfer either its 
> Contributions or its Contributor Version.

\[...\]

> **2\.3\. Limitations on Grant Scope**
>
> The licenses granted in this Section 2 are the only rights granted 
> under this License. No additional rights or licenses will be implied 
> from the distribution or licensing of Covered Software under this 
> License. Notwithstanding Section 2.1(b) above, no patent license is 
> granted by a Contributor:
>
> for any code that a Contributor has removed from Covered Software; or
>
> for infringements caused by: 
> 1. Your and any other third party’s modifications of Covered Software, or 
> 2. the combination of its Contributions with other software (except as 
> part of its Contributor Version); or
> 3. under Patent Claims infringed by Covered Software in the absence of its 
> Contributions.

[^MPL2]: _Mozilla Public License, Version 2.0_, *available at* [https://opensource.org/licenses/MPL-2.0] (https://opensource.org/licenses/MPL-2.0) (2012). 

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

### Industry Agreements: The Open Invention Network Agreement

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

[^OINLicensees]: The current list of OIN licensees is maintained at 
  [https://www.openinventionnetwork.com/community-of-licensees/](https://www.openinventionnetwork.com/community-of-licensees/).
 
The OIN Linux System is defined as follows:[^OINLinuxSystem]

  > “Linux Environment Component” shall mean any of the software packages 
  > whose released source code shall be identified on the OIN website, 
  > including bug fixes and error corrections thereto, or a Predecessor 
  > Release or Successor Release of any of such packages.
  > 
  > “Linux System” shall mean a Linux Environment Component or any combination 
  > of such components to the extent each such component is (i) generally 
  > available under an Open Source License or in the public domain (and the 
  > source code for such component is generally available) and (ii) Distributed 
  > with, or for use with, the Linux Kernel (or is the Linux Kernel).
  
Also see the the tables listing applicable standards[^OINTable0] and
current list of packages.[^OINTable8]
  
[^OINLinuxSystem]: The official definition of the Linux System is defined
  by the definition at [https://www.openinventionnetwork.com/joining-oin/linux-system/](https://www.openinventionnetwork.com/joining-oin/linux-system/)
  and 
  
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
Excerpt from the Open Invention Network License Agreement[^OINLicense]

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
the Members of OIN, OIN, and OIN’s Licensees.

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
been licensed under this Agreement. As used herein, a Licensee’s “Amendment 
Date” shall mean the later of the date an amendment becomes effective under 
Section 2.1 and the date such Licensee becomes a Licensee.

\[...\]

**Definitions:**

“Affiliate” shall mean, with respect to any specified Person, any other 
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

[^SelfExecuting]: *See, e.g.*, section 10 of the GNU General Public License,
  version 3: 10. _Automatic Licensing of Downstream Recipients._ Each time you convey a covered work, the recipient automatically receives a license from the original licensors, to run, modify and propagate that work, subject to this License. 

[^ImpliedLicense]: _De Forest Radio Telephone Co. v. United States_, 273 
  U.S. 236, 241 (1927), _available at_ https://casetext.com/case/de-forest-co-v-united-states


As you read this case and the follow-on cases that have further refined the
scope of implied licenses, think about whether any of a) the statements in 
the license itself, b) the actions of the licensor in applying the open 
source license and distributing copies to the public, or c) the 
self-executing nature of open source licenses may reasonably give rise to an
implied patent license.

#### De Forest Radio Telephone Co. v. United States

--------------------------------------------------------------------------------

United States Supreme Court (1927)[DeForestHeadnote]

[^DeForestHeadnote]: _De Forest Radio Telephone Co. v. United States_, 273 
  U.S. 236, 47 S. Ct. 366 (1927), _available at_ https://casetext.com/case/de-forest-co-v-united-states


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
705. The Act of 1910 provided that whenever an invention described in and 
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
\[Footnote Omitted\] In one meeting, Clayton suggested that Mitsubishi modify 
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
> proved \[sic\] the defense of implied license, \[\Mitsubishi\] must 
> establish by a preponderance of the evidence that (1) there was an 
> existing relationship between Wang and \[Mitsubishi\]; (2) within 
> that relationship, Wang transferred a right to use SIMM invention to 
> \[Mitsubishi\]; (3) the right was transferred for valuable 
> consideration; and (4) Wang has now denied the existence of the right 
> it transferred to \[Mitsubishi\].
> 
> In deciding whether [Mitsubishi has] proved the existence of an implied 
> license, you may consider statements and conduct of Wang from which one 
> would reasonably infer Wang's consent to Mitsubishi's making, using, or 
> selling products to persons other than Wang under the patents.
> 
> If you find that a right to make, use, or sell the SIMM invention  
> granted to \[Mitsubishi\] then you should find and \[sic\] implied 
> license was granted to \[Mitsubishi\] by Wang.

The relevant question to the jury on the Special Verdict Form read, “Has 
Mitsubishi proven by a preponderance of the evidence that Wang licensed 
Mitsubishi to make, use, or sell the subject matter of the '513 patent?. 
The jury answered “Yes.” \[...\] 

After the verdict, the court held a hearing on Mitsubishi's equitable 
defenses, then directed Wang to draft a proposed judgment and findings of 
fact and conclusions of law adopting the jury's determinations on the 
equitable defenses, which Wang did. Mitsubishi objected to Wang's drafts 
and protested that, although the findings and conclusions did not cover the 
implied license, Wang wrote findings on other issues which contradicted and 
undermined the jury's implied license verdict. Furthermore, Wang had 
written that the jury found an implied license, “under the doctrine of legal 
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
verdict, and added the rationale that the implied license arose “under the 
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
constitute “valuable consideration.. The district court's order denying 
Wang's motion for JMOL identified three benefits conferred on Wang: (1) by 
agreeing to manufacture and sell SIMMs, Mitsubishi contributed to a “high 
volume supply and downward pressure on \[the\] price” of SIMMs, which 
benefited Wang as a purchaser of SIMMs; (2) Mitsubishi absorbed development 
and tooling costs; and, (3) Mitsubishi redesigned its SIMMs to conform to 
Wang's preferred design. The district court ruled that each form of 
consideration was supported by substantial evidence.

Looking to the record in search of substantial evidence, Wang's own 
statements show that when the company introduced its SIMM design in June 
1983, Wang intended to buy SIMMs from other producers rather than produce 
SIMMs itself. Eventually, Wang hoped to “get the advantage of the cost 
reduction because of the volumes involved.. The evidence indicates that Wang 
considered lower prices and a larger market to be of value to it, as they 
obviously were as a large user of SIMMs. In time, JEDEC adopted Wang's SIMM 
design as a standard in what became a multi-billion dollar market. The 
market grew; prices dropped. The record contains evidence that Mitsubishi 
contributed to this advantageous outcome. Clayton's notes about Mitsubishi, 
for example, contain references to prices “dropping to mid-teens.. Wang 
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
which Mitsubishi decided against, but Clayton also sought “to open 
\[communication with\] Japan for us on a 256K X9 SIMM. All the while, Wang 
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

One of our predecessor courts observed that “courts generally have first 
looked for facts which give rise to an estoppel in the process of concluding 
that there is an implied license.”  *AMP*, 389 F.2d at 452, 156 USPQ at 649. 
The opinions that hew most closely to the *De Forest* language and the “entire 
course of conduct” analysis rely on the doctrine of equitable estoppel, 
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
Equitable estoppel, on the other hand, focuses on “misleading” conduct 
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
received payment from, the United States for use of an “idea” which later 
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
proved that the “entire course of conduct” between the parties over a 
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

The findings that Wang bestowed “a right to use the SIMM invention” and that 
Mitsubishi supplied valuable consideration to Wang, support our holding that 
Wang's conduct created a license. This falls short of the express licenses or 
assignments usually discussed in conjunction with legal estoppel, but it 
constitutes part of a course of conduct that transcends “unilateral 
expectations ..․ of one party.”  *Stickle*, 716 F.2d at 1559, 219 USPQ at 383. 
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

An \[equitable\] estoppel case ... has three important elements. \[1\] 
The actor, who usually must have knowledge of the true facts, 
communicates something in a misleading way, either by words, conduct or 
silence. \[2\] The other relies upon that communication. \[3\] And the 
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

##### Discussion
 
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
  
4. "Equitable estoppel... focuses on “misleading” conduct suggesting that 
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
> Hilgraeve's entire knowledge base with respect to \[Hilgraeve's\] products. 
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
proposition that "unexpressed terms \[are implied\] to implement \[the\] 
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

##### Discussion
 
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

### Statutory Law

Each area of intellectual property law reserves particular rights to the
owner of the corresponding intellectual property. The exclusive rights 
granted under copyright law are different than the exclusive rights
granted under patent law.

--------------------------------------------------------------------------------
#### 17 U.S. Code § 106 - Exclusive rights in copyrighted works

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
#### 35 U.S.C. 271 Infringement of patent.

(a) Except as otherwise provided in this title, whoever without authority 
makes, uses, offers to sell, or sells any patented invention, within the 
United States, or imports into the United States any patented invention 
during the term of the patent therefor, infringes the patent. 

--------------------------------------------------------------------------------

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
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION 
OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN 
CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

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

##### Discussion
 
1. The licenses above all include the permission to "use" the software. Is
  that a patent grant or verbal shorthand for "create copies of the software
  in a computer memory and interpret the copy by means of a processor"?
  Could it be both? 

2. To what extent does the right the "distribute \[the\] software ... with
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
Plaintiffs and Counterclaim Defendant Aventis Behring GmbH.[^FNOmitted] 
Plaintiff Nattermann is the owner of the '427 patent, Counterclaim Defendant 
Aventis Behring GmbH has a non-exclusive license to the patent, and Plaintiff 
Aventis Behring L.L.C. has a sublicense. The '427 patent involves a drug used 
in the treatment of hemophilia. Plaintiffs claim that an anti-hemophilila drug 
marketed by Defendants under the name KOGENATE® FS infringes the '427 patent. 
Defendants bring counterclaims against Plaintiffs for, inter alia, breach of a 
1998 Supply Agreement entered into by Bayer and Centeon L.L.C., a predecessor 
of Plaintiff Aventis Behring L.L.C., under which Bayer was to manufacture its 
KOGENATE® product for Centeon L.L.C.

[^FNOmitted]: Except where noted, footnotes and cites to the record have been omitted.

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
the Settlement Agreement between Bayer AG and Armour just as the 1994 Agreement 
was part of said Settlement Agreement." The parties incorporated Section 9 of 
the 1994 Agreement into Section 10 of the 1998 Agreement. 

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
\[FN8\] *See* _Carborundum Co. v. Molten Metal Equip. Innovations_, 72 F.3d 
872, 878 (Fed. Cir.1995). The alleged infringer has the burden of establishing 
this affirmative defense. *Id*. It has been observed that:

> \[n\]o formal granting of a license is necessary in order to give it 
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
based. Under Connecticut law, "\[a\]lthough ordinarily the question of 
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
provides, in part, that "\[n\]o license, express or implied, is granted by one 
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
an implied license to the '427 patent. \[FN12\] To the contrary, the provision 
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

\[FN8\]: An express license is merely "\[o\]ne which is granted in direct 
terms." Black's Law Dictionary 920 (6th ed.1990). The definition of "implied 
license" in this context is slightly more nuanced. In patent law, the term 
"implied license" has been used to refer to "different categories of conduct 
which lead to the same conclusion," namely, "a patentee's waiver of the 
statutory right to exclude others from making, using, or selling the patented 
invention." _Wang Labs., Inc. v. Mitsubishi Electronics Am., Inc._, 103 F.3d 
1571, 1580 (Fed.Cir.1997). "\[C\]ourts and commentators relate that implied 
licenses arise by acquiescence, by conduct, by equitable estoppel (estoppel in 
pais), or by legal estoppel." *Id*. These distinctions as to implied licenses 
are not relevant for purposes of the instant motions.

\[FN12\]: Plaintiffs "move for summary judgment of no license—either express 
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
license is merely '\[o\]ne which is granted in direct terms.'" *Id, n.8 
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
Lindwall_, 692 S.E.2d 690 (Ga. App. 2010)). "'\[A\]ll the contract terms must 
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
that "\[a\] Purchase Order will be binding on \[Debtor\] only after accepted 
in writing . . . by \[Debtor\]." Agreement, Exhibit B, § 1. Therefore, under 
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

This case spawned from earlier litigation between Versata and Ameriprise. During that litigation, Ameriprise reached out to XimpleWare to support its defense of the pending litigation and informed XimpleWare that it had discovered XimpleWare VTM-XML source code throughout Versata's DCM product. In violation of Versata's license under the GNU. XimpleWare then filed this suit against the Versata Defendants, Ameriprise and other Versata customers. XimpleWare's complaint asserts claims for (1) direct infringement of the '857, '459 and '652 patents under 35 U.S.C. § 271(a) against all defendants; (2) inducement under 35 U.S.C. § 271(b) against Versata and its corporate parents Aurea and Trilogy; and (3) declaratory relief that the asserted patents are valid and enforceable.

\[...\]

**III. DISCUSSION**

**A. The Versata Customers' Motions to Dismiss**

The court starts with the customers' motions challenging XimpleWare's 
allegations of direct infringement \[of Ximpleware's patents\] pursuant 
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
Ameriprise. As Judge Illston explains, "\[a\]ccepting as true the facts alleged 
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

> \[A\] license ... \[is\] a mere waiver of the right to sue by the patentee."  
> A license need not be a formal grant, but is instead a "consent[] to \[the\] 
> use of the patent in making or using it, or selling it ... and a defense to 
> an action for a tort." The Court of Appeals for the Federal Circuit 
> explained that the inquiry focuses on what the agreement authorizes, not 
> whether the language is couched in terms of a license or a covenant not 
> to sue; effectively the two are equivalent. 

##### Discussion
 
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



<!-- Footnotes themselves at the bottom. -->

## Notes

