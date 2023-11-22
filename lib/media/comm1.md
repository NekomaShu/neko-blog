```tikz
\usepackage{tikz-cd}
\tikzcdset{scale cd/.style={every label/.append style={scale=#1},
    cells={nodes={scale=#1}}}}
\begin{document}
\begin{tikzcd}[scale cd=2, sep=huge]
A \arrow[r, "f"] \arrow[d, "e"']                  & B \arrow[d, "g"] \arrow[rrdd, "g'", bend left] &  &    \\
C \arrow[r, "h"'] \arrow[rrrd, "h'"', bend right] & D \arrow[rrd, "q"]                             &  &    \\
                                                  &                                                &  & D'
\end{tikzcd}
\end{document}
```
