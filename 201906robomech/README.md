# ROBOMECH 2019
https://www.jsme.or.jp/event/2018-36038/

http://robomech.org/2019/papersubmit/

https://mizchi.hatenablog.com/entry/2014/01/20/090957

```
pandoc -f markdown-auto_identifiers -t latex -V fontsize=9pt body.md -o body.tex
platex robomech_201906_suenaga.tex
dvipdfmx robomech_201906_suenaga
xdg-open robomech_201906_suenaga.pdf
```
