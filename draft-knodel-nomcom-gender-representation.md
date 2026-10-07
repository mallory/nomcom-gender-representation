---
title: "Gender Representation in the IETF Nominating Committees"
abbrev: "nomcom-gender-representation"
category: info


docname: draft-knodel-nomcom-gender-representation-latest
submissiontype: IETF
number:
date:
consensus: true
v: 3

area: GENART
workgroup:
keyword:
 - gender
venue:
  group:
  type:
  mail:
  arch:
  github: "mallory/nomcom-gender-representation"
  latest: "https://mallory.github.io/nomcom-gender-representation/draft-knodel-nomcom-gender-representation.html"


author:
 -
    fullname: Mallory Knodel
    organization: NYU
    email: mallory.knodel@nyu.edu
 -
    fullname: Tara Tarakiyee
    organization: Independent
    email: me@tarakiyee.com

normative:

  RFC2119:
  RFC8174:
  RFC3797:

informative:

  RFC8713:
  RFC9389:
  IETFSurvey2025:
    target: https://www.ietf.org/blog/ietf-community-survey-2025/
    title: IETF Community Survey 2025
    author:
      -
        ins: J. Daley
      -
        ins: A. Gohil
    date: 2026-07-14
  Kaeo2023:
    target: https://www.ietf.org/media/documents/Experience_of_Women_Participating_in_the_IETF.pdf
    title: Experience of Women Participating in the IETF
    author:
      ins: M. Kaeo
    date: 2023-10
  IESGFollowUp2024:
    target: https://datatracker.ietf.org/meeting/121/materials/slides-121-systers-sessb-follow-up-to-the-experience-of-women-participating-in-the-ietf-report-00
    title: "Follow-up to the 'Experience of Women Participating in the IETF' Report"
    author:
      ins: R. Danyliw
    date: 2024-11-07
  ICANNCoC:
    target: https://www.icann.org/resources/pages/nomcom2019-conduct-2018-12-07-en
    title: ICANN Nominating Committee Background Information and Code of Conduct
    author:
      org: ICANN
    date: 2018
  ICANNBylaws:
    target: https://www.icann.org/resources/pages/governance/bylaws-en/#article8
    title: "ICANN Bylaws, Article 8, Section 8.2 (Nominating Committee composition)"
    author:
      org: ICANN
    date: 2024
  Kanter1977:
    target: https://doi.org/10.1086/226425
    title: "Some Effects of Proportions on Group Life: Skewed Sex Ratios and Responses to Token Women"
    author:
      ins: R. M. Kanter
    seriesinfo:
      "American Journal of Sociology": "82(5), pp. 965-990"
    date: 1977
  KonradKramerErkut2008:
    target: https://doi.org/10.1016/j.orgdyn.2008.02.005
    title: "Critical Mass: The Impact of Three or More Women on Corporate Boards"
    author:
      -
        ins: A. M. Konrad
      -
        ins: V. W. Kramer
      -
        ins: S. Erkut
    seriesinfo:
      "Organizational Dynamics": "37(2), pp. 145-164"
    date: 2008
  Torchia2011:
    target: https://doi.org/10.1007/s10551-011-0815-z
    title: "Women Directors on Corporate Boards: From Tokenism to Critical Mass"
    author:
      -
        ins: M. Torchia
      -
        ins: A. Calabro
      -
        ins: M. Huse
    seriesinfo:
      "Journal of Business Ethics": "102, pp. 299-317"
    date: 2011
  ChildsKrook2008:
    target: https://mlkrook.org/pdf/childs_krook_2008.pdf
    title: "Critical Mass Theory and Women's Political Representation"
    author:
      -
        ins: S. Childs
      -
        ins: M. L. Krook
    seriesinfo:
      "Political Studies": "56(3), pp. 725-736"
    date: 2008
  OECD2020:
    target: https://doi.org/10.1787/339306da-en
    title: "Innovative Citizen Participation and New Democratic Institutions: Catching the Deliberative Wave"
    author:
      org: OECD
    date: 2020

--- abstract

This document extends the existing limit on nomcom representation by organization ([RFC8713], Section 4.17) so that not all voting members of the IETF Nominating Committee (nomcom) belong to the same gender. It guarantees up to five voting seats to volunteers who opt into a self-declared pool, and changes the selection only in years when a plain random draw would seat fewer.

--- middle

# Introduction

The nomcom is, in every functional sense, a hiring committee: it solicits candidates, reviews their qualifications, interviews them, and selects who will fill the IETF's most senior leadership roles.

This document extends [RFC8713]'s limit on nomcom representation by organization to ensure no nomcom is ever composed of one gender. Like the limit by organization, this is to avoid the appearance of improper bias in choosing IETF leadership: a random draw is representative over many years, but in any single year it can seat a committee drawn from one gender.

This document does not address the nomcom's comportment once seated. A future revision might extend [RFC8713] with conduct standards for non-discrimination, personal conflict of interest, and consistent candidate evaluation, drawing on precedent such as ICANN's Nominating Committee Code of Conduct [ICANNCoC].

