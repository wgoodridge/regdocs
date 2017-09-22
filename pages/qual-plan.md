---
title: Qualification Plan
layout: default
url: /pages/qual-plan.html
---
# Introduction
## Purpose
This Qualification Plan describes the approach that will be taken to ensure that `$qual-system$` is qualified for `$qual-purpose$` in accordance with applicable regulations and `$qual-client$` Standard Operating Procedures.
This plan defines the scope of the qualification effort, a risk-based approach for Qualification, required resources, and the quality assurance activities and deliverables that comprise this effort.  

Execution of the activities described in this plan will generate objective and documented evidence that `$qual-system$` is installed correctly and that it consistently functions as intended for the management of `$qual-purpose$`.

## Scope
### In Scope
A regulatory impact assessment has been carried out for SharePoint 2013 to determine the areas of the system that are subject to validation (refer to Regulatory Impact Assessment Document Number: client-SP2013-RIA-01).

In alignment with the findings reported in this assessment, the scope of this qualification effort is restricted to the “out-of-the-box” SharePoint 2013 functionality which is configured to satisfy the regulatory requirements of 21 CFR Part 11, Subpart B – Electronic Records.

At <Insert Client Name>, SharePoint 2013 will be interfaced with Microsoft Active Directory. The interface
with this user management system is considered to be within the scope of this qualification effort, but
validation of Active Directory itself is excluded from the scope of qualification.

### 1.2.2 Out of Scope
Additional applications and business processes requiring interaction with SharePoint 2013 must be assessed
for regulatory impact and additional validation effort may be required prior to using any such interfaced
applications and processes. Consequently, the following elements are excluded from the scope of this
qualification effort:
• Integrated third-party applications and/or solutions.
• Electronic and/or digital signatures.
• Customizations that address specific business needs that are not related to 21 CFR Part 11, Subpart B –
Electronic Records.
• Customizations that address specific pre-installation activities that are related to Kerberos
authentication.
1.2.3 Assumptions
• <List assumptions>
3.2 System Architecture
SharePoint 2013 supports a multi-layer object-based architecture with the following server roles:
• Web Server (WFE)
• Application Server (APP)
• Database Server (DB)
At <Insert Client Name>, the server roles will be deployed in a small SharePoint 2013 farm. Multiple physical
servers and virtual machines will be used to fulfill the server roles across the different operating
environments. The topology is presented in <Insert System Architecture Diagram or Reference to a System
Description Document>.
3.3 Operating Environment
<Insert Client Name> will maintain the following operating environments for SharePoint 2013:
• Development (DEV) – serves as a non-controlled site for developing configuration changes required for
the system to meet business requirements.
• Test/QA (TEST) – serves as a controlled, pre-production environment for testing and training.
• Production (PROD) – serves as a controlled operational environment for day-to-day activities.
4.0 System Qualification Approach
SharePoint 2013 is a configurable software application and is considered to be a Category 4 type system as defined
in GAMP® 5.
Qualification of SharePoint 2013 for electronic records management will be carried out in accordance with <Insert
Client Name> SOP <Document Number> - <Document Title>, following a risk-based approach.
The Validation Team will perform core qualification activities and generate the deliverables described below to
support the qualification of SharePoint 2013. Qualification deliverables will be considered “living” documents and
will be revised as necessary in order to keep them current and up-to-date.
4.1 Regulatory Impact Assessment (RIA)
The following Regulatory Impact Assessment has been carried out for SharePoint 2013:
• Regulatory Impact Assessment for Electronic Records Management in SharePoint 2013, Document No.
<client-SP2013-RIA-01>
In the assessment, regulations that the SharePoint 2013 system must comply with have been identified. The
assessment was used to determine which aspects of the system are subject to validation.
4.2 Qualification Plan (QPL)
The Qualification Plan (this document) outlines the approach, activities, responsibilities and deliverables for
the qualification of SharePoint 2013 with respect to 21 CFR Part 11 requirements for Electronic Records.
This document must be formally approved prior to the approval of any other qualification document(s) with
the exception of the regulatory impact assessment, requirement specifications, and SOPs which may be
approved prior to or in parallel with this plan.
4.3 Requirements Specification (REQ)
The Requirements Specification identifies business (end-user) requirements, functional requirements, and
security requirements that are correlated to 21 CFR Part 11 requirements for Electronic Records. The REQ
