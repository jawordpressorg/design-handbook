# WordPress components

## What are they?

WordPress Components are the set of interface elements that make up the Block Editor and other projects. This includes several user interface (UI) components like buttons, menus, and text fields. You can find them in the [Gutenberg GitHub repo](https://github.com/WordPress/gutenberg) or in the [Block Editor Handbook](https://developer.wordpress.org/block-editor/components/). The code for these components exists in the Gutenberg repo, and is available through the \`@wordpress/components\` npm package.

*   **Visual components**: These are the reusable bits of UI that can be used in Figma, for creating mockups. The Figma components should mirror exactly what is available in code.
*   **Code components**: These are considered the source of truth. These are the javascript code components that exist in the Gutenberg GitHub repo.

## Workflows

### **Adding a new component in Figma**

Note: this process goes hand in hand with the process of adding a code component to @wordpress/components. That process can be found in the [GitHub Gutenberg repo](https://github.com/WordPress/gutenberg/blob/master/packages/components/src/CONTRIBUTING.md). **In order for a new component to be added to Figma, it must first exist in code (the source of truth).**

Once there is a proposal for a code component on GitHub, the process of adding a Figma component can start. Adding the “**Figma Library Update**” GitHub label will notify the [#design](https://make.wordpress.org/design/tag/design/) Slack channel that a change/addition is needed.

First, open the [WordPress Design](https://www.figma.com/file/e4tLacmlPuZV47l7901FEs/WordPress-Design-Library) Figma library.

*   **Proposals**: Make a component and add it to the [**Proposals** page](https://www.figma.com/file/e4tLacmlPuZV47l7901FEs/WordPress-Design-Library?node-id=2%3A32) to be discussed. During this phase, feel free to work on the component until the component is finalized in the Gutenberg GitHub repo. **Because the Figma components mirror what’s in code, we shouldn’t publish a new Figma component until it’s available in code.**
*   **Iteration**: Iterate on the component until it matches the coded component. This includes color, spacing, typography, states, etc. Make sure you follow the [general component guidelines and naming conventions](https://www.figma.com/file/e4tLacmlPuZV47l7901FEs/WordPress-Design-Library?node-id=1%3A2).
*   **Review**: Once the *coded* component has been finalized, it’s time to review the Figma component and get it ready for publishing. Figma maintainers will need to check for accuracy, layer structure, and naming. Please ping the designers in the [#design](https://make.wordpress.org/design/tag/design/) Slack channel to get a review.
*   **Publish**: After the code component has been released to @wordpress/components, the Figma component can now be published to the Figma library by a maintainer. Be sure to include release notes. Maintainers: Please follow the [publishing guidelines](https://www.figma.com/file/e4tLacmlPuZV47l7901FEs/WordPress-Design-Library?node-id=1%3A2).

### **Editing an existing component in Figma**

If you find a bug, or you’d like to enhance an existing component, please notify those working on Figma in the [#design](https://make.wordpress.org/design/tag/design/) Slack channel. The process is mostly the same as adding a new component, except GitHub and the code components are not involved.  Please follow the process for adding a new Figma component as described above

### **GitHub workflow when a code component changes**

If you make a change to any code component as a designer or developer, the corresponding Figma component will need to be updated.

*   Add the GitHub label “**Figma Library Update**”.
*   Follow the process for editing an existing component as described above.

## Further links

*   [WordPress Design Figma library](https://www.figma.com/file/e4tLacmlPuZV47l7901FEs/WordPress-Design-Library)
*   [Source of the WordPress Components code](https://github.com/WordPress/gutenberg/tree/master/packages/components/src)
*   [Process for contributing changes or additions to the WordPress Components code](https://github.com/WordPress/gutenberg/blob/master/packages/components/src/CONTRIBUTING.md)