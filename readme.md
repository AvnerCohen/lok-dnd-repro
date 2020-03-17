This repo is meant to help resolve a docker-in-docker issue that occurs on circleci
Specifically effecting loki visual testing.

Locally this will work:

```sh
$> yarn install
$> build-storybook -c .storybook
$> yarn test:visual:ci
```

However, same over circleci fails:
https://app.circleci.com/pipelines/github/AvnerCohen/lok-dnd-repro/7/workflows/c383ad89-ffd2-4792-8299-55455fa64a0c/jobs/7