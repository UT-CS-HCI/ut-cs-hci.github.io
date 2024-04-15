# Website for the UT CS HCI Lab

Can be deployed at https://utcshci.utexas.edu/.
Currently deployed at https://ut-cs-hci.github.io/.
The setup is inspired by https://github.com/cmudig/cmudig.github.io and https://github.com/interactive-structures/interactive-structures.github.io. 

## Run

Install Jekyll dependencies with `bundle`. To start this page, run `bundle exec jekyll serve --livereload`.

## Run with Docker

```
docker run \
  --volume="$PWD:/srv/jekyll" \
  -p 4000:4000 -p 35729:35729 \
  -it jekyll/jekyll \
  jekyll serve --livereload
```

## Add Content

To add specific content, follow the README guides in the corresponding directories:

* [Add a person](_people)
* [Add a publication](_publications)
* [Add a post](_posts)
