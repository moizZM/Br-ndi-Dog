# CV replacement sections — English and German

Prepared 26 October 2026 from the two uploaded LaTeX CVs. These edits follow the shared advice on readability, relevant evidence and concise descriptions; individual recruiter preferences vary.

## 1. Header focus line

Replace only the existing `B.Eng. in Electronic Engineering\par` text inside the blue headline block. This describes your target area; keep your actual employment titles in the experience section.

English

```latex
B.Eng. Electronic Engineering | Test \& Validation\par
```

German

```latex
B.Eng. Electronic Engineering | Test und Validierung\par
```

## 2. Professional experience

Replace the whole experience section, ending immediately before the technical skills section.

English

```latex
\section{Professional Experience}
\companyheading{Infineon Technologies AG}{Warstein, Germany}
\roleheading{Working Student | Systems Engineering}{08/2026 to Present}
\begin{cvitems}
  \item Measure gate driver and transformer voltages with an oscilloscope to investigate voltage drop at different DC/DC duty cycles and power module switching frequencies.
  \item Analyse and document measurements and board changes in Excel, using separate worksheets, comparison charts and comments on the findings.
  \item Support double pulse tests and current and temperature tests on power modules and converter setups; record electrical measurements and thermal camera images.
  \item Prepare test guides covering wiring, measurement points and operating steps to support repeatable laboratory setups.
  \item Support through hole and surface mount soldering for laboratory hardware.
\end{cvitems}

\vspace{7pt}
\roleheading{Bachelor Thesis Student and Working Student | Product Application Engineering}{11/2025 to 07/2026}
\begin{cvitems}
  \item Programmed a TI C2000 F28P65x controller in C for EtherCAT command and measurement exchange; configured and checked communication with TwinCAT 3.
  \item Integrated PLECS controller code into the EtherCAT firmware and used an RT Box HIL setup to test control signals and voltage feedback.
  \item Verified signal timing and voltage scaling with PicoScope and TwinCAT Scope; compared measurements with expected values and documented test results.
\end{cvitems}

\vspace{9pt}
\companyheading{Hochschule Hamm-Lippstadt}{Lippstadt, Germany}
\roleheading{Student Assistant | DevOpsSafe Research Project}{04/2025 to 04/2026}
\begin{cvitems}
  \item Developed Python programs to send driving commands to CARLA and receive vehicle data over UDP.
  \item Ran controller programs in a QEMU RISC-V Linux environment, separate from the vehicle simulation.
  \item Tested delayed, missing and modified messages; added checks for outdated vehicle data and logs to investigate communication faults.
\end{cvitems}

\vspace{9pt}
\companyheading{microsynetics GmbH}{Soest, Germany}
\roleheading{Intern and Working Student | Embedded Hardware}{08/2024 to 07/2025}
\begin{cvitems}
  \item Investigated faulty and returned wearable PCBs by comparing voltage, continuity and signal measurements with working boards; documented findings in Confluence.
  \item Supported sensor tests, THT and SMD soldering, and PCB rework.
  \item Created enclosure, PCB holder and flexible PCB models in Fusion 360; checked fit and connector access using 3D printed parts.
  \item Compared datasheets and supported component selection; created an Excel VBA library linking technical data, datasheets and supplier information.
  \item Used ANSYS thermal simulation to analyse temperature distribution and heat flow in sensor designs.
\end{cvitems}
```

German

