# Foro_Foro-acad-mico-5
\documentclass[12pt,a4paper]{article}

% ---------- Paquetes ----------
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage[spanish,es-noshorthands]{babel}
\usepackage{mathptmx}          % Fuente tipo Times New Roman
\usepackage[margin=2.5cm]{geometry}
\usepackage{setspace}
\usepackage{csquotes}
\usepackage{indentfirst}
\usepackage[hidelinks]{hyperref}

\onehalfspacing
\setlength{\parindent}{1.25cm}
\setlength{\parskip}{0pt}

% ---------- Documento ----------
\title{\textbf{Cómo garantizar la calidad de un proyecto de TI}}
\author{Melany Romero\\[0.3em]
       
\date{\today}

\begin{document}

\maketitle
\thispagestyle{empty}

\begin{abstract}
\noindent
La calidad en los proyectos de tecnologías de la información (TI) no es una etapa final, sino un proceso continuo que acompaña todo el ciclo de vida del proyecto. Este ensayo analiza los elementos que permiten garantizarla: la definición clara de requisitos, el uso de estándares y marcos de referencia, las pruebas, la gestión de riesgos y cambios, la medición mediante indicadores y el factor humano.
\end{abstract}

\newpage
\setcounter{page}{1}

% ---------- Introducción ----------
\section{Introducción}

La calidad en un proyecto de tecnologías de la información (TI) no es un paso final, sino un proceso continuo que acompaña todo el ciclo de vida del proyecto. Según el \textit{Project Management Institute} \cite{pmi2021}, la gestión de la calidad abarca planificar, gestionar y controlar la calidad. Muchos proyectos de TI fracasan por requisitos mal definidos, falta de pruebas o mala comunicación, y no solo por errores técnicos. Por ello, garantizar la calidad exige combinar procesos, personas y herramientas.

% ---------- Desarrollo ----------
\section{Desarrollo}

\subsection{Definición clara de requisitos}

La calidad comienza con una definición clara de requisitos. Cuando los interesados y el equipo acuerdan por escrito qué se va a construir y con qué criterios de aceptación, se reducen los retrabajos, que son una de las principales causas de sobrecostos.

\subsection{Estándares y marcos de referencia}

Es necesario adoptar estándares y marcos de referencia. Normas como ISO/IEC 25010, que define el modelo de calidad del producto de software \cite{iso25010}, e ISO 9001, orientada a los sistemas de gestión de calidad \cite{iso9001}, ofrecen buenas prácticas probadas. A ello se suman modelos como CMMI e ITIL y metodologías de trabajo, ya sean ágiles o tradicionales, que incorporan revisiones periódicas.

\subsection{Pruebas y automatización}

Las pruebas son fundamentales. Incluyen pruebas unitarias, de integración, de sistema y de aceptación del usuario, además de revisiones de código y de seguridad. Automatizarlas mediante integración y entrega continuas (CI/CD) permite detectar errores de forma temprana, cuando corregirlos resulta menos costoso.

\subsection{Gestión de riesgos, control de cambios y métricas}

La gestión de riesgos y el control de cambios evitan que el alcance crezca sin control y afecte los tiempos y la calidad. Esto se complementa con métricas e indicadores, como la densidad de defectos, el cumplimiento del cronograma y la satisfacción del cliente, que permiten tomar decisiones basadas en datos.

\subsection{El factor humano}

Un equipo capacitado, con roles definidos y buena comunicación, cumple mejor los estándares. La retroalimentación constante y las lecciones aprendidas cierran el ciclo de mejora continua.

% ---------- Conclusión ----------
\section{Conclusión}

Garantizar la calidad de un proyecto de TI requiere planificación, estándares, pruebas, control de cambios, medición y un equipo comprometido. Cuando estos elementos trabajan de forma conjunta, el proyecto no solo cumple con el tiempo, el costo y el alcance, sino que también satisface las necesidades reales del usuario.

% ---------- Referencias ----------
\begin{thebibliography}{9}

\bibitem{pmi2021}
Project Management Institute. (2021).
\textit{Guía de los fundamentos para la dirección de proyectos (Guía del PMBOK)} (7.ª ed.).
Project Management Institute.

\bibitem{iso25010}
International Organization for Standardization. (2011).
\textit{ISO/IEC 25010: Systems and software engineering — Systems and software Quality Requirements and Evaluation (SQuaRE) — System and software quality models}.
ISO.

\bibitem{iso9001}
International Organization for Standardization. (2015).
\textit{ISO 9001: Sistemas de gestión de la calidad — Requisitos}.
ISO.

\end{thebibliography}

\end{document}
