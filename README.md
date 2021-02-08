# GAGTA 2018

This repo contains a poster I presented at GAGTA in 2018.

[![CC BY 4.0][cc-by-shield]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

## Structure

 - The figures have been separated into standalone files in the `figure` directory. (This reduce time when recompiling the poster.)
 - The poster content is in `poster.tex` with references in `poster.bib`

## How to Compile

To build everything at once, you can run the command:

```bash
latexmk -cd -pdf -interaction=nonstopmode figure/*/*.tex *.tex
```

In summary:
 - compile the figues under the `figure` directory first; then
 - compile `poster.tex` with biber

## Download Compiled Version

You can download a precompiled version of the slides from the [GitHub Releases page](https://github.com/alexbishop/gagta-2018/releases).

## Using the Slides

If you find my slides or latex code useful, I would be interested in hearing from you.
Feel free to contact me at alexbishop1234@gmail.com.
