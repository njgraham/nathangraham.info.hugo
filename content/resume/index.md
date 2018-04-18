+++
categories = ["resume"]
comments = false
date = "2016-10-02T22:55:05-04:00"
draft = false
slug = ""
tags = ["resume"]
title = "Résumé"

showpagemeta = false
+++

## Experience Highlights
* Extract, Transform, Load (ETL) software and infrastructure development for [i2b2](https://www.i2b2.org/) and [PCORnet Common Data Model (CDM)](http://www.pcornet.org/pcornet-common-data-model/) clinical data warehouses:
    * [Healthcare Enterprise Repository for Ontological Narration (HERON)](https://informatics.kumc.edu/work/wiki/HERON) with over 2 billion facts on over 2.5 million patients
    * [Greater Plains Collaborative Reusable Unified Study Environment (GROUSE)](https://informatics.gpcnetwork.org/trac/Project/wiki/GROUSE) which is currently in early
    implementation but will include clinical data from multiple sites linked together with data from the [Centers for Medicare and Medicaid Services (CMS)](https://www.cms.gov/Medicare/Medicare.html)
* Creation of disposable [Docker](https://www.docker.com/) containers for portable ETL/software development and production environments
* Administration of enterprise [Oracle databases](https://www.oracle.com/database/index.html) (10g, 11g, 12c)
* Familiarity with [Epic](http://www.epic.com/) Clarity relational database schema
* OS and application administration/maintenance of user-facing enterprise systems
* Engineering and consulting team leader
* On-site technical consulting for Cerner point of care solutions
* Software development of embedded, desktop, server applications from Windows, OS X, and Linux environments - languages include SQL, Python, C, and C++
* Centralized and decentralized version control systems (Git, Mercurial, StarTeam, CVS)

## Professional Experience
### [EquipmentShare](https://equipmentshare.com) - Kansas City, Missouri
**Automation Engineer** June 2017 - Present

### [University of Kansas Medical Center](http://www.kumc.edu) - Kansas City, Kansas
**Senior Enterprise Systems Engineer** April 2016 - May 2017

**Biomedical Software Engineer** March 2012 - May 2016

* Collaborate with the [Harvard SCILHS network](http://scilhs.org/) and the [Greater Plains Collaborative](http://gpcnetwork.org/) to populate the [PCORNet Common Data Model (CDM)](http://www.pcornet.org/pcornet-common-data-model/) from an i2b2 data warehouse
    * Refer to [kumc-bmi/i2p-transform](https://github.com/kumc-bmi/i2p-transform)
* Manage monthly refresh of an i2b2 enterprise data warehouse (HERON)
    * Execute and troubleshoot [HERON Extract, Transform, Load](https://informatics.kumc.edu/work/browser/heron_load) scripts that populate an i2b2 data warehouse from clinical data sources
        * ETL scripts are primarily written in SQL and are invoked using Python/[Paver](http://paver.github.io/paver/#)
        * Resulting i2b2 fact table contains over 2 billion rows
    * Data sources include [Epic EMR](http://www.epic.com/), [GE IDX Flowcast revenue cycle management system](https://en.wikipedia.org/wiki/IDX_Systems), [North American Association of Central Cancer Registries](http://www.naaccr.org/), [Social Security Death Master File](https://dmf.ntis.gov/weekly/), KU Biospecimen Repository, [Vizient (formerly University HealthSystem Consortium)](https://www.vizientinc.com/), and KU [REDCap](http://www.project-redcap.org/) databases.  National ontologies based on [UMLS](http://www.nlm.nih.gov/research/umls/) and [RxNorm](http://www.nlm.nih.gov/research/umls/rxnorm/)
* Tune Oracle to achieve acceptable i2b2 query performance for end-users
* Develop SQL scripts and supporting Python code to load new fact types and enhance ontologies
    * Standardized medication ontology based on [RxNorm](http://www.nlm.nih.gov/research/umls/rxnorm/)
        * Refer to [epic_med_mapping.sql](https://informatics.kumc.edu/work/browser/heron_load/epic_med_mapping.sql) (primary author)
    * Added support for searching patient medication information based on inpatient/outpatient order, dispense, historical, medication administration record (MAR) dose, and PRN flags
        * Refer to [epic_meds_transform.sql](https://informatics.kumc.edu/work/browser/heron_load/epic_meds_transform.sql) (co-author - added features noted above).
    * Modify ETL code as needed for changes implemented in the source data
* Maintain ETL code base with multiple contributers from KUMC and other institutions
* Participate in peer code review and design automated tests to help ensure quality code and accurate data representation
* Maintain SUSE and CentOS Linux servers utilized for production services such as Oracle databases, application and web servers
    * Configure new systems, apply security patches, install applications such as [Trac](http://trac.edgewall.org/wiki/TracWiki), [Apache http server](http://httpd.apache.org/), [WildFly (JBoss)](http://wildfly.org/), [Jenkins continuous integration server](https://jenkins.io/), [REDCap](http://projectredcap.org/)
    * Implement automated methods to manage log rotation, periodic backups, up-time monitoring, etc.
* Develop Docker container to implement i2b2 stack: WildFly, i2b2 cells/web client, Apache ([docker_i2b2_wcapp](https://bitbucket.org/njgraham/docker_i2b2_wcapp)) which is used for development and production environments.

### [Cerner Corporation](https://www.cerner.com) - Kansas City, Missouri
**Technology Consultant Team Leader** January 2012 - March 2012

* Managed a team of 5 technology consultants specializing in [IBM WebSphere application server](http://www.ibm.com/software/websphere) and Cerner MillenniumMobile Framework (CareMobile/Handheld Specimen Collection)
* Responsibilities included mentoring new associates, direct client interaction to triage needs, commit team resources, and predict project effort

**Senior Technology Consultant** February 2011 - January 2012

**Technology Consultant** August 2010 - February 2011

* Role required 80% travel
* Worked independently to plan, coordinate, and execute on-site training and support engagements with over 40 clients all over the the United States
* Installed, trained clients, and provided technical support for:
    * [IBM WebSphere application server](http://www.ibm.com/software/websphere) and various WebSphere-based Cerner solutions
    * Progress Software SonicMQ (Cerner iBus) supporting Cerner RxStation and MDI/BMDI devices
    * Cerner MillenniumMobile Framework (CareMobile and Handheld Specimen Collection)
* Provided training, support, and custom scripting for [SOTI MobiControl](https://www.soti.net/products/mobicontrol/overview/) device management software
* Supported Honeywell and Motorola Windows Mobile-based hand held computers used for Cerner point-of-care solutions

### [Garmin International](http://www.garmin.com) - Olathe, Kansas
**Software Engineering Team Leader** January 2008 - August 2010

* Managed eight software engineers who focused on integrating new, cutting-edge technologies
* Contributed Microsoft Windows-based tools written in C++ utilizing Microsoft Foundation Class library (MFC)
* Contributed automated testing and GPS performance analysis applications using Python and QT
* Major embedded technology focuses: NAND flash, SD/MMC flash devices, non-volatile memory management, and proprietary operating system development
* Major product contributions included the popular Nüvi series and many other handheld, Automotive, and OEM products
* Traveled around the world including Taiwan, India, and mainland China to support GPS sensor boards

**Software Engineer** December 2002 - December 2007

* Maintained and developed GPS sensor products
* Developed mission-critical, high-integrity embedded non-volatile storage software modules that are used in nearly every consumer product produced by Garmin
* Developed embedded flash translation layer (FTL) software which facilitated the use of file systems and the mass-storage feature on automotive navigation products such as the popular Nüvi and C3 series
* Developed Microsoft Windows-based tools in C++ utilizing USB and RS232 communications for testing and diagnostics
* Traveled within the United States and internationally to Taiwan to support various projects and to meet with vendors to discuss new technologies

**Software Engineer Intern** May 2002 - August 2002

* Developed and maintained Microsoft Windows-based tools for testing and diagnostics
* Maintained and implemented improvements sensor products

### [Boeing](http://www.boeing.com) - St. Louis, Missouri
**Software Engineer Intern** May 2001 - August 2001

* Designed and implemented Microsoft Windows-based software written in C++ to maintain precise temperature and pressure parameters to properly cure epoxy used to repair F-18 aircraft in the field

## Education
### [Missouri University of Science and Technology](http://www.mst.edu)

Graduated in December, 2002 **Cum Laude** with a **B.S. Computer Engineering**

## Personal Projects
* [things2c: Motion Sensor/Video Capture System with Mobile Notifications and NFC Activation](http://nathangraham.info/blog/motion-sensing-video-survallence-system-with-nfc-activation.html)
    * Software/configuration is deployed with [Ansible](https://www.ansible.com/)
* [nathangraham.info](http://nathangraham.info/): Static website hosted on Amazon S3
    * Source content is written in [markdown](https://en.wikipedia.org/wiki/Markdown)/[reStructuredText](https://en.wikipedia.org/wiki/ReStructuredText) and contained entirely in [version control](https://github.com/njgraham/nathangraham.info)
    * Rendered with [Nikola](https://getnikola.com/)
    * [DockerFile](https://docs.docker.com/engine/reference/builder/) builds an environment with the necessary dependencies to edit, build, test, and publish
    * [Online résumé](http://nathangraham.info/resume.html) automatically converted to .pdf/.docx from markdown via build scripts

## Other Experience

### Languages

**Programming**: C, Python, SQL, C++, ARM assembly, R, Java, Perl, JavaScript
**Markup**: HTML, XML, [reStructuredText](https://en.wikipedia.org/wiki/ReStructuredText), [markdown](https://en.wikipedia.org/wiki/Markdown)

### Software/OSs/Platforms

**Application Server:** [WildFly (JBoss)](http://wildfly.org/), [IBM WebSphere application server](http://www.ibm.com/software/websphere)
**Integrated Development Environment:** [Eclipse](https://eclipse.org/downloads/), [Microsoft Visual Studio](https://www.visualstudio.com/en-us/visual-studio-homepage-vs.aspx), [GNU Emacs](https://www.gnu.org/software/emacs/), [PyCharm](https://www.jetbrains.com/pycharm/)
**Version Control:** [Mercurial](https://www.mercurial-scm.org/)/[Bitbucket](https://bitbucket.org/), [Borland StarTeam](http://www.borland.com/en-GB/Products/Change-Management/StarTeam), [git](https://git-scm.com/)/[GitHub](https://github.com/), Subversion, CVS, [TortoiseHg](http://tortoisehg.bitbucket.org/), [SmartGit](http://www.syntevo.com/smartgit/), [SourceTree](https://www.sourcetreeapp.com/), [GitKraken](https://www.gitkraken.com/)
**Bug Tracking/Wiki:** [Trac](http://trac.edgewall.org/wiki/TracWiki), [Jira](https://www.atlassian.com/software/jira)
**Testing/Continuous Integration:** [Jenkins](https://jenkins.io/), [BullseyeCoverage](http://www.bullseye.com/)
**Microsoft:** Microsoft Visual C++, Office Suite
**Operating system:** Microsoft Windows, GNU/Linux (Debian, Ubuntu, Linux Mint, CentOS, SUSE, slackware), OS X, FreeBSD, GarminOS
**Platform:** Oracle [VirtualBox](https://www.virtualbox.org/wiki/VirtualBox), VMWare, Amazon Web Services (including EC2, S3, Route 53), [bitnami deployments](https://bitnami.com/), [Docker](https://www.docker.com/)
**Miscellaneous:** Apache Web Server, gcc, samba, OpenOffice, MatLab, RStudio, Secure Shell (SSH), rsync, GIMP, TrueCrypt, dm-crypt/cryptsetup, paver, [Nikola Static Web Site Generator](https://getnikola.com/), [Ansible](https://www.ansible.com/), [Airflow](http://airflow.incubator.apache.org/index.html), [rocket.chat](https://rocket.chat/), [Raspberry Pi](https://www.raspberrypi.org/), [RabbitMQ](https://www.rabbitmq.com/)
