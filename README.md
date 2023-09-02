# theory.amsterdam: website for TCS in Amsterdam
[![Netlify Status](https://api.netlify.com/api/v1/badges/af68c57e-db12-4d28-8383-410f5b7c9981/deploy-status)](https://app.netlify.com/sites/theory-amsterdam/deploys)

This website provides an overview of the academic research in theoretical computer science (TCS) carried out at various institutions in Amsterdam. 

initiated by Christian Schaffner in September 2021, now maintained by Feline Lindeboom.

built from [Wowchemy's Research Group Template](https://github.com/wowchemy/starter-hugo-research-group) for [Hugo](https://github.com/gohugoio/hugo)

## Building this website from scratch locally

### on Mac/Linux

1. Install [Hugo and its dependencies](https://wowchemy.com/docs/getting-started/install-hugo-extended/)

2. Clone this repo:

```bash
git clone git@github.com:theory-amsterdam/website-theory-amsterdam.git
```

3. Start Hugo server to see the site live locally at http://localhost:1313/ (or at whatever the hugo server tells you)!

```bash
cd website-theory-amsterdam
hugo server
```

4. Edit the [markdown source files](https://wowchemy.com/docs/content/writing-markdown-latex/) with ending .md in the [/content/](https://github.com/theory-amsterdam/website-theory-amsterdam/tree/main/content) subdirectory to make changes to the site. As long as the hugo server is running, your changes should be visible immediately at http://localhost:1313/.

5. Using a suitable editor like [Atom](https://atom.io/) allows to easily search across all source files, and will help finding the correct file to edit if you want to make specific changes.

6. Add new researchers by duplicating a similar subfolder in [/content/authors/](https://github.com/theory-amsterdam/website-theory-amsterdam/tree/main/content/authors) and adjusting the .md content and replacing the avatar picture.

7. When you are happy with the result, commit the changes to the master branch. The site is then automatically deployed to https://theory-amsterdam.netlify.app/ and accessible under https://theory.amsterdam .

### on Windows
1. Install 
- [Github Desktop](https://desktop.github.com/)
- [Atom editor](https://atom.io/)
- [Hugo and its dependencies](https://wowchemy.com/docs/getting-started/install-hugo-extended/#windows), including Go, PowerShell and Scoop.

2. Log in to Github Desktop and go to the _website-theory-amsterdam_ repository.

3. When working on this repository for this first time, clone it. 

4. Whenever you start working on the website, update your local files with any potential new changes by selecting: _current branch – main_ then _choose a branch to merge into main_ then _upstream/main_ then _create a merge commit_.

5. Navigate to the repository in Powershell (default location is Documents/GitHub/website-theory-amsterdam), and start the Hugo server to see the site live locally at http://localhost:1313/ (or at whatever the hugo server tells you):

```
cd ~/Documents/GitHub/website-theory-amsterdam
Hugo serve
```

5. Using a suitable editor like [Atom](https://atom.io/) allows to easily search across all source files, and will help finding the correct file to edit if you want to make specific changes.

6. Add new researchers by duplicating a similar subfolder in [/content/authors/](https://github.com/theory-amsterdam/website-theory-amsterdam/tree/main/content/authors) and adjusting the .md content and replacing the avatar picture.

7. When you are happy with the result, write a summary of your changes under _Summary (required)_ in GitHub Desktop, then click _commit to main_ and then click _Push Origin_. Unfold the tab _branch_ and click on _Create pull request_. The GitHub website automatically opens. There, click (twice) on _Pull request_. Now wait until hopefully the website administrator accepts your pull request.

## Troubleshooting
This [information](https://wowchemy.com/docs/hugo-tutorials/troubleshooting/) might be useful. Sometimes, you might have to [delete Hugo's default cache folder](https://wowchemy.com/docs/hugo-tutorials/troubleshooting/#error-failed-to-resolve-output-format).

For more information, try the search function on the [wowchemy website](https://wowchemy.com/).
