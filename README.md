\section{Hypothesis Testing}

Hypothesis testing is a statistical process used to make inferences about a population based on a sample. It involves testing an assumption (the hypothesis) to determine if there is sufficient evidence to support or reject it. Below are the key concepts:

\subsection{Types of Hypotheses}
\begin{itemize}
    \item \textbf{Null Hypothesis (\(H_0\))}: This is the default assumption that there is no effect, no difference, or no relationship. For example, "The mean income of two groups is the same."
    \item \textbf{Alternative Hypothesis (\(H_a\))}: This is the statement we want to test against the null hypothesis. It suggests there is an effect, difference, or relationship. For example, "The mean income of two groups is different."
\end{itemize}

\subsection{Steps in Hypothesis Testing}
\begin{enumerate}
    \item \textbf{Define the Hypotheses}: Formulate \(H_0\) and \(H_a\).
    \item \textbf{Set the Significance Level (\(\alpha\))}: Typically, \(\alpha = 0.05\), which means there is a 5\% risk of rejecting the null hypothesis when it is true.
    \item \textbf{Choose the Test Statistic}: Depending on the data and hypothesis, use a test such as a t-test, z-test, chi-square test, or ANOVA.
    \item \textbf{Calculate the P-value}: The probability of obtaining the observed results if \(H_0\) is true.
    \item \textbf{Make a Decision}:
    \begin{itemize}
        \item If \(P\)-value \(\leq \alpha\), reject \(H_0\) (evidence supports \(H_a\)).
        \item If \(P\)-value \(> \alpha\), fail to reject \(H_0\) (not enough evidence to support \(H_a\)).
    \end{itemize}
\end{enumerate}

\subsection{Example of Hypothesis Testing}
\begin{itemize}
    \item \textbf{Scenario}: A company wants to test if a new drug is more effective than the current one.
    \item \(H_0\): The new drug is equally effective as the current one.
    \item \(H_a\): The new drug is more effective than the current one.
    \item Perform a test (e.g., t-test), calculate the p-value, and compare it to \(\alpha\) to make a conclusion.
\end{itemize}

\subsection{Types of Errors}
\begin{itemize}
    \item \textbf{Type I Error (\(\alpha\))}: Rejecting \(H_0\) when it is true.
    \item \textbf{Type II Error (\(\beta\))}: Failing to reject \(H_0\) when it is false.
\end{itemize}

Hypothesis testing is widely used in statistics to make informed decisions based on data.
