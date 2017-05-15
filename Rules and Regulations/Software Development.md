**Software Development Regulations**
------------------------------------

Ver.1.0

This document describes the general development workflow for MitocGroup
and Adtechmedia projects. A custom Scrum approach is used as a base for
software development. Below you can find the
rules/regulations/definitions and associated processes.

### **TEAM**

The Team consists of a Product Owner, the Development/QA Team, and a
Scrum Master. Team is self-organizing and cross-functional.
Self-organizing teams choose how best to accomplish their work, rather
than being directed by others outside the team. Cross-functional teams
have all competencies needed to accomplish the work without depending on
others not part of the team.

### **CODE & MANAGEMENT TOOLS**

1)  GitHub is used for Code Management, Storage and as a main Management
    > Tool.

2)  GitHub Organizations:

> [*https://github.com/AdTechMedia*](https://github.com/AdTechMedia)
>
> [*https://github.com/MitocGroup*](https://github.com/MitocGroup)
>
> [*https://github.com/404md*](https://github.com/404md)

1)  ZenHub Plugin is required for GitHub to activate Issue Tracking tool
    > for related projects.

### **PRODUCT BACKLOG**

The Product Backlog is an ordered list of team goals that are needed in
the product and is the single source of requirements for any changes to
be made to the product. The Product Owner is responsible for the Product
Backlog, including its content, availability, and ordering.

### **REQUIREMENTS**

-   Requirements are delivered in form of Team goals by Product Owner
    > every 2 months

<!-- -->

-   Development & QA Team reviews proposed goals and address
    > questions/concerns before scope confirmation

-   Team goals are added to GitHub as epic issues by Product Owner /
    > Scrum Master / Development Team

-   Development Team breaks down the Epic issues into smaller task
    > *(enhancements)*

-   Tasks are associated with a Milestone for a product increment

### 

### 

### **THE SPRINT**

A time-box of two weeks during which a “Done”, useable, and potentially
releasable product Increment is created. A new Sprint starts immediately
after the conclusion of the previous Sprint.

Sprints consist of:

-   The Sprint Planning *(held every Monday)*

-   Daily Scrums *(replaced by Daily Stand-up emails)*

-   The Development work

-   The Sprint Review *(held every Monday)*

-   The Sprint Retrospective *(held every 2nd Monday right after Sprint
    > Review/Planning)*

### **SPRINT BACKLOG**

The Sprint Backlog is the set of Product Backlog items selected for the
Sprint/Milestone, plus a plan for delivering the product Increment and
realizing the Sprint Goal. The Sprint Backlog is a forecast by the
Development Team about what functionality will be in the next Increment
and the work needed to deliver that functionality into a “Done”
Increment.

### **WORKING ENVIRONMENTS**

1)  Local

2)  Development

3)  Stage/Demo

4)  Production

**Local Environment**

-   Development team works on assignments using local code, server or
    > side deploys

-   Development team should keep the local environment up-to-date with
    > production like configurations

-   Code from Local Environment should be pushed to Development
    > environment at least once a day

**Development Environment**

-   Development environment represents code integration from all Local
    > Environments

-   Functional and Integration Testing is performed by QA in Dev
    > Environment for all item delivered by Development team

-   Pushing the code to Dev Environment is a direct responsibility for a
    > developer; it is up to Development Team to decide who will push
    > the code

**Stage/Demo Environment**

-   Stage/Demo Environment is a production like environment

-   Regression Testing is performed by QA in Stage environment before
    > Production Release

-   Development team will push the code to Stage Environment at least 24
    > hours before Production release or upon QA Request

-   Blocking/Critical issues or showstoppers found in Stage environment
    > are Reported by QA as early as possible

**Production Environment**

-   Production Environment is a end user environment accessible to
    > public

-   Code is pushed to Production Environment from Stage
    > environment/branch only

-   Health Check/ Smoke Testing is performed by QA in Production
    > environment after Release

### **RELEASES**

1)  Production release

2)  HotFix

**Production Release**

-   Product increment should be released in Production every second
    > Friday by 7 PM (Moldova Time)

-   Sign Off by Product/Project Manager is required for Production
    > Release

-   Critical and Blocking issues should be reported as earliest as
    > possible or during Development Phase (when code is in Dev
    > Environment)

![](media/image3.png){width="7.890625546806649in"
height="3.4294247594050744in"}

**HotFix**

A hotfix is a single, cumulative package that is used to address a
problem in a software product (i.e. software critical issue). Typically,
hotfixes are made to address a specific customer situation.

-   HotFix is pushed directly to Stage Environment by Development Team

-   Functional Testing is performed by QA Team

-   Limited Regression Testing is performed by QA for HotFix Related
    > areas![](media/image4.png){width="6.5in"
    > height="1.4583333333333333in"}

