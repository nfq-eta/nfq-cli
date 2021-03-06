# eta-cli contributing guide

## Issue Reporting Guidelines

- First identify where error is coming from. If it's occuring while running `eta` command then issue is indeed on
`eta-cli` so please report it here. If error appears when you run one of `npm run` scripts, problem originates
from a template you're using, [maybe one of the offical ones](https://github.com/eta-templates). If so, please
open an issue on a template repository.

- Try to search for your issue, it may have already been answered or even fixed in the development branch.

## Development Setup

``` bash
yarn
npm run lint
```

## Releasing new version
1. Check for js errors `npm run lint`
1. Commit all changes
1. To release a new version `npm run release`
1. Push git changes to master branch with all TAGS
1. Wait for travis to publish
