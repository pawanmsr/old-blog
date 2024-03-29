Personal Outreach
=================

[![Build Status](https://travis-ci.com/pawanmsr/pawanmsr.github.io.svg?branch=main)](https://travis-ci.com/pawanmsr/pawanmsr.github.io)  
[![Deploy Jekyll site to Pages](https://github.com/pawanmsr/pawanmsr.github.io/actions/workflows/jekyll.yml/badge.svg?branch=main)](https://github.com/pawanmsr/pawanmsr.github.io/actions/workflows/jekyll.yml)  

Personal GitHub Pages repository.  
Powered by [Jekyll](https://github.com/jekyll/jekyll). Flavored with [Daktilo](https://github.com/kronik3r/daktilo).

License
-------

Some Rights Reserved.  
[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)  
All user specific content is licensed under [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)

[Daktilo](https://github.com/kronik3r/daktilo) is licensed under [The MIT License.](https://opensource.org/licenses/MIT)

Notes
-----

Test Deployment.

```shell
# https://jekyllrb.com/docs/installation/#requirements
ruby -v
gem -v
gcc -v && g++ -v && make -v

# Install jekyll and blunder.
gem install jekyll bundler

# Install dependencies.
bundle install

# Host on local.
bundle exec jekyll serve
```

Rebase and Squash all commits regularly.

```shell
git rebase -i $commit_hash

# Replace pick with squash
# for all commits except the
# first and the last.

# Replace pick with fixup -c
# for the last commit.

# Keep only the latest commit.

```
 
Delete the repository on GitHub and re-create after evertime a certain number of pull requests are recorded - this will erase the PRs from GitHub (because GitHub does not allow PR deletion on UI).  