```latex
\section{Berufserfahrung}
\companyheading{Infineon Technologies AG}{Warstein, Deutschland}
\roleheading{Werkstudent | Systems Engineering}{08/2026 bis heute}
\begin{cvitems}
  \item Messung von Gatetreiber- und Transformatorspannungen mit dem Oszilloskop, um Spannungsabfälle bei verschiedenen DC/DC-Tastgraden und Schaltfrequenzen des Leistungsmoduls zu untersuchen.
  \item Auswertung und Dokumentation von Messungen und Platinenänderungen in Excel mit separaten Tabellenblättern, Vergleichsdiagrammen und Kommentaren zu den Ergebnissen.
  \item Unterstützung bei Doppelpulstests sowie Strom- und Temperaturtests an Leistungsmodulen und Umrichteraufbauten; Aufzeichnung elektrischer Messwerte und Wärmebilder.
  \item Erstellung von Testanleitungen mit Verkabelung, Messpunkten und Arbeitsschritten für wiederholbare Laboraufbauten.
  \item Unterstützung beim THT- und SMD-Löten für Laborhardware.
\end{cvitems}

\vspace{7pt}
\roleheading{Bachelorand und Werkstudent | Product Application Engineering}{11/2025 bis 07/2026}
\begin{cvitems}
  \item Programmierung eines TI C2000 F28P65x in C für den Austausch von Befehlen und Messwerten über EtherCAT; Einrichtung und Prüfung der Kommunikation mit TwinCAT 3.
  \item Integration von PLECS-Controllercode in die EtherCAT-Firmware und Prüfung von Steuersignalen und Spannungsrückmeldungen mit einem RT Box HIL-Aufbau.
  \item Prüfung von Signaltiming und Spannungsskalierung mit PicoScope und TwinCAT Scope; Vergleich der Messwerte mit den Sollwerten und Dokumentation der Testergebnisse.
\end{cvitems}

\vspace{9pt}
\companyheading{Hochschule Hamm-Lippstadt}{Lippstadt, Deutschland}
\roleheading{Studentische Hilfskraft | Forschungsprojekt DevOpsSafe}{04/2025 bis 04/2026}
\begin{cvitems}
  \item Entwicklung von Python-Programmen zum Senden von Fahrbefehlen an CARLA und zum Empfang von Fahrzeugdaten über UDP.
  \item Ausführung von Controllerprogrammen in einer QEMU RISC-V Linux-Umgebung, getrennt von der Fahrzeugsimulation.
  \item Tests mit verzögerten, fehlenden und veränderten Nachrichten; Ergänzung von Prüfungen auf veraltete Fahrzeugdaten und Protokollen zur Untersuchung von Kommunikationsfehlern.
\end{cvitems}

\vspace{9pt}
\companyheading{microsynetics GmbH}{Soest, Deutschland}
\roleheading{Praktikant und Werkstudent | Embedded Hardware}{08/2024 bis 07/2025}
\begin{cvitems}
  \item Fehleranalyse an defekten und zurückgesandten Wearable-Platinen durch Vergleich von Spannungs-, Durchgangs- und Signalmessungen mit funktionierenden Platinen; Dokumentation in Confluence.
  \item Unterstützung bei Sensortests, THT- und SMD-Lötarbeiten sowie Nacharbeiten an Platinen.
  \item Erstellung von Gehäuse-, Platinenhalter- und flexiblen Platinenmodellen in Fusion 360; Prüfung von Passform und Anschlusszugang mit 3D-gedruckten Teilen.
  \item Vergleich von Datenblättern und Unterstützung bei der Bauteilauswahl; Erstellung einer Excel-VBA-Bibliothek mit technischen Daten, Datenblättern und Lieferanteninformationen.
  \item Untersuchung von Temperaturverteilung und Wärmefluss in Sensorentwürfen mit thermischen Simulationen in ANSYS.
\end{cvitems}
```

## 3. Technical skills

Replace the whole technical skills section. The minipage keeps the heading and skills together on one page.

English

```latex
\par\noindent
\begin{minipage}{\linewidth}
\section{Technical Skills}
\skillline{Test and measurement}
  {Oscilloscopes, PicoScope, multimeters, thermal cameras, PCB fault analysis}
\skillline{Embedded programming}
  {C, Python, TI C2000, Code Composer Studio}
\skillline{Industrial communication}
  {EtherCAT, TwinCAT 3}
\skillline{Simulation and validation}
  {PLECS, RT Box, hardware in the loop (HIL), QEMU, CARLA}
\skillline{PCB design}
  {KiCad, Altium; schematic design and PCB layout}
\skillline{Engineering tools}
  {Git, Linux, Excel VBA, Fusion 360, ANSYS}
\skillline{Languages}
  {English fluent, German basic}
\end{minipage}
\par
```

