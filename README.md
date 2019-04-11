# USAGE

```
cp rireki.tex.example rireki.tex

docker build ./ -t siuissiki/texlive

docker run --rm -v {$PWD}:/workdir siuissiki/texlive uplatex rireki.tex; dvipdfmx rireki.dvi

open rireki.pdf
```
