# GitHub

Shared GitHub [composite actions](https://docs.github.com/en/actions/sharing-automations/creating-actions/creating-a-composite-action) and [reusable workflows](https://docs.github.com/en/actions/sharing-automations/reusing-workflows) by [@drkibitz](https://github.com/drkibitz).

---

## [Actions](actions/)

### [git-push](actions/git-push/action.yml)

A composite action to push changes to a remote Git repository.

### [git-push-over-ssh](actions/git-push-over-ssh/action.yml)

A composite action to securely push changes to a remote Git repository over SSH.

### [parse-git-ssh-url](actions/parse-git-ssh-url/action.yml)

A composite action that parses a Git+SSH URL into its required components.

### [setup-ssh-agent](actions/setup-ssh-agent/action.yml)

A composite action to setup and configure the SSH agent for connecting to a remote host.

### [teardown-ssh-agent](actions/teardown-ssh-agent/action.yml)

A composite action to clean up credentials and configurations from the SSH agent after use.

---

## [Workflows](.github/workflows/)

### [cpanel-git-deployment](.github/workflows/cpanel-git-deployment.yml)

A reusable workflow for deploying to a [cPanel](https://cpanel.net/) hosted site using Git. See the [Guide to Git™ Deployment](https://docs.cpanel.net/knowledge-base/web-services/guide-to-git-deployment/) for more details.

### [cpanel-reverse-git-deployment](.github/workflows/cpanel-reverse-git-deployment.yml)

Reusable workflow to sync runtime changes from a cPanel-hosted site to the source Git repository and push them upstream.
