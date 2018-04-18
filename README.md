This is a demo for the [`gatsby-remark-github`](https://github.com/huy-nguyen/gatsby-remark-github) plugin.

## Prerequisites

*Before* spinning it up, please [create a GitHub personal access token](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/). Because this demo only accesses public repos, the `public_repo` scope is sufficient. However, if you plan on adding more stuff to this repo later and think you might need to fetch from private repos, choose the `repo` scope.

After getting the token, create two files, `.env.development` and `.env.production` whose content is the same:

```
GITHUB_TOKEN=YourGithubToken
```

These two files are already excluded from version control.

## Usage

To run in dvelopment mode, run `gatsby develop`.

To make a production build, run `gatsby build` followed by `gatsby serve`.

