# 📋 Thesis

This repository contains Anand Chowdhary's bachelor thesis, entitled "Email-based Intelligent Virtual Assistants (EIVA)" for Creative Technology BSc at the University of Twente, under [Dr. Job Zwiers](https://people.utwente.nl/j.zwiers) and in association with [Speakup](https://www.speakup.nl).

[![Build LaTeX](https://github.com/AnandChowdhary/thesis/workflows/Build%20LaTeX/badge.svg)](https://github.com/AnandChowdhary/thesis/actions)
[![Release](https://badgen.net/github/release/AnandChowdhary/thesis)](https://github.com/AnandChowdhary/thesis/releases)
[![License](https://badgen.net/github/license/AnandChowdhary/thesis)](./LICENSE)
[![Download PDF](https://badgen.net/badge/download/PDF/purple)](https://essay.utwente.nl/81424/1/Chowdhary_BA_EEMCS.pdf)

[**View published PDF on essay.utwente.nl →**](https://essay.utwente.nl/81424/1/Chowdhary_BA_EEMCS.pdf)

[**DOI: 10.13140/RG.2.2.34795.77608**](https://dx.doi.org/10.13140/RG.2.2.34795.77608)

Related repositories:

- Backend APIs: [o15y/eiva](https://github.com/o15y/eiva)
- Frontend app: [o15y/myeiva.com](https://github.com/o15y/myeiva.com)

## 📃 Abstract

Manually setting up appointments by email wastes tens of hours every month for professionals, because several email exchanges are required before receiving confirmation. Since not everyone can afford to hire full-time assistants, Email-based Intelligent Virtual Assistants (EIVA) can help by automating this task.

In the research described in this paper, a functional EIVA was developed based on research and industry best-practices. Users could simply add their assistant’s address as ‘CC’ in an email, and EIVA would share the recommended location and time slots with guests automatically, based on the user’s availability (determined using their calendar) and scheduling preferences. A companion web application was also developed to manage meetings and settings. The code is open source and was written in TypeScript with Node.js for the backend and Vue.js for the frontend, and deployed on Amazon Web Services architecture in Europe. The product was built with a focus on data privacy and user personalization, through a series of feedback cycles with the external client.

A user experience evaluation of EIVA was conducted with 30 participants that found positive reception. The average rating of the overall assistant was calculated to be 4.4 out of 5, and that of the web app was 4.5 out of 5. Users’ behavior was also understood with the help of heatmaps and visualizations using pageview and mouse clicks tracking. All but one participants said that EIVA met their expectations, and 25 out of 30 would use it in the future if it launches as a service. Most would also be willing to pay for it, with an average amount up to EUR 6.16 per month. Participants also shared their frustrations and feature recommendations. In the future, natural language processing-based classification should be improved and user recommendations can be implemented before launching EIVA as a service for consumers.

## 👩‍💻 Development

Text is written in LaTeX in the [`thesis.tex`](./thesis.tex) file, and compiled to PDF using the available LaTeX distribution.

On GitHub Actions, [`xu-cheng/latex-action@v2`](https://github.com/xu-cheng/latex-action) is used. The PDF is distributed as a [release](https://github.com/AnandChowdhary/thesis/releases) and also hosted using GitHub Pages from the [`gh-pages`](https://github.com/AnandChowdhary/thesis/tree/gh-pages) branch.

Locally, [Texpad](https://www.texpad.com) is used for writing in and compiling LaTeX.

## 📄 License

[CC BY 4.0](./LICENSE) © [Anand Chowdhary](https://anandchowdhary.com)
