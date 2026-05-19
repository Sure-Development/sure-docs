# sure_lib Documentation

Mintlify documentation for [Sure-Development/sure_lib](https://github.com/Sure-Development/sure_lib).

## Scope

This documentation site covers `sure_lib` only. Legacy product documentation has been removed from navigation and content.

## Local development

Install the current Mintlify CLI package:

```bash
npm i -g mint
```

Preview locally:

```bash
mint dev
```

Validate before publishing:

```bash
mint validate
```

## Structure

```text
docs.json
index.mdx
scripts/
  sure_lib/
    overview.mdx
    getting-started.mdx
    module-loader.mdx
    validator.mdx
    listener.mdx
    track.mdx
    player.mdx
    cooldown.mdx
    esx.mdx
    api-reference.mdx
```

## Deployment

Mintlify deploys from the connected GitHub repository after changes are pushed to the configured deployment branch.
