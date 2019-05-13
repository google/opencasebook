# Authorship in Open Source
{:.no_toc}

* Table of Contents
{:toc}

## Introduction

Collaborative authorship is a hallmark of the free and open source software
movement. The Linux kernel is the result of broad collaboration of tens of
thousands of distinct authors, contributing thousands of modifications every
year. But what are the legal consequences of collaborative authorship? Who
decides how the project is licensed? Who has standing to sue over infringement
of the project?

In order to discuss the legal ramifications of collaborative authorship, it is
critical to distinguish the different types of copyrightable works from the
different types of copyright property interests. These two subjects each play a
very important role in the assignment of rights to a copyright-protected work.

United States copyright law only recognizes two forms of property interest to
the copyright rights for that granular work: single-author authorship and joint
authorship. The rights to works authored by a single author vest in a single
entity.[^EntityType] The rights to works authored by joint authors are shared by
the joint authors, with each joint author enjoying an equal interest in the
undivided whole.

[^EntityType]: That entity may be the author as an independent actor, the
    author’s employer under a work for hire arrangement, or someone
    who has contracted the author to create the work as a work for
    hire. 17 U.S.C. § 101.

While 17 U.S.C. § 101 defines many different types of works, most important for
open source projects is the distinction between a standard, monolithic work of
authorship and a collective work of authorship.[^Distinction] A collective work
is a work like a periodical or anthology that consists of separate, identifiable
parts. Each part can be authored by an individual, independent author. A
traditional example of a collective work is an anthology of short stories
written by different authors. If a work qualifies as a collective work, the
copyright ownership of its constituent parts is held by the individual authors
of those parts. The publisher of the collective holds a thin copyright over the
selection and arrangement of the work as a collective, with narrow permission to
use the independent components in the context of publishing the collective work.
[^CollectiveDefinition] Conversely, a standard, monolithic work is one where all
of the parts of the work are interrelated, such as a novel, or a software
application.

[^Distinction]: This is entirely independent from the question of whether the
    work is jointly authored. A work can be both a collective work
    and be a work of joint authorship simultaneously.

[^CollectiveDefinition]: “[T]he owner of copyright in the collective work is
    presumed to have acquired only the privilege of
    reproducing and distributing the contribution as part
    of that particular collective work, any revision of
    that collective work, and any later collective work in
    the same series.” 17 U.S.C. § 201(c).

Lastly, writings play an important role in preempting questions about copyright
ownership and licensing for open source projects. The standard mechanism for
contributing to an open source project is the submission of a pull request,
which entails re-copying the entire repository along with the contributed
changes, together with all of the project’s existing documentation, when
submitting the contribution. Through this mechanism, a contributor is formally
publishing the contribution under the license of the project. Another common
device used by open source projects is a Contributor License Agreement (CLA) or
Developer Certificate of Origin (DCO), both of which can play an important role
in establishing the ownership and licensing of the content of open source
projects.

This chapter will address copyright’s legal framework around collaborative
authorship, specifically evaluating the copyright status of a contribution to a
larger work. This requires examining the distinction between jointly-authored
works and independently-authored works, the distinction between collective works
and monolithic works, and the role that writings can play in resolving
authorship ambiguity.

The first section of this chapter will address the criteria for establishing
that a work is a joint work, the property interest consequences of a joint work,
and the role that joint authorship plays in open source development. While forms
of joint authorship appear in many nation’s copyright laws, the concept varies from country to country.[^NimmerInternational] This
chapter presently focuses on the joint authorship mechanism under United States
law.

[^NimmerInternational]: _See_ 12 M. Nimmer, _Nimmer on Copyright_ V, Foreign
    Laws for a survey of international laws governing joint
    works.

The second section of this chapter addresses the minimum criteria for creating a
copyrightable work and discuss the application of this standard in the context
of open source contributions.

The third section addresses the role that writings play in governing copyright
ownership interests and work classifications in open source development.

But before delving into the cases, the Copyright Act’s definitions section lays
helpful foundations for discussing copyright property interests and work types.

### Definitions

**“Collective Work”** - “A ‘collective work’ is a work, such as a periodical
issue, anthology, or encyclopedia, in which a number of contributions,
constituting separate and independent works in themselves, are assembled into a
collective whole.”[^s101]

[^s101]: 17 U.S.C. § 101.

**“Compilation”** - “A ‘compilation’ is a work formed by the collection and
assembling of preexisting materials or of data that are selected, coordinated,
or arranged in such a way that the resulting work as a whole constitutes an
original work of authorship. The term ‘compilation’ includes collective
works.”[^Compilation]

[^Compilation]: _Id._

**“Contributions to Collective Works"** - “Copyright in each separate
contribution to a collective work is distinct from copyright in the collective
work as a whole, and vests initially in the author of the contribution. In the
absence of an express transfer of the copyright or of any rights under it, the
owner of copyright in the collective work is presumed to have acquired only the
privilege of reproducing and distributing the contribution as part of that
particular collective work, any revision of that collective work, and any later
collective work in the same series.”[^Contributions]

[^Contributions]: 17 U.S.C. § 201(c).

**Copyright to Compilations and Derivative Works** - "The copyright in a
compilation or derivative work extends only to the material contributed by the
author of such work, as distinguished from the preexisting material employed in
the work, and does not imply any exclusive right in the preexisting material.
The copyright in such work is independent of, and does not affect or enlarge the
scope, duration, ownership, or subsistence of, any copyright protection in the
preexisting material."[^103b]

[^103b]: 17 U.S.C. § 103(b).

**Copyrightable Work** - This critical term is not statutorily defined. The
minimum criteria for establishing a copyrightable work must instead be distilled
from case law:

> “The _sine qua non_ of copyright is originality. To qualify for copyright
> protection, a work[^WorkDefinition] must be original to the author. Original,
> as the term is used in copyright, means only that the work was independently
> created by the author (as opposed to copied from other works), and that it
> possesses at least some minimal degree of creativity. To be sure, the
> requisite level of creativity is extremely low; even a slight amount will
> suffice. The vast majority of works make the grade quite easily, as they
> possess some creative spark, "no matter how crude, humble or obvious" it might
> be. Originality does not signify novelty; a work may be original even though
> it closely resembles other works so long as the similarity is fortuitous, not
> the result of copying. To illustrate, assume that two poets, each ignorant of
> the other, compose identical poems. Neither work is novel, yet both are
> original and, hence, copyrightable.” [^Originality]

[^WorkDefinition]: “‘The two fundamental criteria of copyright protection [are]
    originality and fixation in tangible form. . . . The phrase
    “original works of authorship,” which is purposely left
    undefined, is intended to incorporate without change the
    standard of originality established by the courts under the
    [1909] copyright statute.’" _Feist Publ'ns, Inc. v. Rural
    Tel. Serv. Co._, 499 U.S. 340, 355, 111 S. Ct. 1282, 1292-93
    (1991) (citing H. R. Rep. No. 94-1476, p. 51 (1976); S. Rep.
    No. 94-473, p. 50 (1975)).

[^Originality]: _Id._ at 1287-88 (internal citations omitted).

**“Joint Work”** - “A ‘joint work’ is a work prepared by two or more authors
with the intention that their contributions be merged into inseparable or
interdependent parts of a unitary whole.”[^Joint1] “If joint authorship status
is accorded to person whose contribution is relatively minor, that person enjoys
all benefits of joint authorship.” [^Joint2]

[^Joint1]: 17 U.S.C. § 101.

[^Joint2]: _Bencich v. Hoffman_, 84 F. Supp. 2d 1053 (D. Ariz. 2000).

## Section 1 - Copyright Property Interests: The Role of The Joint And Individual Authorship Distinction in Open Source Development

Copyright can either be individually owned or jointly owned. This contrasts with
real property, where a parcel of land is recognized to be infinitely divisible,
and the forms of property interest that an individual can hold to a given piece
of real property vary considerably (fee simple, expectancy interest, tenancy,
life estate, etc.). Copyrighted works are not infinitely divisible. While any
piece of real property can be physically cut in half, it can be impossible to
separate a copyrighted work into fractional works with independent ownership.
Accordingly, there are only two statutorily-recognized forms of copyright
property interest that can attach to an individual work.

If a work is authored by one individual, then the copyright rights vest in that
one individual alone.[^Employed] That individual is the sole entity that can
license or transfer ownership of any of the copyright rights that attach to the
work or that can allege infringement of the work. If the individual received
ideas or input from someone else that constituted improvements or modifications
upon the author’s work, and not separate independently-copyrightable works of
authorship in themselves, the incorporation of such ideas or input might not
disturb the individual’s sole receipt of copyright ownership to the
work.[^Copyrightable]

[^Employed]: However, if the work were to constitute a Work Made For Hire, then
    sole copyright ownership would vest with the principal. 17 U.S.C. §
    201(b).

[^Copyrightable]: "A 'joint work' in [the Ninth] circuit 'requires each author
    to make an independently copyrightable contribution' to the
    disputed work." _Aalmuhammed v. Lee_, 202 F.3d 1227, 1231 (9th
    Cir. 2000) (quoting _Ashton-Tate Corp. v. Ross_, 916 F.2d 516,
    521 (9th Cir. 1990)).

Conversely, if the work is authored by two or more parties, with their
contributions combining to make interdependent parts of an inseparable whole,
and where it is the intent of the parties to be joint-authors of this singular
work, then joint authorship will apply.[^Joint101] For a jointly-authored work,
authorship vests initially in all joint-authors, with each joint-author enjoying
equal interest in the undivided whole.[^Joint201] The concept of joint
authorship is important for the creation of indivisible works that are the
product of collaboration, such as a single sculpture where two authors sculpted
interdependent parts.

[^Joint101]: 17 U.S.C. § 101.

[^Joint201]: 17 U.S.C. § 201(a).

The open source community is intrigued by the joint authorship model.[^Chestek]
However, it may be difficult to establish that an open source project is a joint
work without evidence that the co-authors unambiguously intended for the work to
be a joint work, and that there is a mutual intention to treat one another as
co-authors. As we examine the following cases, consider the asynchronous nature
of open source development and the various possible forms of relationships
between project creators, contributors, and forkers.

[^Chestek]: _See_ Pamela S. Chestek, _A Theory of Joint Authorship For Free and
    Open Source Software Projects_, (2017).

### _Aalmuhammed v. Lee_, 202 F.3d 1227 (9th Cir. 2000)

This seminal Ninth Circuit case on the subject of joint authorship concerned a
joint authorship claim by one of the production assistants for the movie
_Malcolm X_ who played a significant role in informing the movie’s depiction of
Malcolm X’s conversion to Islam. The _Aalmuhammed_ court established a
three-factor test for determining whether joint authorship exists in the
absence of a contract, and it continues to be employed in some circuits today.

#### Opinion

KLEINFELD, Circuit Judge: This is a copyright case involving a claim of
co-authorship of the movie _Malcolm X_. We reject the "joint work" claim but
remand for further proceedings on a quantum meruit claim.

I. FACTS

In 1991, Warner Brothers contracted with Spike Lee and his production companies
to make the movie _Malcolm X_, to be based on the book, _The Autobiography of
Malcolm X_. Lee co-wrote the screenplay, directed, and co-produced the movie,
which starred Denzel Washington as Malcolm X. Washington asked Jefri Aalmuhammed
to assist him in his preparation for the starring role because Aalmuhammed knew
a great deal about Malcolm X and Islam. Aalmuhammed, a devout Muslim, was
particularly knowledgeable about the life of Malcolm X, having previously
written, directed, and produced a documentary film about Malcolm X.

Aalmuhammed joined Washington on the movie set. The movie was filmed in the New
York metropolitan area and Egypt. Aalmuhammed presented evidence that his
involvement in making the movie was very extensive. He reviewed the shooting
script for Spike Lee and Denzel Washington and suggested extensive script
revisions. Some of his script revisions were included in the released version of
the film; others were filmed but not included in the released version. Most of
the revisions Aalmuhammed made were to ensure the religious and historical
accuracy and authenticity of scenes depicting Malcolm X's religious conversion
and pilgrimage to Mecca.

Aalmuhammed submitted evidence that he directed Denzel Washington and other
actors while on the set, created at least two entire scenes with new characters,
translated Arabic into English for subtitles, supplied his own voice for
voice-overs, selected the proper prayers and religious practices for the
characters, and edited parts of the movie during post production. Washington
testified in his deposition that Aalmuhammed's contribution to the movie was
"great" because he "helped to rewrite, to make more authentic." Once production
ended, Aalmuhammed met with numerous Islamic organizations to persuade them that
the movie was an accurate depiction of Malcolm X's life. Aalmuhammed never had a
written contract with Warner Brothers, Lee, or Lee's production companies, but
he expected Lee to compensate him for his work. He did not intend to work and
bear his expenses in New York and Egypt gratuitously. Aalmuhammed ultimately
received a check for $ 25,000 from Lee, which he cashed, and a check for $
100,000 from Washington, which he did not cash.

During the summer before Malcolm X's November 1992 release, Aalmuhammed asked
for a writing credit as a co-writer of the film, but was turned down. When the
film was released, it credited Aalmuhammed only as an "Islamic Technical
Consultant," far down the list. In November 1995, Aalmuhammed applied for a
copyright with the U.S. Copyright Office, claiming he was a co-creator,
co-writer, and co-director of the movie. The Copyright Office issued him a
"Certificate of Registration," but advised him in a letter that his "claims
conflict with previous registrations" of the film.

On November 17, 1995, Aalmuhammed filed a complaint against Spike Lee, his
production companies, and Warner Brothers, (collectively "Lee"), as well as
Largo International, N.V., and Largo Entertainment, Inc. (collectively "Largo"),
and Victor Company of Japan and JVC Entertainment, Inc. (collectively "Victor").
The suit sought declaratory relief and an accounting under the Copyright Act. In
addition, the complaint alleged breach of implied contract, quantum meruit, and
unjust enrichment, and federal (Lanham Act) and state unfair competition claims.
The district court dismissed some of the claims under Rule 12(b)(6) and the rest
on summary judgment.

II. ANALYSIS

A. Copyright claim

Aalmuhammed claimed that the movie Malcolm X was a "joint work" of which he was
an author, thus making him a co-owner of the copyright.[^Aal2] He sought a
declaratory judgment to that effect, and an accounting for profits. He is not
claiming copyright merely in what he wrote or contributed, but rather in the
whole work, as a co-author of a "joint work." [^Aal3] The district court granted
defendants summary judgment against Mr. Aalmuhammed's copyright claims. We
review de novo.[^Aal4]

[^Aal2]: 17 U.S.C. §§ 101, 201(a).

[^Aal3]: _Cf. Thomson v. Larson_, 147 F.3d 195, 206 (2nd Cir. 1998).

[^Aal4]: _See Covey v. Hollydale Mobilehome Estates_, 116 F.3d 830, 834 (9th
    Cir. 1997), _amended by_, 125 F.3d 1281 (1997).

Defendants argue that Aalmuhammed's claim that he is one of the authors of a
joint work is barred by the applicable statute of limitations. A claim of
authorship of a joint work must be brought within three years of when it
accrues.[^Aal5] Because creation rather than infringement is the gravamen of an
authorship claim, the claim accrues on account of creation, not subsequent
infringement, and is barred three years from "plain and express repudiation" of
authorship.[^Aal6]

[^Aal5]: _See_ 17 U.S.C. § 507(b); _Zuill v. Shanahan_, 80 F.3d 1366, 1371 (9th
    Cir. 1996), _cert. denied_, 519 U.S. 1090, 136 L. Ed. 2d 710, 117 S.
    Ct. 763 (1997).

[^Aal6]: _Zuill_, 80 F.3d at 1371.

The movie credits plainly and expressly repudiated authorship, by listing
Aalmuhammed far below the more prominent names, as an "Islamic technical
consultant." That repudiation, though, was less than three years before the
lawsuit was filed. The record leaves open a genuine issue of fact as to whether
authorship was repudiated before that. Aalmuhammed testified in his deposition
that he discussed with an executive producer at Warner Brothers his claim to
credit as one of the screenwriters more than three years before he filed suit.
Defendants argue that this discussion was an express repudiation that bars the
claim. It was not. Aalmuhammed testified that the producer told him "there is
nothing I can do for you," but "he said we would discuss it further at some
point." A trier of fact could construe that communication as leaving the
question of authorship open for further discussion. That leaves a genuine issue
of fact as to whether the claim is barred by limitations, so we must determine
whether there is a genuine issue of fact as to whether Aalmuhammed was an author
of a "joint work."

Aalmuhammed argues that he established a genuine issue of fact as to whether he
was an author of a "joint work," _Malcolm X_. The Copyright Act does not define
"author," but it does define "joint work":

> A "joint work" is a work prepared by two or more authors with the intention
> that their contributions be merged into inseparable or interdependent parts of
> a unitary whole.[^Aal7]

[^Aal7]: 17 U.S.C. § 101.

"When interpreting a statute, we look first to the language."[^Aal8] The
statutory language establishes that for a work to be a "joint work" there must
be (1) a copyrightable work, (2) two or more "authors," and (3) the authors must
intend their contributions be merged into inseparable or interdependent parts of
a unitary whole. A "joint work" in this circuit "requires each author to make an
independently copyrightable contribution" to the disputed work.[^Aal9] Malcolm X
is a copyrightable work, and it is undisputed that the movie was intended by
everyone involved with it to be a unitary whole. It is also undisputed that
Aalmuhammed made substantial and valuable contributions to the movie, including
technical help, such as speaking Arabic to the persons in charge of the mosque
in Egypt, scholarly and creative help, such as teaching the actors how to pray
properly as Muslims, and script changes to add verisimilitude to the religious
aspects of the movie. Speaking Arabic to persons in charge of the mosque,
however, does not result in a copyrightable contribution to the motion picture.
Coaching of actors, to be copyrightable, must be turned into an expression in a
form subject to copyright.[^Aal10] The same may be said for many of
Aalmuhammed's other activities. Aalmuhammed has, however, submitted evidence
that he rewrote several specific passages of dialogue that appeared in Malcolm
X, and that he wrote scenes relating to Malcolm X's Hajj pilgrimage that were
enacted in the movie. If Aalmuhammed's evidence is accepted, as it must be on
summary judgment, these items would have been independently copyrightable.
Aalmuhammed, therefore, has presented a genuine issue of fact as to whether he
made a copyrightable contribution. All persons involved intended that
Aalmuhammed's contributions would be merged into interdependent parts of the
movie as a unitary whole. Aalmuhammed maintains that he has shown a genuine
issue of fact for each element of a "joint work."

[^Aal8]: _Richardson v. United States_, 526 U.S. 813, 119 S. Ct. 1707, 1710, 143
    L. Ed. 2d 985 (1999).

[^Aal9]: _Ashton-Tate Corp. v. Ross_, 916 F.2d 516, 521 (9th Cir. 1990).

[^Aal10]: _See Ashton-Tate Corp. v. Ross_, 916 F.2d 516, 521 (9th Cir. 1990).

But there is another element to a "joint work." A "joint work" includes "two or
more authors."[^Aal11] Aalmuhammed established that he contributed substantially
to the film, but not that he was one of its "authors." We hold that authorship
is required under the statutory definition of a joint work, and that authorship
is not the same thing as making a valuable and copyrightable contribution. We
recognize that a contributor of an expression may be deemed to be the "author"
of that expression for purposes of determining whether it is independently
copyrightable. The issue we deal with is a different and larger one: is the
contributor an author of the joint work within the meaning of 17 U.S.C. § 101.

[^Aal11]: 17 U.S.C. § 101.

By statutory definition, a "joint work" requires "two or more authors."[^Aal12]
The word "author" is taken from the traditional activity of one person sitting
at a desk with a pen and writing something for publication. It is relatively
easy to apply the word "author" to a novel. It is also easy to apply the word to
two people who work together in a fairly traditional pen-and-ink way, like,
perhaps, Gilbert and Sullivan. In the song, "I Am the Very Model of a Modern
Major General," Gilbert's words and Sullivan's tune are inseparable, and anyone
who has heard the song knows that it owes its existence to both men, Sir William
Gilbert and Sir Arthur Sullivan, as its creative originator. But as the number
of contributors grows and the work itself becomes less the product of one or two
individuals who create it without much help, the word is harder to apply.

[^Aal12]: 17 U.S.C. § 101.

Who, in the absence of contract, can be considered an author of a movie? The
word is traditionally used to mean the originator or the person who causes
something to come into being, or even the first cause, as when Chaucer refers to
the "Author of Nature." For a movie, that might be the producer who raises the
money. Eisenstein thought the author of a movie was the editor. The "auteur"
theory suggests that it might be the director, at least if the director is able
to impose his artistic judgments on the film. Traditionally, by analogy to
books, the author was regarded as the person who writes the screenplay, but
often a movie reflects the work of many screenwriters. Grenier suggests that the
person with creative control tends to be the person in whose name the money is
raised, perhaps a star, perhaps the director, perhaps the producer, with control
gravitating to the star as the financial investment in scenes already shot
grows.[^Aal13] Where the visual aspect of the movie is especially important, the
chief cinematographer might be regarded as the author. And for, say, a Disney
animated movie like "The Jungle Book," it might perhaps be the animators and the
composers of the music.

[^Aal13]: _See_ Richard Grenier, _Capturing the Culture_, 206-07 (1991).

The Supreme Court dealt with the problem of defining "author" in new media in
_Burrow-Giles Lithographic Co. v. Sarony_.[^Aal14] The question there was, who
is the author of a photograph: the person who sets it up and snaps the shutter,
or the person who makes the lithograph from it. Oscar Wilde, the person whose
picture was at issue, doubtless offered some creative advice as well. The Court
decided that the photographer was the author, quoting various English
authorities: "the person who has superintended the arrangement, who has actually
formed the picture by putting the persons in position, and arranging the place
where the people are to be - the man who is the effective cause of that";
"'author' involves originating, making, producing, as the inventive or master
mind, the thing which is to be protected"; "the man who really represents,
creates, or gives effect to the idea, fancy, or imagination."[^Aal15] The Court
said that an "author," in the sense that the Founding Fathers used the term in
the Constitution,[^Aal16] was "'he to whom anything owes its origin; originator;
maker; one who completes a work of science or literature.'"[^Aal17]

[^Aal14]: _Burrow-Giles Lithographic Co. v. Sarony_, 111 U.S. 53, 61, 28 L. Ed.
    349, 4 S. Ct. 279 (1884).

[^Aal15]: _Id._ at 61 (quoting _Nottage v. Jackson_, 11 Q.B.D. 627 (1883)).

[^Aal16]: U.S. Const. Art. 1, § 8, cl. 8.

[^Aal17]: _Burrow-Giles_, 111 U.S. at 58 (quoting Worcester).

Answering a different question, what is a copyrightable "work," as opposed to
who is the "author," the Supreme Court held in Feist Publications that "some
minimal level of creativity" or "originality" suffices.[^Aal18] But that measure
of a "work" would be too broad and indeterminate to be useful if applied to
determine who are "authors" of a movie. So many people might qualify as an
"author" if the question were limited to whether they made a substantial
creative contribution that that test would not distinguish one from another.
Everyone from the producer and director to casting director, costumer,
hairstylist, and "best boy" gets listed in the movie credits because all of
their creative contributions really do matter. It is striking in Malcolm X how
much the person who controlled the hue of the lighting contributed, yet no one
would use the word "author" to denote that individual's relationship to the
movie. A creative contribution does not suffice to establish authorship of the
movie.

[^Aal18]: _Feist Publications, Inc. v. Rural Telephone Service Co., Inc._, 499
    U.S. 340, 345, 113 L. Ed. 2d 358, 111 S. Ct. 1282 (1991).

_Burrow-Giles_, in defining "author," requires more than a minimal creative or
original contribution to the work.[^Aal19] Burrow-Giles is still good law, and
was recently reaffirmed in _Feist Publications_.[^Aal20] _Burrow-Giles_ and _Feist
Publications_ answer two distinct questions; who is an author, and what is a
copyrightable work.[^Aal21] _Burrow-Giles_ defines author as the person to whom the
work owes its origin and who superintended the whole work, the "master
mind."[^Aal22] In a movie this definition, in the absence of a contract to the
contrary, would generally limit authorship to someone at the top of the screen
credits, sometimes the producer, sometimes the director, possibly the star, or
the screenwriter - someone who has artistic control. After all, in Burrow-Giles
the lithographer made a substantial copyrightable creative contribution, and so
did the person who posed, Oscar Wilde, but the Court held that the photographer
was the author.[^Aal23]

[^Aal19]: _Burrow-Giles Lithographic Co. v. Sarony_, 111 U.S. 53, 58, 28 L. Ed.
    349, 4 S. Ct. 279 (1883).

[^Aal20]: _Feist Publications, Inc. v. Rural Telephone Service Co., Inc._, 499
    U.S. 340, 346, 113 L. Ed. 2d 358, 111 S. Ct. 1282 (1991).

[^Aal21]: _See Burrow-Giles Lithographic Co. v. Sarony_, 111 U.S. 53, 28 L. Ed.
    349, 4 S. Ct. 279 (1884); _Feist Publications, Inc. v. Rural Telephone
    Service Co., Inc._, 499 U.S. 340, 113 L. Ed. 2d 358, 111 S. Ct. 1282
    (1991).

[^Aal22]: _Burrow-Giles_, 111 U.S. at 61 (quoting _Nottage v. Jackson_, 11
    Q.B.D. 627 (1883)).

[^Aal23]: _Id._ at 61.

The Second and Seventh Circuits have likewise concluded that contribution of
independently copyrightable material to a work intended to be an inseparable
whole will not suffice to establish authorship of a joint work.[^Aal24] Although
the Second and Seventh Circuits do not base their decisions on the word
"authors" in the statute, the practical results they reach are consistent with
ours. These circuits have held that a person claiming to be an author of a joint
work must prove that both parties intended each other to be joint
authors.[^Aal25] In determining whether the parties have the intent to be joint
authors, the Second Circuit looks at who has decision making authority, how the
parties bill themselves, and other evidence.[^Aal26]

[^Aal24]: _Thomson v. Larson_, 147 F.3d 195, (2nd Cir. 1998); _Erickson v.
    Trinity Theatre, Inc._, 13 F.3d 1061 (7th Cir. 1994); _Childress v.
    Taylor_, 945 F.2d 500 (2d Cir. 1991).

[^Aal25]: _Thomson_, 147 F.3d at 202-05.

[^Aal26]: _Id._

In _Thomson v. Larson_, an off-Broadway playwright had created a modern version
of La Boheme, and had been adamant throughout its creation on being the sole
author.[^Aal27] He hired a drama professor for "dramaturgical assistance and
research," agreeing to credit her as "dramaturg" but not author, but saying
nothing about "joint work" or copyright.[^Aal28] The playwright tragically died
immediately after the final dress rehearsal, just before his play became the
tremendous Broadway hit, _Rent_.[^Aal29] The dramaturg then sued his estate for
a declaratory judgment that she was an author of Rent as a "joint work," and for
an accounting.[^Aal30] The Second Circuit noted that the dramaturg had no
decision making authority, had neither sought nor was billed as a co-author, and
that the defendant entered into contracts as the sole author.[^Aal31] On this
reasoning, the Second Circuit held that there was no intent to be joint authors
by the putative parties and therefore it was not a joint work.[^Aal32]

[^Aal27]: _Id._ at 197.

[^Aal28]: _Id._

[^Aal29]: _Id._ at 198.

[^Aal30]: _Id._

[^Aal31]: _Id._ at 202-04.

[^Aal32]: _Id._ at 202-24.

