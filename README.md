# git-green-someone-else

Update: Github has made some restrictions on the "Contribution Graph", see [here](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/managing-contribution-settings-on-your-profile/why-are-my-contributions-not-showing-up-on-my-profile#commits)

so, for __commits and contribution graph__ in a user profile, it works with any of the following are met:

> - You are a collaborator on the repository or are a member of the organization that owns the repository.
> - You have forked the repository.
> - You have opened a pull request or issue in the repository.
> - You have starred the repository.

for __listing of contributors__ to a repo, it still works.


```plain
$ cd your/project
$ git green "Jayin Ton <tonjayin@gmail.com>"
```

> Someone will be pushing to your repo being "greened" and then getting mad at you.

<img width="209" height="167" src="QQ20160510-1.png" />


### Installation

```plain
$ curl -s https://raw.githubusercontent.com/fritx/git-green-someone-else/master/install.sh | bash
```


### Roadmap

- [x] git green someone
- [ ] git ungreen someone
- [ ] github id
- [ ] commit dates
- [x] install via curl
- [ ] more..


### Related

- https://github.com/jayphelps/git-blame-someone-else
- https://github.com/gelstudios/gitfiti
- https://help.github.com/articles/why-are-my-contributions-not-showing-up-on-my-profile/
- http://stackoverflow.com/questions/920413/make-error-missing-separator
- https://learnxinyminutes.com/docs/bash/
- http://stackoverflow.com/questions/10768584/execute-python-commands-passed-as-strings-in-command-line-using-python-c
