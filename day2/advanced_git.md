# Advanced Git/Github practice

*We decided not to prepare a presentation for this session, but only a series of notes that will guide us through the process.*

## Exploring Github

- What is [Github](https://en.wikipedia.org/wiki/GitHub)?
- Similar products to github ([Gitlab](https://about.gitlab.com/), [Bitbucket](https://bitbucket.org/), ...)
- The Github start page: How to navigate this website, how to find what you're searching for and how to use the social network aspect to your advantage?
- Profile page: Your personal page and what you can learn from it.
- The repository: The main unit of interaction and how it works.

## Hands-on experience

### Setup a Github repository and connect to it

- Create an own repository: Your Name + your favorite animal -> ClemensDonkey
- Connect to [github via ssh](https://help.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh):
	- Generating a new SSH key
	- Adding a new SSH key to your GitHub account
	- Testing your SSH connection
- Clone the repository (with ssh): `git clone ...`
- Inspect the remotes: `git remote -v`

### Working with Git + Github

- Edit the README file in your repository with a text editor
- Stage, commit and push your changes: `git status` + `git add --all` + `git commit -m "my first commit to github"` + `git push` + `git status`
- Go back to github and inspect your changes

### Collaborative working

- Fork the repository of your friend on Github
- Clone your fork to your computer `git clone ...`
- Make changes in the README of this forked repository with a text editor
- Stage, commit and push your changes: `git status` + `git add --all` + `git commit -m "my first commit to github"` + `git push` + `git status`
- Back to Github: Propose a Pull Request
- Merge the changes of your partner
- Inspect the github network graph
- Pull and inspect the new version of your own repository `git pull` + `git log`

## Advanced topics

- Merge conflicts
- Protected branches
- Other git features

