# Haushaltsbuch – A Simple-Language Budgeting Tool for Everyday Financial Management

Copyright © 2026 Elisabeth Vanderheiden.

An interactive household budgeting application in Simple German (Einfache Sprache), designed to help people with reading difficulties, cognitive impairments or limited financial literacy record income and expenses independently.

## Overview

Haushaltsbuch supports self-determined financial record-keeping by combining a reduced, accessible interface with categories that reflect the everyday income and expense situations of people receiving disability-related benefits, workshop wages or family allowances. The application runs entirely in the browser and stores all entries locally on the user's own device, so that no personal financial data is transmitted to any server.

Users record entries as either income or expense, assign a category, enter an amount and a date, and may add an optional note. The application then provides:

* a monthly overview of income, expenses and the remaining balance
* a six-month comparison chart of income and expenses
* a category breakdown of the current month's expenses, shown as a donut chart
* a chronological list of all entries for the current month
* export of all entries as a CSV table or as a printable PDF

## Categories

Income categories include Lohn (wages), Werkstatt-Entgelt (workshop wages), Kindergeld (child benefit), Sozialleistung (social benefit) and Geldgeschenk (monetary gift), alongside a general Sonstiges (other) category. Expense categories include Wohnen (housing), Internet, Essen (food), Verkehr (transport), Versicherung (insurance), Gesundheit (health), Freizeit (leisure) and Kleidung (clothing), alongside Sonstiges (other).

## Purpose

The tool addresses a gap in existing budgeting applications, most of which assume a level of reading fluency, financial vocabulary and digital literacy that excludes many people with disabilities or learning difficulties. By using Simple German throughout, a reduced set of categories, and a data model that requires no account creation or internet connection, Haushaltsbuch aims to make basic financial self-management accessible to a wider group of users.

## Intended Users

* people with dyslexia, cognitive impairments or intellectual disabilities
* participants in sheltered workshops (Werkstätten für Menschen mit Behinderung)
* adult education providers and support workers accompanying financial literacy training
* trainers and coaches in inclusive education settings

## Technical Notes

The application is built as a static, installable Progressive Web App (PWA). It can be added to a mobile home screen and used offline once loaded, through a service worker that caches the application shell locally. No backend, database or account system is used. All data remains in the browser's local storage on the user's own device.

## Live Application

https://research2026-collab.github.io/Haushaltsbuch/

## Funding

Entwickelt im Rahmen des Projektes Inklusion - ToolCheck, gefördert vom Ministerium für Wissenschaft, Weiterbildung und Gesundheit Rheinland-Pfalz, AZ 53 18-202616/32-ZE.

## Author

Elisabeth Vanderheiden

## Citation

Please cite version 1.0.0 of this software as:

Vanderheiden, E. (2026). *Haushaltsbuch – A Simple-Language Budgeting Tool for Everyday Financial Management* (Version 1.0.0) [Computer software]. Zenodo. https://doi.org/10.5281/zenodo.XXXXXXX

*(DOI to be updated once the corresponding Zenodo record has been minted.)*

## Licence

The educational content of this repository, including the category descriptions, information texts and accompanying materials, is licensed under the Creative Commons Attribution-NonCommercial 4.0 International Licence (CC BY-NC 4.0).

The source code of this application is provided for access to the published web application only. All rights to the source code are reserved. No permission is granted to copy, redistribute, modify or use the source code except where required by applicable law or with the prior written permission of the copyright holder.

Icons and other third-party materials remain the property of their respective copyright holders.

## Keywords

Simple language, financial education, budgeting, accessibility, disability, dyslexia, inclusion, digital participation
