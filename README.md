# HighTechU Member Projects Portfolio

HighTechU Members Projects: GitHub Repositories built by Youth.

## Built with

* [Jekyll](https://jekyllrb.com/docs/) (for building your website)
* [GitHub Pages](https://pages.github.com/) (for hosting your website)
* [GitHub's API](https://developer.github.com/v3/) (for automatically populating your website with content)

## Get Started

### Installation

#### Install in your local development environment

If you want to manage your website in a local web development environment, you'll be using [Ruby](https://jekyllrb.com/docs/installation/).

**[Clone](https://help.github.com/articles/cloning-a-repository/)** the repository.

#### Install Jekyll

Jekyll is a [Ruby Gem](https://jekyllrb.com/docs/ruby-101/#gems) that can be installed on most systems.

1. Install a full [Ruby development environment](https://jekyllrb.com/docs/installation/)
2. Install Jekyll and [bundler](https://jekyllrb.com/docs/ruby-101/#bundler) [gems](https://jekyllrb.com/docs/ruby-101/#gems)
```
gem install jekyll bundler 
```
3. Change into your new directory
```
cd portfolio
```
4. Install missing gems
```
bundle install
```
5. Build the site and make it available on a local server
```
bundle exec jekyll serve
```

You should see something like:

```
Configuration file: /octocat/personal-website/_config.yml
            Source: /octocat/personal-website
       Destination: /octocat/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
   GitHub Metadata: No GitHub API authentication could be found. Some fields may be missing or have incorrect data.
                    done in 14.729 seconds.
 Auto-regeneration: enabled for '/octocat/personal-website'
    Server address: http://127.0.0.1:4000
  Server running... press ctrl-c to stop.
```

Don't worry about the "No GitHub API authentication could be found" message. [API authentication is only necessary](https://github.com/jekyll/github-metadata/blob/master/docs/authentication.md) if you intend to display more detailed metadata, like a branch name.

6. Now browse to [http://localhost:4000](http://localhost:4000)

### Publish

Push to the `main` branch, GitHub Pages will deploy the website. 

## License

This portfolio is based off the [Github.dev Personal Website theme](https://github.com/github/personal-website), which is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
