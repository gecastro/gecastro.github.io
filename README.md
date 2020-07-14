# Intro

My personal website based on Jekyll

Running with docker

docker run --rm --hostname jekyll --volume="$PWD:/root/website" -p 4000:4000 -it jekyll:latest /bin/bash -ic "cd website; bundle exec jekyll serve -H 0.0.0.0"
