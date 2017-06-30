# Commit & Branching Guidelines

## Commit Messages

Write your git comments by following at least the following rules
* Prefix each commit message with a nice subject line.<br/>
  Example: `PROJECT_NAME-1234 Add User Authentication`
   * Start with the issue number of the issue in Jira including the project prefix,
      e.g. `PROJECT_NAME-456`
   * Add short high level description of what you did
   * Description is in imperative form:
      as if you would order the commit what it does.
      E.g. “Update dependencies” instead of     “Updates dependencies” or “Updated dependencies”
   * No longer than 50 characters
   * Avoid "Implement ..." as a verb
      (yes, sure, that is what we usually do!)
* Use more lines to explain the commit, if necessary
* Try to follow other recommendations as mentioned in this useful [Guide for Commit Messages](http://chris.beams.io/posts/git-commit/)

## Branching Model and Workflow

We work by following the **Git Flow Branching Model and Workflow**.

 Here are the most important rules summarized and precised, how we live it in this project:

**Branch Workflow Rules:**

* **Branch `master`**: contains only the last published/released version of our software, no work is done directly on that branch.

* **Branch `develop`**: this is the branch where we integrate our work that is usually done on separate feature branches.

* **Work on Feature Branches** by following these simple rules:

   * **Create a feature branch with name `feature/xyz-some-description`**,
     where the `xyz` prefix is the full issue number (including project prefix!) of the Jira ticket, that this branch belongs to. Example: feature/PROJECT_NAME-1234-user-authentication

   * **Integrate your feature branch often with work from others (daily!)** by pulling from the base branch (usualy `develop`)!

   * **Do small Merge Requests (per small task!) to review and merge your feature branches**:

       * **Do this regularly and not for work of several weeks!** Usually for each task on a story. Avoid having long living isolated feature branches with many unintegrated changes. Those will become more difficult to merge and to review.

       * **Open MR on Gitlab and post to slack `#review` channel for review:** One colleague (at least) will review it and give you feedback (4 eyes principle!). This is a good way we can learn from each other, do know how transfer and constantly improve our quality of work.

       * **Take the feedback from review seriously and try to improve accordingly:**
          * Small corrections should be done immediately on the same MR (just push to same branch again!)
          * Some other review comments may also just lead to new tasks, that you open, to resolve them later. Because often during the review of an MR points may come up, that should not block the merging of your MR.
          * Some of this tasks might even need further discussions with the reviewer or even the team what is the best solution and further planning.

 * **Release and Hotfix Branches:** for stabilizing releases we will use relase branches (and later if needed maybe also hotfix branches).

      * **Changes are also done on feature branches first, and then merged via MR to this branches (see above)**

      * **Changes on this branches need also be merged to the `develop` branch (immediately!)**: Every developer is responsible to merge the release or hotfix branch also to develop, every time he merged one of his changes to one of this branches (we should probably automate this once!). It is important to do this regularly and immediately after a merge to this branches, such that no one else will have troubles with merging later to the develop branch.

For more informations about Git Flow Branching Workflow, see [Git Flow Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)
