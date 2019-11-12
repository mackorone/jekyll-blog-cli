# jekyll-blog-cli

A small CLI for managing Jekyll blog posts

## Installation

1. Install `argcomplete`:

```bash
sudo pip3 install argcomplete
```

2. Add to your `~/.bashrc`:

```bash
export PATH=$PATH:<PATH_TO_THIS_REPO>
export BLOG_ROOT=<PATH_TO_YOUR_BLOG_ROOT>
eval "$(register-python-argcomplete blog)"
```
