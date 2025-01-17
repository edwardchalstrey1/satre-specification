(standard)=

# A Standard Architecture for TREs

<!-- What this document intends to do (and what it doesn't), the level of detail we aim for contrasted with other technical standards -->

The SATRE standard has been developed based on the following principles:

- TREs should be as as easy as possible for end-users to use (_e.g._ researchers) whilst still remaining secure.
- TRE deployments should be offered that support data of different levels of sensitivity (_e.g._ through a tiered system of technical controls and policies).
- TREs conforming to the standard should be interoperable and provide a familiar end-user experience.
- The standard will be managed and updated following an open, community-driven process, and will not be tied to a single vendor or implementation.

The SATRE standard is based around the idea of capabilities, some of which are required and some of which are optional.
Any particular TRE implementation should be able to score itself against each capability as either "supported", "partially supported" or "unsupported" (see {ref}`evaluation` for details).
The capabilities are grouped into the following broad categories:

- {ref}`information governance <standard_capability_information_governance>`
- {ref}`computing technology <standard_capability_computing_technology>`
- {ref}`data management <standard_capability_data_management>`
- {ref}`information security <standard_capability_information_security>`

In addition to these capabilities, any organisation running a TRE will need to possess various {ref}`supporting capabilities <standard_capability_supporting>`, particularly around:

- legal requirements — particularly around data protection and contract management
- relationship management — engagement with internal and external stakeholders as well as the wider public

Finally, the organisation will need to consider different {ref}`roles <standard_capability_roles>` with which individuals might interact with the TRE.

There might be good reasons why any particular TRE does not possess one or more of the capabilities listed in this specification, but most TREs should aspire to meet them in the long-term.

<!-- List of capabilities. Each of these hould be described in prose and accompanied by a short requirements table of "Statement" and "Guidance" for each requirement. -->

(standard_capability_information_governance)=

## 1. Information governance

What the organisation does to ensure information risk is measured and managed to an acceptable level.

### 1.1 Compliance, monitoring and reporting

The ability of the organisation to monitor compliance with internal and external requirements, agreements, laws and standards.

| Statement | Guidance |
| --------- | -------- |
|           |          |

### 1.2 Policy regulation and management

TODO: someone needs to write a sentence

| Statement | Guidance |
| --------- | -------- |
|           |          |

### 1.3 Quality management

The ability of the organisation to measure and control quality of processes, documentation and outputs.

| Statement | Guidance |
| --------- | -------- |
|           |          |

#### 1.4 Audit and reporting

The ability of the organisation to adhere to stated processes and external standards.

| Statement | Guidance |
| --------- | -------- |
|           |          |

### 1.5 Risk management

The ability of the organisation to measure, forecast and evaluate risks to information.

| Statement | Guidance |
| --------- | -------- |
|           |          |

### 1.6 Project management

The ability of the organisation to manage projects effectively.

### 1.7 Researcher accreditation

The ability of the organisation to ensure that people with access to data are identified correctly and they are suitably qualified.

#### 1.7.1 Training management

The ability of the organisation to track and maintain adequate training levels.

| Statement | Guidance |
| --------- | -------- |
|           |          |

#### 1.7.2 Training delivery

The ability of the organisation to deliver training.

| Statement | Guidance |
| --------- | -------- |
|           |          |

(standard_capability_computing_technology)=

## 2. Computing technology

What the organisation does to manage systems for storing, retrieving, analysing and sending information.

### 2.1 End user computing

The ability of the organisation to provide and manage devices workspaces, interfaces and applications used by researchers to interact with underlying systems and data.

#### 2.1.1 User interface

terminal, desktop, notebook, webapp etc.

| Statement | Guidance |
| --------- | -------- |
|           |          |

#### 2.1.2 Software tools

programming languages, IDEs, desktop applications etc.

| Statement | Guidance |
| --------- | -------- |
|           |          |

#### 2.1.3 High performance computing

| Statement | Guidance |
| --------- | -------- |
|           |          |

#### 2.1.4 Accelerators

GPU, FPGA, ASIC, xPU

| Statement | Guidance |
| --------- | -------- |
|           |          |

#### 2.1.5 Cluster computing

SLURM, Kubernetes etc.

| Statement | Guidance |
| --------- | -------- |
|           |          |

#### 2.1.6 Databases

SQL, noSQL, etc.

| Statement | Guidance |
| --------- | -------- |
|           |          |

### 2.2 Infrastructure analytics

The ability of the organisation to process and analyse data about the usage of the TRE.

| Statement | Guidance |
| --------- | -------- |
|           |          |

### 2.3 Network management

The ability of the organisation to administer and secure network infrastructure using applications, tools and processes.

| Statement | Guidance |
| --------- | -------- |
|           |          |

### 2.4 Infrastructure lifecycle management

The ability of the organisation to manage necessary physical or virtual infrastructure.

| Statement | Guidance |
| --------- | -------- |
|           |          |

#### 2.4.1 Deployment management

The ability of the organisation to instantiate, deploy, change or remove deployed infrastructure.

| Statement | Guidance |
| --------- | -------- |
|           |          |

#### 2.4.2 Capacity management

The ability of the organisation to ensure the right amount of resources are available at the right time to provide a service.

| Statement | Guidance |
| --------- | -------- |
|           |          |

#### 2.4.3 Configuration management

The ability of the organisation to identify, maintain, and verify information on IT assets and configurations in the organisation.

| Statement | Guidance |
| --------- | -------- |
|           |          |

### 2.5 Availability management

The ability of the organisation to ensure all IT infrastructure, processes, tools, roles etc are appropriate for the agreed availability targets.

| Statement | Guidance |
| --------- | -------- |
|           |          |

(standard_capability_data_management)=

## 3. Data management

The ability of the organisation to manage data assets and ensure information remains secure.

### 3.1 Data lifecycle management

The ability of the organisation to manage how and where data is stored, how it moves, changes and is removed.

| Statement | Guidance |
| --------- | -------- |
|           |          |

### 3.2 Identity and access management

The ability of the organisation to ensure the right people (identities) can access the tools and data they need and no more.

| Statement | Guidance |
| --------- | -------- |
|           |          |

### 3.3 Output management

The ability of the organisation to ensure outputs are safely published and shared.

| Statement | Guidance |
| --------- | -------- |
|           |          |

### 3.4 Information discovery

The ability of the organisation to support users who want to browse the data available within an environment at various levels of abstraction.

| Statement | Guidance |
| --------- | -------- |
|           |          |

(standard_capability_information_security)=

## 4. Information security

The ability of the organisation to protect against the unauthorized use of information, especially electronic data and the measures taken to achieve this.

### 4.1 Vulnerability management

The ability of the organisation to identify, assess, report on, manage and remediate cyber vulnerabilities across endpoints, workloads, and systems.

| Statement | Guidance |
| --------- | -------- |
|           |          |

### 4.2 Security testing

The ability of the organisation to gain assurance in the security of an IT system by testing or attempting to breach some or all of that system's security.

| Statement | Guidance |
| --------- | -------- |
|           |          |

### 4.3 Encryption

The ability of the organisation to deploy and manage encryption to protect information assets.

| Statement | Guidance |
| --------- | -------- |
|           |          |

### 4.4 Physical security

The ability of the organisation to manage and protect physical assets from unauthorised access, damage or destruction.

| Statement | Guidance |
| --------- | -------- |
|           |          |

(standard_capability_supporting)=

## 5. Supporting

### 5.1 Legal

The ability of the organisation to access suitable and timely legal advice.

| Statement | Guidance |
| --------- | -------- |
|           |          |

### 5.2 Relationship management

The ability of the organisation to maintain engagement with its customers, stakeholders and other interested parties.

| Statement | Guidance |
| --------- | -------- |
|           |          |

### 5.3 Other

The ability of the organisation to access other supporting capabilities such as financial or business continuity.

| Statement | Guidance |
| --------- | -------- |
|           |          |

(standard_capability_roles)=

## 6. Roles

A TRE conforming to the SATRE standard should provide a broadly similar experience for stakeholders operating in each of these defined roles.
There is not necessarily a one-to-one mapping between roles and people.
One person can have multiple roles.

### 6.1 TRE users

The researchers working on projects that involve logging into a TRE to access data.

<!-- The document will explain that user experience of the platform and associated documentation should feel similar across TREs conforming to SATRE standard. -->

| Statement | Guidance |
| --------- | -------- |
|           |          |

### 6.2 TRE administration roles

The IT and related professionals who will be responsible for deploying and managing instances of a TRE conforming to the SATRE standard.
These roles cover managing TRE computing infrastructure, but also administering the TRE itself (e.g. managing users and projects).

<!-- The document will explain that SATRE conforming TREs should have documentation and infrastructure deployment code/apps that conform to software engineering best practices, which are also defined here, making them "simple" for an IT professional to follow; troubleshooting steps included. -->

| Statement | Guidance |
| --------- | -------- |
|           |          |

### 6.3 TRE developer roles

The software engineers responsible for developing and maintaining TRE software, including adding functionality, bug fixes and general maintenance.

<!-- The document will explain recommended practices suitable for developing a software of this complexity and reference learnings from existing TRE developers. -->

| Statement | Guidance |
| --------- | -------- |
|           |          |

### 6.4 TRE governance roles

Roles that uphold the governance of TREs.
Such governance responsibilities typically involve establishing policies and procedures to ensure the responsible use of data, protecting the privacy and confidentiality of research participants, and promoting transparency and accountability in research activities.
Typical roles might include data custodians, ethicists, an independent board or a lay panel.

| Statement | Guidance |
| --------- | -------- |
|           |          |

## Architecture

<!--
Includes diagrams of how the TRE features connect together, but remains a high level description that doesn't specify which exact technologies a TRE developer should use.
This can also offer an explanation of how people from different roles interact/experience these features.
-->

## Conclusion

<!--
Benefits of adopting this standard for developing a TRE.
Benefits of existing TRE efforts working to conform to this standard (users and admin roles as well as developers).
-->
