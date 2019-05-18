# Text based quiz games

These programs can be entered using any text editor or IDE, but I suggest using [the Mu editor](https://codewith.mu/)
because it comes with Python, Pygame Zero and other libraries all pre-installed in one easy download.

## Hello, world

The traditional first program used to make sure Python is working and that we can run programs. 

\begin{codelisting}
\codecaption{Hello, world}
\label{code:hello}
<<(programs/01_intro.py)
\end{codelisting}

\noindent If using the Mu editor:

* Click the mode button and make sure the mode is set to 'Python3'
* Type in the program. 
* Click 'Save' and enter a name for the program.
* Click 'Run'.

## Getting input from the keyboard

When you run this program it will pause and wait for you to enter some
text with the keyboard, followed by the return key. The text you enter
is stored in a variable, *x*.

\begin{codelisting}
\codecaption{Getting input from the keyboard}
\label{code:input}
<<(programs/02_input.py)

\end{codelisting}

\noindent Can you add some names of your friends with different messages for each?

## Decisions: if, elif, else

This is how I added another name.

\begin{codelisting}
\codecaption{Decisions: if, elif, else}
\label{code:input2}
<<(programs/03_input2.py, options: "hl_lines": [6, 7, 8, 9])
\end{codelisting}

\noindent Program~\ref{code:input2} is very similar to Program~\ref{code:input}. The new lines have been highlighted.  You can either modify Program~\ref{code:input} or else create
a new file and use copy and paste to copy the code from the old program into the new.

## A random maths question

\begin{codelisting}
\codecaption{A random maths question}
\label{code:maths}
<<(programs/04_maths_question.py)
\end{codelisting}

* add some more questions, e.g.
   * instead of 7, use another random number
   * use a bigger random number
   * multiply or divide or subtract numbers
* print how many questions the player got correct at the end.

## Keeping score

\begin{codelisting}
\codecaption{Keeping score}
\label{code:maths2}
<<(programs/05_maths_question2.py)
\end{codelisting}

## Guessing game with a loop

\begin{codelisting}
\codecaption{Guessing game with a loop}
\label{code:loop}
<<(programs/06_loop.py)
\end{codelisting}

* give a hint to the player when they are wrong
* print how many guesses at the end

## Improved guessing game

\begin{codelisting}
\codecaption{Improved guessing game}
\label{code:loop2}
<<(programs/07_loop2.py)
\end{codelisting}