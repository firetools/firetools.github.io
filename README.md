# Firetools website

This is the Firetools project website repository.

## How was it made?

This website was generated from the [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes),
[configured as necessary](https://mmistakes.github.io/minimal-mistakes/docs/configuration/).

## Run the website locally

Source: https://cassidyjames.com/blog/github-pages-jekyll-fedora-silverblue/

Create the environment in a toolbox container:

```
toolbox create jekyll
toolbox enter jekyll
sudo dnf install ruby ruby-devel openssl-devel @development-tools gcc-c++
sudo gem install bundler
bundle config set --local path 'vendor/bundle'  # To install locally
cd to/website
bundle install
```

Run the website with:

```
bundle exec jekyll serve --host 0.0.0.0 --future
```

Then you can navigate to http://localhost:4000 to view your site.

## Troubleshooting

For questions about using Jekyll, start a discussion on the [Jekyll Forum](https://talk.jekyllrb.com/) or [StackOverflow](https://stackoverflow.com/questions/tagged/jekyll). Other resources:

- [Ruby 101](https://jekyllrb.com/docs/ruby-101/)
- [Setting up a Jekyll site with GitHub Pages](https://jekyllrb.com/docs/github-pages/)
- [Configuring GitHub Metadata](https://github.com/jekyll/github-metadata/blob/master/docs/configuration.md#configuration) to work properly when developing locally and avoid `No GitHub API authentication could be found. Some fields may be missing or have incorrect data.` warnings.

## Icons

Find the icons here: https://fontawesome.com/

## Apply inline styles

Like this:

```markdown
| <i class="fa-brands fa-linux"></i> Ask a question |
| <i class="fa-brands fa-apple"></i> Submit an issue | 
{: style="font-size: 150%" }
```

or

```markdown
<div markdown="1" style="font-size:200%">
| <i class="fa-brands fa-linux"></i> Ask a question |
| <i class="fa-brands fa-apple"></i> Submit an issue | 
</div>
```