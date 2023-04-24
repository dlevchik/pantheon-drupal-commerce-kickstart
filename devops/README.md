# DevOps

This folder contains a series of scripts to test and deploy different upstreams and start states based on drupal-composer-managed.

## Deploying drupal-composer-managed public upstream

This happens on CI when commits are merged into the release branch.

## Deploying drupal-10-composer-managed start state upstream.

You should run this process manually.

Make sure you have write access to https://github.com/pantheon-upstreams/drupal-10-composer-managed and run the following script from the repo root:

```
./devops/scripts/deploy-d10-start-state.sh
```

Verify your changes are in the public repo.

## Deploying decoupled-drupal-10-composer-managed start state upstream.

You should run this process manually.

Make sure you have write access to https://github.com/pantheon-upstreams/decoupled-drupal-10-composer-managed and run the following script from the repo root:

```
./devops/scripts/deploy-d10-decoupled-start-state.sh
```

Verify your changes are in the public repo.