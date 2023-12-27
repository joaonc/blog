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

