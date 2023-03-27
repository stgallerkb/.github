## Workflow Templates

This repo contains a handful of starter workflows which should be used for new projects. They ensure that each project contains
standardized CI, CD and security scanning processes.

To use our starter workflows, simply head over to the **Actions** tab and you'll see a section _"By St.Galler Kantonalbank AG"_. If the project already has configured workflows, you can always use the **New Workflow** button to create new workflows based on the shared workflows.

- Documentation of corporate [shared workflows](https://github.com/stgallerkb/workflows#available-workflows-to-use)
- Documentation of corporate [shared actions](https://github.com/stgallerkb/actions#available-actions-to-use)
- Read more about [using GitHub starter workflows](https://docs.github.com/en/actions/using-workflows/using-starter-workflows)

### CI

#### Java + React CI

A basic continuous integration worflow for Applications with a Java Backend and a React Frontend.

### CD

#### Deployment

An automatic continuous deployment workflow to deploy applications to corresponding project environments via K8s.

#### Manual Deployment

A manual deployment workflow to deploy applications to a single project environments via K8s.

### Security

#### CodeQL

An automatic continuous workflow to scan and analzye code on push, pull request and schedule triggers.
