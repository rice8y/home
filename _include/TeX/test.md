# Test

```latex
\documentclass{ltjsarticle}
\usepackage{texshade}
\thispagestyle{empty}
\begin{document}
\begin{texshade}{sample.fasta}
  \shadingmode[charge]{functional}
  \shadeallresidues
  \fingerprint{360}
  \gapchar{rule}
  \showlegend
\end{texshade}
\end{document}
```