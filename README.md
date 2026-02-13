# cooltex
Collection of useful latex macros

Just add `cooltex.sty` in your latex project.

> [!NOTE]
> Remember to add `\usepackage{cooltex}` on top of your latex document!





## Tiny demo
```latex
\usepackage{cooltex}

\begin{simplebox}

\[
\foode{x^2 + x}{0}{2}
\]

This is how you write an ode with a single command
\end{simplebox}

Just some text for reference...

\begin{titlebox}{Linear programming problem}
This is a linear programming problem with a title:

\[
  \lp{\min_c}{c^Tx}{
    x \geq 0,
    AX > b,
    CX < d  
  }
\]
\end{titlebox}



\begin{codebox}{language=python, shadow=true}
df = pd.DataFrame()

def f(x,y):
    return x+y
\end{codebox}


\begin{simplebox}

Code inside a simplebox

You can easily remove shadow and rownumber

\begin{codebox}{language=cpp, rownumber=false, shadow=false, highlight={3}}
int x = 5;
\end{codebox}

You can wrap boxes!

\end{simplebox}
```

<p align="center">
<img width="584" height="800" alt="image" src="https://github.com/user-attachments/assets/7f33ed3b-6bee-4263-a081-6fd73471195e" />
</p>




