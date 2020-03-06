---
layout: page
title: Contributing
permalink: /contributing/
---
### How

1. Say something via email: [contact@pubtest.me](mailto:contact@pubtest.me)
2. Hit us up on Twitter via [@pubtestme][pubtestme-twitter]
3. Work on [the wiki][pubtestme-wiki]
4. [Open an issue][pubtestme-new-issue] against the site
5. Develop a change and [open a pull-request][pubtestme-new-pull-req]

The top of the list is the easiest and the bottom requires the most effort and
experience. Working on the wiki, creating an issue or opening a pull-request
all [require a (free) GitHub account][github-join] ([what is GitHub?][github]).

[github]: https://github.com/
[github-join]: https://github.com/join
[pubtestme-new-issue]: https://github.com/pubtestme/pubtestme.github.io/issues/new
[pubtestme-new-pull-req]: https://github.com/pubtestme/pubtestme.github.io/compare
[pubtestme-twitter]: https://twitter.com/pubtestme
[pubtestme-wiki]: https://github.com/pubtestme/pubtestme.github.io/wiki

#### The Wiki

[The wiki][pubtestme-wiki] is not the main site, rather it's a staging area - a
place to quickly jot down links or to collaborate on material that isn't yet
fully formed. The aim is to keep it informal and low friction, but occasionally
we may have to do some housekeeping to keep it sensible.

Try to avoid creating wiki pages for incidents that are already present on the
main site - if there are problems with an existing page use [one of the other
options for contributing](#how) instead. Similarly, once content is well-formed
enough to be migrated to the main site its wiki page will eventually be
removed.

### What

1. Identifying or fixing bad content
2. Contributing a report or news article
3. Contributing an incident

Contributions identifying bad content should contain a short statement of the
problem, include a link to the incident at hand, and ideally suggest a
resolution.

Contributions of new incidents should be self contained: There must be a summary of
the activity in question, and at least one of either a formal report or a news
headline to anchor the activity in reality and time. New posts can be
contributed in both issue and pull-request forms. If the content meets the
[material criteria](#material-criteria) then site administrators will implement
the site changes and attribute them to the issue owner.

Contributions via pull-requests must adhere to the [licensing and legal
requirements outlined below](#licensing).

[pubtestme-repo]: https://github.com/pubtestme/pubtestme.github.io/

### Content
#### Material Criteria

Whether an activity is against public interest is measured by meeting one or
more of the following criteria:

1. A public institution has handed down a report that demonstrates an
activity failed to meet legal obligations or required standards. For example,
reports published by the [Australian National Audit Office (ANAO)][anao]

2. An activity that has been reported to disregard advice from relevant public
servants, research or scientific organisations to the detriment of the public

3. Activities reported to [breach ministerial standards as set out by the Department of
the Prime Minister and Cabinet][pmc-ministerial-standards]

4. Activities reported to breach the constitution, federal or state law.

[anao]: https://www.anao.gov.au/
[pmc-ministerial-standards]: https://www.pmc.gov.au/resource-centre/government/statement-ministerial-standards

#### Acceptable, preferred content

1. Journal publications, Australian Public Service reports, peer-reviewed
primary source material backing claims
2. News articles from reputable sources
3. Public statements, audio and video material of unelected responsible public servants
4. For the purpose of clarification of position, political party media releases

#### Unacceptable content

* Opinion or editorial news articles
* Articles not linking to acceptable, preferred content as supporting evidence

#### Useful Resources

* [Analysis & Policy Observatory][apo] ([RSS][apo-rss])
* [Australian National Audit Office][anao]
* [Commonwealth Ombudsman][commonwealth-ombudsman]
* [Grant Connect][grant-connect]
* [Hansard][hansard]
* [House of Representatives Committee Transcripts][hor-committee-transcripts]
* [Paliamentary Business][parliamentary-business]
* [Parlwork][parlwork]
* [Register of Members' Interests][members-interests]
* [Senate Committee Transcripts][senate-committee-transcripts]
* [Support for Businesses in Australia][business-gov-au]

[apo]: https://apo.org.au/
[apo-rss]: https://apo.org.au/rss/all
[business-gov-au]: https://www.business.gov.au/
[commonwealth-ombudsman]: https://www.ombudsman.gov.au/
[grant-connect]: https://www.grants.gov.au/?event=public.home
[hansard]: https://www.aph.gov.au/Parliamentary_Business/Hansard
[hor-committee-transcripts]: http://parlinfo.aph.gov.au/parlInfo/search/summary/summary.w3p;adv=yes;orderBy=priority,doc_date-rev;query=Dataset%3AcomRep;resCount=Default
[members-interests]: https://www.aph.gov.au/Senators_and_Members/Members/Register
[parliamentary-business]: https://www.aph.gov.au/Parliamentary_Business
[parlwork]: https://parlwork.aph.gov.au/
[senate-committee-transcripts]: http://parlinfo.aph.gov.au/parlInfo/search/summary/summary.w3p;adv=yes;orderBy=customrank;page=0;query=Dataset%3AcomSen,estimate;resCount=Default


### Licensing
#### Content License

"Content" covers any data that is acted upon by code that is not itself code.
Content may take the form of free-form text and elements of attribution as
covered by [Acceptable, preferred
content](#acceptable-preferred-content).

Referenced content is subject to its authors' license and redistribution
policies.

All content is licensed under Creative Commons [Attribution-ShareAlike 4.0
International (CC BY-SA 4.0)](/LICENSE.CC-BY-SA-4.0.txt).

#### Code License

"Code" covers any instructions to the site layout or rendering engines. This
may take the form of basic web technologies like HTML, CSS and Javascript, or
template control instructions.

All contributed code must be licensed under the [MIT
license](/LICENSE.MIT.txt).

Code source files must contain a SPDX marker indicating the specified license
as well as copyright information for significant contributions.

#### Developer Certificate of Origin

All contributions must be in the form of a patch series or pull-request with
each commit message containing a Signed-off-by line indicating acknowledgement
of the [Developer Certificate of Origin](https://developercertificate.org/).

### Contributions and Trust Relationships

Contributors and contributions adhering to the [Acceptable, preferred
content](#markdown-acceptable-preferred-content) guidelines are welcomed.
However, contributions are accepted at the discretion of site administrators
and may be rejected on grounds of trust or other subjective properties. The
content must be objective, but the administrators' relationship with
contributors may not be.
