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
- Add a repository-secret with your gitlab-username (named "GITLAB_USERNAME")
