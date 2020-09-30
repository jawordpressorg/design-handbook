# Global styles

Global styles extends the efforts of [Full Site Editing](https://make.wordpress.org/design/handbook/focuses/full-site-editing/) in bringing a higher level of customization to Gutenberg and WordPress. Together, these features enable users to have improved control over aesthetics and layouts beyond the context of single Pages and Posts.

This initiative adds an interface to apply styling when in site editing mode. The styling will initially be global but also be able to apply just to the document (e.g. a Page or a Post) or to a component itself. For example, styling an individual button, all buttons within a page, and/or all buttons across an entire site.

## Details

**Focus maintainers:** @itsjonq, @karmatosed

**Timeline:** estimated v1 for 5.5 (at least in the experimental flag)

**Tags:** [#global-styles](https://make.wordpress.org/design/tag/global-styles/)

**Tickets, Issues, and PRs:**

*   [GitHub project](https://github.com/WordPress/gutenberg/projects/40)
*   [Block styles development issue](https://github.com/WordPress/gutenberg/issues/19611)
*   [Site edit global styling interface](https://github.com/WordPress/gutenberg/issues/19255)
*   Related issues:
    *   [Color picker iterations](https://github.com/WordPress/gutenberg/issues/19785)

## Framing

Creating a style and applying across your site is hard right now.

Supplemental to this is the work for block style system that creates a clear stack and foundation.

> The idea is to provide a unified system for Gutenberg blocks (core + 3rd party) and themes to work well with each other. They also have to understand and respect user overrides. These defined styles can be applied globally throughout the user’s site (e.g. Declaring font scale, or colors, or how all Buttons look).
> 
> [https://github.com/WordPress/gutenberg/issues/19611](https://github.com/WordPress/gutenberg/issues/19611)

To start the specification for this interface in v1 will be:

*   Typography: set base size, increase/decrease scale, set alignment.
*   Colors: set background, typography and primary.

## Plan

#### Design tasks

There are of course development tasks but as this is on make/design focusing on what design to expect.

Task

Status

Link

Global style defaults

In Progress

Color picker iteration

Done

[https://github.com/WordPress/gutenberg/issues/19785](https://github.com/WordPress/gutenberg/issues/19785)

Range control

Done

[https://github.com/WordPress/gutenberg/issues/19845](https://github.com/WordPress/gutenberg/issues/19845)

Flow diagrams for v1

Done

[https://github.com/WordPress/gutenberg/issues/19255#issuecomment-582393358](https://github.com/WordPress/gutenberg/issues/19255#issuecomment-582393358)

Explore beyond a sidebar

Done

[https://github.com/WordPress/gutenberg/issues/20212](https://github.com/WordPress/gutenberg/issues/20212)

Explore switching from global to local styles

Done

[https://github.com/WordPress/gutenberg/issues/19255#issuecomment-587572951](https://github.com/WordPress/gutenberg/issues/19255#issuecomment-587572951)

Block review

In progress

Sidebar v2

Done

[https://github.com/WordPress/gutenberg/issues/19255#issuecomment-585729528](https://github.com/WordPress/gutenberg/issues/19255#issuecomment-585729528)

Explore recommended styles

In progress

Explore how to apply global styling

In progress

## Visuals

### Flows

#### Editing typescale

![](https://i0.wp.com/make.wordpress.org/design/files/2020/01/Flow_-Increase-typescale.png?fit=776%2C279&ssl=1)

## Updates

*   19/02: all design tasks updated into table to show current work.