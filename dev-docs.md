# Cellxgene Documentation

The cellxgene documentation are deployed via gitbooks to a custom URL: docs.cellxgene.cziscience.com. Changes made to the main branch are automatically deployed to the live site.

## When to update the documentation:

1. When adding new functionality to cellxgene
2. When removing functionality from cellxgene
3. When making a significant change to the Portal UI
4. When making a significant change to the Explorer UI

## How to update the documentation

For simple documentation changes that modify text or media on existing pages, PRs can simply be made against the main branch of this repository. When merged, changes will be automatically deployed to the documentation.

For complex updates that change the structure of the documentation, or when there are questions about how added content will be displayed, it is recommended to additionally:
1. Fork the repository and set up a gitbook (see below)
2. Link the gitbook to the PR so reviewers can review how the changes will be deployed. 

## Creating a gitbook for a fork of cellxgene-documentation

1. Fork github.com/chanzuckerberg/cellxgene-documentation
2. Create a gitbook account and ask acarr@chanzuckerberg.com for an invitation to CZI's gitbook team
3. Create a new "space" in your personal "org".
4. Click "integrations" on the left sidebar and turn on the Github integration
5. Select "list all repositories" and use the search bar to find your fork of cellxgene-documentation
6. Select branches to sync and select the "main" branch
7. Select "I write my content on GitHub" to sync the repository to gitbook

This generates a _reusable_ gitbook serving your fork. Updating your fork from upstream on github will automatically deploy the changes to your fork, allowing you to use it again for future updates.
