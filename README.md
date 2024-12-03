
%-------------------------
% Resume in Latex
% Author : Jake Gutierrez
% Based off of: https://github.com/sb2nov/resume
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}


%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\classesList}[4]{
    \item\small{
        {#1 #2 #3 #4 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------
% \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
%   \textbf{\href{http://sourabhbajaj.com/}{\Large Sourabh Bajaj}} & Email : \href{mailto:sourabh@sourabhbajaj.com}{sourabh@sourabhbajaj.com}\\
%   \href{http://sourabhbajaj.com/}{http://www.sourabhbajaj.com} & Mobile : +1-123-456-7890 \\
% \end{tabular*}

\begin{center}
    {\Huge SARIKONDA SAI CHARAN RAJU} \\ \vspace{1pt}
    Hyderabad,Telangana
    \small \raisebox{-0.1\height}\faPhone\ +91-9666553814 ~\\ \vspace{1pt}
   \href{mailto:x@gmail.com}{\raisebox{-0.2\height}\faEnvelope\  \underline{charanraju0321@gmail.com}} ~ 
    \href{https://linkedin.com/in//}{\raisebox{-0.2\height}\faLinkedin\ \underline{saicharanrajus}}  ~
    \vspace{-8pt}
\end{center}


%-----------EDUCATION-----------
\section{EDUCATION}
  \resumeSubHeadingListStart
    \resumeSubheading
      {MALLAREDDY ENGINEERING COLLEGE}{Aug 2020- May 2024}
      { Bachelor of Technology in Information Technology}{Hyderabad,Telangana}
  \resumeSubHeadingListEnd
    \resumeSubheading
      { Narayana Junior Colege}{Jun 2018– May 2020}
      {Mathematics ,Physics and Chemistry}{Hyderabad,Telangana}
     \resumeSubHeadingListEnd

%------RELEVANT COURSEWORK-------
\section{KEY SKILLS}
    %\resumeSubHeadingListStart
        \begin{multicols}{4}
            \begin{itemize}[itemsep=3pt, parsep=3pt]
                \item SQL
                \item Selenium
                \item Software Methodology
                \item Database Management
                \item power BI
                \item Data Structures
                
                
                \item Machine Learning 
                \item Advanced Excel
                
                \item Java
                
                \item Python 
                 
                
                

            \end{itemize}
        \end{multicols}
        \vspace*{1.0\multicolsep}
    %\resumeSubHeadingListEnd



%-----------PROJECTS-----------
\section{PROJECTS}
    \vspace{-5pt}
    \resumeSubHeadingListStart
        \resumeProjectHeading
          {\textbf{TIME SERIES ANALYSIS OF AIR POLLUTANTS (PM2.5) USING LSTM ALGORITHM
} $|$ \emph{}}{January 2022}
          \resumeItemListStart
          
            \resumeItem{Preprocessed large-scale environmental data and designed LSTM architectures for predictive models.}
             \resumeItem{Conducted exploratory data analysis (EDA) to identify trends, seasonality, and patterns in air pollutant levels, aiding decision-makers in environmental management.}
             \resumeItem{Acquired and processed extensive datasets of air quality measurements using SQL programming, ensuring data quality and integrity.}
             \resumeItem{Produced accurate forecasts of air quality, demonstrating proficiency in data analytics, machine learning, and environmental science.}
             
            
            \resumeItemListEnd
          \vspace{-13pt}

          
    
    \resumeSubHeadingListStart
        \resumeProjectHeading 
        {\textbf{Anomaly Detection System Based on User password typing pattern
} $|$ \emph{}}{December 2023}
           \resumeItemListStart
           \resumeItem{Developed and implemented an Anomaly Detection System using regex programming to analyze user password typing patterns, enhancing security by identifying irregularities in user behavior.}
           \resumeItem{Showcased proficiency in data analysis, machine learning, and cybersecurity through the design and deployment of advanced security solutions.}
           \resumeItem{Leveraged One-Class Classification (OCC) algorithms to model and identify normal typing patterns, detecting deviations indicative of potential security breaches.}
           \resumeItem{Demonstrated a sophisticated understanding of machine learning techniques tailored for outlier detection, improving the system’s ability to distinguish legitimate from suspicious login attempts.}
        \vspace{-13pt}
      \resumeItemListEnd
      \resumeProjectHeading
    
    
    \resumeSubHeadingListEnd
\vspace{-15pt}


%
%-----------PROGRAMMING SKILLS/CERTIFICATIONS-----------
\section{CERTIFICATIONS}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{MICROSOFT} {: Microsoft Python Programming} \\
     \textbf{Hacker Rank}  {   : Python (Basic)} \\
     \hspace{2.3cm}
     \textbf{}{   : SQL(Basic) } \\
     \hspace{2.3cm}
     \textbf{}{ : SQL(Intermediate) } \\
    }}
 \end{itemize}
 \vspace{-16pt}


%-----------INVOLVEMENT---------------
\section{Leadership / Extracurricular}
    \resumeSubHeadingListStart
        \resumeSubheading{National Service Scheme}{MallaReddy Engineering College}{Coordinator}{}
            \resumeItemListStart
                \resumeItem{Served as the dedicated National Service Scheme (NSS) Coordinator, overseeing and coordinating various community service initiatives and projects involving.}
                \resumeItem{Compiled and submitted detailed reports on NSS activities, documenting the impact and outcomes achieved, and ensuring compliance with organizational and regulatory requirements.}
            \resumeItemListEnd
        
    \resumeSubHeadingListEnd


\end{document}
