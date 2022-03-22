# Checklist Draft
Draft for checklist for programming review

The purpose of this document is to provide a framework to review your work and the work of others. It is a liveable document that may change depending on timeframes, needs, changes in technology, or changes in overall goals.

**Code Reviewing for others:**



* Don’t be rude just to be rude, we’re all here for one goal
* Explain clear reasoning of why it needs to be improved
* If you have a better approach feel free to suggest that instead
* Include a positive point for every negative: this helps motivation and may also help people where they need to learn more or where their strengths are


**Before starting the PR**

1. Make sure all code is documented according to standards (when it exists), or at least similarly to other files
2. Make sure all changes that can be applied to prefabs, are applied to prefabs.
3. If adding something new to the scene, either add it to an existing prefab, or make one for it.
4. When making a new one that has to be added, make note of the need to add it, and any requirements for it, to the PR description
5. Make sure the game runs, and no new errors are introduced.
6. Make sure you're not accidentally updating some random meta files, feel free to ping peoples if unsure if something is needed.
7. **Remember to clock your hours!**


**Programming Review Checklist:**

1. If there isn't anything strange in the prefabs or or code, go ahead and test locally
2. Does the code have conflicts?
    *  Yes:
            * what kind of conflicts?
            * Can I resolve it myself? If not message the creator of the PR saying they need to update it, and add the label NEEDS REVISION
    * No conflicts:
            * any comments on the PR? have those been addressed?
            * No comments: DM to see if the person is online, ask of the status
            * Comments addressed: continue with the review
3. Look at the description 
    * Is there detail on what was changed and why?
4. Look at the files changes
    * Skim for coding that doesn't meet the coding format or documentation standards
    * Skim the prefab .meta files, to see if anything looks "fishy" (this comes with experience, feel free to reach out for help)
    * Look at the prefab/file names to make sure they make sense (currently no standard for it)
    * If something stands out start a git review: click the plus that's next to the line number of the issue, and starting a review by adding comments
    * Make sure to document all issues, and make sure documentation also meets documentation standards
    * If there's any png or image files uploaded, make sure they're not huge (the standard will tell you how big)
    * Test locally before submitting the review
5. If any issues come up submit the review with a general overview/summary of major changes in the PR
6. No issues at all? Just merge it


