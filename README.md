```latex
%Website
%https://tikz.dev/

%Draw Plaid
\draw[very thin,color=gray!15,step=.5] (-5,-1.5) grid (5,2.5);

%Take Coordinates
\foreach \i in {-4,...,-2,-1,1,2,...,4}
\draw[] (\i,.1)--(\i,-.1) node[below] {$\i$};%x-axis
\foreach \i in {-1,1,2}
\draw[] (.1,\i)--(-.1,\i) node[left] {$\i$};%y-axis
```

%Pattern
\usetikzlibrary {patterns,patterns.meta}
\draw[pattern={Lines[angle=45,distance={12pt/sqrt(3)}]}, pattern color=blue]
