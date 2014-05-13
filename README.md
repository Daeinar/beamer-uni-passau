### Inofficial Universität Passau LaTeX Beamer Theme

####Screenshots

<div align="center"><img src="https://github.com/Daeinar/beamer-uni-passau/blob/master/screenshots/1.png?raw=true" alt="Title Page"/></div>
<div align="center"><img src="https://github.com/Daeinar/beamer-uni-passau/blob/master/screenshots/2.png?raw=true" alt="Slide 1"/></div>
<div align="center"><img src="https://github.com/Daeinar/beamer-uni-passau/blob/master/screenshots/3.png?raw=true" alt="Slide 2"/></div>

####Usage
Copy `beamerthemeunipassau.sty`, `beamerouterthemeunipassau.sty` and `logo.pdf` to the folder containing your main slide file. Then include the style by adding
```
\mode<presentation>
{
  \usetheme{unipassau}
  \setbeamercovered{transparent}
}
\logo{\includegraphics[width=3cm]{logo.pdf}\vspace{218pt}\hspace{8pt}}
```
to your main slide file.

####Examples
See `slides.tex` and `slides.pdf`.

####License
This LaTeX beamer theme is released under the [CC0 license](https://creativecommons.org/publicdomain/zero/1.0/). The full license text is included in the file `LICENSE`.

