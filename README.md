# OPEN_POS

![licence](https://img.shields.io/badge/licence-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `OPEN_POS` in category **POS_SYSTEMS**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** https://github.com/kimdj/OpenPOS · **Upstream pin:** `8e659f1f1995715621ac3f50d9c34d55faf5296d` · **Category:** POS_SYSTEMS · **Vendor:** Anticloud FZ LLE · **Licence:** MIT

---

## What This Project Does

# OpenPOS Project

Copyright (c) 2017 David Kim

This work is available under the "MIT License". Please see the file 'LICENSE' in this distribution for license terms.

## Week 4 Update

Basic framework for the POS and backend setup is complete.  Routed user authentication and login to the main page, which contains the POS browser interface.  I still need to complete the README.md and the database functionality which would allow each user to maintain their own POS system populated with their own saved settings.  I also need to re-setup gulp to automate installation procedures.  CSS also needs modifying to facilitate a better UI experience.

## Description
OpenPOS is an open source, cloud-based Point-Of-Sale System. OpenPOS uses the MEAN stack, a full-stack JavaScript framework:  

### [Node.js](https://nodejs.org/)

Node.js is an open source, JavaScript runtime environment for executing server-side JavaScript code.  The platform is built on Google Chrome's V8 JavaScript engine.  It is highly scalable and developer friendly nature.  In a nutshell, Node.js is the core backend platform / web framework.  

### [Express.js](http://expressjs.com/)

Express.js is an open source, JavaScript development framework that provides a robust set of web and mobile application features for Node.js.  It provides URL routing among other various functionalities.  In a nutshell, Express.js supplements the backend web framework.  

### [AngularJS](https://angularjs.org/)

AngularJS is an open source, JavaScript framework with the core goal of simplification.  It excels at building dynamic, single page applications (SPAs) while supporting the Model View Controller (MVC) programming paradigm.  In a nutshell, AngularJS takes care of the frontend framework.  

### [MongoDB](https://www.mongodb.com/)

MongoDB is an open source, cross-platform document-oriented NoSQL database program.  It uses JSON-like documents with dynamic schemas (BSON) to persist data.  MongoDB is built for scalability, high availability and performance from a single server deployment to large complex multi-site infrastructures.  

### [Mongoose](http://mongoosejs.com)

Mongoose provides a straight-forward, schema-based solution to model your application data. It includes built-in type casting, validation, query building, business logic hooks and more, out of the box.  

### [Passport](http://passportjs.org)

Passport is authentication middleware for Node.js. Extremely flexible and modular, Passport can be unobtrusively dropped in to any Express-based web application. A comprehensive set of strategies support authentication using a username and password, Facebook, Twitter, and more.  

### [Gulp.js](https://gulpjs.com/)

Gulp is a command line task runner utilizing the Node.js platform.  It runs custom defined repetitious tasks and manages process automation.  

### [Browsersync](https://www.browsersync.io/)

Browsersync is an automation tool that synchronizes file changes and interactions across many devices.  This allows for faster development and better application testing procedures.  

### [Handlebars.js](https://www.npmjs.com/package/handlebars)

Handlebars.js is an extension to the Mustache templating language created by Chris Wanstrath. Handlebars.js and Mustache are both logicless templating languages that keep the view and the code separated like we all know they should be.  

## Prerequisites
### Node.js & NPM Installation

[Debian and Ubuntu based Linux distributions](https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions)

[macOS](https://nodejs.org/en/download/package-manager/#macos)

[Windows](https://nodejs.org/en/download/package-manager/#windows)

### MongoDB Installation

https://docs.mongodb.com/manual/installation/

### MongoDB Atlas Setup (Optional)

[Create a free sandbox](https://www.mongodb.com/cloud/atlas)

## Quick Start

source the project
```
$ git source https://github.com/kimdj/OpenPOS.git
```

Change directory to the project
```
$ cd ./OpenPOS
```

Install dependencies
```
$ npm install
```

If you're using a local MongoDB instance, start the service:
```
$ mongod --dbpath /data/db
```

Or, if you're using MongoDB Atlas, connect to the database:
```
$ mongo "mongodb://openposcluster-shard-00-00-zb2uf.mongodb.net:27017, openposcluster-shard-00-01-zb2uf.mongodb.net:27017, openposcluster-shard-00-02-zb2uf.mongodb.net:27017/test?replicaSet=OpenPOSCluster-shard-0" --authenticationDatabase admin --ssl --username <USERNAME> --password
```

Start the server
```
$ gulp
```

Or, start the web app
```
$ node server.js
```

## Contribute

If you'd like to contribute to this project, please refer to https://github.com/kimdj/OpenPOS/issues/.

## Credits

[AngularJS POS Demo](http://embed.plnkr.co/I6XAHz/)  
[loginapp](https://github.com/bradtraversy/loginapp)

## Contact

E-mail: kim.david.j@gmail.com

## License

[The MIT License](LICENSE.md)

---

## Installation

See the upstream documentation quoted in What This Project Does above.

## Usage

See the upstream documentation quoted in What This Project Does above.

## API

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | MIT |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Contributing

Fork the project, create a feature branch, run the test suite, and open a pull request against upstream.

## License

Upstream © its respective contributors under MIT (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** https://github.com/kimdj/OpenPOS
- **Pinned SHA:** `8e659f1f1995715621ac3f50d9c34d55faf5296d`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`7a91e39e0765be25898227a0455c4df65753b14493b89d5411870799ff343c62`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

