---
title: "Composition and Comportment of the IETF Nominating Committee"
abbrev: "nomcom-composition-comportment"
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
 - diversity
 - comportment
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
    organization: Center for Democracy and Technology
    email: mknodel@cdt.org

normative:

informative:

  RFC8713:
  RFC9389:
  Vervoe:
    target: https://vervoe.com/gender-discrimination-in-hiring-practices/
    title: Gender Discrimination in Hiring Practices
    author:
      org: Vervo
    date: 2022
  ICANNCoC:
    target: https://www.icann.org/resources/pages/nomcom2019-conduct-2018-12-07-en
    title: ICANN Nominating Committee Background Information and Code of Conduct
    author:
      org: ICANN
    date: 2018
  ICANNOP:
    target: https://www.icann.org/resources/pages/nomcom2021-operating-procedures-2021-02-02-en
    title: ICANN Nominating Committee (NomCom) Operating Procedures
    author:
      org: ICANN
    date: 2021
  Bohnet2016:
    target: https://hbr.org/2016/04/how-to-take-bias-out-of-interviews
    title: How to Take the Bias Out of Interviews
    author:
      ins: I. Bohnet
    date: 2016

--- abstract

This document addresses two complementary gaps in the operation of the IETF Nominating Committee (nomcom). First, it extends the existing limit on nomcom representation by organization ([RFC8713], Section 4.17) so that not all voting members belong to the same gender. Second, it proposes a comportment framework for nomcom members so that the nomcom conducts itself with the rigor and fairness expected of any committee that evaluates candidates for leadership roles.

--- middle

# Introduction

The nomcom is, in every functional sense, a hiring committee: it solicits candidates, reviews their qualifications, interviews them, and selects who will fill the IETF's most senior leadership roles. It is reasonable, then, to hold the nomcom to the standards expected of any hiring committee, both in who is qualified to sit on it (composition) and in how it conducts itself while doing this work (comportment).

This document extends RFC 8713 in two ways.

It extends the limit on nomcom representation by organization to ensure no noncom is ever composed of one gender. This is because the literature supports the claims that lack of gender diversity in hiring teams reinforces under representation of gender minorities in leadership positions and that lack of gender diversity in leadership perpetuates gender discrimination [Vervoe].  

It also adds additional considerations for the operation of the noncom by documenting conduct standards for non-discrimination, personal conflict of interest, and conformant evaluations, which are on par with today's industry standards.

# Composition of the IETF Nomcom

[RFC8713] already limits nomcom representation by organization: Section 4.17 provides that no more than two voting volunteers may share the same primary affiliation. This safeguard addresses one axis of nomcom capture and imbalance, but it does not address gender.

The IETF considers influence and weaknesses in nomcom selection in [RFC8713]. The rationale for the two-per-organization limit, as documented in the "Oral Tradition" appendix of [RFC8713], is to avoid the appearance of improper bias in choosing IETF leadership: rather than defining precise rules for what counts as "affiliation," the IETF community relies on the honor and integrity of participants to make the limit work in practice. Likewise, gender diversity in IETF leadership should be considered a community strengthening exercise insofar as gender diversity has been shown to lead to more productivity, creativity and reinforces a culture of respect and value for all participants. If we consider the nomcom as a "team", it will itself benefit from having more gender diversity among its voting members.

The nomcom itself conventionally asks candidates some form of the question, 'Describe your perspective on what diversity should mean for the IETF, and the degree to which existing IETF participation meets those expectations. What have you done in the past to encourage participation by those who might otherwise not have considered engaging with the IETF?' implying diversity is regarded in the IETF.

To address gender representation in the IETF nomcom, at a minimum we can ensure that all voting members are not of the same gender. All attempts to ensure gender representation in the nomcom should include:
    a. increase participation in the community from women and non-binary individuals so that the eligible pool is more gender diverse.
    b. encourage eligible women and non-binary members of the community to accept selection to the nomcom.

