If you want to merge 2 (or more) repos into one, whilst retaining history: [Merge git repos into a new repository whilst maintaining history](https://www.vvse.com/blog/blog/2017/04/16/merge-git-repositories-into-a-new-repository-while-preserving-the-commit-history/)

Notes:
* Works best if each source repo has a single root folder
  * Example can re-write repo using *nix tools to get this
* If you also want to merge code bases, this will be an extra step
* Be sure to re-write pipelines for new paths, and to allow multiple artefacts, if needed
