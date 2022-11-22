This is a dummy-project to test the integration of Gitlab-CI into Repos hosted on Github.

Steps to be done:

- Allow Force-Push on remote protected branches in remote Repo
- Create Personal Access Token in GitLab,
so that the GitHub-CI can push to GitLab
- This Token needs the necessary permissions:
  - API (Read & Write)
  - Read repository
  - Write repository
- Add this token in Github as Action-Secret (named "GITLAB_TOKEN")
- Ask the maintainer of the repo to add your user to the Gitlab-Repo as well (with at leas Developer-Rights)

If you forked the Repo, please activate the Github-Actions in the "Actions"-Tad, then your own credentials are used

Maybe all these steps are not necessary at all. Let's see...
