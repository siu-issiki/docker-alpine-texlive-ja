# USAGE

```
docker build ./ -t siuissiki/texlive

cp rireki.tex.example rireki.tex

docker run --rm -v ${PWD}:/workdir siuissiki/texlive bash -c 'uplatex rireki.tex; dvipdfmx rireki.dvi'

open rireki.pdf
```
