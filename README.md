\documentclass[11pt,a4paper]{article}

\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage[french,english]{babel}
\usepackage[margin=2.5cm]{geometry}
\usepackage{amsmath, amsfonts, amssymb}
\usepackage{enumitem}
\usepackage{tcolorbox}
\usepackage{titlesec}
\usepackage{fancyhdr}
\usepackage{xcolor}
\usepackage{hyperref}
\usepackage{orcidlink}

\hypersetup{
    pdfauthor={Dr. Mohamed Nour Kayad},
    pdftitle={OECQ-V1: Hierarchical Active Safety Architecture with Thermodynamic Arbitration by Green AI},
    colorlinks=true,
    linkcolor=darkblue,
    urlcolor=darkblue
}

\definecolor{darkblue}{rgb}{0.0, 0.0, 0.4}
\definecolor{safetyred}{rgb}{0.7, 0.0, 0.0}

\titleformat{\section}{\large\bfseries\color{darkblue}}{}{0em}{}[\titlerule]
\titlespacing*{\section}{0pt}{2ex}{1.5ex}

\pagestyle{fancy}
\fancyhf{}
\lhead{\small \textbf{OECQ-V1} | Version Publique}
\rhead{\small Sûreté Nucléaire Innovante}
\lfoot{\scriptsize \copyright~2026 Consortium Deep Tech}
\rfoot{\scriptsize Page \thepage}

\begin{document}

