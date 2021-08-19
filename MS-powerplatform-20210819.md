# Power platform
- power bi
- pwoer apps
- power automate - rpa
- power virtual agents - self-services = code + chatbot

* built on
 - data connectors
 - ai builder
 - common data services - model biz data & security for shares


# Data connectors

* share between power automate, power apps, logic apps
 * 400+ connectors on market incl generic ones like REST API connector
 
- tabular data
 * database, common data service
- function-based data
 
* triggers = power automate use it to start a workflow
* actions = prompted by a user or trigger 

# How
1. Start from "Data and services" - identify data that will drive the app
1. Process automation
1. User experiencs - mobile, embedded, web, AR...

# Power apps
* low-code apps and forms
* low-code backend with CDS
* add AI with no code - 11 models available

1. canvas apps
1. model-driven apps (must be CDS backend, biz logic in data layer)
1. low-code websites with portals = MS Forms / Power Apps Portal



# CDS - CDM (common data model)
- scalable data modeling and storage options
- *sharepoint online lists* easy but with limitations 

CDS = API + Authentication + authorization + auditing + workflows + biz rules + calculations + jobs + modelling + validation + reporting + rdbms + blobs + data lakes + events + webhooks + ...
    = API + security + logic + data + storage + integration

CDM = ER models shared across MS applications, model itself is published to github
CDM accelerators = dimension / hierachy relations in models (MS only)

- standard entites - created for every instance of a CDS database
- complex entites - with server side rules, end user may require additional license to use them
- each CDS has a standard set of entities, each entity has a standard set of fields.

* CDS environment - created under a AAD tenant. 
 - for geographic segregation (GDPR etc)
 - for app life cycle management
 - for different biz policy / requirement

* CSD biz rules
 - maintain biz logic at data layer

# Security and Administration
* centralize at https://admin.powerplatform.microsoft.com


# Power Apps

organization wide initiatives > mission critical use cases > complex processes and data structure > personal and team productivity
* number of (vocal) users growth 'complexity' exponentially

Target audience: citizen developer, build app for oneself / local team, e.g. update an excel, but account for 80% of apps on market.

1. every one can builder
1. agile - CICD lifecycle
1. WYSIWYG editor

- sharing app
 1. save it, give it a icon, 
   * to local computer for private use
   * to cloud for publish
 1. if save to cloud, choose a co-owner
 1. share the app AND data source
 
# Power automate

* have prebuilt templates
* 300+ connectors, integrate with MS ecosystem

UI flows
Biz Process flows
Event Driven flows

* types of trigger
 - when something (data) changes
 - on a schedule
 - on a button press

* use biz flow to simplify form entry
