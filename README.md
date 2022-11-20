# Venkat-Amith-Woonna---Resume

%-----------------------------------------------------------------------------------------------------------------------------------------------%
%	The MIT License (MIT)
%
%	Copyright (c) 2021 Jitin Nair
%
%	Permission is hereby granted, free of charge, to any person obtaining a copy
%	of this software and associated documentation files (the "Software"), to deal
%	in the Software without restriction, including without limitation the rights
%	to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
%	copies of the Software, and to permit persons to whom the Software is
%	furnished to do so, subject to the following conditions:
%	
%	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
%	IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
%	FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
%	AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
%	LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
%	OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
%	THE SOFTWARE.
%	
%
%-----------------------------------------------------------------------------------------------------------------------------------------------%

%----------------------------------------------------------------------------------------
%	DOCUMENT DEFINITION
%----------------------------------------------------------------------------------------

% article class because we want to fully customize the page and not use a cv template
\documentclass[a4paper,12pt]{article}

%----------------------------------------------------------------------------------------
%	FONT
%----------------------------------------------------------------------------------------

% % fontspec allows you to use TTF/OTF fonts directly
% \usepackage{fontspec}
% \defaultfontfeatures{Ligatures=TeX}

% % modified for ShareLaTeX use
% \setmainfont[
% SmallCapsFont = Fontin-SmallCaps.otf,
% BoldFont = Fontin-Bold.otf,
% ItalicFont = Fontin-Italic.otf
% ]
% {Fontin.otf}

%----------------------------------------------------------------------------------------
%	PACKAGES
%----------------------------------------------------------------------------------------
\usepackage{url}
\usepackage{parskip} 	

%other packages for formatting
\RequirePackage{color}
\RequirePackage{graphicx}
\usepackage[usenames,dvipsnames]{xcolor}
\usepackage[scale=0.9]{geometry}

%tabularx environment
\usepackage{tabularx}

%for lists within experience section
\usepackage{enumitem}

% centered version of 'X' col. type
\newcolumntype{C}{>{\centering\arraybackslash}X} 

%to prevent spillover of tabular into next pages
\usepackage{supertabular}
\usepackage{tabularx}
\newlength{\fullcollw}
\setlength{\fullcollw}{0.47\textwidth}

%custom \section
\usepackage{titlesec}				
\usepackage{multicol}
\usepackage{multirow}

%CV Sections inspired by: 
%http://stefano.italians.nl/archives/26
\titleformat{\section}{\Large\scshape\raggedright}{}{0em}{}[\titlerule]
\titlespacing{\section}{0pt}{10pt}{10pt}

%for publications
\usepackage[style=authoryear,sorting=ynt, maxbibnames=2]{biblatex}

%Setup hyperref package, and colours for links
\usepackage[unicode, draft=false]{hyperref}
\definecolor{linkcolour}{rgb}{0,0.2,0.6}
\hypersetup{colorlinks,breaklinks,urlcolor=linkcolour,linkcolor=linkcolour}
\addbibresource{citations.bib}
\setlength\bibitemsep{1em}

%for social icons
\usepackage{fontawesome5}

%debug page outer frames
%\usepackage{showframe}

%----------------------------------------------------------------------------------------
%	BEGIN DOCUMENT
%----------------------------------------------------------------------------------------
\begin{document}

% non-numbered pages
\pagestyle{empty} 

%----------------------------------------------------------------------------------------
%	TITLE
%----------------------------------------------------------------------------------------

% \begin{tabularx}{\linewidth}{ @{}X X@{} }
% \huge{Your Name}\vspace{2pt} & \hfill \emoji{incoming-envelope} email@email.com \\
% \raisebox{-0.05\height}\faGithub\ username \ | \
% \raisebox{-0.00\height}\faLinkedin\ username \ | \ \raisebox{-0.05\height}\faGlobe \ mysite.com  & \hfill \emoji{calling} number
% \end{tabularx}