Considering _Burrow-Giles_, the recent cases on joint works[^Aal33] (especially
the thoughtful opinion in _Thomson v. Larson_ [^Aal34]), and the Gilbert and
Sullivan example, several factors suggest themselves as among the criteria for
joint authorship, in the absence of contract. First, an author
"superintends"[^Aal35] the work by exercising control.[^Aal36] This will likely
be a person "who has actually formed the picture by putting the persons in
position, and arranging the place where the people are to be - the man who is
the effective cause of that,"[^Aal37] or "the inventive or master mind" who
"creates, or gives effect to the idea."[^Aal38] Second, putative coauthors make
objective manifestations of a shared intent to be coauthors, as by denoting the
authorship of The Pirates of Penzance as "Gilbert and Sullivan."[^Aal39] We say
objective manifestations because, were the mutual intent to be determined by
subjective intent, it could become an instrument of fraud, were one coauthor to
hide from the other an intention to take sole credit for the work. Third, the
audience appeal of the work turns on both contributions and "the share of each
in its success cannot be appraised."[^Aal40] Control in many cases will be the
most important factor.

[^Aal33]: _See Thomson v. Larson_, 147 F.3d 195, (2nd Cir. 1998); _Erickson v.
    Trinity Theatre, Inc._, 13 F.3d 1061 (7th Cir. 1994); _Childress v.
    Taylor_, 945 F.2d 500 (2nd Cir. 1991).

[^Aal34]: _Thomson v. Larson_, 147 F.3d 195 (2nd Cir. 1998).

[^Aal35]: _Burrow-Giles v. Sarony_, 111 U.S. at 61 (quoting _Nottage v.
    Jackson_, 11 Q. B. div. 627 (1883)).

[^Aal36]: _Thomson_, 147 F.3d at 202.

[^Aal37]: _Burrow-Giles v. Sarony_, 111 U.S. at 61 (quoting _Nottage v.
    Jackson_, 11 Q. B. Div. 627 (1883)).

[^Aal38]: _Id._

[^Aal39]: _Cf. Thomson v. Larson_, 147 F.3d 195, 202 (2nd Cir. 1998).

[^Aal40]: _Edward B. Marks Music Corp. v. Jerry Vogel Music Co., Inc._, 140 F.2d
    266, 267 (2nd Cir. 1944) (Hand, J.) modified by, 140 F.2d 268 (1944).

The best objective manifestation of a shared intent, of course, is a contract
saying that the parties intend to be or not to be co-authors. In the absence of
a contract, the inquiry must of necessity focus on the facts. The factors
articulated in this decision and the Second and Seventh Circuit decisions cannot
be reduced to a rigid formula, because the creative relationships to which they
apply vary too much. Different people do creative work together in different
ways, and even among the same people working together the relationship may
change over time as the work proceeds.

Aalmuhammed did not at any time have superintendence of the work.[^Aal41] Warner
Brothers and Spike Lee controlled it. Aalmuhammed was not the person "who has
actually formed the picture by putting the persons in position, and arranging
the place . . . ."[^Aal42] Spike Lee was, so far as we can tell from the record.
Aalmuhammed, like Larson's dramaturg, could make extremely helpful
recommendations, but Spike Lee was not bound to accept any of them, and the work
would not benefit in the slightest unless Spike Lee chose to accept them.
Aalmuhammed lacked control over the work, and absence of control is strong
evidence of the absence of co-authorship.

[^Aal41]: _See Burrow-Giles v. Sarony_, 111 U.S. 53, 61, 28 L. Ed. 349, 4 S. Ct.
    279 (1883).

[^Aal42]: _Id._

Also, neither Aalmuhammed, nor Spike Lee, nor Warner Brothers, made any
objective manifestations of an intent to be coauthors. Warner Brothers required
Spike Lee to sign a "work for hire" agreement, so that even Lee would not be a
co-author and co-owner with Warner Brothers. It would be illogical to conclude
that Warner Brothers, while not wanting to permit Lee to own the copyright,
intended to share ownership with individuals like Aalmuhammed who worked under
Lee's control, especially ones who at the time had made known no claim to the
role of co-author. No one, including Aalmuhammed, made any indication to anyone
prior to litigation that Aalmuhammed was intended to be a co-author and
co-owner.

Aalmuhammed offered no evidence that he was the "inventive or master mind" of
the movie. He was the author of another less widely known documentary about
Malcolm X, but was not the master of this one. What Aalmuhammed's evidence
showed, and all it showed, was that, subject to Spike Lee's authority to accept
them, he made very valuable contributions to the movie. That is not enough for
co-authorship of a joint work.

The Constitution establishes the social policy that our construction of the
statutory term "authors" carries out. The Founding Fathers gave Congress the
power to give authors copyrights in order "to promote the progress of Science
and useful arts."[^Aal43] Progress would be retarded rather than promoted, if an
author could not consult with others and adopt their useful suggestions without
sacrificing sole ownership of the work. Too open a definition of author would
compel authors to insulate themselves and maintain ignorance of the
contributions others might make. Spike Lee could not consult a scholarly Muslim
to make a movie about a religious conversion to Islam, and the arts would be the
poorer for that.

[^Aal43]: U.S. Const. Art. 1, § 8, cl. 8.

The broader construction that Aalmuhammed proposes would extend joint authorship
to many "overreaching contributors,"[^Aal44] like the dramaturg in Thomson, and
deny sole authors "exclusive authorship status simply because another person
rendered some form of assistance."[^Aal45] Claimjumping by research assistants,
editors, and former spouses, lovers and friends would endanger authors who
talked with people about what they were doing, if creative copyrightable
contribution were all that authorship required.

[^Aal44]: _Thomson_, 147 F.3d at 200 (internal quotations omitted).

[^Aal45]: _Id._ at 202 (citing _Childress v. Taylor_, 945 F.2d 500, 504 (1991)).

Aalmuhammed also argues that issuance of a copyright registration certificate to
him establishes a prima facie case for ownership. A prima facie case could not
in any event prevent summary judgment in the presence of all the evidence
rebutting his claim of ownership. "The presumptive validity of the certificate
may be rebutted and defeated on summary judgment."[^Aal46] The Copyright Office
stated in its response to Aalmuhammed's application for copyright (during the
pendency of this litigation) that his claims "conflict with previous
registration claims," and therefore the Copyright Office had "several questions"
for him. One of the questions dealt with the "intent" of "other authors," i.e.,
Warner Brothers. The evidence discussed above establishes without genuine issue
that the answers to these questions were that Warner Brothers did not intend to
share ownership with Aalmuhammed.

[^Aal46]: _S.O.S., Inc. v. Payday, Inc._, 886 F.2d 1081, 1086 (9th Cir. 1989).

Because the record before the district court established no genuine issue of
fact as to Aalmuhammed's co-authorship of Malcolm X as a joint work, the
district court correctly granted summary judgment dismissing his claims for
declaratory judgment and an accounting resting on co-authorship.

[***]

##### Discussion

1.  Could a contributor to an open source project seek compensation for their
    contributions under a theory of quantum meruit?

2.  Is a co-author of a work inherently a co-author of derivative works? _See
    Richlin v. MGM Pictures, Inc._, 531 F.3d 962 (heirs of co-author of 14-page
    treatment that was basis for Pink Panther movies not entitled to
    co-authorship of the actual movies).

3.  If two parties enter into an agreement to be co-authors of a work, and then
    the work is authored by one of the parties with no copyrightable
    contributions from the second party, is the second party a co-author? _See
    Richlin v. MGM Pictures, Inc._, 531 F.3d 962, 968, 2008 U.S. App. LEXIS
    12917, *15 (“A contract evidencing intent to be or not to be coauthors is
    dispositive.”)(citing _Aalmuhammed v. Lee_, 202 F.3d 1227, 1234 (9th Cir.
    2000)), but _see also Weissmann v. Freeman_, 868 F.2d 1313, 1327 (2d Cir.
    1989)(“one cannot be found to be a joint author of a work without actually
    having contributed to that work.”)(Judge Pierce’s concurrence, citing 1 M.
    Nimmer, _Nimmer on Copyright_ § 6.07 (1988)).

4.  Professor Melville Nimmer firmly disagrees with the Ninth Circuit’s joint authorship
    test formulated in _Aalmuhammed_:

> > “The Aalmuhammed court’s emphasis on 'control' as the most important factor
> > in the joint authorship analysis is inconsistent with the plain meaning,
> > legislative history, and transparent logic of the Copyright Act’s ownership
> > regime. The Section 101 definition of 'joint work' recognizes a wide range
> > of collaborative working arrangements by requiring only that “the authors
> > collaborated with each other, or if each of the authors prepared his or her
> > contribution with the knowledge and intention that it would be merged with
> > the contributions of other authors as ‘inseparable or interdependent parts
> > of a unitary whole.’ The master-mind concept narrows the range of joint
> > authors down to one or a few individuals for administrative convenience or
> > to avoid unjustified windfalls, not out of fidelity to legislative
> > intent.”[^Nimmer]

> Does the Ninth Circuit misconstrue the legislative intent behind joint works
> in _Aalmuhammed_? Are we likely to see refinement of the Ninth Circuit’s
> three-factor test?

[^Nimmer]: 1 _Nimmer on Copyright_ § 6.07 (2018)

### _Weissmann v. Freeman_, 868 F.2d 1313 (2d Cir. 1989)

Our next case concerns a dispute that arose when one of two joint authors of
scholarly works independently published a paper derived from the jointly-authored
works. It highlights an important issue for open source developers to consider,
namely: the creation of works that are derived from joint works, and the
relationship between joint authors and those derivative works.

#### Opinion

CARDAMONE, Circuit Judge: This appeal presents the paradigm of the problems that
arise when a long relationship between accomplished professor and brilliant
assistant comes to an end. Together the two had researched and co-authored
scholarly scientific works. When the appellant--the younger
assistant--individually wrote what she considered a new work, the appellee--the
mentor--believing himself a co-author of the new piece, used his assistant's
work, styling it as his own, and thereby precipitated the instant litigation.

Heidi S. Weissmann, M.D. appeals the dismissal after a bench trial in the
Southern District of New York (Pollack, J.), of her copyright infringement suit
against Leonard M. Freeman, M.D. Among the issues presented on appeal is the
novel question of whether a medical paper derived from the parties' prior
jointly authored works is itself a joint work, or whether it is a copyrightable
individual derivative work, the infringement of which gives rise to a cause of
action under the Copyright Act, 17 U.S.C. § 101, et seq. (1982 & Supp. III
1985).

FACTS

The parties are both accomplished scientists in the field of nuclear medicine.
Appellant Weissmann is an Associate Professor of Radiology and Nuclear Medicine
at the Albert Einstein College of Medicine (Einstein), and is an attending
physician specializing in nuclear medicine at the Montefiore Medical Center
(Montefiore). She has received numerous awards in the area of radionuclide
imaging, and published more than 80 scholarly articles. Appellee Freeman is also
a prolific author, and a noted lecturer in the fields of nuclear medicine and
diagnostic radiology. He has served as President of the Society of Nuclear
Medicine, and currently is a professor of Radiology and of Nuclear Medicine at
Einstein, where he has taught since 1964. He is the Director of the Nuclear
Medicine Service at Montefiore and Vice-Chairman of the Department of Nuclear
Medicine at Einstein.

The parties' professional association began in 1977 when Dr. Weissmann was in
her fourth year of residency at Montefiore and Dr. Freeman was Chief of the
Division of Nuclear Medicine at that hospital. In early 1977 appellee was
researching the application of the derivatives of a certain radiopharmaceutical,
iminodiacetic acid (IDA). IDA is a substance labeled with a radioactive isotope
that is injected into the bloodstream and, when picked up by the liver, permits
diagnosis of certain liver and biliary disorders. In the late 1970's drug
manufacturers producing IDA analogs needed scientists to develop a patient data
base to obtain approval of their Food and Drug Administration applications in
order to market the isotopes in the United States. One selected scientist was
Dr. Freeman, who began using the IDA analogs in his research efforts. As a
fourth-year resident, appellant worked on these initial studies under Dr.
Freeman's tutelage. The parties' first jointly authored article on IDA
derivatives was published in January 1979. Over the next several years a series
of articles on the use of IDA scanning in diagnosing biliary diseases were
published in the names of Freeman, Weissmann, and other scientists.

