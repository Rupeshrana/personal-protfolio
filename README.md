# personal-protfolio
%-------------------------
% Resume in Latex
% Author : Chandramouli Haldar
% License : MIT
%------------------------

%---- Required Packages and Functions ----

\documentclass[a4paper,11pt]{article}
\usepackage{latexsym}
\usepackage{xcolor}
\usepackage{float}
\usepackage{ragged2e}
\usepackage[empty]{fullpage}
\usepackage{wrapfig}
\usepackage{lipsum}
\usepackage{tabularx}
\usepackage{titlesec}
\usepackage{geometry}
\usepackage{marvosym}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage{multicol}
\usepackage{graphicx}
\usepackage{cfr-lm}
\usepackage[T1]{fontenc}
\setlength{\multicolsep}{0pt} 
\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}
\setlength{\footskip}{4.08003pt} % Fix for the footskip warning}
\geometry{left=1.4cm, top=0.8cm, right=1.2cm, bottom=1cm}
% Adjust margins
%\addtolength{\oddsidemargin}{-0.5in}
%\addtolength{\evensidemargin}{-0.5in}
%\addtolength{\textwidth}{1in}
\usepackage[most]{tcolorbox}
\tcbset{
	frame code={}
	center title,
	left=0pt,
	right=0pt,
	top=0pt,
	bottom=0pt,
	colback=gray!20,
	colframe=white,
	width=\dimexpr\textwidth\relax,
	enlarge left by=-2mm,
	boxsep=4pt,
	arc=0pt,outer arc=0pt,
}

\urlstyle{same}

\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-7pt}]

%-------------------------
% Custom commands
\newcommand{\resumeItem}[2]{
  \item{
    \textbf{#1}{:\hspace{0.5mm}#2 \vspace{-0.5mm}}
  }
}

\newcommand{\resumePOR}[3]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1},\hspace{0.3mm}#2 & \textit{\small{#3}} 
    \end{tabular*}
    \vspace{-2mm}
}

