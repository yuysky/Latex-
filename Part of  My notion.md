## Part of  My notion
```latex
\documentclass{article}
\usepackage{graphicx} % Required for inserting images
\graphicspath{{图片/}}

\title{My notion of Latex}
\author{yuysky \thanks{He is willing to be a happy dog.}}
\date{April 25,2023}

\begin{document}

\maketitle
\tableofcontents
\newpage

We have now added a article with title, author and date.

% 这里是注释部分，不会出现在文本中

% 粗体、斜体和下横线
Some of the \textbf{greatest} 
discoveries in \underline{science} 
were made by \textbf{\textit{accident}}.

% \emph的应用
Some of the greatest \emph{discoveries} in science 
were made by accident.

\textit{Some of the greatest \emph{discoveries} 
in science were made by accident.}

\textbf{Some of the greatest \emph{discoveries} 
in science were made by accident.}

% 插入图片

% The \includegraphcs command is 
% provided (implemented) by the 
% graphicx package
\begin{figure}[htp]
    \centering
    \includegraphics[width=0.75\textwidth]{图片/fa392f7127505745a685cf16a0f3508.jpg}
    \caption{chatting picture}
    \label{fig:chatting}
\end{figure}

There's a picture from the chatting with my girlfriend.It has
some interesting meaning:
\begin{itemize}
    \item I'm curious about the reaction of her when I do something interesting.
    \item She feels a little shocked when I said that.
    \item She is so cute like the cat in the emoji.
\end{itemize}

But I don't think we should pay to the author of the emoji:
\begin{enumerate}
    \item We can use almost all of the emoji without money.
    \item Even there is not emoji, she can still transfer her feelings with Chinese not Spanish.
    \item The cute cat is not real, but she is really cute.
\end{enumerate}

One day, I said to her, ' do you know $E = mc^2$? ' She feel a little confused, and angrily answered ,' who don't know 
\begin{equation}
    E = mc^2
\end{equation}
? Do you think I'm a fool? You don't have a good fruit to eat.'
I feel unhappy because she didn't understand what I said. So I fight back,'well, why did I not have a good fruit to eat? Can you write an article to proof that?'
She write the article within 2 minutes and send it to me with a strange smile.

\begin{abstract}
    The article is about why yuysky doesn't have a good fruit to eat, and proof  the logic that yuysky is a stupid pig, never a happy dog.  
\end{abstract}

\section{a good fruit}
A good fruit is what all the people want to get. However, it is not available just with the patting on the ass of horse.\newline The right place of the patting is a very important factor concerning whether you can eat a good fruit.

\subsection{why yuysky not get?}
Yuysky patted on the wrong place of the ass so that he not only didn't get a good fruit, but also need to compensate the emotional damages.

\section{why not a dog}
Because yuysky never wakes up in the beautiful morning and night, he is not qualified to looK after the house which is the duty of a dog. 
\subsection{why not a happy dog}
Can a dog without the ability of keeping the house be happy? It doesn't need to proof.
\newline\newline\newline\newline

\centering
Fine, yuysky is a pig.

\end{document}
```

