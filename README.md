# Dockerfile Codeless Language Module for BBEdit

## What does it do?

It provides a bit of syntax highlighting and commenting ability for ([Dockerfiles](https://docs.docker.com/engine/reference/builder/)) in [BBEdit](https://www.barebones.com/support/bbedit/).

## Why?

It's nicer to read.

## Is it all your own work?

No, I can't remember if I made the original or I got it from somewhere (sorry and thanks if you do exist and I've forgotten who you are!) as I'm only now getting around to sharing it, and I took a few ideas from [poblish's Dockerfile plist](https://github.com/poblish/Docker.bbpackage), so again, thanks.

## To use

Pop the plist into "~/Library/Application Support/BBEdit/Language Modules/", either by dropping the file there or, if you'd like to stay up to day with changes git clone, e.g.

    git clone https://github.com/yb66/BBEdit-Dockerfile "~/The place I keep git projects/BBEdit-Dockerfile"

Then create a link:

    ln "~/The place I keep git projects/BBEdit-Dockerfile/Dockerfile.plist" "~/Library/Application Support/BBEdit/Language Modules/"

In both cases BBEdit will require a restart. Files called `Dockerfile` will automatically be recognised.

## Licence

See LICENCE.txt


## Contributions welcome!

Anything I've missed or you think could be improved, just let me know.
