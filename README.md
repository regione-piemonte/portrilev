# Project Title
PORTRILEV\
Portale delle Rilevazioni

# Project Description
This is a project for the Public Administration.\
The project allows the collection of generic and configurable data among the
actors of the system, called compilators and managers.

The modules are as follow:
- backend and frontend services:
  - [portrilweb](https://github.com/regione-piemonte/portrilev-portrilweb):
  service implementation and webapp for the SURVEY functionalities.
- transversal:
  - [portrilDB](https://github.com/regione-piemonte/portrilev-portrildb):
  database implementation, with all the required scripts.
 
# Configurations
For the configuration of each single module, please refer to the README.md file
which is present in each module.

# Getting Started
Please refer to the Prerequisites section to gather the requested configuration
prior to configure the project.

Please refer to the Installing section for specifications about the
installation process.

# Prerequisites
- The Java projects are written in UTF-8 and are compatible with Java 1.6.0_43.
- (Compilation only) The `JAVA_HOME` environment variable is required to point
  to the Java 1.6.0_43 JDK home folder.
- The Java runtime used is 1.6.0_43.
- Apache Ant for the building process.
- Apache Ivy for dependencies management.
- All libraries are published at [http://repart.csi.it](http://repart.csi.it).
  They are also collected in the `lib.tar.gz` file for easiness of access.
- A "JEE 6 full profile"-compatible Application Server (tested on JBoss EAP 6.1.0).
- The correct version for the DBMS (tested on PostgreSQL 9.6).

# Installing
Please refer to the [INSTALLATION.md](./INSTALLATION.md) file for the steps
required for the installation.

# Contributing
Please read [CONTRIBUTING.md](./CONTRIBUTING.md) for details on our code of
conduct, and the process for submitting pull requests to us.

# Versioning
We partially use Semantic Versioning for versioning. (http://semver.org) \
A major version increment in SemVer standard corresponds to a non-compatible
upgrade of the project; yet a non-compatible upgrade to the project not
necessarily corresponds to a major version increment.

# Authors
See the list of contributors who participated in this project in file
[AUTHORS.txt](./AUTHORS.txt).

# Copyrights
See the list of copyrighters in this project in file
[Copyrights.txt](./Copyrights.txt)\
“&copy; Copyright Regione Piemonte – 2020”.

# License
SPDX-License-Identifier: EUPL-1.2-or-later\
See the [**"EUPL v1_2 IT-LICENSE.txt"**](./EUPL%20v1_2%20IT-LICENSE.txt)
and [**"EUPL v1_2 EN-LICENSE.txt"**](./EUPL%20v1_2%20EN-LICENSE.txt) files for
details