# Conventions and Definitions

{::boilerplate bcp14-tagged}

"Dominant gender" means the gender named as such by the nomcom chair in the call for volunteers, based on the composition of past nomcoms. At the time of writing it is men.

"General pool" means all eligible volunteers in a given year, including those in the opt-in pool. "Opt-in pool" means the pool defined in Section 4.1.

# Gender Representation in the IETF Nomcom

[RFC8713] already limits nomcom representation by organization: Section 4.17 provides that no more than two voting volunteers may share the same primary affiliation. This safeguard addresses one axis of nomcom capture and imbalance, but it does not address gender.

The IETF considers influence and weaknesses in nomcom selection in [RFC8713]. The rationale for the two-per-organization limit, as documented in the "Oral Tradition" appendix of [RFC8713], is to avoid the appearance of improper bias in choosing IETF leadership: rather than defining precise rules for what counts as "affiliation," the IETF community relies on the honor and integrity of participants to make the limit work in practice. Likewise, gender diversity in IETF leadership should be considered a community strengthening exercise insofar as gender diversity has been shown to lead to more productivity, creativity and reinforces a culture of respect and value for all participants. If we consider the nomcom as a "team", it will itself benefit from having more gender diversity among its voting members.

The nomcom itself conventionally asks candidates some form of the question, 'Describe your perspective on what diversity should mean for the IETF, and the degree to which existing IETF participation meets those expectations. What have you done in the past to encourage participation by those who might otherwise not have considered engaging with the IETF?' implying diversity is regarded in the IETF.

Five of the twelve nomcoms seated between 2015 and 2026 had no women among their voting members. To address gender representation in the IETF nomcom, at a minimum we can ensure that all voting members are not of the same gender. All attempts to ensure gender representation in the nomcom should include:
    a. increase participation in the community from women and non-binary individuals so that the eligible pool is more gender diverse.
    b. encourage eligible women and non-binary members of the community to accept selection to the nomcom.

While the IETF does not routinely confirm the gender of volunteers, it measures gender diversity through its annual community survey, in which women were under 10% of respondents in 2025 [IETFSurvey2025]. The IETF LLC commissioned an independent report on the experience of women participating in the IETF [Kaeo2023], and IETF leadership has stated its commitment to gender diversity and reported on steps taken in response [IESGFollowUp2024].

# Suggested Remedy

Section 4.17 of [RFC8713] constrains nomcom composition by primary affiliation. This document adds a second composition constraint, applied at the same point in the process, in the form of a guaranteed minimum number of seats for volunteers in an opt-in pool.

## Opt-in Pool

The nomcom chair MUST name the dominant gender, as defined in Section 2, in the call for volunteers.

An eligible volunteer ([RFC8713], as updated by [RFC9389]) MAY opt into a self-declared pool of volunteers who do not identify as members of the dominant gender (the "opt-in pool"). The opt-in pool is defined by self-identification alone. Membership in the opt-in pool is the only information disclosed. Every volunteer in the opt-in pool is also in the general pool.

A volunteer who opts in by mistake MAY correct the declaration at any time before the general pool list is published. Once published, opt-in pool membership is fixed, consistent with the verifiability requirement in Section 4.3.

## Guaranteed Seats

Let p be the size of the opt-in pool. The number of guaranteed seats is r = min(5, p): five, or the whole opt-in pool if it has fewer than five members.

If p is 0, no seats are guaranteed, and the IETF community MUST be notified that all voting volunteers may share one gender that year for this reason.

## Selection

A single [RFC3797] selection MUST be run over the published general pool list, which MUST show which volunteers are in the opt-in pool.

Volunteers are seated in list order, subject to the limit in Section 4.17 of [RFC8713], with one exception: once the number of unfilled seats equals the number of guaranteed seats not yet held by opt-in pool members, only opt-in pool members are seated. If no opt-in pool member who can be seated remains on the list, the exception lapses and the remaining seats are filled in list order, starting with any volunteers it passed over.

For example, take a nomcom with eleven voting seats, an opt-in pool of one volunteer (so r = min(5, 1) = 1), and a published general pool list, in draw order, that begins V1 through V10 and then, in position 15, the single opt-in pool member Z. Seats 1 through 10 are filled by V1 through V10 in order; no exception applies yet, since the one guaranteed seat is not yet held and more than one seat remains unfilled. Before the eleventh seat, one seat is unfilled and one guaranteed seat is not yet held, so the exception applies: V11 through V14 are passed over, and Z is seated in the eleventh seat.

If a seated volunteer is later replaced under [RFC8713], the same rule applies to the choice of replacement.

## Rationale

The selection is a single [RFC3797] draw over a list published in advance. Opt-in pool membership is part of that list, so no seat depends on information absent from it and the outcome remains independently verifiable. A rule that depended on volunteers' genders would not have this property: it would either break verifiability, if that data is private, or force disclosure.

