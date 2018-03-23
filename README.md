# ai-notes
Notes from the CS5201 (Object Oriented Numerical Modeling) class at Missouri S&amp;T.

If you have trouble compiling these notes, here's what I had to do to get it working:

```
# make tlmgr work if you've never used it?
sudo apt install xzdec
sudo tlmgr init-usertree

# used packages
tlmgr install nag upquote units siunitx enumitem tocloft forest pgf pgfopts etoolbox elocalloc environ inlinedef trimspaces algorithmicx pgf-umlcd
```

Then you can do `xelatex master.tex` and you're good to go! At the moment, `xelatex` is needed because `pdflatex` doesn't support font-spec, which is used to change the font. I might change this.

Thanks much to Illya Starikov for his [AI notes](https://github.com/IllyaStarikov/ai-notes) as a base.