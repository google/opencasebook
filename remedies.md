# Contract and Copyright Remedies Available under Open Source Licenses
{:.no_toc}

* Table of Contents
{:toc}

## Introduction

What happens if you do not follow the terms of an open source license? Are you
liable for breach of contract or copyright claims? This distinction is critical,
as the remedies are different for both.[^1]

Generally, a licensor who grants a nonexclusive license to copyrighted material
waives the right to sue a licensee for copyright infringement, and may sue only
for breach of contract.[^2] "If, however, a license is limited in scope and the
licensee acts outside the scope, the licensor may bring an action for copyright
infringement."[^3] But how might a licensee act outside the scope of a license?

This chapter will present two cases, *Jacobsen v. Katzer* and *MDY v. Blizzard
Entm't*. The primary focus of these opinions is the difference between
contractual covenants and contractual conditions. A covenant is an unqualified
promise to perform or refrain from an act. A condition is an act or event,
uncertain to occur, that must occur before a duty to perform arises. The Courts
in these cases build upon the understanding that conditions define the scope of
a contract, and use this for determining which acts of a licensee will therefore
fall outside the scope of a contract and expose the licensee to the possibility
of copyright infringement remedies.

The *Jacobsen* court examines the connection between the copyright license at
issue and the economic rights of the licensor. The *MDY* court considers whether
the condition violated has a nexus to the licensor's exclusive rights of
copyright. While reading these cases ask yourself, how are these tests related?

We commence with a comparison of the remedies for contract breach and copyright
infringement to provide context. We conclude by reviewing the terms of a few
open source licenses under the framework of covenants, conditions, and nexuses
between conditions and the exclusive rights of copyright.

### The Remedies Compared

Contract remedies are generally limited to an award of damages that will fulfill
the "expectation interest" of the harmed party.[^4] In other words, the harmed
party is owed the amount of money that will put them in as good a position as
they would have been if the contract had been performed.[^5] Other available
contract remedies include specific performance,[^6] for example injunctions to
stop distributing a work of software, but specific performance will not be
ordered if money is adequate to fulfill the harmed party's expectation
interest.[^7] Punitive damages are unrecoverable for breach of contract unless
the breach itself is a tort for which punitive damages are recoverable.[^8]

The remedies for copyright infringement, on the other hand, can include up to
$150,000 in statutory damages per work infringed.[^12] Alternatively, a
copyright holder can seek "to recover the actual damages suffered by him or her
as a result of the infringement, and any profits of the infringer that are
attributable to the infringement.[^13] A court may order injunctive relief, such
as blocking a copyright infringer from making derivative works.[^14] A court may
also impound all articles embodying a reproduction of the copyrighted work.[^15]
A court may also award costs and attorney's fees.[^16]

## Cases

### Jacobsen v. Katzer

--------------------------------------------------------------------------------

535 F.3d 1373

HOCHBERG, District Judge. We consider here the ability of a copyright holder to
dedicate certain work to free public use and yet enforce an "open source"
copyright license to control the future distribution and modification of that
work.

[...]

I.

Jacobsen manages an open source software group called Java Model Railroad
Interface ("JMRI"). Through the collective work of many participants, JMRI
created a computer programming application called DecoderPro, which allows model
railroad enthusiasts to use their computers to program the decoder chips that
control model trains. DecoderPro files are available for download and use by the
public free of charge from an open source incubator website called SourceForge;
Jacobsen maintains the JMRI site on SourceForge. The downloadable files contain
copyright notices and refer the user to a "COPYING" file, which clearly sets
forth the terms of the Artistic License.

Katzer/Kamind offers a competing software product, Decoder Commander, which is
also used to program decoder chips. During development of Decoder Commander, one
of Katzer/Kamind's predecessors or employees is alleged to have downloaded the
decoder definition files from DecoderPro and used portions of these files as
part of the Decoder Commander software. The Decoder Commander software files
that used DecoderPro definition files did not comply with the terms of the
Artistic License. Specifically, the Decoder Commander software did not include
(1) the authors' names, (2) JMRI copyright notices, (3) references to the
COPYING file, (4) an identification of SourceForge or JMRI as the original
source of the definition files, and (5) a description of how the files or
computer code had been changed from the original source code. The Decoder
Commander software also changed various computer file names of DecoderPro files
without providing a reference to the original JMRI files or information on where
to get the Standard Version.[^17]

Jacobsen moved for a preliminary injunction, arguing that the violation of the
terms of the Artistic License constituted copyright infringement and that, under
Ninth Circuit law, irreparable harm could be presumed in a copyright
infringement case. The District Court reviewed the Artistic License and
determined that "Defendants' alleged violation of the conditions of the license
may have constituted a breach of the nonexclusive license, but does not create
liability for copyright infringement where it would not otherwise exist."
[cite]. The District Court found that Jacobsen had a cause of action only for
breach of contract, rather than an action for copyright infringement based on a
breach of the conditions of the Artistic License. Because a breach of contract
creates no presumption of irreparable harm, the District Court denied the motion
for a preliminary injunction.

Jacobsen appeals the finding that he does not have a cause of action for
copyright infringement. Although an appeal concerning copyright law and not
patent law is rare in our Circuit, here we indeed possess appellate
jurisdiction.

[…]

A.

Public licenses, often referred to as "open source" licenses, are used by
artists, authors, educators, software developers, and scientists who wish to
create collaborative projects and to dedicate certain works to the public.
Several types of public licenses have been designed to provide creators of
copyrighted materials a means to protect and control their copyrights. Creative
Commons, one of the amici curiae, provides free copyright licenses to allow
parties to dedicate their works to the public or to license certain uses of
their works while keeping some rights reserved.

Open source licensing has become a widely used method of creative collaboration
that serves to advance the arts and sciences in a manner and at a pace that few
could have imagined just a few decades ago. For example, the Massachusetts
Institute of Technology ("MIT") uses a Creative Commons public license for an
OpenCourseWare project that licenses all 1800 MIT courses. Other public licenses
support the GNU/Linux operating system, the Perl programming language, the
Apache web server programs, the Firefox web browser, and a collaborative
web-based encyclopedia called Wikipedia. Creative Commons notes that, by some
estimates, there are close to 100,000,000 works licensed under various Creative
Commons licenses. The Wikimedia Foundation, another of the amici curiae,
estimates that the Wikipedia website has more than 75,000 active contributors
working on some 9,000,000 articles in more than 250 languages.

Open source software projects invite computer programmers from around the world
to view software code and make changes and improvements to it. Through such
collaboration, software programs can often be written and debugged faster and at
lower cost than if the copyright holder were required to do all of the work
independently. In exchange and in consideration for this collaborative work, the
copyright holder permits users to copy, modify and distribute the software code
subject to conditions that serve to protect downstream users and to keep the
code accessible.[^18] By requiring that users copy and restate the license and
attribution information, a copyright holder can ensure that recipients of the
redistributed computer code know the identity of the owner as well as the scope
of the license granted by the original owner. The Artistic License in this case
also requires that changes to the computer code be tracked so that downstream
users know what part of the computer code is the original code created by the
copyright holder and what part has been newly added or altered by another
collaborator.

