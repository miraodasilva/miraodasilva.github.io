My personal page.

This was forked from [this repo](https://github.com/academicpages/academicpages.github.io). Please check that repo for all the information on how to use the template. That repo is forked (then detached) by [Stuart Geiger](https://github.com/staeiou) from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under the MIT License. See LICENSE.md.

## Notes for future reference
- TLDR: Just push to master branch to publish changes on the website. Check the commit on github for a green light, which means the website has been built successfully.
- To test locally you must:
    - install packages without sudo by installing [Homebrew](https://brew.sh/) and use it to install `rbenv`, `rbenv-bundler` and `nodejs` (if you do have sudo, you can use `sudo apt install ruby-dev ruby-bundler nodejs`).
    - in the repo directory, do `bundle clean`, `bundle install` and then `bundle exec jekyll liveserve --config _config.yml,_config.dev.yml` - the website will run on localhost:4000, and with this config override everything should run smoothly.
- Check my first commit with all the basic website content and functionality to check what exactly I changed/added compared to the repo I forked - this should also be helpful to understand roughly how the code works.