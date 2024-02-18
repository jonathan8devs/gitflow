<!--
##########################################################################
############################# ⚠️ ATTENTION ⚠️ ############################

⚠️ Please switch to the `Preview`-Tab and follow the instructions there ⚠️

############################# ⚠️ ATTENTION ⚠️ #############################
##########################################################################
-->

# Create `Release` or `Hotfix` Branch

**Manual creation of `release` or `hotfix` branches is not recommended!** To ensure proper workflow, these branches should be generated automatically through a predefined process.

## Here's how to create the correct branch
 1. Read the entire note before you continue
 2. Click the Link: [Create Release/Hotfix](../actions/workflows/gitflow_create_release.yml)
 3. **Ignore the branch selection.** Releases are automatically generated from the `dev` branch, and hotfixes from the `main` branch.

<img src="https://github.com/jonathan8devs/gitflow/blob/dev/.github/PULL_REQUEST_TEMPLATE/initiate_a_release.png?raw=true" alt="View of the workflow" height=auto width="100%" style="display:block; margin: 1em auto">

## Versioning

- Automatic versioning based on Semantic Versioning 2.0.0 is used.
- If no hotfix occurred since the last release, select MAJOR, MINOR, or PATCH for automatic incrementing.

## ⚠️ Important

- If a hotfix happened between releases or you **don't** want automatic incrementing, **manually enter the next version number**. This is m**andatory after a hotfix!**


**Following these steps ensures proper versioning and workflow. Avoid manual branch creation.**