Traditionally, copyright owners sold their copyrighted material in exchange for
money. The lack of money changing hands in open source licensing should not be
presumed to mean that there is no economic consideration, however. There are
substantial benefits, including economic benefits, to the creation and
distribution of copyrighted works under public licenses that range far beyond
traditional license royalties. For example, program creators may generate market
share for their programs by providing certain components free of charge.
Similarly, a programmer or company may increase its national or international
reputation by incubating open source projects. Improvement to a product can come
rapidly and free of charge from an expert not even known to the copyright
holder. The Eleventh Circuit has recognized the economic motives inherent in
public licenses, even where profit is not immediate. See Planetary Motion, Inc.
v. Techsplosion, Inc., 261 F.3d 1188, 1200 (11th Cir. 2001) (Program creator
"derived value from the distribution [under a public license] because he was
able to improve his Software based on suggestions sent by end-users. . . . It is
logical that as the Software improved, more end-users used his Software, thereby
increasing [the programmer's] recognition in his profession and the likelihood
that the Software would be improved even further.").

B.

The parties do not dispute that Jacobsen is the holder of a copyright for
certain materials distributed through his website.[^19] Katzer/Kamind also
admits that portions of the DecoderPro software were copied, modified, and
distributed as part of the Decoder Commander software. Accordingly, Jacobsen has
made out a prima facie case of copyright infringement. Katzer/Kamind argues that
they cannot be liable for copyright infringement because they had a license to
use the material. Thus, the Court must evaluate whether the use by Katzer/Kamind
was outside the scope of the license. *See LGS Architects*, 434 F.3d at 1156.
The copyrighted materials in this case are downloadable by any user and are
labeled to include a copyright notification and a COPYING file that includes the
text of the Artistic License. The Artistic License grants users the right to
copy, modify, and distribute the software:

provided that [the user] insert a prominent notice in each changed file stating
how and when [the user] changed that file, and provided that [the user] do at
least ONE of the following:

a) place [the user's] modifications in the Public Domain or otherwise make them
Freely Available, such as by posting said modifications to Usenet or an
equivalent medium, or placing the modifications on a major archive site such as
ftp.uu.net, or by allowing the Copyright Holder to include [the user's]
modifications in the Standard Version of the Package.

b) use the modified Package only within [the user's] corporation or
organization.

c) rename any non-standard executables so the names do not conflict with the
standard executables, which must also be provided, and provide a separate manual
page for each nonstandard executable that clearly documents how it differs from
the Standard Version, or

d) make other distribution arrangements with the Copyright Holder.

The heart of the argument on appeal concerns whether the terms of the Artistic
License are conditions of, or merely covenants to, the copyright license.
Generally, a "copyright owner who grants a nonexclusive license to use his
copyrighted material waives his right to sue the licensee for copyright
infringement" and can sue only for breach of contract. Sun Microsystems, Inc.,
v. Microsoft Corp., 188 F.3d 1115, 1121 (9th Cir. 1999); Graham v. James, 144
F.3d 229, 236 (2d Cir. 1998). If, however, a license is limited in scope and the
licensee acts outside the scope, the licensor can bring an action for copyright
infringement. See S.O.S., Inc. v. Payday, Inc., 886 F.2d 1081, 1087 (9th
Cir.1989); Nimmer on Copyright, § 1015[A]\(1999\).

Thus, if the terms of the Artistic License allegedly violated are both covenants
and conditions, they may serve to limit the scope of the license and are
governed by copyright law. If they are merely covenants, by contrast, they are
governed by contract law. *See Graham*, 144 F.3d at 236-37 whether breach of
license is actionable as copyright infringement or breach of contract turns on
whether provision breached is condition of the license, or mere covenant); Sun
Microsystems, 188 F.3d at 1121 (following Graham; independent covenant does not
limit scope of copyright license). The District Court did not expressly state
whether the limitations in the Artistic License are independent covenants or,
rather, conditions to the scope; its analysis, however, clearly treated the
license limitations as contractual covenants rather than conditions of the
copyright license.[^20]

Jacobsen argues that the terms of the Artistic License define the scope of the
license and that any use outside of these restrictions is copyright
infringement. Katzer/Kamind argues that these terms do not limit the scope of
the license and are merely covenants providing contractual terms for the use of
the materials, and that his violation of them is neither compensable in damages
nor subject to injunctive relief. Katzer/Kamind's argument is premised upon the
assumption that Jacobsen's copyright gave him no economic rights because he made
his computer code available to the public at no charge. From this assumption,
Katzer/Kamind argues that copyright law does not recognize a cause of action for
non-economic rights, relying on Gilliam v. ABC, 538 F.2d 14, 20-21 (2d Cir.
1976) "American copyright law, as presently written, does not recognize moral
rights or provide a cause of action for their violation, since the law seeks to
vindicate the economic, rather than the personal rights of authors."). The
District Court based its opinion on the breadth of the Artistic License terms,
to which we now turn.

III.

