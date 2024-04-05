# Registries of Good Practice project<!-- omit in toc -->

<!-- note that this table of contents is being managed using the 'Markdown All in One' extension in VS Code -->

- [Introduction](#introduction)
  - [What is a registry?](#what-is-a-registry)
- [Goals](#goals)
- [Communication and Collaboration](#communication-and-collaboration)
  - [Updates (reverse chronological order)](#updates-reverse-chronological-order)
- [Principles](#principles)
  - [No New Registries](#no-new-registries)
  - [Empower Others](#empower-others)
  - [Be Realistic](#be-realistic)
  - [Be Useful](#be-useful)
  - [Iterate Early, Often, and in the Open](#iterate-early-often-and-in-the-open)
  - [Build on the Work of Others](#build-on-the-work-of-others)
  - [Make it Easy to Maintain](#make-it-easy-to-maintain)
- [User Needs](#user-needs)
  - [Roles](#roles)
  - [Journeys and Needs](#journeys-and-needs)
- [Licensing \& Copyright](#licensing--copyright)
  - [Source Data \& Aggregate Data](#source-data--aggregate-data)
  - [Source Code](#source-code)
  - [Documentation \& Publications](#documentation--publications)


## Introduction

The "Registries of Good Practice" Project is a collaboration between the Digital Preservation Coalition (DPC) and Yale University Library (YUL). The [formal announcement can be found here](https://www.dpconline.org/news/registries-of-good-practice). The project will explore and develop different approaches to analyze, collate, present and, most importantly, make discoverable the many existing registries and collections of digital preservation good practice.

- The high-level project plan and progress is [openly accessible as a GitHub project](https://github.com/orgs/digipres/projects/2/views/1).
- The offical DPC project page is [here](https://www.dpconline.org/digipres/collaborative-projects/registries-of-good-practice).


### What is a registry?

The idea of a 'technical registry' is a bit of jargon with a long history in the field of digital preservation. The general idea was already well established at _iPRES 2004_:

> Cooperation has always been essential in the digital preservation community regarding knowledge exchange and collaboration in research activities. As initiatives increasingly turn to implementation, cooperation also gains practical significance. Initiatives embark on collaboratively building services that are required by various preservation systems.
This presentation addresses file format registries. The preservation community jointly calls for a register that identifies and documents file formats, to come to terms with the myriad of different file formats. Activities towards building a file format registry are emerging, as already some preservation initiatives rely on such a future service in their current approaches.
>
> From [File format registries - a global infrastructure for local persistence](https://phaidra.univie.ac.at/detail/o:295015)

An earlier 2003 publication suggests this terminology is inherited from the [IANA Media Type Registry](https://www.iana.org/assignments/media-types/): 

> "The current MIME Media Types registry does not provide sufficient granularity of format typing or sufficient standardized representation information about formats."
>
> From [Towards a global digital format registry](https://archive.ifla.org/IV/ifla69/papers/128e-Abrams_Seaman.pdf)

But the idea of registries of reference information goes back much further, as indicated in this [GOV.UK publication about what it takes to be a register](https://gds.blog.gov.uk/2015/10/13/the-characteristics-of-a-register/) and by the venerable registries referenced from there (like the [UK Land Registry](https://www.gov.uk/government/organisations/land-registry)).

But for the purposes of this project, we're not interpreting this too strictly. Perhaps in the past we have focussed too much on _the registry we need to build_ and rushed too far ahead. We want to focus on the community of digital preservation practitioners, and understand their needs and capabilities. We want to learn from the registries (and other information sources) that have been well-used and have stood the test of time. Anything that people can use to improve how they do digital preservation is in scope.

## Goals

To explore the following issues:

- What is the current ‘landscape’ of active and openly-accessible registries of things like format, software, tools and workflows, and how are they being used in practice? How do vendors integrate and use them? How does that compare with what practitioners do with them, and how registry maintainers build them? What works well? What’s not so good? How could things be improved?
- How do practitioners work towards ‘good practice’, and could ‘registries of practice’ help? What methods do people use to improve their practices? How do we build on the work of others, and avoid reinventing the wheel? What are the good sources of information about practical digital preservation? How useful are the iPres proceedings in this regard? How can we improve the discoverability of these kinds of resources?
- What are the common practices used to build and maintain technical registries themselves? What are the constraints we’re operating under? How does that affect the kind of approaches we can take? What kinds of contributions are welcome, and through which channels?

The intended outcomes are:

- An established [_Preservation Registries Special Interest Group (PR-SIG)_](https://www.dpconline.org/digipres/pr-sig) where people can come together to talk about digital preservation registries.
- A range of formal and informal publications documenting the current state of our registries.
- New tools and services to help us improve our practices and maintain our registries, built with long-term maintenance and sustainability in mind.


## Communication and Collaboration

You can get involved with this project by:

- Joining the [Preservation Registries Special Interest Group](https://www.dpconline.org/digipres/pr-sig).
- Looking out for project updates via [the DPC website](https://www.dpconline.org/digipres/tags/registries-of-good-practice) and DPC social media channels ([Mastodon](https://digipres.club/@dpc_chat), [Twitter/X](https://twitter.com/dpc_chat), [LinkedIn](https://www.linkedin.com/company/digital-preservation-coalition/)).
- Looking out for blogs on technical details via [Andy Jackson's personal blog](https://anjackson.net/tags/digital-preservation/) and his social media channels ([Mastodon](https://digipres.club/@anj), [Twitter/X](https://twitter.com/anjacks0n), [LinkedIn](https://www.linkedin.com/in/andrewnjackson/)).
- Checking the aforementioned [GitHub project board](https://github.com/orgs/digipres/projects/2/views/1).
- Watching this GitHub repository.
- Creating and commenting on GitHub issues, submitting pull requests.


### Updates (reverse chronological order)

- 2024-02-23 - DPC Blog: [Goals & Principles](https://www.dpconline.org/blog/registries-of-practice-goals-principles)
- 2024-02-16 - Formal project annoucement: [New project launched to help practitioners discover digital preservation resources](https://www.dpconline.org/news/registries-of-good-practice)


## Principles

While it’s not yet clear what the outputs of this project will be, we feel it’s important to establish some of the principles that we will use to guide our work. This isn’t an exhaustive list, and these rules may need to be refined over time. But we’ve seen a lot of registry projects come and go, and this is our attempt to articulate what we’ve learned from that, and how that will shape our work.

### No New Registries

We’ve been involved in digital preservation for a long time, and have seen a lot of short-term project funding spent on grand visions of what preservation registries could be. While those research projects have been very valuable in helping us understand what might be possible, very few have successfully made the transition from prototype to production. We believe most of these projects underestimated the barriers to adoption, the effort required to fill these registries, and the difficulties involved in managing data over time (especially around maintaining parallel [‘forks’](https://en.wikipedia.org/wiki/Fork_(software_development) "External Link (opens in new window): https://en.wikipedia.org/wiki/Fork_(software_development)") of curated datasets).

This project is not about ‘owning’ or ‘solving’ the registry problem. Maintaining registries of technical information is difficult work and requires a commitment of time and skills that are in short supply across our sector. It is very important to us that whatever we do will respectfully highlight the long-term and ongoing efforts that people and organisations have put into the registries we all depend on.

### Empower Others

This project will deliver one full-time person of effort over two short years, so how do we maximise the long-term returns from this brief pulse of funding?  We believe that, rather than replicating the kind of work that is already being done, it will be better for everyone if we find ways of contributing that help empower the existing communities in and around preservation registries. Therefore, we will start by building a deeper understanding of ‘the registries problem’ from a practical point of view, and look for ways to help.

Can we build tools that will help registry maintainers work more quickly and confidently? Can we provide resources that will help grow the community of people who use and contribute to registries? Can we make it easier to learn from the past and avoid common pitfalls or reinvented wheels? How can we be a force-multiplier for good practice?

### Be Realistic

While we want to be ambitious and try new things, we also have to be realistic about the limitations of this project: it’s one full-time equivalent person for two years. We believe we can make a significant contribution to the practice of digital preservation, but this will require clarity of purpose and focussed prioritisation.

Similarly, we understand there are many pressures and complicating factors that mean the teams running our registries are already overstretched. We will aim to support those teams, and to avoid encouraging unreasonable demands or expectations.

### Be Useful

This might sound obvious, but over the years there have been a lot of “if you build it they will come” digital preservation projects that foundered because practitioners were unable to integrate those products into their work. Whatever we build must be driven by genuine user need and must work with or around the practical barriers that practitioners, registry maintainers and vendors face.

This is where wider community feedback is critically important. We can’t tell if we’re succeeding unless you let us know whether what we’re doing is actually useful!

### Iterate Early, Often, and in the Open

It is not clear what the shared needs and common barriers are for the digital preservation community, and safe spaces for discussion are only part of the solution. To ensure we’re on the right track, any tools or resources we develop must be rapidly and openly iterated. Broadly speaking, rather than gathering formal requirements, we will focus on generating experimental prototypes to probe the issues and provoke discussion. The biggest benefit of time-limited project funding is the opportunity to fail, and to learn from the failures. 

### Build on the Work of Others

There is so much great work out there, and we want to learn from it, build on it, and shout about it from the rooftops. Not just the preservation registries, but also many different resources and tools from a range of institutions and individuals. Publicising the good work of others will be critical to our success.

Our biggest fear is accidentally leaving someone out! There’s a lot going on and the person doing most of the work on this project has been heavily focussed on web archiving in recent years.  Please don’t be offended if we seem to miss you out, and please don’t assume anything is obvious to us! Please get in touch!

### Make it Easy to Maintain

While we hope to be able to continue at least some of this work beyond this initial two years, there are no guarantees. Therefore, it is critical that the output of the project is something that the DPC and the wider digital preservation community can maintain.

At first, while exploring and experimenting, we can relax this constraint a little, but it will always be borne in mind that the final results cannot be something that requires a lot of complex infrastructure or frequent maintenance. Quite what this means is also unclear at this point, but it’s safe to say it’s more like [minimal computing](https://sas-dhrh.github.io/dhcc-toolkit/toolkit/minimal-computing.html "External Link (opens in new window): https://sas-dhrh.github.io/dhcc-toolkit/toolkit/minimal-computing.html") and less like ChatGPT.

## User Needs

```warning
This section is a very rough early draft.
```

We want the outputs of the project to be useful, so we want to focus clearly on user needs. This is in part based on [the GOV.UK advice on user research](https://www.gov.uk/service-manual/user-research/start-by-learning-user-needs), with the possibility of future [Wardley mapping](https://blog.gardeviance.org/2016/04/on-user-needs-and-listening-to-customers.html) of the [technology landscape](https://learnwardleymapping.com/landscape/) being kept in mind.

Based on our previous experience, we're avoiding leaping immediately to user _requirements_. We have found that being asked to enumerate requirements up front tends to get lost in the details and overloaded with discordant expectations and unvoiced assumptions. We want to start by thinking about [needs and capabilities in context](https://learnwardleymapping.com/2021/01/12/5-ways-to-represent-user-needs-on-a-wardley-map/), before getting into user stories as ways of framing requirements.

### Roles

To make sure the needs are clear, it's necessary to make sure we clearly identify the different user roles. Note that individual users may act in more than one of these roles.

- **Patrons**
  - The people who we are doing all this preservation for, now and in the future.
  - In OAIS terms, the _Consumers_ of the material that is in the _Archive_. 
- **Creators**
  - The people who create what we preserve.
  - This includes any people who are in some sense 'in' what we preserve. e.g. people's information, or stories, or data. 
  - In OAIS terms, roughly corresponds to the _Producers_ of the material that goes into the _Archive_, excepting that OAIS doesn't explicitly consider the people 'in' the _Archive_.
- **Custodians**
  - Whoever has overall responsibility for what is being preserved.
  - Whoever has decision-making authority over how things are done.
  - In OAIS terms, the _Management_, who defined the policies the _Archive_ operates under.
- **Practitioners**
  - Someone who does the work involved in digital preservation. Handling files, ingesting into repository systems, managing replicas, facilitating access, etc.
  - They act according to the policies established by the _Custodian_.
  - In OAIS terms, they are the _Archive_. Or at least, the human part of the _Archive_. But OAIS doesn't draw that distinction.
- **Registry Contributors**
  - People who find relevant information and do the analysis required to prepare it for inclusion in a registry.
- **Registry Maintainers**
  - The people who run the long-term registry infrastructure we depend on.
  - Works with internal and external _Registry Contributors_ to add and update the contents of the registry.
- **Tool Maintainers**
  - People who maintain the tools that _Practitioners_ and _Platform Providers_ depend on.
  - Often open source projects.
- **Platform Providers**
  - People that provide services and systems to help do the work of digital preservation.
  - Often involves re-packaging the registries from the _Registry Maintainers_ and the tools from the _Tool Maintainers_.
  - May be open source or proprietary commercial vendors, in-house teams, or a mixture of both.
- **Researcher**
  - The people researching new theories and practices of digital preservation.
- **Funders**
  - Organisations that fund digital preservation work.
  - Should perhaps distinguish between ongoing versus time-limited project funding?


### Journeys and Needs

We are currently working on understanding the user journeys and needs relating to practice and registries in digital preservation. At this stage, this is focusing on how things work at Yale University Libraries.  We will share what we find, and look to work with other _Practitioners_ to refine and grow the results of this work.

In parallel with that work, we are building prototypes exploring ways of answering some of the questions we think are likely to come up:

- What can we find out about _File Format X_?
- Who else has worked with _File Format X_, and what did they do?
- Who else has worked on _DigiPres Problem Y_ and how did it go?
- What tools can I use to do _DigiPres Action Z_?

The work on user journeys should help establish the relevant of these questions, and where the  _Practitioners_ are when they start asking these questions...

- Asking in search engines?
- Starting with a file?
- Starting from a repository system?
- Starting with a script?
- ...


## Licensing & Copyright

### Source Data & Aggregate Data

We gather data from multiple sources for indexing, but the original data remains under the creators' terms of publication.  Databases or other consumptive data sets remain bound by the terms of the original sources in each data set. Index data that is considered purely factual and non-consumptive _may_ be made available under CC0 terms.

Note that these datasets are intended for research and analysis. They are not intended for re-use as part of an automated process (e.g. format identification), and are not suitable for using in that way.  The aim of this project is to surface gaps, differences and conflicts between registries, so that interested parties can understand and resolve those tensions. Embedding these aggregated datasets in any automated process is likely to lead to inconsistent and unpredictable outcomes.

### Source Code

The project source code is not intended nor suitable for embedding in closed or proprietary systems. As such, the default license for source code will be the AGPL-3.0. 

If the project ends up creating tools or libraries that would be suitable for re-use, they will be distilled into separate repositories and made available under the terms of the MIT license. But in preference to that, wherever possible, the project will contribute to existing open source projects. Contributions to any third-party tools or libraries will be made under terms appropriate to that tool or library.

### Documentation & Publications

Documentation published by the project will be made available under the terms of the AGPL-3.0 or CC-BY depending on context. Formal publications will be made available under CC-BY terms.