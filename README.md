joaonc's blog

# Installation
## Hugo
### Windows
```
choco install hugo-extended
```
The `extended` version of Hugo is required for some themes.
See [Editions](https://gohugo.io/installation/windows/#editions) for more info.

# Blog maintenance.
## Create new post

```
hugo new posts/my-new-post.md
```
Can also simply add a new `.md` file under `content/posts`, but with the `hugo` command, the new
file will be created from a template and have pre-filled metadata.


## Publish

```
hugo -t <theme>

# Ex:
hugo -t PaperMod
```

## Update themes

The PaperMod update was installed following
[these](https://github.com/adityatelange/hugo-PaperMod/wiki/Installation#method-2) instructions
(submodule).

To update the theme:
```
git submodule update --remote --merge
```