\begin{center}
    \textsc{\Large Rapport Technique Public} \\
    \vspace{0.3cm}
    \hrule height 1.5pt
    \vspace{0.5cm}
    {\huge \textbf{OECQ-V1}} \\
    \vspace{0.2cm}
    {\Large Hierarchical Active Safety Architecture with Thermodynamic Arbitration by Green AI} \\
    \vspace{0.1cm}
    \textit{Version Publique – Demande de revue TSR-GRS à l'AIEA} \\
    \vspace{0.4cm}
    \hrule height 1pt
\end{center}

\vspace{0.8cm}

\textbf{Auteur principal :} Dr. Mohamed Nour Kayad \orcidlink{0009-0002-1443-7599} \\
\textbf{Co-auteur :} Genspark Free IA \\
\textbf{Affiliation :} Consortium Deep Tech \\
\textbf{Date :} 29 avril 2026

\section*{Abstract}
OECQ-V1 presents a novel Hierarchical Active Safety Architecture for nuclear facilities, leveraging Green Artificial Intelligence as a thermodynamic arbiter. Departing from traditional passive and threshold-based safety systems, OECQ-V1 performs real-time physical coherence validation before any control action.

The core decision engine relies on a thermodynamic arbitration score:
\[ R_{real}^{Q} = \frac{K^{Q}}{D^{Q} + O^{Q}} \]
where \( K^{Q} \) quantifies the real-time consensus between neutron flux, thermal gradients, and mechanical pressures; \( D^{Q} \) evaluates entropy generation and energy dissipation; and \( O^{Q} \) accounts for sensor noise and neuromorphic uncertainty.

Two non-disengageable hardware vetoes ensure robust fail-safe behavior: an analog voltage-drop veto triggered when inter-sensor discrepancy exceeds 2\%, and automatic transition to Secure Blind Mode under data degradation.

Fully aligned with IAEA international safety standards, particularly the Fundamental Safety Principles (\textbf{SF-1}) and the design requirements of \textbf{SSR-2/1 (Rev. 1)}, OECQ-V1 strengthens defense-in-depth while enabling dynamic optimization. A formal request for \textbf{Technical Safety Review (TSR-GRS)} has been submitted to the IAEA.

This architecture offers a promising pathway for safer and more autonomous deployment of next-generation nuclear systems, including Small Modular Reactors (SMRs).

\vspace{0.8cm}

\section{1. Paradigme de Sûreté Hiérarchique Active}
L'architecture OECQ-V1 repose sur le concept de \textbf{Sûreté Hiérarchique Active}. Elle valide la cohérence physique de chaque action avant exécution, contrairement aux systèmes classiques qui se contentent de maintenir des paramètres dans des limites prédéfinies.

\section{2. Score d'Arbitrage Thermodynamique}
\begin{equation}
    R_{real}^{Q} = \frac{K^{Q}}{D^{Q} + O^{Q}}
\end{equation}

\begin{itemize}[label=\textcolor{darkblue}{$\blacktriangleright$}]
    \item \textbf{$K^{Q}$} : Cohérence entre flux neutroniques, gradients thermiques et pressions mécaniques.
    \item \textbf{$D^{Q}$} : Dissipation entropique et pertes énergétiques.
    \item \textbf{$O^{Q}$} : Pénalité liée au bruit capteur et à l'incertitude.
\end{itemize}

\section{3. Verrous de Sécurité Non-Débrayables}
\begin{itemize}
    \item[\textbf{A.}] Veto analogique par chute de tension (> 2\% d'écart inter-capteurs).
    \item[\textbf{B.}] Mode Aveugle Sécurisé en cas de dégradation des données.
\end{itemize}

\section{4. Alignement avec les Normes AIEA}
OECQ-V1 est pleinement alignée avec les **Principes Fondamentaux de Sûreté (SF-1)** et les exigences de **SSR-2/1 (Rev. 1)**. Une demande officielle de **Technical Safety Review (TSR-GRS)** a été soumise à l'AIEA.

\vspace{1.5cm}
\begin{flushright}
    \textit{Version publique – Zenodo} \\
    \textbf{Dr. Mohamed Nour Kayad} \orcidlink{0009-0002-1443-7599} \\
    Consortium Deep Tech
\end{flushright}

\end{document}<img width="790" height="790" alt="1000070887" src="https://github.com/user-attachments/assets/fcc03e8b-9be0-46ef-b302-cbe97dfabbdf" />
<img width="700" height="472" alt="1000070889" src="https://github.com/user-attachments/assets/6d8a7c12-9e43-4c89-993a-bda0bff41afc" />
<img width="702" height="472" alt="1000070888" src="https://github.com/user-attachments/assets/d637c4bd-a181-4521-934f-a838cb446ba2" />
<img width="743" height="472" alt="1000070890" src="https://github.com/user-attachments/assets/f6a7ef38-699d-4124-8b16-889c2ca36338" />
<img width="790" height="590" alt="1000070891" src="https://github.com/user-attachments/assets/e891dddb-ef3b-4390-9dd9-bf48cb4d22ea" />
<img width="952" height="416" alt="1000070892" src="https://github.com/user-attachments/assets/3cb2930d-9579-4368-8f0e-4a850c2f9fb6" />
<img width="865" height="473" alt="1000070893" src="https://github.com/user-attachments/assets/a76a2386-9fd3-430b-9cb0-d90efcbc6f21" />
<img width="1080" height="2400" alt="1000071237" src="https://github.com/user-attachments/assets/4a6d9f06-e4cc-485f-b84a-83dd41dc16c9" />
<img width="1000" height="571" alt="1000071285" src="https://github.com/user-attachments/assets/4d3d0ef9-f4de-4437-abfc-de9e3e4fe8d2" />
<img width="705" height="472" alt="1000071341" src="https://github.com/user-attachments/assets/1570abeb-cf67-4a82-8eaa-76f3faa1b536" />
<img width="1080" height="705" alt="1000071978" src="https://github.com/user-attachments/assets/ed114953-6dfe-4d9b-88d9-19dcf1d5b078" />
<img width="835" height="485" alt="1000073111" src="https://github.com/user-attachments/assets/bd72be85-bead-4396-a9eb-29d780428a4e" />
<img width="693" height="396" alt="1000073345" src="https://github.com/user-attachments/assets/30d8d076-3bf6-4b32-ad4b-67ffd1d4bd4d" />
<img width="757" height="474" alt="1000073346" src="https://github.com/user-attachments/assets/63eb3b40-316c-46bb-90dd-3b1790fb282c" />
<img width="841" height="473" alt="1000073351" src="https://github.com/user-attachments/assets/ad5e430c-3a07-4a52-b88e-bd6a0d7cbc33" />
<img width="606" height="549" alt="1000073353" src="https://github.com/user-attachments/assets/26f97e9f-cea6-4649-95f2-1385ba6e60ca" />
<img width="1089" height="472" alt="1000073354" src="https://github.com/user-attachments/assets/735449c3-8b6a-4cc1-a946-ef51628edc17" />
<img width="980" height="790" alt="1000073355" src="https://github.com/user-attachments/assets/657e9e08-3d3b-4ae7-993e-536ef2043f92" />