The Artistic License states on its face that the document creates conditions:
"The intent of this document is to state the conditions under which a Package
may be copied." (Emphasis added.) The Artistic License also uses the traditional
language of conditions by noting that the rights to copy, modify, and distribute
are granted "provided that" the conditions are met. Under California contract
law, "provided that" typically denotes a condition. *See, e.g., Diepenbrock v.
Luiz*, 159 Cal. 716, 115 P. 743 (1911) (interpreting a real property lease
reciting that when the property was sold, "this lease shall cease and be at an
end, provided that the party of the first part shall then pay [certain
compensation] to the party of the second part"; considering the appellant's
"interesting and ingenious" argument for interpreting this language as creating
a mere covenant rather than a condition; and holding that this argument "cannot
change the fact that, attributing the usual and ordinary signification to the
language of the parties, a *condition* is found in the provision in question")
(emphases added).

The conditions set forth in the Artistic License are vital to enable the
copyright holder to retain the ability to benefit from the work of downstream
users. By requiring that users who modify or distribute the copyrighted material
retain the reference to the original source files, downstream users are directed
to Jacobsen's website. Thus, downstream users know about the collaborative
effort to improve and expand the SourceForge project once they learn of the
"upstream" project from a "downstream" distribution, and they may join in that
effort.

The District Court interpreted the Artistic License to permit a user to "modify
the material in any way" and did not find that any of the "provided that"
limitations in the Artistic License served to limit this grant. The District
Court's interpretation of the conditions of the Artistic License does not credit
the explicit restrictions in the license that govern a downloader's right to
modify and distribute the copyrighted work. The copyright holder here expressly
stated the terms upon which the right to modify and distribute the material
depended and invited direct contact if a downloader wished to negotiate other
terms. These restrictions were both clear and necessary to accomplish the
objectives of the open source licensing collaboration, including economic
benefit. Moreover, the District Court did not address the other restrictions of
the license, such as the requirement that all modification from the original be
clearly shown with a new name and a separate page for any such modification that
shows how it differs from the original.

Copyright holders who engage in open source licensing have the right to control
the modification and distribution of copyrighted material. As the Second Circuit
explained in Gilliam v. ABC, 538 F.2d 14, 21 (2d Cir. 1976), the "unauthorized
editing of the underlying work, if proven, would constitute an infringement of
the copyright in that work similar to any other use of a work that exceeded the
license granted by the proprietor of the copyright." Copyright licenses are
designed to support the right to exclude; money damages alone do not support or
enforce that right. The choice to exact consideration in the form of compliance
with the open source requirements of disclosure and explanation of changes,
rather than as a dollar-denominated fee, is entitled to no less legal
recognition. Indeed, because a calculation of damages is inherently speculative,
these types of license restrictions might well be rendered meaningless absent
the ability to enforce through injunctive relief.

In this case, a user who downloads the JMRI copyrighted materials is authorized
to make modifications and to distribute the materials "provided that" the user
follows the restrictive terms of the Artistic License. A copyright holder can
grant the right to make certain modifications, yet retain his right to prevent
other modifications. Indeed, such a goal is exactly the purpose of adding
conditions to a license grant.[^21] The Artistic License, like many other common
copyright licenses, requires that any copies that are distributed contain the
copyright notices and the COPYING file. See, e.g., 3-10 Nimmer on Copyright §
10.15 ("An express (or possibly an implied) condition that a licensee must affix
a proper copyright notice to all copies of the work that he causes to be
published will render a publication devoid of such notice without authority from
the licensor and therefore, an infringing act.").

It is outside the scope of the Artistic License to modify and distribute the
copyrighted materials without copyright notices and a tracking of modifications
from the original computer files. If a downloader does not assent to these
conditions stated in the COPYING file, he is instructed to "make other
arrangements with the Copyright Holder." Katzer/Kamind did not make any such
"other arrangements." The clear language of the Artistic License creates
conditions to protect the economic rights at issue in the granting of a public
license. These conditions govern the rights to modify and distribute the
computer programs and files included in the downloadable software package. The
attribution and modification transparency requirements directly serve to drive
traffic to the open source incubation page and to inform downstream users of the
project, which is a significant economic goal of the copyright holder that the
law will enforce. Through this controlled spread of information, the copyright
holder gains creative collaborators to the open source project; by requiring
that changes made by downstream users be visible to the copyright holder and
others, the copyright holder learns about the uses for his software and gains
others' knowledge that can be used to advance future software releases.

IV.

For the aforementioned reasons, we vacate and remand. [...] The judgment of the
District Court is vacated and the case is remanded for further proceedings
consistent with this opinion.

#### Discussion

1.  The test for determining copyright liability for breach of a license stated
    by the Federal Circuit in *Jacobsen* relies on distinguishing covenants from
    conditions. This excerpt from a later case clarifies the distinction under
    California law:

        "A covenant 'is another word for a contractual promise.' A promise for
        contract purposes 'is a manifestation of intention to act or refrain from
        acting in a specified way, so made as to justify a promisee in understanding
        that a commitment has been made.' Implied covenants are disfavored and will
        only be found if they effectuate the intent of the parties, are a legal
        necessity and 'after examining the contract as a whole it is [] obvious that
        the parties had no reason to state the covenant[.]' A condition, on the
        other hand, 'is an event, not certain to occur, which must occur, unless its
        non-occurrence is excused, before performance under a contract becomes due.'
        Under California law a conditional obligation is one 'when the rights or
        duties of any party thereto depend upon the occurrence of an uncertain
        event.'" [Netbula, LLC v. Storage Tech. Corp., No. C06-07391 MJJ, 2008 U.S.
        Dist. LEXIS 4119, at 9 (N.D. Cal. Jan. 17,
        2008)](https://advance.lexis.com/api/document/collection/cases/id/4RN5-M7P0-TXFP-C34C-00000-00?page=9&reporter=1293&context=1000516)*
        (internal citations omitted).

2.  When might a license term be a condition rather than a covenant?

    See [Sun Microsystems, Inc. v. Microsoft Corp., 81 F. Supp. 2d 1026, 1032-33
    (N.D. Cal.
    2000)](https://advance.lexis.com/api/document/collection/cases/id/3YP8-G380-0038-Y0HN-00000-00?page=1032&reporter=1109&context=1000516)*
    (finding breached compatibility obligations to be a covenant, emphasizing
    that the license grant was not stated as being conditioned on the
    compatibility obligations and emphasizing the presence of a cure provision
    within the agreement); [Montalvo v. LT's Benjamin Records, Inc., 56 F. Supp.
    3d 121, 130 (D.P.R.
    2014)](https://advance.lexis.com/api/document/collection/cases/id/5DHT-78M1-F04F-50S6-00000-00?page=130&reporter=1121&context=1000516)
    (holding failure to pay royalties to be a breach of a covenant); *[Sleash,
    LLC v. One Pet Planet, LLC, No. 3:14-cv-00863-ST, 2014 U.S. Dist. LEXIS
    109253, at 51 (D. Or. Aug. 6,
    2014)](https://advance.lexis.com/api/document/collection/cases/id/5CVC-W4C1-F04F-30TP-00000-00?page=51&reporter=1293&context=1000516)
    (finding one contract term to be a covenant where the term appeared in a
    separate section from the license grant and finding another contract term to
    be a covenant where the term was stated in promissory, as opposed to
    conditional, terms).

    But see [Accusoft Corp. v. Quest Diagnostics, Inc., No. 12-cv-40007-TSH,
    2015 U.S. Dist. LEXIS 156693, at 76 (D. Mass. Aug. 19,
    2015)](https://advance.lexis.com/api/document/collection/cases/id/5HDR-RB11-F04D-D0HK-00000-00?page=76&reporter=1293&context=1000516)*
    (finding a number of EULA terms to be conditions under Massachusetts law, as
    the terms clearly limited the scope of the license and were stated with
    emphatic, conditional language); [Alaska Stock, LLC v. Pearson Educ., Inc.,
    975 F. Supp. 2d 1027, 1044 (D. Alaska
    2013)](https://advance.lexis.com/api/document/collection/cases/id/59HT-5V91-F04C-N013-00000-00?page=1044&reporter=1109&context=1000516)
    (holding that a term limiting "the number of publications in which an image
    could appear [was] no different from the Ninth Circuit's example of the
    person who made a hundred copies of a book while licensed to make only one"
    and was therefore a condition); [Jacobsen v. Katzer, 535 F.3d 1373, 1381
    (Fed. Cir.
    2008)](https://advance.lexis.com/api/document/collection/cases/id/4T6V-54Y0-TX4N-G15K-00000-00?page=1381&reporter=1107&context=1000516)
    ("Under California contract law, 'provided that' typically denotes a
    condition.").

3.  The Jacobsen court recognizes that open source licensing schemes can confer
    an economic benefit upon licensors. [Jacobsen v. Katzer, 535 F.3d 1373, 1382
    (Fed. Cir.
    2008)](https://advance.lexis.com/api/document/collection/cases/id/4T6V-54Y0-TX4N-G15K-00000-00?page=1382&reporter=1107&context=1000516)("The
    clear language of the Artistic License creates conditions to protect the
    economic rights at issue in the granting of a public license. These
    conditions govern the rights to modify and distribute the computer programs
    and files included in the downloadable software package. The attribution and
    modification transparency requirements directly serve to drive traffic to
    the open source incubation page and to inform downstream users of the
    project, which is a significant economic goal of the copyright holder that
    the law will enforce.").

    What if there was no economic benefit conferred by a software license, or by
    a given condition of a software license? For example, what if an author
    conditioned redistribution of their program upon the redistributor doing ten
    push-ups for each distribution? How would the court interpret
    non-performance of the condition? Would that be an act outside the scope of
    the copyright license, and therefore infringement?

4.  The Restatement (Second) of Contracts defines a condition as "an event, not
    certain to occur, which must occur, unless its non-occurrence is excused,
    before performance under a contract becomes due." § 224. How might the
    non-occurrence of a condition be excused in the software licensing context?
    Under an open source license, would the excused non-occurrence of a
    condition mean that breach of that condition could not give rise to
    copyright infringement?

### MDY Industries, LLC v. Blizzard Entertainment, Inc., et al

--------------------------------------------------------------------------------

629 F.3d 928 (9th Cir. 2010)

OPINION

CALLAHAN, Circuit Judge:

Blizzard Entertainment, Inc. ("Blizzard") is the creator of World of Warcraft
("WoW"), a popular multiplayer online role-playing game in which players
interact in a virtual world while advancing through the game's 70 levels. MDY
Industries, LLC and its sole member Michael Donnelly ("Donnelly") (sometimes
referred to collectively as "MDY") developed and sold Glider, a software program
that automatically plays the early levels of WoW for players.

MDY brought this action for a declaratory judgment to establish that its Glider
sales do not infringe Blizzard's copyright or other rights, and Blizzard
asserted counterclaims under the Digital Millennium Copyright Act ("DMCA"), 17
U.S.C. § 1201 *et seq*., and for tortious interference with contract under
Arizona law. The district court found MDY and Donnelly liable for secondary
copyright infringement, violations of DMCA §§ 1201(a)(2) and (b)(1), and
tortious interference with contract. We reverse the district court except as to
MDY's liability for violation of DMCA § 1201(a)(2) and remand for trial on
Blizzard's claim for tortious interference with contract.

I.

<span style="text-decoration:underline;">A. World of Warcraft</span>

In November 2004, Blizzard created WoW, a "massively multiplayer online
role-playing game" in which players interact in a virtual world. WoW has ten
million subscribers, of which two and a half million are in North America. The
WoW software has two components: (1) the game client software that a player
installs on the computer; and (2) the game server software, which the player
accesses on a subscription basis by connecting to WoW's online servers. WoW does
not have single-player or offline modes.

WoW players roleplay different characters, such as humans, elves, and dwarves. A
player's central objective is to advance the character through the game's 70
levels by participating in quests and engaging in battles with monsters. As a
player advances, the character collects rewards such as in-game currency,
weapons, and armor. WoW's virtual world has its own economy, in which characters
use their virtual currency to buy and sell items directly from each other,
through vendors, or using auction houses. Some players also utilize WoW's chat
capabilities to interact with others.

<span style="text-decoration:underline;">B. Blizzard's use agreements</span>

Each WoW player must read and accept Blizzard's End User License Agreement
("EULA") and Terms of Use ("ToU") on multiple occasions. The EULA pertains to
the game client, so a player agrees to it both before installing the game client
and upon first running it. The ToU pertains to the online service, so a player
agrees to it both when creating an account and upon first connecting to the
online service. Players who do not accept both the EULA and the ToU may return
the game client for a refund.

<span style="text-decoration:underline;">C. Development of Glider and
Warden</span>

Donnelly is a WoW player and software programmer. In March 2005, he developed
Glider, a software "bot" (short for robot) that automates play of WoW's early
levels, for his personal use. A user need not be at the computer while Glider is
running. As explained in the Frequently Asked Questions ("FAQ") on MDY's website
for Glider:

Glider . . . moves the mouse around and pushes keys on the keyboard. You tell it
about your character, where you want to kill things, and when you want to kill.
Then it kills for you, automatically. You can do something else, like eat dinner
or go to a movie, and when you return, you'll have a lot more experience and
loot.

Glider does not alter or copy WoW's game client software, does not allow a
player to avoid paying monthly subscription dues to Blizzard, and has no
commercial use independent of WoW. Glider was not initially designed to avoid
detection by Blizzard.

The parties dispute Glider's impact on the WoW experience. Blizzard contends
that Glider disrupts WoW's environment for non-Glider players by enabling Glider
users to advance quickly and unfairly through the game and to amass additional
game assets. MDY contends that Glider has a minimal effect on non-Glider
players, enhances the WoW experience for Glider users, and facilitates disabled
players' access to WoW by auto-playing the game for them.

In summer 2005, Donnelly began selling Glider through MDY's website for fifteen
to twenty-five dollars per license. Prior to marketing Glider, Donnelly reviewed
Blizzard's EULA and client-server manipulation policy. He reached the conclusion
that Blizzard had not prohibited bots in those documents.

In September 2005, Blizzard launched Warden, a technology that it developed to
prevent its players who use unauthorized third-party software, including bots,
from connecting to WoW's servers. Warden was able to detect Glider, and Blizzard
immediately used Warden to ban most Glider users. MDY responded by modifying
Glider to avoid detection and promoting its new anti-detection features on its
website's FAQ. It added a subscription service, Glider Elite, which offered
"additional protection from game detection software" for five dollars a month.

Thus, by late 2005, MDY was aware that Blizzard was prohibiting bots. MDY
modified its website to indicate that using Glider violated Blizzard's ToU. In
November 2005, Donnelly wrote in an email interview, "Avoiding detection is
rather exciting, to be sure. Since Blizzard does not want bots running at all,
it's a violation to use them." Following MDY's anti-detection modifications,
Warden only occasionally detected Glider. As of September 2008, MDY had gross
revenues of $3.5 million based on 120,000 Glider license sales.

<span style="text-decoration:underline;">D. Financial and practical impact of
Glider</span>

Blizzard claims that from December 2004 to March 2008, it received 465,000
complaints about WoW bots, several thousand of which named Glider. Blizzard
spends $940,000 annually to respond to these complaints, and the parties have
stipulated that Glider is the principal bot used by WoW players. Blizzard
introduced evidence that it may have lost monthly subscription fees from Glider
users, who were able to reach WoW's highest levels in fewer weeks than players
playing manually. Donnelly acknowledged in a November 2005 email that MDY's
business strategy was to make Blizzard's anti-bot detection attempts financially
prohibitive:

The trick here is that Blizzard has a finite amount of development and test
resources, so we want to make it bad business to spend that much time altering
their detection code to find Glider, since Glider's negative effect on the game
is debatable . . . . [W]e attack th[is] weakness and try to make it a bad idea
or make their changes very risky, since they don't want to risk banning or
crashing innocent customers.

[...]

II.

On December 1, 2006, MDY filed an amended complaint seeking a declaration that
Glider does not infringe Blizzard's copyright or other rights. In February 2007,
Blizzard filed counterclaims and third-party claims against MDY and Donnelly
for, *inter alia*, contributory and vicarious copyright infringement, violation
of DMCA §§ 1201(a)(2) and (b)(1), and tortious interference with contract.

In July 2008, the district court granted Blizzard partial summary judgment,
finding that MDY's Glider sales contributorily and vicariously infringed
Blizzard's copyrights and tortiously interfered with Blizzard's contracts. The
district court also granted MDY partial summary judgment, finding that MDY did
not violate DMCA § 1201(a)(2) with respect to accessing the game software's
source code.

In September 2008, the parties stipulated to entry of a $6 million judgment
against MDY for the copyright infringement and tortious interference with
contract claims. They further stipulated that Donnelly would be personally
liable for the same amount if found personally liable at trial. After a January
2009 bench trial, the district court held MDY liable under DMCA §§ 1201(a)(2)
and (b)(1). It also held Donnelly personally liable for MDY's copyright
infringement, DMCA violations, and tortious interference with contract.

On April 1, 2009, the district court entered judgment against MDY and Donnelly
for $6.5 million, an adjusted figure to which the parties stipulated based on
MDY's DMCA liability and post-summary judgment Glider sales. The district court
permanently enjoined MDY from distributing Glider. MDY's efforts to stay
injunctive relief pending appeal were unsuccessful. On April 29, 2009, MDY
timely filed this appeal. On May 12, 2009, Blizzard timely cross-appealed the
district court's holding that MDY did not violate DMCA §§ 1201(a)(2) and (b)(1)
as to the game software's source code.

III.

We review de novo the district court's (1) orders granting or denying summary
judgment; (2) conclusions of law after a bench trial; and (3) interpretations of
state law. *Padfield v. AIG Life Ins*., 290 F.3d 1121, 1124 (9th Cir. 2002);
*Twentieth Century Fox Film Corp. v. Entm't Distrib*., 429 F.3d 869, 879 (9th
Cir. 2005); *Laws v. Sony Music Entm't, Inc*., 448 F.3d 1134, 1137 (9th Cir.
2006). We review the district court's findings of fact for clear error.
*Twentieth Century Fox*, 429 F.3d at 879.

IV.

We first consider whether MDY committed contributory or vicarious infringement
(collectively, "secondary infringement") of Blizzard's copyright by selling
Glider to WoW players.[^22] *See ProCD, Inc. v. Zeidenberg*, 86 F.3d 1447, 1454
(7th Cir. 1996) ("A copyright is a right against the world. Contracts, by
contrast, generally affect only their parties.").* *To establish secondary
infringement, Blizzard must first demonstrate direct infringement. *See A&M
Records, Inc. v. Napster, Inc*., 239 F.3d 1004, 1019, 1022 (9th Cir. 2001). To
establish direct infringement, Blizzard must demonstrate copyright ownership and
violation of one of its exclusive rights by Glider users. *Id*. at 1013. MDY is
liable for contributory infringement if it has "intentionally induc[ed] or
encourag[ed] direct infringement" by Glider users. *MGM Studios Inc. v.
Grokster, Ltd*., 545 U.S. 913, 930, 125 S. Ct. 2764, 162 L. Ed. 2d 781 (2005).
MDY is liable for vicarious infringement if it (1) has the right and ability to
control Glider users' putatively infringing activity and (2) derives a direct
financial benefit from their activity. *Id*. If Glider users directly infringe,
MDY does not dispute that it satisfies the other elements of contributory and
vicarious infringement.

As a copyright owner, Blizzard possesses the exclusive right to reproduce its
work. 17 U.S.C. § 106(1). The parties agree that when playing WoW, a player's
computer creates a copy of the game's software in the computer's random access
memory ("RAM"), a form of temporary memory used by computers to run software
programs. This copy potentially infringes unless the player (1) is a licensee
whose use of the software is within the scope of the license or (2) owns the
copy of the software. *See Sun Microsystems, Inc. v. Microsoft Corp*., 188 F.3d
1115, 1121 (9th Cir. 1999) ("*Sun I*"); 17 U.S.C. § 117(a). As to the scope of
the license, ToU § 4(B), "Limitations on Your Use of the Service," provides:

You agree that you will not . . . (ii) create or use cheats, bots, "mods,"
and/or hacks, or any other third-party software designed to modify the World of
Warcraft experience; or (iii) use any third-party software that intercepts,
"mines," or otherwise collects information from or through the Program or
Service.

By contrast, if the player owns the copy of the software, the "essential step"
defense provides that the player does not infringe by making a copy of the
computer program where the copy is created and used solely "as an essential step
in the utilization of the computer program in conjunction with a machine." 17
U.S.C. § 117(a)(1).

<span style="text-decoration:underline;">A. Essential step defense</span>

We consider whether WoW players, including Glider users, are owners or licensees
of their copies of WoW software. If WoW players own their copies, as MDY
contends, then Glider users do not infringe by reproducing WoW software in RAM
while playing, and MDY is not secondarily liable for copyright infringement.

In *Vernor v. Autodesk, Inc*., we recently distinguished between "owners" and
"licensees" of copies for purposes of the essential step defense. *Vernor v.
Autodesk, Inc*., 621 F.3d 1102, 1108-09 (9th Cir. 2010; *see also MAI Sys. Corp.
v. Peak Computer, Inc*., 991 F.2d 511, 519 n.5 (9th Cir. 1993); *Triad Sys.
Corp. v. Se. Express Co*., 64 F.3d 1330, 1333, 1335-36 (9th Cir. 1995); *Wall
Data, Inc. v. Los Angeles County Sheriff's Dep't*, 447 F.3d 769, 784-85 (9th
Cir. 2006). In *Vernor*, we held "that* *a software user is a licensee rather
than an owner of a copy where the copyright owner (1) specifies that the user is
granted a license; (2) significantly restricts the user's ability to transfer
the software; and (3) imposes notable use" restrictions. 621 F.3d at 1111
(internal footnote omitted).

Applying *Vernor*, we hold that WoW players are licensees of WoW's game client
software. Blizzard reserves title in the software and grants players a
non-exclusive, limited license. Blizzard also imposes transfer restrictions if a
player seeks to transfer the license: the player must (1) transfer all original
packaging and documentation; (2) permanently delete all of the copies and
installation of the game client; and (3) transfer only to a recipient who
accepts the EULA. A player may not sell or give away the account.

Blizzard also imposes a variety of use restrictions. The game must be used only
for non-commercial entertainment purposes and may not be used in cyber cafes and
computer gaming centers without Blizzard's permission. Players may not
concurrently use unauthorized third-party programs. Also, Blizzard may alter the
game client itself remotely without a player's knowledge or permission, and may
terminate the EULA and ToU if players violate their terms. Termination ends a
player's license to access and play WoW. Following termination, players must
immediately destroy their copies of the game and uninstall the game client from
their computers, but need not return the software to Blizzard.

Since WoW players, including Glider users, do not own their copies of the
software, Glider users may not claim the essential step defense. 17 U.S.C. §
117(a)(1). Thus, when their computers copy WoW software into RAM, the players
may infringe unless their usage is within the scope of Blizzard's limited
license.

<span style="text-decoration:underline;">B. Contractual covenants vs. license
conditions</span>

"A copyright owner who grants a nonexclusive, limited license ordinarily waives
the right to sue licensees for copyright infringement, and it may sue only for
breach of contract." *Sun I*, 188 F.3d at 1121 (internal quotations omitted).
However, if the licensee acts outside the scope of the license, the licensor may
sue for copyright infringement. *Id*. (citing *S.O.S., Inc. v. Payday, Inc*.,
886 F.2d 1081, 1087 (9th Cir. 1989)). Enforcing a copyright license "raises
issues that lie at the intersection of copyright and contract law." *Id*. at
1122.

We refer to contractual terms that limit a license's scope as "conditions," the
breach of which constitute copyright infringement. *Id*. at 1120. We refer to
all other license terms as "covenants," the breach of which is actionable only
under contract law. *Id*. We distinguish between conditions and covenants
according to state contract law, to the extent consistent with federal copyright
law and policy. *Foad Consulting Group v. Musil Govan Azzalino*, 270 F.3d 821,
827 (9th Cir. 2001).

A Glider user commits copyright infringement by playing WoW while violating a
ToU term that is a license condition. To establish copyright infringement, then,
Blizzard must demonstrate that the violated term — ToU § 4(B) — is a condition
rather than a covenant. *Sun I*, 188 F.3d at 1122. Blizzard's EULAs and ToUs
provide that they are to be interpreted according to Delaware law. Accordingly,
we first construe them under Delaware law, and then evaluate whether that
construction is consistent with federal copyright law and policy.

A covenant is a contractual promise, i.e., a manifestation of intention to act
or refrain from acting in a particular way, such that the promisee is justified
in understanding that the promisor has made a commitment. *See Travel Centers of
Am. LLC v. Brog*, No. 3751-CC, 2008 Del. Ch. LEXIS 183, *9 (Del. Ch. Dec. 5,
2008); *see also* Restatement (Second) of Contracts § 2 (1981). A condition
precedent is an act or event that must occur before a duty to perform a promise
arises. *AES P.R., L.P. v. Alstom Power, Inc*., 429 F. Supp. 2d 713, 717 (D.
Del. 2006) (citing Delaware state law); *see also* Restatement (Second) of
Contracts § 224. Conditions precedent are disfavored because they tend to work
forfeitures. *AES*, 429 F. Supp. 2d at 717 (internal citations omitted).
Wherever possible, equity construes ambiguous contract provisions as covenants
rather than conditions. See* Wilmington Tr. Co. v. Clark*, 325 A.2d 383, 386
(Del. Ch. 1974). However, if the contract is unambiguous, the court construes it
according to its terms. *AES*, 429 F. Supp. 2d at 717 (citing 17 Am. Jur. 2d
Contracts § 460 (2006)).

Applying these principles, ToU § 4(B)(ii) and (iii)'s prohibitions against bots
and unauthorized third-party software are covenants rather than
copyright-enforceable conditions. *See Greenwood v. CompuCredit Corp*., 615 F.3d
1204, 1212, (9th Cir. 2010) ("[H]eadings and titles are not meant to take the
place of the detailed provisions of the text," and . . . "the heading of a
section cannot limit the plain meaning of the text." (quoting *Bhd. of R.R.
Trainmen v. Balt. & Ohio R.R*., 331 U.S. 519, 528-29, 67 S. Ct. 1387, 91 L. Ed.
1646 (1947))). Although ToU § 4 is titled, "Limitations on Your Use of the
Service," nothing in that section conditions Blizzard's grant of a limited
license on players' compliance with ToU § 4's restrictions. To the extent that
the title introduces any ambiguity, under Delaware law, ToU § 4(B) is not a
condition, but is a contractual covenant. *Cf. Sun Microsystems, Inc. v.
Microsoft Corp*., 81 F. Supp. 2d 1026, 1031-32 (N.D. Cal. 2000) ("*Sun II*")
(where Sun licensed Microsoft to create only derivative works compatible with
other Sun software, Microsoft's "compatibility obligations" were covenants
because the license was not specifically conditioned on their fulfillment).

To recover for copyright infringement based on breach of a license agreement,
(1) the copying must exceed the scope of the defendant's license and (2) the
copyright owner's complaint must be grounded in an exclusive right of copyright
(e.g., unlawful reproduction or distribution). *See Storage Tech. Corp. v.
Custom Hardware Eng'g & Consulting, Inc*., 421 F.3d 1307, 1315-16 (Fed. Cir.
2005). Contractual rights, however, can be much broader:

[C]onsider a license in which the copyright owner grants a person the right to
make one and only one copy of a book with the caveat that the licensee may not
read the last ten pages. Obviously, a licensee who made a hundred copies of the
book would be liable for copyright infringement because the copying would
violate the Copyright Act's prohibition on reproduction and would exceed the
scope of the license. Alternatively, if the licensee made a single copy of the
book, but read the last ten pages, the only cause of action would be for breach
of contract, because reading a book does not violate any right protected by
copyright law.

*Id*. at 1316. Consistent with this approach, we have held that* *the potential
for infringement exists only where the licensee's action (1) exceeds the
license's scope (2) in a manner that implicates one of the licensor's exclusive
statutory rights. *See, e.g., Sun I*, 118 F.3d at 1121-22 (remanding for
infringement determination where defendant allegedly violated a license term
regulating the creation of derivative works).[^23]

Here, ToU § 4 contains certain restrictions that are grounded in Blizzard's
exclusive rights of copyright and other restrictions that are not. For instance,
ToU § 4(D) forbids creation of derivative works based on WoW without Blizzard's
consent. A player who violates this prohibition would exceed the scope of her
license and violate one of Blizzard's exclusive rights under the Copyright Act.
In contrast, ToU § 4(C)(ii) prohibits a player's disruption of another player's
game experience. *Id*. A player might violate this prohibition while playing the
game by harassing another player with unsolicited instant messages. Although
this conduct may violate the contractual covenants with Blizzard, it would not
violate any of Blizzard's exclusive rights of copyright. The anti-bot provisions
at issue in this case, ToU § 4(B)(ii) and (iii), are similarly covenants rather
than conditions. A Glider user violates the covenants with Blizzard, but does
not thereby commit copyright infringement because Glider does not infringe any
of Blizzard's exclusive rights. For instance, the use does not alter or copy WoW
software.

Were we to hold otherwise, Blizzard — or any software copyright holder — could
designate any disfavored conduct during software use as copyright infringement,
by purporting to condition the license on the player's abstention from the
disfavored conduct. The rationale would be that because the conduct occurs while
the player's computer is copying the software code into RAM in order for it to
run, the violation is copyright infringement. This would allow software
copyright owners far greater rights than Congress has generally conferred on
copyright owners.[^24]

We conclude that for a licensee's violation of a contract to constitute
copyright infringement, there must be a nexus between the condition and the
licensor's exclusive rights of copyright.[^25] Here, WoW players do not commit
copyright infringement by using Glider in violation of the ToU. MDY is thus not
liable for secondary copyright infringement, which requires the existence of
direct copyright infringement. *Grokster*, 545 U.S. at 930.

It follows that because MDY does not infringe Blizzard's copyrights, we need not
resolve MDY's contention that Blizzard commits copyright misuse. Copyright
misuse is an equitable defense to copyright infringement, the contours of which
are still being defined. *See Practice Mgmt. Info. Corp. v. Am. Med. Ass'n*, 121
F.3d 516, 520 (9th Cir. 1997). The remedy for copyright misuse is to deny the
copyright holder the right to enforce its copyright during the period of misuse.
Since MDY does not infringe, we do not consider whether Blizzard committed
copyright misuse.

We thus reverse the district court's grant of summary judgment to Blizzard on
its secondary copyright infringement claims. Accordingly, we must also vacate
the portion of the district court's permanent injunction that barred MDY and
Donnelly from "infringing, or contributing to the infringement of, Blizzard's
copyrights in WoW software."

[...]

#### Discussion

1.  *MDY* provides the Ninth Circuit's test for determining whether a licensee's
    breach of a copyright license will give rise to claims for copyright
    infringement. See *[MDY Indus., LLC v. Blizzard Entm't, Inc., 629 F.3d 928,
    940-41 (9th Cir.
    2010)](https://advance.lexis.com/api/document/collection/cases/id/51PJ-CY71-652R-8004-00000-00?page=940&reporter=1107&context=1000516)*
    ("[T]he potential for infringement exists only where the licensee's action
    (1) exceeds the license's scope (2) in a manner that implicates one of the
    licensor's exclusive statutory rights. [...] [F]or a licensee's violation of
    a contract to constitute copyright infringement, there must be a nexus
    between the condition and the licensor's exclusive rights of copyright.").

2.  Both the Ninth Circuit in *MDY* and the Federal Circuit in *Jacobsen* rely
    on the following holdings from *Sun I*: (1) a licensee must act outside the
    scope of a copyright license in order to be liable for copyright
    infringement, and (2) a copyright license's terms must be distinguished as
    either covenants or limitations on the scope of the license. Are the Ninth
    Circuit and the Federal Circuit both reading *Sun I* the same way?

3.  Are the *Jacobsen* "covenant vs. condition" and the *MDY* "nexus" tests in
    conflict? Is *MDY*'s expansion of the test to require a nexus between the
    breached condition and an exclusive right of copyright necessary in order to
    avoid absurd results? See *[MDY Indus., LLC v. Blizzard Entm't, Inc., 629
    F.3d 928, 941 (9th Cir.
    2010)](https://advance.lexis.com/api/document/collection/cases/id/51PJ-CY71-652R-8004-00000-00?page=941&reporter=1107&context=1000516)*
    ("Were we to hold otherwise, Blizzard — or any software copyright holder —
    could designate any disfavored conduct during software use as copyright
    infringement, by purporting to condition the license on the player's
    abstention from the disfavored conduct. The rationale would be that because
    the conduct occurs while the player's computer is copying the software code
    into RAM in order for it to run, the violation is copyright infringement.
    This would allow software copyright owners far greater rights than Congress
    has generally conferred on copyright owners.")

4.  Does the Ninth Circuit's recognition of a "distinct nexus between payment
    and all commercial copyright licenses" break the *MDY* test? How does this
    reconcile with Jacobsen's acknowledgement of the economic benefit conferred
    by an open source licensing scheme? See *[Jacobsen v. Katzer, 535 F.3d 1373,
    1382 (Fed. Cir.
    2008)](https://advance.lexis.com/api/document/collection/cases/id/4T6V-54Y0-TX4N-G15K-00000-00?page=1382&reporter=1107&context=1000516)*
    ("The clear language of the Artistic License creates conditions to protect
    the economic rights at issue in the granting of a public license. These
    conditions govern the rights to modify and distribute the computer programs
    and files included in the downloadable software package. The attribution and
    modification transparency requirements directly serve to drive traffic to
    the open source incubation page and to inform downstream users of the
    project, which is a significant economic goal of the copyright holder that
    the law will enforce.").

5.  In Jacobsen, the Federal Circuit held that certain terms of the Artistic
    License should be regarded as conditions: the requirement that licensees
    "duplicate all of the original copyright notices and associated
    disclaimers," and the requirement that modifiers of the software insert
    "prominent notices in each changed file stating how and when you changed
    that file."[^26] Would a court applying *MDY's* nexus test* *find that these
    conditions of the artistic license bear a nexus to the licensor's exclusive
    rights of copyright? If so, which rights? See 17 U.S.C. § 106(2) (exclusive
    right to prepare derivative works); and see [17 U.S.C. §§ 1202 (b)(1) and
    -(c)(1) (prohibiting removal of copyright management
    information](https://advance.lexis.com/api/document/collection/statutes-legislation/id/4YF7-GKH1-NRF4-40GT-00000-00?context=1000516)
    and defining copyright management information to comprise copyright
    notices).

6.  What, aside from breach of contractual conditions, will constitute actions
    outside the scope of a copyright license? See *[Storage Tech. Corp. v.
    Custom Hardware Eng'g & Consulting, Inc., 421 F.3d 1307, 1315-16 (Fed. Cir.
    2005)](https://advance.lexis.com/search/?pdmfid=1000516&crid=225f26f3-3466-4cfb-9ed3-dc86b1e7ecfe&pdsearchterms=MDY+Indus.%2C+LLC+v.+Blizzard+Entm%27t%2C+Inc.%2C+629+F.3d+928&pdstartin=hlct%3A1%3A1&pdtypeofsearch=searchboxclick&pdsearchtype=SearchBox&pdqttype=and&pdpsf=&ecomp=9t_t9kk&earg=pdpsf&prid=05631962-2c5f-4891-b19a-2340843af7db#)*
    ("[C]onsider a license in which the copyright owner grants a person the
    right to make one and only one copy of a book with the caveat that the
    licensee may not read the last ten pages. Obviously, a licensee who made a
    hundred copies of the book would be liable for copyright infringement
    because the copying would violate the Copyright Act's prohibition on
    reproduction and would exceed the scope of the license. Alternatively, if
    the licensee made a single copy of the book, but read the last ten pages,
    the only cause of action would be for breach of contract, because reading a
    book does not violate any right protected by copyright law.").

    What other kinds of complaints are grounded in an exclusive right of
    copyright? See* [Adobe Sys. v. A & S Elecs., Inc., 153 F. Supp. 3d 1136,
    1144 (N.D. Cal.
    2015)](https://advance.lexis.com/api/document/collection/cases/id/5HRG-4JP1-F04C-T0BK-00000-00?page=1144&reporter=1121&context=1000516)*
    (finding that defendant exceeded scope of license and committed copyright
    infringement by selling CD keys - non-copyright protected 25-digit numbers -
    which facilitated the sale and use of software that defendant had no right
    to distribute).

7.  Suppose a Licensor were to permit a Licensee to create derivative works of
    the Licensor's program, provided that Licensee not sell any copies. What
    happens if Licensee owns a single, lawfully made copy of Licensor's program
    and sells it on eBay? Does the first sale doctrine overcome the nexus
    between the breached condition and the Licensor's exclusive rights of
    copyright if the exclusive right at issue is exhausted? See *[Kirtsaeng v.
    John Wiley & Sons, Inc., 133 S. Ct. 1351, 1374
    (2013)](https://advance.lexis.com/api/document/collection/cases/id/580N-WHV1-F04K-F1PY-00000-00?page=1374&reporter=1990&context=1000516)*;
    [17 U.S.C.S. §
    109](https://advance.lexis.com/api/document/collection/statutes-legislation/id/4YF7-GJT1-NRF4-43YX-00000-00?context=1000516).

## Common open source license terms: Covenants or Conditions?

*Jacobsen* and *MDY* provide possible frameworks for evaluating whether breach
of a copyright license will be regarded as copyright infringement or breach of
contract alone. How would courts apply these tests to the terms of common open
source licenses? This section will highlight a few terms from popular open
source licenses to emphasize the importance of this test in the world of open
source licensing.

### The MIT License

--------------------------------------------------------------------------------

Copyright (c) <year> <copyright holders>

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

#### Discussion

1.  What terms MIT license that could be considered covenants or conditions?
    Would the Jacobsen court regard the requirement that licensees include the
    copyright notice in all copies or portions of the software to be a
    condition? Is there a connection between this term and an economic interest
    of the licensor?

2.  Applying the *MDY* test, is there an essential nexus between the MIT
    license's notice reproduction requirement and one of the exclusive rights of
    copyright? Has the Digital Millennium Copyright Act expanded the exclusive
    rights of copyright? See Infra, *MDY* Discussion, point 5.

### The GPL v.2

--------------------------------------------------------------------------------

[...]

1.  This License applies to any program or other work which contains a notice
    placed by the copyright holder saying it may be distributed under the terms
    of this General Public License. The "Program", below, refers to any such
    program or work, and a "work based on the Program" means either the Program
    or any derivative work under copyright law: that is to say, a work
    containing the Program or a portion of it, either verbatim or with
    modifications and/or translated into another language. (Hereinafter,
    translation is included without limitation in the term "modification".) Each
    licensee is addressed as "you".

2.  You may modify your copy or copies of the Program or any portion of it, thus
    forming a work based on the Program, and copy and distribute such
    modifications or work under the terms of Section 1 above, provided that you
    also meet all of these conditions:

[...]

b) You must cause any work that you distribute or publish, that in whole or in
part contains or is derived from the Program or any part thereof, to be licensed
as a whole at no charge to all third parties under the terms of this License.

These requirements apply to the modified work as a whole. If identifiable
sections of that work are not derived from the Program, and can be reasonably
considered independent and separate works in themselves, then this License, and
its terms, do not apply to those sections when you distribute them as separate
works. But when you distribute the same sections as part of a whole which is a
work based on the Program, the distribution of the whole must be on the terms of
this License, whose permissions for other licensees extend to the entire whole,
and thus to each and every part regardless of who wrote it.

1.  You may copy and distribute the Program (or a work based on it, under
    Section 2) in object code or executable form under the terms of Sections 1
    and 2 above provided that you also do one of the following:

a) Accompany it with the complete corresponding machine-readable source code,
which must be distributed under the terms of Sections 1 and 2 above on a medium
customarily used for software interchange; or,

b) Accompany it with a written offer, valid for at least three years, to give
any third party, for a charge no more than your cost of physically performing
source distribution, a complete machine-readable copy of the corresponding
source code, to be distributed under the terms of Sections 1 and 2 above on a
medium customarily used for software interchange; or,

c) Accompany it with the information you received as to the offer to distribute
corresponding source code. (This alternative is allowed only for noncommercial
distribution and only if you received the program in object code or executable
form with such an offer, in accord with Subsection b above.)

The source code for a work means the preferred form of the work for making
modifications to it. For an executable work, complete source code means all the
source code for all modules it contains, plus any associated interface
definition files, plus the scripts used to control compilation and installation
of the executable.

[...]

#### Discussion

1.  Is Section 2 requirement that independent and separate works, when combined
    with GPL v.2-licensed code to form a larger whole, must be licensed under
    the GPL v.2, a covenant or a condition? How about the Section 3 requirement
    that distribution of any GPL v.2-licensed code in binary form (as an
    executable program or as part of an executable program) be accompanied with
    distribution of the complete source code for the entire binary? See* *Infra,
    *Jacobsen* Discussion, point 2.

2.  Does the re-licensing requirement in Section 2 have a nexus to the
    licensor's exclusive rights of copyright? How about the source-mirroring
    requirement in Section 3? See *[Versata Software, Inc. v. Ameriprise Fin.,
    Inc., No. A-14-CA-12-SS, 2014 U.S. Dist. LEXIS 30934, at *14-15 (W.D. Tex.
    Mar. 10,
    2014)](https://advance.lexis.com/api/document/collection/cases/id/5BPT-NC51-F04F-C00V-00000-00?page=14&reporter=1293&context=1000516)*
    ("The 'viral' component of the GPL is separate and distinct from any
    copyright obligation. Copyright law imposes no open source obligations, and
    Ameriprise has not sued Versata for infringing XimpleWare's copyright by
    distributing VTD-XML without permission. Instead, Ameriprise has sued based
    on Versata's breach of an additional obligation: an affirmative promise to
    make its derivative work open source because it incorporated an open source
    program into its software. Ameriprise's claim therefore requires an 'extra
    element' in addition to reproduction or distribution: a failure to disclose
    the source code of the derivative software.").

3.  Do the GPLv2's relicensing terms govern derivative works alone, or is the
    requirement broader, extending to works that would not be considered
    derivative works under copyright law? See 7 Wash J.L. Tech. & Arts 265, 271
    (2012) ("[T]he reference in Section 2(b) to a "work that in whole or in part
    contains . . . the Program," could be construed as including any work that
    incorporates code from the Program, no matter how insignificant and with no
    regard to whether the included code would be protectable under the Copyright
    Act."). If the re-licensing requirement is intended to apply to works that
    are not derivative works, could the requirement still be a condition? Would
    it still have a nexus to the licensor's exclusive rights of copyright?

### The GPL v.3

[...]

1.  Protecting Users' Legal Rights From Anti-Circumvention Law.

No covered work shall be deemed part of an effective technological measure under
any applicable law fulfilling obligations under article 11 of the WIPO copyright
treaty adopted on 20 December 1996, or similar laws prohibiting or restricting
circumvention of such measures.

When you convey a covered work, you waive any legal power to forbid
circumvention of technological measures to the extent such circumvention is
effected by exercising rights under this License with respect to the covered
work, and you disclaim any intention to limit operation or modification of the
work as a means of enforcing, against the work's users, your or third parties'
legal rights to forbid circumvention of technological measures. [...]

1.  Termination.

You may not propagate or modify a covered work except as expressly provided
under this License. Any attempt otherwise to propagate or modify it is void, and
will automatically terminate your rights under this License (including any
patent licenses granted under the third paragraph of section 11).

However, if you cease all violation of this License, then your license from a
particular copyright holder is reinstated (a) provisionally, unless and until
the copyright holder explicitly and finally terminates your license, and (b)
permanently, if the copyright holder fails to notify you of the violation by
some reasonable means prior to 60 days after the cessation.

Moreover, your license from a particular copyright holder is reinstated
permanently if the copyright holder notifies you of the violation by some
reasonable means, this is the first time you have received notice of violation
of this License (for any work) from that copyright holder, and you cure the
violation prior to 30 days after your receipt of the notice.

Termination of your rights under this section does not terminate the licenses of
parties who have received copies or rights from you under this License. If your
rights have been terminated and not permanently reinstated, you do not qualify
to receive new licenses for the same material under section 10.

#### Discussion

1.  Read Section 3 of the GPLv3. How would a court apply the MDY and Jacobsen
    tests to a contractual condition bears a nexus to an exclusive right of
    copyright, but not to the licensor's exclusive rights of copyright in the
    copyrighted work being licensed? Could a licensor's expectation interest in
    the scheme of Section 3 be fulfilled without specific performance?

2.  Section 8 of the GPLv3 includes a remedy scheme that permanently reinstates
    a license if a licensee meets the criteria for curing the violation. Does
    the mere existence of this provision require treating all of the GPL's terms
    as covenants rather than conditions? *[Sun Microsystems, Inc. v. Microsoft
    Corp., 81 F. Supp. 2d 1026, 1033 (N.D. Cal.
    2000)](https://advance.lexis.com/api/document/collection/cases/id/3YP8-G380-0038-Y0HN-00000-00?page=1033&reporter=1109&context=1000516)*
    ("If Sun could sue for copyright infringement immediately upon Microsoft's
    failure to fully meet the compatibility requirements, the remedies scheme
    would be frustrated and Microsoft would not get the full benefit of its
    bargained for cure periods.").

<!-- Footnotes themselves at the bottom. -->

## Notes

[^1]: See Infra, The Penalties Compared
[^2]: *[Sun Microsystems, Inc. v. Microsoft Corp., 188 F.3d 1115, 1121 (9th Cir.
    1999)](https://advance.lexis.com/api/document/collection/cases/id/3X7T-TDB0-0038-X066-00000-00?page=1121&reporter=1107&context=1000516)*.

[^3]: Id.
[^4]: Restat 2d of Contracts, § 347.
[^5]: Id. at Comment a.
[^6]: Restat 2d of Contracts, § 345(d).
[^7]: Restat 2d of Contracts, § 359(1).
[^8]: Restat 2d of Contracts, § 355.
[^12]: 17 USC 504(c)(2); See also *[Capitol Records, Inc. v. Thomas-Rasset, 692
    F.3d 899 (8th Cir.
    2012)](https://advance.lexis.com/api/document/collection/cases/id/56JC-B7G1-F04K-S2WM-00000-00?page=901&reporter=1107&context=1000516)*(affirming
    statutory damages award of $222,000; holding the $150,000 statutory cap
    to apply on a 'per work infringed' basis).

[^13]: 17 USC 504(b).
[^14]: 17 USC 502.
[^15]: 17 USC 503(a)(1)(B).
[^16]: 17 USC 505.
[^17]: FN1. Katzer/Kamind represents that all potentially infringing activities
    using any of the disputed material have been voluntarily ceased. The
    district court held that it could not find as a matter of law that
    Katzer/Kamind's voluntary termination of allegedly wrongful activity
    renders the motion for preliminary injunction moot because it could not
    find as a matter of law that it is absolutely clear that the alleged
    behavior could not recur. *[Jacobsen, 2007 U.S. Dist. LEXIS 63568, 2007
    WL 2358628 at
    *5](https://advance.lexis.com/document?crid=fea82229-8d17-4893-b80f-513bb7af0d56&pddocfullpath=%2Fshared%2Fdocument%2Fcases%2Furn%3AcontentItem%3A4T6V-54Y0-TX4N-G15K-00000-00&pdcontentcomponentid=6396&pdpinpoint=PAGE_1375_1107&pdmfid=1000516&pdisurlapi=true#)*.
    We agree that this matter is not moot. See also *[Adarand Constructors,
    Inc. v. Slater, 528 U.S. 216, 222
    (2000)](https://advance.lexis.com/document?crid=fea82229-8d17-4893-b80f-513bb7af0d56&pddocfullpath=%2Fshared%2Fdocument%2Fcases%2Furn%3AcontentItem%3A4T6V-54Y0-TX4N-G15K-00000-00&pdcontentcomponentid=6396&pdpinpoint=PAGE_1375_1107&pdmfid=1000516&pdisurlapi=true#)*
    ("Voluntary cessation of challenged conduct moots a case . . . only if it
    is *absolutely* clear that the allegedly wrongful behavior could not
    reasonably be expected to recur." (emphasis in original)).

[^18]: FN2. For example, the GNU General Public License, which is used for the
    Linux operating system, prohibits downstream users from charging for a
    license to the software. See *Wallace v. IBM Corp.*, 467 F.3d 1104,
    1105-06 (7th Cir.2006).

[^19]: FN3. Jacobsen's copyright registration creates the presumption of a valid
    copyright. See, e.g.,* [Triad Sys. Corp. v. Se. EXP. Co., 64 F.3d 1330,
    1335 (9th Cir.
    1995)](https://advance.lexis.com/document?crid=fea82229-8d17-4893-b80f-513bb7af0d56&pddocfullpath=%2Fshared%2Fdocument%2Fcases%2Furn%3AcontentItem%3A4T6V-54Y0-TX4N-G15K-00000-00&pdcontentcomponentid=6396&pdpinpoint=PAGE_1375_1107&pdmfid=1000516&pdisurlapi=true#)*.

[^20]: FN4. The District Court held that "Defendants' alleged violation of the
    conditions of the license may have constituted a breach of the
    nonexclusive license . . . [and] the Court finds that Plaintiff's claim
    properly sounds in contract." *[Jacobsen, 2007 U.S. Dist. LEXIS 63568,
    2007 WL 2358628 at
    *7](https://advance.lexis.com/document?crid=fea82229-8d17-4893-b80f-513bb7af0d56&pddocfullpath=%2Fshared%2Fdocument%2Fcases%2Furn%3AcontentItem%3A4T6V-54Y0-TX4N-G15K-00000-00&pdcontentcomponentid=6396&pdpinpoint=PAGE_1375_1107&pdmfid=1000516&pdisurlapi=true#)*.
    Thus, despite the use of the word "conditions," the District Court
    treated the terms of the Artistic License as contractual covenants which
    did not limit the scope of the license.

[^21]: FN5. Open source licensing restrictions are easily distinguished from
    mere "author attribution" cases. Copyright law does not automatically
    protect the rights of authors to credit for copyrighted materials. See*
    [Gilliam, 538 F.2d at
    20-21](https://advance.lexis.com/document?crid=fea82229-8d17-4893-b80f-513bb7af0d56&pddocfullpath=%2Fshared%2Fdocument%2Fcases%2Furn%3AcontentItem%3A4T6V-54Y0-TX4N-G15K-00000-00&pdcontentcomponentid=6396&pdpinpoint=PAGE_1375_1107&pdmfid=1000516&pdisurlapi=true#)*
    ("American copyright law, as presently written, does not recognize moral
    rights or provide a cause of action for their violation, since the law
    seeks to vindicate the economic, rather than the personal rights of
    authors."); *[Graham, 144 F.3d at
    236](https://advance.lexis.com/document?crid=fea82229-8d17-4893-b80f-513bb7af0d56&pddocfullpath=%2Fshared%2Fdocument%2Fcases%2Furn%3AcontentItem%3A4T6V-54Y0-TX4N-G15K-00000-00&pdcontentcomponentid=6396&pdpinpoint=PAGE_1375_1107&pdmfid=1000516&pdisurlapi=true#)*.
    Whether such rights are protected by a specific license grant depends on
    the language of the license. See* [County of Ventura v. Blackburn, 362
    F.2d 515, 520 (9th Cir.
    1966)](https://advance.lexis.com/document?crid=fea82229-8d17-4893-b80f-513bb7af0d56&pddocfullpath=%2Fshared%2Fdocument%2Fcases%2Furn%3AcontentItem%3A4T6V-54Y0-TX4N-G15K-00000-00&pdcontentcomponentid=6396&pdpinpoint=PAGE_1375_1107&pdmfid=1000516&pdisurlapi=true#)*
    (copyright infringement found where the county removed copyright notices
    from maps licensed to it where the license granted the county "the right
    to obtain duplicate tracings" from photographic negatives that contained
    copyright notices).

[^22]: FN1. Alternatively, MDY asks that we determine whether there are any
    genuine issues of material fact that warrant a remand for trial on
    Blizzard's secondary copyright infringement claims. We find none.

[^23]: FN2. See also* [S.O.S., 886 F.2d at
    1089](https://advance.lexis.com/document/?pdmfid=1000516&crid=06650db3-0f63-4524-9068-1e89116d90ac&pddocfullpath=%2Fshared%2Fdocument%2Fcases%2Furn%3AcontentItem%3A51PJ-CY71-652R-8004-00000-00&pddocid=urn%3AcontentItem%3A51PJ-CY71-652R-8004-00000-00&pdcontentcomponentid=6393&pdshepid=urn%3AcontentItem%3A51P5-94G1-DXC7-J10H-00000-00&pdteaserkey=sr0&ecomp=r89tk&earg=sr0&prid=029365ab-656c-46c5-a540-be903eb10e58#)*
    (remanding for infringement determination where licensee exceeded the
    license's scope by preparing a modified version of software programs
    without licensor's authorization); *[LGS Architects, Inc. v. Concordia
    Homes, Inc., 434 F.3d 1150, 1154-57 (9th Cir.
    2006)](https://advance.lexis.com/document/?pdmfid=1000516&crid=06650db3-0f63-4524-9068-1e89116d90ac&pddocfullpath=%2Fshared%2Fdocument%2Fcases%2Furn%3AcontentItem%3A51PJ-CY71-652R-8004-00000-00&pddocid=urn%3AcontentItem%3A51PJ-CY71-652R-8004-00000-00&pdcontentcomponentid=6393&pdshepid=urn%3AcontentItem%3A51P5-94G1-DXC7-J10H-00000-00&pdteaserkey=sr0&ecomp=r89tk&earg=sr0&prid=029365ab-656c-46c5-a540-be903eb10e58#)*
    (licensor likely to prove infringement where licensee used architectural
    plans for project outside the license's scope, where licensee's use may
    have included unauthorized reproduction, distribution, and public display
    of the plans); *[Frank Music Corp. v. Metro-Goldwyn-Mayer, Inc., 772 F.2d
    505, 511 (9th Cir.
    1985)](https://advance.lexis.com/document/?pdmfid=1000516&crid=06650db3-0f63-4524-9068-1e89116d90ac&pddocfullpath=%2Fshared%2Fdocument%2Fcases%2Furn%3AcontentItem%3A51PJ-CY71-652R-8004-00000-00&pddocid=urn%3AcontentItem%3A51PJ-CY71-652R-8004-00000-00&pdcontentcomponentid=6393&pdshepid=urn%3AcontentItem%3A51P5-94G1-DXC7-J10H-00000-00&pdteaserkey=sr0&ecomp=r89tk&earg=sr0&prid=029365ab-656c-46c5-a540-be903eb10e58#)*
    (hotel infringed copyright by publicly performing copyrighted music with
    representations of movie scenes, where its public performance license
    expressly prohibited the use of accompanying visual representations).

[^24]: FN3. A copyright holder may wish to enforce violations of license
    agreements as copyright infringements for several reasons. First, breach
    of contract damages are generally limited to the value of the actual loss
    caused by the breach. See 24 Richard A. Lord, *Williston on Contracts* §
    65:1 (4th ed. 2007). In contrast, copyright damages include the copyright
    owner's actual damages and the infringer's actual profits, or statutory
    damages of up to $150,000 per work. [17 U.S.C. §
    504](https://advance.lexis.com/document/?pdmfid=1000516&crid=06650db3-0f63-4524-9068-1e89116d90ac&pddocfullpath=%2Fshared%2Fdocument%2Fcases%2Furn%3AcontentItem%3A51PJ-CY71-652R-8004-00000-00&pddocid=urn%3AcontentItem%3A51PJ-CY71-652R-8004-00000-00&pdcontentcomponentid=6393&pdshepid=urn%3AcontentItem%3A51P5-94G1-DXC7-J10H-00000-00&pdteaserkey=sr0&ecomp=r89tk&earg=sr0&prid=029365ab-656c-46c5-a540-be903eb10e58#);
    see* [Frank Music Corp. v. MGM, Inc., 772 F.2d 505, 512 n.5 (9th Cir.
    1985)](https://advance.lexis.com/document/?pdmfid=1000516&crid=06650db3-0f63-4524-9068-1e89116d90ac&pddocfullpath=%2Fshared%2Fdocument%2Fcases%2Furn%3AcontentItem%3A51PJ-CY71-652R-8004-00000-00&pddocid=urn%3AcontentItem%3A51PJ-CY71-652R-8004-00000-00&pdcontentcomponentid=6393&pdshepid=urn%3AcontentItem%3A51P5-94G1-DXC7-J10H-00000-00&pdteaserkey=sr0&ecomp=r89tk&earg=sr0&prid=029365ab-656c-46c5-a540-be903eb10e58#)*.
    Second, copyright law offers injunctive relief, seizure of infringing
    articles, and awards of costs and attorneys' fees. [17 U.S.C. §§
    502-03](https://advance.lexis.com/document/?pdmfid=1000516&crid=06650db3-0f63-4524-9068-1e89116d90ac&pddocfullpath=%2Fshared%2Fdocument%2Fcases%2Furn%3AcontentItem%3A51PJ-CY71-652R-8004-00000-00&pddocid=urn%3AcontentItem%3A51PJ-CY71-652R-8004-00000-00&pdcontentcomponentid=6393&pdshepid=urn%3AcontentItem%3A51P5-94G1-DXC7-J10H-00000-00&pdteaserkey=sr0&ecomp=r89tk&earg=sr0&prid=029365ab-656c-46c5-a540-be903eb10e58#),
    [505](https://advance.lexis.com/document/?pdmfid=1000516&crid=06650db3-0f63-4524-9068-1e89116d90ac&pddocfullpath=%2Fshared%2Fdocument%2Fcases%2Furn%3AcontentItem%3A51PJ-CY71-652R-8004-00000-00&pddocid=urn%3AcontentItem%3A51PJ-CY71-652R-8004-00000-00&pdcontentcomponentid=6393&pdshepid=urn%3AcontentItem%3A51P5-94G1-DXC7-J10H-00000-00&pdteaserkey=sr0&ecomp=r89tk&earg=sr0&prid=029365ab-656c-46c5-a540-be903eb10e58#).
    Third, as amicus Software & Information Industry Association highlights,
    copyright law allows copyright owners a remedy against "downstream"
    infringers with whom they are not in privity of contract. See* [ProCD,
    Inc., 86 F.3d at
    1454](https://advance.lexis.com/document/?pdmfid=1000516&crid=06650db3-0f63-4524-9068-1e89116d90ac&pddocfullpath=%2Fshared%2Fdocument%2Fcases%2Furn%3AcontentItem%3A51PJ-CY71-652R-8004-00000-00&pddocid=urn%3AcontentItem%3A51PJ-CY71-652R-8004-00000-00&pdcontentcomponentid=6393&pdshepid=urn%3AcontentItem%3A51P5-94G1-DXC7-J10H-00000-00&pdteaserkey=sr0&ecomp=r89tk&earg=sr0&prid=029365ab-656c-46c5-a540-be903eb10e58#)*.

[^25]: FN4. A licensee arguably may commit copyright infringement by continuing
    to use the licensed work while failing to make required payments, even
    though a failure to make payments otherwise lacks a nexus to the
    licensor's exclusive statutory rights. We view payment as *sui generis*,
    however, because of the distinct nexus between payment and all commercial
    copyright licenses, not just those concerning software.

[^26]: https://opensource.org/licenses/artistic-license-1.0
