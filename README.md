# Tone

> [!IMPORTANT]
> Hello! Hi! Sup? While we are **100%** going to launch as an open source platform, we have decided to operate closed source until we get our geese in line. We have a tiny, dedicated team that is looking to grow. If you're interested in contributing, please introduce yourself by either joining our [Discord community](https://discord.com/invite/dfky8n7kFv) dropping a line at [dev@sone.works](mailto:dev@sone.works)

> [!NOTE]
> This is document is intended for current Tone contributors, see above to get involved.

## Table of Contents
- [Leads](#leads)
- [Onboarding](#onboarding)
- [Frequently Asked Questions](#frequently-asked-questions)
  - [What access do I need?](#faq-access)
  - [How are we organized?](#faq-organized)
  - [How do I pick up work?](#faq-work)
  - [How do I get something into production?](#faq-production)
  - [How do I work on _____? That seems really interesting to me.](#faq-how)
- [Noteable Resources](#noteable-resources)
  - [Quarternote](#quarternote)
  - [Tone's Web App](#web-app)
  - [Tone API Modules](#api-modules)
  - [Tone Frontend Modules](#frontend-modules)

## Leads
We have an open door policy and are friendly folk, please don't be afraid to reach out if you are stuck or have any general questions.
- **Dev**: Lon Beshiri (@lonbes)
- **UX**: Matthew Lewicki (@dogwood)

## Onboarding
If you haven't already, be sure to follow your platform's **Onboarding** steps.

- **Web**: [Sone Web Engineering Guide](https://github.com/sone-works/sone-dev-web/tree/main?tab=readme-ov-file#onboarding).

## Frequently Asked Questions

### What access do I need to get started?<a id="faq-access"></a>
While we try keep access requests to a minimal, there are a few you will need to get started:
- A Sone Github organization request
- Invited to the Tone Github team
- Invited to the Sone Notion

Please be sure to (nicely) annoy Lon for any unfulfilled access requests.

### How are we organized?<a id="faq-organized"></a>
We are currently spread over Discord (community), Github (code), Notion (work), and Figma (design).

Work typically operates on two-week sprints with a loose mid-point check in. Discord is our main method of communication and the `#tone-dev` channel being quickest way to get help.

### How do I pick up work?<a id="faq-work"></a>
Work is available in the Sone Notion, under Tone, in the Development board. While you're always free to make a fix or grab a task from the backlog, be sure to check in first to see if there's any beans that need grinding (work that needs to be done).

### How do I get something into production?<a id="faq-production"></a>
As most of our CI/CD is done through Github Actions, getting things into production is relatively painless. Open up a pull request with your work and tag the code owner. They should reach out/leave comments on the request, and once merged and released, your code should be out into the world.

### How do I work on _____? That seems really interesting to me.<a id="faq-how"></a>
We want you to work on _____!!! We cannot understand how much we want you to enjoy what you are working on, as it's exactly why we are doing this project. We get that everyone has a different preference for their cup of tea, and if you have something you want to work on, just reach out in the Discord and throw it out for discussion. It really is that simple.

## Noteable Resources

### Quarternote<a id="quarternote"></a>
Tone's design system and style guide. This repo contains Tone's design tokens, iconography, front-end components, and documentation.
- **Repo**: https://github.com/sone-works/tone-quarternote
- **Docs**: https://quarternote.sone.dev
- **Figma**: https://www.figma.com/design/IuNSqPEIv2h0rZqyj2dcjz/Tone-Design-Library?m=auto&t=hGcBy04V1SweDLna-6

### Tone's Web App<a id="web-app"></a>
This is Tone's main webapp built using the React framework Remix. This can be treated as a shell repository, as most of it's content is imported from external libraries.
- **Repo**: https://github.com/sone-works/tone-app-web
- **Production URL**: https://tone.audio

### Tone API Modules<a id="api-modules"></a>
A client/server agnostic library to interact with Tone's main APIs.
- **Repo**: https://github.com/sone-works/tone-api-modules

### Tone Frontend Modules<a id="frontend-modules"></a>
A frontend repository and library containing contexts, hooks, and utilities.
- **Repo**: https://github.com/sone-works/tone-frontend-modules
