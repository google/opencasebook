# Trademarks in Open Source
{:.no_toc}

* Table of Contents
{:toc}

## Introduction

Many people have misconceptions about how to license and enforce trademarks -- even some intellectual property attorneys. This chapter will use U.S. case law to illuminate the relationship between open source licenses and trademark rights. This shared basis of understanding should help dispel common trademark licensing and enforcement myths that circulate in discussion boards for open source developers without citation to primary sources. For example, some people believe that releasing a
project under an open source license gives the licensor the right to prevent anyone else from using the name of
the project under any circumstances.[^NominativeDiscussion] Others assume that trademarks can only be enforced if they are formally
registered,[^CommonLawDiscussion] or that trademark rights can be licensed in exactly the same way that copyrights and patents are licensed.

[^NominativeDiscussion]: _See_ discussion _infra_ Fair Use Defense to Trademark
    Infringement.

[^CommonLawDiscussion]: _See_ discussion _infra_ Common Law Trademarks in Open
    Source.

Trademarks serve a different purpose from copyrights and patents and can be licensed differently. Unlike copyright and patent laws, which were designed to incentivize creative
works and useful inventions, trademark law's purpose is to protect consumers by
guaranteeing the source of a product or service.[^LanhamAct] Copyrights and patent rights are property rights, whereas trademarks are fundamentally concerned with consumer protection. As such, an
open source author may choose to openly license her project's copyrights and
patents while still enforcing her trademarks. Trademark enforcement is not
inconsistent with open source principles: it restricts how a brand identifier
can be used, rather than restricting what you can do with the open source code.[^OpenSourcePrinciples] Even Richard Stallman, the founder and
president of the Free Software Foundation, recognizes that trademark enforcement
is reasonable as long as software freedom is not restricted.[^RichardStallman]

