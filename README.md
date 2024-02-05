## Soil-fertility-prediction

\documentclass{article}
\usepackage{graphicx}
\usepackage{float}

\title{Soil Fertility Prediction Report}
\author{Your Name}
\date{\today}

\begin{document}

\maketitle

\section*{Introduction}
This report presents a soil fertility prediction study where we employed standardization and outlier removal through boxplot analysis as part of the preprocessing steps. Four classification models, namely Logistic Regression, Random Forest Classifier, Decision Tree, and Artificial Neural Network (ANN), were trained and evaluated for predicting soil fertility.

\section*{Preprocessing}
For preprocessing, we standardized the features and removed outliers using boxplot analysis. Standardization ensures that all features have a mean of 0 and a standard deviation of 1, promoting stable model training. Outliers were identified and removed based on their representation in boxplots.

\section*{Model Training}

\subsection*{Logistic Regression}
The Logistic Regression model was trained using the preprocessed data.

\subsection*{Random Forest Classifier}
The Random Forest Classifier was trained to capture complex relationships within the dataset.

\subsection*{Decision Tree}
A Decision Tree model was employed for its interpretability and simplicity.

\subsection*{Artificial Neural Network (ANN)}
The ANN model, a deep learning approach, was utilized for its ability to capture intricate patterns in the data.

\section*{Model Evaluation}

\subsection*{Logistic Regression}
The Logistic Regression model achieved an accuracy of $XX\%$. The confusion matrix is presented in Figure~\ref{fig:logreg_conf_matrix}.

\begin{figure}[H]
    \centering
    \includegraphics[width=0.5\textwidth]{logreg_conf_matrix.png}
    \caption{Confusion Matrix for Logistic Regression}
    \label{fig:logreg_conf_matrix}
\end{figure}

\subsection*{Random Forest Classifier}
The Random Forest Classifier yielded an accuracy of $XX\%$. The corresponding confusion matrix is shown in Figure~\ref{fig:rf_conf_matrix}.

\begin{figure}[H]
    \centering
    \includegraphics[width=0.5\textwidth]{rf_conf_matrix.png}
    \caption{Confusion Matrix for Random Forest Classifier}
    \label{fig:rf_conf_matrix}
\end{figure}

\subsection*{Decision Tree}
The Decision Tree model achieved an accuracy of $XX\%$. The confusion matrix is displayed in Figure~\ref{fig:dt_conf_matrix}.

\begin{figure}[H]
    \centering
    \includegraphics[width=0.5\textwidth]{dt_conf_matrix.png}
    \caption{Confusion Matrix for Decision Tree}
    \label{fig:dt_conf_matrix}
\end{figure}

\subsection*{Artificial Neural Network (ANN)}
The ANN model demonstrated an accuracy of $XX\%$. The confusion matrix is illustrated in Figure~\ref{fig:ann_conf_matrix}.

\begin{figure}[H]
    \centering
    \includegraphics[width=0.5\textwidth]{ann_conf_matrix.png}
    \caption{Confusion Matrix for Artificial Neural Network (ANN)}
    \label{fig:ann_conf_matrix}
\end{figure}

\end{document}
