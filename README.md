# :pushpin: Deprecated

This repo is no longer active.

I have a new [bash script](https://github.com/mackorone/dotfiles/blob/main/bashrc/blog.sh) that works better for my needs.

<details>
<summary><h4>Click to view original README.md</h4></summary>

# jekyll-blog-cli

A small CLI for managing Jekyll blog posts

## Features

1. List all blog posts
2. Open posts by title
3. Update dates in filenames
4. Run a local Jekyll server

## Installation

1. Install `argcomplete`:

```bash
sudo pip3 install argcomplete
```

2. Add to your `~/.bashrc`:

```bash
export PATH=$PATH:<PATH_TO_THIS_REPO>
export BLOG_ROOT=<PATH_TO_YOUR_BLOG>
eval "$(register-python-argcomplete blog)"
```