\begin{tabularx}{\linewidth}{@{} C @{}}
\Huge{VENKAT AMITH WOONNA} \\[7.5pt]
\href{https://github.com/homealone07}{\raisebox{-0.05\height}\faGithub\ homealone07} \ $|$ \ 
\href{https://www.linkedin.com/in/venkat-amith-woonna-38bb721b8}{\raisebox{-0.05\height}\faLinkedin\ Venkat Amith} \ $|$ \ 
\href{mailto:venkatamithwoonna@gmail.com}{\raisebox{-0.05\height}\faEnvelope \ venkatamithwoonna@gmail.com} \ $|$ \ 
\href{tel:+000000000000}{\raisebox{-0.05\height}\faMobile \ +91 8520870730} \\
\end{tabularx}

%----------------------------------------------------------------------------------------
% EXPERIENCE SECTIONS
%----------------------------------------------------------------------------------------

%Interests/ Keywords/ Summary
\section{Summary}
Computer Science student at Vellore Institute of Technology, Chennai. 

Seeking opportunities to develop practical knowledge and seeking exciting opportunities related to the same. I am always curious about things and enjoy learning. I like to solve problems and fix errors. I am a detailed oriented person and I keep my goals and tasks organized. I believe that the skills I have attained from the dynamic environment and the competitive university life define me and I am looking forward to implementing and polishing
them in any opportunity that I receive. Aspiring to improve my problem-solving skills. Skilled in C++, C and python.


%Experience
\section{Work Experience}

\begin{tabularx}{\linewidth}{ @{}l r@{} }
\textbf{Principal Secretary } & \hfill Jan 2021 - present \\[3.75pt]
\multicolumn{2}{@{}X@{}}{Principal Secretary at Microsoft Innovations Club VIT CHENNAI

Organised a 24 hours hackathon on environment , organised a ctf and many more workshops and gained the experience of leadership}  \\
\end{tabularx}

\begin{tabularx}{\linewidth}{ @{}l r@{} }
\textbf{Design Lead} & \hfill May 2021 - present \\[3.75pt]
\multicolumn{2}{@{}X@{}}{Design Lead at NSS VIT CHENNAI and DAO COMMUNITY VIT CHENNAI

Specialised in graphic designing , poster designing and presentations}
\end{tabularx}

%Projects
\section{Projects}

\begin{tabularx}{\linewidth}{ @{}l r@{} }
\textbf{Smart E-business for small enterprise} & \hfill \href{https://github.com/homealone07/Connect-mern/tree/master}{Link to Demo} \\[3.75pt]
\multicolumn{2}{@{}X@{}}{A web application where all small enterprises and medium enterprises register and upload all the product details and make them available to the customers. Our project will also provide analysis and analytics of the products and management of capital of the enterprise.}.\\*[5pt]

~\\
\textbf{Phishing website detection from website URLs} & \hfill \href{https://github.com/Santhosh2231/Phishing-website-Detection}{Link to Demo} \\[3.75pt]
\multicolumn{2}{@{}X@{}}{
A website that will be used to detect whether a website is legitimate or phishing using Machine learning algorithms.In our project, we applied algorithms like Logistic Regression, Naive Bayes, Support vector Machine and Random Forest Classifier to the model that was developed. During testing, it was observed that the system worked well and as expected.Our project aims to improve the detection method for detecting phishing websites using machine learning technology}

\end{tabularx}

%----------------------------------------------------------------------------------------
%	EDUCATION
%----------------------------------------------------------------------------------------
\section{Education}
\begin{tabularx}{\linewidth}{@{}l X@{}}	

2020 - present & Bachelor's Degree at \textbf{Vellore Institute of Technology} \hfill (GPA: 8.4/10) \\ 

2020 & Class 12th State Board of Andhra Pradesh \hfill  (Grades) \\

2018 & Class 10th CBSE \hfill  (Grades) \\
\end{tabularx}

%----------------------------------------------------------------------------------------
%	PUBLICATIONS
%----------------------------------------------------------------------------------------

%----------------------------------------------------------------------------------------
%	SKILLS
%----------------------------------------------------------------------------------------
\section{Skills}
\begin{tabularx}{\linewidth}{@{}l X@{}}
C++ , Python , MATLAB , R-Studio , LaTeX &  \normalsize{These are some skills where i am Technically skillful}\\

Graphic Designing , Leadership , Communication &  \normalsize{There are some of my skills that show case the creative and non-technical phase of myself}\\  
\end{tabularx}

\vfill
\center{\footnotesize Last updated: \today}

\end{document}
