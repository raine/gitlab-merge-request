# gitlab-merge-request

Create a merge request on Gitlab for the current branch from command-line.

Opens `$EDITOR` for entering a title for the merge request.

After creation, outputs a clickable URL to open it in browser.

## setup

```sh
$ curl https://raw.githubusercontent.com/raine/gitlab-merge-request/master/gitlab-merge-request > ~/bin
$ chmod +x ~/bin/gitlab-merge-request
$ gem install git gitlab
$ export GITLAB_API_ENDPOINT=https://gitlab.yourcompany.com/api/v3
$ export GITLAB_API_PRIVATE_TOKEN=<YOUR_TOKEN>
```

Get the private token from https://gitlab.yourcompany.com/profile/account

## usage

```sh
$ gitlab-merge-request
```
