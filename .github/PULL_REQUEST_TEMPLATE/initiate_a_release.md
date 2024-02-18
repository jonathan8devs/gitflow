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

 1. Click the button below:<div style="text-align:center;"><a href="../actions/workflows/gitflow_create_release.yml" style="background-color: #04AA6D;border: none;color: white;padding: 15px 32px;text-align: center;text-decoration: none;display: inline-block;font-size: 16px;margin: 20px 0">Create Release/Hotfix<a></div>
 2. **Ignore the branch selection.** Releases are automatically generated from the `dev` branch, and hotfixes from the `main` branch.



## Versioning

- Automatic versioning based on Semantic Versioning 2.0.0 is used.
- If no hotfix occurred since the last release, select MAJOR, MINOR, or PATCH for automatic incrementing.

## ⚠️ Important

- If a hotfix happened between releases or you **don't** want automatic incrementing, **manually enter the next version number**. This is m**andatory after a hotfix!**


**Following these steps ensures proper versioning and workflow. Avoid manual branch creation.**