The guarantee is a minimum, not an addition: it takes effect only when a plain draw would seat fewer than r opt-in pool members, and otherwise the outcome is that of the plain draw. As the opt-in pool approaches half of all volunteers the guarantee almost never takes effect (about 5% of draws at parity), so nothing needs to change if a different gender becomes dominant.

When the pool is skewed, the guarantee is deliberately super-proportional. The literature on tokenism finds that members of a small minority in a deliberative body carry a visibility burden and are treated as representatives of a category rather than as individuals [Kanter1977]. Studies of corporate boards report that this changes at around three members ([KonradKramerErkut2008], [Torchia2011]). These are studies of standing boards, not selection committees, and a fixed threshold is contested [ChildsKrook2008]; while three bears out in the evidence as a floor below which the effect is most acute, we set five as the cap because it approaches parity for a nomcom with eleven seats. Volunteers seated under the guarantee serve as individuals and do not represent a gender.

Stratification by declared characteristics is established practice in bodies constituted by lot [OECD2020], and compositional constraints are the norm rather than the exception among comparable nominating bodies: ICANN's Nominating Committee is constituted from designated seats [ICANNBylaws].

This section would update Sections 4.16 and 4.17 of [RFC8713]. Section 4.16 calls a selection method fair "if each eligible volunteer is equally likely to be selected". The affiliation limit already qualifies that definition, and this document would qualify it further: volunteers remain equally likely to be selected within the opt-in pool and within the rest of the general pool. The method remains unbiased in the sense of Section 4.16: once the list is published, no one can influence the outcome.

# Privacy Considerations

Serving on the nomcom is voluntary. Public disclosure of one's gender and pronouns in the IETF Datatracker should remain voluntary. Disclosure of one's gender during meeting registration for the purposes of tracking community diversity should remain voluntary and non-public.

Under Section 4, no volunteer is asked to state a gender, and no gender is inferred from pronouns used in mailing list discussion, recorded meetings, or the Datatracker. The only disclosure is opt-in pool membership.

Because [RFC3797] verifiability requires the list to be published in advance, membership in the opt-in pool is public. It stays public: the list is archived, and membership can be compiled across years. Volunteers MUST be told this at the point of declaration. For some volunteers, opt-in pool membership may reveal more about them than they have otherwise made public. Gender data collected for community measurement, whether at meeting registration or in the Datatracker, MUST NOT be used to construct the opt-in pool.

# Security Considerations

Self-declaration is not verified. The challenge period in Section 4.17 of [RFC8713] still applies to the selection, but a challenge cannot rest on a volunteer's declaration. As with the affiliation limit, the mechanism relies on the honour and integrity of participants rather than on precise rules.

When the opt-in pool is small, its members are far more likely to be seated than other volunteers, and when it has five or fewer members all of them are seated, subject to the affiliation limit. This is an incentive to declare, including for organizations seeking seats, though the affiliation limit bounds what any one organization can gain.

A small opt-in pool may also mean the same volunteers serve repeatedly. Sitting nomcom members cannot be considered for the positions that nomcom fills ([RFC8713], Section 5.11), so frequent service has a cost for those volunteers and for the pool of candidates.

# IANA Considerations

This document has no IANA actions.

--- back

# Acknowledgments

Thanks to Martin Thomson and Suresh Krishnan for informed initial thoughts on bringing this idea to the community. The selection rule in Section 4.3 follows a suggestion by Joel Halpern. Thanks to Brian Carpenter, Stephen Farrell, Bron Gondwana, Russ Housley, Christian Huitema, Ted Lemon, John Levine, S. Moonesamy, Mark Nottingham, Michael Richardson, Rich Salz, Michael StJohns, Andrew Sullivan and Rob Wilton for review and comments on the eligibility-discuss list.

# Changes
{:removeinrfc}

Since -05:

- Raised the guaranteed-seat cap from three to five (r = min(5, p)).
- Made the nomcom chair's duty to name the dominant gender in the call for volunteers an explicit requirement in Section 4.1.
- Added a procedure for correcting an erroneous opt-in declaration before the general pool list is published.
- Added a worked example of the selection procedure.

Since -04:

- Replaced the two-draw reserved-seat formula with a single draw and a guaranteed minimum of three seats, which takes effect only when a plain draw would seat fewer.
- Volunteers in the opt-in pool are always in the general pool; "mixed gender pool" is no longer used.
- The nomcom chair names the dominant gender in the call for volunteers.
- Replaced the hiring-literature rationale in the Introduction with the rationale [RFC8713] gives for the affiliation limit.
- Sourced the statements in Section 3 about measuring gender diversity.
- Qualified the evidence for a minimum of three.
- Noted that the mechanism would also update the fairness definition in Section 4.16 of [RFC8713].
- Expanded Privacy and Security Considerations: permanence of the published list, challenges, the incentive to declare, repeat service.
