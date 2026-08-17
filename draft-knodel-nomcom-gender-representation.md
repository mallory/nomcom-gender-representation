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
  Bohnet2016:
    target: https://hbr.org/2016/04/how-to-take-the-bias-out-of-interviews
    title: How to Take the Bias Out of Interviews
    author:
      ins: I. Bohnet
    date: 2016
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

This document extends the existing limit on nomcom representation by organization ([RFC8713], Section 4.17) so that not all voting members of the IETF Nominating Committee (nomcom) belong to the same gender.

--- middle

# Introduction

The nomcom is, in every functional sense, a hiring committee: it solicits candidates, reviews their qualifications, interviews them, and selects who will fill the IETF's most senior leadership roles.

This document extends [RFC8713]'s limit on nomcom representation by organization to ensure no nomcom is ever composed of one gender. This is because the literature supports the claims that lack of gender diversity in hiring teams reinforces under representation of gender minorities in leadership positions and that lack of gender diversity in leadership perpetuates gender discrimination [Bohnet2016].

This document does not address the nomcom's comportment once seated. A future revision might extend [RFC8713] with conduct standards for non-discrimination, personal conflict of interest, and consistent candidate evaluation, drawing on precedent such as ICANN's Nominating Committee Code of Conduct [ICANNCoC].

# Conventions and Definitions

{::boilerplate bcp14-tagged}

"Dominant gender" means the gender held by the majority of eligible nomcom volunteers in a given year. "Opt-in pool" means the pool defined in Section 4.1.

# Gender Representation in the IETF Nomcom

[RFC8713] already limits nomcom representation by organization: Section 4.17 provides that no more than two voting volunteers may share the same primary affiliation. This safeguard addresses one axis of nomcom capture and imbalance, but it does not address gender.

The IETF considers influence and weaknesses in nomcom selection in [RFC8713]. The rationale for the two-per-organization limit, as documented in the "Oral Tradition" appendix of [RFC8713], is to avoid the appearance of improper bias in choosing IETF leadership: rather than defining precise rules for what counts as "affiliation," the IETF community relies on the honor and integrity of participants to make the limit work in practice. Likewise, gender diversity in IETF leadership should be considered a community strengthening exercise insofar as gender diversity has been shown to lead to more productivity, creativity and reinforces a culture of respect and value for all participants. If we consider the nomcom as a "team", it will itself benefit from having more gender diversity among its voting members.

The nomcom itself conventionally asks candidates some form of the question, 'Describe your perspective on what diversity should mean for the IETF, and the degree to which existing IETF participation meets those expectations. What have you done in the past to encourage participation by those who might otherwise not have considered engaging with the IETF?' implying diversity is regarded in the IETF.

To address gender representation in the IETF nomcom, at a minimum we can ensure that all voting members are not of the same gender. All attempts to ensure gender representation in the nomcom should include:
    a. increase participation in the community from women and non-binary individuals so that the eligible pool is more gender diverse.
    b. encourage eligible women and non-binary members of the community to accept selection to the nomcom.

While the IETF does not routinely confirm the gender of volunteers, we have committed to improving gender diversity in the community by way of measuring it and identifying concrete steps to mitigate imbalance.

# Suggested Remedy

Section 4.17 of [RFC8713] constrains nomcom composition by primary affiliation. This document adds a second composition constraint, applied at the same point in the process, in the form of a stratified selection over two pools, a mixed gender pool and an opt-in non-dominant genders pool.

## Opt-in Pool

An eligible volunteer MAY opt into a self-declared pool of volunteers who do not identify as members of the dominant gender (the "opt-in pool"). Membership in the opt-in pool is the only information disclosed. Volunteers in the opt-in pool may also opt into the mixed gender pool.

## Reserved Seats

Let n be the number of voting volunteer slots, p the size of the opt-in pool, and t the size of the mixed gender pool. The number of reserved seats r is determined as follows:

- If p is 0, no seats are reserved, and the IETF community MUST be notified that all n voting volunteers may share one gender that year for this reason.
- Otherwise, r = min(p, max(3, min(floor(n/2), floor(n * p / t)))).

## Selection

The r reserved seats MUST be selected first, by an [RFC3797] selection over the published opt-in pool list. The remaining n - r seats MUST then be selected by a second [RFC3797] selection over the general pool, excluding volunteers already selected. Both selections MAY use the same publicly announced seed material and be conducted as a single ceremony. The limit in Section 4.17 of [RFC8713] continues to apply across both selections.

## Rationale

Each selection is an ordinary [RFC3797] draw over a list published in advance, and no seat is conditional on information absent from that list, so every seat remains independently verifiable. A rule that skips candidates mid-draw does not have this property: it requires volunteers' genders to be known at selection time, which either breaks verifiability if that data is private or forces disclosure if it is not.

The proportional cap ensures the mechanism never produces a composition the volunteer pool does not already support. It removes the variance of a flat draw rather than adding preference. The floor of three is deliberately super-proportional when the pool is skewed. The literature on tokenism finds that a lone minority member of a deliberative body carries a visibility burden and is treated as a category representative rather than as an individual [Kanter1977], and that this shifts at around three members [KonradKramerErkut2008] [Torchia2011]. 

Stratified selection over declared strata is established practice in bodies constituted by lot [OECD2020], and compositional constraints are the norm rather than the exception among comparable nominating bodies: ICANN's Nominating Committee is constituted from designated seats [ICANNBylaws].

This section would update Section 4.17 of [RFC8713].

# Privacy Considerations

Serving on the nomcom is voluntary. Public disclosure of one's gender and pronouns in the IETF Datatracker should remain voluntary. Disclosure of one's gender during meeting registration for the purposes of tracking communty diversity should remain voluntary and non-public.

Under Section 4, no volunteer is asked to state a gender, and no gender is inferred from pronouns used in mailing list discussion, recorded meetings, or the Datatracker. The only disclosure is opt-in pool membership.

Because [RFC3797] verifiability requires each pool to be published in advance, membership in the opt-in pool is public. Volunteers MUST be told this at the point of declaration. Gender data collected for community measurement, whether at meeting registration or in the Datatracker, MUST NOT be used to construct the opt-in pool.

# Security Considerations

Self-declaration is not verified. As with the affiliation limit in Section 4.17 of [RFC8713], the mechanism relies on the honour and integrity of participants rather than on precise rules.

# IANA Considerations

This document has no IANA actions.

--- back

# Acknowledgments

Thanks to Martin Thomson and Suresh Krishnan for informed initial thoughts on bringing this idea to the community.
