# Zyzyxia Public Licence

### Version 1, 1 October 2026. 

*SPDX-FileCopyrightText: 2026 JM van Schalkwyk  
SPDX-License-Identifier: LicenseRef-Zyzyxia-1*

# PREAMBLE

The Zyzyxia Public Licence (ZPL) is a copyleft licence for the Zyzyxia
programming language and for programs and documentation written in it.

Its purposes are to keep code and its explanation together, so that
every work can be understood and traced to its origin; to keep derived
works under the same terms; and to reserve to the copyright holders the
use of their work to train machine-learning models, restricting its
submission to generative AI systems.

It does not seek to extend copyright or to limit any right that the law
gives you. Because it restricts a field of use, it is a source-available
licence, not a free software or open source licence.

Certain parts of the Licence are derived from [the GNU General Public
Licence version 3](https://www.gnu.org/licenses/gpl-3.0.en.html) (the
GPL v3), but the Licence is not compatible with that licence in either
direction. GPL v3 forbids additional restrictions (like those in Section
1 of the ZPL); the ZPL mandates licensing under the ZPL.

This preamble explains the Licence and is not part of its terms and
conditions, which follow:

# **TERMS AND CONDITIONS**

## **0. Definitions**

“**This Licence**” refers to version 1 of the ****Zyzyxia**** Public
Licence.

Each licensee is addressed as “you”. “Licensees” and “recipients” may be
individuals or organisations.

“**Instructions**” refers to human-readable text written in the
programming language ****Zyzyxia. ****

“**Code**” refers to Instructions, or any transformation or
representation of such Instructions.

“**Object Code**” here refers to any transformation of Instructions that
cannot be completely transformed back to the original Instructions
without additional information not contained in the object code itself.
Object Code is a subset of “Code”.

“**Code Execution**” is the interpretation, compilation or other use of
Code to perform actions of any kind in hardware or on a virtual machine.

“**Documentation**” refers to words written in natural language (for
example, English) and any accompanying equations, figures or diagrams
that describe how Code operates, or the context in which Code operates;
or explain any aspect of the use or function of Code.

To “**modify**” a work means to copy from or adapt all or part of the
work, other than the making of an exact copy. The resulting work is
called a “modified version” of the earlier work or a work “based on” the
earlier work.