While the IETF does not routinely confirm the gender of volunteers, we have committed to improving gender diversity in the community by way of measuring it and identifying concrete steps to mitigate imbalance.

## Suggested Remedy for Composition

The “two-per-organisation limit” of Section 4.17 of [RFC8713] can easily be extended to ensure a nomcom consisting of no more than n-1 members from any one gender (where n is the number of available volunteer slots), requiring skips for the nth slot until a gender minority volunteer is chosen.

This assumes that for any given pool therein contains at least one gender minority volunteer. If there does not exist one gender minority volunteer in a given year's pool, this rule is withdrawn and the community should be notified of this reason that all ten nomcom volunteers will have the same gender that year.

This short remedy would update Section 4.17 of [RFC8713].

# Comportment of the IETF Nomcom

Composition governs who is eligible to sit on the nomcom. It does not govern how the nomcom conducts itself once seated: how it interviews candidates, how it weighs what it hears, and how individual members manage their own relationships to candidates. A nomcom that is well-composed but poorly conducted can still reproduce the same discrimination and imbalance that Section "Composition of the IETF Nomcom" is meant to address. This section proposes a comportment framework to close that gap.

The nomcom's function is functionally indistinguishable from that of a hiring committee: it defines a pool of eligible candidates, solicits statements of interest, conducts interviews or consultations, and selects among candidates for open leadership roles. Organizations that run hiring committees, and other Standards Development Organizations (SDOs) that run comparable nominating bodies, have converged on a small set of practices to keep that process fair [ICANNCoC]. The IETF's own nomcom rules already reflect some of this convergence: [RFC8713] Section 3.6 and Section 9 impose confidentiality on nomcom deliberations, and Section 5.7 permits recall of a disruptive or uncooperative member. What is currently missing is any explicit standard for non-discrimination, for personal (as opposed to organizational) conflicts of interest, and for how candidates are actually questioned and evaluated.

## Suggested Remedies for Comportment

To bring the nomcom's conduct in line with this precedent, [RFC8713] could be updated to add, alongside the existing confidentiality provisions of Section 3.6 and Section 9:

a. A non-discrimination clause obligating nomcom members not to discriminate against a candidate on the basis of gender or other protected characteristics, in questioning, deliberation, or selection.

b. A personal conflict-of-interest rule requiring a nomcom member to disclose to the chair any financial or personal relationship with a candidate that might affect, or reasonably be seen to affect, their evaluation of that candidate, and to recuse themselves from deliberation on that candidate. This closes a gap that the organizational affiliation limit of Section 4.17 does not reach.

c. A requirement that the nomcom chair, before interviews begin for a given seat, establish a common set of core questions and evaluation criteria to be put to every candidate for that seat, consistent with the evidence that structured interviews reduce bias [Bohnet2016].

# Privacy Considerations

Serving on the nomcom is voluntary. Public disclosure of one's gender and pronouns in the IETF Datatracker should remain voluntary. Disclosure of one's gender during meeting registration for the purposes of tracking communty diversity should remain voluntary and non-public.

The pronouns used for an eligible nomcom volunteer in conversation, mailing list discussion, recorded meeting videos and notes can be strong indicators of that volunteer's gender. However it is best practice to resolve any doubt by directly asking the volunteer whether they identify as a member of the dominant gender.

As part of nomcom processes that change as a result of this document's recommended remedy, the gender of eligible nomcom volunteers must not be publicly documented, and wherein this information is used to determine the pool, it must be kept private.

Personal conflict-of-interest disclosures made under the comportment remedy of this document, including the nature of a nomcom member's relationship to a candidate, are similarly sensitive. Such disclosures should be made only to the nomcom chair, treated with the same confidentiality already required of nomcom deliberations under Section 3.6 and Section 9 of [RFC8713], and not publicly documented.

# Security Considerations

There are no security considerations for this document.

# IANA Considerations

This document has no IANA actions.

--- back

# Acknowledgments

Thanks to Martin Thompson and Suresh Krishnan for informed initial thoughts on bringing this idea to the community.
