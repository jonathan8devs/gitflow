<!--
##########################################################################
############################# ⚠️ ATTENTION ⚠️ #############################

⚠️ Please switch to the `Preview`-Tab and follow the instructions there ⚠️

############################# ⚠️ ATTENTION ⚠️ #############################
##########################################################################
-->

# Prerequisites for adding changes or new features

In principle, there is no obligation to use a pull request for a `release` or `hotfix` branch. This means you can also push changes directly to it. However, it is possible to make a pull request from a `feature` branch to the `release` or `hotfix` branch.

Basically, a few conditions must be checked to ensure that the deployments work and the internal process is adhered to.If you want to make a pull request on a `release` or `hotfix` branch, please note the following requirements:
- [ ] **Your branch starts with `feature/`?** Not? Then rename it. No other naming is accepted by the workflows!
- [ ] **Meaningful branch name?** Not? Then please rename your branch first!
- [ ] **Your feature branch is created from the `release` or `hotfix` branch?** Not? Then make sure that the `release` or `hotfix` is pulled into your branch!
- [ ] **PR is from the feature branch to the `release` or `hotfix` branch?** Not? Make sure the PR is correct from Feature to `release` or `hotfix`!

If all points are fulfilled, then you may click here: [Create Feature Pull Request](?expand=1&template=create_feature.md)