# GitHub

Shared GitHub [composite actions](https://docs.github.com/en/actions/sharing-automations/creating-actions/creating-a-composite-action) and [reusable workflows](https://docs.github.com/en/actions/sharing-automations/reusing-workflows) by [@drkibitz](https://github.com/drkibitz).

---

## [Actions](actions/)

### [parse-git-ssh-url](actions/parse-git-ssh-url/action.yml)

A composite action that parses a Git+SSH URL into its required components.

### [git-push-over-ssh](actions/git-push-over-ssh/action.yml)

A composite action to securely push changes to a remote Git repository over SSH.

---

## [Workflows](.github/workflows/)

### [cpanel-git-deployment](.github/workflows/cpanel-git-deployment.yml)

A reusable workflow for deploying to a [cPanel](https://cpanel.net/) hosted site using Git. See the [Guide to Git™ Deployment](https://docs.cpanel.net/knowledge-base/web-services/guide-to-git-deployment/) for more details.