German

```latex
\par\noindent
\begin{minipage}{\linewidth}
\section{Technische Kenntnisse}
\skillline{Test und Messtechnik}
  {Oszilloskope, PicoScope, Multimeter, Wärmebildkameras, Fehleranalyse an Platinen}
\skillline{Embedded-Programmierung}
  {C, Python, TI C2000, Code Composer Studio}
\skillline{Industrielle Kommunikation}
  {EtherCAT, TwinCAT 3}
\skillline{Simulation und Validierung}
  {PLECS, RT Box, Hardware in the Loop (HIL), QEMU, CARLA}
\skillline{Platinenentwicklung}
  {KiCad, Altium; Schaltplanerstellung und Platinenlayout}
\skillline{Entwicklungswerkzeuge}
  {Git, Linux, Excel VBA, Fusion 360, ANSYS}
\skillline{Sprachen}
  {Englisch fließend, Deutsch Grundkenntnisse}
\end{minipage}
\par
```

## 4. Education

Replace the whole education section, including the preceding Needspace command.

English

```latex
\Needspace{10\baselineskip}
\section{Education}
\companyheading{Hochschule Hamm-Lippstadt}{Lippstadt, Germany}
\roleheading{B.Eng. Electronic Engineering}{09/2022 to 07/2026}
\begin{cvitems}
  \item Final grade: 2.0 (210 ECTS); bachelor thesis: 1.0; project work and practical semester: 1.3 each.
  \item Thesis: Development, Implementation and Validation of an EtherCAT Slave for Controlling Power Stages.
  \item Relevant coursework: electronics, embedded systems, control systems, PCB design, and system testing.
\end{cvitems}
```

German

```latex
\Needspace{10\baselineskip}
\section{Studium}
\companyheading{Hochschule Hamm-Lippstadt}{Lippstadt, Deutschland}
\roleheading{B.Eng. Electronic Engineering}{09/2022 bis 07/2026}
\begin{cvitems}
  \item Abschlussnote: 2,0 (210 ECTS); Bachelorarbeit: 1,0; Projektarbeit und Praxissemester: jeweils 1,3.
  \item Bachelorarbeit: Development, Implementation and Validation of an EtherCAT Slave for Controlling Power Stages.
  \item Relevante Studieninhalte: Elektronik, eingebettete Systeme, Regelungstechnik, Platinenentwurf und Systemtests.
\end{cvitems}
```

## 5. Publication contribution

Replace only the cvitems block below the publication title card. The acceptance status and title remain in the card.

English

```latex
\begin{cvitems}
  \item Developed the controller side of the CARLA/QEMU testbed, including vehicle commands and UDP communication.
\end{cvitems}
```

German

```latex
\begin{cvitems}
  \item Entwicklung des Controllerteils im CARLA/QEMU-Prüfstand, einschließlich Fahrbefehlen und UDP-Kommunikation.
\end{cvitems}
```

## 6. Personal section

Delete the final Personal / Persönliches section, including its Needspace command and cvitems block. Keep the final `\end{document}`.

The project descriptions and training entries can remain in place. The revised text uses no invented performance figures, qualifications or test results. It preserves the stated availability and language levels.

Sources for the editing approach:

- German recruiter discussion: https://www.reddit.com/r/arbeitsleben/comments/1ak4nod/hrrecruiter_was_ist_euch_wichtig_wenn_ihr/
- Hays Germany, 17 June 2026: https://www.hays.de/blog/karriere-und-entwicklung/der-perfekte-lebenslauf

