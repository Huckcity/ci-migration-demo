# CI migration demo

A repository with one CI configuration for each system that [jenkins-to-actions](https://github.com/Huckcity/jenkins-to-actions) converts: a `Jenkinsfile`, `.gitlab-ci.yml`, `azure-pipelines.yml`, `.circleci/config.yml`, `bitbucket-pipelines.yml` and `.travis.yml`.

The open pull request was created by one command, with no manual edits:

```sh
npx jenkins-to-actions audit --repos Huckcity/ci-migration-demo --open-prs
```

It is left open on purpose so you can see what the tool produces, TODO steps and all.