“**Literate Source Document**” is a document containing Documentation
and Instructions, that can by simple transformation be converted into
both a PDF document that describes the contained Instructions, and Code
that can be subject to Code Execution. (A typical example of a Literate
Source Document would be a LaTeX document containing Instructions
embedded in ‘verbatim’ environments within the document, together with a
description of those Instructions. A typical example of simple
transformations that fulfil both requirements would be first, rendering
of the LaTeX document as a PDF document using PDFLaTeX, and extraction
of the verbatim text using the tool
[Dogwagger](https://github.com/jvanschalkwyk/dogwagger).) The Literate
Source Document is the authoritative source from which both
human-readable documentation and executable Code are derived.

A “**Covered Work**” means any copyrightable work licensed under this
Licence, including one or more of the following: the unmodified Code, or
Documentation, or a Literate Source Document; or a modified version of
any of the preceding items.

**“Publicly Available”** means available to any person without
registration or payment, on terms permitting its use for the purpose
concerned.

An “**Open Format**” is a file format or transmission format that: (a)
is Publicly Available in enough detail to allow an independent person to
read, unpack and copy files in that format; (b) has at least one
functioning implementation that is available to the public in source
code form, on terms that permit its use for reading, unpacking and
copying; and (c) requires no password, key or other credential, and is
not protected by any technical measure that restricts reading, unpacking
or copying.

Where a Covered Work contains or represents Code, the “**Corresponding
Literate Source Document**” is a Literate Source Document that: (a)
contains complete Instructions from which that Code was produced, or
which it represents; (b) includes, or identifies by Publicly Available
reference, all scripts and tools needed to perform the transformation
described under “Literate Source Document”; (c) contains Documentation
that satisfies Section 2.1.7, and that covers (i) the intent of the
Instructions and the context in which they are intended to be deployed;
(ii) how the Instructions work, including all non-trivial algorithms;
and (iii) any context, known to the person conveying it, in which the
Code should not be deployed; (d) in the case of a modified version, has
its Documentation updated to describe the modifications; and (e) is in
an Open Format, as are any tools or scripts it includes.

**“Machine-Learning Model”** means a computational model whose
parameters, weights or other internal state are determined, wholly or
partly, by an automated optimisation or fitting procedure applied to
data, including neural networks, language models, embedding models or
learned classifiers. A program is not a Machine-Learning Model merely
because its author adjusted constants or heuristics by hand.

**“Generative AI System”** means a computational system that uses a
Machine-Learning Model to generate or transform Code or natural-language
text in response to inputs of any kind; a compiler, interpreter,
assembler, linker, formatter, parser, search engine, version-control
system, or other software that does not use a Machine-Learning Model is
not a Generative AI System merely because it processes or transforms
Code.

**“AI Training Use”** means any use of a Covered Work, or of any copy,
extract, transformation or representation of it:

\(a\) to train, pre-train, fine-tune, distil, align, evaluate or
benchmark a Machine-Learning Model;

\(b\) to create embeddings, vector indexes or similar derived
representations for storage in a retrieval or knowledge system that
supplies content to a Machine-Learning Model; or

\(c\) to compile, label, curate, sell or license a dataset for any of
the purposes in (a) or (b).

To “**propagate**” a work means to copy, distribute (with or without
modification), or make available to the public.

To “**convey**” a work means any kind of propagation that enables other
parties to make or receive copies, regardless of how they subsequently
use such copies, in part or in full.

A “**User Product**” is either (a) a “consumer product”, which means any
tangible personal property which is normally used for personal, family,
or household purposes, or (b) anything designed or sold for
incorporation into a dwelling. In determining whether a product is a
consumer product, doubtful cases shall be resolved in favour of
coverage. For a particular product received by a particular user,
“normally used” refers to a typical or common use of that class of
product, regardless of the status of the particular user or of the way
in which the particular user actually uses, or expects or is expected to
use, the product. A product is a consumer product regardless of whether
the product has substantial commercial, industrial or non-consumer uses,
unless such uses represent the only significant mode of use of the
product.

“**Installation Information**” for a User Product means any methods,
procedures, authorisation keys, or other information required to install
and execute modified versions of a Covered Work in that User Product
from a modified version of its Code. The information MUST suffice to
ensure that the continued functioning of the modified Code is in no case
prevented or interfered with solely because modification has been made.

A “**contributor**” is a copyright holder who authorises *use under this
Licence* of the Covered Work or a work on which the Covered Work is
based. The work thus licensed is called the contributor’s “contributor
version”.

## **1. Use with Generative AI Systems**

### **1.1 No licence for AI Training Use**

You MUST NOT engage in AI Training Use, or cause or permit another
person to do so on your behalf. The rights granted by this Licence do
not extend to AI Training Use. The copyright holders expressly reserve
all rights in respect of AI Training Use, including for the purposes of
any text-and-data-mining exception or opt-out provision under applicable
law.

A notice of reservation, in human-readable or machine-readable form,
whether in a file header, a NOTICE file, or served with the Covered
Work, is an express reservation of rights for the purposes of this
Section. The reservation applies whether or not a notice is provided,
and the absence or removal of a notice does not waive it.

### **1.2 Input to Generative AI Systems**

You MUST NOT submit, upload, transmit or otherwise provide any part of a
Covered Work as input to a Generative AI System.

### **1.3 Conveying**

You MUST NOT convey a Covered Work to a person if you know, or have
reasonable grounds to believe, that the person intends AI Training Use.
Whenever you convey a Covered Work, you MUST include a notice of the
reservation in Section 1.1. Making a Covered Work available to the
public, with the notice of the reservation in Section 1.1, is not by
itself a breach of this Section 1.3.

### **1.4 Exclusions**

The following are not breaches of this Section 1:

\(a\) using or reproducing the text of this Licence and the notices
required by it;

\(b\) quoting a Covered Work in a bug report, error message or citation,
to the extent reasonably necessary for that purpose;

\(c\) processing by a hosting platform or network operator solely to
provide the hosting or network service (for example, malware, secret or
spam detection), provided the result is not used for AI Training Use;
and

\(d\) use of assistive technologies, such as screen readers, machine
translation or spelling correction, on a transient basis without
retention for AI Training Use.

### **1.5 Scope of the grant**

The restrictions in this Section 1 are limits on the scope of the rights
granted by this Licence, and are also covenants.

## **2. Usage and Conveying**

### **2.1 Conveying**

#### **2.1.1 General rule**

You may convey a Covered Work only as expressly permitted by this
Licence. Whenever you convey a Covered Work, you MUST:

\(a\) where the Covered Work is Code (including Object Code), provide
the Corresponding Literate Source Document for that Code in accordance
with Section 2.1.2;

\(b\) include a copy of this Licence; and

\(c\) include a clear statement that the Covered Work is covered by the
****Zyzyxia**** Public Licence.

#### **2.1.2 Providing the Corresponding Literate Source Document**

You provide it by one of the following means:

\(a\) conveying it together with the Code, on the same medium or in the
same transmission; or

\(b\) accompanying the Code with a statement identifying a location
(such as a network address), and a version identifier or hash, from
which any person may copy the Corresponding Literate Source Document for
the Code as conveyed, under the terms of this Licence, without
registration and at no charge (or, for a physical medium, at no more
than the reasonable cost of supplying it). You MUST keep the
Corresponding Literate Source Document available at that location for as
long as you convey the Code and for at least three years after you last
convey it.

The location under (b) may be on a server operated by another person,
but you remain responsible for its availability and for compliance with
this Section 2.1.2.

#### **2.1.3 Fragments**

Where you convey only part of the Code, you satisfy Section 2.1.2 by
providing, or by precisely identifying (by document, version and
location), an existing Corresponding Literate Source Document from which
that part derives.

Quoting a short extract of a Covered Work, to the extent reasonably
necessary for criticism, review or citation, with attribution and a
statement that the extract is covered by this Licence and where it can
be found, does not require you to license the work in which it appears
under this Licence, or to comply with Section 2.1.1(b) and (c). The
extract itself remains a Covered Work. Section 1 continues to apply to
it.

#### **2.1.4 Notices**

Each copy you convey MUST preserve all copyright notices and other
notices identifying the authorship and provenance of the Covered Work,
all notices stating that it is governed by this Licence, all notices of
the reservation in Section 1.1, and all notices concerning the absence
of warranty.

#### **2.1.5 Aggregation**

The inclusion of a Covered Work with separate and independent works does
not, by itself, cause this Licence to apply to those other works. This
Section is subject to Section 2.3.

#### **2.1.6 Charges**

You may charge any price or no price for each copy that you convey, and
you may offer support or warranty protection for a fee. This does not
permit any charge for access to the Corresponding Literate Source
Document beyond that allowed by Section 2.1.2(b).

#### 2.1.7 Adequacy of Documentation

Documentation is adequate for limb (c) of the definition of
Corresponding Literate Source Document if it covers each of the matters
in limb (c)(i) to (iii) in reasonable detail, and is no less detailed
than the Documentation that accompanied the version you received and,
for portions you wrote or modified, no less detailed than that of
comparable portions of the same work. It is not inadequate merely
because a reader would prefer more detail. A deficiency under limb (c)
alone is not a violation of this Licence unless the copyright holder has
notified you of it with reasonable particularity and you have not
remedied it within 60 days. A notice under this Section is not a notice
of violation for the purposes of Section 5.1(b).

#### **2.1.8 Each conveyor responsible**

Except as provided in Section 2.1.3, each person who conveys Code is
responsible for compliance with Section 2.1.2 for their own conveyance,
and may not rely on a location given by a person from whom they received
it. If you received Code with only a location, you MUST copy the
Corresponding Literate Source Document before you convey the Code.

### **2.2. Conveying Verbatim Copies**

You may convey verbatim copies of a Covered Work in accordance with
Section 2.1.

### **2.3. Conveying Modified Source Versions**

You may convey a work based on a Covered Work, in accordance with
Section 2.1, provided that the work carries prominent notices stating
that you modified it and giving a relevant date, and that you license
the entire work, as a whole, under this Licence to anyone who comes into
possession of a copy.

For the purposes of this Licence, a work is also based on a Covered Work
if it incorporates Instructions from the Covered Work, whether by
copying them or by including them in the work when it is built, or if
its Instructions import or link to the Covered Work, or call it within
the same process or program. A work is not based on a Covered Work
merely because it communicates with it as a separate program or process,
for example by command line, socket or network request. The Zyzyxia
language implementation is not part of a work merely because the work is
run by it.

The output of Code Execution is not a Covered Work, or a work based on
one, merely because it was produced by a Covered Work. It is a Covered
Work only to the extent that it contains Instructions or Documentation
copied or adapted from a Covered Work.

### **2.4. User Products**

If you convey Code in, with, or specifically for use in a User Product,
as part of a transaction in which the right of possession and use of the
User Product is transferred to the recipient in perpetuity or for a
fixed term (however characterised), you MUST also provide all
Installation Information for that User Product. Section 2.1.2 applies to
Installation Information as it applies to the Corresponding Literate
Source Document, and Installation Information MUST be in an Open Format.

The requirement to provide Installation Information does not include a
requirement to continue to provide support, warranty or updates for a
work that the recipient has modified or installed, or for the User
Product in which it was modified or installed. Access to a network may
be denied when the modification itself materially and adversely affects
the operation of the network or violates the rules and protocols for
communication across the network.

## **3. Basic Permissions**

All rights granted under this Licence are granted for the term of
copyright on the Covered Work, and are irrevocable provided the stated
conditions are met, subject to Section 5. Subject to Section 1, you may
make, run, and modify Covered Works that you do not convey, and use them
privately.

You may convey Covered Works to others for the sole purpose of having
them make modifications for you, or provide you with facilities for
running or storing those works, provided that you comply with the terms
of this Licence in conveying all material for which you do not control
copyright. Those thus making, running or storing the Covered Works for
you MUST do so exclusively on your behalf and under your direction, and
MUST NOT use them for AI Training Use or for any purpose of their own
other than processing permitted by Section 1.4(c). Such persons act
under the rights granted to you and do not receive rights of their own
under this Licence or Section 7 by reason of that arrangement.

Conveying in any other circumstances is governed by Section 2.
Sublicensing is not allowed; see Section 7.

## **4. Protecting Users’ Legal Rights From Anti-Circumvention Law**

No Covered Work shall be deemed part of an effective technological
measure under any applicable law fulfilling obligations under article 11
of the WIPO copyright treaty adopted on 20 December 1996, or similar
laws prohibiting or restricting circumvention of such measures.

When you convey a Covered Work, you waive any legal power to forbid
circumvention of technological measures to the extent such circumvention
is effected by exercising rights under this Licence with respect to the
Covered Work, and you disclaim any intention to limit operation or
modification of the work as a means of enforcing, against the work’s
users, your or third parties’ legal rights to forbid circumvention of
technological measures.

Nothing in this Section prevents any person from using technical
measures to prevent or deter AI Training Use or submission to a
Generative AI System, and circumvention of such measures for those
purposes is not an exercise of rights under this Licence.

## **5. Termination and Reinstatement**

A violation of this Licence terminates your rights under this Licence,
including any patent licences granted under Section 8. Your rights may
be reinstated only as provided in Sections 5.1 and 5.2, and subject to
Section 5.3.

### **5.1 Reinstatement (general)**

Your rights from a particular copyright holder are reinstated
permanently if:

\(a\) that holder notifies you of a violation, by reasonable means and
with reasonable particularity;

\(b\) this is the first notice of a violation of this Licence that you
have received from that holder; and

\(c\) you cure the violation notified within 60 days after receipt of
the notice.

If a holder has not notified you of a violation within 60 days after you
cease all violations of which you are aware, your rights from that
holder are reinstated permanently on expiry of that period.

To “cure” a violation means to cease it and to remedy its consequences
so far as you reasonably can, including by supplying anything whose
omission was the violation. Payment of compensation is not part of cure,
except as provided in Section 5.3.

Permanent reinstatement under Section 5.1(a) to (c), or under Section
5.2, is available once for each copyright holder. Reinstatement because
a holder has given no notice within the 60 days does not use up that one
reinstatement. After a reinstatement that does use it up, a later
violation of any kind terminates your rights from that holder with no
further reinstatement under either Section.

### **5.2 Interactive breaches** 

If your only violations are a submission of a Covered Work as input to a
Generative AI System in breach of Section 1.2, and a violation of
Section 9 arising solely from the terms on which the operator offers
that system, and neither amounts to AI Training Use by you or by a
person acting on your behalf, your rights from each affected copyright
holder are reinstated permanently if you:

\(a\) cease the submission and any conveying of the Covered Work while
bound by those terms;

\(b\) take all reasonable steps to have the input deleted, including
making a deletion request to the operator of the system where the
operator offers one; and

\(c\) notify each affected copyright holder within 30 days of becoming
aware of the violation, at any contact address that holder has provided
for notices concerning the Covered Work (including an address in a
notice required by this Licence), stating the system and operator
concerned, the portion submitted, and what you know about whether the
operator has retained the input or used it for AI Training Use.

If a holder has provided no contact address, condition (c) does not
apply to that holder. Failure to meet the deadline in (c) does not
prevent reinstatement under Section 5.1.

Reinstatement under this Section is not undone by anything the operator
later does with the input, provided that, where condition (c) applies,
your notice was complete and accurate to your knowledge.

### **5.3 Training breaches**

A violation of Section 1 that involves AI Training Use by you or by a
person acting on your behalf is not reinstated under Section 5.1 or 5.2.
Your rights from an affected copyright holder may be reinstated only if
that holder agrees in writing. That holder may make its agreement
conditional on any of the following:

\(a\) removal of the Covered Work from all datasets and derived indexes
under your control;

\(b\) retraining, or, where retraining is impracticable, another remedy
the holder accepts in writing (for example, an agreed unlearning
procedure or a retrospective licence);

\(c\) a written statement of the extent of the use; and

\(d\) payment of compensation agreed in writing.

Reinstatement under this Section 5.3 does not count as the reinstatement
available once under Section 5.1 or 5.2. Section 7 does not restrict
conditions imposed under this Section 5.3, because they apply only to
persons whose rights have been terminated.

### **5.4 Effect of reinstatement; third parties**

Reinstatement of your rights by one copyright holder restores your
rights only in respect of that holder’s contributions to the Covered
Work. Reinstatement does not by itself release any claim arising from
acts done while your rights were terminated.

Termination of your rights does not terminate the licences of parties
who have received copies or rights from you under this Licence. If your
rights have been terminated and not reinstated, you do not qualify to
receive new licences under Section 7 for the material of any holder from
whom your rights have not been reinstated.

## **6. Copyright and Acceptance**

Nothing other than this Licence grants permission to exercise the rights
granted by copyright in the Covered Work. Any act requiring such
permission and not authorised by this Licence is prohibited by this
Licence.

Nothing in this Licence asserts that an act which does not require
permission under applicable law constitutes copyright infringement
merely because it is prohibited by this Licence.

By modifying or conveying a Covered Work, or by doing any other act that
requires permission under this Licence, you indicate your acceptance of
this Licence to do so.

## **7. Automatic Licensing of Downstream Recipients**

Each time you convey a Covered Work, the recipient automatically
receives a licence from each contributor and each other copyright holder
who has licensed it under this Licence, to run, modify and propagate
that work, subject to this Licence, including Sections 1 and 2. Rights
to convey are governed by Section 2. Sublicensing is not allowed. You
are not responsible for enforcing this Licence against third parties,
but you remain responsible for your own compliance and for the
compliance of persons acting on your behalf.

An “entity transaction” is a transaction transferring control of an
organisation, or substantially all assets of one, or subdividing an
organisation, or merging organisations. If propagation of a Covered Work
results from an entity transaction, each party to that transaction who
receives a copy of the work also receives whatever licences to the work
the party’s predecessor in interest had or could give under the previous
paragraph, plus a right to possession of the Corresponding Literate
Source Document of the work from the predecessor in interest, if the
predecessor has it or can get it with reasonable efforts. A party to an
entity transaction does not obtain any right that its predecessor
lacked, is not freed by the transaction from any condition under Section
5.3, and remains subject to Section 2.

Except as provided in Section 5.3, you may not impose any further
restrictions on the exercise of the rights granted or affirmed under
this Licence. Restrictions imposed by this Licence itself, including
Section 1 and the conditions in Section 3, are not further restrictions.
For example, you may not impose a licence fee, royalty, or other charge
for exercise of rights granted under this Licence, other than as
permitted by Section 2.1.6.

## **8. Patents**

### **8.1 Patent licence**

A contributor’s “essential patent claims” are all patent claims owned or
controlled by the contributor, whether already acquired or hereafter
acquired, that would be infringed by making, using or selling its
contributor version in a manner permitted by this Licence, but not
claims that would be infringed only as a consequence of further
modification of the contributor version. “Control” includes the right to
grant patent sublicences consistently with this Licence. Each
contributor grants you a non-exclusive, worldwide, royalty-free patent
licence under its essential patent claims to make, use, sell, offer for
sale, import and otherwise run, modify and propagate the contents of its
contributor version, subject to this Licence.

### **8.2 Extension to all recipients**

If, in connection with conveying a Covered Work, you grant a patent
licence (any express agreement or commitment not to enforce a patent) to
some recipients covering that work, the patent licence is automatically
extended to all recipients of the Covered Work and of works based on it.

### **8.3 No patent retaliation**

If you initiate litigation (including a cross-claim or counterclaim)
alleging that making, using, selling, offering for sale or importing the
Covered Work or any portion of it infringes a patent claim, that is a
violation of this Licence.

### **8.4 Defences preserved**

Nothing in this Licence excludes or limits any implied licence or other
defence to infringement that may be available to you under applicable
patent law.

## **9. Conflicting obligations**

If obligations are imposed on you (whether by court order, agreement,
platform terms or otherwise) that conflict with this Licence, they do
not excuse you from complying with it. If you cannot satisfy both this
Licence and those obligations, you may not convey the Covered Work, and
no such obligation excuses a breach of Section 1. Conveying a Covered
Work in these circumstances is a violation of this Licence. For example,
if you agree to terms that require you to collect a royalty from
recipients for their further conveying, that require you to keep any
part of the Corresponding Literate Source Document confidential, or that
purport to grant AI Training Use rights in the Covered Work, the only
way to comply with both those terms and this Licence is to refrain from
conveying the Covered Work.

Agreeing to the terms on which a Generative AI System is offered is not
itself a violation of this Section. However, you MUST NOT convey a
Covered Work while bound by terms that purport to grant AI Training Use
rights in the Covered Work, and any such purported grant is ineffective
against the copyright holders.

## **10. Disclaimer of Warranty**

THERE IS NO WARRANTY FOR THE COVERED WORK, TO THE EXTENT PERMITTED BY
APPLICABLE LAW. EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT
HOLDERS AND/OR OTHER PARTIES PROVIDE THE COVERED WORK “AS IS” WITHOUT
WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A
PARTICULAR PURPOSE. THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF
THE COVERED WORK IS WITH YOU. SHOULD THE COVERED WORK PROVE DEFECTIVE,
YOU ASSUME THE COST OF ALL NECESSARY SERVICING, REPAIR OR CORRECTION.

## **11. Limitation of Liability**

IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING
WILL ANY COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MODIFIES AND/OR
CONVEYS THE COVERED WORK AS PERMITTED ABOVE, BE LIABLE TO YOU FOR
DAMAGES, INCLUDING ANY GENERAL, SPECIAL, INCIDENTAL OR CONSEQUENTIAL
DAMAGES ARISING OUT OF THE USE OR INABILITY TO USE THE COVERED WORK
(INCLUDING BUT NOT LIMITED TO LOSS OF DATA OR DATA BEING RENDERED
INACCURATE OR LOSSES SUSTAINED BY YOU OR THIRD PARTIES OR A FAILURE OF
THE COVERED WORK TO OPERATE WITH ANY OTHER PROGRAMS), EVEN IF SUCH
HOLDER OR OTHER PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH
DAMAGES.

## **12. Interpretation of Sections 10 and 11**

If the disclaimer of warranty and limitation of liability in Sections 10
and 11 cannot be given legal effect according to their terms in the
jurisdiction concerned, it is the intention of the parties that the
court apply the law of that jurisdiction that most closely approximates
an absolute waiver of all civil liability in connection with the Covered
Work, to the extent that law permits, unless a warranty or assumption of
liability accompanies a copy of the Covered Work in return for a fee.

## **13. Governing Law and Jurisdiction**

### 13.1 Governing Law

This Licence, including its interpretation, what it permits, and the
termination and reinstatement of rights under it, is governed by the law
of New Zealand, without regard to its conflict-of-laws rules. Whether a
work is protected, who owns it, whether an act requires the permission
of a copyright holder, and whether an act infringes copyright are
governed by the law that applies to those questions under the rules of
private international law. Where that law requires permission for an
act, whether this Licence grants that permission is determined under the
first sentence.

### 13.2 Jurisdiction

You submit to the non-exclusive jurisdiction of the courts of New
Zealand. Any copyright holder may also bring proceedings in any other
court that has jurisdiction over you or over the act complained of.

### 13.3 Limits to Right or Remedy

Nothing in this Section limits any right or remedy that applicable
mandatory law gives you or a copyright holder.

### 13.4 Later version

You may apply a later version of the Zyzyxia Public Licence to a Covered
Work only if the copyright holder has expressly stated that later
versions may be applied. Later versions are those published by the
licence steward, (JM van Schalkwyk, or a successor designated by the
steward in writing and published at https://www.zyzyxia.org).

## **14. Severability**

If any provision of this Licence is held unenforceable in any
jurisdiction, it is enforced to the fullest extent permitted there and
the remaining provisions are unaffected. Without limiting that, each of
the following is severable from the others, so that a finding against
one does not affect the others: (a) the covenant in the first sentence
of Section 1.1; (b) the limit on the rights granted and the reservation
of rights in the rest of Section 1.1, and Section 1.5; and (c) the
restriction on input to Generative AI Systems in Section 1.2. Section 12
applies in preference to this Section 14 in respect of Sections 10 and
11.

## **15. Applying this Licence**

A copyright holder applies this Licence to a work by including in the
work, or in a NOTICE file accompanying it, a statement that the work is
licensed under the Zyzyxia Public Licence version 1, together with the
holder’s name and a year. A holder who wishes to receive notices under
Sections 5 and 2.1.7 SHOULD include a contact address in that statement.
Where the holder has not provided one, notice may be given by any
reasonable means.

**END OF TERMS AND CONDITIONS.**

# How to apply this licence

To apply the Licence to a work, include a copy of the Licence with the
work, and attach the following notice to each file (for example, in a
header or comment):

> Copyright © \[year\] \[copyright holder\]

> This work is licensed under the Zyzyxia Public Licence, version 1.  
> You may convey it only together with its Corresponding Literate
> Source  
> Document, as that Licence requires. All rights are reserved in respect
> of  
> AI Training Use, including for the purposes of any
> text-and-data-mining  
> exception or opt-out provision under applicable law. Submitting this
> work  
> as input to a Generative AI System is prohibited.

> Contact address for notices concerning this work: \[address\]

> *SPDX-FileCopyrightText: \[year\] \[copyright holder\]*  
> *SPDX-License-Identifier: LicenseRef-Zyzyxia-1*

A contact address is optional, but Section 5.2(c) requires notice only
to holders who have provided one.

Here is some additional information about SPDX, the TDM reservation
protocol, and robots.txt.

## A. SPDX identifier

[SPDX](https://spdx.dev/about/overview/) is an open standard for
communicating software bill of material information, including
provenance, license, security, and other related information. SPDX has a
[list of licences](https://spdx.dev/learn/handling-license-info/). Each
file should contain information along these lines:

> *SPDX-FileCopyrightText: 2026 JM van Schalkwyk  
> SPDX-License-Identifier: LicenseRef-Zyzyxia-1*

## B. TDM reservation protocol

The [TDM reservation
protocol](https://www.w3.org/community/reports/tdmrep/CG-FINAL-tdmrep-20240202/)
defines a simple and practical Web protocol, capable of expressing the
reservation of rights relative to text & data mining (TDM) applied to
lawfully accessible Web content, and to ease the discovery of TDM
licensing policies associated with such content. There are three
conventions:

1.  As an HTTP header: *tdm-reservation: 1*
2.  In HTML: *\<meta name="tdm-reservation" content="1"\>*
3.  Insert a json file: */.well-known/tdmrep.json* with the following
    contents :

*\[{"location": "/", "tdm-reservation": 1}\]*

## C. robots.txt

This is a voluntary entry—often ignored by modern AI crawlers—along the
lines of:

*User-agent: GPTBot  
User-agent: ClaudeBot  
User-agent: CCBot  
User-agent: Google-Extended  
Disallow: /*

Such a list will need to be maintained, as agents change.