[^LanhamAct]: In the United States, copyright and patent laws have a
    Constitutional basis, whereas trademark laws have their basis in
    the Lanham Act. _See Trademark Infringement_, Legal Information
    Institute,
    [https://www.law.cornell.edu/wex/trademark_infringement](https://www.law.cornell.edu/wex/trademark_infringement);
    _see also Overview of Trademark Law_, Berkman Klein Center for
    Internet & Society at Harvard University,
    [http://cyber.harvard.edu/metaschool/fisher/domain/tm.htm](http://cyber.harvard.edu/metaschool/fisher/domain/tm.htm);
    _Intellectual Property Clause_, Legal Information Institute,
    https://www.law.cornell.edu/wex/intellectual_property_clause.
    However, trademarks are commonly understood to be intellectual
    property. _See Black's Law Dictionary_, _Third Pocket Edition_ at
    368 ("1. A category of intangible rights protecting commercially
    valuable products of the human intellect. The category comprises
    primarily trademark, copyright, and patent rights, but also
    includes trade-secret rights, publicity rights, moral rights, and
    rights against unfair competition. 2. A commercially valuable
    product of the human intellect, in a concrete or abstract form,
    such as a copyrightable work, a protectable trademark, a
    patentable invention, or a trade secret."); _see also_ Barlow
    Burke, Ann M. Burkhart & R.H. Helmholz, _Fundamentals of Property
    Law_ 902 (3d ed. 2010) ("Trademark law . . . has much to do with
    holders and consumers' interests in commerce; for that reason, it
    is, among the many types of intellectual property, the least
    property-oriented") (citation omitted).

[^OpenSourcePrinciples]: _See The Open Source Definition_, Open Source
    Initiative,
    [https://opensource.org/osd](https://opensource.org/osd)
    (Principles of Open Source) (CC BY 4.0); _see also Open
    Source Frequently Answered Questions_, Open Source
    Initiative,
    [https://opensource.org/faq](https://opensource.org/faq)
    ("Open Source is about software source code, not about
    identity."); _Trademarks and Free Software_, FOSSmarks,
    [http://fossmarks.org/](http://fossmarks.org/)
    ("Trademarks and FOSS are not incompatible; instead,
    trademarks are legal tools strongly aligned with FOSS
    principles.") (CC BY 4.0).

[^RichardStallman]: When asked for his opinion on trademark enforcement of a
    logo, Stallman responded, "It is no problem if the program
    contains trademarked images and names, and provided that the
    trademark usage and requirements don't make it difficult in
    practice to change the program and publish a modified
    version. In other words, it has to be easy to find and
    remove the trademarks, if and when the trademark conditions
    require this." Richard Stallman, _Re: Issue of Trademark
    Logo Images in Source Distribution, Savannah-hackers,_
    [https://lists.gnu.org/archive/html/savannah-hackers/2004-11/msg00508.html](https://lists.gnu.org/archive/html/savannah-hackers/2004-11/msg00508.html)
    (last visited Dec. 15, 2017); _see also_ Pamela S. Chestek,
    _The Uneasy Role of Trademarks in Free and Open Source
    Software: You Can Share My Code But You Can't Share My
    Brand_, The Trademark Reporter, July-Aug, 2012, Vol. 102 No.
    4 1028, 1036.

How courts have applied the logic and tension of trademark
law in these cases illustrates the nature of trademarks and their rich interplay
with software and technology. The reasoning from these cases is contextualized with discussion questions and an examination of how popular open source licenses have struggled to address trademark rights, as well as several organizations' trademark
policies.

[^FreeExpression]: _See, Playboy Enters. v. Welles_, 279 F.3d 796, 804 (9th Cir.
    2002), _available at_
    [https://scholar.google.com/scholar_case?case=16988495062292324](https://scholar.google.com/scholar_case?case=16988495062292324)
    ("There is simply no descriptive substitute for the
    trademarks used in Welles' metatags. Precluding their use
    would have the unwanted effect of hindering the free flow of
    information on the internet, something which is certainly not
    a goal of trademark law.").

## Cases

### Unmanaged Trademarks: Naked Licensing

When evaluating how to manage your trademarks, consider the default behavior:
what happens if nothing is done to protect a trademark in an open source
project? In this context, "doing nothing" to protect a trademark could mean
choosing a license which explicitly disavows any grant of trademark rights, but
undermining that provision over email by freely allowing anyone to use the
trademark. This type of activity might be seen as an implied license -- or
worse -- naked licensing.

As we will see in the following case's discussion of naked licensing, doing nothing to
control the quality associated with a licensed trademark risks losing the
enforceability of a trademark altogether. _FreecycleSunnyvale v. Freecycle Network_ summarizes the heart of
the issue:[^QualitySymbol]

> [T]rademark owners have a duty to control the quality of their trademarks. It
> is well-established that a trademark owner may grant a license and remain
> protected provided quality control of the goods and services sold under the
> trademark by the licensee is maintained. "Naked licensing" occurs when a
> licensor "fails to exercise adequate quality control over the licensee." Naked
> licensing may result in the trademark's ceasing to function as a symbol of
> quality and a controlled source.

[^QualitySymbol]: _FreecyleSunnyvale v. Freecycle Network_, 626 F.3d 509, 515
    (9th Cir. 2010), _available at_
    http://cdn.ca9.uscourts.gov/datastore/opinions/2010/11/24/08-16382.pdf
    (citation omitted).

Just as with waiving copyright to a work or publishing an invention before
patenting it, overly permissive trademark licensing without quality control
risks diminishing the enforceability of the trademark.

As you read _Freecycle_, consider the open source applications of the court's
analysis of the types of control a licensor may have over licensed trademarks. For
example, what would happen if a project wishes to explicitly permit the use of the project's trademarks in some circumstances? How could the licensor maintain contractual or actual control?

When crafting a trademark enforcement strategy consider what the value of a trademark could be to your open source project. Does the unique brand of the project attract contributions or bolster widespread adoption? How much of a priority is the unique identity of the project to the core contributors? Would the project want to retain exclusive rights to certify compliant sub-projects or sell project-related merchandise? The value
of a trademark can vary from project to project.

Although the _Freecycle_ case does not concern software, The Freecycle Network's structure of
loose franchising arrangements was central to the holding and could be analogous
to many open source collaborations. The Freecycle Network leveraged online communities to
unite passionate contributors around a shared goal, progressing with a
democratized structure and little apparent interest in trademark protection. Due to the organization's lack
of contractual or actual control over the quality associated with the use of the term "Freecycle," the Court held that The Freecycle Network had engaged in naked licensing and abandoned its trademarks.

#### FreecycleSunnyvale v. Freecycle Network

--------------------------------------------------------------------------------

626 F.3d 509 (9th Cir. 2010)[^FreecycleHeadnote]

[^FreecycleHeadnote]: _FreecyleSunnyvale v. Freecycle Network_, 626 F.3d 509
    (9th Cir. 2010), _available at_
    http://cdn.ca9.uscourts.gov/datastore/opinions/2010/11/24/08-16382.pdf

CALLAHAN, Circuit Judge:

FreecycleSunnyvale ("FS") is a member group of The Freecycle Network ("TFN"), an
organization devoted to facilitating the recycling of goods. FS filed a
declaratory action against TFN arising from a trademark licensing dispute,
alleging noninfringement of TFN's trademarks and tortious interference with FS's
business relations. FS moved for partial summary judgment on the issue of
whether its naked licensing defense to trademark infringement allowed it to
avoid a finding of infringement as a matter of law.[^SummaryJudgment] TFN argued
that it had established adequate quality control standards over its licensees'
services and use of the trademarks to avoid a finding of naked licensing and
abandonment of its trademarks. The district court granted summary judgment to
FS. We hold that TFN (1) did not retain express contractual control over FS's
quality control measures, (2) did not have actual controls over FS's quality
control measures, and (3) was unreasonable in relying on FS's quality control
measures. Because we find that TFN engaged in naked licensing and thereby
abandoned its trademarks, we affirm.

[^SummaryJudgment]: Naked licensing occurs when a licensor does not exercise
    adequate quality control over its licensee's use of a
    licensed trademark such that the trademark may no longer
    represent the quality of the product or service the consumer
    has come to expect. _See Barcamerica Int'l USA Trust v.
    Tyfield Importers, Inc_., 289 F.3d 589, 595-96 (9th Cir.
    2002). By not enforcing the terms of the trademark's use,
    the licensor may forfeit his rights to enforce the exclusive
    nature of the trademark. The key question is therefore
    whether TFN produced any evidence to raise a material fact
    issue as to whether it: (1) retained contractual rights to
    control the quality of the use of its trademark; (2)
    actually controlled the quality of the trademark's use; or
    (3) reasonably relied on FS to maintain the quality.
    _Barcamerica_, 289 F.3d at 596-98 (upholding trademarks
    where a licensor is familiar with the licensee and
    reasonably relies on the licensee's own quality control

I

A

In March 2003, Deron Beal ("Beal") founded TFN, an umbrella non-profit Arizona
corporation dedicated to "freecycling." The term "freecycling" combines the
words "free" and "recycling" and refers to the practice of giving an unwanted
item to a stranger so that it can continue to be used for its intended purpose,
rather than disposing of it.[^FreecyclingVocab] As practiced by TFN, freecycling
is primarily a local activity conducted by means of internet groups, which are
created by volunteers through online service providers like Yahoo! Groups and
Google Groups.[^YahooGroups] Although not required to do so, most TFN member
groups use Yahoo! Groups as a forum for members to coordinate their freecycling
activities. TFN also maintains its own website, www.freecycle.org, which
provides a directory of member groups as well as resources for volunteers to
create new groups. The website also includes a section devoted to etiquette
guidelines.

[^FreecyclingVocab]: Beal did not coin the word "freecycle" and TFN is not the
    first organization to promote freecycling.

[^YahooGroups]: In general, online discussion groups such as Yahoo! Groups and
    Google Groups allow individuals with a shared common interest to
    communicate by means of posting messages to the particular
    group's online forum. Such groups may be subject to terms and
    conditions of the service provider. In addition, discussion
    groups often have volunteer group moderators who monitor the
    discussions, and each group may adopt and enforce rules and
    regulations (e.g., discussion etiquette) separate from whatever
    terms the online service provider imposes.

TFN asserts that it maintains a "Freecycle Ethos"—a democratic leadership
structure, in which decisions are made through a process of surveys and
discussions among volunteer moderators. Local volunteer moderators are
responsible for enforcing TFN's rules and policies, but the moderators have
flexibility in enforcement depending on the moderators' assessment of their
local communities.

Since May 2003, TFN has been using three trademarks, FREECYCLE, THE FREECYCLE
NETWORK, and a logo (collectively "the trademarks") to identify TFN's services
and to identify member groups' affiliation with TFN. Federal registration of the
trademarks is currently pending in the United States, but the trademarks have
been registered in other countries. TFN permits member groups to use the
trademarks. When TFN first started, Beal personally regulated the use of the
trademarks but, as TFN has grown, it has relied on local moderators to regulate
member groups' use of the trademarks.

Lisanne Abraham ("Abraham") founded FS on October 7, 2003, in Sunnyvale,
California, without TFN's knowledge or involvement. She established the group by
entering into a service contract with Yahoo! Groups and becoming the group's
moderator. Upon establishing FS, Abraham adapted etiquette guidelines and
instructions for how to use FS from either TFN's or one of TFN's member group's
website. On October 7, 2003, Abraham emailed Beal directly asking for a logo for
FS, and they spoke over the phone within days of the email communication. After
the phone conversation, Beal emailed Abraham on October 9, 2003, stating: "You
can get the neutral logo from www.freecycle.org, just don't use it for
commercial purposes or you [sic] maybe Mark or Albert can help you to do your
own fancy schmancy logo!"[^12] This email is the only record of a direct
communication between FS and TFN regarding the use of any of the trademarks.

[^12]: Mark Messinger is the moderator for the Olympia, Washington, freecycle
    group. He helped Abraham fashion a unique freecycle logo for Sunnyvale.
    Albert Kaufman apparently introduced Abraham to freecycling.

Between October 7, 2003, and October 9, 2003, FS was added to TFN's list of
online freecycling groups displayed on TFN's website. Then, on October 9, 2003,
Abraham received an email from Beal addressed to nineteen moderators of new
freecycle Yahoo! Groups which, among other things, welcomed them to TFN. The
email did not discuss or include any restrictions or guidance on the use of
TFN's trademarks. On October 13, 2003, Abraham received another email from TFN,
this time an invitation to join the "freecyclemodsquad" Yahoo! Group ("modsquad
group"), an informal discussion forum exclusively for the moderators of
freecycle Yahoo! Groups to share ideas.

Before 2004, TFN had only a few suggested guidelines in the etiquette section of
its website, including a "Keep it Free" rule. Then, on January 4, 2004, Beal
sent an email to the modsquad group, asking whether TFN should also limit listed
items to those that were legal. Ultimately, Beal proposed the adoption of a
"Keep it Free, Legal & Appropriate for All Ages" rule and asked "that all
moderators vote on whether they feel this is the one rule that should apply to
ALL local groups or not." Between January 4 and January 11, 2004, a majority of
the modsquad group voted to require all local groups to adopt the rule and, on
January 11, Beal informed the group that "I'm glad to say . . . we now have one
true guiding principle." Although the moderators adopted the "Keep it Free,
Legal & Appropriate for All Ages" rule, following its adoption, they frequently
discussed what the actual meaning of the rule was and, ultimately, its
definition and enforcement varied from group to group.

Although the underlying reason is not evident from the record or the parties'
briefs, on November 1 and November 14, 2005, TFN sent emails to FS ordering the
group to cease and desist using the Freecycle name and logo and threatening to
have Yahoo! terminate FS's Yahoo! Group if FS did not comply. On November 5, FS
emailed Yahoo! and disputed TFN's ability to forbid the use of the trademarks by
informing Yahoo! of the license that TFN allegedly had granted FS in October
2003 (i.e., Beal's October 9, 2003 email authorizing Abraham to use the logo).
On November 21, Yahoo! terminated the FS Yahoo! Group at TFN's request, after
receiving a claim from TFN that FS was infringing on TFN's trademark rights.

B

On January 18, 2006, FS filed a declaratory judgment action against TFN in the
U.S. District Court for the Northern District of California, alleging
noninfringement of TFN's trademarks and tortious interference with FS's business
relations. TFN brought counterclaims for trademark infringement and unfair
competition under the Lanham Act and California Business and Professions Code
section 17200.

FS then moved for summary judgment on the issue of whether its naked licensing
defense to trademark infringement allowed it to avoid a finding of infringement
as a matter of law. FS argued that TFN had abandoned its trademarks because it
engaged in naked licensing when it granted FS the right to use the trademarks
without either (1) the right to control or (2) the exercise of actual control
over FS's activities. On March 13, 2008, the district court granted summary
judgment in favor of FS, holding that TFN engaged in naked licensing and
therefore abandoned its rights to the trademarks. The parties stipulated to
dismiss the remaining claims, and final judgment was entered on May 20, 2008.
TFN thereafter timely filed its appeal.

II

[. . . .]

Here, we need not decide which standard of proof applies because, even applying
the higher standard of proof—clear and convincing—and viewing the evidence in
the light most favorable to TFN as the non-moving party, FS has demonstrated
that TFN engaged in naked licensing and consequently abandoned the trademarks.

III

An introduction to "naked licensing" of trademarks is in order, as this issue
has seldom arisen in this circuit or in our sister circuits. Our only discussion
of this subject is in _Barcamerica_, 289 F.3d at 598 (holding that Barcamerica,
a vintner, engaged in naked licensing and abandoned its trademark by failing to
retain or otherwise exercise adequate quality control over the trademark it had
licensed to another company), and that decision informs and guides our
discussion here.

As a general matter, trademark owners have a duty to control the quality of
their trademarks. McCarthy § 18:48. "It is well-established that '[a] trademark
owner may grant a license and remain protected provided quality control of the
goods and services sold under the trademark by the licensee is maintained.' "
_Barcamerica_, 289 F.3d at 595-96 (quoting _Moore Bus. Forms, Inc. v. Ryu_, 960
F.2d 486, 489 (5th Cir. 1992)).

"Naked licensing" occurs when the licensor "fails to exercise adequate quality
control over the licensee." _Id._ at 596. Naked licensing may result in the
trademark's ceasing to function as a symbol of quality and a controlled source.
_Id._ (citing McCarthy § 18:48). We have previously declared that naked
licensing is \"_inherently deceptive_ and constitutes abandonment of any rights
to the trademark by the licensor." _Id._ at 598. "Consequently, where the
licensor fails to exercise adequate quality control over the licensee, 'a court
may find that the trademark owner has abandoned the trademark, in which case the
owner would be estopped from asserting rights to the trademark.'" _Id._ at 596
(quoting _Moore_, 960 F.2d at 489).

A

At issue here is whether there is clear and convincing evidence, viewed in the
light most favorable to TFN, that TFN allowed FS to use the trademarks with so
few restrictions as to compel a finding that TFN engaged in naked licensing and
abandoned the trademarks. TFN contends that disputed issues of material fact
remain as to whether TFN's quality control standards, during the relevant time
period, were sufficient. Although TFN concedes that it did not have an express
license agreement, it alleges that a reasonable jury could find that it had
adequate quality control measures in place when FS was authorized to use the
trademarks, making summary judgment inappropriate.

1

When deciding summary judgment on claims of naked licensing, we first determine
whether the license contained an express contractual right to inspect and
supervise the licensee's operations. _See Barcamerica_, 289 F.3d at 596. The
absence of an agreement with provisions restricting or monitoring the quality of
goods or services produced under a trademark supports a finding of naked
licensing. _Id._ at 597; _see also_ _Stanfield v. Osborne Indus., Inc._, 52 F.3d
867, 871 (10th Cir. 1995) (granting summary judgment where license agreement
lacked right to inspect or supervise licensee's operations and gave the licensee
sole discretion to design the trademark).

TFN concedes that it did not have an express license agreement with FS regarding
FS's use of the trademarks. Without an express license agreement, TFN
necessarily lacks express contractual rights to inspect and supervise FS.
However, TFN argues that the October 9, 2003 email, in which Beal advised
Abraham that: "You can get the neutral logo from www.freecycle.org, _just don't
use it for commercial purposes_ . . . .", reflects an implied license. Emphasis
added.

Even assuming that Beal's emailed admonition to Abraham not to use the
trademarks for commercial purposes constitutes an implied licensing agreement,
it contained no express contractual right to inspect or supervise FS's services
and no ability to terminate FS's license if FS used the trademarks for
commercial purposes. _See_ _Barcamerica_, 289 F.3d at 597 (determining that a
license agreement lacking similar controls was insufficient). We therefore hold
that, by TFN's own admission, there is no disputed issue of material fact as to
whether TFN maintained an express contractual right to control quality.

2

TFN next contends that, despite its lack of an express contractual _right_ to
control quality, a material issue of fact remains as to whether TFN maintained
_actual_ control over its member groups' services and use of the trademarks when
FS was granted use of the trademarks in October 2003. "The lack of an express
contract right to inspect and supervise a licensee's operations is not
conclusive evidence of lack of control." _Barcamerica_, 289 F.3d at 596.
However, where courts have excused the lack of a contractual right to control
quality, they have still required that the licensor demonstrate _actual_ control
through inspection or supervision. _See, e.g._, _Stanfield_, 52 F.3d at 871
("The absence of an express [^13]contractual right of control does not
necessarily result in abandonment of a mark, as long as the licensor in fact
exercised sufficient control over its licensee.").

[^13]: Notably, Beal did not propose, and the modsquad did not adopt, this
    standard until January 2004, more than three months after Abraham founded
    FS in October 2003. The only standard listed in TFN's etiquette section
    on its website in 2003 was "Keep it Free," but there was no requirement
    that member groups adopt this standard. Similarly, TFN's incorporation of
    the Yahoo! Groups' service terms was not done until after FS was given
    use of the trademarks in October 2003. Because we hold that TFN did not
    exercise actual control no matter what time period is considered, we do
    not address whether actual supervision would be sufficient if it starts
    at some point after the granting of a license to use a trademark.

TFN asserts that it exercised actual control over the trademarks because it had
several quality control standards in place, specifically: (1) the "Keep it Free,
Legal, and Appropriate for all Ages" standard and TFN's incorporation of the
Yahoo! Groups' service terms; (2) the non-commercial services requirement
(expressed in Beal's October 9, 2003 email); (3) the etiquette guidelines listed
on TFN's website; and (4) TFN's "Freecycle Ethos" which, TFN contends,
establishes policies and procedures for member groups, even if local member
groups are permitted flexibility in how to apply those policies and procedures.
In addition, TFN cites _Birthright v. Birthright, Inc._, 827 F. Supp. 1114
(D.N.J. 1993) for the principle that loosely organized non-profits like TFN and
FS that share "the common goals of a public service organization" are subject to
less stringent quality control requirements.

First, we disagree with TFN's contentions that the "Keep it Free, Legal, and
Appropriate for all Ages" standard and its incorporation of the Yahoo! Groups'
service terms constituted actual controls over its member groups. The undisputed
evidence showed that TFN's licensees were not required to adopt the "Keep it
Free, Legal, and Appropriate for all Ages" standard, nor was it uniformly
applied or interpreted by the local groups. Similarly, FS was not required to
use Yahoo! Groups and was not asked to agree to the Yahoo! Groups' service terms
as a condition of using TFN's trademarks. Moreover, the Yahoo! Groups' service
terms, which regulate generic online activity like sending spam messages and
prohibiting harassment, cannot be considered quality controls over TFN's member
groups' services and use of the trademarks. The service terms apply to every
Yahoo! Group, and do not control the quality of the freecycling services that
TFN's member groups provide. Thus, the "Keep it Free, Legal and Appropriate for
All Ages" standard and the Yahoo! Groups' service terms were not quality
controls over FS's use of the trademarks.

Second, we conclude that TFN's non-commercial requirement says nothing about the
_quality_ of the services provided by member groups and therefore does not
establish a control requiring member groups to maintain consistent quality.
Thus, it is not an actual control in the trademark context. Third, because
member groups may freely adopt and adapt TFN's listed rules of etiquette and
because of the voluntary and amorphous nature of these rules, they cannot be
considered an actual control. For example, FS modified the etiquette that was
listed on TFN's website and TFN never required FS to conform to TFN's rules of
etiquette. Fourth, TFN admits that a central premise of its "Freecycle Ethos" is
local enforcement with local variation. By definition, this standard does not
maintain consistency across member groups, so it is not an actual control.

Even assuming that TFN's asserted quality control standards actually relate to
the quality of its member groups' services, they were not adequate quality
controls because they were not enforced and were not effective in maintaining
the consistency of the trademarks. Indeed, TFN's alleged quality controls fall
short of the supervision and control deemed inadequate in other cases in which
summary judgment on naked licensing has been granted to the licensee. _See,
e.g._, _Barcamerica_, 289 F.3d at 596-97 (finding no express contractual right
to inspect and supervise the use of the marks coupled with licensor's infrequent
wine tastings and unconfirmed reliance on the winemaker's expertise was
inadequate evidence of quality controls to survive summary judgment);
_Stanfield_, 52 F.3d at 871 (granting summary judgment to the licensee where the
license agreement lacked a right to inspect or supervise licensee's operations,
and alleged actual controls were that the licensor examined one swine heating
pad, looked at other pet pads, and occasionally reviewed promotional materials
and advertising).

Moreover, even if we were inclined to accept the premise allegedly set forth in
Birthright, that loosely organized non-profits that share common goals are
subject to less stringent quality control requirements for trademark purposes,
the result would be the same. In _Birthright_, the court held that the license
was not naked because the licensor "monitored and controlled" its licensees' use
of the trademarks. 827 F. Supp. at 1139-40; _see also_ _Barcamerica_, 289 F.3d
at 596 (holding that a licensor may overcome the lack of a formal agreement if
it exercises actual control over its licensees). Here, TFN exercised no actual
control over its licensees, so even under a less stringent standard, TFN has not
raised a material issue of fact as to whether it exercised actual control over
FS's use of the trademarks. _See Barcamerica_, 289 F.3d at 598.

3

TFN contends that even if it did not exercise actual control, it justifiably
relied on its member groups' quality control measures. Although "courts have
upheld licensing agreements where the licensor is familiar with and relies upon
the licensee's own efforts to control quality," _Barcamerica_, 289 F.3d at 596
(internal quotation marks and brackets omitted), we, like the other circuits
that have considered this issue, have required that the licensor and licensee be
involved in a "close working relationship" to establish adequate quality control
in the absence of a formal agreement, _id._ at 597; _accord Stanfield_, 52 F.3d
at 872; _Taco Cabana Int'l, Inc. v. Two Pesos, Inc._, 932 F.2d 1113, 1121 (5th
Cir. 1991). In _Barcamerica_, we cited four examples of "close working
relationships" that would allow the licensor to rely on the licensee's own
quality control: (1) a close working relationship for eight years; (2) a
licensor who manufactured ninety percent of the components sold by a licensee
and with whom it had a ten year association and knew of the licensee's
expertise; (3) siblings who were former business partners and enjoyed a
seventeen-year business relationship; and (4) a licensor with a close working
relationship with the licensee's employees, and the pertinent agreement provided
that the license would terminate if certain employees ceased to be affiliated
with the licensee. 289 F.3d at 597.

Here, TFN and FS did not enjoy the type of close working relationship that would
permit TFN to rely on FS's quality control measures. TFN had no long term
relationship with Abraham or the FS group. In fact, the October 9, 2003 email
between Beal and Abraham, which mentions using the TFN logo, was the parties'
first and only written communication about the trademarks prior to TFN's
requests to stop using them in November 2006. In addition, TFN had no experience
with FS that might have supported its alleged confidence in FS's quality control
measures. Thus, even considered in a light most favorable to TFN, no evidence
showed the type of close working relationship necessary to overcome TFN's lack
of quality controls over FS. _See id._

Furthermore, we have held that, while reliance on a licensee's own quality
control efforts is a relevant factor, such reliance is _not alone sufficient_ to
show that a naked license has not been granted.[^14] _See Transgo, Inc. v. Ajac
Transmission Parts Corp._, 768 F.2d 1001, 1017-18 (9th Cir. 1985) (noting that,
although the licensor had worked closely with the licensee for ten years, the
licensor did not rely solely on his confidence in the licensee, but exercised
additional control by, _inter alia_, periodically inspecting those goods and was
consulted regarding any changes in the product). Because sole reliance on a
licensee's own control quality efforts is not enough to overcome a finding of
naked licensing without other indicia of control, _see id._ at 1017-18, and
because TFN lacked a close working relationship with FS and failed to show any
other indicia of actual control, we conclude that TFN could not rely solely on
FS's own quality control efforts.

[^14]: Other circuits have also relied on the licensor's confidence in the
    licensee only where there were additional indicia of control. _See, e.g.,
    Stanfield_, 52 F.3d at 872 (holding summary judgment for the licensee
    appropriate where no special relationship between the parties existed and
    no evidence of actual control over the licensee existed); _Land O' Lakes
    Creameries, Inc. v. Oconomowoc Canning Co._, 330 F.2d 667 (7th Cir. 1964)
    (upholding trademark where licensor's name appeared on trademark product
    label, and product was sold under license for forty years without
    complaints about quality).

B

TFN's three remaining arguments also fail to raise a material issue of fact that
precludes a grant summary of judgment for FS. First, TFN asserts that it should
be subject to a lesser level of quality control standard because its services
are not dangerous to the public and the public expects local variation in
services so the probability of deception is low. We have stated that the
"standard of quality control and the degree of necessary inspection and policing
by the licensor will vary." _Barcamerica_, 289 F.3d at 598. The licensor need
only exercise "control sufficient to meet the reasonable expectations of
customers." McCarthy, § 18:55. However, because TFN did not establish _any_
quality control requirements for its member groups, we do not need to decide
what efforts to oversee a licensee's performance might meet a low standard of
quality control.

TFN's remaining two arguments—(1) that FS must show both naked licensing _and_ a
loss of trademark significance, and (2) that FS is estopped from supporting its
naked licensing defense with evidence that demonstrates that TFN did not
adequately control the services offered by FS when using the trademarks— are
both raised for the first time on appeal, so we decline to reach them. [. . .]

IV

We determine, viewing the record in the light most favorable to TFN, that TFN
(1) did not retain express contractual control over FS's quality control
measures, (2) did not have actual control over FS's quality control measures,
and (3) was unreasonable in relying on FS's quality control measures. Therefore,
we conclude that TFN engaged in naked licensing and consequently abandoned the
trademarks. The district court's grant of summary judgment in favor of FS and
against TFN is AFFIRMED.

##### Discussion {#discussion}

1.  What would be the possible detriments to an open source project or community if a court found that the project's trademarks had been abandoned due to evidence of naked licensing? Would the benefits of attempting to freely license all
    trademarks to the open source community at large outweigh the project's
    loss of enforcement rights?

1.  _Freecycle_ found that the absence of an agreement with provisions
    "restricting or monitoring the quality of goods or services produced under a
    trademark supports a finding of naked licensing"[^15] and cited _Stanfield
    v. Osborne Indus., Inc._, 52 F.3d 867, 871 (10th Cir. 1995). In _Stanfield_, the court granted
    summary judgment where a license agreement lacked the right to inspect or
    supervise a licensee's operations and gave the licensee sole discretion to
    design the trademark. What would a right to inspect or supervise quality
    look like in the context of software? Can a boilerplate provision be enough
    to resolve trademark enforcement concerns? Do any of the most popular open
    source licenses specifically protect the licensor's right to enforce
    trademark rights against downstream users? What role could a project maintainer's discretion play when it comes to accepting pull requests?

1.  Absent any express contractual right to inspect or supervise the quality of
    the goods or services associated with a trademark, what would "actual
    control" look like for open source software? _Stanfield_ notes that the
    "absence of an express contractual right does not necessarily result in
    abandonment of a mark, as long as the licensor in fact exercised sufficient
    control over its licensee."[^16] If an open source project chooses to
    licenses its trademarks, how can quality control standards be set? How
    should they be enforced?

1.  Although the _Freecycle_ court noted that the existence of a "close working
    relationship" between a licensor and licensee may not be sufficient to
    "overcome a finding of naked licensing without other indicia of
    control,"[^17] the court cited numerous examples of the types of close
    working relationships that could help to support a finding of actual control
    over the quality associated with a mark. Would these types of close working
    relationships be likely to arise in open source collaborations? If a
    project author and a contributor had been working together closely for eight
    years, could that support a finding that there qas adequate control? What if the close collaborator then fell out with the main project owner and forked the project. Would the project owner still be able to enforce the mark against the contributor?[^18]

[^16]: _Stanfield_, 52 F.3d at 871.

[^15]: _FreecyleSunnyvale v. Freecycle Network_, 626 F.3d 509, 516 (9th Cir.
    2010).

[^17]: _Freecycle,_ 626 F.3d at 519 (citation omitted).

[^18]: _See, e.g._, _Trademarks and Free Software_, FOSSmarks,
    [http://fossmarks.org/](http://fossmarks.org/) ("It may be the case that
    confusion between two products with similar/identical trademarks isn't
    intentional wrongdoing, but rather a matter of differing views on a
    project's direction, sometimes resulting in a fork. But if both forks use
    the same trademark, users won't be able to distinguish them."); _see
    also_ Rudolf Olah, _Node.js has forked into Ayo_, SourceContribute (Aug.
    22, 2017)
    [https://sourcecontribute.com/2017/08/22/node-js-has-forked-into-ayo/](https://sourcecontribute.com/2017/08/22/node-js-has-forked-into-ayo/)
    (summarizing the forking of Node.js into a new forke named "Ayo" after a
    falling out among contributors after the Node.js Code of Conduct was not
    enforced against a controversial developer).

### Common Law Trademarks

In the United States and countries with similar common law legal systems, a
trademark does not have to be formally registered to be enforceable.[^19]
However, in the United States a "common law" trademark must meet the requirements
set out by the courts in order to be enforceable. Primarily, an unregistered
mark must be: (1) used in commerce, and (2) used prior to the alleged trademark
infringement.[^20]

[^19]: _See Unregistered trademark_, Wikipedia,
    [https://en.wikipedia.org/wiki/Unregistered_trademark](https://en.wikipedia.org/wiki/Unregistered_trademark)
    (last visited Jan. 2, 2018) (CC-BY-SA 3.0).

[^20]: _See Tally-Ho, Inc. v. Coast Community College Dist._, 889 F.2d 1018,
    1022-23 ("Under the common law, trademark rights are appropriated only
    through actual prior use in commerce.") (citation omitted).

It may be counterintuitive that the "use in commerce" requirement does not
necessarily mean a profitable or profit-seeking use. In fact, as the following case clarifies, the term
"use in commerce" is used as a reference to Congress's authority to regulate
trademarks under the U.S. Constitution's Commerce Clause rather than an intent
to limit trademarks to profit-making activity.[^Planet] Where a developer released open source software under the name Coolmail, the court rejected the argument
that the lack of direct profit from releasing software under the GNU General
Public License rendered the original Coolmail name unenforceable as a trademark,
holding that distributing software for end-users over the Internet
satisfies the "use in commerce" requirement.

The second prong of unregistered trademark analysis, "prior use," is a fact-based determination.[^21] _Planetary Motion_ restates
the test for whether sufficient "prior use" of a mark has been proven to
establish trademark ownership rights:[^PlanetaryOwnership]

> first, adoption, and, second, use in a way sufficiently public to identify or
> distinguish the marked goods in an appropriate segment of the public mind as
> those of the adopter of the mark, is competent to establish ownership, even
> without evidence of actual sales.

In _Planetary Motion_ the successful party bought the trademark rights from the
earliest author of the email software called "Coolmail." As you read the
following case, consider: how is use
in commerce defined? Which of Byron Darrah's actions were taken into
consideration by the court as evidence of trademark ownership rights? What is the reasoning behind permitting non-profit
organizations to enforce their trademarks? What benefits does the Court
attribute to the original author releasing software under the GPL?

[^Planet]: _Planetary Motion, Inc. v. Techsplosion, Inc._, 261 F.3d 1188
    (11th Cir. 2001)

[^21]: _See New England Duplicating Co. v. Mendes_, 190 F.2d 415, 417-418 (1st
    Cir. 1951) (after finding "use in commerce" jurisdiction predicate
    satisfied, court noted that "the question remains whether the plaintiff
    has established that he was the 'owner' of the mark, for under 15 U.S.C.
    § 1051 only the owner of the mark is entitled to have it registered.")

[^PlanetaryOwnership]: 261 F.3d at 1195 (citation omitted).

#### Planetary Motion, Inc. v. Techsplosion, Inc.

--------------------------------------------------------------------------------

261 F.3d 1188 (11th Cir. 2001)[^22]

[^22]: _Planetary Motion, Inc. v. Techsplosion, Inc._, 261 F.3d 1188 (11th Cir.
    2001), _available at_
    https://law.justia.com/cases/federal/appellate-courts/F3/261/1188/570628/.

Appeal from the United States District Court for the Southern District of
Florida. Before TJOFLAT and WILSON, Circuit Judges, and RESTANI, Judge.[^23]

[^23]: Honorable Jane A. Restani, Judge, United States Court of International
    Trade, sitting by designation.

RESTANI, Judge:

Planetary Motion, Inc. ("Planetary Motion" or "Appellee") sued Techsplosion,
Inc. and Michael Gay a/k/a Michael Carson (respectively "Techsplosion" and
"Carson"; collectively "Appellants") for infringement and dilution of an
unregistered trademark under Section 43(a) and (c) of the Federal Trademark Act,
15 U.S.C. § 1051 _et seq._ (1994) ("Lanham Act"), and for violation of Florida's
unfair competition law. Fla. Stat. Ann. § 495.151 (West 2000). Finding that
Planetary Motion had established priority of use and a likelihood of confusion,
the United States District Court for the Southern District of Florida entered
summary judgment in favor of Planetary Motion. We affirm the judgment and vacate
the award of attorney fees.

_Facts_

I. _Development and Distribution of the "Coolmail" Software_

In late 1994, Byron Darrah ("Darrah") developed a UNIX-based program (the
"Software") that provides e-mail users with notice of new e-mail and serves as a
gateway to the users' e-mail application. On December 31, 1994, Darrah
distributed the Software over the Internet by posting it on a UNIX user site
called "Sunsite," from which it could be downloaded for free. Darrah had named
the Software "Coolmail" and this designation appeared on the announcement sent
to the end-users on Sunsite as well as on the Software user-manual, both of
which accompanied the release.

The Software was distributed without charge to users pursuant to a GNU General
Public License that also accompanied the release. A GNU General Public License
allows users to copy, distribute and/or modify the Software under certain
restrictions, e.g., users modifying licensed files must carry "prominent
notices" stating that the user changed the files and the date of any change.
After the release of the Software, Darrah received correspondence from users
referencing the "Coolmail" mark and in some cases suggesting improvements. In
1995, Darrah released two subsequent versions of the Software under the same
mark and also pursuant to the GNU General Public License.

In early 1995, a German company named S.u.S.E. GmbH sought permission from
Darrah to include the Software in a CD-ROM package sold as a compilation of
Unix-based programs. Darrah consented and, pursuant to the GNU licensing
agreement, S.u.S.E. distributed the Software in its compilation product and in
subsequent versions thereof. S.u.S.E. sold and continues to sell the software
compilation in stores in the United States and abroad, as well as over the
Internet.

II. _Launch of Techsplosion's "CoolMail" E-mail Service_

In 1998, Appellant Carson formed Techsplosion, for the purpose of operating a
business based on an e-mail service that he had developed. On April 16, 1998,
Techsplosion began offering the e-mail service on the Internet under the mark
"CoolMail." Two days later, Techsplosion activated the domain name "coolmail.to"
Techsplosion delivered an e-mail solicitation under the "CoolMail" mark to
approximately 11,000 members of the Paramount Banner Network, an Internet
advertising network, also created and operated by Carson. Techsplosion charged
no fee to subscribe to the service and generated revenues through the sale of
banner advertisements on its web site.

III. _Planetary Motion's E-mail Service & Application for Trademark
Registration_

Appellee Planetary Motion is a computer software and telecommunications company
that developed and owns an electronic mail service called "Coolmail." As part of
its service, Planetary Motion enables a person to check e-mail via telephone
without logging onto a computer. On April 24, 1998, Planetary Motion filed three
intent-to-use applications to register the mark "Coolmail" with the United
States Patent and Trademark Office. Though Planetary Motion was aware that
Darrah's Software also bore the mark "Coolmail," it represented in its
applications that it was not aware of any mark upon which its proposed
registered mark would infringe. Planetary Motion launched its Coolmail e-mail
service to subscribers on June 8, 1998.

IV. _Planetary Motion's Complaint and Subsequent Acquisition of Darrah's Rights_

On April 22, 1999, Planetary Motion filed a complaint against Techsplosion. In
the complaint, Planetary Motion alleged infringement of the alleged mark
"Coolmail" for use in connection with e-mail services. Planetary alleged federal
trademark infringement and unfair competition under Section 43(a) of the Lanham
Act, 15 U.S.C. § 1125 (a), as well as injury to business reputation and dilution
under Florida Statute § 495.151.

On June 10, 1999, Techsplosion filed an Answer, Affirmative Defenses, and
Counterclaims. The counterclaims alleged infringement of the mark "Coolmail" for
use in connection with e-mail services. Techsplosion alleged unfair competition,
false designation, description, and representation under the Lanham Act, common
trademark infringement, common law unfair competition, and injury to business
reputation and dilution.

In July of 1999, Planetary Motion purchased from Darrah all rights, title, and
interest to the Software including all copyrights, trademarks, patents and other
intellectual property rights.[^24] On August 31, 1999, Planetary filed an
Amended Verified Complaint, adding a claim for dilution under Section 43(c) of
the Lanham Act, 15 U.S.C. § 1125 (c), and alleging violation of trademark rights
assigned from Darrah.

[^24]: The assignee of a trade name or service mark "steps into the shoes of the
    assignor." _Premier Dental Prods. Co. v. Darby Dental Supply Co._, 794
    F.2d 850, 853 (3d Cir.), cert. denied, 479 U.S. 950 (1986). Appellants do
    not contest the validity of the assignment from Darrah, nor do they
    dispute that in purchasing rights to Darrah's software, Planetary Motion
    succeeded to all rights possessed by Darrah.

V. _Disposition of Planetary Motion's Complaint_

On January 31, 2000, the district court entered an Order granting Planetary
Motion's motion for summary judgment and denying Carson's and Techsplosion's
motion for summary judgment. The district court based the Order on two findings:
(1) that the alleged mark was affixed to Darrah's software, and that Darrah's
distribution of the software over the Internet constituted a "transport in
commerce," resulting in the creation of trademark rights and priority, and (2)
there was a likelihood of confusion because the marks "are essentially the
same." The district court did not reach the issue of whether Techsplosion's use
of "CoolMail" in connection with its e-mail service diluted Planetary Motion's
mark.

[. . . .]

_Standard of Review_

Review of a district court's grant of summary judgment is _de novo,_ with all
facts and reasonable inferences therefrom reviewed in the light most favorable
to the non-moving party. _Carnival Brand Seafood Co. v. Carnival Brands, Inc._,
187 F.3d 1307, 1309 (11th Cir. 1999).

_Discussion_

Section 43(a) of the Lanham Act forbids unfair trade practices involving
infringement of trade dress, service marks, or trademarks, even in the absence
of federal trademark registration.[^25] _Two Pesos, Inc. v. Taco Cabana, Inc._,
505 U.S. 763, 768, 120 L. Ed. 2d 615, 112 S. Ct. 2753 (1992). Section 43(a) is
remedial in nature and should be interpreted and applied broadly so as to
effectuate its remedial purpose. _Montgomery v. Noga_, 168 F.3d 1282, 1300 & n.
29 (11th Cir. 1999) (citing _Warner Bros., Inc. v. Gay Toys, Inc._, 658 F.2d 76,
79 (2d Cir. 1981)). To prevail under this section, a claimant must show (1) that
it had prior rights to the mark at issue and (2) that the defendant had adopted
a mark or name that was the same, or confusingly similar to its mark, such that
consumers were likely to confuse the two.[^26] _Lone Star Steakhouse & Saloon,
Inc. v. Longhorn Steaks, Inc._, 106 F.3d 355, 360 (11th Cir. 1997) (citing
_Conagra Inc. v. Singleton_, 743 F.2d 1508, 1512 (11th Cir. 1984)), _modified,_
122 F.3d 1379 (1997). Appellants argue that the district court erred in finding
that Planetary Motion had established both elements. Appellants also dispute the
scope of injunctive relief, as well as the award of attorney fees and costs.

[^25]: Section 43(a) provides in pertinent part: (1) Any person who, on or in
    connection with any goods or services, or any container for goods, uses
    in commerce any word, term, name, symbol, or device, or any combination
    thereof, or any false designation of origin, false or misleading
    description of fact, or false or misleading representation of fact,
    which-- (A) is likely to cause confusion, or to cause mistake, or to
    deceive as to the affiliation, connection, or association of such person
    with another person, or as to the origin, sponsorship, or approval of his
    or her goods, services, or commercial activities by another person, or
    (B) in commercial advertising or promotion, misrepresents the nature,
    characteristics, qualities, or geographic origin of his or her or another
    person's goods, services, or commercial activities, shall be liable in a
    civil action by any person who believes that he or she is or is likely to
    be damaged by such act. 15 U.S.C. § 1125(a).

[^26]: Courts may use an analysis of federal infringement claims as a "measuring
    stick" in evaluating the merits of state law claims of unfair
    competition. _See Investacorp, Inc. v. Arabian Inv. Banking Corp._
    (Investcorp) E.C., 931 F.2d 1519, 1521 (11th Cir.), cert. denied, 502
    U.S. 1005 (1991).

I. _Prior Use in Commerce_

Under common law, trademark ownership rights are "appropriated only through
actual prior use in commerce." _Tally-Ho, Inc. v. Coast Cmty College Dist._, 889
F.2d 1018, 1022 (11th Cir. 1989) (citation omitted). Under the Lanham Act,[^27]
the term "use in commerce" is defined in relevant part as follows:

> the bona fide use of a mark in the ordinary course of trade, and not made
> merely to reserve a right in a mark. . . . A mark shall be deemed to be in use
> in commerce . . . on goods when (A) it is placed in any manner on the goods or
> their containers or the displays associated therewith or on the tags or labels
> affixed thereto, or if the nature of the goods makes such placement
> impracticable, then on documents associated with the goods or their sale, and
> (B) the goods are sold or transported in commerce . . . .

[^27]: "In the absence of registration, rights to a mark traditionally have
    depended on the very same elements that are now included in the statutory
    definition: the bona fide use of a mark in commerce that was not made
    merely to reserve a mark for later exploitation." _Allard Enters., Inc.
    v. Advanced Programming Res., Inc._, 146 F.3d 350, 357 (6th Cir. 1998).
    Common law and statutory trademark infringements are merely specific
    aspects of unfair competition. _New West Corp. v. NYM Co. of Cal., Inc._,
    595 F.2d 1194, 1201 (9th Cir. 1979) (citing, _inter alia_, _Dresser
    Indus., Inc. v. Heraeus Engelhard Vacuum, Inc._, 395 F.2d 457, 461 (3d
    Cir.), cert. denied, 393 U.S. 934 (1968)).

15 U.S.C. § 1127.[^28] The district court found that because the statute is
written in the disjunctive (i.e., "sale _or_ transport"), Darrah's wide
distribution of the Coolmail software over the Internet, even absent any sales
thereof, was sufficient to establish ownership rights in the "CoolMail" mark.
Appellants contend that "transport in commerce" alone -- here, Darrah's free
distribution of software over the Internet "with no existing business, no intent
to form a business, and no sale under the mark" -- is insufficient to create
trademark rights. Appellants' Brief at 13. Appellants' argument lacks merit.

[^28]: Appellants appear to have conceded that if Darrah sent out original
    programs and related manuals, this would satisfy the affixation
    requirement: MR. GIGLIOTTI [counsel for Techsplosion]: [The mark] has to
    be on the product or on the associated documentation. It is on neither.
    THE COURT: It is not on the associated documentation [?] How about the
    original programs Darrah sent out and manuals that went with it, and all
    that material, wasn't that enough for affixation? MR. GIGLIOTTI: Yes,
    Your Honor, that is affixation; however, he did not meet the sale
    requirement. R3-85-19 to 20. In any case, the affixation requirement is
    met because the Software was distributed under a filename that is also
    the claimed mark, was promoted under the same mark, was accompanied by a
    user manual bearing the mark, and was sold in a compilation under the
    mark.

The parties do not make clear the two different contexts in which the phrase
"use in commerce" is used. The term "use in commerce" as used in the Lanham Act
"denotes Congress's authority under the Commerce Clause rather than an intent to
limit the Lanham Act's application to profit making activity." _United We Stand
Am., Inc. v. United We Stand, Am. N.Y., Inc._, 128 F.3d 86, 92-93 (2d Cir. 1997)
(citation omitted), _cert. denied,_ 523 U.S. 1076, 140 L. Ed. 2d 673, 118 S. Ct.
1521 (1998); U.S. Const., Art. I, § 8, cl. 3. Because Congress's authority under
the Commerce Clause extends to activity that "substantially affects" interstate
commerce, _United States v. Lopez_, 514 U.S. 549, 559, 131 L. Ed. 2d 626, 115 S.
Ct. 1624 (1995), the Lanham Act's definition of "commerce" is concomitantly
broad in scope: "all commerce which may lawfully be regulated by Congress." 15
U.S.C. § 1127. _See also_ _Steele v. Bulova Watch Co._, 344 U.S. 280, 283-84, 97
L. Ed. 319, 73 S. Ct. 252 (1952); _Larry Harmon Pictures Corp. v. Williams Rest.
Corp._, 929 F.2d 662, 666 (Fed. Cir.) (allowing registration for an intrastate
provider of restaurant services with an undefined interstate clientele), _cert.
denied,_ 502 U.S. 823, 116 L. Ed. 2d 58, 112 S. Ct. 85 (1991). The distribution
of the Software for end-users over the Internet satisfies the "use in commerce"
jurisdictional predicate. _See, e.g.,_ _Planned Parenthood Fed'n of Am., Inc. v.
Bucci_, 1997 U.S. Dist. LEXIS 3338, 42 U.S.P.Q.2D (BNA) 1430, 1434, 1997 WL
133313 (S.D.N.Y. 1997) ("The nature of the Internet indicates that establishing
a typical home page on the Internet, for access to all users, would satisfy the
Lanham Act's 'in commerce' requirement."), _aff'd,_ 152 F.3d 920 (2d Cir.),
_cert. denied,_ 525 U.S. 834, 142 L. Ed. 2d 71, 119 S. Ct. 90 (1998).

Nevertheless, the use of a mark in commerce also must be sufficient to establish
_ownership rights_ for a plaintiff to recover against subsequent users under
section 43(a). _See_ _New England Duplicating Co. v. Mendes_, 190 F.2d 415,
417-18 (1st Cir. 1951) (after finding "use in commerce" jurisdiction predicate
satisfied, court noted that "the question remains whether the plaintiff has
established that he was the 'owner' of the mark, for under 15 U.S.C. § 1051 only
the 'owner' of a mark is entitled to have it registered."). The court in
_Mendes_ set forth a two part test to determine whether a party has established
"prior use" of a mark sufficient to establish ownership:

Evidence showing, first, adoption,[^29] and, second, use in a way sufficiently
public to identify or distinguish the marked goods in an appropriate segment of
the public mind as those of the adopter of the mark, is competent to establish
ownership, even without evidence of actual sales.[^30]

[^29]: It is uncontested that Darrah adopted the mark "Coolmail" before
    Appellants' use of the mark in connection with their e-mail service.

[^30]: This ownership test is not for the purpose of establishing the "use in
    commerce" jurisdictional predicate of the Lanham Act. _See, e.g._, _Univ.
    of Fla. v. KPB, Inc._, 89 F.3d 773, 776 n.4 (11th Cir. 1996). See supra
    discussion in text.

_Id._ at 418. _See also_ _New West_, 595 F.2d at 1200.[^31]

Courts generally must inquire into the activities surrounding the prior use of
the mark to determine whether such an association or notice is present. _See,
e.g._, _Johnny Blastoff, Inc. v. L.A. Rams Football Co._, 188 F.3d 427, 433 (7th
Cir. 1999) ("The determination of whether a party has established protectable
rights in a trademark is made on a case by case basis, considering the totality
of the circumstances."), _cert. denied,_ 528 U.S. 1188, 146 L. Ed. 2d 100, 120
S. Ct. 1241 (2000). Under the "totality of circumstances" analysis, a party may
establish "use in commerce" even in the absence of sales. "Although evidence of
sales is highly persuasive, the question of use adequate to establish
appropriation remains one to be decided on the facts of each case . . . ." _New
West_, 595 F.2d at 1200 (quoting _Mendes_, 190 F.2d at 418). The court in _New
West_ recognized that "mere advertising by itself may not establish priority of
use," but found that promotional mailings coupled with advertiser and
distributor solicitations met the _Mendes_ "public identification" ownership
requirement. 595 F.2d at 1200. Thus, contrary to Appellants' assertions, the
existence of sales or lack thereof does not by itself determine whether a user
of a mark has established ownership rights therein.[^32] _Compare Marvel Comics
Ltd. v. Defiant_, 837 F. Supp. 546, 549 (S.D.N.Y. 1993)(finding announcement of
"Plasmer" title to 13 million comic book readers and promotion at annual trade
convention sufficient to establish trademark ownership rights, notwithstanding
lack of any sales) _with_ _Warnervision Entm't Inc. v. Empire of Carolina Inc._,
915 F. Supp. 639, 645-46 (S.D.N.Y.) (finding toy manufacturer's promotional
efforts insufficient to establish priority of use where only a few presentations
were made to industry buyers, even though one resulted in a sale to a major toy
retailer), _aff'd in part, vacated in part,_ 101 F.3d 259 (2d Cir. 1996).[^33]

[^31]: This ownership requirement parallels the statutory definition of
    "trademark": "any word, name, symbol, or device, or any combination
    thereof . . . used by a person . . . to identify and distinguish his or
    her goods . . . from those manufactured or sold by others . . . ." 15
    U.S.C. § 1127. The Seventh Circuit has held that a higher quantum of use
    may be necessary to establish ownership rights under common law than
    under the statute because the notice function of registration is lacking.
    _See Zazu Designs v. L'Oreal, S.A._, 979 F.2d 499, 503-04 (7th Cir.
    1992). In addition, the continuity of a user's commercial activities in
    connection with the mark is also relevant to determining whether use is
    sufficient to establish common law ownership. _Circuit City Stores, Inc.
    v. CarMax, Inc._, 165 F.3d 1047, 1054-55 (6th Cir. 1999) ("A party
    establishes a common law right to a trademark only by demonstrating that
    its use of the mark was 'deliberate and continuous, not sporadic, casual
    or transitory.'").

[^32]: Appellants cite _Future Domain Corp. v. Trantor Sys. Ltd._, 27 U.S.P.Q.2d
    1289, 1293 (N.D. Cal. 1993) for the proposition that there must be a sale
    in order to satisfy the "use in commerce" requirement. Future Domain,
    however, turned not on the existence of sales but whether the extent of
    the purported mark owner's activities created a public association
    between the mark and the product. There, the court determined that a
    computer software manufacturer's promotion of a mark at a trade show --
    where at most 7,000 persons actually received or requested information
    about the mark and where no orders were taken -- was not sufficient to
    create such an association. _Id._ at 1293-95.

[^33]: Courts applying the "totality of circumstances" approach routinely have
    found evidence of a few sales of goods to which the mark had been affixed
    insufficient to establish trademark ownership. For example, in _Zazu
    Designs_, 979 F.2d at 503-04, the plaintiff hair salon had sold a few
    bottles of shampoo bearing the mark "Zazu" both over the counter and
    mailed over state lines. The court found that such limited sales "neither
    link the Zazu mark with [the plaintiff's] product in the minds of
    consumers nor put other producers on notice." _Id._ at 503

Similarly, not every transport of a good is sufficient to establish ownership
rights in a mark. To warrant protection, use of a mark "need not have gained
wide public recognition," but "secret, undisclosed internal shipments are
generally inadequate." _Blue Bell, Inc. v. Farah Mfg. Co._, 508 F.2d 1260, 1265
(5th Cir. 1975).[^34] In general, uses that are _de minimis_ may not establish
trademark ownership rights. _See, e.g.,_ _Paramount Pictures Corp. v. White_, 31
U.S.P.Q.2D (BNA) 1768, 1772-73 (Trademark Tr. & App. Bd.1994) (finding no bona
fide use in ordinary course of trade where mark was affixed to a game consisting
of three pieces of paper and distributed for the purpose of promoting musical
group).

[^34]: In _Bonner v. City of Prichard_, 661 F.2d 1206 (11th Cir. 1981) (en
    banc), the Eleventh Circuit adopted as binding precedent all decisions
    handed down by the former Fifth Circuit prior to October 1, 1981.

We find that, under these principles, Darrah's activities under the "Coolmail"
mark constitute a "use in commerce" sufficiently public to create ownership
rights in the mark. First, the distribution was widespread, and there is
evidence that members of the targeted public actually associated the mark
Coolmail with the Software to which it was affixed. Darrah made the software
available not merely to a discrete or select group (such as friends and
acquaintances, or at a trade show with limited attendance), but to numerous
end-users via the Internet. The Software was posted under a filename bearing the
"Coolmail" mark on a site accessible to anyone who had access to the Internet.
End-users communicated with Darrah regarding the Software by referencing the
"Coolmail" mark in their e-mails. Appellants argue that only technically-skilled
UNIX-users made use of the Software, but there is no evidence that they were so
few in number to warrant a finding of _de minimis_ use.

Third, the mark served to identify the source of the Software. The "Coolmail"
mark appeared in the subject field and in the text of the announcement
accompanying each release of the Software, thereby distinguishing the Software
from other programs that might perform similar functions available on the
Internet or sold in software compilations.[^35] The announcements also
apparently indicated that Darrah was the "Author/Maintainer of Coolmail" and
included his e-mail address. The user manual also indicated that the Software
was named "Coolmail."[^36] The German company S.u.S.E. was able to locate Darrah
in order to request permission to use his Software in its product under the mark
"Coolmail." Appellants do not assert that S.u.S.E. was unaware that the Software
was called "Coolmail" when it contacted Darrah.

[^35]: Darrah testified that " [m]ost of the source files . . . have [the mark]
    in them. Also there's a copyright notice included with the software that
    has the name Coolmail. And the name of the executable file itself is
    Coolmail." R2-47-Exh. 3 at 67.

[^36]: Darrah: The Coolmail name always comes with the documentation that comes
    with the software.

    *************************************************************************

    Q: What documentation are you talking about? A: There's a user manual
    that comes with it.

    *************************************************************************

    Q: Does it say "Coolmail" on page 1? A. Yes. Q: Where does it say
    "Coolmail" on page 1? A: At the top. . . . and on the header of every
    page. Q: What does it say, exactly? A: I'm not sure if it says this
    verbatim, it's "Coolmail," space, then the version number. R2-47-Exh. 3
    at 68, 72 to 73.

Fourth, other potential users of the mark had notice that the mark was in use in
connection with Darrah's Software. In investigating whether the mark Coolmail
existed before submitting its trademark registration application for its e-mail
service, Planetary Motion was able to discover that Darrah was using the mark to
designate his Software product.

Fifth, the Software was incorporated into several versions of a product that was
in fact sold worldwide and specifically attributed ownership of the Software to
Darrah under the "Coolmail" mark. Any individual using the S.u.S.E. product, or
competitor of S.u.S.E., that wanted to know the source of the program that
performed the e-mail notification function, could do so by referring to the user
manual accompanying the product.[^37] There is no support for the argument that
for a trademark in software to be valid, the mark must appear on the box
containing the product incorporating it, that the mark must be displayed on the
screen when the program is running, or that the software bearing the mark be a
selling point for the product into which it is incorporated. There is no
requirement that the public come to associate a mark with a product in any
particular way or that the public be passive viewers of a mark for a sufficient
public association to arise.

[^37]: The user manual for the S.u.S.E. Linux 4.3 product includes a list of
    application packages that contains the following attribution: coolmail
    "Cool" XBiff Clone Shows if new mail has arrived. The main advantage of
    this program is that you can click into the window to fire up the mailer
    of your choice. Docu: man coolmail Copyright: (c) 1994 Byron C. Darrah
    Author: Byron C. Darrah < darrah@kaiwan.com > Randall K. Sharpe <
    rsharpe@ncsa.uiuc.edu > Version: 1.3 Supp. Exh. 1 at 14-72 and 42-110.

Sixth, software is commonly distributed without charge under a GNU General
Public License. The sufficiency of use should be determined according to the
customary practices of a particular industry. _See_ S. Rep. 100-515 at 44 (1988)
("The committee intends that the revised definition of 'use in commerce' see
note 13, _supra_ be interpreted to mean commercial use _which is typical in a
particular industry._") (emphasis added). That the Software had been distributed
pursuant to a GNU General Public License does not defeat trademark ownership,
nor does this in any way compel a finding that Darrah abandoned his rights in
trademark. Appellants misconstrue the function of a GNU General Public License.
Software distributed pursuant to such a license is not necessarily ceded to the
public domain and the licensor purports to retain ownership rights, which may or
may not include rights to a mark.[^38]

[^38]: Because a GNU General Public License requires licensees who wish to copy,
    distribute, or modify the software to include a copyright notice, the
    license itself is evidence of Darrah's efforts to control the use of the
    "CoolMail" mark in connection with the Software.

Appellants cite _Heinemann v. General Motors Corp._, 342 F. Supp. 203 (N.D. Ill.
1972), _aff'd,_ 478 F.2d 1405 (7th Cir. 1973), for the proposition that Darrah
was a "hobbyist" unworthy of common law trademark protection. _Heinemann_ is
factually distinguishable from the case at hand. The plaintiff in Heinemann used
a mark in connection with his automobile before an automobile manufacturer
independently had adopted the same name for a new model. The court held that the
plaintiff had not established common law ownership rights based on two findings.
First, the court found that because Heinemann's purpose in using the mark was to
"open at a later date an automobile equipment shop which would have capitalized
upon the slogan," he merely attempted to "reserve a trade or service mark
pending the creation of a trade or business . . . ." 342 F. Supp. at 207. The
court reasoned as follows:

While the law does not require a nationwide business; an old, established
business; or even a profitable business for the acquisition of property
interests in trade or service marks, it does require a _presently existing_
trade or business for such acquisition. The exhibits disclose that Plaintiff had
only a desire to open a business _in futuro._ To hold otherwise would make a
trade mark a property right in gross, instead of a right appurtenant.

_Id._ (emphasis in original). The _Heinemann_ court also found that plaintiff
Heinemann's activities consisted merely of occasionally racing or displaying the
automobile at fairs as a hobby, as evidenced by his testimony that he was
employed at an oil company. _Id._ Here, Darrah did not attempt to "warehouse"
the mark by promoting a product he merely _intended_ to develop and distribute
at a later date. Darrah's use of the mark to designate the distributed Software
and each subsequent version thereof indicates that his use was not mere sporadic
or token use.[^39] Furthermore, unlike Heinemann, Darrah activities pertained to
his chosen profession. Darrah is employed as a computer systems administrator,
which entails the management and oversight of computer networks and systems as
well as the development of software in support thereof.

[^39]: Appellants contend that the district court erred in "ignoring" the first
    sentence of the present definition of "use in commerce" ("the bona fide
    use of a mark in the ordinary course of trade, and not made merely to
    reserve a right in a mark"), which was added pursuant to the Trademark
    Law Revision Act of 1988 ("Revision Act"), Pub. L. No. 100-667, 102 Stat.
    3935 (1988). The court in _Allard_ found that a magistrate judge's
    reliance on case law that antedated the revision was proper because the
    language of the revised definition is "entirely consistent with the
    traditional rules governing common-law ownership of trademarks." 146 F.3d
    at 357. The _Allard_ court noted that "the purpose of this revision 'was
    to eliminate 'token use' as a basis for registration, and that the
    stricter standard contemplates instead commercial use of the type common
    to the particular industry in question.'" _Id._ (citation omitted). The
    reason "token use" was expressly eliminated was that the Revision Act had
    created an "intent-to-use" application system that rendered such a
    "commercial sham" unnecessary. _See_ 134 Cong. Rec. 32,053 (Oct. 20,
    1988) (Sen. DeConcini). The revision did not alter the meaning of the
    phrase "sold or transported in commerce" or in any way increase the
    quantum of use necessary to acquire trademark ownership as developed by
    common law. _See id._ ("Congress' intent that the revised definition
    still encompass genuine, but less traditional, trademark uses must be
    made clear. For example, such uses as clinical shipments of a new drug
    awaiting FDA approval, test marketing, or infrequent sales of large or
    expensive or seasonal products, reflect legitimate trademark uses in the
    normal course of trade and are not to be excluded by the House
    language."). There is no evidence to support the contention that Darrah's
    purpose was merely to secure trademark rights to reserve the mark for
    future use.

Appellants also rely on _DeCosta v. Columbia Broad. Sys., Inc._, 520 F.2d 499,
513 (1st Cir. 1975), _cert. denied_, 423 U.S. 1073 (1976), to argue that Darrah
is an eleemosynary individual and therefore unworthy of protection under unfair
competition laws. [. . .] Common law unfair competition protection extends to
non-profit organizations because they nonetheless engage in _competition_ with
other organizations.[^40] _See_ _Girls Clubs of Am., Inc. v. Boys Clubs of Am.,
Inc._, 683 F. Supp. 50 (S.D.N.Y. 1988), _aff'd,_ 859 F.2d 148 (2d Cir.). Thus,
an eleemosynary individual that uses a mark in connection with a good or service
may nonetheless acquire ownership rights in the mark if there is sufficient
evidence of competitive activity.[^41]

[^40]: The _DeCosta_ court recognized that "the law of unfair competition . . .
    protects 'eleemosynary organizations (which) function in commerce and, in
    form, resemble business enterprises . . . . The happenstance that they
    are nonprofit-seeking ventures, and therefore removed, as such, from the
    rigors of business competition, neither eliminates the element of
    competition nor disentitles them to protection against the unfair
    competition of similar organizations.'" 520 F.2d at 512 (quoting Callman,
    Vol. 1,s 1.1, p. 4).

[^41]: The _DeCosta_ court noted that [common law unfair competition]
    [p]rotection at present has the merits of inherent limitations: the
    existence of a trade, business, or profession where the 'good will' to be
    protected has been subject to the acid test of the willingness of people
    to pay for goods or services; or, in the case of nonprofit institutions,
    the voluntary investment in time, effort, and money of many individuals
    to create and maintain a program of sufficient interest to consumers,
    members, and sponsors to warrant protection. 520 F.2d at 513. We find
    that such an "inherent limitation," if it in fact exists, is inapplicable
    in this context. One individual can invest time, effort and money in
    developing software or other technologically-based goods or services that
    would be of interest to a multitude of users, other developers, and
    retail establishments. In fact, the program was of sufficient interest
    for S.u.S.E. to put effort into including it in its own software which
    was sold for profit, including the effort of obtaining Darrah's
    permission under the GNU General Public License.

Here, Darrah's activities bear elements of competition, notwithstanding his lack
of an immediate profit-motive. By developing and distributing software under a
particular mark, and taking steps to avoid ceding the Software to the public
domain, Darrah made efforts to retain ownership rights in his Software and to
ensure that his Software would be distinguishable from other developers who may
have distributed similar or related Software. R2-47-Exh. 3 at 67. Competitive
activity need not be fueled solely by a desire for direct monetary gain. Darrah
derived value from the distribution because he was able to improve his Software
based on suggestions sent by end-users. Just as any other consumers, these
end-users discriminate among and share information on available software. It is
logical that as the Software improved, more end-users used his Software, thereby
increasing Darrah's recognition in his profession and the likelihood that the
Software would be improved even further.

In light of the foregoing, the use of the mark in connection with the Software
constitutes significant and substantial public exposure of a mark sufficient to
have created an association in the mind of public.

II. _Likelihood of Confusion_

The district court supported its determination of "likelihood of confusion" with
the following findings: (1) the mark used by Planetary Motion("Coolmail") is
"essentially the same" as that used by Techsplosion ("CoolMail")[^42]; (2) both
marks are used in connection with e-mail services; (3) both plaintiff and
defendants serve e-mail customers via the Internet; and (4) both use the
Internet to promote their services. R2-62-7.[^43] Appellants do not dispute the
accuracy of these findings. Rather, Appellants claim the district court
improperly based its analysis on a comparison of the parties' respective e-mail
services, rather than on a comparison of Techsplosion's "CoolMail" e-mail
service to the "Coolmail" Software. Appellants argue that the latter comparison
is required because Planetary Motion acquired its rights to the "Coolmail" mark
by assignment of rights in Darrah's Software, and under the "natural expansion"
doctrine this is a use unrelated to Planetary Motion's current use of e-mail
services. Thus, Appellants' argument in essence goes to whether the scope of
trademark protection enjoyed by Planetary Motion extends from the initial use
(in connection with the Software) to the current use (in connection with
Planetary Motion's e-mail services).

[^42]: The Ninth Circuit in _Brookfield Communications, Inc. v. W. Coast Entm't
    Corp._, 174 F.3d 1036, 1055 (1999), explained that the domain name
    "moviebuff.com" was virtually identical to "MovieBuff," because "Web
    addresses are not caps-sensitive."

[^43]: This Court considers the following seven factors in assessing whether or
    not a likelihood of consumer confusion exists: (1) type of mark; (2)
    similarity of mark; (3) similarity of the products the marks represent;
    (4) similarity of the parties' retail outlets (trade channels) and
    customers; (5) similarity of advertising media; (6) defendant's intent;
    and (7) actual confusion. _See Lone Star_, 122 F.3d at 1382. Of these,
    the type of mark and the evidence of actual confusion are the most
    important. _See Dieter v. B & H Indus. of Southwest Fla., Inc._, 880 F.2d
    322, 326 (11th Cir. 1989), _cert. denied_, 498 U.S. 950 (1990). In this
    case, there is evidence that end-users subscribed to Techsplosion's
    e-mail service under the impression they were subscribing to Planetary
    Motion's service. See R2-46-Exh. 1-G).

The scope of protection enjoyed by a trademark owner is not restricted to the
owner's original use. The "natural expansion" doctrine is applied to determine
the proper scope of protection where a mark owner's previous use differs from
its current use, and the junior use intervenes. Under this doctrine, the first
trademark owner's rights are limited to goods on which the mark has already been
used or that lie within the realm of natural expansion; "this appears to be no
more than a specific application of the familiar 'related goods' test." J.
McCarthy, § 24:20.[^44] _See also_ _Carnival_, 187 F.3d at 1310-11.

[^44]: The theory of "natural expansion" as applied to determinations of the
    scope of protection "relates to a situation where the senior user of mark
    A on product line X expands use of mark A to product line Z and conflicts
    with an 'intervening junior user' who has already been using mark A on
    product line Z." J. McCarthy, § 24:20. This differs from the "natural
    expansion" doctrine as applied to determining the geographical
    delimitation of common law trademark rights. _See id._ § 26:20;
    _Tally-Ho_, 889 F.2d at 1023, 1027-29. The 'natural expansion' thesis
    seems to be nothing more than an unnecessarily complicated application of
    the likelihood of confusion of source or sponsorship test to a particular
    factual situation. If the intervening use was likely to cause confusion
    [with respect to the mark owner's previous use], it was an infringement
    and the senior user has the right to enjoin such use, whether it had in
    fact already expanded itself or not. J. McCarthy, § 24:20.

The court in _Tally-Ho_ explained that a senior user's rights "may extend into
uses in 'related' product or service markets (termed the 'related goods
doctrine')," and that "an owner of a common law trademark may use its mark on
related products or services and may enjoin a junior user's use of the mark on
such related uses . . . ." 889 F.2d at 1023 (citing J. McCarthy, § 24:1 to
24:12). This rule is limited by equitable considerations. The court in
_Carnival_ noted that " A trademark owner cannot by the normal expansion of its
business extend the use or registration of its mark to _distinctly different_
goods or services not comprehended by its previous use . . . where the result
could be a conflict with _valuable intervening rights established by another
through extensive use_ . . . of the same or similar mark for like or similar
goods and services." 187 F.3d at 1310-11 (citations and internal quotation marks
omitted) (emphasis added).

Courts determine the proper scope of protection of a mark in the context of
intervening uses by applying the "source or sponsorship" test. Under this test,
a trademark owner has "protection against use of its mark on any product or
service which would reasonably be thought by the buying public to come from the
same source, or thought to be affiliated with, connected with, or sponsored by,
the trademark owner." J. McCarthy, § 24:6. The public perception in this regard
is determined at the time the junior user first used the mark on the product or
service to which the allegedly infringing mark is affixed.[^45] _Carnival_, 187
F.3d at 1312. The court in _Tally-Ho_ explained that "related use" is "merely a
facet of the likelihood of confusion test and therefore requires an inquiry into
the seven factors affecting the likelihood of confusion . . . ."[^46] 889 F.2d
at 1027.

[^45]: Techsplosion, the junior user in this case, first used the mark
    "CoolMail" in connection with its e-mail service in April 16, 1998,
    before Planetary motion filed its intent-to-use application.

[^46]: The court in Carnival explained the "source or sponsorship" inquiry in
    this context as follows: The likelihood-of-confusion test, when applied
    at this stage in order to determine priority where there are issues of
    related use, does not substitute for the likelihood-of-confusion test
    that controls whether infringement of the plaintiff's trademark is
    occurring or has occurred. These are two independent inquiries. Once
    priority in the use of a mark for a particular class of goods or services
    has been established, then it is necessary to perform the [liability
    stage] likelihood-of-confusion test, as of the current time and as
    between the plaintiff's current products (i.e., those that inherit the
    priority with respect to the previously used mark) and the allegedly
    infringing products of the defendant, to determine whether the plaintiff
    ultimately prevails in a trademark infringement litigation. 187 F.3d at
    1311, n. 4 (citation omitted). Thus, evidence supporting a finding of
    "related use" need not rise to the level of finding likelihood of
    confusion for the purposes of establishing liability, but may nonetheless
    serve as a guide for determining the scope of protection.

We find that the relatedness between e-mail notification software and a service
that allows users to check e-mail via telephone line is not so attenuated that
the district court mistakenly failed to limit Planetary Motion's rights in the
mark to its use in connection with the Software. Consumers reasonably could
attribute the Software and an e-mail service under the same name to the same
source for several reasons.[^47] Both the Software and the e-mail service belong
to the same general field of commerce, i.e., information technology, and both
deal more specifically with e-mail.[^48] Appellants do not dispute Planetary
Motion's contention that major firms in this field sell e-mail software as well
as provide e-mail service.[^49] _See_ Darrah Affidavit, R2-46-Exh. 2 at P 34.
Both the Software and the e-mail service involve sending messages over the
Internet: the former provides a functionality that enables a user with e-mail
capability to receive notification of new mail, and the latter enables
subscribers to the service to send and receive e-mail. Both the Software and the
e-mail service were promoted over the Internet to those who make use of e-mail.

[^47]: The extension of Planetary Motion's rights to the mark in connection with
    its e-mail service does not, as Appellants assert, hinge on whether
    Darrah intended to launch, or even was capable of launching, an e-mail
    service similar to those of the parties. For goods or services to be
    "related," they need not have exactly the same customer base or be in
    direct competition with one another.

[^48]: _Cf._ _Commerce Nat'l Ins. Servs., Inc. v. Commerce Insurance Agency,
    Inc._, 214 F.3d 432, 438, 441-43 (3d Cir. 2000). The court in Commerce
    Nat'l found clear error in the district court's "likelihood of confusion"
    analysis that had been based "primarily on the assumption that banking
    and insurance are similar industries in the minds of consumers and that
    consumers would expect banks to expand into the insurance industry,"
    where evidence of such perception consisted of an affidavit and an
    "unpersuasive report" and where state law limited banks from engaging in
    the general insurance industry. 214 F.3d at 441.

[^49]: _See_ _Scarves by Vera, Inc. v. Todo Imports, Ltd._, 544 F.2d 1167,
    1174-75 (2d Cir. 1976). The court in Scarves by Vera found a use of mark
    on cosmetics to infringe on use on apparel and household linens, even
    though plaintiff had no plans to enter the former market. The court
    reasoned that other fashion designers were commonly involved in both
    markets, such that customers would likely assume that defendant's use was
    a similar expansion by plaintiff.

Furthermore, the equities do not necessarily favor Techsplosion.[^50]
Techsplosion's "CoolMail" e-mail service had not been in operation for an
extended period of time before Planetary Motion entered the market under the
name "Coolmail," and Planetary Motion is not merely attempting to reserve the
mark for a future business endeavor. Accordingly, we sustain the district
court's finding of "likelihood of confusion."

[^50]: _See Rosenthal A.G. v. Rite Lite, Ltd._, 986 F. Supp. 133, 141 (E.D.N.Y.
    1997) (" [A]bsent equities in a defendant's favor, courts should enjoin
    defendants 'from using a similar trademark whenever the non-competitive
    products are sufficiently related that customers are likely to confuse
    the source of origin.'") (citation omitted). The court in Rosenthal,
    relying on "undisputed evidence and basic common sense," found the two
    markets at issue to be sufficiently related and noted that the equities
    did not tip in the defendant's favor where the plaintiff had in fact
    entered the defendant's market. _Id._ (" [T]he interest at stake is more
    than plaintiff's interest in being able to enter a related market at some
    future time . . . .").

[. . . .]

_Conclusion_

Accordingly, the district court's order and final judgment are AFFIRMED, except
that the order adopting the magistrate judge's report and recommendation, with
respect to the award of attorney fees, is VACATED.

##### Discussion

1.  At what point did Darrah begin using the mark "Coolmail" in commerce? What
    needs to be done with open source software in order to constitute "sale or
    transport in commerce"? Is it enough to publish the code publicly? To
    publish the code publicly under an open source license? To email the code
    privately? Does the court suggest that affirmative steps are required to
    avoiding ceding software to the public domain when publicly distributing
    software for free?

1.  What does it mean to purchase trademark rights in an unregistered trademark?
    Planetary Motion began using Coolmail after Techsplosion, and purchased
    rights from Darrah only after the filing of its claims and Techsplosion's
    counterclaims. What effect does this have in the analysis?

### Fair Use Defense to Trademark Infringement: Nominative Use

In trademark law, nominative use is one of the most important balances between
consumer protection and free expression. Nominative use permits
the use of a trademark -- even in commercial contexts -- if it is the most
accurate way to refer to a good or service without misleading consumers as to its source.

The three-part test for nominative use was first laid out in _New Kids on the
Block_:[^51]

> [W]here the defendant uses a trademark to describe the plaintiff's product,
> rather than its own, we hold that a commercial user is entitled to a
> nominative fair use defense provided he meets the following three
> requirements: First, the product or service in question must be one not
> readily identifiable without the use of the trademark; second, only so much of
> the mark or marks may be used as is reasonably necessary to identify the
> product or service; and third, the user must do nothing that would, in
> conjunction with the mark, suggest sponsorship or endorsement by the trademark
> holder.

In an open source context, an example of a possible nominative use could be
listing the name of a library as a dependency of software you are distributing.

[^51]: _New Kids on the Block v. News America Pub., Inc._, 971 F.2d 301, 308
    (9th Cir. 1992), available at
    [https://www.law.berkeley.edu/files/New_Kids_on_the_Block_v_News_America.pdf](https://www.law.berkeley.edu/files/New_Kids_on_the_Block_v_News_America.pdf)
    (citation omitted).

Project forking's naming conventions are another area of possible nominative use, although it remains a gray area. [^52] Consider how, when you fork an original project on GitHub,
the result is that you have a different version of the source code from that
project copied into your own account at a URL which probably reads
"github.com/[yourusername]/[originalprojectname]." The original project name
could conceivably be trademarked. Does this mean that all other users should be
prevented from forking that project, or that they should have to fork it with a
changed project name?

[^52]: _Fork (software development)_, Wikipedia,
    [https://en.wikipedia.org/wiki/Fork_(software_development)](https://en.wikipedia.org/wiki/Fork_\(software_development\))
    ("In software engineering, a project fork happens when developers take a
    copy of source code from one software package and start independent
    development on it, creating a distinct and separate piece of software.")
    (last visited Dec. 7, 2017) (CC-BY-SA 3.0).

Concern and confusion abounds on discussion boards about the issue
of using trademarks in project forking. In one thread a non-attorney's
top-voted answer recommends that a user register their project name as a trademark "because
then people are required to get your permission before re-using the name."[^53]
While there is no definitive case law on trademarks and project forking conventions, the
concept of nominative use can provide more general guidance as to the permissionless use of
trademarked names.

[^53]: Top-voted answer by Bart van Ingen Schenau, posted June 13, 2013 at
    15:29,
    [https://softwareengineering.stackexchange.com/questions/201442/what-to-do-when-somebody-forks-my-open-source-project-with-the-same-name](https://softwareengineering.stackexchange.com/questions/201442/what-to-do-when-somebody-forks-my-open-source-project-with-the-same-name)
    (last visited Dec. 7, 2017).

Nominative use prevents trademark holders from depleting general language by
monopolizing every use of a word.[^54] Nominative use has many parallels to the
fair use doctrine in copyright law, and is sometimes referred to as nominative
trademark fair use. Both trademark nominative use and copyright fair use permit
context-specific use of intellectual property without the IP owner's
permission in order to balance the interests of IP owners against necessary
and natural uses.[^55] The Ninth Circuit Court of Appeals provided an
illustrative example in _New Kids_: "one might refer to the 'two-time world
champions' or 'the professional basketball team from Chicago,' but it's far
simpler (and more likely to be understood) to refer to the Chicago Bulls."[^56]

[^54]: _See Playboy Enters. v. Welles_, 279 F.3d 796, 802 (9th Cir. 2002) ("To
    satisfy the first part of the test for nominative use, 'the product or
    service in question must be one not readily identifiable without use of
    the trademark[.]' This situation arises 'when a trademark also describes
    a person, a place or an attribute of a product' and there is no
    descriptive substitute for the trademark. In such a circumstance,
    allowing the trademark holder exclusive rights would allow the language
    to 'be depleted in much the same way as if generic words were
    protectable.'") (citation omitted).

[^55]: _See, e.g.,_ Mike Masnick, _Hey Advertisers! Stop Believing the NFL's Lies About
    Trademark Law And Call The Super Bowl The Super Bowl_, techdirt (Feb. 3,
    2012, 9:21 AM),
    [https://www.techdirt.com/articles/20120202/04205917638/hey-advertisers-stop-believing-nfls-lies-about-trademark-law-call-super-bowl-super-bowl.shtml](https://www.techdirt.com/articles/20120202/04205917638/hey-advertisers-stop-believing-nfls-lies-about-trademark-law-call-super-bowl-super-bowl.shtml).

[^56]: _New Kids on the Block_, 971 F.2d at 308.

_Playboy Enters. v. Welles_ applies nominative use analysis to 1981 Playmate of
the Year model Terri Welles's use of Playboy Enterprise's trademarked terms on
her website and its metadata tags. As you read, consider: did Playboy have the
right to prevent her from accurately proclaiming that she has received the
designation of Playmate of the Year? Was Ms. Welles permitted to use their
trademarks to promote her own competing website without authorization?

#### Playboy Enters. v. Welles

--------------------------------------------------------------------------------

279 F.3d 796 (9th Cir. 2002)[^FirstWelles]

[^FirstWelles]: _Playboy Enters. v. Welles_, 279 F.3d 796 (9th Cir. 2002),
    _available at_
    https://www.law.berkeley.edu/wp-content/uploads/2016/05/Playboy-v-Welles-279_F.3d_796.pdf

Appeal from the United States District Court for the Southern District of
California. D.C. No. CV-98-00413-JNK. Judith N. Keep, Chief District Judge, and
Robert J. Bryan, District Judge, Presiding.

T.G. NELSON, Circuit Judge:

Playboy Enterprises, Inc. (PEI), appeals the district court's grant of summary
judgment as to its claims of trademark infringement, unfair competition, and
breach of contract against Terri Welles; Terri Welles, Inc.; Pippi, Inc.; and
Welles' current and former "webmasters," Steven Huntington and Michael Mihalko.
We have jurisdiction pursuant to 28 U.S.C. § 1291, and we affirm in part and
reverse in part.

[. . . .]

I.

Background

Terri Welles was on the cover of Playboy in 1981 and was chosen to be the
Playboy Playmate of the Year for 1981. Her use of the title "Playboy Playmate of
the Year 1981," and her use of other trademarked terms on her website are at
issue in this suit. During the relevant time period, Welles' website offered
information about and free photos of Welles, advertised photos for sale,
advertised memberships in her photo club, and promoted her services as a
spokesperson. A biographical section described Welles' selection as Playmate of
the Year in 1981 and her years modeling for PEI. After the lawsuit began, Welles
included discussions of the suit and criticism of PEI on her website and
included a note disclaiming any association with PEI.[^57]

[^57]: The disclaimer reads as follows:" This site is neither endorsed, nor
    sponsored, nor affiliated with Playboy Enterprises, Inc. PLAYBOY tm
    PLAYMATE OF THE YEAR tm AND PLAYMATE OF THE MONTH tm are registered
    trademarks of Playboy Enterprises, Inc."

PEI complains of four different uses of its trademarked terms on Welles'
website: (1) the terms "Playboy "and "Playmate" in the metatags of the
website;[^58] (2) the phrase "Playmate of the Year 1981" on the masthead of the
website; (3) the phrases "Playboy Playmate of the Year 1981 "and "Playmate of
the Year 1981" on various banner ads, which may be transferred to other
websites; and (4) the repeated use of the abbreviation "PMOY '81" as the
watermark on the pages of the website.[^59] PEI claimed that these uses of its
marks constituted trademark infringement, dilution, false designation of origin,
and unfair competition. The district court granted defendants' motion for
summary judgment. PEI appeals the grant of summary judgment on its infringement
and dilution claims. We affirm in part and reverse in part.

[^58]: Metatags are hidden code used by some search engines to determine the
    content of websites in order to direct searchers to relevant sites.

[^59]: PEI claims that "PMOY" is an unregistered trademark of PEI, standing for
    "Playmate of the Year."

[. . . .]

A. Trademark Infringement

Except for the use of PEI's protected terms in the wallpaper of Welles' website,
we conclude that Welles' uses of PEI's trademarks are permissible, nominative
uses. They imply no current sponsorship or endorsement by PEI. Instead, they
serve to identify Welles as a past PEI "Playmate of the Year."[^60]

[^60]: _See New Kids on the Block v. New America Publ'g, Inc._, 971 F.2d 302,
    306 (9th Cir. 1992) (describing a nominative use as one that "does not
    imply sponsorship or endorsement of the product because the mark is used
    only to describe the thing, rather than to identify its source").

We articulated the test for a permissible, nominative use in _New Kids On The
Block v. New America Publishing, Inc_.[^61] The band, New Kids On The Block,
claimed trademark infringement arising from the use of their trademarked name by
several newspapers. The newspapers had conducted polls asking which member of
the band New Kids On The Block was the best and most popular.[^62] The papers'
use of the trademarked term did not fall within the traditional fair use
doctrine. Unlike a traditional fair use scenario, the defendant newspaper was
using the trademarked term to describe not its own product, but the
plaintiff's.[^63] Thus, the factors used to evaluate fair use were
inapplicable.[^64] The use was nonetheless permissible, we concluded, based on
its nominative nature.

[^61]: 971 F.2d 302 (9th Cir. 1992).

[^62]: _Id_. at 304.

[^63]: The "classic fair use case" is one in which "the defendant has used the
    plaintiff's mark to describe the defendant's _own_ product." _Id_. at 308
    (emphasis in original).

[^64]: _See New Kids_, 971 F.2d at 308-09 (adopting a three-factor test for
    nominative use, not the eight-factor test for likelihood of confusion set
    forth in _AMF, Inc. v. Sleekcraft Boats_, 599 F.2d 341, 348-49 (9th Cir.
    1979), and applied in fair use cases).

We adopted the following test for nominative use:

First, the product or service in question must be one not readily identifiable
without use of the trademark; second, only so much of the mark or marks may be
used as is reasonably necessary to identify the product or service; and third,
the user must do nothing that would, in conjunction with the mark, suggest
sponsorship or endorsement by the trademark holder.[^65]

[^65]: _New Kids_, 971 F.2d at 308 (footnote omitted).

We noted in _New Kids_ that a nominative use may also be a commercial one.[^66]

In cases in which the defendant raises a nominative use defense, the above
three-factor test should be applied instead of the test for likelihood of
confusion set forth in _Sleekcraft_.[^67] The three-factor test better evaluates
the likelihood of confusion in nominative use cases. When a defendant uses a
trademark nominally, the trademark will be identical to the plaintiff's mark, at
least in terms of the words in question. Thus, application of the _Sleekcraft_
test, which focuses on the similarity of the mark used by the plaintiff and the
defendant, would lead to the incorrect conclusion that virtually all nominative
uses are confusing. The three-factor test -- with its requirements that the
defendant use marks only when no descriptive substitute exists, use no more of
the mark than necessary, and do nothing to suggest sponsorship or endorsement by
the mark holder --better addresses concerns regarding the likelihood of
confusion in nominative use cases.

We group the uses of PEI's trademarked terms into three for the purpose of
applying the test for nominative use. First, we analyze Welles' use of the terms
in headlines and banner advertisements. We conclude that those uses are clearly
nominative. Second, we analyze the use of the terms in the metatags for Welles'
website, which we conclude are nominative as well. Finally, we analyze the terms
as used in the wallpaper of the website. We conclude that this use is not
nominative and remand for a determination of whether it infringes on a PEI
trademark.

[^66]: _Id_. at 309 ("Where, as here, the use does not imply sponsorship or
    endorsement, the fact that it is carried on for profit and in competition
    with the trademark holder's business is beside the point.").

[^67]: 599 F.2d at 348-49.

_1. Headlines and banner advertisements._

To satisfy the first part of the test for nominative use, "the product or
service in question must be one not readily identifiable without use of the
trademark[.]"[^68] This situation arises "when a trademark also describes a
person, a place or an attribute of a product"[^69] and there is no descriptive
substitute for the trademark. In such a circumstance, allowing the trademark
holder exclusive rights would allow the language to "be depleted in much the
same way as if generic words were protectable."[^70] In _New Kids_, we gave the
example of the trademarked term, "Chicago Bulls."[^71] We explained that "one
might refer to the 'two-time world champions' or' the professional basketball
team from Chicago,' but it's far simpler (and more likely to be understood) to
refer to the Chicago Bulls." Moreover, such a use of the trademark would "not
imply sponsorship or endorsement of the product because the mark is used only to
describe the thing, rather than to identify its source."[^72] Thus, we
concluded, such uses must be excepted from trademark infringement law.

The district court properly identified Welles' situation as one which must also
be excepted. No descriptive substitute exists for PEI's trademarks in this
context. The court explained:

There is no other way that Ms. Welles can identify or describe herself and her
services without venturing into absurd descriptive phrases. To describe herself
as the "nude model selected by Mr. Hefner's magazine as its number-one
prototypical woman for the year 1981" would be impractical as well as
ineffectual in identifying Terri Welles to the public.[^73]

[^68]: _New Kids_, 971 F.2d at 308.

[^69]: _Id_. at 306.

[^70]: _Id_.

[^71]: _Id_.

[^72]: _Id_.

[^73]: _PEI v. Welles_, 78 F. Supp. 2d 1066, 1079 (S.D. Cal. 1999).

We agree. Just as the newspapers in _New Kids_ could only identify the band
clearly by using its trademarked name, so can Welles only identify herself
clearly by using PEI's trademarked title.

The second part of the nominative use test requires that "only so much of the
mark or marks may be used as is reasonably necessary to identify the product or
service[.]"[^74] _New Kids_ provided the following examples to explain this
element: "[A] soft drink competitor would be entitled to compare its product to
Coca-Cola or Coke, but would not be entitled to use Coca-Cola's distinctive
lettering."[^75] Similarly, in a past case, an auto shop was allowed to use the
trademarked term "Volkswagen" on a sign describing the cars it repaired, in part
because the shop "did not use Volkswagen's distinctive lettering style or color
scheme, nor did he display the encircled 'VW' emblem."[^76] Welles' banner
advertisements and headlines satisfy this element because they use only the
trademarked words, not the font or symbols associated with the trademarks.

[^74]: _New Kids_, 971 F.2d at 308.

[^75]: _Id_. at n. 7.

[^76]: _Id_. (quoting _Volkswagenwerk Aktiengesellschaft v. Church_, 411 F.2d
    350 (9th Cir. 1969)).

The third element requires that the user do "nothing that would, in conjunction
with the mark, suggest sponsorship or endorsement by the trademark holder."[^77]
As to this element, we conclude that aside from the wallpaper, which we address
separately, Welles does nothing in conjunction with her use of the marks to
suggest sponsorship or endorsement by PEI. The marks are clearly used to
describe the title she received from PEI in 1981, a title that helps describe
who she is. It would be unreasonable to assume that the Chicago Bulls sponsored
a website of Michael Jordan's simply because his name appeared with the
appellation "former Chicago Bull." Similarly, in this case, it would be
unreasonable to assume that PEI currently sponsors or endorses someone who
describes herself as a "Playboy Playmate of the Year in 1981." The designation
of the year, in our case, serves the same function as the "former" in our
example. It shows that any sponsorship or endorsement occurred in the past.[^78]

[^77]: _Id_. 971 F.2d at 308.

[^78]: We express no opinion regarding whether an individual's use of a current
    title would suggest sponsorship or endorsement.

In addition to doing nothing in conjunction with her use of the marks to suggest
sponsorship or endorsement by PEI, Welles affirmatively disavows any sponsorship
or endorsement. Her site contains a clear statement disclaiming any connection
to PEI. Moreover, the text of the site describes her ongoing legal battles with
the company.[^79]

[^79]: By noting Welles' affirmative actions, we do not mean to imply that
    affirmative actions of this type are necessary to establish nominative
    use. _New Kids_ sets forth no such requirement, and we do not impose one
    here.

For the foregoing reasons, we conclude that Welles' use of PEI's marks in her
headlines and banner advertisements is a nominative use excepted from the law of
trademark infringement.

_2. Metatags._

Welles includes the terms "playboy" and "playmate" in her metatags. Metatags
describe the contents of a website using keywords. Some search engines search
metatags to identify websites relevant to a search.[^80] Thus, when an internet
searcher enters "playboy" or "playmate" into a search engine that uses metatags,
the results will include Welles' site.[^81] Because Welles' metatags do not
repeat the terms extensively, her site will not be at the top of the list of
search results. Applying the three-factor test for nominative use, we conclude
that the use of the trademarked terms in Welles' metatags is nominative.

[^80]: _See Brookfield Communications, Inc. v. West Coast Entertainment_, 174
    F.3d 1036, 1045 (9th Cir. 1999).

[^81]: We note that search engines that use their own summaries of websites, or
    that search the entire text of sites, are also likely to identify Welles'
    site as relevant to a search for "playboy" or "playmate," given the
    content of the site.

As we discussed above with regard to the headlines and banner advertisements,
Welles has no practical way of describing herself without using trademarked
terms. In the context of metatags, we conclude that she has no practical way of
identifying the content of her website without referring to PEI's trademarks.

A large portion of Welles' website discusses her association with Playboy over
the years. Thus, the trademarked terms accurately describe the contents of
Welles' website, in addition to describing Welles. Forcing Welles and others to
use absurd turns of phrase in their metatags, such as those necessary to
identify Welles, would be particularly damaging in the internet search context.
Searchers would have a much more difficult time locating relevant websites if
they could do so only by correctly guessing the long phrases necessary to
substitute for trademarks. We can hardly expect someone searching for Welles'
site to imagine the same phrase proposed by the district court to describe
Welles without referring to Playboy -- "the nude model selected by Mr. Hefner's
organization . . . ." Yet if someone could not remember her name, that is what
they would have to do. Similarly, someone searching for critiques of Playboy on
the internet would have a difficult time if internet sites could not list the
object of their critique in their metatags.

There is simply no descriptive substitute for the trademarks used in Welles'
metatags. Precluding their use would have the unwanted effect of hindering the
free flow of information on the internet, something which is certainly not a
goal of trademark law.[^82] Accordingly, the use of trademarked terms in the
metatags meets the first part of the test for nominative use.

[^82]: Admittedly, this hindrance would only occur as to search engines that use
    metatags to direct their searches.

We conclude that the metatags satisfy the second and third elements of the test
as well. The metatags use only so much of the marks as reasonably necessary[^83]
and nothing is done in conjunction with them to suggest sponsorship or
endorsement by the trademark holder. We note that our decision might differ if
the metatags listed the trademarked term so repeatedly that Welles' site would
regularly appear above PEI's in searches for one of the trademarked terms.[^84]

[^83]: It is hard to imagine how a metatag could use more of a mark than the
    words contained in it, but we recently learned that some search engines
    are now using pictures. Searching for symbols, such as the Playboy bunny,
    cannot be far behind. That problem does not arise in this case, however,
    and we need not address it.

[^84]: PEI asserts that it introduced evidence showing that Welles' site has
    been listed before PEI's on occasion. However, an examination of the
    evidence PEI cites shows that Welles' site, although sometimes ranked
    highly, was still listed below PEI's in search results.

_3. Wallpaper/watermark._

The background, or wallpaper, of Welles' site consists of the repeated
abbreviation "PMOY '81," which stands for "Playmate of the Year 1981."[^85]
Welles' name or likeness does not appear before or after "PMOY '81." The pattern
created by the repeated abbreviation appears as the background of the various
pages of the website. Accepting, for the purposes of this appeal, that the
abbreviation "PMOY" is indeed entitled to protection, we conclude that the
repeated, stylized use of this abbreviation fails the nominative use test.

The repeated depiction of "PMOY '81" is not necessary to describe Welles.
"Playboy Playmate of the Year 1981" is quite adequate. Moreover, the term does
not even appear to describe Welles -- her name or likeness do not appear before
or after each "PMOY '81." Because the use of the abbreviation fails the first
prong of the nominative use test, we need not apply the next two prongs of the
test.

[^85]: "PMOY" is not itself registered as a trademark. PEI argued before the
    district court that it is nonetheless protected because it is a
    well-known abbreviation for the trademarked term "Playmate of the Year."
    In this court PEI cites one affidavit that supports this argument.

Because the defense of nominative use fails here, and we have already determined
that the doctrine of fair use does not apply, we remand to the district court.
The court must determine whether trademark law protects the abbreviation "PMOY,"
as used in the wallpaper.

B. Trademark Dilution

The district court granted summary judgment to Welles as to PEI's claim of
trademark dilution. We affirm on the ground that all of Welles' uses of PEI's
marks, with the exception of the use in the wallpaper which we address
separately, are proper, nominative uses. We hold that nominative uses, by
definition, do not dilute the trademarks. Federal law provides protection
against trademark dilution:

The owner of a famous mark shall be entitled, subject to the principles of
equity and upon such terms as the court deems reasonable, to an injunction
against another person's commercial use in commerce of a mark or trade name, if
such use begins after the mark has become famous and causes dilution of the
distinctive quality of the mark. . . .[^86]

[^86]: 15 U.S.C. § 1125(c)(1).

Dilution, which was not defined by the statute, has been described by the courts
as "the gradual 'whittling away' of a trademark's value."[^87] Traditionally,
courts have recognized two forms of dilution: blurring and tarnishment. Blurring
occurs when another's use of a mark creates "the possibility that the mark will
lose its ability to serve as a unique identifier of the plaintiff's
product."[^88] Tarnishment, on the other hand, occurs "when a famous mark is
improperly associated with an inferior or offensive product or service."[^89] As
we recognized in _Panavision_, dilution may occur through uses on the internet
as well as elsewhere.[^90]

[^87]: _Academy of Motion Picture Arts & Sciences v. Creative House Promotions_,
    _Inc._, 944 F.2d 1446, 1457 (9th Cir. 1991) (_citing_ J. McCarthy,
    _Trademarks and Unfair Competition_, § 24: 13 (2d ed. 1984)).

[^88]: _Panavision Int'l, L.P. v. Toeppen_, 141 F.3d 1316, 1326 n. 7 (9th Cir.
    1998).

[^89]: _Id_.

[^90]: _Id_. at 1326-27.

Dilution works its harm not by causing confusion in consumers' minds regarding
the source of a good or service, but by creating an association in consumers'
minds between a mark and a different good or service.[^91] As explained in a
First Circuit case, in dilution (as compared to infringement) "an entirely
different issue is at stake --not interference with the source signaling
function but rather protection from an appropriation of or free riding on the
investment [the trademark holder] has made in its [trademark]."[^92] Thus, for
example, if a cocoa maker began using the "Rolls Royce" mark to identify its hot
chocolate, no consumer confusion would be likely to result. Few would assume
that the car company had expanded into the cocoa making business. However, the
cocoa maker would be capitalizing on the investment the car company had made in
its mark. Consumers readily associate the mark with highly priced automobiles of
a certain quality. By identifying the cocoa with the Rolls Royce mark, the
producer would be capitalizing on consumers' association of the mark with high
quality items. Moreover, by labeling a different product "Rolls Royce," the
cocoa company would be reducing the ability of the mark to identify the mark
holder's product. If someone said, "I'm going to get a Rolls Royce," others
could no longer be sure the person was planning on buying an expensive
automobile. The person might just be planning on buying a cup of cocoa. Thus,
the use of the mark to identify the hot chocolate, although not causing consumer
confusion, would cause harm by diluting the mark.

[^91]: _See_ 4 J. McCarthy, _Trademarks and Unfair Competition_, § 24: 70 (4th
    ed. 2001).

[^92]: _I.P. Lund Trading ApS v. Kohler Co._ 163 F.3d 27, 50 (1st Cir. 1998).

Uses that do not create an improper association between a mark and a new product
but merely identify the trademark holder's products should be excepted from the
reach of the anti-dilution statute. Such uses cause no harm. The anti-dilution
statute recognizes this principle and specifically excepts users of a trademark
who compare their product in "commercial advertising or promotion to identify
the competing goods or services of the owner of the famous mark."[^93]

[^93]: 15 U.S.C. § 1125(c)(4)(A).

For the same reason uses in comparative advertising are excepted from
anti-dilution law, we conclude that nominative uses are also excepted. A
nominative use, by definition, refers to the trademark holder's product. It does
not create an improper association in consumers' minds between a new product and
the trademark holder's mark.

When Welles refers to her title, she is in effect referring to a product of
PEI's. She does not dilute the title by truthfully identifying herself as its
one-time recipient any more than Michael Jordan would dilute the name "Chicago
Bulls" by referring to himself as a former member of that team, or the two-time
winner of an Academy Award would dilute the award by referring to him or herself
as a "two-time Academy Award winner." Awards are not diminished or diluted by
the fact that they have been awarded in the past.

Similarly, they are not diminished or diluted when past recipients truthfully
identify themselves as such. It is in the nature of honors and awards to be
identified with the people who receive them. Of course, the conferrer of such
honors and awards is free to limit the honoree's use of the title or references
to the award by contract. So long as a use is nominative, however, trademark law
is unavailing.

The one exception to the above analysis in this case is Welles' use of the
abbreviation "PMOY" on her wallpaper. Because we determined that this use is not
nominative, it is not excepted from the anti-dilution provisions. Thus, we
reverse as to this issue and remand for further proceedings. We note that if the
district court determines that" PMOY" is not entitled to trademark protection,
PEI's claim for dilution must fail. The trademarked term, "Playmate of the Year"
is not identical or nearly identical to the term "PMOY." Therefore, use of the
term "PMOY" cannot, as a matter of law, dilute the trademark "Playmate of the
Year."[^94]

[. . . .]

[^94]: _See Luigino's, Inc. v. Stouffer Corp._, 170 F.3d 827, 832 (8th Cir.
    1999) (holding that marks must be "similar enough that a significant
    segment of the target group of customers sees the two marks as
    essentially the same"); J. McCarthy, _McCarthy on Trademarks and Unfair
    Competition_, § 24: 90.2 (4th ed. 2001).

IV.

Conclusion

For the foregoing reasons, we affirm the district court's grant of summary
judgment as to PEI's claims for trademark infringement and trademark dilution,
with the sole exception of the use of the abbreviation "PMOY." We reverse as to
the abbreviation and remand for consideration of whether it merits protection
under either an infringement or a dilution theory. We also affirm as to PEI's
claims for breach of contract. In a separate memorandum disposition, we resolve
the issues raised by Welles' cross-appeal.

AFFIRMED in part, REVERSED and REMANDED in part. Costs to Terri Welles and Terri
Welles, Inc.

##### Discussion

1.  Consider how the _New Kids on the Block_ factors apply to a hypothetical
    project name which uses a trademark. Is the use of the original project name
    a descriptive reference to the original project? Would the original
    project would be readily identifiable without the use of the trademark? Does
    it use more of the trademarked word than is necessary? Would the use of the
    trademarked word suggest sponsorship or endorsement by the original
    trademark holder?

1.  How relevant is the likelihood of confusion of consumers based on convention? For example, consider to what extent the reuse of a project name in a fork may indicate to others users that the fork is officially affiliated or endorsed by the original project. Arguably the GitHub community at large will be so familiar with the
    functionality and naming conventions of project forking that reuse of an original project name in a project fork would not confuse users as to any affiliation or endorsement. Is the GitHub community the relevant group of consumers? Would that likelihood of confusion be determinative? Would the balance change if a project has a policy governing when project forks may use the original project name?

1.  What are the reasons why a project forker may want to refer
    back to the original project? As assessed in _Welles_, are there adequate
    "descriptive substitutes" or would changing forking norms force users to
    "use absurd turns of phrases" in a way that would be "particularly damaging"
    and "have the unwanted effect of hindering the free flow of information on
    the internet"?[^95] Would a project detriment its own third party contributions by strictly prohibiting the use of its name in project forks?

1.  In addition to the nominative use exception to trademark infringement, there
    are also uses of trademarked words which are not considered "trademark use."
    For example, an entirely non-commercial use of trademarked words should not
    be considered "trademark use." Additionally, the functionality doctrine limits
    the enforceability of trademarks in order to curb abuse. _Autodesk, Inc. v.
    Dassault Systemes Solidworks Corp._ held that file extensions are functional
    and could not be trademarked, reasoning:[^CurbAbuse]

    > [N]o one can have rights to a trademark that is functional, because
    > trademark law is meant to promote competition by protecting a firm's
    > reputation, and not to inhibit competition by allowing a trademark owner
    > to control and monopolize a useful and functional product feature. Indeed,
    > without the functionality doctrine, trademarks could be abused to provide
    > the protections of patents, but with potentially limitless duration.

    Debate continues to rage over whether hashtags in social media are purely
    functional objects or source identifiers.[^96] What are other possible
    functional object uses in open source projects?

[^CurbAbuse]: Autodesk, Inc. v. Dassault Systemes Solidworks Corp._, 685 F.
    Supp. 2d 1023, 1025 (N.D. Cal. 2009) (citation omitted).

[^95]: _Playboy Enters. v. Welles_, 279 F.3d 796, 804 (9th Cir. 2002) ("There is
    simply no descriptive substitute for the trademarks used in Welles'
    metatags. Precluding their use would have the unwanted effect of
    hindering the free flow of information on the internet, something which
    is certainly not a goal of trademark law.") (footnote omitted).

[^96]: _See_ Carrie L. Kiedrowski & Charlotte K. Murphy, _Are Hashtags Capable
    of Trademark Protection under U.S. Law?_, INTABulletin (Feb. 1, 2016),
    https://www.inta.org/INTABulletin/Pages/AreHashtagsCapableofTMProtectionunderUSLaw-.aspx.

## License Terms' Bearing on Trademark Use

This section will provide excerpts of popular open source licenses, ranging from
a license that does not address trademark rights, to those that implicitly
address them, to those that explicitly disclaim any grant of trademark rights.

### MIT

--------------------------------------------------------------------------------

Excerpt from the MIT License[^97]

> Copyright &lt;YEAR&gt; &lt;COPYRIGHT HOLDER&gt;
>
> Permission is hereby granted, free of charge, to any person obtaining a copy
> of this software and associated documentation files (the "Software"), to deal
> in the Software without restriction, including without limitation the rights
> to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
> copies of the Software, and to permit persons to whom the Software is
> furnished to do so, subject to the following conditions:
>
> The above copyright notice and this permission notice shall be included in all
> copies or substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
> FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
> AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
> LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
> OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
> SOFTWARE.

[^97]: _The MIT License_, Open Source Initiative,
    [https://opensource.org/licenses/MIT](https://opensource.org/licenses/MIT)
    (last visited Dec. 12, 2017) (CC-BY 4.0).

#### Discussion

1.  Do you see any terms in this license that explicitly address trademark
    rights? Could trademarks be implied?

1.  A number of message board discussions are concerned about losing trademark
    rights in a logo if they release a project under an MIT license.[^98] Could
    logos also be protected by other intellectual property
    rights? If an entity added its logo to an open source project it published as an image within the
    library, and applied the MIT license to the project, what legal
    ramifications would this have for the logo?

[^98]: _See, e.g._, _Do I retain right to my extension's logo if I use MIT
    license in my Firefox extension?_, StackExchange Discussion Board,
    [https://opensource.stackexchange.com/questions/5718/company-logo-in-an-mit-licensed-project](https://opensource.stackexchange.com/questions/5718/company-logo-in-an-mit-licensed-project)
    (last visited Dec. 13, 2017); _How should I license my project's logo?_,
    StackExchange Discussion Board,
    [https://opensource.stackexchange.com/questions/2224/how-should-i-license-my-projects-logo](https://opensource.stackexchange.com/questions/2224/how-should-i-license-my-projects-logo)
    (last visited Jan. 2, 2018 ).

### BSD-3-Clause

--------------------------------------------------------------------------------

Excerpt from the 3-Clause BSD License[^99]

> Copyright <YEAR> <COPYRIGHT HOLDER>
>
> [. . .]
>
> 1\. Redistributions of source code must retain the above copyright notice,
> this list of conditions and the following disclaimer.
>
> [. . .]
>
> 3\. Neither the name of the copyright holder nor the names of its contributors
> may be used to endorse or promote products derived from this software without
> specific prior written permission.
>
> [. . . .]

[^99]: _The 3-Clause BSD License_, Open Source Initiative,
    [https://opensource.org/licenses/BSD-3-Clause](https://opensource.org/licenses/BSD-3-Clause)
    (last visited Dec. 13, 2017) (CC-BY 4.0).

#### Discussion

1.  In this context, what does the "name of the copyright holder" mean? Could
    that be the name of the entity releasing the software? If so, based on your
    reading of _Planetary Motion_, could the project name also be a trademark?
    Consider the application of the common law requirements stated by _Planetary
    Motion_: use in commerce and priority of ownership.

1.  If Company released open source software Project, and Independent Engineer
    builds on that software to facilitate illegal transactions online, would
    clause 3 prevent Independent Engineer from using the Company name for his
    additions?

1.  Clause 1 of the BSD 3-clause license requires all redistributions to reproduce the
    above copyright notice, which could include the original author's name. How
    does this requirement interact with Section 3's prohibition against using
    the copyright holder to endorse or promote products? Could republishing the
    license in derivative software itself appear to be endorsement or
    affiliation?

1.  As a practical matter, what would be the most effective way for an open
    source project to establish acceptable use guidelines for trademarks,
    assuming that the project owners wish to permit certain uses? Based on your own
    experiences and your understanding of the cases in this chapter, consider the convenient accessibility of including guidelines in the
    license itself versus the flexibility of maintaining a separate
    trademark policy document.

### PHP-3.0

--------------------------------------------------------------------------------

Excerpt from the PHP License, version 3.0[^100]

> 4\. Products derived from this software may not be called "PHP", nor may "PHP"
> appear in their name, without prior written permission from group@php.net. You
> may indicate that your software works in conjunction with PHP by saying "Foo
> for PHP" instead of calling it "PHP Foo" or "phpfoo"

[^100]: _The PHP License 3.0_, Open Source Initiative,
    [https://opensource.org/licenses/PHP-3.0](https://opensource.org/licenses/PHP-3.0)
    (last visited Dec. 13, 2017) (CC-BY 4.0).

#### Discussion

1.  Based on your understanding of nominative use from _Playboy_, is it possible
    for PHP to dictate acceptable use of their name in this manner? Would the
    use of "PHP" without prior written permission still be legally defensible in some
    contexts? Would a project named "PHPabulous" be permissible nominative use
    or trademark infringement? Does nominative use overcome more restrictive license terms?

1.  If written permission was granted for one project to use PHP, would all
    subsequent contributors also require written permission for PHP to appear in
    forks and patches of the permitted PHP-named project? Is there a separate
    goodwill value in accepting the preferences of the license author regardless
    of whether they are enforceable? Consider all of Facebook's reasons for
    naming its PHP transpiler "HipHop for PHP" in accordance with the
    conventions stated in this license.[^101]

1.  How does the PHP license's naming convention interact with other licenses
    and naming conventions? Could PHP-licensed software be combined with GPL
    licensed software and then redistributed? Could this combination be
    distributed as binary? Could it be combined into software with PHP in its
    title?

[^101]: Haiping Zhao, _HipHop for PHP: Move Fast_ (Feb. 2, 2010, 9:41 AM),
    https://www.facebook.com/notes/facebook-engineering/hiphop-for-php-move-fast/280583813919.

### Apache 2.0

--------------------------------------------------------------------------------

Excerpt from the Apache License, Version 2.0, January 2004[^102]

> 6\. Trademarks. This License does not grant permission to use the trade names,
> trademarks, service marks, or product names of the Licensor, except as
> required for reasonable and customary use in describing the origin of the Work
> and reproducing the content of the NOTICE file.

[^102]: _Apache License, Version 2.0_, Apache Foundation,
    [https://www.apache.org/licenses/LICENSE-2.0](https://www.apache.org/licenses/LICENSE-2.0)
    (Jan. 2004).

#### Discussion

1.  Is it necessary for the Apache license to explicitly permit uses of the
    names and marks "as required for reasonable and customary use in describing
    the origin of the Work" or does this necessarily overlap with the legal
    defense of nominative use? Is this intended as guidance for trademark jurisdictions that lack the nominative use defense? 

1.  As a practical matter, is there additional information that licensees might
    want about the trademark permissions granted or not granted under the Apache
    license? For example, the Apache Foundation itself publishes a trademark
    policy and describes what it considers to be its trademarks.[^103]

[^103]: _Apache License FAQ_, Apache Foundation,
    [http://www.apache.org/foundation/license-faq.html#Marks](http://www.apache.org/foundation/license-faq.html#Marks)
    ("'Apache', 'Apache Software Foundation', the multicoloured feather, and
    the various Apache project names and logos are either registered
    trademarks or trademarks of The Apache Software Foundation in the United
    States and other countries. Please see our Trademark Policy for details
    of how to use Apache project trademarks or our helpful site map of
    trademark resources."); _see also Apache Trademark Policy_, Apache
    Foundation,
    [http://www.apache.org/foundation/marks/](http://www.apache.org/foundation/marks/)
    (v1.1, 2014).

### GNU GPL v.3

--------------------------------------------------------------------------------

Excerpt from the GNU General Public License, Version 3[^104]

> Notwithstanding any other provision of this License, for material you add to a
> covered work, you may (if authorized by the copyright holders of that
> material) supplement the terms of this License with terms:
>
> *   a) Disclaiming warranty or limiting liability differently from the terms
>     of sections 15 and 16 of this License; or
> *   b) Requiring preservation of specified reasonable legal notices or author
>     attributions in that material or in the Appropriate Legal Notices
>     displayed by works containing it; or
> *   c) Prohibiting misrepresentation of the origin of that material, or
>     requiring that modified versions of such material be marked in reasonable
>     ways as different from the original version; or
> *   d) Limiting the use for publicity purposes of names of licensors or
>     authors of the material; or
> *   e) Declining to grant rights under trademark law for use of some trade
>     names, trademarks, or service marks; or
> *   f) Requiring indemnification of licensors and authors of that material by
>     anyone who conveys the material (or modified versions of it) with
>     contractual assumptions of liability to the recipient, for any liability
>     that these contractual assumptions directly impose on those licensors and
>     authors.
>
> All other non-permissive additional terms are considered "further
> restrictions" within the meaning of section 10. [. . . .]

[^104]: _GNU General Public License v.3_, GNU Operating System,
    [https://www.gnu.org/licenses/gpl-3.0.en.html](https://www.gnu.org/licenses/gpl-3.0.en.html)
    (Jun. 29, 2007).

#### Discussion

1.  If a license provision is merely optional, as with the trademark section
    above, does that lead to license proliferation?[^105] Could the inclusion of
    the optional trademark provision complicate license scanning?

1.  Apart from section "e," which explicitly mentions trademark, are there other
    provisions which could bear on trademark protections?

    *   Based on your understanding of _Freecycle_ how might subsection "c"
        serve a trademark function by protecting the source identifier? Is
        merely suggesting that a licensor can adopt additional trademark
        protections adequate control over the uses associated with the licensed
        marks?

    *   Based on your reading of _Playboy Enters. v. Welles_, how could
        nominative use interact with the intent of subsection "d" to limit "the
        use for publicity purposes of names of licensors or authors of the
        material"?

[^105]: As defined in Wikipedia, "License proliferation is the phenomena of an
    abundance of already existing and the continued creation of new software
    licenses for software and software packages in the FOSS ecosystem.
    License proliferation affects the whole FOSS ecosystem negatively by the
    burden of increasingly complex license selection, license interaction,
    and license compatibility considerations." _License proliferation_,
    Wikipedia,
    [https://en.wikipedia.org/wiki/License_proliferation](https://en.wikipedia.org/wiki/License_proliferation)
    (last visited Jan. 4, 2017) (CC-BY-SA 4.0); _see also_ _The License
    Proliferation Project_, Open Source Initiative,
    [https://opensource.org/proliferation](https://opensource.org/proliferation)
    (last visited Jan. 4, 2017) (CC-BY 4.0) ("This explosion of choice in
    licensing reflected both the interest in Open Source as well as the many
    particular ways in which people wanted to create and or manage their
    Open Source software. Unfortunately, while all of these licenses provide
    the freedom to read, modify, and share source code, many of the licenses
    were legally incompatible with other free and open source licenses,
    seriously constraining the ways in which developers could innovate by
    _combining_ rather than merely _extending_ Open Source software.").

## Trademark Usage Guidelines and Enforcement Policies

There are many reasons for a commercial actor to develop, register, and police its
trademarks. The careful selection of a brand name will
forestall accusations that its brand infringes another trademark. Consistent,
regimented use of the brand in commerce should permit the brand to obtain
trademark status. Registration of the brand as a trademark will deter
infringement, prevent the registration of similar trademarks, and facilitate
enforcement efforts. Policing the manner in which others use the trademark will help retain the strength of the mark. Balanced enforcement of a trademark can preserve the distinctiveness of an exclusive source identifier while allowing for legitimate fair uses.

Organizations often maintain trademark policies that establish the
organization's approach toward trademark enforcement. The Wikimedia
Foundation is one such organization, and it has published its trademark enforcement
policy publicly at
[https://wikimediafoundation.org/wiki/Trademark_policy](https://wikimediafoundation.org/wiki/Trademark_policy).
This policy provides valuable insight into the thinking of an organization
engaged in the collaborative production of open content.

### Wikimedia Foundation Trademark Policy

--------------------------------------------------------------------------------

A notable feature of the Wikimedia Foundation's enforcement policy is that there
are very few uses of the trademark that the policy seeks to prevent.[^106] The
policy explicitly permits uses of the trademarks to create mimicking sites if
they are clearly parodies. This enforcement carve-out is consistent with
trademark nominative use precedent,[^Mattel] but is not behavior that every
organization would want to encourage.

[^106]: _Trademark Policy_, Wikimedia Foundation,
    [https://wikimediafoundation.org/wiki/Trademark_policy](https://wikimediafoundation.org/wiki/Trademark_policy)
    (last visited Jan. 4, 2017) (CC-BY-SA 3.0).

[^Mattel]: _See_ _Mattel, Inc. v. MCA Records_, 296 F.3d 894 (2002), _available
    at_ https://scholar.google.com/scholar_case?case=4174039731032587001.

Excerpt:

> 3 When you may use the Wikimedia marks without asking us
>
> 3.1 Use of trademarks on the Wikimedia sites
>
> You may use and remix the Wikimedia marks on the Wikimedia sites as you
> please.
>
> 3.2 Community-focused events
>
> You may use the trademarks for events that promote our mission and are
> intended to be predominantly attended by Wikimedia community members. These
> are events like hackathons, editor meetups, photographer excursions, and
> WikiCons.
>
> For example, you can put the Wikipedia puzzle globe logo on banners and
> posters at an edit-a-thon you have organized.
>
> GLAM initiatives and photo contests require a Quick License under Section 4.1.
> This provision does not allow you to use the marks for fundraising.
>
> 3.3 Outreach and recruiting new contributors
>
> You may use the marks consistent with our mission to educate people about the
> Wikimedia sites and to recruit new contributors, as long as you make it clear
> that you do not work for the Wikimedia Foundation. You can create educational
> material or banners to decorate a public fair stand or to publicize an
> edit-a-thon. This provision does not allow you to use the marks for
> fundraising.
>
> 3.4 Community logo use
>
> The Wikimedia Community logo can be used freely. But you may not file
> trademark applications incorporating the logo. The Wikimedia community wants
> to ensure that the logo remains available for all to use.
>
> 3.5 Discussing something other than Wikimedia sites (fair use)
>
> Wordmarks can sometimes have a primary meaning, in addition to representing a
> brand (like the words "apple" or "facebook"). Our wordmarks were not real
> words before our projects were created. But we will interpret fair use broadly
> to include the use of our wordmarks when you clearly mean to talk about
> something other than the Wikimedia sites.
>
> 3.6 Refer to Wikimedia sites (nominative use)
>
> You can use the non-stylized wordmarks (e.g., "Wikipedia") to describe: * A
> Wikimedia site or another aspect of the Wikimedia movement in a text (e.g., "I
> love reading about coal balls on Wikipedia"). * A derivative work of Wikimedia
> content in a way that is not misleading (e.g., "the encyclopedic content on
> this site is derived from Wikipedia"). You may use all Wikimedia marks on your
> own website as a hyperlink to the Wikimedia sites. The use of logos in
> hyperlinks should follow the Visual Identity Guidelines (e.g., the marks may
> be resized, but not modified in any other way).
>
> Here are some other specific cases of nominative use:
>
> 3.6.1 News reporting
>
> You may use the Wikimedia marks to make truthful statements about the
> Wikimedia sites in news reports and commentary.
>
> 3.6.2 Personal blogs and social media
>
> You may use the Wikimedia marks to make or illustrate truthful statements
> about the Wikimedia sites in personal blogs and social media. But please do
> not do it to imply endorsement by or affiliation with the Wikimedia
> Foundation. To avoid confusion, do not use the Wikimedia logos in the
> background, as your profile image, or in the header of your blog, in the name
> of your blog, or in your social media username. This section is not meant to
> restrict your use of the Community logo under Section 3.4.
>
> 3.6.3 Artistic, scientific, literary, political, and other non-commercial uses
>
> You can use the Wikimedia marks to discuss the Wikimedia sites in artistic,
> scientific, literary, and political work. But please send us a request if you
> want to place a Wikimedia mark on the cover of your book, display a Wikimedia
> mark in a movie, or organize an event or presentation that could be
> interpreted to be endorsed by the Wikimedia Foundation. For more information,
> please see Section 4. You may use the marks in satire or jokes. To avoid
> confusing users that your work is affiliated with the Wikimedia sites, it may
> be helpful to mark your work as "satire" or "parody."
>
> 4 Special uses that require permission
>
> All uses that are not allowed under Section 3 or prohibited by Section 5 of
> this policy require a trademark license.
>
> [. . . .]
>
> 5 Prohibited uses
>
> 5.1. Misleading mirrors and mimicking sites
>
> Please do not create a website that mimics the "look and feel" of a Wikimedia
> site. This especially applies to imitated Wikipedia articles. If you have a
> good reason to create a mimicking site, please contact us at
> trademarks@wikimedia.org.
>
> You do not need to contact us if you just want to use the MediaWiki software
> to create a wiki or if your mimicking site is clearly a parody.
>
> If you create a mirror, make sure to comply with the relevant licenses for the
> content. Avoid copying links to Wikimedia policies and contact details. Please
> do not use the Wikimedia marks in a mirror of a Wikimedia site.
>
> 5.2 Linking to non-Wikimedia sites
>
> You may use Wikimedia marks to link to Wikimedia sites only. Please refer to
> Links to Wikimedia sites if you want to link to a Wikimedia site from your
> website.
>
> 5.3 Misrepresentation
>
> When you use a Wikimedia mark under this policy, please use it to represent
> only the project for which it stands. Please do not create the impression that
> your use is in any way endorsed, sponsored by, or is part of the Wikimedia
> Foundation. This section also applies when you are granted a license to use a
> mark that doesn't permit you to suggest such an endorsement.
>
> 6 Trademark Misuse
>
> 6.1 Reporting misuse
>
> Fighting trademark misuse is very important. We put a lot of effort into going
> after cases of trademark infringement because we want to protect the valuable
> trademark rights the community has created. If you see a mark being used in
> any way that could be infringing, please tell us! Just send an email to
> legal-tm-vio@wikimedia.org or fill in this form. We really appreciate your
> help!
>
> 6.2 Revoking permission for misuses
>
> We may revoke the right to use the Wikimedia marks under this policy at any
> time by providing notice in any manner if we determine that a trademark use is
> inconsistent with our mission or could harm community members, movement
> organizations, or the Wikimedia Foundation.

#### Discussion

1.  Section 4 of the Trademark Enforcement Policy states that any uses not
    expressly permitted in Section 3 require a license. Is this enforceable? How well does Section 3 capture nominative fair uses?

### Linux Foundation Trademark Usage Guidelines

--------------------------------------------------------------------------------

The Linux Foundation does not publicly elaborate on its trademark enforcement
philosophy but does maintain Trademark Usage Guidelines.[^108] In a similar
fashion to Wikimedia, the Linux Foundation
includes in its Guidelines an overview of the rights and responsibilities one
has when using someone else's trademarks. This portion of the
Guidelines includes admonishments of activities that could be detrimental to the
trademarks being used, but is also similar to Wikimedia in that it specifically addresses
fair use, including the fact that the law authorizes certain uses of others'
trademarks without permission.

Excerpt:

> **Rules that Apply to Trademarks In General**
>
> There are some basic rules that apply to any use of any trade or service mark
> that you do not own, including any mark of The Linux Foundation, without the
> express permission of the owner.
>
> *   A trademark should never be used as a verb or noun. A trademark should be
>     used only as an adjective followed by the generic name/noun.
> *   A trademark should not be used in the plural or possessive form.
> *   A trademark should not be altered or amended in any way. A mark should not
>     be combined with any other mark, hyphenated, abbreviated or displayed in
>     parts. A trademark that is depicted as two or more words should not be
>     compressed into one word. A logo should not be displayed with color
>     variations, or with other elements superimposed on top of the logo.
> *   A trademark should not be used as your domain name or as part of your
>     domain name.
> *   A trademark should not be used as part of your product name.
> *   A trademark should not be incorporated into your company's logos or
>     designs.
> *   A trademark notice should be used on the most prominent and/or first
>     appearance of each mark of The Linux Foundation, and a trademark notice
>     should not be changed. In particular, a ™ should not be changed to an ® in
>     a trademark notice by anyone other than the owner. If you are unsure about
>     whether a mark of The Linux Foundation is registered in your country,
>     please contact us for additional guidance as to what trademark symbol you
>     should use.
>
> There are also some basic rights that everyone has to use any trademark, which
> are often referred to as "fair use," and The Linux Foundation does not intend
> to restrict those rights. You may make fair use of word marks to make true
> factual statements. But fair use does not permit you to state or imply that
> the owner of a mark produces, endorses, or supports your company, products, or
> services. Even when making fair use of a trademark, you should acknowledge the
> owner of the trademark with a trademark notice, such as the notice displayed
> on The Linux Foundation project websites.
>
> **Rules and Policies Applicable to Marks Owned by The Linux Foundation**
>
> In addition to the generally applicable rules discussed above, there are a few
> specific rules that we ask everyone to follow when using trademarks owned by
> The Linux Foundation.
>
> *   Use the full form of any trademarks (e.g., "The Linux Foundation") in the
>     first reference in all documents of mass communication, including
>     marketing collateral and web pages. You may then use any abbreviated or
>     short form references (e.g. "TLF") within the same the document where the
>     full form has already been used.
> *   Use The Linux Foundation's trademarks in a form that distinguishes them
>     from the text around them, such as by capitalization, bold or italic
>     fonts, or with quotation marks. Any use of registered trademarks listed
>     above should include the ® symbol immediately after the first usage (e.g.,
>     "The Linux Foundation® projects develop open source…."). Any use of
>     unregistered trademarks listed above should include a TM immediately after
>     the first usage (e.g., "The Core Infrastructure Initiative TM community
>     seeks to secure….")
> *   Do not use The Linux Foundation trademarks in a manner that would
>     disparage The Linux Foundation or its projects (e.g., untruthful
>     advertising, false/misleading promotional materials, etc.).
> *   Do not use a The Linux Foundation logo on the cover of a book or magazine
>     without written permission from The Linux Foundation.
> *   Do not use The Linux Foundation trademarks more prominently than your own
>     company, product or service name.
> *   Do not use a logo of The Linux Foundation on posters, brochures, signs,
>     websites, or other marketing materials to promote your events, products or
>     services without written permission from The Linux Foundation.
> *   Do not refer to a product or service as being certified under any of The
>     Linux Foundation's marks unless your company has successfully undergone
>     the requisite compliance testing and has explicit authorization to use
>     such terms from The Linux Foundation.
> *   Do not attempt to claim or assert any ownership rights in any mark of The
>     Linux Foundation and do not attempt to register any The Linux Foundation
>     trademark as a trademark, trade name, domain name, or "doing business as"
>     name, alone or (unless specifically licensed) in combination with your own
>     trademarks.

[^108]: _The Linux Foundation's Trademarks_, Linux Foundation,
    [https://www.linuxfoundation.org/trademark-usage/](https://www.linuxfoundation.org/trademark-usage/)
    (last visited Jan. 4, 2018) (CC-BY-4.0).

#### Discussion

1.  If someone were to use the Wikimedia Foundation or Linux Foundation's
    trademarks with permission, would they be contractually bound to observe the
    rules the foundations have placed on how their trademarks may be used?

1.  Would all of the actions proscribed by the Linux Foundation's Usage
    Guidelines constitute prima facie grounds for a trademark infringement suit?

1.  The Mozilla Foundation is another organization focused on producing open
    source software that maintains a public trademark policy, available at
    [https://www.mozilla.org/en-US/foundation/trademarks/policy/](https://www.mozilla.org/en-US/foundation/trademarks/policy/).
    In what ways are these three foundations' policies similar? In what ways are
    they distinct? Do the commonalities in these three organizations' policies
    establish a consensus for how trademarks should be approached by open source
    communities?

### Pokemon Legal Information Notice

--------------------------------------------------------------------------------

The Pokemon Company has a trademark policy embedded in a concise Legal
Information notice on its website.[^109] The policy goes further than
advertising that the company will police its trademarks aggressively. It asserts
a compulsory license scheme whereby a commercial licensee's distribution of anything
containing or derived from the Pokemon Company's trademarks triggers a royalty-free
license of that content to The Pokemon Company.

> Legal Information
>
> © 2017 Pokémon. © 1995–2017 Nintendo/Creatures Inc./GAME FREAK inc. Pokémon,
> Pokémon character names, Nintendo 3DS, Nintendo DS, Wii, Wii U, and Wiiware
> are trademarks of Nintendo. The YouTube logo is a trademark of Google Inc.
> Other trademarks are the property of their respective owners.
>
> Distribution in any form and any channels now known or in the future of
> derivative works based on the copyrighted property trademarks, service marks,
> trade names and other proprietary property (Fan Art) of The Pokémon Company
> International, Inc., its affiliates and licensors (Pokémon) constitutes a
> royalty-free, non-exclusive, irrevocable, transferable, sub-licensable,
> worldwide license from the Fan Art's creator to Pokémon to use, transmit,
> copy, modify, and display Fan Art (and its derivatives) for any purpose. No
> further consideration or compensation of any kind will be given for any Fan
> Art. Fan Art creator gives up any claims that the use of the Fan Art violates
> any of their rights, including moral rights, privacy rights, proprietary
> rights publicity rights, rights to credit for material or ideas or any other
> right, including the right to approve the way such material is used. In no
> uncertain terms, does Pokémon's use of Fan Art constitute a grant to Fan Art's
> creator to use the Pokémon intellectual property or Fan Art beyond a personal,
> noncommercial home use.

[^109]: _Legal Information_, Pokemon Co. Int'l, Inc.,
    [https://www.pokemon.com/us/legal/](https://www.pokemon.com/us/legal/)
    (2017).

#### Discussion

1.  Are the terms of the Pokemon Company's Legal Information notice enforceable?
    What significance does the distinction between copyright and trademark play,
    if any? 

1.  Must a creator of Pokemon "Fan Art" be aware of this policy in order to be
    bound by it in any way?

<!-- Footnotes themselves at the bottom. -->

## Notes

