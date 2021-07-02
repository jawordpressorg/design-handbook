# Contributing to Gutenberg

If you’d like to contribute to the design or front-end, feel free to contribute to tickets labelled [Design](https://github.com/WordPress/gutenberg/issues?q=is%3Aissue+is%3Aopen+label%3ADesign). We could use your thoughtful replies, mockups, animatics, sketches, doodles. It’s best to keep proposed changes simple and constrained in scope so that it’s easy to compare, discuss, and implement changes.

## Terms

*   [Labels](https://github.com/WordPress/gutenberg/labels): each GitHub issue has labels that denote the ‘state’.
*   [PR: pull request](https://github.com/WordPress/gutenberg/pulls): how to add a ‘patch’ in terms of GitHub.
*   [Milestones](https://github.com/WordPress/gutenberg/milestones): a way to chart and manage the project.

## Labels

Whilst not an exhaustive list here are some of the useful labels to know about:

*   [Bug](https://github.com/WordPress/gutenberg/labels/%5BType%5D%20Bug): something is broken or doesn’t work as expected.
*   [Enhancement](https://github.com/WordPress/gutenberg/labels/%5BType%5D%20Enhancement): a suggestion for an improvement, or feature.
*   [Needs design feedback](https://github.com/WordPress/gutenberg/labels/Needs%20Design%20Feedback): feedback on something that exists.
*   [Needs design](https://github.com/WordPress/gutenberg/labels/Needs%20Design): a feature or iteration that needs a design.

## Choose your own adventure

### Without coding

*   **Advisor**: go through ‘[needs design feedback’](https://github.com/WordPress/gutenberg/labels/Needs%20Design%20Feedback) issues.
*   **Screenshotter**: add screenshots to issues that have none of the problems**.  
    **
*   **Informer**: ask for more information as can’t replicate a problem.
*   **Tester**: test not only Gutenberg on all devices, browsers and situations, but also test bugs [here](https://github.com/WordPress/gutenberg/labels/Needs%20Testing) and [here](https://github.com/WordPress/gutenberg/labels/%5BType%5D%20Bug). Also [testing any PR](https://github.com/WordPress/gutenberg/pulls) is a great way to help move issues along.
*   **Copy issues**: review and suggest [copy](https://github.com/WordPress/gutenberg/labels/Copy).
*   **Creator**: add to ‘[needs design](https://github.com/WordPress/gutenberg/labels/Needs%20Design)’ or anything that seems like it would be good to have a design.
*   **Documentor**: everything needs documentation.
*   **Triage**: see an issue without any comments or actions? Go through from oldest issues and make sure all issues can move on a little.

### With coding

*   **Patcher:** make PRs
    *   [Good first bugs](https://github.com/WordPress/gutenberg/labels/Good%20First%20Issue).
*   **Reviewing code:** CSS for example is crucial.  
      
    *Note: due to technical nature some of the triaging is a little intimidating for new contributors.*

## Diving into the code

*Note: this isn’t for all designers but if you do want to explore, here are some guides to get you started.*

### Setting up system

To run Gutenberg from GitHub and potentially make PR you need a few things:

*   A local environment, Docker is recommended because Gutenberg has a container.
*   GitHub app: recommended unless you want to explore the world of the command line: [https://desktop.github.com/](https://desktop.github.com/).
*   A code editor: [https://atom.io/](https://atom.io/) is from GitHub but you can use whatever you find useful, [https://code.visualstudio.com/](https://code.visualstudio.com/) also is an option.
*   Terminal app if on mac (or another way to interact at that level): at some point you’re going to have to dive into command line but there are some simple steps to this you can always refer to.

### Useful resources

*   https://desktop.github.com/
*   https://help.github.com/
*   https://help.github.com/articles/git-cheatsheet/
*   https://help.github.com/articles/creating-a-pull-request/

### Workflow

A good workflow for new contributors to follow is listed below:

*   [Fork](https://help.github.com/articles/fork-a-repo/) Gutenberg repository.
*   [Clone](https://help.github.com/en/articles/cloning-a-repository) forked repository.
*   Create a new [branch](https://help.github.com/en/articles/creating-and-deleting-branches-within-your-repository).
*   Make [code changes](https://help.github.com/en/desktop/contributing-to-projects/committing-and-reviewing-changes-to-your-project).
*   Commit code changes within the newly created branch.
*   [Push branch](https://help.github.com/en/articles/pushing-to-a-remote) to forked repository.
*   Submit [Pull Request](https://help.github.com/articles/creating-a-pull-request/) to Gutenberg repository.

### Branch naming

Ideally name your branches with prefixes and descriptions, like this: \[type\]/\[change\]. A good prefix would be:

*   **add/** = add a new feature
*   **try/** = experimental feature, “tentatively add”
*   **update/** \= update an existing feature