\newcommand{\resumeSubheading}[4]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.98\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1} & \textit{\footnotesize{#4}} \\
        \textit{\footnotesize{#3}} &  \footnotesize{#2}\\
    \end{tabular*}
    \vspace{-2.4mm}
}

\newcommand{\resumeProject}[4]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.98\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1} & \textit{\footnotesize{#3}} \\
        \footnotesize{\textit{#2}} & \footnotesize{#4}
    \end{tabular*}
    \vspace{-2.4mm}
}

\newcommand{\resumeSubItem}[2]{\resumeItem{#1}{#2}\vspace{-4pt}}

% \renewcommand{\labelitemii}{$\circ$}
\renewcommand{\labelitemi}{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*,labelsep=0mm]}
\newcommand{\resumeHeadingSkillStart}{\begin{itemize}[leftmargin=*,itemsep=1.7mm, rightmargin=2ex]}
\newcommand{\resumeItemListStart}{\begin{justify}\begin{itemize}[leftmargin=3ex, rightmargin=2ex, noitemsep,labelsep=1.2mm,itemsep=0mm]\small}

\newcommand{\resumeSubHeadingListEnd}{\end{itemize}\vspace{2mm}}
\newcommand{\resumeHeadingSkillEnd}{\end{itemize}\vspace{-2mm}}
\newcommand{\resumeItemListEnd}{\end{itemize}\end{justify}\vspace{-2mm}}
\newcommand{\cvsection}[1]{%
\vspace{2mm}
\begin{tcolorbox}
    \textbf{\large #1}
\end{tcolorbox}
    \vspace{-4mm}
}

\newcolumntype{L}{>{\raggedright\arraybackslash}X}%
\newcolumntype{R}{>{\raggedleft\arraybackslash}X}%
\newcolumntype{C}{>{\centering\arraybackslash}X}%
%---- End of Packages and Functions ------

%-------------------------------------------
%%%%%%  CV STARTS HERE  %%%%%%%%%%%
%%%%%% DEFINE ELEMENTS HERE %%%%%%%
\newcommand{\name}{Students Name} % Your Name
\newcommand{\course}{B.Tech.} % Your Course
\newcommand{\department}{ CSE - DS}
\newcommand{\roll}{XXXXXXXXX} % Your Roll No.
\newcommand{\phone}{XXXXXXXXX} % Your Phone Number
\newcommand{\emaila}{something@example.com} %Email 1
\newcommand{\emailb}{rupeshkrrana2003@gmail.com} %Email 2

\newcommand{\website}{https://example.com} %Website
\newcommand{\linkedin}{LINKEDINUSERID} %linkedin




\begin{document}
\fontfamily{cmr}\selectfont
%----------HEADING-----------------
\parbox{2.8cm}{%



}\parbox{\dimexpr\linewidth-0.1cm\relax}{
\begin{tabularx}{\linewidth}{L R} 
  \textbf{\LARGE SUNNY KUMAR } & +91-6200429546\\
  \course &  \href{mailto:example@lol.com}{sunnykumar7482816501@gmail.com}\\
  {Haldia Institute Of Technology} & \href{https://www.linkedin.com/in/sunny-1st-4bb41a25a}{Sunny Kumar} 
    \end{tabularx}
}



% %-----------EDUCATION-----------------
\section{\textbf{Education}}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Haldia Institute Of Technology}{Purba Medinipur, India}
      {B.Tech. - Computer Science \& Engineering (Artificial Intelligence and Machine Learning)  ;  CGPA: 7.38}{2022 - 2026}

      \resumeSubheading
      {J.J.COLLEGE,ARA,BHOJPUR, Arrah }{Arrah,Bihar}
      {INTERMEDIATE;  Percentage:62.60}{2019 - 2021}

       \resumeSubheading
      {R D M HIGH SCHOOL GADHANI BHOJPUR, Arrah }{Arrah,Bihar}
      {Metriculation;  Percentage:77}{2019}
      
\resumeSubHeadingListEnd

  
      

\vspace{-5pt}
% %-----------SKILLS-----------------

\section{\textbf{Skills}}
\vspace{-0.4mm}
 \resumeHeadingSkillStart
  \resumeSubItem{Programming Languages:}
    { C++ , Java, Python(Pandas, NumPy)}
  \resumeSubItem{Web Technologies:}
    { HTML, CSS , JavaScript , React }
  \resumeSubItem{Database Systems:}
    { MySQL}
  \resumeSubItem{Data Science \& Machine Learning:}
    { Data Visualization (Matplotlib, Seaborn, Plotly) ,  Scikit-learn}
  \resumeSubItem{Version Control:}
    { Git, GitHub}
  \resumeSubItem{Tools:}
    { Jupyter Notebook , VS Code}
  
 \resumeHeadingSkillEnd



%-----------PROJECTS-----------------
\section{\textbf{Projects}}
\vspace{-0.4mm}
\resumeSubHeadingListStart


\resumeProject
    {\href{https://github.com/Rupeshrana/SMS-spam-classsifier}{Heart Disease Detection using Machine Learning :}}
    {}
    {04/2023 - 05/2023}
    
\resumeItemListStart
    \item-Implemented and compared three machine learning algorithms—Logistic Regression, SVM, and Decision Tree. 
    \item Achieved 90\% accuracy using the Decision Tree model, making it the most effective among the three. 
   \item Built and deployed a Flask-based web application for real-time predictions, with an interactive interface to ensure user-friendly experience 
  
\resumeItemListEnd

\resumeProject
    {\href{https://github.com/Rupeshrana/Portfolio}{Medical Insurance Cost Prediction }}
    
    {03/2024 - 05/2024}

\resumeItemListStart
    \item \textbf{Tech Stack:} Machine Learning ,Python, Pandas, NumPy, Algorithms, Scikit-Learn  
    \item This project predicts medical insurance costs using machine learning algorithms like Linear Regression and Random Forest 
    \item Implemented in Python with Pandas, Scikit-learn, and data visualization tools, it analyzes factors like age, BMI, and smoking habits to deliver accurate cost estimates, aiding individuals and insurance providers 
     
\resumeItemListEnd
\resumeSubHeadingListEnd
\vspace{-5.5mm}




\section{\textbf{Training & Internships}}
\vspace{-0.4mm}
\resumeSubHeadingListStart
\resumePOR
    {DATA SCIENCE INTERN  } % Certification Name
    {SABUDH FOUNDATION  }
   
    {01 Jan, 2025  - 30 Jun, 2025 } % Duration
    
\resumeSubHeadingListEnd

\vspace{-6mm}
\vspace{-0.4mm}
\resumeSubHeadingListStart
\resumePOR
    {In House Training - Machine Learning Institute Name: Databits Technologia } % Certification Name
   
    {06 Jan, 2025  -  06 Mar, 202 5} % Duration
    
\resumeSubHeadingListEnd

\vspace{-6mm}
\vspace{-0.4mm}
\resumeSubHeadingListStart
\resumePOR
    {Agentic AI: From Learner to Builder – Become an AI Agent Architec } % Certification Name
    {IBM SkillsBuild } % Issuer
   
    
\resumeSubHeadingListEnd

\vspace{-6mm}

%-----------ACHIEVEMENTS-----------------
\section{\textbf{Achievements}}
\vspace{-0.2mm}
\resumeSubHeadingListStart
\resumePOR{ Leetcode}{\href{https://leetcode.com/u/RupeshRana/}{Achieved Leetcode badge for Solving Coding Problems Consistently }}{}

\resumeSubHeadingListEnd
\vspace{-6mm}

\section{\textbf{Positions of Responsibility}}
\vspace{-0.4mm}
\resumeSubHeadingListStart
    \resumePOR{\href{www.Position.com}{ PUBLIC RELATIONS (PR)
}, } % Position
    { TARUGURDIANS} %Club,Event
    {2023-2026} %Tenure Period

   



\resumeSubHeadingListEnd
\vspace{-2mm}
% \hspace*{-5mm}\rule{1.035\textwidth}{0.1mm}

\vspace{-4mm}

%-------------------------------------------
\end{document}