Beginning in 1980 the parties worked together as researchers and co-authors of a
number of papers focusing on various aspects of nuclear medicine, particularly
IDA imaging. Prior versions of the work alleged to have been infringed in the
instant litigation were first written in 1980 for a nuclear medicine review
course sponsored by the Harvard Medical School. The district court found that
the work in which appellant claims a copyright (Plaintiff's exhibit 1 or P-1) is
a "syllabus," that is, a paper reviewing the state of the art of hepatobiliary
imaging techniques, prepared to accompany lectures, and used by medical
residents to study for specialty boards. From 1980 to 1985 prior versions of P-1
were constantly revised and updated by the parties in an ongoing cooperative
effort.

In 1985 Dr. Weissmann authored the article that precipitated the present
copyright suit. It was entitled "Hepatobiliary Imaging" (P-1), and reported on a
relatively new diagnostic technique employing radioactive analogs of the agent
IDA. The work was prepared as a chapter for the Radiological Society of North
America's book entitled "Syllabus: A Categorical Course in Nuclear Medicine,"
printed and published in 1985. The publication listed Dr. Weissmann as the
article's sole author.

Appellant's creation admittedly was derived from previous papers jointly written
by the parties during the course of their professional relationship that
extended from 1977 to 1984. An examination of the relevant documents reveals
that portions of P-1 were taken virtually verbatim from prior jointly authored
pieces that had been presented at Einstein and at the Mount Sinai School of
Medicine (Mount Sinai) in 1983 and 1984 respectively. Although P-1 appears to
restate the central propositions asserted in the prior works, Weissmann's
exhibits includes the following new elements: (1) a new selection of photo
illustrations and associated captions; (2) references to four recent reports in
the pertinent literature; (3) new textual additions; and (4) reorganization of
previous material. Appellee conceded at trial that this material in P-1 was
created solely by appellant.

In the summer of 1987 Dr. Freeman was invited to give a review course on nuclear
medicine at Mount Sinai. He prepared P-1 to use in giving the course by deleting
Dr. Weissmann's name from P-1 and replacing it with his own, and by adding three
words to the title. Fifty copies of the article were made. Before the date set
for the course, appellant obtained one of the copies, and through counsel
requested that her revised article not be circulated, and that all those who had
received copies be informed that she claimed sole authorship of it. The article
was removed from the packet of course materials. Dr. Freeman delivered his
lecture without the use of his version of P-1.

After this incident, Weissmann filed the instant suit alleging copyright
infringement in violation of 17 U.S.C. § 501 (1982 & Supp. 1985). In her prayer
for relief she sought a declaration that Freeman had committed actionable
infringement, an injunction permanently restraining him from infringing, and an
award of actual damages and profits. Appellant consented to the dismissal of her
claim for attorney's fees because the copyright she obtained covering P-1 was
not registered before the suit was commenced, and such is a statutory
prerequisite to a claim for attorney's fees.

PROCEEDINGS BELOW

After a four-day bench trial, Judge Pollack in a written decision concluded that
Dr. Freeman's use of P-1 did not violate the copyright law. 684 F. Supp. 1248
(S.D.N.Y. 1988). In support of its determination that Freeman had not infringed
any legally cognizable rights that appellant may have had in P-1, the district
court found that appellee was a joint author, and therefore a co-owner of any
copyright Weissmann acquired in the article. 684 F. Supp. at 1260. The trial
court also determined that P-1's new matter was too trivial to qualify for
protection as a derivative work under the copyright statute. _Id._ at 1261.
Additionally, it ruled that even were Freeman not a joint author of the
allegedly infringed work, and even were P-1's new matter copyrightable,
Freeman's purported use of P-1 was a fair use within the purview of § 107 of the
Copyright Act. _Id._ at 1261-62.

In the course of the proceedings the district court denied appellant's two
substantive motions. The first was pursuant to Rule 15(b)for leave to amend the
pleadings to conform to the proof. Appellant sought to have the court evaluate
and consider claims arising from appellee's allegedly publishing another
verbatim copy of P-1 under his name for a December 1986 symposium in the
Republic of China (the Taiwan Publication), and the supposed proof that
Freeman's conduct constituted misrepresentation of origin under § 43(a) of the
Lanham Act and under the common law. The second motion made under Rule 60(b)
sought reconsideration by the trial court of its finding that the Taiwan
Publication had not been proven to be connected with Dr. Freeman. Appellee's
request for attorney's fees and for sanctions was denied. Appellant appeals from
the dismissal of her copyright infringement suit, and appellee cross-appeals
from the denial of attorney's fees and sanctions against appellant.

DISCUSSION

On appeal appellant argues that the district court erred in (1) determining that
appellee was a joint author of P-1 within the meaning of §§ 101 and 201 of the
Copyright Act, (2) concluding that P-1 did not contain sufficient new matter to
qualify for copyright protection as a derivative work under §§ 101 and 103(b),
and (3) deciding that, even if appellee was not a joint author and the article
therefore did qualify for protection as a derivative work, appellee's use of P-1
constituted a fair use under § 107, and (4) denying appellant's 15(b) and 60(b)
motions.

I Joint Authorship

Before discussing whether P-1 was a joint work, we set forth the standard of
review to be applied to the district court's determination that P-1 was such a
work. Ordinarily the clearly erroneous standard under Fed. R. Civ. P. 52(a)
would govern. But, when a district court makes findings of fact predicated upon
an incorrect legal standard such findings are not binding on an appellate court.
_See United States v. Parke, Davis & Co._, 362 U.S. 29, 44, 4 L. Ed. 2d 505, 80
S. Ct. 503, (1960) (Rule 52 inapplicable where district court's findings
premised on erroneous view of legal standard).

Here the district court determined that the entire series of the parties' works
on the subject of radionuclide imaging--including the work alleged to have been
infringed--constituted a single evolutionary joint work. It discussed the
conceded joint authorship in the preexisting works. Without making any specific
findings respecting P-1 itself, the court found that Dr. Freeman was a co-owner
of P-1 and that P-1 was a joint work. The trial court made this surprising
finding despite Dr. Freeman's concession that he had no hand in P-1's
preparation. The finding was made based on the district court's mistaken view
that joint authorship of the prior existing works automatically makes the two
joint authors co-owners of the derivative work. Such a ruling stands copyright
law on its head. It flies in the face of the Copyright Act which affords
protection to each work at the moment of its creation. Thus, § 101 provides for
those works prepared over time that "the portion of it that has been fixed at
any particular time constitutes the work as of that time, and where the work has
been prepared in different versions, each version constitutes a separate work."
Of greater significance is that the trial court's view would convert all
derivative works based upon jointly authored works into joint works, regardless
of whether there had been any joint labor on the subsequent version. If such
were the law, it would eviscerate the independent copyright protection that
attaches to a derivative work that is wholly independent of the protection
afforded the preexisting work. _See_ § 103(b). Hence, it was a plain error for
the district court to rule, as a matter of law, that Dr. Freeman's joint
authorship of the prior works made him a joint author with appellant in the
derivative work. The district court also made a finding of fact that Dr. Freeman
was a joint author with Dr. Weissmann of P-1. Section 201(a) of the Act
provides: "Copyright in a work protected under [the Copyright Act] vests
initially in the author or co-authors of the work." Section 101 defines a "joint
work" as one "prepared by two or more authors with the intention that their
contributions be merged into inseparable or interdependent parts of a unitary
whole." In a joint work each author "automatically acquires an undivided
ownership in the entire work" including any portion of it. 1 M. Nimmer, _Nimmer
on Copyright_ § 6.03, at 6-6 (1988). Thus, an action for infringement between
joint owners will not lie because an individual cannot infringe his own
copyright. The only duty joint owners have with respect to their joint work is
to account for profits from its use. _See Donna v. Dodd, Mead & Co._, 374 F.
Supp. 429, 430 (S.D.N.Y. 1974). A review of the meaning of §§ 101 and 103(b) and
of their legislative history reveals two basic criteria that must be satisfied
before one is a joint author of a derivative work. First, each putative author
must have "contributed" to the work. Second, each must intend to contribute to a
joint work at the time his or her alleged contribution is made. Because § 103(b)
extends independent protection to derivative works, an intent to contribute or
an actual contribution to previous works does not serve as proof of ownership in
the derivative work. _See_ H.R. Rep. No. 1476, 94th Cong., 2d Sess. 103, 120,
_reprinted_ in 1976 U.S. Code Cong. & Admin. News 5659, 5736 (_House Report_).
We consider these two criteria.

A. Contribution to Derivative Work The statute envisions that each author
contribute to a joint work. "Under the [§ 101] definition a work would not be
'joint' unless its authors collaborated among themselves or unless each of the
authors knew, at the time the work was being written, that his contribution
would be integrated as an 'inseparable' or 'interdependent' part of a 'unitary
whole.'" _Supplementary Report of the Register of Copyrights on the General
Revision of the U.S. Copyright Law_: 1965 Revision Bill, 89th Cong., 1st Sess.,
Copyright Law Revision Part 6, at 65 (House Comm. Print 1965), _reprinted in_ 1
Copyright Law Revision (1964-1965).

In enacting the definition of a joint work set forth in § 101, Congress
endeavored to "make[] plain that copyright in a derivative work is independent
of, and does not enlarge the scope of rights in, any pre-existing material
incorporated in it. There [was] thus no need to spell this conclusion out in the
definition of 'joint work.'" House Report at 120. The legislative history
clearly indicates that one cannot be deemed to be a joint author without
actually collaborating in the work's preparation. Critical therefore "is the
intention, at the time the writing is done, that the parts be absorbed or
combined into an integrated unit." _Id._ That intention must be with respect to
the work in which a copyright is claimed, not with respect to the prior works
from which it is derived. _See MCA, Inc. v. Wilson_, 425 F. Supp. 443, 455
(S.D.N.Y. 1976) (owner of underlying work obtains no property rights in
derivative work), _aff'd_, 677 F.2d 180 (2d Cir. 1981).

In the case at hand, because Dr. Freeman conceded that he had not participated
in drafting the new matter included in P-1, it follows as a logical corollary,
therefore, that he acquired no interest in or right to use P-1 beyond those
rights which he had as co-author in the prior joint material incorporated into
P-1. Even though one co-author has the right to revise a joint work in order to
create an individual derivative work, the other co-author acquires no property
rights in the newly created work prepared without his involvement. _See Dynamic
Solutions, Inc. v. Planning and Control, Inc._, 646 F. Supp. 1329, 1338-39
(S.D.N.Y. 1986) (even sole author/owner of preexisting material contained in
derivative work has no property right in new matter created for the derivative
work added without his participation); _see also_ _Weinstein v. University of
Illinois_, 811 F.2d 1091, 1095 (7th Cir. 1987); _House Report_ at 120; 1 Nimmer
§ 6.06[B], at 6-15.

B. Intent to Contribute to Derivative Work

The second point upon which inquiry is focused is Dr. Weissmann's intent. The
district court made no express finding on this critical issue. It simply stated
in conclusory fashion that because the parties had intended P-1's predecessors
to be used jointly as a "stock piece" to accompany their review lectures, they
had somehow impliedly agreed that all future works on the subject of radioactive
analogs of IDA, including P-1, would also be a joint work.

In order for a work to be deemed a joint work, the parties must evince "the
intention that their contributions be merged," § 101 (emphasis added), "at the
time the writing is done," House Report at 120, not at some later date. _See_ 1
_Nimmer_ § 6.03, at 6-7. The law on this point is set forth in _Edward B. Marks
Music Corp. v. Jerry Vogel Music Co._, 140 F.2d 266 (2d Cir. 1944) (L. Hand,
J.). There it was observed that a finding of joint authorship requires that each
author intend his or her contribution, at the time that it is created, to become
part of a unitary work to which another will make or already has made a
contribution. Or, as Judge Hand stated it, "when both plan an undivided whole .
. ., their separate interests will be as inextricably involved, as are the
threads out of which they have woven the seamless fabric of the work." _Id._ at
267; _see also Shapiro, Bernstein & Co. v. Jerry Vogel Music Co._, (_"Melancholy
Baby"_), 161 F.2d 406, 409 (2d Cir. 1946), _cert. denied_, 331 U.S. 820, 91 L.
Ed. 1837, 67 S. Ct. 1310 (1947).

_Marks_ was a case in which one individual had written the lyrics for a song and
another had written the music. Neither party knew the other, but both were aware
that their individual efforts would not stand alone. In holding that the
resulting song was a joint work, the critical fact was that both parties were
equally aware that their individual authorship efforts would have to be combined
in order to create the final integrated product--a commercially viable song.
_See Marks_, 140 F.2d at 267. From this, the rule has evolved that an author who
intends to create a joint work must clearly demonstrate his or her intent in
that regard. Although such an intent may, as in _Marks_, be inferred from the
circumstances surrounding the creation of the work, in the absence of such a
showing, the work is presumed to be the product of an individual author and is
the sole property of its creator. _See, e.g., Gilliam v. American Broadcasting
Cos., Inc._, 538 F.2d 14, 22 (2d Cir. 1976) (Lumbard, J.) (reservation of rights
by one party inconsistent with joint authorship and work not therefore joint);
_Picture Music, Inc. v. Bourne, Inc._, 314 F. Supp. 640, 645 (S.D.N.Y. 1970)
(declining to find joint authorship where a "common design to create a single
work" not shown to exist), _aff'd on other grounds_, 457 F.2d 1213 (2d Cir.),
_cert. denied_, 409 U.S. 997, 34 L. Ed. 2d 262, 93 S. Ct. 320 (1972); _cf.
Community for Creative Non-Violence v. Reid_, 270 U.S. App. D.C. 26, 846 F.2d
1485, 1497 (D.C. Cir. 1988), _cert. granted_, 488 U.S. 940, 109 S. Ct. 362, 102
L. Ed. 2d 352 (1988).

In the present case, Drs. Weissmann and Freeman collaborated in the preparation
and publication of the works from which P-1 was derived. Yet, there is no
evidence that they intended their joint product to be forever indivisible like
the finite whole of the completed single song in _Marks_. The facts point to a
contrary conclusion. Scientific research is a quest for new discoveries and the
preexisting joint works by definition were continually evolving. Dr. Weissmann
believed she had a new and better approach and decided to author her research
alone. Section 103(b) of the Copyright Act gives her that right when it extends
independent protection to derivative works. The joint authorship of the
underlying work does not confer any property right in the new work, save those
rights which the co-author (here Dr. Freeman) of the previous works retains in
the material used as part of the compilation of the derivative work. The
district court opinion reveals a fundamental misunderstanding of these
principles. This misconception is reflected in its discussion of Dr. Weissmann's
intent to merge her efforts with Dr. Freeman based only on P-1's predecessors,
and not on P-1 itself.

C. Appellant's Intent to Create a Derivative Work

The remainder of discussion of joint authorship concerns the substantial and
uncontroverted evidence that Dr. Weissmann intended P-1 to be her own individual
work. As a preliminary matter, it is important to note that of the 88 articles,
abstracts, and book chapters listed on her curriculum vitae, 71 credit Dr.
Freeman as a co-author. Appellant's having deviated from that pattern in
submitting P-1 for publication as a chapter in the Radiological Society of North
America's book under the name "Heidi S. Weissmann" is persuasive proof of the
fact that she intended this particular piece to represent her own individual
authorship. Appellant's use of her own by-line on P-1 constitutes prima facie
proof that this work was not intended to be joint. Appellee failed to produce
any evidence to rebut appellant's showing. In fact, Dr. Freeman lectured at the
same meeting at which P-1 was first presented, and made no objection to the
omission of his name from it.

Again, had the trial court separately considered P-1, it would have concluded
that appellant's article was the only work with respect to which it was
repeatedly conceded that appellee had played no role. Yet, the trial judge found
that "plaintiff did almost all of the writing" for the works listed on her
resume of which Freeman was a "co-author" and that she routinely "submitted
drafts to Dr. Freeman before publication." 684 F. Supp. at 1254. It also found
that "she would always make sure to leave a copy of a manuscript on his desk if
he was not in town or busy with other commitments; she did not always get
comments back, but often she did." _Id._ Hence, it is significant on the issue
of appellant's intent that P-1 was one of those few works that was not submitted
for Dr. Freeman's review and on which she did not receive his comments. These
facts--found by the district court--strongly evidence appellant's intent that
P-1 be solely her own work.

The district court found that Freeman's participation in the preparation of P-1
was "strikingly illustrated" by Weissmann's inclusion in P-1 of a section
entitled "False-Positive Studies for Acute Cholecystitis" which Dr. Freeman had
independently composed for a 1984 Harvard review course. The incorporation of
this material into P-1 is irrelevant to the question of whether or not the
parties intended P-1 to be a joint work. Appellant correctly points out that the
inclusion of the "False Positive" section is not proof of any intention on Dr.
Freeman's part to make a contribution to P-1 because, prior to 1985, he could
not have formed an intent to contribute his efforts to her then nonexistent
work.

In sum, the evidence presented at trial fully supports appellant's contention
that the work alleged to have been infringed was solely the product of her
authorship efforts. Although her work derived from preexisting jointly authored
material, appellee played no role in P-1's creation. As a non-contributing party
to P-1, Dr. Freeman's intent regarding his contributions to the underlying
preexisting work is not relevant to claimed joint authorship of P-1. The
district court's conclusion that P-1 was a joint work because the entire series
of the parties' articles on IDA, including P-1, was one evolutionary joint work
disregards the copyright protection accorded derivative works, independent of
the preexisting works under § 103(b). As a consequence of its plain error of law
in this regard, the district court's finding of fact that Freeman's
co-authorship of the preexisting works also made him a joint author of P-1 is
clearly erroneous.

II Derivative Work

We now turn attention to whether P-1 qualifies for protection as a derivative
work as that term is defined by the Copyright Act. To establish a claim of
copyright infringement, plaintiff must prove ownership of a valid copyright and
copying by the defendant. With Dr. Freeman's copying admitted, the only question
is whether Dr. Weissmann owned a valid copyright in a so-called derivative work.
Although her certificate of registration "constitute[s] prima facie evidence of
the validity of the copyright and of the facts stated in the certificate," 17
U.S.C. § 410(c), it is not conclusive on the issue of copyrightability; it
merely creates a presumption of validity. _See, e.g., Durham Indus., Inc. v.
Tomy Corp._, 630 F.2d 905, 908 (2d Cir. 1980); _Past Pluto Productions Corp. v.
Dana_, 627 F. Supp. 1435, 1440 (S.D.N.Y. 1986) (certificate shifts burden to
defendant to disprove copyright's validity). Section 101 of the Copyright Act
defines a "derivative work" as one that is based on "preexisting works." In
addition, § 103(b) provides as follows

> The copyright in a compilation or derivative work extends only to the material
> contributed by the author of such work, as distinguished from the preexisting
> material employed in the work, and does not imply any exclusive right in the
> preexisting material. The copyright in such a work is independent of, and does
> not affect or enlarge the scope, duration, ownership, or subsistence of, any
> copyright protection in the preexisting material.

Section 101 of the statute further defines a derivative work as "[a] work
consisting of editorial revisions, annotations, elaborations, or other
modifications which, as a whole, represent an original work of authorship. . .
." Thus, it is clear that "the manner of expression, the author's analysis or
interpretation of events, the way he structures his material and marshals facts,
his choice of words, and the emphasis he gives to particular developments" are
protected under the copyright laws. _Wainwright Securities, Inc. v. Wall Street
Transcript Corp._, 558 F.2d 91, 95-96 (2d Cir. 1977), _cert. denied_, 434 U.S.
1014, 54 L. Ed. 2d 759, 98 S. Ct. 730 (1978).

The principle of derivative work protection is subject to two important
limitations, both of which were purportedly recognized by the district court. To
support a copyright, a derivative work must be more than trivial, and the
protection afforded a derivative work must reflect the degree to which the
derivative work relies on preexisting material, without diminishing the scope of
the latter's copyright protection. _Durham Indus._, 630 F.2d at 909. This rule
is premised on the notion that "'the one pervading element prerequisite to
copyright protection regardless of the form of work' is the requirement of
originality--that the work be the original product of the claimant." _L. Batlin
& Son v. Snyder_, 536 F.2d 486, 489-90 (2d Cir.) (_en banc_) (quoting 1 Nimmer §
10, at 32 (1975)), cert. denied, 429 U.S. 857, 50 L. Ed. 2d 135, 97 S. Ct. 156
(1976). Originality is and always has been rightly prized. Dostoevsky, for
example, insisted that the measure of a person's worth in pre-Revolutionary
Russia did not depend so much on money or position, as it did on one's
originality. F. Dostoevsky, _The Idiot_, Part I (Garrett Trans. 1958). Mill
wrote that "nothing was ever yet done which someone was not the first to do, and
. . . all good things which exist are the fruits of originality. . . ." J.S.
Mill, _On Liberty_ 271 (Harv. Classics, Eliot ed. 1909).

In the law of copyright only an unmistakable dash of originality need be
demonstrated, high standards of uniqueness in creativity are dispensed with. In
deciding whether the originality of the matter added in P-1 is sufficient to
qualify for protection as a derivative work, the standard enunciated in _Alfred
Bell & Co. v. Catalda Fine Arts, Inc._, 191 F.2d 99 (2d Cir. 1951) (Frank, J.),
remains the law in this Circuit: "All that is needed to satisfy both the
Constitution and the statute is that the 'author' contributed something more
than a 'merely trivial' variation, something recognizably 'his own'" _Id._ at
102-03. The originality requirement for a revised version is a "minimal" or
"modest" one. _See, e.g., Eden Toys, Inc. v. Florelee Undergarment Co._, 697
F.2d 27, 35 (2nd Cir. 1982); _Durham Indus._, 630 F.2d at 910; _Puddu v.
Buonamici Statuary, Inc._, 450 F.2d 401, 402 (2d Cir. 1971); _Millworth
Converting Corp. v. Slifka_, 276 F.2d 443, 445 (2d Cir. 1960).

The district court here concluded that P-1 and its predecessors had evolved over
an extended period of time and that Weissmann's additions were minuscule,
demonstrating little originality. 684 F. Supp. at 1261. Although recognizing
that the selection and arrangement of data may merit copyright protection, _see
Eckes v. Card Prices Update_, 736 F.2d 859, 863 (2d Cir. 1984), the trial judge
believed that "the update was done as part of the evolution of the stock piece"
and that appellant's modifications of the preexisting joint works did not
warrant copyright protection. 684 F. Supp. at 1261.

It was formerly our rule that where, as here, the originality of a work could be
determined entirely by reference to documentary evidence, we were in as good a
position as the district court to evaluate originality. _See Eden Toys_, 697
F.2d at 34 n. 6 and 35 (2d Cir. 1982); _Taylor v. Lombard_, 606 F.2d 371, 372
(2d Cir. 1979); _Jack Kahn Music Co. v. Baldwin Piano and Organ Co._, 604 F.2d
755, 758 (2d Cir. 1979). _But see Apex Oil v. Vanguard Oil & Service Co._, 760
F.2d 417, 424 (2d Cir. 1985) (Oakes, J. concurring) (suggesting that "appellate
courts must not exercise de novo review over findings . . . based . . . on
documents or objective evidence"). In 1985 Rule 52(a) of Fed. R. Civ. P. was
amended so that findings of fact based upon documentary--along with
oral--evidence are not to be set aside unless clearly erroneous.

In our view the district court implausibly overlooked the fact that appellant's
1985 selection of subject matter and content drawn from prior works and their
rearrangement in P-1 is sufficiently the product of original authorship to
warrant copyright protection. It failed to give detailed consideration to the
new matter that Weissmann added to the parties' prior works in her authorship of
P-1. Its main discussion of P-1's content is a passing reference to the addition
of "only" four new sources from the relevant scientific literature. Although the
credibility of the parties as witnesses was fully discussed, the relevance of
such an inquiry is problematic when the evidence upon which the derivative work
determination must be based is solely documentary. Credibility might have been
relevant, for example, had the question of who actually authored the new
material been contested. But it is scarcely pertinent to determining whether the
newly-added matter satisfies the statutory requirements for protectability.
Research has not revealed a single case in which credibility has been deemed
significant--let alone dispositive--on the question of whether there is a
sufficient level of originality in a given work to render it copyrightable.
While the district court's findings based on the credibility of witnesses is
entitled to deference, the trial judge cannot insulate his findings on
originality from appellate review by calling them credibility determinations.
_Anderson v. City of Bessemer_, 470 U.S. 564, 575, 84 L. Ed. 2d 518, 105 S. Ct.
1504, (1985).

Our examination of the relevant documents reveals that Weissmann's additions and
modifications in P-1 extend well beyond the mere addition of "four sources." A
thorough review of P-1 and of the works from which it is derived demonstrates
that Dr. Weissmann added the following new elements to the existing prior joint
work: (1) a selection and arrangement of photo illustrations and associated
captions; (2) references to recent reports in the pertinent literature; (3)
selection, condensation, and description of additional source material; (4)
several new textual additions; (5) substantial rearrangement of the manner and
order of presentation of material contained in the parties' prior joint works;
and (6) the addition of a section on "congenital disorders," a revised treatment
of "chronic cholecystitis," and the incorporation of Dr. Freeman's "false
positive" studies.

The district court found that many of the foregoing additions and revisions
repeated verbatim portions of prior works and, from that finding, concluded that
P-1 was neither new nor copyrightable. This finding wholly ignores the statutory
scheme that expressly protects the selection of subject matter and content from
underlying works, as well as the rearrangement of preexisting material taken
from those works. _See_ 17 U.S.C. § 101 (defining derivative work as an
"abridgment, condensation or any other form in which a work may be recast,
transformed, or adapted"). Further, a comparison of the parties' prior
works--including P-1's most recent predecessor--at once demonstrates numerous
differences, and highlights the fact that P-1 gave IDA imaging new and original
treatment. Moreover, Dr. Freeman's copying and distributing P-1 as his own work
is further evidence of the non-triviality of Dr. Weissmann's work, since copying
without regard to a plaintiff's rights is probative on the issue of the
originality of a work. _See Bleistein v. Donaldson Lithographing Co._, 188 U.S.
239, 252, 47 L. Ed. 460, 23 S. Ct. 298, (1903) (Holmes, J.) (that works have
worth is sufficiently shown by desire to copy them "without regard to the
plaintiff's rights").

We conclude therefore that the district court's holding that Weissmann could not
acquire a copyright in a derivative work based upon a jointly authored work was
an error of law that disregarded the provisions of § 103(b) and the protection
it extends to derivative works. Moreover, Dr. Freeman failed to rebut the _prima
facie_ showing of copyrightability appellant obtained by her certificate of
copyright registration. As a consequence, we hold that Dr. Weissmann's additions
and modifications to the preexisting joint work satisfy the modest requirements
set forth in § 103(b) and in the relevant case law sufficiently to make P-1
entitled to copyright protection as a derivative work. The district court's
findings--upon which it reached a contrary legal conclusion--were clearly
erroneous because they have left us, after a thorough review of all the
evidence, with a firm conviction that the district court was mistaken. _See
United States v. United States Gypsum Co._, 333 U.S. 364, 395, 92 L. Ed. 746, 68
S. Ct. 525, (1948).

CONCLUSION

For the reasons stated, we hold that P-1 was an individually-authored,
copyrightable, derivative work created by appellant and that Dr. Freeman's use
cannot be said to be a fair use of it. Accordingly, we reverse the judgment of
the district court and remand the case to it with directions that judgment be
entered in favor of appellant Weissmann. The judgment otherwise appealed from is
affirmed.

REVERSED IN PART AND AFFIRMED IN PART.

Concur by: PIERCE (In Part)

Concur PIERCE, Circuit Judge, concurring: I join in Parts II-V of the court's
opinion. I join only in the result in Part I.

As to Part I, I agree that we must reverse and remand because Dr. Freeman failed
to rebut appellant's claim (evidenced by her registration of P-1 as a derivative
work) that she did not intend the new material to be "merged" with the prior
joint work. _See generally_ 1 M. Nimmer, _Nimmer on Copyright_ § 6.03 (1988).
Appellant's certificate of registration served as "prima facie evidence of the
validity of the copyright and of the facts stated in the certificate." 17 U.S.C.
§ 410(c) (1982). For Dr. Freeman to claim that his use was not an infringement,
but rather that the work was "joint,” was a defense much like any other under
the Copyright Act. _See_ 3 M. Nimmer, _supra_, § 13.04. Therefore, it was
incumbent upon Dr. Freeman to rebut appellant's prima facie evidence that the
work (P-1) was derivative, not joint. Appellee failed to meet his burden,
however, for he failed to present sufficient evidence to demonstrate appellant's
intent to create a joint work.

The district court appears to have applied the opposite presumption. Rather than
focusing on the appellant's intent at the time of creating the derivative work,
the court dwelt primarily on the parties' long-standing and close professional
relationship. From that, it seems to have presumed that P-1--a by-product of
that professional collaboration--was a "joint" work. That presumption, however,
in effect placed the burden on the putative author to show that the work was
derivative, rather than on the putative infringer to show that the work was
joint. The district court's approach was therefore at odds with the statutory
scheme of burdens of proof, and must be reversed as a matter of law.

I differ, though, with Judge Cardamone's reasoning in Part I. The fact that Dr.
Freeman was not the author of any of the new material that went into P-1 did
not, of itself, preclude that work from being "joint." Of course, as Judge
Cardamone notes, one cannot be found to be a joint author of a work without
actually having contributed to that work. _See_ 1 M. Nimmer, _supra_, § 6.07.
However, that does not mean that an author, to be a "joint" author, must have
contributed to each incremental addition to the work. Thus, in this case, had
Dr. Weissmann's intent been otherwise--had she intended the work to be
joint--Dr. Freeman could have been deemed a joint author simply by virtue of his
contributions to the earlier work, into which Dr. Weissmann's material would
have been "merged." _See, e.g., Edward B. Marks Music Corp. v. Jerry Vogel Music
Co._, 140 F.2d 266, 267 (2d Cir. 1944); 1 M. Nimmer, _supra_, § 6.03, at 6-7.

Further, I do not agree that the earlier incorporation of Dr. Freeman's "False
Positives" study into the evolving syllabus was irrelevant. Though not
dispositive, the parties' past willingness to have their works absorbed into the
syllabus was relevant to the question of appellant's intent when she reshaped
the syllabus into P-1.

On balance, however, I agree with the court that the evidence relied upon by
appellee was not sufficient to show that appellant intended to create a joint
work. Therefore, I join the conclusion of the court, and would reverse and
remand, with judgment to be entered for appellant.

##### Discussion

1.  Open source projects are commonly thought of as a chain of derivative works,
    whereby every commit is either a copy or derivative work of the previous
    iteration of the project.[^Chestek2] If a software developer is a joint
    author of Version 1.2 of an open source project, does that developer remain
    a joint author of Version 1.3 if that developer neither contributed any of
    the changes distinguishing versions 1.2 and 1.3 and was not the project
    maintainer who accepted the changes?

2.  How dispositive is the intent of the authors in determining whether or not a
    work is jointly authored? What is the minimal amount of evidence required to
    establish the authors' intent with respect to whether the works should be
    considered jointly authored? What steps can be taken to ensure that a work
    is jointly authored? To ensure that a work is not jointly authored?

3.  What are the risks that joint authorship presents to copyright holders? What
    are the benefits that it confers? Do open source project maintainers benefit
    from a joint authorship model? Do contributors benefit under a joint
    authorship model?

[^Chestek2]: _See_ Pamela S. Chestek, _A Theory of Joint Authorship For Free and
    Open Source Software Projects_, (2017).

### _Gaylord v. United States_, 595 F.3d 1364 (Fed. Cir. 2010)

Our final case on the topic of joint authors concerns the authorship of a
sculptural work called “The Column” crafted by the sculptor Frank Gaylord. When
the work was used as the basis for a United States stamp, Gaylord protested that
he had not permitted this derivative work. The government argued that it was a
joint author of the original sculptural work and therefore did not require
Gaylord’s permission in order to publish the derivative stamp.

This case has many similarities to _Weissmann_, but presents an example of the
Federal Circuit deciding a question of joint authorship, and illustrates the
consequences when joint authorship in the original work is not found.

#### Opinion

MOORE, Circuit Judge.

Mr. Frank Gaylord appeals the decision of the United States Court of Federal
Claims that a stamp issued by the United States Postal Service made fair use of
a copyrighted work, specifically, soldier sculptures in formation constituting
part of the Korean War Veterans Memorial (Memorial). The court determined that
Mr. Gaylord was the sole author of the soldier sculptures and that his
sculptures were not exempt from copyright protection under the Architectural
Works Copyright Protection Act (AWCPA). Because the court erred when it
determined that the stamp made fair use of Mr. Gaylord's work, but it correctly
determined that the government was not a joint author and that the AWCPA did not
bar an infringement suit, we affirm-in-part, reverse-in-part, and remand for a
determination of damages.

BACKGROUND

This case arises from the Postal Service's decision to issue a 37-cent stamp
depicting a portion of the Memorial. The path from the concept of the Memorial
to the creation of the stamp spans more than 15 years.

In 1986, Congress enacted legislation to erect a memorial in Washington, D.C. to
honor veterans of the Korean War. Authorization of Memorial, Pub. L. No. 99-572,
§ 1, 100 Stat. 3226 (1986). The legislation authorized the American Battle
Monuments Commission (Commission) to establish the Memorial, and the Commission
sponsored a contest to select the designer of the Memorial. A team from the
Pennsylvania State University (the Penn State Team) won the contest with a
proposal to create 38 larger-than-life granite soldiers in formation. According
to the Penn State Team, "[f]rom a distance, one [would see] the Memorial as an
elusive, dream-like presence of ghostly figures moving across a remote
landscape." Although its original concept undoubtedly influenced the design of
the Memorial, the Penn State Team eventually withdrew from the project.[^Gaylord1]

[^Gaylord1]: The members of the Penn State Team are not parties to this litigation,
    and no one has suggested that they have copyrights in the Memorial.

The Army Corps of Engineers selected Cooper-Lecky Architects, P.C.
(Cooper-Lecky) as the prime contractor for the creation, construction, and
installation of the Memorial. Cooper-Lecky sponsored a competition to select the
sculptor for the Memorial. Mr. Gaylord, a nationally recognized sculptor, won
the contest.

In 1990, Mr. Gaylord began work on the project. Although the Penn State Team's
proposal called for 38 granite soldiers, "the final design featured 19 stainless
steel statues representing a platoon of foot soldiers in formation," referred to
as The Column. Gaylord, 85 Fed. Cl. at 63. Mr. Gaylord prepared successively
larger models of the soldiers, transforming them along the way in response to
critiques and suggestions by Cooper-Lecky, members of the Korean War Veterans
Memorial Advisory Board (VAB), and the Commission on Fine Arts (CFA). Once Mr.
Gaylord completed models for the soldiers, they were cast in stainless steel and
installed at the site of the Memorial on the National Mall in Washington, D.C.
At the suggestion of a member of the VAB, Mr. Gaylord staggered the statues,
thereby creating the composition of The Column. Cooper-Lecky, the VAB, and the
CFA all participated in incorporating The Column into the Memorial, which also
includes landscaping, a mural, and granite plates representing the reflection of
rice paddies at the soldiers' feet. A picture of The Column--taken on a sunny
day--is below.

Mr. Gaylord received five copyright registrations relating to the soldier
sculptures from 1990 to 1995. Each certificate listed Mr. Gaylord as the sole
author. The registrations include pictures of the clay models for the sculptures
as they evolved over the years, and eventually, the sculptures themselves. For
example, in his November 11, 1993 registration, he described the work as clay
"statuettes -- fully approved -- 19 soldiers -- National Korean War Veterans
Memorial." His August 12, 1994 registration concerned "19 7'-6" tall clay
soldiers to be cast in stainless steel for the National Korean War Veterans
Memorial on the mall in Washington, D.C." Shortly after the statues were
installed, on May 1, 1995, Mr. Gaylord filed a certificate of copyright
registration for the soldiers as they appeared before and after casting. This
certificate included photographs of the soldiers as installed on the National
Mall.

In 1995, shortly after the Memorial was dedicated, a photographer named John
Alli took a photograph of the Memorial as a retirement gift for his father, a
veteran of the Korean War. Mr. Alli visited the Memorial on five or six
occasions, taking photographs at various times of year and day. One such visit
occurred in January 1996 just after a snowstorm. Over the course of about two
hours on that cold winter morning, Mr. Alli took about 100 photographs of the
Memorial, including photographs of individual soldiers, from various angles
using different exposures and lighting conditions. Mr. Alli selected one of his
photographs for his father's retirement gift. The photograph, titled "Real
Life," is reproduced below. No one questions that Mr. Alli is entitled to his
own copyright protection in his photograph as a derivative work.

Mr. Alli decided to sell prints of the photograph. He therefore sought
permission from the copyright owner of the underlying work, eventually locating
Mr. Lecky of Cooper-Lecky, who held himself out as the "outright" owner of the
copyright. Mr. Alli agreed to pay a 10% royalty on sales of prints of his
photographs to a licensing entity established by Mr. Lecky. Mr. Lecky did not
notify Mr. Gaylord about the agreement with Mr. Alli.[^Gaylord2]

[^Gaylord2]: In 2006, Mr. Gaylord sued Mr. Alli for copyright infringement. Mr. Alli
    settled the dispute and agreed to pay Mr. Gaylord 10% of his net sales.

In 2002, the Postal Service decided to issue a 37-cent stamp commemorating the
50th anniversary of the armistice of the Korean War. The Postal Service selected
Mr. Alli's photograph for the stamp and paid him $ 1500 for its use. Mr. Alli
told the Postal Service that it would need the permission of the owner of the
copyright of the underlying work and referred the Postal Service to Mr. Lecky.

The Postal Service issued the stamp, titled "Korean War Veterans Memorial." The
stamp features Mr. Alli's photo and depicts 14 of the 19 soldier sculptures
(photos redacted).

The Postal Service produced approximately 86.8 million stamps before retiring
the stamp on March 31, 2005. The Postal Service acknowledged that it received
over $ 17 million from the sale of nearly 48 million stamps. It was estimated
that in 2003, the Postal Service generated $ 5.4 million from the sales of
stamps to collectors who did not use the stamps to send mail. In addition, the
Postal Service sold retail goods such as commemorative panels and framed art
featuring images of the stamp. It did not seek or obtain Mr. Gaylord's
permission to use the sculptures in the stamp or in any related retail goods.

Mr. Gaylord sued the government in the Court of Federal Claims on July 25, 2006,
alleging infringement of his copyright. On June 16-20, 2008, the Court of
Federal Claims conducted a trial, at which the government argued that the stamp
made fair use of the work, excepting it from copyright liability. The government
further argued that it had rights to the work as a joint author, which would
provide it an unlimited license in the work. Finally, the government argued that
the stamp fell under the exclusion from liability for copyright infringement for
architectural works under the AWCPA. The Court of Federal Claims determined that
Mr. Gaylord was the sole copyright owner of The Column and that The Column did
not qualify as an architectural work under the AWCPA. _Gaylord v. United
States_, 85 Fed. Cl. 59, 67, 72 (2008). However, the Court of Federal Claims
also determined that the government was not liable for copyright infringement
because the government's use of The Column was fair use. _Id._ at 71. Mr.
Gaylord appeals the court's decision as to fair use, and the government
challenges the court's determinations of ownership and the inapplicability of
the AWCPA. We have jurisdiction pursuant to 28 U.S.C. § 1295(a)(3).

[...]

II. Joint Authorship

The government asserts that it has rights to The Column through the
contributions of Cooper-Lecky, the VAB, and/or the CFA (collectively, the
government entities). Joint authors each possess an independent right to use or
license the copyrighted work, subject only to a duty to account to the other
coauthor(s) for any profits earned on the work. _Cmty. for Creative Non-Violence
v. Reid_, 846 F.2d 1485, 1498, 270 U.S. App. D.C. 26 (D.C. Cir. 1988) (_CCNV_),
aff'd, 490 U.S. 730, 109 S. Ct. 2166, 104 L. Ed. 2d 811 (1989). Cooper-Lecky
granted the government a license to use any work that Cooper-Lecky might hold
copyright in, and the VAB and CFA are government entities. Thus, if
Cooper-Lecky, the VAB, or the CFA are joint authors with Mr. Gaylord, the
government would have a right to use The Column free from Mr. Gaylord's claims
of infringement, subject to its duty to account to Mr. Gaylord.

On appeal, the government alleges that the trial court erred by misreading the
certificates of registration, by failing to treat the presumption of validity as
rebuttable, and by concluding that The Column was not a joint work. We conclude
that the Court of Federal Claims treatment on each issue was proper.

The Court of Federal Claims first noted that Mr. Gaylord was entitled to a prima
facie presumption of the validity of his copyright registrations. _Gaylord_, 85
Fed. Cl. at 66; _see also_ 17 U.S.C. § 410(c) ("In any judicial proceedings the
certificate of a registration made before or within five years after first
publication of the work shall constitute prima facie evidence of the validity of
the copyright and of the facts stated in the certificate. The evidentiary weight
to be accorded the certificate of a registration made thereafter shall be within
the discretion of the court."). On appeal, the government challenges this
presumption, arguing that statements of Mr. Gaylord's sole authorship are
rendered facially ambiguous because certain of his copyright registration
certificates indicate that the underlying work was "fully approved" or "[f]ully
approved by all federal commissions." These notations appear in the section
titled "Nature of Authorship," describing the nature of the work, rather than in
the space provided for the "Name of Author." The statements of approval do not
undermine Mr. Gaylord's assertions on his registration forms that he is the sole
author of The Column. Approval--much like comment and criticism--does not amount
to authorship. _See PODS, Inc. v. Porta Stor, Inc._, 484 F.3d 1359, 1370 (Fed.
Cir. 2007).

The government next argues that the Court of Federal Claims erred by failing to
treat the presumption of validity as rebuttable. It asserts that "Gaylord bears
the burden of establishing sole ownership of 'The Column'" because "the court
should have shifted the burden back to Gaylord in light of the government's
evidence." We disagree. The Court of Federal Claims thoroughly discussed the
government's evidence and concluded that "Defendant's proffered contributions of
the various committees to 'The Column' are not evidence of joint ownership, but
rather of suggestion and criticism." Gaylord, 85 Fed. Cl. at 67. The Court of
Federal Claims committed no error in its treatment of the burdens or in the
presumption of validity--the court treated the presumption as unrebutted, not
unrebuttable.

Finally, the government argues that the Court of Federal Claims erred in not
concluding that the copyright at issue was a joint work. We see no clear error
in the Court of Federal Claims' finding that The Column is not a joint work. "A
'joint work' is a work prepared by two or more authors with the intention that
their contributions be merged into inseparable or interdependent parts of a
unitary whole." 17 U.S.C. § 101. Authorship is a question of fact. _S.O.S., Inc.
v. Payday, Inc._, 886 F.2d 1081, 1086 (9th Cir. 1989); _see also Medforms, Inc.
v. Healthcare Mgmt. Solutions, Inc._, 290 F.3d 98, 110 (2d Cir. 2002).

Joint authorship requires "an original work of authorship" from each author.
_CCNV_, 846 F.2d at 1495. "To be an author, one must supply more than mere
direction or ideas: one must 'translate [] an idea into a fixed, tangible
expression entitled to copyright protection.'" S.O.S., 886 F.2d at 1087 (quoting
_CCNV_, 490 U.S. at 737); _see also PODS_, 484 F.3d at 1370 ("Mere participation
in, contributions to, and review of the work of [another person] would not
necessarily create a joint work."). As a general rule, each joint author must
make an independently copyrightable contribution to the work.[^Gaylord4] _See
Aalmuhammed v. Lee_, 202 F.3d 1227, 1234 (9th Cir. 1999); _Thomson v. Larson_,
147 F.3d 195, 200 (2d Cir. 1998); _Erickson v. Trinity Theatre, Inc._, 13 F.3d
1061, 1071 (7th Cir. 1994); _M.G.B. Homes, Inc. v. Ameron Homes, Inc._, 903 F.2d
1486, 1493 (11th Cir. 1990). Thus, "[a] co-authorship claimant bears the burden
of establishing that each of the putative co-authors (1) made independently
copyrightable contributions to the work; and (2) fully intended to be
co-authors." _Thomson_, 147 F.3d at 200.

[^Gaylord4]: The Seventh Circuit carved out an "exception" to this rule in a case
    where neither collaborator made independently copyrightable
    contributions, but the result of the collaboration produced a
    copyrightable work. _Gaiman v. McFarlane_, 360 F.3d 644, 658 (7th Cir.
    2004). The court explained that "it would be paradoxical if though the
    result of [the contributors'] joint labors had more than enough
    creativity and originality to be copyrightable, no one could claim
    copyright." _Id._ Because the government does not argue that Mr.
    Gaylord's work was not worthy of copyright protection, this exception
    does not apply here.

The government argues that the contributions of the various government entities
merged with Mr. Gaylord's contributions to create a joint work, analogizing to
_CCNV_, 846 F.2d at 1485. In _CCNV_, the Community for Creative Non-Violence (CCNV)
decided to sponsor a display to "dramatize the plight of the homeless." _CCNV_,
846 F.2d at 1487. Members of the CCNV conceived of a detailed plan for the
display, involving a modern Nativity scene depicting two homeless adults and one
infant huddling for warmth over a steam grate placed atop a pedestal from which
simulated steam would flow through the grate. _Id._ The CCNV also decided that
the display would include a shopping cart containing the belongings of the
homeless family. _Id._ at 1497 n.16. A sculptor, James Earl Reid, sculpted the
three human figures and the shopping cart, making changes along the way to
accommodate CCNV's requests. _Id._ at 1487-88. A cabinetmaker created the steam
grate pedestal. _Id._ at 1488. The two portions were joined and the entire work
was placed on display. _Id._ A dispute later arose over the copyright in the
work, and CCNV sought a declaration of copyright ownership. _Id._ The primary
issue in the case was whether the display was a work made for hire, which would
have given CCNV rights to the display. The United States Court of Appeals for
the District of Columbia Circuit concluded that the display was not a work made
for hire because the statutory requirements set forth in 17 U.S.C. § 101(2)were
not met, but remanded for the lower court to determine whether CCNV might have
rights as a joint author. _Id._ at 1494-98. It noted that CCNV contributed the
steam grate pedestal, created the initial concept of the display, and provided
ongoing direction of the realization of the display. _Id._ at 1497. It also
noted "various indicia of the parties' intent, from the outset, to merge their
contributions into a unitary whole, and not to construct and separately preserve
discrete parts as independent works." _Id._

The Supreme Court granted certiorari and determined that the display was not a
work made for hire, but noted that "CCNV nevertheless may be a joint author of
the sculpture if, on remand, the District Court determines that CCNV and Reid
prepared the work 'with the intention that their contributions be merged into
inseparable or interdependent parts of a unitary whole.'" _Cmty. for Creative
Non-Violence v. Reid_, 490 U.S. 730, 753, 109 S. Ct. 2166, 104 L. Ed. 2d 811
(1989). The case settled without a decision on the merits of the joint
authorship issue. _See Cmty. for Creative Non-Violence v. Reid_, Civ. No.
86-1507, 1991 U.S. Dist. LEXIS 21020, 1991 WL 415523 (D.D.C. Jan. 7, 1991).

The government asserts that the facts of _CCNV_ are "nearly identical" to this
case. As an analogy to the steam grate pedestal that CCNV contributed, the
government points to the physical contributions of Cooper-Lecky: a reflecting
pool, landscaping around The Column, and irregular polished granite bands
representing rice paddies. Notably, none of these features appear in the stamp.
Even more notably, none of these features appear in the copyright that Mr.
Gaylord obtained. Cooper-Lecky's physical contributions relate to the Memorial
as a whole, not The Column. Mr. Gaylord did not copyright the Memorial. His
copyright does not include the reflecting pool, the landscaping, or the rice
paddies. The copyright over which we are deciding ownership is the copyright of
The Column. None of these contributions by Cooper-Lecky establish entitlement to
joint authorship over The Column--they are completely independent from the
copyrighted matter in this case.

Focusing on The Column, the government lists several contributions by
Cooper-Lecky, the VAB, and the CFA as evidence of joint authorship. The VAB
created the story of each soldier, including the ethnicity, military service,
and equipment representative of soldiers in the Korean War. At one point, the
VAB told Mr. Gaylord to change the ethnicity of one soldier from Italian to
Hispanic. The VAB also told Mr. Gaylord to sculpt certain soldiers clean shaven
and others with buckled chin-straps. Although the government argues that Mr.
Gaylord, Mr. Nelson, and Cooper-Lecky all decided that the soldiers would wear
ponchos, we see no clear error in the Court of Federal Claims' finding that "the
poncho concept was based on models produced by Mr. Gaylord." Gaylord, 85 Fed.
Cl. at 67. According to the government, Cooper-Lecky instructed Mr. Gaylord to
reduce the amount of wind in the ponchos and to reduce the age of the soldiers
by removing wrinkles from their faces. Cooper-Lecky and the CFA had Mr. Gaylord
change the position of the first soldier in The Column from a celebratory
squatting pose to standing. Finally, a member of the VAB suggested that Mr.
Gaylord stagger the placement of the statues in formation. The government
asserted that Cooper-Lecky, the VAB, and the CFA "each collaborated to modify
the entire compositional structure and setting of 'The Column.'" _Id._ at 66.
The Court of Federal Claims found, however, that "Mr. Gaylord created the
composition of 'The Column,' using Colonel Bill Weber's [a member of the VAB]
suggestion to stagger the statues." _Id._ The Court of Federal Claims addressed
the contributions of Cooper-Lecky, the VAB, and the CFA and concluded that they
did not constitute evidence of joint authorship "but rather of suggestion and
criticism." _Id._ at 67. The court explained that "Mr. Gaylord was able to
translate the competing and conflicting ideas, comments, and suggestions of
multiple committee members into a new set of figures." _Id._ The Court of
Federal Claims' conclusions regarding the contributions by Mr. Gaylord and the
government entities are not clearly erroneous. While the government entities
provided some direction and ideas, this effort did not rise to the level
necessary for a joint work.

If one commissioned a work for a cowboy riding a horse, that contribution would
not constitute copyrightable expression. _See_ 17 U.S. C. § 102(b) (no copyright protection for ideas). If one
later instructed the artist to depict the cowboy as weathered, wearing a cowboy
hat, and riding slowly in calm wind, that would not rise to the level of
copyrightable expression. _See S.O.S._, 886 F.2d at 1087 ("A person who merely
describes to an author what the commissioned work should do or look like is not
a joint author for purposes of the Copyright Act."). The contributions to The
Column by Cooper-Lecky, the VAB, and the CFA amount to no more here. The VAB may
have suggested ethnicities and equipment to make the soldiers appear
representative of those in the Korean War, but it was Mr. Gaylord who
transformed those ideas into copyrightable expression. Cooper-Lecky may have
suggested that Mr. Gaylord depict more youthful soldiers with less wind in their
ponchos, but those ideas are not copyrightable. The government makes much of
Cooper-Lecky's role in changing the stance of the first soldier. But as the
Court of Federal Claims found, upon receiving suggestions and criticism from
Cooper-Lecky and members of the committees, Mr. Gaylord transformed the statues
himself. The Court of Federal Claims did not apply a "sole laborer" test as the
government alleges, rather, it found that the contributions made by
Cooper-Lecky, the VAB, and the CFA to The Column do not amount to independently
copyrightable expression. We see no clear error in the Court of Federal Claims'
conclusion that Mr. Gaylord is the sole author and sole owner of the copyright
in The Column.

Moreover, the Court of Federal Claims determined that the parties never intended
to create a joint work in The Column, as distinct from the Memorial. Gaylord, 85
Fed. Cl. at 67. Section 101 requires that a joint work "is a work prepared by
two or more authors with the intention that their contributions be merged into
inseparable or interdependent parts of a unitary whole." 17 U.S.C. § 101. We see
no clear error in the Court of Federal Claims' determination that Cooper-Lecky
and Mr. Gaylord did not intend The Column to be a joint work. As the Court of
Federal Claims indicates, "The history of 'The Column' project thus shows an
open and contentious dispute regarding copyright ownership, ultimately with
[Cooper-Lecky's] concession that Mr. Gaylord was the sole owner of the
copyright." Gaylord, 85 Fed. Cl. at 67. In 1994, before the soldier statues were
cast in their final form, Cooper-Lecky and Mr. Gaylord agreed that "[t]he
copyright for this work will be held by the Artist [Mr. Gaylord]." The agreement
goes on to specify that the terms of the use of the copyright are articulated
under a separate contract. The 1994 agreement was signed by Mr. Lecky of
Cooper-Lecky on January 27, 1994, and by Mr. Gaylord on February 7, 1994.
According to the government, the final full-sized soldiers were created in
August 1994.

The separate agreement referenced in the 1994 contract is a 1995 agreement in
which Mr. Gaylord granted Cooper-Lecky royalty-bearing licensing rights in Mr.
Gaylord's copyrighted work. The agreement acknowledged the separate
contributions of Cooper-Lecky and Mr. Gaylord to the Memorial, which the
agreement characterized as a collective work. The 1995 agreement, like the 1994
agreement, recognizes that Mr. Gaylord "is the sole author of the soldier
sculptures to become part of the overall Memorial." The government asserts that
the 1995 agreement cannot dispose of the authorship dispute because it arose
after Mr. Gaylord created the final full-sized soldiers, and copyright ownership
vests at the moment the work is fixed in any tangible form. Although it arose
after the creation of the statues in their final form, the 1995 agreement
reflects the understandings of Cooper-Lecky and Mr. Gaylord with respect to
authorship of The Column and ownership of its copyright. The 1995 agreement
crystallizes the intentions of the parties, which are manifest from the 1994
agreement and actions of the parties preceding the creation of The Column. We
see no clear error in the Court of Federal Claims' determination that the
parties never intended The Column to be a joint work.

The dissent argues that the government escapes liability for copyright
infringement either by virtue of a contract with Cooper-Lecky or 28 U.S.C. § 1498. These issues were raised sua sponte by the dissent--we received no argument or briefing on either issue. The government cannot escape liability under its DACA31-90-C-0057 contract because Mr. Gaylord is not a party to that contract. Moreover, neither section of DACA31-90-C-0057 cited by the dissent concerns works by Mr. Gaylord. Section I-28 concerns works to which Cooper-Lecky
could assert or establish authorship. Section I-29 concerns works made for hire,
and the government has not provided any evidence establishing that The Column
was a work made for hire. _See_ 17 U.S.C. §§ 101, 201. Nor can the government
escape liability under 28 U.S.C. § 1498, because there is no evidence that Mr.
Gaylord created The Column in the service of the United States or using
government time, material, or facilities. We decline to engage in appellate
fact-finding to cobble together an excuse for the government's copyright
infringement.

We conclude that the Court of Federal Claims did not clearly err in determining
that authorship of The Column rested solely with Mr. Gaylord.

[***]

##### Discussion

1.  What do the United States Government in _Gaylord_ and Aalmuhammed in
    _Aalmuhammed_ have in common? What distinguishes their cases from one another?
    Which comes closer to demonstrating joint authorship?

2.  What consequences could the legal operation of joint authorship have on the
    maintenance of an open source project? What is the worst thing that could
    happen to a contributor as a result of failing to be acknowledged as a joint author of a
    project that the contributor largely authored? What is the worst thing that could happen to a project
    as a result of the project acknowledging a person who creates a one character bug fix as
    a joint author of the project?

3.  If an open source project that originated with a sole entity is determined
    to be a work jointly authored by multiple entities, what is the harm
    suffered by the original entity? How could the latter entities exploit the
    work in a way that would be injurious to the original entity?

4.  How might the duty of accounting[^Accounting] come into play in the context
    of a jointly-authored open source project? Can the joint author of an open
    source project use the entire project outside the terms of its license? If
    the joint author were to use the project under the terms of the license,
    would the duty of accounting automatically be satisfied?

[^Accounting]: _See Oddo v. Ries_, 743 F.2d 630, 633 (9th Cir. 1984) ("A
    co-owner of a copyright must account to other co-owners for any
    profits he earns from licensing or use of the copyright, but the
    duty to account does not derive from the copyright law's
    proscription of infringement. Rather, it comes from equitable
    doctrines relating to unjust enrichment and general principles of
    law governing the rights of co-owners.")(internal quotations
    omitted).

## Section 2 - Copyrightable Works: The Role of Collective Works in Open Source Projects

While Section 1 of this chapter focused on the nature of a copyright property
interest, distinguishing individual copyright holders from joint authors, this
section will address the different types of copyrightable works, and the role
that this distinction plays in open source development. The primary focus will
be on the specific type of work that open source projects are most commonly
considered to be: a collective work.

To be a collective work, the work must be composed of pieces that constitute
separate and independent works of authorship. At first blush, this requirement
creates the impression that an open source project would only constitute a
collective work when the project incorporates a free-standing library or piece
of software as a component of the project. However, does this narrow
interpretation of the requirement reconcile with copyright law? Might a work be
able to constitute a separate, independent work of authorship without meeting
the criteria that one would associate with a free-standing library or piece of
software?

There are some scenarios in open source development that clearly point to the
creation of a collective work. The primary example being the case where a
pre-existing library is added, in its entirety, to an open source project. This
action neatly fits the statutory definition of a collective work. But does any
contribution to an open source project create a collective work? What are the
rights held by the author of a component of a collective work?

### _TCA Television Corp. v. McCollum_, 839 F.3d 168 (2d Cir. 2016)

Our first case will examine the barriers that exist to alleging copyright
infringement of a work that is merely an incorporated component of a larger
work. In this case, the component work at issue is Abbot and Costello’s famous
_Who’s On First_ routine, a self-contained routine that featured as a component
of various radio and television performances. When the routine was later
exploited by a third party, who has standing to sue?

#### Opinion

Reena Raggi, Circuit Judge:

In this action for copyright infringement, plaintiffs, successors-in-interest to
the estates of William "Bud" Abbott and Lou Costello, appeal from a judgment of
dismissal entered in the United States District Court for the Southern District
of New York (George B. Daniels, Jr., _Judge_) in favor of defendants, who
include the producers of Hand to God and the play's author, Robert Askins. _See
TCA Television Corp. v. McCollum_, 151 F. Supp. 3d 419 (S.D.N.Y. 2015).
Plaintiffs assert that the district court erred in concluding from the amended
complaint that defendants' use of a portion of the iconic Abbott and Costello
comedy routine, _Who's on First?_, in Act I of _Hand to God_ was so
transformative as to establish defendants' fair use defense as a matter of law.
_See_ Fed. R. Civ. P. 12(b)(6). Defendants here not only defend the district
court's fair use determination but also argue that affirmance is warranted, in
any event, by plaintiffs' failure to plead a valid copyright interest. The
district court rejected that argument. _See TCA Television Corp. v. McCollum_,
151 F. Supp. 3d at 430-31.[^TCA1]

[^TCA1]: Defendants do not cross-appeal the district court's denial of dismissal
    on the ground of copyright invalidity; rather, they argue it as an
    alternative ground for affirmance, even if plaintiffs' fair use
    challenge prevails. In this opinion, we first address plaintiffs'
    challenge to the fair use determination supporting dismissal because if
    we were to identify no error in that ruling there would be no need to
    consider defendants' proposed alternative ground for affirmance.

For the reasons explained herein, we conclude that defendants' verbatim
incorporation of more than a minute of the _Who's on First?_ routine in their
commercial production was not a fair use of the material. Nevertheless, we
affirm dismissal because plaintiffs fail plausibly to allege a valid copyright
interest.

I. Background

The following facts derive from plaintiffs' amended complaint, incorporated
exhibits, and documents susceptible to judicial notice. _See Goel v. Bunge,
Ltd._, 820 F.3d 554, 559 (2d Cir. 2016)(acknowledging that, on motion to
dismiss, courts may consider documents appended to or incorporated in complaint
and matters of which judicial notice may be taken); _Island Software & Comput.
Serv., Inc. v. Microsoft Corp._, 413 F.3d 257, 261 (2d Cir. 2005) (stating that
court may take judicial notice of copyright registrations). For purposes of this
appeal, we presume these facts to be true. _See Anschutz Corp. v. Merrill Lynch
& Co._, 690 F.3d 98, 102 (2d Cir. 2012).

A. Abbott and Costello's Who's on First? Routine

Abbott and Costello were a popular mid-Twentieth Century comedy duo. One of
their routines, commonly referred to as Who's on First? (also, the "Routine"),
has become a treasured piece of American entertainment history.[^TCA2] The
Routine's humor derives from misunderstandings that arise when Abbott announces
the roster of a baseball team filled with such oddly named players as "Who,"
"What," and "I Don't Know." A rapid-fire exchange reveals that "who's on first"
need not be a question. It can be a statement of fact, i.e., a player named
"Who" is the first baseman. Later parts of the routine reveal, after similar
comic misunderstandings, that a player named "What" is the second baseman, and
one named "I Don't Know" is the third baseman.

[^TCA2]: In 1999, _Time_ magazine named the Routine the best comedy sketch of
    the Twentieth Century. _See_ Am. Compl. ¶ 37; _Best of the Century_,
    Time, December 31, 1999, at 73.

B. Agreements Pertaining to Rights in the Routine

The parties cite various contracts and copyright filings spanning more than 40
years as relevant to claimed rights in the Routine.

1) Abbott and Costello's Agreements with UPC

a. The July 1940 Agreement

Abbott and Costello first performed _Who's on First?_ in the late 1930s, notably
on a 1938 live radio broadcast of _The Kate Smith Hour_. The Routine was
published for purposes of federal copyright law when Abbott and Costello
performed a version of it in their first motion picture, _One Night in the
Tropics_ ("_Tropics_").[^TCA3]

[^TCA3]: Viewing the facts in the light most favorable to plaintiffs, the
    district court discussed in some detail why (1) before _Tropics_'s
    release, the Routine was protected by common law copyright; and (2) the
    movie's release could constitute "publication" of the Routine,
    extinguishing any common law right and requiring registration and
    deposit with the federal Copyright Office to claim any statutory
    copyright protection. _See TCA Television Corp. v. McCollum_, 151 F.
    Supp. 3d at 427-30.

The team appeared in Tropics pursuant to a July 24, 1940 contract (the "July
Agreement") with Universal Pictures Company, Inc. ("UPC"). The July Agreement
guaranteed Abbott and Costello a minimum of five weeks' work at a pay rate of
$3,500 per week. In turn, Abbott and Costello (the "Artists") agreed to grant
UPC (the "Producer") certain rights and to furnish it with certain items. We
reproduce the relevant text here, adding bracketed signals and highlighting to
distinguish various provisions:

> [1] The Artists expressly give and grant to the Producer the sole and
> exclusive right to photograph and/or otherwise reproduce any and all of their
> acts, poses, plays and appearances of any and all kinds during the term
> hereof, and [2] further agree [a] to furnish to the Producer, without charge
> to it, the material and routines heretofore used and now owned by the Artists
> for use by the Producer in the photoplay in which they appear hereunder and
> for which the Producer shall have the exclusive motion picture rights, and [b]
> to record their voices and all instrumental, musical and other sound effects
> produced by them, and [c] to reproduce and/or transmit the same, either
> separately or in conjunction with such acts, poses, plays and appearances as
> the Producer may desire, and further [3] give and grant to the Producer solely
> and exclusively all rights of every kind and character whatsoever in and to
> the same, or any of them, perpetually, including as well the perpetual right
> to use the names of the Artists and pictures or other reproductions of the
> Artists' physical likenesses, and recordations and reproductions of the
> Artists' voices, in connection with the advertising and exploitation thereof.

J.A. 168-69.

b. The November 1940 Agreement

On November 6, 1940, only days before _Tropics_'s public release, Abbott and
Costello entered into a new multi-year/multi-picture agreement with UPC (the
"November Agreement").[^TCA4] That contract terminated the July Agreement
without prejudice to, among other things, UPC's "ownership . . . of all rights
heretofore acquired," including those "in or to any . . . material furnished or
supplied by the Artists." _Id._ at 162. In the November Agreement, Abbott and
Costello agreed "to furnish and make available to the Producer all literary and
dramatic material and routines heretofore used by the Artists either on the
radio or otherwise and now owned by the Artists," and acknowledged that "the
Producer shall have the right to use said material and routines to such extent
as the Producer may desire in connection with any photoplay in which the Artists
render their services hereunder and in connection with the advertising and
exploitation of such photoplay." _Id._ at 129. Abbott and Costello agreed that
they would "not use or license, authorize or permit the use of any of the
material and/or routines" so referenced "in connection with motion pictures" by
others than UPC for specified times. _Id._ Nevertheless, they reserved the right
to use materials and routines created by them (without the assistance of UPC
writers) "on the radio and in personal appearances." _Id._ at 129-30.

[^TCA4]: Plaintiffs' amended complaint cites only the November Agreement with
    UPC as the relevant contract. _See_ Am. Compl. ¶ 43. By the time that
    agreement was signed, however, Abbott and Costello presumably had
    already finished their work on _Tropics_—including any additions to the
    Routine reflected in that movie. Thus, it would appear that the team's
    work on _Tropics_ was pursuant to the July Agreement, discussed _supra_
    at I.B.1.a. The discrepancy does not affect our analysis here because,
    in the district court, defendants conceded that, at least for purposes
    of their motion to dismiss, the July Agreement had "in effect, been
    pleaded" by plaintiffs in support of their claim. Sept. 9, 2015 Hr'g
    Tr. 2-3.

2) UPC Registers a Copyright for _Tropics_

In November 1940, UPC registered a copyright for _Tropics_ with the United
States Copyright Office, which it renewed in December 1967. _See id._ at 36,
39-40.

3) UPC Uses an Expanded Version of the Routine in The Naughty Nineties and
Registers a Copyright for that Movie

In 1945, Abbott and Costello performed an expanded version of _Who's on First?_
in another movie for UPC, _The Naughty Nineties_. That version maintains the
core of the Routine—with "Who" on first base, "What" on second, and "I Don't
Know" on third—but several new players take the field: left fielder "Why,"
center fielder "Because," pitcher "Tomorrow," catcher "Today," and shortstop "I
Don't Care."

In June 1945, UPC registered a copyright for _The Naughty Nineties_ with the
United States Copyright Office, which it renewed in 1972. _See id._ at 37,
41-42; Am. Compl. ¶ 45.[^TCA5]

[^TCA5]: By operation of the Sonny Bono Copyright Term Extension Act, Pub. L.
    No. 105-298, 112 Stat. 2827 (1998), the renewal term for _Tropics_ will
    not expire until 2035 and that for _The Naughty Nineties_ will not
    expire until 2040. _See_ 17 U.S.C. § 304(b).

4) The 1944 Copyright Registration for "Abbott and Costello Baseball Routine"

In April 1944, a work entitled "Abbott and Costello Baseball Routine" was
registered with the Copyright Office "in the name of Bud Abbott and Lou
Costello, c/o Writers War Board." J.A. 114. The certificate indicates that this
"Baseball Routine" was published on "March 13, 1944" in "'_Soldier Shows_,' No.
19." _Id._[^TCA6] The record suggests that this registration was not renewed,
prompting the Copyright Office to conclude that the work had entered the public
domain in 1972, and, on that ground, to reject a 1984 application for a
derivative work registration filed by the children of Abbott and Costello based
on the 1944 registration.

[^TCA6]: The George Mason University Libraries, in their "Guide to the John C.
    Becher Soldier Show Collection, 1940-1953," indicates that "Soldier
    Shows" refers to entertainments "made by soldiers for soldiers," with
    the object of "mass participation" to raise morale. J.A. 208-09.
    Because the record here is devoid of any information about either
    Soldier Shows generally or Soldier Shows, No. 19 in particular, we make
    no assumptions about the content of the material that is the subject of
    the 1944 copyright registration.

5) The 1984 Quitclaim Agreement

Plaintiffs do not rely on the 1944 registration to support their copyright claim
here. Rather, they claim to have succeeded to UPC's copyright interests in the
Routine as performed in Tropics and The Naughty Nineties based on a quitclaim
agreement dated March 12, 1984 (the "Quitclaim").

In the Quitclaim, which was subsequently recorded with the Copyright Office,
UPC's successor-in-interest, Universal Pictures ("Universal"), granted Abbott &
Costello Enterprises ("A & C"), a partnership formed by the heirs of Abbott and
Costello,[^TCA7] "any and all" of Universal's rights, title, and interest in the
Routine. _Id._ at 45. Universal stated that it did so relying upon A & C's
representation that it was "a partnership composed of the successors in interest
to the late Bud Abbott and Lou Costello" and, therefore, "the owner of copyright
in and to the Routine." _Id._ at 46.

[^TCA7]: Bud Abbott died in 1974; Lou Costello died in 1959. _See Bud Abbott,
    Straight Man to Lou Costello, Is Dead_, N.Y. Times, April 25, 1974, at
    42; _Lou Costello, 52, Dies on Coast; Comic Had Teamed with Abbott_,
    N.Y. Times, Mar. 4, 1959, at 31.

A & C dissolved in 1992, with 50% of its assets transferred to TCA Television
Corporation, a California entity owned by Lou Costello's heirs, and the other
50% divided evenly between Bud Abbott's heirs, Vickie Abbott Wheeler and Bud
Abbott, Jr. Wheeler would later transfer her 25% interest to a California
partnership, Hi Neighbor, and Abbott, Jr. would transfer his 25% interest to
Diana Abbott Colton. It is by operation of the Quitclaim and the referenced
dissolution and transfer agreements that plaintiffs TCA Television, Hi Neighbor,
and Colton now claim a copyright interest in Who's on First?.

C. Hand to God

As described in the amended complaint, _Hand to God_ (the "Play") is "a dark
comedy about an introverted student in religious, small-town Texas who finds a
creative outlet and a means of communication through a hand puppet, wh[ich]
turns into his evil or devilish persona." Am. Compl. ¶ 58. After two successful
off-Broadway runs, _Hand to God_ opened to critical acclaim on Broadway in the
spring of 2015. Through press coverage, plaintiffs learned that _Hand to God_
incorporated part of the Routine in one of its "key scene[s]," without license
or permission. _Id._ at ¶ 63. While the Play was still in previews for its
Broadway opening, plaintiffs sent defendants a cease and desist letter.
Defendants' failure to comply with that request prompted this lawsuit.

1.  The Relevant Scene

Plaintiffs allege that the Play infringes their copyright in the Routine by
using its first part—that is, the part pertaining to first baseman "Who"—in Act
I, Scene 2. In that scene, which occurs approximately 15 minutes into the Play,
the lead character, "Jason," and the girl with whom he is smitten, "Jessica,"
have just emerged from the basement of their church, where they had been
participating in a Christian puppet workshop. Jason tries to impress Jessica by
using his sock puppet, "Tyrone," to perform, almost verbatim, a little over a
minute of _Who's on First?_. Jason plays the Bud Abbott role, while Tyrone
assumes Lou Costello's character.[^TCA8]

[^TCA8]: (footnote describing the Routine as used in the Play omitted).

When Jason somewhat bashfully concludes the "Who" part of the Routine, Jessica
compliments him by saying, "That's really good," and asks, "Did you come up with
that all by yourself[?]" Suppl. App'x 21. When Jason answers, "Yes," the
audience laughs at what it recognizes as a lie. _Id._; _see_ Am. Compl. ¶ 64.
The answer, however, triggers a different response from the puppet, which,
seemingly of its own volition, calls Jason a "Liar," and states that the comic
exchange they just performed is "a famous routine from the [F]ifties." Suppl.
App'x 21. Jason corrects Tyrone, stating that the sketch is from the "Forties."
_Id._ Tyrone then insults Jessica, telling her that she would know the Routine's
origin if she "weren't so stupid." _Id._ Jason and Jessica each order Tyrone to
"shut up" to no effect. _Id._ at 22. Instead, as the scene continues, Tyrone
vulgarly divulges Jason's physical desire for Jessica. Only after a seeming
physical struggle with Tyrone is Jason able to remove the puppet from his hand
and thereby end Tyrone's outburst. Jason tries to apologize to Jessica, but she
quickly exits, leaving Jason—in the words of the stage direction— "[d]efeated by
what he ca[]n't defeat." _Id._ at 24.

The scene foreshadows darker and more disturbing exchanges between Jason and the
puppet that will occur as the Play proceeds.

1.  Promotional Materials

Plaintiffs allege that, in online promotional materials for the Play, defendants
used a "video clip" of Jason and his puppet performing _Who's on First?_ to
"stoke interest" in and sell tickets for the Play. Am. Compl. ¶¶ 69, 89. These
promotional materials are not part of the court record.

D. District Court Proceedings

On June 4, 2015, plaintiffs filed this action in the Southern District of New
York, claiming both federal and common law copyright infringement. Defendants
promptly moved to dismiss, arguing, _inter alia_, that (1) plaintiffs did not
hold a valid copyright; (2) the Routine was in the public domain; and (3) _Hand
to God_'s incorporation of the Routine was sufficiently transformative to
qualify as a permissible fair use, not prohibited infringement.

On December 17, 2015, the district court granted defendants' motion to dismiss.
It declined to do so on either of the first two grounds argued by defendants,
concluding that, at the 12(b)(6) stage, plaintiffs had "sufficiently alleged a
continuous chain of title" to the Routine to survive dismissal. _TCA Television
Corp. v. McCollum_, 151 F. Supp. 3d at 431. Instead, the court concluded that
dismissal was warranted because defendants' use of _Who's on First?_ in _Hand to
God_ was "highly transformative" and a non-infringing fair use. _Id._ at 434,
437.

This appeal followed.

[...]

B. Dismissal for Failure To Plead a Valid Copyright

Defendants argue that, even if we reject dismissal on the basis of a fair use
defense, we should affirm because plaintiffs fail plausibly to plead ownership
of a valid copyright in the Routine. _See Feist Publ'ns, Inc. v. Rural Tel.
Serv. Co._, 499 U.S. 340, 361, 111 S. Ct. 1282, 113 L. Ed. 2d 358 (1991)
(identifying two elements of infringement: (1) ownership of valid copyright and
(2) copying original elements of work). Defendants assert that Abbott and
Costello's Who's on First? Routine fell into the public domain in 1968, when the
initial copyright term for Tropics expired. Defendants concede that UPC's
registration for that movie protected the Routine—first published therein—from
entering the public domain through the term of that copyright, _see Shoptalk,
Ltd. v. Concorde-New Horizons Corp._, 168 F.3d 586, 592 (2d Cir. 1999), but they
assert that only Abbott and Costello, as the Routine's authors, could renew the
copyright in that work—as distinct from Tropics—which the team failed to
do.[^TCA15]

[^TCA15]: Because both parties seemingly concede that the Routine was protected
    from entering the public domain through at least _Tropics_'s initial
    copyright term, we need not determine whether _Tropics_'s publication
    automatically divested Abbott and Costello of their common law
    copyright and injected it into the public domain. _See Roy Export Co.
    Establishment of Vaduz, Liechtenstein v. Columbia Broad. Sys., Inc._,
    672 F.2d 1095, 1101-02 (2d Cir. 1982).

In disputing this challenge, plaintiffs argue that UPC had the right to renew
the copyright in the Routine because (1) Abbott and Costello assigned ownership
of their common law copyright in the Routine to UPC in either the July or
November Agreement, (2) the Routine as published in Tropics was a "work for
hire" owned by UPC, and (3) the Routine merged into Tropics so as to support a
single copyright. Plaintiffs maintain that, under any of these theories, UPC's
renewal of the Tropics copyright also maintained copyright protection for the
Routine, so that they now hold a valid copyright in that work by virtue of UPC's
transfer of its rights in the Routine in the Quitclaim.

We identify no merit in any of the theories relied on by plaintiffs to support
their copyright claim and, accordingly, we affirm dismissal of the amended
complaint for failure to plead a valid copyright.

1.  Copyright Assignment

In rejecting defendants' copyright invalidity challenge, the district court
thought that "[t]he contract language, together with UPC's subsequent
registration of the copyrights" for _Tropics_ and _The Naughty Nineties_, might
admit a finding of "implied assignment of the initial copyright from Abbott and
Costello." _TCA Television Corp. v. McCollum_, 151 F. Supp. 3d at 429; _see
Nimmer_ § 10.03[B][2], at 10-56.2(6) (explaining that pre-1978 assignment of
common law copyright could be effectuated orally or implied from conduct). The
conclusion is flawed in two respects. First, as detailed in this section, the
July and November Agreements clearly express the parties' intent for Abbott and
Costello to license the use of, not to assign copyrights in, their existing
comedy routines for use in UPC movies in which the team appeared. Second, and
requiring no further discussion in the face of clear contract language, UPC's
registration (and renewal) of copyrights in its movies says nothing about what
Abbott and Costello intended to convey in the two agreements because UPC would
have taken such action to protect its independent movie rights in any event.
_See generally Faulkner v. Nat'l Geographic Soc'y_, 220 F. Supp. 2d 237, 239
(S.D.N.Y. 2002)(noting that under 1909 Copyright Act, proprietor of collective
work had right to renew copyright in collective work itself).

Turning then to the agreements, we note at the outset that neither contract has
a choice of law provision. Thus, the controlling law would be the contract's
"center of gravity," which typically is the place of contracting or performance.
_Lazard Freres & Co. v. Protective Life Ins. Co._, 108 F.3d 1531, 1539 (2d Cir.
1997)(internal quotation marks omitted). The July Agreement was executed in New
York with expected performance in California. The November Agreement was also to
be performed in California and may have been executed there, where UPC was
located and Abbott and Costello were then completing _Tropics_. Any uncertainty
on the latter point is irrelevant, however, because New York and California law
both instruct that contracts must be interpreted according to the mutual intent
of the parties at the time the contract was formed. _See Welsbach Elec. Corp. v.
MasTec N. Am., Inc._, 7 N.Y.3d 624, 629, 859 N.E.2d 498, 825 N.Y.S.2d 692, 695
(2006); _AIU Ins. Co. v. Superior Court_, 51 Cal. 3d 807, 821, 274 Cal. Rptr.
820, 799 P.2d 1253, 1264 (1990). Both states recognize that the best evidence of
the parties' intent is the language used in their contract. _See Brad H. v. City
of New York_, 17 N.Y.3d 180, 185, 951 N.E.2d 743, 928 N.Y.S.2d 221, 224 (2011);
_AIU Ins. Co. v. Superior Court_, 51 Cal. 3d at 822, 799 P.2d at 1264. Thus,
where contract language is clear and unambiguous, courts will enforce an
agreement according to its terms, without looking outside the four corners of
the document. _See Brad H. v. City of New York_, 17 N.Y.3d at 185, 928 N.Y.S.2d
at 224; _AIU Ins. Co. v. Superior Court_, 51 Cal. 3d at 822, 799 P.2d at 1264.

The July Agreement employing Abbott and Costello for "one feature photoplay,"
J.A. 165, states that the team would furnish UPC with "routines heretofore used
and now owned by Artists for use by the Producer in the photoplay in which they
appear hereunder and for which the Producer shall have the exclusive motion
picture rights," _id._ at 169 (emphases added). The longer-term November
Agreement similarly states that the team would furnish UPC with all "routines
heretofore used by the Artists either on the radio or otherwise and now owned by
the Artists," and that UPC would "have the right to use said material and
routines to such extent as the Producer may desire in connection with any
photoplay in which the Artists render their services hereunder." _Id._ at 129
(emphases added). As the highlighted language in each agreement makes plain,
Abbott and Costello furnished UPC with their routines for a limited purpose: use
in any movies in which the team appeared under the respective
agreements.[^TCA16] This is unmistakably the language of an exclusive,
limited-use license, not the assignment of copyright. _See_ Compendium of
Copyright Office Practices § 12.2.1 (1973) (stating that license is "exclusive
or non-exclusive grant of permission to use a copyrighted work for certain
purposes").

[^TCA16]: Plaintiffs acknowledged as much in the district court when they argued
    that the agreements' language "represented a clear grant of rights to
    UPC in all previous acts and routines created by Abbott and Costello .
    . . _if used in any motion pictures produced by UPC in which Abbott &
    Costello provided their services._" Pls.' Mem. Opp. Mot. Dismiss at 7,
    _TCA Television Corp. v. McCollum_, No. 15-cv-4325 (GBD), ECF No. 61
    (emphasis added).

A clause in the July Agreement granting UPC "all rights of every kind and
character whatsoever in and to the same . . . perpetually" warrants no different
conclusion. J.A. 169. This language appears in the same sentence as that quoted
in the preceding paragraph and, thus, "all rights . . . in and to the same" can
only be understood to reference UPC's motion picture rights, not the team's
common law copyright in its routines.[^TCA17] Indeed, in the November Agreement,
wherein the team grants UPC the right to photograph and reproduce their "acts,"
the "perpetual" right "to use the same" is expressly granted "only in connection
with the photoplays in which the Artists appear hereunder and in connection with
the advertising and exploitation thereof." _Id._ at 127. The November Agreement
states that "the Producer shall not have the right to use the Artists' names or
likenesses or reproductions of their voices in radio broadcasts (except as
hereinafter expressly permitted) independent of . . . motion picture productions
or in commercial tie-ups." _Id._ at 128.

[^TCA17]: _See supra_ p. 7 (quoting relevant sentence in July Agreement in
    full).

Other language in the November Agreement further confirms that Abbott and
Costello granted UPC only a license to use their routines. The team therein
agreed "that they w[ould] not use or license, authorize or permit the use of any
of the material and/or routines" furnished to UPC under the agreement "in
connection with motion pictures for any person, firm or corporation other than
the Producer, at any time prior to the termination of the employment of the
Artists under this agreement or one year after the general release of the
photoplay in which used, whichever is later." _Id._ at 129. The fact that the
Agreement limits Abbott and Costello's ability to use or license specified
material (i.e., material created before the agreements) only "in connection with
motion pictures," and only for a limited time, plainly indicates the parties'
understanding that the team retained ownership of the copyright in their
pre-agreement material and granted UPC only a license. _See P.C. Films Corp. v.
MGM/UA Home Video Inc._, 138 F.3d 453, 456 (2d Cir. 1998) (explaining that under
1909 Copyright Act, "transfer of anything less than the totality of rights
commanded by copyright was automatically a license rather than an assignment
[of] the copyright").

Thus, the language of the July and November Agreements, by itself, clearly
belies plaintiffs' claim that Abbott and Costello therein conveyed their common
law copyright in the Routine to UPC. That conclusion is reinforced by the very
Quitclaim on which plaintiffs' claimed ownership of the _Who's on First?_
copyright depends. To secure the Quitclaim of UPC's interests in the Routine
(then held by its successor, Universal), plaintiffs' predecessors-in-interest
therein represented that they owned the copyright in the Routine. In short, the
parties to the Quitclaim understood Abbott and Costello not to have transferred,
but to have retained, ownership of the Routine's copyright.

Accordingly, plaintiffs cannot state a plausible infringement claim based on a
1940 transfer of copyright ownership from Abbott and Costello to UPC in either
the July or November Agreement. The record does not support such
assignment.[^TCA18]

[^TCA18]: Because the agreements cannot be construed to effect an assignment of
    the Routine's copyright to UPC, we need not decide whether they
    further conveyed the Routine's renewal rights. _See Corcovado Music
    Corp. v. Hollis Music, Inc._, 981 F.2d 679, 684 (2d Cir. 1993)
    (recognizing strong presumption against conveyance of renewal rights).

1.  Work Made for Hire

Plaintiffs maintain that, even if the July and November Agreements cannot be
construed to have assigned copyrights, they are work-for-hire agreements. They
argue that UPC, "[a]s the author under a work-for-hire agreement of the films .
. . , properly registered its copyright in these two films with the Copyright
Office, and thereafter timely renewed their copyright registrations."
Appellants' Br. 9; _see Estate of Burne Hogarth v. Edgar Rice Burroughs, Inc._,
342 F.3d 149, 156-57 (2d Cir. 2003) (explaining that, under 1909 Copyright Act,
employer was legal author and, therefore, had renewal rights).

The argument is defeated by plaintiffs' own allegation—which we must accept as
true—that the Routine was first performed in March 1938, more than two years
before Abbott and Costello entered into the July and November Agreements with
UPC. _See_ Am. Compl. ¶ 32. Insofar as Abbott and Costello had already performed
_Who's on First?_ in 1938, they plainly did not _create_ the Routine at UPC's
"instance and expense" in 1940, as would be required for it to be a
work-for-hire. _Playboy Enters., Inc. v. Dumas_, 53 F.3d 549, 554 (2d Cir. 1995)
(stating that work is considered "for hire" when made at hiring party's instance
and expense, _i.e._, "when the motivating factor in producing the work was the
employer who induced the creation" (internal quotation marks omitted)); _see
also Urantia Found. v. Maaherra_, 114 F.3d 955, 961 (9th Cir. 1997) ("An
employment (or commissioning) relationship at the time the work is created is a
condition for claiming renewal as the proprietor of a work made for hire."
(internal quotation marks omitted)).

Plaintiffs seek to avoid this conclusion by noting defendants' (1) concession—at
least for purposes of their motion to dismiss—that new material was added to the
Routine for Tropics, _see TCA Television Corp. v. McCollum_, 151 F. Supp. 3d at
431; and (2) failure to establish "the contents, language or scope of
protectable expression of the 1938 radio broadcast," Appellants' Reply Br. 22.
We are not persuaded.

On review of a motion to dismiss, courts must draw all reasonable inferences in
plaintiffs' favor. Even applying that principle here, it is not plausible to
infer that the Routine, as performed in 1938, did not already contain the
initial series of exchanges about a person named "Who" playing first base for
the simple reason that there is no Routine without at least that part. Further,
because that is the part of the Routine appropriated in _Hand to God_,
plaintiffs must plausibly allege a valid copyright in that material, regardless
of later additions. Thus, to the extent plaintiffs' copyright claim rests on a
theory of work-for-hire, it was their burden to plead facts showing that the
appropriated parts of the Routine had not existed in the 1938 iteration of
_Who's on First?_, but were first created for Tropicsso as to be covered by the
copyright and copyright renewal of that movie. _See Feist Publ'ns, Inc. v. Rural
Tel. Serv. Co._, 499 U.S. at 361(stating that to establish infringement claim,
plaintiff must demonstrate, among other things, ownership of valid copyright).

1.  Merger of Routine in Motion Pictures

Finally, plaintiffs argue that even if their copyright ownership claim cannot
rest on either an assignment or work-for-hire theory, it is plausible because
"so much of the Routine as was used in the Movies 'merged' with the Movies to
become a 'unitary whole.'" _See_ Appellants' Reply Br. 28. Thus, the Routine was
not separately registerable; rather it was protected by UPC's statutory
registration and its renewal of the copyrights for movies using the Routine.

This argument also fails because, as this court recently observed, "authors of
_freestanding_ works that are incorporated into a film . . . may copyright these
'separate and independent works.'" _16 Casa Duse, LLC v. Merkin_, 791 F.3d 247,
259 (2d Cir. 2015) (emphasis added) (quoting 17 U.S.C. § 101); _see id._ at 257
(noting that separate copyrights may be necessary where motion picture
incorporates "separate, freestanding pieces that independently constitute 'works
of authorship'"). _Who's on First?_ was such a freestanding work within
_Tropics_. As already noted, plaintiffs acknowledged in the amended complaint
that the Routine (1) was prepared and existed on its own for some years before
it was performed in _Tropics, see_ Am. Compl. ¶ 32; and (2) was performed
independently from the films "thousands of times" on the radio and elsewhere,
_see id._ at ¶¶ 34-35; _see also_ J.A. 129 (stating in November Agreement that
"Artists reserve the right to use on the radio and in personal appearances" all
preexisting routines). The Quitclaim representation that plaintiffs'
predecessors-in-interest still owned the Routine's copyright in 1984 is also at
odds with the argument that the Routine had so merged with _Tropics_ as to admit
a single copyright owned by UPC.

Neither _Garcia v. Google, Inc._, 786 F.3d 733 (9th Cir. 2015) (_en banc_), nor
_Richlin v. Metro-Goldwyn-Mayer Pictures, Inc._, 531 F.3d 962 (9th Cir. 2008),
relied on by plaintiffs, is to the contrary. In Garcia, the Ninth Circuit
reversed a panel decision holding that an actor's five-second contribution to a
movie was sufficiently creative to entitle her to register a copyright in her
performance. The en banc court explained that "[t]reating every acting
performance as an independent work" would be a "logistical and financial
nightmare." _Garcia v. Google, Inc._, 786 F.3d at 743. This case is not
analogous. While the screen actor's performance there was so "integrated into"
the filmed work as to be "inseparable from" it, _see 16 Casa Duse, LLC v.
Merkin_, 791 F.3d at 254, _Who's on First?_ is a freestanding comedy routine
performed by Abbott and Costello not only years before the first frame of
_Tropics_ was ever filmed but also for many years thereafter. Thus, the concerns
at issue in _Garcia_ are not present here.

As for _Richlin_, the Ninth Circuit did not there hold, as plaintiffs contend,
that an author is "_not_ entitled to an independent copyright by reason of
inclusion of his [story] treatment's material in [a] motion picture."
Appellants' Reply Br. 27-28 (emphasis in original). Rather, the court there
assumed that plaintiffs' story treatment was independently copyrightable when it
held that plaintiffs had "failed to secure a federal copyright for it." _Richlin
v. Metro-Goldwyn-Mayer Pictures, Inc._, 531 F.3d at 976. Thus, the court
acknowledged that "publication of a motion picture with notice secures federal
statutory copyright protection for all of its component parts," but observed
"that does not mean that the component parts necessarily each secure an
independent federal statutory copyright." _Id._ at 975-76. The movie's
publication protected so much of the treatment as was disclosed therein, but it
"did not constitute publication of the Treatment 'as such'—i.e., as a work
standing alone." _Id._ at 973.

This reasoning undermines rather than supports plaintiffs' merger theory. The
plaintiffs in Richlin "clearly intended" that the treatment "be merged into
inseparable or interdependent parts of a unitary whole." _Id._ at 967. That is
not this case. As already explained, the Routine was created and performed by
Abbott and Costello well before _Tropics_ was filmed, and the team continued to
perform it for years after. Indeed, the Agreements' licensing of the Routine's
performance in _Tropics_ and _The Naughty Nineties_ contemplated such
independent performances. In these circumstances, we conclude that the Routine
did not merge into UPC's films so as to avoid the need for its creators to renew
the copyright. _See 16 Casa Duse, LLC v. Merkin_, 791 F.3d at 259.

In sum, because plaintiffs fail plausibly to allege that (1) Abbott and Costello
assigned their common law copyright in _Who's on First?_ to UPC; (2) the
Routine, as appropriated by defendants in _Hand to God_, was first created for
UPC as a work-for-hire; or (3) the Routine so merged with the UPC movies in
which it was performed as to become a unitary whole, we conclude that plaintiffs
did not plead their possession of a valid copyright in the Routine, as required
to pursue their infringement claim.

Accordingly, even though the district court erred in dismissing plaintiffs'
amended complaint based on defendants' fair use of the appropriated material, we
affirm dismissal based on plaintiffs' failure plausibly to allege a valid
copyright.

[***]

##### Discussion

1.  The Court concluded that plaintiffs had failed to plead ownership of a valid
    copyright to the *Who's On First* routine because the copyrights to the
    routine were never independently renewed. If the copyrights to the routine
    had been renewed before expiring, what would the result have been?

2.  How might the _TCA_ court evaluate minor contributions to an open source
    project? Is a patch to an open source project equivalent to an actor's
    performance in a movie? Is it easier, or more appropriate, to treat a patch
    as an independent work of authorship?

### _Effects Assocs. v. Cohen_, 908 F.2d 555 (9th Cir. 1990)

This next case we will examine is another dispute related to movie production.
Footage was prepared for inclusion in a horror movie by an independent
contractor. The producer who requested the footage was disastisfied, and paid
only half the promised amount for the work. The contractor sued the producer on
copyright grounds, alleging that the producer had incorporated the footage in
the horror film without a license.

This case addresses an issue that is critical to open source development: If a
contributor has submitted work to be included in a larger work, has the author
of the larger work received a license from the contributor to incorporate that
contribution?

#### Opinion

KOZINSKI, Circuit Judge.

What we have here is a failure to compensate. Larry Cohen, a low-budget horror
movie mogul, paid less than the agreed price for special effects footage he had
commissioned from Effects Associates. Cohen then used this footage without first
obtaining a written license or assignment of the copyright; Effects sued for
copyright infringement. We consider whether a transfer of copyright without a
written agreement, an arrangement apparently not uncommon in the motion picture
industry, conforms with the requirements of the Copyright Act.

Facts

This started out as a run-of-the-mill Hollywood squabble. Defendant Larry Cohen
wrote, directed and executive produced "The Stuff," a horror movie with a dash
of social satire: Earth is invaded by an alien life form that looks (and tastes)
like frozen yogurt but, alas, has some unfortunate side effects - it's addictive
and takes over the mind of anyone who eats it. Marketed by an unscrupulous
entrepreneur, the Stuff becomes a big hit. An industrial spy hired by ice cream
manufacturers eventually uncovers the terrible truth; he alerts the American
people and blows up the yogurt factory, making the world safe once again for
lovers of frozen confections.

In cooking up this gustatory melodrama, Cohen asked Effects Associates, a small
special effects company, to create footage to enhance certain action sequences
in the film. In a short letter dated October 29, 1984, Effects offered to
prepare seven shots,[^Eff1] the most dramatic of which would depict the
climactic explosion of the Stuff factory. Cohen agreed to the deal orally, but
no one said anything about who would own the copyright in the footage.

[^Eff1]: The price originally agreed to was $ 62,335; in an invoice dated
    January 10, 1985, Effects adjusted this amount upward to $ 64,033.92,
    because of additional expenses incurred in creating the shots.

Cohen was unhappy with the factory explosion Effects created, and he expressed
his dissatisfaction by paying Effects only half the promised amount for that
shot. Effects made several demands for the rest of the money (a little over $
8,000), but Cohen refused. Nevertheless, Cohen incorporated Effects's footage
into the film and turned it over to New World Entertainment for distribution.
Effects then brought this copyright infringement action, claiming that Cohen
(along with his production company and New World) had no right to use the
special effects footage unless he paid Effects the full contract price. Effects
also brought pendent state law claims for fraud and conspiracy to infringe
copyright.

The district court initially dismissed the suit, holding that it was primarily a
contract dispute and, as such, did not arise under federal law. In an opinion
remarkable for its lucidity, we reversed and remanded, concluding that plaintiff
was "master of his claim" and could opt to pursue the copyright infringement
action instead of suing on the contract. _Effects Assocs., Inc. v. Cohen_, 817
F.2d 72, 73 (9th Cir. 1987). We recognized that the issue on remand would be
whether Effects had transferred to Cohen the right to use the footage. _Id._ at
73 & n. 1, 74. On remand, the district court granted summary judgment to Cohen
on the infringement claim, holding that Effects had granted Cohen an implied
license to use the shots. Accordingly, the court dismissed the remaining state
law claims, allowing Effects to pursue them in state court. We review the
district court's grant of summary judgment de novo.

Discussion

A. Transfer of Copyright Ownership

The law couldn't be clearer: The copyright owner of "a motion picture or other
audiovisual work" has the exclusive rights to copy, distribute or display the
copyrighted work publicly. 17 U.S.C. § 106 (1988). While the copyright owner can
sell or license his rights to someone else, section 204 of the Copyright Act
invalidates a purported transfer of ownership unless it is in writing. 17 U.S.C.
§ 204(a) (1988).[^Eff2] Here, no one disputes that Effects is the copyright
owner of the special effects footage used in "The Stuff,"[^Eff3] and that
defendants copied, distributed and publicly displayed this footage without
written authorization.

[^Eff2]: The Copyright Act defines "transfer of copyright ownership" as an
    "assignment, mortgage, exclusive license, or any other conveyance,
    alienation, or hypothecation of a copyright or of any of the exclusive
    rights comprised in a copyright . . . but not including a nonexclusive
    license." 17 U.S.C. § 101.

[^Eff3]: Cohen concedes that he licensed Effects to prepare the footage as a
    derivative work incorporating other shots from "The Stuff," and that
    Effects has a valid copyright in this footage. Appellees' Brief at 25
    n. 3.

Cohen suggests that section 204's writing requirement does not apply to this
situation, advancing an argument that might be summarized, tongue in cheek, as:
Moviemakers do lunch, not contracts. Cohen concedes that "in the best of all
possible legal worlds" parties would obey the writing requirement, but contends
that moviemakers are too absorbed in developing "joint creative endeavors" to
"focus upon the legal niceties of copyright licenses." Appellees' Brief at 16,
18. Thus, Cohen suggests that we hold section 204's writing requirement
inapplicable here because "it is customary in the motion picture industry . . .
not to have written licenses." _Id._ at 18. To the extent that Cohen's argument
amounts to a plea to exempt moviemakers from the normal operation of section 204
by making implied transfers of copyrights "the rule, not the exception," _id._,
we reject his argument.

Common sense tells us that agreements should routinely be put in writing. This
simple practice prevents misunderstandings by spelling out the terms of a deal
in black and white, forces parties to clarify their thinking and consider
problems that could potentially arise, and encourages them to take their
promises seriously because it's harder to backtrack on a written contract than
on an oral one. Copyright law dovetails nicely with common sense by requiring
that a transfer of copyright ownership be in writing. Section 204 ensures that
the creator of a work will not give away his copyright inadvertently and forces
a party who wants to use the copyrighted work to negotiate with the creator to
determine precisely what rights are being transferred and at what price. _Cf.
Community for Creative Non-Violence v. Reid_, 490 U.S. 730, 109 S. Ct. 2166,
2177-78, 104 L. Ed. 2d 811 (1989) (describing purpose of writing requirement for
works made for hire). Most importantly, section 204 enhances predictability and
certainty of copyright ownership - "Congress' paramount goal" when it revised
the Act in 1976. _Community for Creative Non-Violence_, 109 S. Ct. at 2177; _see
also Dumas v. Gommerman_, 865 F.2d 1093, 1103-04 (9th Cir. 1989). Rather than
look to the courts every time they disagree as to whether a particular use of
the work violates their mutual understanding, parties need only look to the
writing that sets out their respective rights.

Section 204's writing requirement is not unduly burdensome; it necessitates
neither protracted negotiations nor substantial expense. The rule is really
quite simple: If the copyright holder agrees to transfer ownership to another
party, that party must get the copyright holder to sign a piece of paper saying
so. It doesn't have to be the Magna Charta; a one-line pro forma statement will
do.

Cohen's attempt to exempt moviemakers from the requirements of the Copyright Act
is largely precluded by recent Supreme Court and circuit authority construing
the work-for-hire doctrine.[^Eff4] Section 101 of the Act defines, in relevant
part, a work made for hire as "a work prepared by an employee within the scope
of his or her employment." 17 U.S.C. § 101 (1988). Section 201(b) provides that
the copyright in such a work is presumed to vest in the employer, not the
employee. 17 U.S.C. § 201(b) (1988). Prior to the Supreme Court's decision in
Community for Creative Non-Violence, some circuits had broadly construed section
101's use of the term employee, holding a work to have been prepared by an
employee whenever the hiring party controlled, or had the right to control, the
product. _See Community for Creative Non-Violence_, 109 S. Ct. at 2172. This
broad definition encompassed virtually all contributions to books and movies
because, as the Court recognized, such contributions are "usually prepared at
the instance, direction, and risk of a publisher or producer." _Id._ at 2173.
The Court rejected this rule as inconsistent with both the language and purpose
of the Copyright Act. _Id._ at 2172-74, 2177-78. It held instead that the term
employee was to be defined according to general agency principles, _id._ at
2173, 2178; where a non-employee contributes to a book or movie, as Effects did
here, the exclusive rights of copyright ownership vest in the creator of the
contribution, unless there is a written agreement to the contrary. _See id._ at
2173.

[^Eff4]: Because Effects is not an employee and there is no written agreement
    stating that plaintiff's footage is a work made for hire, Cohen can't
    take advantage of this doctrine. _See_ pp. 7709-10 infra. In any event,
    Cohen has waived this argument by failing to raise it below. _See
    S.O.S., Inc. v. Payday, Inc._, 886 F.2d 1081, 1087 (9th Cir. 1989).

This is similar to the conclusion we had reached several months earlier in
_Dumas v. Gommerman_. We had reasoned that, while many individuals may
contribute to the final product, the Act does no more than give publishers and
producers "statutory permission" to contract with the various contributors for
the rights of authorship. 865 F.2d at 1101 (quoting _Easter Seal Soc'y v.
Playboy Enters._, 815 F.2d 323, 329 (5th Cir. 1987), cert. denied 485 U.S. 981,
108 S. Ct. 1280, 99 L. Ed. 2d 491 (1988)(emphasis original)). Absent an express
transfer of ownership, a contributor who is not an employee retains ownership of
his copyright. _See id._

Thus, section 101 specifically addresses the movie and book publishing
industries, affording moviemakers a simple, straightforward way of obtaining
ownership of the copyright in a creative contribution -- namely, a written
agreement. The Supreme Court and this circuit, while recognizing the custom and
practice in the industry, have refused to permit moviemakers to sidestep section
204's writing requirement. Accordingly, we find unpersuasive Cohen's contention
that section 204's writing requirement, which singles out no particular group,
somehow doesn't apply to him. As section 204 makes no special allowances for the
movie industry, neither do we.

B. Nonexclusive Licenses

Although we reject any suggestion that moviemakers are immune to section 204, we
note that there is a narrow exception to the writing requirement that may apply
here. Section 204 provides that all transfers of copyright ownership must be in
writing; section 101 defines transfers of ownership broadly, but expressly
removes from the scope of section 204 a "nonexclusive license." _See_ note 2
supra. The sole issue that remains, then, is whether Cohen had a nonexclusive
license to use plaintiff's special effects footage.

The leading treatise on copyright law states that "[a] nonexclusive license may
be granted orally, or may even be implied from conduct." 3 M. Nimmer & D.
Nimmer, Nimmer on Copyright § 10.03[A], at 10-36 (1989). Cohen relies on the
latter proposition; he insists that, although Effects never gave him a written
or oral license, Effects's conduct created an implied license to use the footage
in "The Stuff."

Cohen relies largely on our decision in _Oddo v. Ries_, 743 F.2d 630 (9th Cir.
1984). There, we held that Oddo, the author of a series of articles on how to
restore Ford F-100 pickup trucks, had impliedly granted a limited non-exclusive
license to Ries, a publisher, to use plaintiff's articles in a book on the same
topic. We relied on the fact that Oddo and Ries had formed a partnership to
create and publish the book, with Oddo writing and Ries providing capital. _Id._
at 632 & n. 1. Oddo prepared a manuscript consisting partly of material taken
from his prior articles and submitted it to Ries. _Id._ at 632. Because the
manuscript incorporated pre-existing material, it was a derivative work; by
publishing it, Ries would have necessarily infringed the copyright in Oddo's
articles, unless Oddo had granted him a license. _Id._ at 634. We concluded
that, in preparing and handing over to Ries a manuscript intended for
publication that, if published, would infringe Oddo's copyright, Oddo "impliedly
gave the partnership a license to use the articles insofar as they were
incorporated in the manuscript, for without such a license, Oddo's contribution
to the partnership venture would have been of minimal value." _Id._[^Eff5]

[^Eff5]: Oddo did nevertheless prevail, but on other grounds. Ries was unhappy
    with Oddo's manuscript and hired another writer to do the job right.
    This writer added much new material, but also used large chunks of
    Oddo's manuscript, thereby incorporating portions of Oddo's
    pre-existing articles. 743 F.2d at 632. By publishing the other
    writer's book, Ries exceeded the scope of his implied license to use
    Oddo's articles and was liable for copyright infringement. _Id._ at
    634.

The district court agreed with Cohen, and we agree with the district court: Oddo
controls here. Like the plaintiff in Oddo, Effects created a work at defendant's
request and handed it over, intending that defendant copy and distribute
it.[^Eff6] To hold that Effects did not at the same time convey a license to use
the footage in "The Stuff" would mean that plaintiff's contribution to the film
was "of minimal value," a conclusion that can't be squared with the fact that
Cohen paid Effects almost $ 56,000 for this footage. Accordingly, we conclude
that Effects impliedly granted nonexclusive licenses to Cohen and his production
company to incorporate the special effects footage into "The Stuff" and to New
World Entertainment to distribute the film.[^Eff7]

[^Eff6]: As the district court found, "every objective fact concerning the
    transaction at issue supports a finding that an implied license
    existed." Order Granting Summary Judgment (Aug. 26, 1988) at 2.
    Effects's copyright registration certificate states that the footage is
    to be used in "The Stuff," so does the letter agreement of October 29,
    1984, and Effects's President James Danforth agreed at his deposition
    that this was his understanding. CR 24 at 11. Also, Effects delivered
    the film negatives to Cohen, never warning him that cutting the
    negatives into the film would constitute copyright infringement. CR 24
    at 29. While delivery of a copy "does not of itself convey any rights
    in the copyrighted work," 17 U.S.C. § 202 (1988) (emphasis added), it
    is one factor that may be relied upon in determining that an implied
    license has been granted.

[^Eff7]: Plaintiff argues that an implied license is an equitable remedy, akin
    to estoppel, for which Cohen does not qualify because he hasn't paid in
    full the agreed-to price for the footage. We reject this argument.
    Plaintiff cites no authority for the proposition that an implied
    license is equitable in nature; it seems to us to be a creature of law,
    much like any other implied-in-fact contract. _See, e.g., Landsberg v.
    Scrabble Crossword Game Players, Inc._, 802 F.2d 1193, 1199 (9th Cir.
    1986). In any event, it is unclear that a balancing of equities would
    favor plaintiff, who has been paid almost $ 56,000 for footage that is
    worthless to Cohen should plaintiff prevail. Nor can we construe
    payment in full as a condition precedent to implying a license.
    Conditions precedent are disfavored and will not be read into a
    contract unless required by plain, unambiguous language. _Sulmeyer v.
    United States (In re Bubble Up Delaware, Inc.)_, 684 F.2d 1259, 1264
    (9th Cir. 1982). The language of the October 29, 1984, agreement
    doesn't support a conclusion that full payment was a condition
    precedent to Cohen's use of the footage. Moreover, Effects's president
    conceded at his deposition that he never told Cohen that a failure to
    pay would be viewed as copyright infringement. CR 24 at 29.

Conclusion

We affirm the district court's grant of summary judgment in favor of Cohen and
the other defendants. We note, however, that plaintiff doesn't leave this court
empty-handed. Copyright ownership is comprised of a bundle of rights; in
granting a nonexclusive license to Cohen, Effects has given up only one stick
from that bundle -- the right to sue Cohen for copyright infringement. It
retains the right to sue him in state court on a variety of other grounds,
including breach of contract. Additionally, Effects may license, sell or give
away for nothing its remaining rights in the special effects footage. Those
rights may not be particularly valuable, of course: "The Stuff" was something
less than a blockbuster, and it remains to be seen whether there's a market for
shots featuring great gobs of alien yogurt oozing out of a defunct factory. On
the other hand, the shots may have much potential for use in music videos. _See
generally_ Kozinski & Banner, _Who's Afraid of Commercial Speech?_, 76 Va. L.
Rev. 627, 641 (1990). In any event, whatever Effects chooses to do with the
footage, Cohen will have no basis for complaining. And that's an important
lesson that licensees of more versatile film properties may want to take to
heart.

##### Discussion

1.  What actions of the contractor could have been sufficient to demonstrate
    that the scene was not licensed for inclusion in the movie? What actions
    could have ensured that scene would not be found to have been licensed for
    inclusion in the movie?

2.  What actions could the filmmaker have taken to prevent the issue of whether
    the scene had been licensed for inclusion in the movie from being a triable
    question of fact?

### _N.Y. Times Co. v. Tasini_, 533 U.S. 483 (2001)

Our next case concerns a dispute over permission to exploit components of a
collective work. The case concerned freelance contributors to the New York Times
and the limited authority the Times received to republish the contributors'
articles in new media. The dispute was escalated all the way to the Supreme
Court, and was resolved in favor of finding that the Times had not received any
permission to republish the contributors' works in digital archives.

#### Opinion

This copyright case concerns the rights of freelance authors and a presumptive
privilege of their publishers. The litigation was initiated by six freelance
authors and relates to articles they contributed to three print periodicals (two
newspapers and one magazine). Under agreements with the periodicals' publishers,
but without the freelancers' consent, two computer database companies placed
copies of the freelancers' articles -- along with all other articles from the
periodicals in which the freelancers' work appeared -- into three databases.
Whether written by a freelancer or staff member, each article is presented to,
and retrievable by, the user in isolation, clear of the context the original
print publication presented.

The freelance authors' complaint alleged that their copyrights had been
infringed by the inclusion of their articles in the databases. The publishers,
in response, relied on the privilege of reproduction and distribution accorded
them by § 201(c) of the Copyright Act, which provides:

"Copyright in each separate contribution to a collective work is distinct from
copyright in the collective work as a whole, and vests initially in the author
of the contribution. In the absence of an express transfer of the copyright or
of any rights under it, the owner of copyright in the collective work is
presumed to have acquired only the privilege of reproducing and distributing the
contribution as part of that particular collective work, any revision of that
collective work, and any later collective work in the same series." 17 U.S.C. §
201(c).

Specifically, the publishers maintained that, as copyright owners of collective
works, i.e., the original print publications, they had merely exercised "the
privilege" § 201(c) accords them to "reproduce and distribute" the author's
discretely copyrighted contribution.

In agreement with the Second Circuit, we hold that § 201(c) does not authorize
the copying at issue here. The publishers are not sheltered by § 201(c), we
conclude, because the databases reproduce and distribute articles standing alone
and not in context, not "as part of that particular collective work" to which
the author contributed, "as part of . . . any revision" thereof, or "as part of
. . . any later collective work in the same series." Both the print publishers
and the electronic publishers, we rule, have infringed the copyrights of the
freelance authors.

I

A

Respondents Jonathan Tasini, Mary Kay Blakely, Barbara Garson, Margot Mifflin,
Sonia Jaffe Robbins, and David S. Whitford are authors (Authors). Between 1990
and 1993, they wrote the 21 articles (Articles) on which this dispute centers.
Tasini, Mifflin, and Blakely contributed 12 Articles to The New York Times, the
daily newspaper published by petitioner The New York Times Company (Times).
Tasini, Garson, Robbins, and Whitford wrote eight Articles for Newsday, another
New York daily paper, published by petitioner Newsday, Inc. (Newsday). Whitford
also contributed one Article to Sports Illustrated, a weekly magazine published
by petitioner Time, Inc. (Time). The Authors registered copyrights in each of
the Articles. The Times, Newsday, and Time (Print Publishers) registered
collective work copyrights in each periodical edition in which an Article
originally appeared. The Print Publishers engaged the Authors as independent
contractors (freelancers) under contracts that in no instance secured consent
from an Author to placement of an Article in an electronic database.[^Tasini1]

[^Tasini1]: In the District Court, Newsday and Time contended that the
    freelancers who wrote for their publications had entered into
    agreements authorizing reproduction of the Articles in the
    databases. The Court of Appeals ruled that Newsday's defense was
    waived, and rejected Time's argument on the merits. Neither
    petitioner presses the contention here.

At the time the Articles were published, all three Print Publishers had
agreements with petitioner [1005] LEXIS/NEXIS (formerly Mead Data Central
Corp.), owner and operator of NEXIS, a computerized database that stores
information in a text-only format. NEXIS contains articles from hundreds of
journals (newspapers and periodicals) spanning many years. The Print Publishers
have licensed to LEXIS/NEXIS the text of articles appearing in the three
periodicals. The licenses authorize LEXIS/NEXIS to copy and sell any portion of
those texts.

Pursuant to the licensing agreements, the Print Publishers regularly provide
LEXIS/NEXIS with a batch of all the articles published in each periodical
edition. The Print Publisher codes each article to facilitate computerized
retrieval, then transmits it in a separate file. After further coding,
LEXIS/NEXIS places the article in the central discs of its database.

Subscribers to NEXIS, accessing the system through a computer, may search for
articles by author, subject, date, publication, headline, key term, words in
text, or other criteria. Responding to a search command, NEXIS scans the
database and informs the user of the number of articles meeting the user's
search criteria. The user then may view, print, or download each of the articles
yielded by the search. The display of each article includes the print
publication (e.g., The New York Times), date (September 23, 1990), section
(Magazine), initial page number (26), headline or title ("Remembering Jane"),
and author (Mary Kay Blakely). Each article appears as a separate, isolated
"story" -- without any visible link to the other stories originally published in
the same newspaper or magazine edition. NEXIS does not contain pictures or
advertisements, and it does not reproduce the original print publication's
formatting features such as headline size, page placement (e.g., above or below
the fold for newspapers), or location of continuation pages.

The Times (but not Newsday or Time) also has licensing agreements with
petitioner University Microfilms International (UMI). The agreements authorize
reproduction of Times materials on two CD-ROM products, the New York Times
OnDisc (NYTO) and General Periodicals OnDisc (GPO).

Like NEXIS, NYTO is a text-only system. Unlike NEXIS, NYTO, as its name
suggests, contains only the Times. Pursuant to a three-way agreement,
LEXIS/NEXIS provides UMI with computer files containing each article as
transmitted by the Times to LEXIS/NEXIS. Like LEXIS/NEXIS, UMI marks each
article with special codes. UMI also provides an index of all the articles in
NYTO. Articles appear in NYTO in essentially the same way they appear in NEXIS,
i.e., with identifying information (author, title, etc.), but without original
formatting or accompanying images.

GPO contains articles from approximately 200 publications or sections of
publications. Unlike NEXIS and NYTO, GPO is an image-based, rather than a
text-based, system. The Times has licensed GPO to provide a facsimile of the
Times' Sunday Book Review and Magazine. UMI "burns" images of each page of these
sections onto CD-ROMs. The CD-ROMs show each article exactly as it appeared on
printed pages, complete with photographs, captions, advertisements, and other
surrounding materials. UMI provides an index and abstracts of all the articles
in GPO.

Articles are accessed through NYTO and GPO much as they are accessed through
NEXIS. The user enters a search query using similar criteria (e.g., author,
headline, date). The computer program searches available indexes and abstracts,
and retrieves a list of results matching the query. The user then may view each
article within the search result, and may print the article or download it to a
disc. The display of each article provides no links to articles appearing on
other pages of the original print publications.[^Tasini2]

[^Tasini2]: For example, the GPO user who retrieves Blakely's "Remembering Jane"
    article will see the entirety of Magazine page 26, where the article
    begins, and Magazine page 78, where the article continues and ends.
    The NYTO user who retrieves Blakely's article will see only the text
    of the article and its identifying information (author, headline,
    publication, page number, etc.). Neither the GPO retrieval nor the
    NYTO retrieval produces any text on page 27, page 79, or any other
    page. The user who wishes to see other pages may not simply "flip"
    to them. She must conduct a new search.

B

On December 16, 1993, the Authors filed this civil action in the United States
District Court for the Southern District of New York. The Authors alleged that
their copyrights were infringed when, as permitted and facilitated by the Print
Publishers, LEXIS/NEXIS and UMI (Electronic Publishers) placed the Articles in
the NEXIS, NYTO, and GPO databases (Databases). The Authors sought declaratory
and injunctive relief, and damages. In response to the Authors' complaint, the
Print and Electronic Publishers raised the reproduction and distribution
privilege accorded collective work copyright owners by 17 U.S.C. § 201(c). After
discovery, both sides moved for summary judgment.

The District Court granted summary judgment for the Publishers, holding that §
201(c) shielded the Database reproductions. 972 F. Supp. 804, 806 (1997). The
privilege conferred by § 201(c) is transferable, the court first concluded, and
therefore could be conveyed from the original Print Publishers to the Electronic
Publishers. Id. at 816. Next, the court determined, the Databases reproduced and
distributed the Authors' works, in § 201(c)'s words, "as part of . . . [a]
revision of that collective work" to which the Authors had first contributed. To
qualify as "revisions," according to the court, works need only "preserve some
significant original aspect of [collective works] -- whether an original
selection or an original arrangement." Id. at 821. This criterion was met, in
the District Court's view, because the Databases preserved the Print
Publishers'"selection of articles" by copying all of the articles originally
assembled in the periodicals' daily or weekly issues. Id. at 823. The Databases
"highlighted" the connection between the articles and the print periodicals, the
court observed, by showing for each article not only the author and periodical,
but also the print publication's particular issue and page numbers. Id. at 824
("The electronic technologies not only copy the publisher defendants' complete
original 'selection' of articles, they tag those articles in such a way that the
publisher defendants' original selection remains evident online.").

The Authors appealed, and the Second Circuit reversed. 206 F.3d 161 (1999). The
Court of Appeals granted summary judgment for the Authors on the ground that the
Databases were not among the collective works covered by § 201(c), and
specifically, were not "revisions" of the periodicals in which the Articles
first appeared. Id. at 167-170. Just as § 201(c) does not "permit a Publisher to
sell a hard copy of an Author's article directly to the public even if the
Publisher also offered for individual sale all of the other articles from the
particular edition," the court reasoned, so § 201(c) does not allow a Publisher
to "achieve the same goal indirectly" through computer databases. Id. at 168. In
the Second Circuit's view, the Databases effectively achieved this result by
providing multitudes of "individually retrievable" articles. Ibid. As stated by
the Court of Appeals, the Databases might fairly be described as containing "new
anthologies of innumerable" editions or publications, but they do not qualify as
"revisions" of particular editions of periodicals in the Databases. Id. at 169.
Having concluded that § 201(c) "does not permit the Publishers," acting without
the author's consent, "to license individually copyrighted works for inclusion
in the electronic databases," the court did not reach the question whether the §
201(c) privilege is transferable. Id. at 165, and n. 2.

We granted certiorari to determine whether the copying of the Authors' Articles
in the Databases is privileged by 17 U.S.C. § 201(c). 531 U.S. 978 (2000).Like
the Court of Appeals, we conclude that the § 201(c) privilege does not override
the Authors' copyrights, for the Databases do not reproduce and distribute the
Articles as part of a collective work privileged by § 201(c). Accordingly, and
again like the Court of Appeals, we find it unnecessary to determine whether the
privilege is transferable.

II

Under the Copyright Act, as amended in 1976, "copyright protection subsists . .
. in original works of authorship fixed in any tangible medium of expression . .
. from which they can be perceived, reproduced, or otherwise communicated." 17
U.S.C. § 102(a). When, as in this case, a freelance author has contributed an
article to a "collective work" such as a newspaper or magazine, see § 101
(defining "collective work"), the statute recognizes two distinct copyrighted
works: "Copyright in each separate contribution to a collective work is distinct
from copyright in the collective work as a whole . . . ." § 201(c) (emphasis
added). Copyright in the separate contribution "vests initially in the author of
the contribution" (here, the freelancer). Ibid. Copyright in the collective work
vests in the collective author (here, the newspaper or magazine publisher) and
extends only to the creative material contributed by that author, not to "the
preexisting material employed in the work," § 103(b). _See also Feist
Publications, Inc. v. Rural Telephone Service Co._, 499 U.S. 340, 358, 113 L.
Ed. 2d 358, 111 S. Ct. 1282 (1991) (copyright in "compilation" -- a term that
includes "collective works," 17 U.S.C. § 101 -- is limited to the compiler's
original "selection, coordination, and arrangement").

Prior to the 1976 revision, as the courts below recognized, see 206 F.3d at 168;
972 F. Supp. at 815, authors risked losing their rights when they placed an
article in a collective work. Pre-1976 copyright law recognized a freelance
author's copyright in a published article only when the article was printed with
a copyright notice in the author's name. See Copyright Act of 1909, § 18, 35
Stat. 1079. When publishers, exercising their superior bargaining power over
authors, declined to print notices in each contributor's name, the author's
copyright was put in jeopardy. See A. Kaminstein, Divisibility of Copyrights,
Study No. 11, in Copyright Law Revision Studies Nos. 11-13, prepared for the
Senate Committee on the Judiciary, 86th Cong., 2d Sess., p. 18 (1960). The
author did not have the option to assign only the right of publication in the
periodical; such a partial assignment was blocked by the doctrine of copyright
"indivisibility." See id. at 11. Thus, when a copyright notice appeared only in
the publisher's name, the author's work would fall into the public domain,
unless the author's copyright, in its entirety, had passed to the publisher. See
id. at 18. Such complete transfer might be accomplished by a contract, perhaps
one with a provision, not easily enforced, for later retransfer of rights back
to the author. See id. at 20-22. Or, absent a specific contract, a court might
find that an author had tacitly transferred the entire copyright to a publisher,
in turn deemed to hold the copyright in "trust" for the author's benefit. See
id. at 18-19; see generally 3 M. Nimmer, Copyright § 10.01[C][2], pp. 10-12 to
10-14 (2000).

In the 1976 revision, Congress acted to "clarify and improve [this] confused and
frequently unfair legal situation with respect to rights in contributions." H.
R. Rep. No. 94-1476, p. 122 (1976) (hereinafter H. R. Rep.).[^Tasini3] The 1976
Act rejected the doctrine of indivisibility, recasting the copyright as a bundle
of discrete "exclusive rights," 17 U.S.C. § 106 (1994 ed. and Supp.
V),[^Tasini4] each of which "may be transferred . . . and owned separately," §
201(d)(2).[^Tasini5] Congress also provided, in § 404(a), that "a single notice
applicable to the collective work as a whole is sufficient" to protect the
rights of freelance contributors. And in § 201(c), Congress codified the
discrete domains of "copyright in each separate contribution to a collective
work" and "copyright in the collective work as a whole." Together, § 404(a) and
§ 201(c) "preserve the author's copyright in a contribution even if the
contribution does not bear a separate notice in the author's name, and without
requiring any unqualified transfer of rights to the owner of the collective
work." H. R. Rep. 122.

[^Tasini3]: Two Registers of Copyrights have observed that the 1976 revision of
    the Copyright Act represented "a break with the two-hundred-year-old
    tradition that has identified copyright more closely with the
    publisher than with the author." Letter from M. Peters to Rep.
    McGovern, reprinted in 147 Cong. Rec. E182 (Feb. 14, 2001)
    (hereinafter Peters Letter) (quoting Ringer, First Thoughts on the
    Copyright Act of 1976, 22 N. Y. L. S. L. Rev. 477, 490 (1977)). The
    intent to enhance the author's position vis-a-vis the patron is also
    evident in the 1976 Act's work-for-hire provisions. See _Community
    for Creative Non-Violence v. Reid_, 490 U.S. 730, 742-750, 104 L.
    Ed. 2d 811, 109 S. Ct. 2166 (1989); see also 17 U.S.C. § 203(a)(5)
    (inalienable authorial right to revoke a copyright transfer).
    Congress' adjustment of the author/publisher balance is a
    permissible expression of the "economic philosophy behind the
    [Copyright Clause]," i.e., "the conviction that encouragement of
    individual effort [motivated] by personal gain is the best way to
    advance public welfare." _Harper & Row, Publishers, Inc. v. Nation
    Enterprises_, 471 U.S. 539, 558, 85 L. Ed. 2d 588, 105 S. Ct. 2218
    (1985) (quoting _Mazer v. Stein_, 347 U.S. 201, 219, 98 L. Ed. 630,
    74 S. Ct. 460, 1954 Dec. Comm'r Pat. 308 (1954)).

[^Tasini4]: As amended, § 106 now provides: "Subject to sections 107 through
    121, the owner of copyright under this title has the exclusive
    rights to do and to authorize any of the following: "(1) to
    reproduce the copyrighted work in copies or phonorecords; "(2) to
    prepare derivative works based upon the copyrighted work; "(3) to
    distribute copies or phonorecords of the copyrighted work to the
    public by sale or other transfer of ownership, or by rental, lease,
    or lending; "(4) in the case of literary, musical, dramatic, and
    choreographic works, pantomimes, and motion pictures and other
    audiovisual works, to perform the copyrighted work publicly; "(5) in
    the case of literary, musical, dramatic, and choreographic works,
    pantomimes, and pictorial, graphic, or sculptural works, including
    the individual images of a motion picture or other audiovisual work,
    to display the copyrighted work publicly; and "(6) in the case of
    sound recordings, to perform the copyrighted work publicly by means
    of a digital audio transmission."

[^Tasini5]: It bears repetition here, see _supra_, at 7, that we neither decide
    nor express any view on whether the § 201(c) "privilege" may be
    transferred.

Section 201(c) both describes and circumscribes the "privilege" a publisher
acquires regarding an author's contribution to a collective work:

"In the absence of an express transfer of the copyright or of any rights under
it, the owner of copyright in the collective work is presumed to have acquired
only the privilege of reproducing and distributing the contribution as part of
that particular collective work, any revision of that collective work, and any
later collective work in the same series." (Emphasis added.)

A newspaper or magazine publisher is thus privileged to reproduce or distribute
an article contributed by a freelance author, absent a contract otherwise
providing, only "as part of" any (or all) of three categories of collective
works: (a) "that collective work" to which the author contributed her work, (b)
"any revision of that collective work," or (c) "any later collective work in the
same series." In accord with Congress' prescription, a "publishing company could
reprint a contribution from one issue in a later issue of its magazine, and
could reprint an article from a 1980 edition of an encyclopedia in a 1990
revision of it; the publisher could not revise the contribution itself or
include it in a new anthology or an entirely different magazine or other
collective work." H. R. Rep. 122-123.

Essentially, § 201(c) adjusts a publisher's copyright in its collective work to
accommodate a freelancer's copyright in her contribution. If there is demand for
a freelance article standing alone or in a new collection, the Copyright Act
allows the freelancer to benefit from that demand; after authorizing initial
publication, the freelancer may also sell the article to others. _Cf. Stewart v.
Abend_, 495 U.S. 207, 229, 109 L. Ed. 2d 184, 110 S. Ct. 1750 (1990) ("when an
author produces a work which later commands a higher price in the market than
the original bargain provided, the copyright statute [i.e., the separate renewal
term of former 17 U.S.C. § 24] is designed to provide the author the power to
negotiate for the realized value of the work"); id. at 230 (noting author's
"inalienable termination right" under current 17 U.S.C. §§ 203, 302). It would
scarcely "preserve the author's copyright in a contribution" as contemplated by
Congress, H. R. Rep. 122, if a newspaper or magazine publisher were permitted to
reproduce or distribute copies of the author's contribution in isolation or
within new collective works. See Gordon, _Fine-Tuning Tasini: Privileges of
Electronic Distribution and Reproduction_, 66 Brooklyn L. Rev. 473, 484 (2000).
[^Tasini6]

[^Tasini6]: The dissenting opinion suggests that a ruling for the Publishers
    today would maintain, even enhance, authors' "valuable copyright
    protection." Post, at 16-17 (opinion of STEVENS, J.). We are not so
    certain. When the reader of an article in a periodical wishes to
    obtain other works by the article's author, the Databases enable
    that reader simply to print out the author's articles, without
    buying a "new anthology . . . or other collective work," H. R. Rep.
    122-123. In years past, books compiling stories by journalists such
    as Janet Flanner and Ernie Pyle might have sold less well had the
    individual articles been freely and permanently available on line.
    In the present, print collections of reviews, commentaries, and
    reportage may prove less popular because of the Databases. The
    Register of Copyrights reports that "freelance authors have
    experienced significant economic loss" due to a "digital revolution
    that has given publishers [new] opportunities to exploit authors'
    works." Peters Letter E182. More to the point, even if the dissent
    is correct that some authors, in the long-run, are helped, not hurt,
    by Database reproductions, the fact remains that the Authors who
    brought the case now before us have asserted their rights under §
    201(c). We may not invoke our conception of their interests to
    diminish those rights.

III

In the instant case, the Authors wrote several Articles and gave the Print
Publishers permission to publish the Articles in certain newspapers and
magazines. It is undisputed that the Authors hold copyrights and, therefore,
exclusive rights in the Articles.[^Tasini7] It is clear, moreover, that the
Print and Electronic Publishers have exercised at least some rights that § 106
initially assigns exclusively to the Authors: LEXIS/NEXIS' central discs and
UMI's CD-ROMs "reproduce . . . copies" of the Articles, § 106(1); UMI, by
selling those CD-ROMs, and LEXIS/NEXIS, by selling copies of the Articles
through the NEXIS Database, "distribute copies" of the Articles "to the public
by sale," § 106(3); and the Print Publishers, through contracts licensing the
production of copies in the Databases, "authorize" reproduction and distribution
of the Articles, § 106.[^Tasini8]

[^Tasini7]: The Publishers do not claim that the Articles are "works made for
    hire." 17 U.S.C. § 201(b). As to such works, the employer or person
    for whom a work was prepared is treated as the author. Ibid. The
    Print Publishers, however, neither engaged the Authors to write the
    Articles as "employees" nor "commissioned" the Articles through "a
    written instrument signed by [both parties]" indicating that the
    Articles shall be considered "works made for hire." § 101 (1994 ed.,
    Supp. V) (defining "work made for hire").

[^Tasini8]: Satisfied that the Publishers exercised rights § 106 initially
    assigns exclusively to the Author, we need resolve no more on that
    score. Thus, we do not reach an issue the Register of Copyrights has
    argued vigorously. The Register maintains that the Databases
    publicly "display" the Articles, § 106(5); because § 201(c) does not
    privilege "display," the Register urges, the § 201(c) privilege does
    not shield the Databases. See Peters Letter E182-E183.

Against the Authors' charge of infringement, the Publishers do not here contend
the Authors entered into an agreement authorizing reproduction of the Articles
in the Databases. See supra, at 3, n. 1. Nor do they assert that the copies in
the Databases represent "fair use" of the Authors' Articles. See 17 U.S.C. § 107
("fair use of a copyrighted work . . . is not an infringement"; four factors
identified among those relevant to fair use determination). Instead, the
Publishers rest entirely on the privilege described in § 201(c). Each discrete
edition of the periodicals in which the Articles appeared is a "collective
work," the Publishers agree. They contend, however, that reproduction and
distribution of each Article by the Databases lie within the "privilege of
reproducing and distributing the [Articles] as part of . . . [a] revision of
that collective work," § 201(c). The Publishers' encompassing construction of
the § 201(c) privilege is unacceptable, we conclude, for it would diminish the
Authors' exclusive rights in the Articles. In determining whether the Articles
have been reproduced and distributed "as part of" a "revision" of the collective
works in issue, we focus on the Articles as presented to, and perceptible by,
the user of the Databases. HN10 See § 102 (copyright protection subsists in
original works fixed in any medium "from which they can be perceived,
reproduced, or otherwise communicated"); see also § 101 (definitions of "copies"
and "fixed"); Haemmerli, Commentary: _Tasini v. New York Times Co._, 22
Colum.-VLA. J. L. & Arts 129, 142-143 (1998). In this case, the three Databases
present articles to users clear of the context provided either by the original
periodical editions or by any revision of those editions. The Databases first
prompt users to search the universe of their contents: thousands or millions of
files containing individual articles from thousands of collective works (i.e.,
editions), either in one series (the Times, in NYTO) or in scores of series (the
sundry titles in NEXIS and GPO). When the user conducts a search, each article
appears as a separate item within the search result. In NEXIS and NYTO, an
article appears to a user without the graphics, formatting, or other articles
with which the article was initially published. In GPO, the article appears with
the other materials published on the same page or pages, but without any
material published on other pages of the original periodical. In either
circumstance, we cannot see how the Database perceptibly reproduces and
distributes the article "as part of " either the original edition or a
"revision" of that edition.

One might view the articles as parts of a new compendium -- namely, the entirety
of works in the Database. In that compendium, each edition of each periodical
represents only a miniscule fraction of the ever-expanding Database. The
Database no more constitutes a "revision" of each constituent edition than a
400-page novel quoting a sonnet in passing would represent a "revision" of that
poem. HN11 "Revision" denotes a new "version," and a version is, in this
setting, a "distinct form of something regarded by its creators or others as one
work." Webster's Third New International Dictionary 1944, 2545 (1976). The
massive whole of the Database is not recognizable as a new version of its every
small part.

Alternatively, one could view the Articles in the Databases "as part of" no
larger work at all, but simply as individual articles presented individually.
That each article bears marks of its origin in a particular periodical (less
vivid marks in NEXIS and NYTO, more vivid marks in GPO) suggests the article was
previously part of that periodical. But the markings do not mean the article is
_currently_ reproduced or distributed as part of the periodical. The Databases'
reproduction and distribution of individual Articles -- simply as _individual
Articles_ -- would invade the core of the Authors' exclusive rights under §
106.[^Tasini9]

[^Tasini9]: The dissenting opinion takes as its starting point "what is sent
    from the New York Times to the Electronic Databases." See post, at
    6-11. This case, however, is not ultimately about what is sent
    between Publishers in an intermediate step of Database production;
    it is about what is presented to the general public in the
    Databases. See supra, at 14. Those Databases simply cannot bear
    characterization as a "revision" of any one periodical edition. We
    would reach the same conclusion if the Times sent intact newspapers
    to the Electronic Publishers.

The Publishers press an analogy between the Databases, on the one hand, and
microfilm and microfiche, on the other. We find the analogy wanting. Microforms
typically contain continuous photographic reproductions of a periodical in the
medium of miniaturized film. Accordingly, articles appear on the microforms,
writ very small, in precisely the position in which the articles appeared in the
newspaper. The Times, for example, printed the beginning of Blakely's
"Remembering Jane" Article on page 26 of the Magazine in the September 23, 1990,
edition; the microfilm version of the Times reproduces that same Article on film
in the very same position, within a film reproduction of the entire Magazine, in
turn within a reproduction of the entire September 23, 1990, edition. True, the
microfilm roll contains multiple editions, and the microfilm user can adjust the
machine lens to focus only on the Article, to the exclusion of surrounding
material. Nonetheless, the user first encounters the Article in context. In the
Databases, by contrast, the Articles appear disconnected from their original
context. In NEXIS and NYTO, the user sees the "Jane" Article apart even from the
remainder of page 26. In GPO, the user sees the Article within the context of
page 26, but clear of the context of page 25 or page 27, the rest of the
Magazine, or the remainder of the day's newspaper. In short, unlike microforms,
the Databases do not perceptibly reproduce articles as part of the collective
work to which the author contributed or as part of any "revision"
thereof.[^Tasini10]

[^Tasini10]: The Court of Appeals concluded NEXIS was infringing partly because
    that Database did "almost nothing to preserve the copyrightable
    aspects of the [Print] Publishers' collective works," i.e., their
    original "selection, coordination, and arrangement." 206 F.3d 161,
    168 (CA2 1999). We do not pass on this issue. It suffices to hold
    that the Databases do not contain "revisions" of the Print
    Publishers' works "as part of" which the Articles are reproduced
    and distributed.

Invoking the concept of "media neutrality," the Publishers urge that the
"transfer of a work between media" does not "alter the character of" that work
for copyright purposes. Brief for Petitioners 23. That is indeed true. See 17
U.S.C. § 102(a) (copyright protection subsists in original works "fixed in any
tangible medium of expression"). But unlike the conversion of newsprint to
microfilm, the transfer of articles to the Databases does not represent a mere
conversion of intact periodicals (or revisions of periodicals) from one medium
to another. The Databases offer users individual articles, not intact
periodicals. In this case, media neutrality should protect the Authors' rights
in the individual Articles to the extent those Articles are now presented
individually, outside the collective work context, within the Databases' new
media.[^Tasini11]

[^Tasini11]: The dissenting opinion apparently concludes that, under the banner
    of "media-neutrality," a copy of a collective work, even when
    considerably changed, must constitute a "revision" of that
    collective work so long as the changes were "necessitated by . . .
    the medium." Post, at 9. We lack the dissent's confidence that the
    current form of the Databases is entirely attributable to the
    nature of the electronic media, rather than the nature of the
    economic market served by the Databases. In any case, we see no
    grounding in § 201(c) for a "medium-driven" necessity defense,
    post, at 9, n. 11, to the Authors' infringement claims.
    Furthermore, it bears reminder here and throughout that these
    Publishers and all others can protect their interests by private
    contractual arrangement.

For the purpose at hand -- determining whether the Authors' copyrights have been
infringed -- an analogy to an imaginary library may be instructive.[^Tasini12]
Rather than maintaining intact editions of periodicals, the library would
contain separate copies of each article. Perhaps these copies would exactly
reproduce the periodical pages from which the articles derive (if the model is
GPO); perhaps the copies would contain only typescript characters, but still
indicate the original periodical's name and date, as well as the article's
headline and page number (if the model is NEXIS or NYTO). The library would
store the folders containing the articles in a file room, indexed based on
diverse criteria, and containing articles from vast numbers of editions. In
response to patron requests, an inhumanly speedy librarian would search the room
and provide copies of the articles matching patron-specified criteria.

[^Tasini12]: The Publishers have frequently referred to their products as
    "electronic libraries." We need not decide whether the Databases
    come within the legal coverage of the term "libraries" as used in
    the Copyright Act. For even if the Databases are "libraries," the
    Copyright Act's special authorizations for libraries do not cover
    the Databases' reproductions. See, e.g., 17 U.S.C. § 108(a)(1)
    (reproduction authorized "without any purpose of direct or indirect
    commercial advantage"); § 108(b)(reproduction authorized "solely
    for purposes of preservation and security or for deposit for
    research use"); § 108(c) (1994 ed., Supp. V) (reproduction "solely
    for the purpose of replacement of a copy or phonorecord that is
    damaged, deteriorating, lost, or stolen, or if the existing format
    in which the work is stored has become obsolete").

Viewing this strange library, one could not, consistent with ordinary English
usage, characterize the articles "as part of" a "revision" of the editions in
which the articles first appeared. In substance, however, the Databases differ
from the file room only to the extent they aggregate articles in electronic
packages (the LEXIS/NEXIS central discs or UMI CD-ROMs), while the file room
stores articles in spatially separate files. The crucial fact is that the
Databases, like the hypothetical library, store and retrieve articles separately
within a vast domain of diverse texts. Such a storage and retrieval system
effectively overrides the Authors' exclusive right to control the individual
reproduction and distribution of each Article, 17 U.S.C. §§ 106(1), (3). _Cf.
Ryan v. Carl Corp._, 23 F. Supp. 2d 1146 (ND Cal. 1998) (holding copy shop in
violation of § 201(c)).

The Publishers claim the protection of § 201(c) because users can manipulate the
Databases to generate search results consisting entirely of articles from a
particular periodical edition. By this logic, § 201(c) would cover the
hypothetical library if, in response to a request, that library's expert staff
assembled all of the articles from a particular periodical edition. However,
HN12 the fact that a third party can manipulate a database to produce a
noninfringing document does not mean the database is not infringing. Under §
201(c), the question is not whether a user can generate a revision of a
collective work from a database, but whether the database itself perceptibly
presents the author's contribution as part of a revision of the collective work.
That result is not accomplished by these Databases.

The Publishers finally invoke _Sony Corp. of America v. Universal City Studios,
Inc._, 464 U.S. 417, 78 L. Ed. 2d 574, 104 S. Ct. 774 (1984). That decision,
however, does not genuinely aid their argument. Sony held that the "sale of
copying equipment" does not constitute contributory infringement if the
equipment is "capable of substantial noninfringing uses." Id. at 442. The
Publishers suggest that their Databases could be liable only under a theory of
contributory infringement, based on end-user conduct, which the Authors did not
plead. The Electronic Publishers, however, are not merely selling "equipment";
they are selling copies of the Articles. And, as we have explained, it is the
copies themselves, without any manipulation by users, that fall outside the
scope of the § 201(c) privilege.

IV

The Publishers warn that a ruling for the Authors will have "devastating"
consequences. Brief for Petitioners 49. The Databases, the Publishers note,
provide easy access to complete newspaper texts going back decades. A ruling for
the Authors, the Publishers suggest, will punch gaping holes in the electronic
record of history. The Publishers' concerns are echoed by several historians,
see Brief for Ken Burns et al. as Amici Curiae, but discounted by several other
historians, see Brief for Ellen Schrecker et al. as Amici Curiae; Brief for
Authors' Guild, Jacques Barzun et al. as Amici Curiae.

Notwithstanding the dire predictions from some quarters, see also post, at 16
(STEVENS, J., dissenting), it hardly follows from today's decision that an
injunction against the inclusion of these Articles in the Databases (much less
all freelance articles in any databases) must issue. See 17 U.S.C. § 502(a)
(court "may" enjoin infringement); _Campbell v. Acuff-Rose Music, Inc._, 510
U.S. 569, 578, n. 10, 127 L. Ed. 2d 500, 114 S. Ct. 1164 (1994) (goals of
copyright law are "not always best served by automatically granting injunctive
relief"). The parties (Authors and Publishers) may enter into an agreement
allowing continued electronic reproduction of the Authors' works; they, and if
necessary the courts and Congress, may draw on numerous models for distributing
copyrighted works and remunerating authors for their distribution. See, e.g., 17
U.S.C. § 118(b); _Broadcast Music, Inc. v. Columbia Broadcasting System, Inc._,
441 U.S. 1, 4-6, 10-12, 60 L. Ed. 2d 1, 99 S. Ct. 1551 (1979) (recounting
history of blanket music licensing regimes and consent decrees governing their
operation).[^Tasini13] In any event, speculation about future harms is no basis
for this Court to shrink authorial rights Congress established in § 201(c).
Agreeing with the Court of Appeals that the Publishers are liable for
infringement, we leave remedial issues open for initial airing and decision in
the District Court.

[^Tasini13]: Courts in other nations, applying their domestic copyright laws,
    have also concluded that Internet or CD-ROM reproduction and
    distribution of freelancers' works violate the copyrights of
    freelancers. See, e.g., _Union Syndicale des Journalistes Franais
    v. SDV Plurimdia_ (T.G.I., Strasbourg, Fr., Feb. 3, 1998), in
    Lodging of International Federation of Journalists (IFJ) as _Amicus
    Curiae_; _S. C. R. L. Central Station v. Association Generale des
    Journalistes Professionnels de Belgique_ (CA, Brussels, Belg., 9e
    ch., Oct. 28, 1997), transl. and ed. in 22 Colum.-VLA J. L. & Arts
    195 (1998); _Heg v. De Volskrant B. V._ (Dist. Ct., Amsterdam,
    Neth., Sept. 24, 1997), transl. and ed. in 22 Colum.-VLA J. L. &
    Arts, at 181. After the French Plurimdia decision, the journalists'
    union and the newspaper-defendant entered into an agreement
    compensating authors for the continued electronic reproduction of
    their works. See _FR3 v. Syndicats de Journalistes_ (CA, Colmar,
    Sept. 15, 1998), in Lodging of IFJ as _Amicus Curiae_. In Norway,
    it has been reported, a similar agreement was reached. See Brief
    for IFJ as _Amicus Curiae_ 18.

********************************************************************************

We conclude that the Electronic Publishers infringed the Authors' copyrights by
reproducing and distributing the Articles in a manner not authorized by the
Authors and not privileged by § 201(c). We further conclude that the Print
Publishers infringed the Authors' copyrights by authorizing the Electronic
Publishers to place the Articles in the Databases and by aiding the Electronic
Publishers in that endeavor. We therefore affirm the judgment of the Court of
Appeals.

It is so ordered.

[Dissent by Justice Stevens, joined by Justive Breyer omitted]

#### Discussion

1.  In Justice Stevens' omitted dissent, Stevens declares that "[n]o one doubts
    that the New York Times has the right to reprint its issues in Braille, in a
    foreign language, or in microform, even though such revisions might look and
    feel quite different from the original." Is Justice Stevens' statement of
    the law correct? Note the § 101 definition of "derivative work."

2.  In discussing "media neutrality," the Court explains, "the Publishers urge
    that the 'transfer of a work between media' does not 'alter the character
    of' that work for copyright purposes. That is indeed true. See 17 U.S.C. §
    102(a) (copyright protection subsists in original works "fixed in any
    tangible medium of expression"). But unlike the conversion of newsprint to
    microfilm, the transfer of articles to the Databases does not represent a
    mere conversion of intact periodicals (or revisions of periodicals) from one
    medium to another." Is the Court's characterization of media neutrality
    correct? Is the majority's distinction between the conversion of newsprint
    to microfilm and the conversion of newsprint to ASCII salient? What is the
    Court holding to be permissible with respect to the "mere conversion of
    intact [works] from one medium to another"?

3.  Is it appropriate to think of an open source project as a collective work?
    As the maintainer of an open source project that receives contributions,
    what is the cost/benefit analysis for treating the project as an individual
    work as opposed to a collective work?

## Section 3 - Writings: The Role of Contributor License Agreements, Developer Certificates of Origin, and Other Writings in Governing Copyright Ownership of Contributions to Open Source Projects

There are two, often interrelated, questions that have arisen throughout this
chapter: When someone has contributed to a work, have they become a joint
author? And, have they actually licensed their contribution to the larger work?
As critical and academically-complex as these questions are in world of open
source development, both questions are frequently resolved through common
conventions of open source development.

The first convention to note is the technical nature of “pull request”
contributions to open source projects. When a GitHub member contributes a patch
to someone else’s project on GitHub, they generally do so in the form of a pull
request. The pull request entails copying the entire project and republishing
it, together with the contributor’s modifications, as a new version. Therefore,
as part of submitting that patch, the user has formally applied whatever license
documentation had been included in the project to the contents of the patch.

This does leave two holes that are important to note. If a contributor
contributes code not by way of pull request, but say, by email, it becomes much
less clear that inbound/outbound contribution licensing applies. A court might
conclude from the context of the email, and from the industry practice of
inbound/outbound, that the email contributor has licensed the work to the
project, but it would be highly fact-dependent. The second hole enters if the
project does not have a license at the time the contribution is received. With
no license or contributing documentation in operation, it is left entirely to
the facts of the contribution to determine whether a joint, collective, and/or
derivative work has been created, to what part of the project the contributor
owns, and what, if any, license the project creator or public has received to
the contributed work.

The second convention is the role of writings such as Contributor License
Agreements, Developer Certificates of Origin, and contributing instructions in
further clarifying that a project receives a license to the contents of
third-party contributions. Some of these documents provide a clear statement as
to the type of intellectual property being created and who owns what:

> “You (or your employer) retain the copyright to your contribution; this simply
> gives us permission to use and redistribute your contributions as part of the
> project.”[^Goog]

[^Goog]: Contributing instructions for _snappy_ (retrieved from
    https://github.com/google/snappy/blob/master/CONTRIBUTING.md on
    8/20/18).

By specifically clarifying that the contribution is regarded as a copyrighted
work, with copyrights held by the contributor, and a license attaching to the
contribution that permits the contribution to be incorporated into the larger
work, this (in theory) effectively forces a court to treat the project as a
collective work, with all contributions to the work constituting individually
owned but affirmatively licensed components. This writing goes very far to
suggest that the contributor is not being treated as a coauthor.

Conversely, the language of the Linux Foundation’s Developer Certificate of
Origin, while including an express license of the contribution to the project,
does not have terms identifying the contribution as a work that is copyrighted
to the author and licensed to the project. This (in theory) leaves the
determination that the contributor has become a co-author a greater possibility.

While many of the conventions and practical writings that comprise open source
development operate to resolve ambiguities around authorship and licensing
status, there is one convention within open source that leaves for difficult
open questions; the AUTHORS file. Many open source projects include an AUTHORS
file, but the was this file is used varies between projects, and is sometimes
ambiguous. Some projects maintain both a list of CONTRIBUTORS and AUTHORS which
ostensibly (or expressly) separates the list of humans that have contributed to
the project from humans and/or entities that hold copyright rights to portions
of the project. However, AUTHORS files rarely, if ever, expressly state that the
enumerated authors are the individual copyright holders to separate and
distinguishable parts of the project, rather than co-authors of the whole. The
grouped designation of “authors” for the “project” strongly lends to an
interpretation that the named authors are indeed “co-authors.”

### _Corwin v. Quinonez_, 858 F. Supp. 2d 903 (N.D. Ohio 2012)

Our final case concerns a copyright dispute between former bandmates. Plaintiff
Michael Corwin alleged that he was a co-author of the band's songs and sought an
accounting of the profits defendant Wesley Quinonez had earned from the songs.

Here we see the District Court for the Northern District of Ohio endorse the
_Childress_ standard over the _Aalmuhammed_ standard, finding Quinonez's lack of
intent to treat Corwin as a co-author to be dispositive.

#### Opinion

MEMORANDUM OPINION KATZ, J.

Plaintiff Michael Corwin brings this action for a declaratory judgment and
accounting of profits against Defendant Wesley Quinonez. Plaintiff seeks a
declaratory judgment that he and Defendant are joint owners of thirty-one songs
created during their membership in the band "Rediscover." Further, Plaintiff
contends that as joint authors, he and Defendant are co-owners of the copyrights
for the songs at issue, and that he is therefore entitled to an accounting of
any profits Defendant has derived therefrom. Defendant counterclaimed for a
declaration that he is the sole author and sole owner of the songs in question,
and further counterclaimed for an accounting of any profits Plaintiff derived
from the songs.

The matter is currently before the Court on Defendant's motion for summary
judgment as to the parties' competing requests for a declaration of authorship.
(Doc. 30). For the reasons stated herein, Defendant's motion is granted and
Plaintiff's complaint is dismissed.[^Cor1]

[^Cor1]: Because Defendant's motion "expressly reserves any argument as to
    damages," _id._ at 1, Count II (Accounting) and Count III (Constructive
    Trust) of Defendant's third amended counterclaim remain pending.

I. Background

Defendant is the founder and original member of Rediscover. Defendant styles
Rediscover's music as "electro-pop;" i.e., pop music that is predominately
created electronically, but that may also include vocal and instrumental
components. Prior to Plaintiff's membership, Defendant, as the sole member of
Rediscover, had "written, produced, performed," and was selling a compact disc
("CD") album titled "The Ocean is Calling Us." (Plaintiff's Deposition, Doc. 46
at 21:10-22:11) (hereinafter, "Pl's. Dep."). Plaintiff joined Rediscover in
January 2005 and remained a member through June 2008. In addition to Plaintiff
and Defendant, Rediscover included band members Robert Wagner and Daaren Davis.

During Plaintiff's membership, Rediscover went on tour, had a short-lived
relationship with a record label (Unborn Media Records, d/b/a One Big Spark,
(hereinafter, "One Big Spark," or "the record label")), and recorded three
albums: "Out of Touch,"[^Cor2] "Call Me When You Get This,"[^Cor3] and
"Sleepless Nights."[^Cor4] Additionally, a fourth album, "Lost Songs,"[^Cor5]
was produced sometime after Plaintiff's membership ended. Combined, these four
albums include the thirty-one songs currently in dispute, as reflected by a
stipulation the parties filed with the Court. (Doc. 51).

[^Cor2]: The "Out of Touch" album contains the following four songs, all of
    which are in dispute: "Dance Transylvania," "I Consume You," "This
    Place," "Your Pretty Eyes." (Doc. 51).

[^Cor3]: The "Call Me When You Get This" album contains the following seven
    songs, all of which are in dispute: "Baby Got Her Gun Out," "Shake It,"
    "Do You Think?," "My Pretty Eyes," "Standing On Edge," "I Consume You -
    alt. version." (Doc. 51).

[^Cor4]: The "Sleepless Nights" album contains the following nine songs, all of
    which are in dispute: "Sleepless Nights," "Standing On Edge - alt.
    version," "Say It Like You Mean It," "Drink The Night Away,"
    "Gorgeous," "I'm Just Like The Other Guys," "Not Invited," "Face Down,"
    "I Will Forget You." (Doc. 51).

[^Cor5]: The "Lost Songs" album contains the following eleven songs, all of
    which are [**4] in dispute: "Belmont," "Ecstacy," "Every Fucking
    Movie," "Hang On," "Hideout," "I'm In Love With You," "One Eighty,"
    "Shake," "Stuck in 1999," "Voodoo," "You Won't Be Breathing." (Doc.
    51).

The first two albums, "Out of Touch" and "Call Me When You Get This," were both
recorded in Defendant's basement studio using recording equipment and computer
software provided by Defendant. "Out of Touch" was finished sometime in 2005,
and "Call Me When You Get This" was finished sometime in 2006. The parties
disagree about the extent of Plaintiff's input and control over the writing and
recording process, but with the exception of three songs—"Dance Transylvania,"
"I Consume You," and "Baby Got Her Gun Out"—Plaintiff agrees that Defendant
independently programed and recorded each basic electronic song using music
production software called FL Studio. Once the basic song was created, Plaintiff
and Defendant collaborated on how Plaintiff could perform live instrumental
components on top of the basic track. For "Dance Transylvania," "I Consume You,"
and "Baby Got Her Gun Out," Plaintiff apparently contends that he brought the
original idea for these songs to Defendant,[^Cor6] but concedes that he had no
working knowledge of FL Studio during the production of the first album, and
only limited knowledge during production of the second.

[^Cor6]: Plaintiff does not make any specific arguments as to "Dance
    Transylvania," "I Consume You," or "Baby Got Her Gun Out." The Court
    was apprized of Plaintiff's apparent claims about the three songs only
    through _Defendant_'s reference to portions of Plaintiff's deposition.
    Nowhere does Plaintiff's brief assert that Plaintiff made contributions
    to "Dance Transylvania," "I Consume You," or "Baby Got Her Gun Out"
    that were more substantial than the contributions he made to any of the
    other songs at issue. Instead, Plaintiff's brief only contains sweeping
    assertions about all thirty-one disputed songs. Similarly, Plaintiff's
    affidavit—which purports to enumerate the contributions Plaintiff made
    to each of the disputed songs—only lists contributions for eighteen
    songs, and does not even mention "Dance Transylvania," "I Consume You,"
    or "Baby Got Her Gun Out." (Doc. 47-2 at ¶5).

Sometime prior to production of the third album, "Sleepless Nights," Rediscover
became affiliated with the record label One Big Spark. "Sleepless Nights" was
subsequently recorded with the assistance of the label.[^Cor7] In addition to
pre-production work in Baltimore, Defendant again independently programed and
recorded each of the basic electronic songs for "Sleepless Nights" using FL
Studio. Plaintiff, Defendant, and band members Robert Wagner and Daaron Davis
then traveled to Florida to finish recording the album alongside record producer
Pete Thornton. As with the previous two albums, the four band members
collaborated on how to add instrumental and vocal components to the already
existing tracks. Moreover, Plaintiff and Defendant worked with Thornton on
technical production aspects throughout recording.

[^Cor7]: Specific details regarding the nature of Rediscover's "affiliation"
    with One Big Spark remain unclear.

At some point after the Florida recording sessions it was determined that
portions of the album were unsatisfactory. It is unclear from the briefs who
made this determination but, in any event, Defendant traveled to Boston to
re-master the album with producers from One Big Spark. While there, Defendant
re-wrote portions of songs and altered or omitted portions of the other band
members' contributions, including Plaintiff's. Neither Plaintiff nor the other
two band members traveled to Boston or otherwise participated in the
re-mastering process, though they were aware of Defendant's activities.

At some point after the re-mastering process, Rediscover's affiliation with One
Big Spark "fell apart" in 2008. Despite this, One Big Spark agreed to give the
final master recordings to Rediscover for the band's use.

The recording process for, and Plaintiff's involvement in, the final album,
"Lost Songs," is unclear, as the parties' briefs do not mention the album by
name. What is clear is that Plaintiff's membership in Rediscover ended in
mid-2008, apparently before "Lost Songs" was recorded. Even so, the parties'
stipulation lists the "Lost Songs" album and each of its eleven songs as
disputed. (Doc. 51). Moreover, Plaintiff's affidavit enumerates contributions he
made to ten of the album's eleven songs.

In addition to the parties' above-described involvement in the recording
process, it should be noted that several songs were registered with Broadcast
Music, Inc. ("BMI"), a performance rights society that manages licensing
negotiations for the music of member composers. Specifically, composers can
register songs with BMI, and BMI then "negotiates blanket licenses which grant
the operator of a bar, radio station, etc., the right to play any of the
thousands of songs in [BMI's] stable for a fixed fee. BMI distributes 80 percent
of the money received for such licenses back to the composers based on the
popularity of their songs." _Broadcast Music, Inc. v. Star Amusements_, 44 F.3d
485, 486 (7th Cir. 1995). In this case, "Baby Got Her Gun Out," "Shake It," "Do
You Think," and "Kiss Me" were registered with BMI in four equal shares—one
share for each of Rediscover's four members—so that each band member would
receive an equal portion of the royalties. It is unclear who registered these
four songs, but Plaintiff stated at deposition that band member Robert Wagner
was the first to begin BMI registrations, and that Defendant also registered
songs.[^Cor8] (Pl's. Dep. at 140:18-141:1).

[^Cor8]: Defendant's Counterclaim for an accounting and constructive trust of
    Plaintiff's profits alleges that Plaintiff registered "Dance
    Transylvania" and "I Consume You" with BMI. Further, the Counterclaim
    alleges that Plaintiff claimed the full 200% interest in the royalties
    for both songs (100% writer's share and 100% publisher's share). (Doc.
    26 at 5-10). The motion _sub judice_, however, only requests a
    declaration of ownership as to the thirty-one disputed songs. As
    explained _infra_, Plaintiff's alleged registration is not relevant to
    this inquiry.

Finally, on December 13, 2010—after Plaintiff filed this lawsuit— Defendant
secured four copyright registrations, one for each of the four albums at issue.
[^Cor9] (Doc. 31-1 at 1-12).All four registrations denote "Wesley James
Quinonez, dba Rediscover" as the author and copyright claimant, and state that
Quinonez dba Rediscover created the "sound recording, music, [and] lyrics" for
all four albums. _Id._

[^Cor9]: The Court notes a slight discrepancy between the album titles listed in
    the parties' stipulation, and the "Title of Work" information listed in
    Defendant's copyright registrations. Specifically, whereas the parties'
    stipulation lists the title of Rediscover's 2006 album as "Call Me When
    You Get This," copyright registration SR 669-420 lists the "Title of
    Work"—i.e., album title—as "Shake It, et al." (Doc. 51; Doc. 31-1 at
    1-3). Despite this, the songs listed in the stipulation match those
    listed in the copyright registration and, in any event, Plaintiff does
    not dispute that the copyright registrations proffered by Defendant
    accurately characterize and appropriately apply to the thirty-one songs
    at issue in this case. Defendant filed the following four copyright
    registrations: SR 670-739 (for the album "Out of Touch"), SR 669-420
    (for the album "Shake It, et al."), SR 670-722 (for the album
    "Sleepless Nights"), and SR 670-714 (for the album "Lost Songs". (Doc.
    31-1 at 1-12).

II. Summary Judgment Standard

Summary judgment is appropriate where "the pleadings, depositions, answers to
interrogatories, and admissions on file, together with the affidavits, if any,
show there is no genuine issue as to any material fact and that the moving party
is entitled to judgment as a matter of law." Fed. R. Civ. P. 56(c). The moving
party bears the initial responsibility of "informing the district court of the
basis for its motion, and identifying those portions of 'the pleadings,
depositions, answers to interrogatories, and admissions on file, together with
the affidavits, if any,' which it believes demonstrate the absence of a genuine
issue of material fact." _Celotex Corp. v. Catrett_, 477 U.S. 317, 323, 106 S.
Ct. 2548, 2553, 91 L. Ed. 2d 265 (1986). The movant may meet this burden by
demonstrating the absence of evidence supporting one or more essential elements
of the non-movant's claim. _Id._ at 323-25. Once the movant meets this burden,
the opposing party "must set forth specific facts showing that there is a
genuine issue for trial." _Anderson v. Liberty Lobby, Inc._, 477 U.S. 242, 250,
106 S. Ct. 2505, 2511, 91 L. Ed. 2d 202 (1986) (quoting Fed. R. Civ. P. 56(e)).

Once the burden of production has so shifted, the party opposing summary
judgment cannot rest on its pleadings or merely reassert its previous
allegations. It is not sufficient "simply [to] show that there is some
metaphysical doubt as to the material facts." _Matsushita Elec. Indus. Co. v.
Zenith Radio Corp._, 475 U.S. 574, 586, 106 S. Ct. 1348, 1356, 89 L. Ed. 2d 538
(1986). Rather, Rule 56(e) "requires the nonmoving party to go beyond the
pleadings" and present some type of evidentiary material in support of its
position. _Celotex_, 477 U.S. at 324, 106 S. Ct. at 2553; _see also Harris v.
General Motors Corp._, 201 F.3d 800, 802 (6th Cir. 2000). Summary judgment must
be entered "against a party who fails to make a showing sufficient to establish
the existence of an element essential to that party's case, and on which that
party will bear the burden of proof at trial." _Celotex_, 477 U.S. at 322, 106
S. Ct. at 2552.

"In considering a motion for summary judgment, the Court must view the facts and
draw all reasonable inferences therefrom in a light most favorable to the
nonmoving party." _Williams v. Belknap_, 154 F. Supp. 2d 1069, 1071 (E.D. Mich.
2001) (citing _60 Ivy Street Corp. v. Alexander_, 822 F.2d 1432, 1435 (6th Cir.
1987)). However, "'at the summary judgment stage the judge's function is not
himself to weigh the evidence and determine the truth of the matter,'" _Wiley v.
U.S._, 20 F.3d 222, 227 (6th Cir. 1994) (quoting Anderson, 477 U.S. at 249);
therefore, "[t]he Court is not required or permitted . . . to judge the evidence
or make findings of fact." _Williams_, 154 F. Supp. 2d at 1071. The purpose of
summary judgment "is not to resolve factual issues, but to determine if there
are genuine issues of fact to be tried." _Abercrombie & Fitch Stores, Inc. v.
Am. Eagle Outfitters, Inc._, 130 F. Supp. 2d 928, 930 (S.D. Ohio 1999).
Ultimately, this Court must determine "whether the evidence presents a
sufficient disagreement to require submission to a jury or whether it is so
one-sided that one party must prevail as a matter of law." _Anderson_, 477 U.S.
at 251-52; _see also Atchley v. RK Co._, 224 F.3d 537, 539 (6th Cir. 2000).

III. Discussion

A. Preliminary Issues

1.  Absence of Copyright Registration by Plaintiff

As a threshold matter, Defendant argues that Plaintiff's lawsuit is barred by 17
U.S.C. § 411(a), which requires that "no action for infringement of the
copyright in any United States work shall be instituted until registration of
the copyright claim has been made in accordance with this title." (Doc. 50 at
1). Noting that Plaintiff has failed to produce a registered copyright,
Defendant contends that Plaintiff's claims must be dismissed.

Defendant's argument is inapposite, as Plaintiff did not file a copyright
infringement lawsuit. Rather, Plaintiff filed a declaratory judgment claim
pursuant to 28 U.S.C. § 2201 requesting a declaration that he and Defendant are
joint authors of the songs in question. _See Gaiman v. McFarlane_, 360 F.3d 644,
648, 652 (7th Cir. 2004) (suit for declaration of joint authorship "is not a
suit for infringement."); _see also Severe Records v. Rich_, 658 F.3d 571,
581-82 (6th Cir. 2011) (citing Goodman, _infra_, at 1032); _Zuill v. Shanahan_,
80 F.3d 1366, 1369 (9th Cir. 1996) (distinguishing claims of joint authorship
and claims of infringement); _Goodman v. Lee_, 815 F.2d 1030, 1031-32 (5th Cir.
1987) (joint author sought declaratory judgment of joint authorship); _Brown v.
Flowers_, 297 F. Supp. 2d 846, 851 (M.D.N.C. 2003), _aff'd_ 196 Fed. Appx. 178,
2006 U.S. App. LEXIS 19055 (4th Cir. 2006) (Section 411(a) not applicable where
"[plaintiff] is not bringing an infringement action . . . [but instead] alleges
that the partnership had ownership rights in the songs created . . . .").
Defendant's invocation of Section 411(a) as a bar to Plaintiff's lawsuit is
therefore unpersuasive.

1.  Distinction Between Sound Recordings and the Underlying Compositions

At the outset, the Court notes that copyright law recognizes a distinction
between sound recordings and the underlying composition. _BTE, ET, CIE, LLC v.
Bonnecze_, 43 F. Supp. 2d 619, 627-28 (E.D.L.A. 1999). The District of New
Jersey explained this distinction as follows:

> A sound recording as copyrightable subject matter must be distinguished from
> the copyrighted literary, musical or dramatic work embodied in the sound
> recording and fixed on a phonorecord. When a copyrighted song is recorded on a
> phonorecord, there are two separate copyrights: one on the musical composition
> and the other in the sound recording. The sound recording is the aggregation
> of the sounds captured in the recording while the song or tangible medium of
> expression embodied in the recording is the musical composition. Thus, the
> rights of an owner of a copyright in a sound recording do not extend to the
> song itself. A copyright in the recording and in the song are separate and
> distinct and by statute are treated differently.

_T.B. Harms Co. v. Jem Records, Inc._, 655 F. Supp. 1575, 1577 n.1 (D.N.J. 1987)
(internal citations omitted).

In this case, Defendant's counterclaim unambiguously seeks a declaration of sole
ownership both as to the sound recordings and the underlying compositions. (Doc.
26 at ¶¶3-4). The relief sought by Plaintiff, however, is less clear.
Plaintiff's Complaint refers exclusively to "the compositions," or "the musical
compositions." Similarly, Plaintiff's response to Defendant's motion for summary
judgment refers exclusively to "the compositions" in the statement of facts
section, (Doc. 47 at 3-7), and otherwise seems to use the words "song," "work,"
"track," and "composition" interchangeably. The exception to this is two places
in which Plaintiff's brief reads: "Plaintiff states the following as his
contributions to the final recording of the following tracks," (Doc. 47 at 7)
(emphasis added), and "the evidence is on Plaintiff's favor to indicate that his
contributions to the final work were indeed significant enough to create a joint
work . . . ." _Id._ at 12 (emphasis added). Whether the Court construes
Plaintiff's request as involving the sound recordings, the underlying
compositions, or both is moot because, as explained below, Plaintiff is unable
to establish joint authorship.

B. Plaintiff's Assertion of Joint Authorship

Copyright ownership of a protected work initially vests in the work's author. 17
U.S.C. § 201(a). When a work is "prepared by two or more authors with the
intention that their contributions be merged into inseparable or interdependent
parts of a unitary whole," 17 U.S.C. § 101, the authors create a "joint work,"
_id._, and are considered to be "joint authors." _Childress v. Taylor_, 945 F.2d
500, 505 (2d Cir. 1991). Thus, joint authors are entitled to "equal undivided
interests in the whole work-in other words, each joint author has the right to
use or to license the work as he or she wishes, subject only to the obligation
to account to the other joint owner for any profits that are made." _Thomson v.
Larson_, 147 F.3d 195, 199 (2d. Cir. 1998) (citing 17 U.S.C. § 201(a));
_Childress_, 945 F.2d at 508). Further, because joint authors own an undivided
interest, they are not liable to one another for copyright infringement. _See
Newman v. Crowell_, 1979 U.S. Dist. LEXIS 9343, at *4-*5 (S.D.N.Y. Oct. 4, 1979)
(joint copyright owners cannot sue each other for infringement "because a
copyright owner cannot infringe his own copyright.").

In an unpublished opinion, _BancTraining Video Sys. v. First Am. Corp._, 1992
U.S. App. LEXIS 3677 (6th Cir. Mar. 3, 1992), the Sixth Circuit analyzed joint
authorship, but did not establish a specific test for courts to apply when
determining the issue. The parties do not cite BancTraining or otherwise suggest
what the Sixth Circuit's joint authorship test is or should be. Instead, they
argue under the Second Circuit's _Childress v. Taylor_ test, which requires a
party claiming joint authorship to show that (1) each party intended to be joint
authors, and (2) each party made an independently copyrightable contribution to
the work. _See Childress v. Taylor_, _supra_, 945 F.2d at 505-06; _see also
Thomson v. Larson_, _supra_, 147 F.3d 195 (refining _Childress_' joint
authorship test). After examination, this Court believes _Childress_ states the
appropriate test for determining joint authorship.

In adopting the _Childress_ test, this Court finds persuasive the Seventh
Circuit's reasoning for doing so in _Erickson v. Trinity Theatre, Inc._, 13 F.3d
1061 (7th Cir. 1994). _See Erickson_ at 1067-71 (_Childress_ best satisfies
statutory definition of joint work, _Childress_' "independently copyrightable
contribution" requirement provides consistency, promotes judicial efficiency,
and reinforces goals of Copyright Act, and majority of courts considering joint
authorship have applied _Childress_). Moreover, this Court notes that several
other district courts in the Sixth Circuit have applied _Childress_ and
_Erickson_ when confronting claims of joint authorship. _See Downey v. Downey_,
2010 U.S. Dist. LEXIS 99828, at *5 (S.D. Ohio Aug. 26, 2010); _Tang v. Putruss_,
521 F. Supp. 2d 600, 606 (E.D. Mich. 2007); _Perry v. Herd_, 2006 U.S. Dist.
LEXIS 17404, at *57 (E.D. Tenn. Feb. 14, 2006); _Balkin v. Wilson_, 863 F. Supp.
523, 528 (W.D. Mich. 1994). Therefore, this Court will apply the _Childress_
test to Plaintiff's claim of joint authorship.

As explained above, _Childress_ requires a party claiming joint authorship to
show that (1) each party intended to be joint authors, and (2) each party made
an independently copyrightable contribution to the work. 945 F.2d at 505-06.
With regard to intent, it is not enough that the parties intend their
contributions to be merged into "inseparable or interdependent parts of a
unitary whole." _See Bonnecaze_, supra, 43 F. Supp. 2d at 623 (citing
_Childress_, 945 F.2d at 507-08). Rather, the parties must "entertain in their
minds the concept of joint authorship." _Childress_, 945 F.2d at 508; _see also
Thomson_, 147 F.3d at 201 (citing _Childress_, 945 F.2d at 508) ("since
coauthors are afforded equal rights in the co-authored work, the 'equal sharing
of rights should be reserved for relationships in which all participants fully
intend to be joint authors.'"). Further, in _Thomson v. Larson_, the Second
Circuit explained that "the intention standard is not strictly subjective." 147
F.3d at 201 ("co-authorship intent does not turn solely on the parties' own
words or professed state of mind."). Instead, _Childress_ requires "a nuanced
inquiry into the factual indicia of ownership," which includes decision making
authority over the work, the way in which contributors bill or credit themselves
for the work, control of written agreements related to the work, and any other
evidence. _Id._ (_emphasis added_). With regard to _Childress_' second prong, a
putative joint author's contribution must be independently copyrightable.
_Erickson_, 13 F.3d at 1072. As such, "ideas, refinements, and suggestions,
standing alone," are not sufficient. _Id._ Rather, a party asserting joint
authorship must point to specific contributions that were fixed in a tangible
medium. _Id._ at 1071; _see also Bonnecaze_, 43 F. Supp. 2d at 628 (ideas and
insights contributed by drummer of rock band insufficient to establish joint
authorship of underlying compositions, and drummer's contributions to sound
recordings cannot serve as the required tangible expression for establishing
joint authorship of underlying compositions).

Applying the _Childress_ test to the facts of this case, the Court finds that
Plaintiff is unable to establish joint authorship for failure to satisfy the
first prong: a showing of intent. Plaintiff advances three substantive arguments
to demonstrate Defendant's intent. First, several portions of Plaintiff's
complaint and opposition brief claim that Defendant acknowledged Plaintiff as a
joint author and co-owner:

> Defendant denies the fact that for several years Defendant acknowledged and
> conceded Plaintiff's 50% ownership of the Compositions. Thus there is a
> dispute as to this fact . . . . After being pressed by Plaintiff to share
> revenues from the songs, about August 2010, Defendant then repudiated
> Plaintiff's co-ownership by contending that Defendant was the sole owner of
> the Compositions. (Doc. 47, Pl's. Mem. at 5);

> In the present case Defendant Quinonez did previously acknowledge Plaintiff
> Corwin as a joint-author and therefore their [sic] exists an intent at the
> time of the writing that the parts be absorbed or combined into an integrated
> unit. _Id._ at 13;

> Plaintiff states in his affidavit that Quinonez had acknowledged him as a
> co-author publicly and then ceased to do so in August 2010. _Id._ at 15
> (emphasis added);

> By letters to Plaintiff and other individuals in August 2010 and thereafter,
> Defendant for the first times repudiated. Plaintiff's co-ownership . . . .
> (Doc. 1, Pl's. Compl., at ¶15) (emphasis added).

The only evidence Plaintiff offers in support of these unsubstantiated claims is
another unsubstantiated claim; namely, his affidavit, which states that
"[Defendant] acknowledged my contribution in the past. [Defendant] then
repudiated my co-ownership to copywritten [sic] works in August of 2010." (Doc.
47-2 at ¶¶6-7). Such a conclusory allegation is insufficient to create a genuine
dispute of fact regarding Defendant's intent to be joint authors with Plaintiff.
_See Sigmon v. Appalachian Coal Props._, 400 Fed. Appx. 43, 2010 U.S. App. LEXIS
19493, at *48-*49 (6th Cir. Sept. 17, 2010) ("While an affidavit may certainly
be sufficient to establish a genuine issue of material fact . . . that is not
the case if the affidavit contains only conclusory allegations and naked
conclusions of law . . . ."). This is especially true given that Plaintiff
claims Defendant acknowledged his joint authorship status both publicly, (Doc.
47 at 15), and in letters to "other individuals," (Doc. 1 at ¶15), yet he fails
to provide any evidence aside from his own conclusory affidavit. To the
contrary, Defendant produced the affidavit of fellow band member, Robert Wagner,
which states:

> I cannot support the allegation that [Defendant] has previously conceded a
> 50/50 ownership of the songs in question with [Plaintiff]. I have no knowledge
> of [Defendant] making any statement to that effect . . . . I cannot support
> the allegation that [Defendant] has sent letters to [Plaintiff] and others
> repudiating a 50/50 ownership of the songs in question. I have no knowledge of
> correspondence addressing 50/50 ownership of the songs in question.[^Cor10]

[^Cor10]: Defendant also submitted the affidavit of Mike Hearst, which likewise
    denies knowledge of Defendant conceding joint authorship. (Doc. 40-1
    at p.2, ¶¶5-6). It is unclear to the Court, however, who Mike Hearst
    is.

(Doc. 40-1 at p.4, ¶¶5-6). Plaintiff's baseless assertion that Defendant
conceded joint authorship is therefore not persuasive.[^Cor11]

[^Cor11]: The Court's analysis is not altered by Plaintiff's passing reference
    to _Janky v. Lake County Convention & Visitors Bureau_, 576 F.3d 356
    (7th Cir. 2009). That case involved a clear concession of joint
    authorship—namely, plaintiff's filing of the copyright registration
    with defendant listed as a joint author and the song designated as a
    "joint work"—followed by a post-hoc excuse that the registration was
    simply meant to convey gratitude. _Id._ at 362.

Second, Plaintiff claims he and Defendant shared decision making authority
sufficient to demonstrate a mutual intent to be joint authors. Specifically,
Plaintiff cites a portion of Defendant's deposition that describes the process
by which Plaintiff recorded live instrumental components on top of Defendant's
pre-recorded electronic song:

> Q: For all the songs that have lead guitar . . . you guys would have some
> process where you would discuss what was going to go in there?

> A: Sure.

> Q: And then the plaintiff would play what he thought was appropriate and you
> would hit the buttons to record it and he would play it and it would get
> recorded, right?

> A: Fair enough.

(Doc. 45, Defendant's Deposition, at 58:3-12) (hereinafter, "Def's. Dep.").
Citing this exchange, Plaintiff claims that "Defendant's own words show his
intention at the time the songs were created that the parts created by Plaintiff
were to be absorbed or combined into an integrated unit the song itself." (Doc.
47 at 7).

Setting aside the fact that this deposition excerpt limits Defendant's statement
to a description of Plaintiff's lead guitar contributions, and that Plaintiff
has claimed guitar contributions in only nineteen songs-all of which appear on
the third and fourth albums only, (Doc. 47 at 7-8)-Defendant's statement does
not satisfy _Childress_' intent requirement. As explained above, it is not
enough that the parties intend their contributions to be merged into
"inseparable or interdependent parts of a unitary whole." _See Bonnecaze_, 43 F.
Supp. 2d at 623 (citing _Childress_, 945 F.2d at 507-08). The parties must
"entertain in their minds the concept of joint authorship." _Childress_, 945
F.2d at 508. When reading past the excerpt cited by Plaintiff, it is clear that
"Defendant's own words" do not establish that he entertained the concept of
joint authorship in his mind, because Defendant's words do not describe a
scenario in which he ceded control of the recordings to Plaintiff:

> Q: [The style of the lead guitar part] was within the discretion of the
> plaintiff, right?

> A: It was actually in the discretion of me. It was if I thought it was going
> to fit with the song.

> Q: Okay. Maybe that's not what I want to ask you . . . . With respect to the
> style of it, maybe it was your decision, I don't know, is that true?

> A: That is true. I made the final decision of what we used for the song.

(Def's. Dep. at 58:19-59:5). _See Erickson_, 13 F.3d at 1072 (no intent for
joint authorship where minor suggestions made by putative joint author, but
final decision belonged "entirely" to principal playwright); cf. Janky, 576 F.3d
at 362 (sufficient joint authorship intent where putative joint author "wielded
considerable control over what the song finally looked like; one could even say
he demanded the changes.").[^Cor12] Further, Plaintiff concedes that when
Defendant traveled to Boston to re-master the "Sleepless Nights" album,
Defendant re-wrote portions of songs and altered or omitted portions of the
other band members' contributions, including Plaintiff's. Plaintiff further
concedes that neither he nor the other two band members traveled to Boston or
participated in this process. Thus, Plaintiff cannot show that he exercised
decision making authority sufficient to demonstrate a mutual intent to be joint
authors.

[^Cor12]: The Court is aware that the Second Circuit admonished that "the
    intention standard is not strictly subjective. In other words,
    co-authorship intent does not turn solely on the parties' own words or
    professed state of mind." _Thomson_, 147 F.3d at 201. In this
    instance, however, Plaintiff limits his argument to the sufficiency of
    Defendants words to establish intent of joint authorship.

Finally, Plaintiff points to the band's four songs that were registered with BMI
in each of the four band members' names. Plaintiff maintains that the profit
sharing and mutual recognition resulting therefrom demonstrates joint authorship
intent. This argument is not persuasive. Plaintiff concedes that he does not
even know who registered the songs, let alone that Defendant did so
contemplating that the two of them should be joint authors. Moreover, even if
Defendant did register the songs, doing so in each of the four members' names
hardly evinces an intent that only two of them be joint authors. Further,
Plaintiff points to only four songs registered with BMI, leaving twenty-seven
songs unaccounted for. Simply put, a reasonable jury could not find that the
four-way registration of four songs demonstrates intent of joint authorship.

For the reasons stated above, the Court finds that Plaintiff cannot satisfy the
requisite showing of intent under _Childress_' joint authorship test, and the
Court therefore need not examine the "independent copyrightable contribution"
prong. Moreover, Plaintiff's claim for a declaration of joint authorship must be
dismissed and, because Plaintiff's claims for an accounting and constructive
trust are not cognizable without a showing of joint authorship, the remainder of
Plaintiff's complaint must also be dismissed.

C. Defendant's Assertion of Sole Authorship

Defendant's third amended counterclaim seeks a declaratory judgment that he is
the sole author of the compositions at issue, and the sole owner of the sound
recordings at issue. (Doc. 23 at ¶¶3-4).

Under Section 410(a) of the Copyright Act, a copyright registration made within
five years after publication of a work is prima facie evidence and creates a
rebuttable presumption of the registration's validity and of the facts stated
therein. BancTraining, 1992 U.S. App. LEXIS 3677, at *7-*8 (citing 17 U.S.C. §
410(a)). In this case, the copyright registrations for the "Shake It, et al.,"
"Sleepless Nights," and "Lost Songs" albums were made within five years. (Doc.
31-1 at 1-9). Defendant has therefore proffered prima facie evidence of sole
authorship, and Plaintiff has failed to rebut this evidence with his assertion
of joint authorship.

Defendant concedes that the copyright registration for the "Out of Touch" album
was made some five and a half years after its first publication. _Id._ at 10-12.
Despite this delay, "[t]he evidentiary weight to be accorded the certificate of
registration made [after five years] shall be within the discretion of the
court." 17 U.S.C. § 410(a). In this case, the Court finds the copyright
registration, coupled with Defendant's song-by-song description of his
authorship, (Doc. 30 at 14-36), satisfies Defendant's burden of demonstrating
authorship, and Plaintiff again has failed to rebut this showing with his
assertion of joint authorship.

In light of the above, the Court finds that Defendant is the sole author of the
compositions at issue, and the sole owner of the sound recordings at issue.

V. Conclusion

For the reasons stated herein, Defendant's motion for summary judgment is
granted. (Doc. 30). The Court hereby declares that Defendant is the sole author
of the compositions at issue, and the sole owner of the sound recordings at
issue (Copyright Registrations SR 670-739; SR 669-420; SR 670-722; and SR
670-714). Further, Plaintiff's complaint is dismissed. (Doc. 1). Counts II and
III of Defendant's third amended counterclaim remain pending. (Doc. 23).

IT IS SO ORDERED.

##### Discussion

1.  How are the _Aalmuhammed_ and _Childress_ standards different? What do they
    have in common? Which circuits have formally adopted which test as of the
    time of your reading?

2.  If provided with a clear written declaration of intention to be joint
    authors, what are the minimal criteria for meeting the second prong of the
    _Childress_ test?

3.  A helpful example of interdependent contributions is the case of _Brownstein
    v. Lindsay_, 742 F.3d 55, 59 (3d Cir. 2014) where one author created a test
    using scientific principles and the other author created software embodying
    the first author’s test:

> “Beginning around December 1993, Lindsay began devising the idea and
> developing the rules for categorizing names by ethnicity (e.g., by looking at
> first names, last names, suffixes, prefixes, and geographic location). These
> rules became known as the Ethnic Determinate System ("EDS") — they could be
> written out in text, just as one might write out a recipe or driving
> directions. The system would use this set of rules to run a computer program
> that would predict the ethnicity of a random list of names from a direct
> mailing database.

> In January 1994, Lindsay enlisted Brownstein to turn her rules into computer
> code. This required Brownstein to code a number of computer programs that did
> everything from rewriting a list of names into the proper data format for
> processing to turning Lindsay's rules into computer code. These programs
> became known as the ETHN programs. Over the years, Brownstein improved and
> updated the ETHN programs, with each new generation of programs being a
> distinct work from the previous generation. The combined system of Lindsay's
> rules and Brownstein's computer code was named the LCID. The result was that
> Lindsay was the sole author of the EDS, as an independent work of the LCID,
> Brownstein was the sole author of the ETHN programs, as another independent
> work of the LCID, and they both had an equal authorship interest in the LCID
> as a joint work of the EDS and the ETHN programs.”

> Is a court likely to consider the nature of open source development analagous
> or distinct from this form of cooperation? What could the role of “project
> maintainer” designations and privileges have when evaluating which author(s)
> possess creative control over the work?

1.  What type of copyrighted work is this open source casebook? If you were to
    contribute content to this casebook, what rights would you hold over what
    content? Where do you look to find answers to these questions?
