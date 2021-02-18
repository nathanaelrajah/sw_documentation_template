Introduction/Background
======================
Digiteks Insurance Solutions is a digital assessing company offering services to insurance companies. The core business goal is to provide this assessing service to their clients in the most efficient aproach possible, thus ensuring absolute client satisfaction. 

Project objctives/Goals
======================
1) To have a cenralised digital claims management and workflow system that integrates all workflows of the business in order to produce an efficient system.
2) 
 


Requirements Overview
======================


The user stories link to the relevant system tests.



The **software requirements** define the system from a blackbox/interfaces perspective. They are split into the following sections:

- **User Interfaces** - :ref:`user-interfaces`
- **Technical Interfaces** - :ref:`technical-interfaces`
- **Runtime Interfaces and Constraints** - :ref:`runtime_interfaces`

The *Produktbeschreibung* and especially the *Zweckbestimmung* give an overview of the intended use of this system.

.. todo::

.. _quality_goals:

Quality Goals
-------------

**Contents.**

The top three (max five) goals for the architecture and/or constraints
whose fulfillment is of highest importance to the major stakeholders.
Goals that define the architecture’s quality could be:

-  availability

-  modifiability

-  performance

-  security

-  testability

-  usability

**Motivation.**

If you as an architect do not know how the quality of your work can be
judged …

**Form.**

Simple tabular representation, ordered by priorities

**Background Information.**

**NEVER** start developing an architecture if these goals have not been
put into writing and have not been signed by the major stakeholders.


**Sources.**

The DIN/ISO 92000 Standard contains an extensive set of possible quality
goals.

Stakeholders
------------

**Contents.**

Internal:

Admin Staff
Assessors

External:

Insurers
Panelbeaters
Clients

**Motivation.**

If you do not know the persons participating in or concerned with the
project you may get nasty surprises later in the development process.
Should your project manager maintain this list, make sure that all the
people influencing the architecture are part of it.

**Form.**

Simple table with role names, person names, their knowledge as
pertaining to architecture, their availability, etc. .Stakeholders

+--------------------------+-------------------------------------------------+
| Role/Name                | Goal/Boundaries                                 |
+==========================+=================================================+
| Insurers                 | To appoint claims using the system              |
+--------------------------+-------------------------------------------------+
| Panelbeaters             | To be appointed on claims by using the system   |
+--------------------------+-------------------------------------------------+
| Admin Staff              | To recieve claims, attach all files for the     |
|                          | claims and appoint an assessor on the claim     |
+--------------------------+-------------------------------------------------+
| Assessors                | To use all the files and data provided to them  |
|                          | by the system in order to complete an assessment|
+--------------------------+-------------------------------------------------+
|                          |                                                 |
+--------------------------+-------------------------------------------------+
