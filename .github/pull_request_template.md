<!--
##########################################################################
############################# ⚠️ ATTENTION ⚠️ ############################

⚠️ Please switch to the `Preview`-Tab and follow the instructions there ⚠️

############################# ⚠️ ATTENTION ⚠️ #############################
##########################################################################
-->

# Template selection
We use Gitflow as the basis for our GitHub repositories. You can find a description of exactly what this means at the end of this template!

## I would like to:

### Develop
- **[Add a new feature to the `dev`-Branch](https://web.de)**

### Release
- **[Initiate a release](?expand=1&template=initiate_a_release.md)**
- **[Add a change or feature to the current `release`-branch](https://web.de)**

### Hotfix
- **[Initiate a hotfix](?expand=1&template=initiate_a_release.md)**
- **[Add a change or feature to the current `hotfix`-branch](https://web.de)**


## Gitflow-Workflow
<img src="https://wac-cdn.atlassian.com/dam/jcr:cc0b526e-adb7-4d45-874e-9bcea9898b4a/04%20Hotfix%20branches.svg?cdnVersion=1424" alt="Pictorial representation of the Gitflow" height=auto width="50%" style="display:block; margin: 1em auto">

Once `dev` has acquired enough features for a release (or a predetermined release date is approaching), you fork a `release` branch off of `dev`. Creating this branch starts the next release cycle, so no new features can be added after this point—only bug fixes, documentation generation, and other release-oriented tasks should go in this branch. Once it's ready to ship, the `release` branch gets merged into `main` and tagged with a version number. In addition, it should be merged back into develop, which may have progressed since the release was initiated.

Using a dedicated branch to prepare releases makes it possible for one team to polish the current release while another team continues working on features for the next release. It also creates well-defined phases of development (e.g., it's easy to say, “This week we're preparing for version 4.0,” and to actually see it in the structure of the repository).
