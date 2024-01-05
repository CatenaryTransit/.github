<div align="center">

![Banner](https://files.catbox.moe/ta0y7z.png)

[![Discord]](https://discord.gg/WHqTZPdfy5) [![License]](https://www.gnu.org/licenses/agpl-3.0.en.html#license-text)

Catenary Maps is an **ad-free**, **open-source tool** for seamless public transport navigation. Using real-time data and innovative algorithms, we streamline your transit experience. Navigate public transport smarter and smoother with us!

</div>

## About

We're a fully student team focused on creating advanced routing, estimated time of arrival (ETA), and data processing algorithms. Our goal is to provide accurate real-time data in a user-friendly, accessible format.

The supporting foundation of Catenary Maps is Catenary Transit Initiatives, Inc., a registered nonprofit public benefit corporation in California.

## Repositories

| Name                                                                   | Description                                                                                                              | Technologies                  |
| ---------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ | ----------------------------- |
| [catenary-frontend](https://github.com/CatenaryMaps/catenary-frontend) | Default, original frontend for Catenary with realtime vehicle locations, labelled routes and stops.                      | Svelte, Tailwind              |
| [catenary-backend](https://github.com/CatenaryMaps/catenary-backend)   | Rust backend that powers Catenary with import, APIs for trip calculations, and routing algorithms.                       | Rust                          |
| [catenary-landing](https://github.com/CatenaryMaps/catenary-landing)   | Landing page for Catenary, providing a concise overview of the project in a concise, responsive format.                  | Next.js, Tailwind, TypeScript |
| [catenary-flutter](https://github.com/CatenaryMaps/catenary-flutter)   | Experimental rewrite of Catenary's frontend in Flutter, with support for native mobile and Web platforms.                | Rust, Flutter                 |
| [kactus-gtfs-rt](https://github.com/CatenaryMaps/kactus-gtfs-rt)       | Redis-based cache microservice fetching GTFS-rt from thousands of agencies every second and syncing with our algorithms. | Rust                          |
| [zotgtfs](https://github.com/CatenaryMaps/zotgtfs)                     | ZotGTFS, making GTFS-rt and static data from Transloc                                                                    | Rust                          |
| [amtrak-gtfs-rt](https://github.com/catenarymaps/amtrak-gtfs-rt)       | Amtrak Track-a-train to GTFS-rt conversion                                                                               | Rust                          |
| [skokieswift](https://github.com/CatenaryMaps/skokieswift)             | Experimental reverse engineering of the CTA Train Tracker API, adapting it to GTFS-rt for use in Catenary.               | WIP                           |
| [announcements](https://github.com/CatenaryMaps/announcements)         | Publishing automated announcements for the world's transit systems.                                                      | N/A                           |

## Developer Guide / Getting Started

Join our Discord! A notes are available [here](https://github.com/CatenaryMaps/cantenarymaps) and in our [roadmap](https://github.com/orgs/CatenaryMaps/projects/1/).

## Maintainers

| Name           | Pronouns | Title                                                   | Roles                                             | Education                                  |
|----------------|----------|----------------------------------------------------------|---------------------------------------------------|--------------------------------------------|
| Kyler Chin     | he/him   | Founder, Executive Director, Boardmember                          | Systems Programmer, Algorithms, Frontend, Design | University of California, Irvine           |
| Kin Tsang      | he/him   | Director of Systems Architecture, Boardmember           | Algorithms                                        |                                            |
| Andrew Shen    | he/him   | Director of Machine Learning, Boardmember                | Frontend/Flutter                                  | University of California, Irvine           |
| Samuel Sharp   | he/him   | Frontend and Native Lead                      | Frontend/Flutter, Design, UX/UI                   | San Diego High School                      |
| Andrew Bustos  | he/him   |                                                          | Frontend/Flutter, User Design                     | California State University, East Bay      |
| Jason T. | he/him | Frontend Web Lead | Frontend/Web, UX/UI, Accessibility Design | University of California, San Diego |
| Brandon Z. | he/they | User Interface & Experience Design Lead | Frontend/Web, UX/UI, Design | University of Southern California |

## What's next for us?

We aim to develop a deliverable product over the upcoming weeks, incorporating features such as geocoding, departure and arrival algorithms, transfer and route information, along with routing algorithms tailored for bicycles, pedestrians, and wheelchair users. Additionally, we plan to launch a mobile application utilizing Flutter.

[Discord]: https://img.shields.io/badge/join%20our%20discord!-088EAF?style=for-the-badge&logo=discord&labelColor=%23555555&logoColor=%23ffffff
[License]: https://img.shields.io/static/v1?label=License&message=AGPL-3&color=088EAF&style=for-the-badge
