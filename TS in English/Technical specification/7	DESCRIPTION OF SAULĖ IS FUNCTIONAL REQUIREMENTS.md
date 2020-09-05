## 7	DESCRIPTION OF SAULĖ IS FUNCTIONAL REQUIREMENTS

#### 7.1	SAULĖ IS USERS

28. On the figure below one can find the users of SAULĖ IS. During the analysis and design phase, SAULĖ IS users must be decomposed in accordance with the operating rules, data and function access restrictions. A mechanism for user roles and rights must be implemented to ensure that users with certain roles can see and manage data and perform the functions to which they have rights.

![image](https://user-images.githubusercontent.com/61745726/92297276-56216600-ef46-11ea-87ba-18bfbb9fb1ce.png)

Table 7.1. Description of SAULĖ IS users
<ol>
<li>
<table width="100%">
<thead>
<tr>
<td width="33%">
<p>User</p>
</td>
<td width="66%">
<p>Description</p>
</td>
</tr>
</thead>
<tbody>
<tr>
<td width="33%">
<p>1. Implementing agencies</p>
</td>
<td width="66%">
<p>1.1. Basic functions of users:</p>
<p>1.1.1. Monitoring and control of procurement in projects funded by different funding sources:</p>
<p>1.1.2. Preliminary verification of the project contractor procurement documents (frequency depends on the documents submitted by the project contractor);</p>
<p>1.1.3. Ex-post verification of the project contractor procurement documents (frequency depends on the documents submitted by the project contractor);</p>
<p>1.1.4. Monitoring the implementation of contracts signed by the project contractor;</p>
<p>1.1.5. Analysis of procurement statistics of project contractors;</p>
<p>1.1.6. Receiving of messages (the frequency set by user as needed);</p>
<p>1.1.7. Receiving of statistics. The frequency is set by the user as needed.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>2. Supervisory agencies</p>
</td>
<td width="66%">
<p>2.1. Basic functions of users:</p>
<p>2.1.1. Monitoring, inspection, assessment of procurements performed by other institutions;</p>
<p>2.1.2. Monitoring of implementation of contracts signed by other institutions;</p>
<p>2.1.3. Analysis of procurement statistics of the institutions executing procurements;</p>
<p>2.1.4. Monitoring and analysis of inspections by implementing agencies.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>3. Procurement Executors</p>
</td>
<td width="66%">
<p>3.1. Basic functions of users:</p>
<p>3.1.1. Procurement - procurement planning processes, market research, publication of technical specifications, procurement, assessment of tenders (the frequency depends on need), organisation of renewed competition and e-Auctions;</p>
<p>3.1.2. Conclude and sign contracts (the frequency depends on the number of contracts awarded by the contracting authority);</p>
<p>3.1.3. Execute, change contracts;</p>
<p>3.1.4. Obtain statistics related to the institution&rsquo;s procurement or general market statistics (the frequency set by user as needed);</p>
<p>3.1.5. Receiving of messages (the frequency set by user as needed);</p>
<p>3.1.6. Information subscriptions (the frequency set by user as needed).</p>
<p>3.1.7. Publish the statistics related to the institution&rsquo;s procurement.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>4. Suppliers</p>
</td>
<td width="66%">
<p>4.1. Basic functions of users:</p>
<p>4.1.1. Participate in procurements - monitor planned procurements, assess market research, technical specifications performed by institutions, submit tenders (the frequency depends on the need);</p>
<p>4.1.2. Coordinate contracts and sign them (the frequency depends on the number of contracts concluded by the supplier);</p>
<p>4.1.3. Coordinate and sign contract amendments;</p>
<p>4.1.4. Provide handover certificates for goods, services or works and invoices;</p>
<p>4.1.5. Receive notifications about procurement in progress in the selected area (the frequency is set by the user as needed);</p>
<p>4.1.6. Get statistical information about published procurements, signed contracts.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>5. PPO</p>
</td>
<td width="66%">
<p>5.1. Basic functions of users:</p>
<p>5.1.1. SAULĖ IS maintenance and development;</p>
<p>5.1.2. Administration of the internal portal;</p>
<p>5.1.3. Monitoring, analysis and risk assessment of procurements (contracts) in progress;</p>
<p>5.1.4. Consulting of SAULĖ IS users on the system usage;</p>
<p>5.1.5. Consulting of procurement executors and suppliers on procurement issues (examination of letters, answers to inquiries, etc.);</p>
<p>5.1.6. Control of procurement, contracts, control of procurement executors, and revision of the activities performed;</p>
<p>5.1.7. Collection, dissemination and publication of statistical information related to procurement.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>6. Public</p>
</td>
<td width="66%">
<p>6.1. Basic functions of users:</p>
<p>6.1.1. Obtainment and use if open data as needed;</p>
<p>6.1.2. Access to information related to procurement, offences, including legal procurement information - will then cover everything - planning, procurement procedure, contract execution, etc.;</p>
<p>6.1.3. Receiving of notifications (news) about procurements (contracts) in progress according to the selected area (the frequency is set by the user as needed);</p>
<p>6.1.4. View published statistics.</p>
</td>
</tr>
</tbody>
</table>
</li>
</ol>

#### 7.2	ARCHITECTURE OF SAULĖ IS COMPONENTS

35. On the figure below one can find the possible architecture of the SAULĖ IS components (application software, data management software, integration software, frameworks, etc.). In the detailed analysis and design phase, the components demonstrated on the diagram can be decomposed by splitting them into other separate physical and logical components, ensuring that all functional and non-functional requirements for the component are met. The final architecture may be revised and must be agreed with the Contracting Authority.

![image](https://user-images.githubusercontent.com/61745726/92297297-8832c800-ef46-11ea-8049-29996351dc1b.png)
Fig. 7.2. Diagram of architecture of SAULĖ IS components

36. Description of architecture components: 
Table 7.2. Description of architecture components
<table width="100%">
<thead>
<tr>
<td width="33%">
<p>Component</p>
</td>
<td width="66%">
<p>Description</p>
</td>
</tr>
</thead>
<tbody>
<tr>
<td width="33%">
<p>1. Portal &ldquo;Saulė&rdquo;</p>
</td>
<td width="66%">
<p>1.1. SAULĖ IS portal is designed for performance of procurement procedures and procurement-related activities by the Procurement Executors, Suppliers and the Public. The portal must be created during the installation agreement. This component must implement the processes and functions described in Section 7.5.</p>
<p>1.2. &ldquo;Saulė&rdquo; Portal must be implemented using the advanced web application development technologies.</p>
<p>1.3. The implementation of a multi-tier architecture must ensure a minimum link between the application layer and the database level, avoiding the implementation of logic rules at the database level.</p>
<p>1.4. &ldquo;Saulė&rdquo; Portal must be developed based on microservice-oriented architecture or an equivalent principle.</p>
<p>1.5. Different environments must be created for authenticated users of &ldquo;Saulė&rdquo; Portal (Suppliers and Procurement Executors) and unauthorized users (designed for the public).</p>
<p>1.6. For authorized users (Suppliers and Procurement Executors), the functionality of connecting to &ldquo;Saulė&rdquo; Portal must be created using the VIISP authentication electronic service, and for foreign citizens - identification with a username and password.</p>
<p>1.7. During the execution of this Contract, the following interfaces of &ldquo;Saulė&rdquo; Portal must be realized:</p>
<p>1.7.1. Link No 1 - the link of &ldquo;Saulė&rdquo; Portal application and the Document Management Subsystem must be created for the purpose of the document management portal.</p>
<p>1.7.2. Link No 2 - a data exchange interface of &laquo;Saulė&raquo; Portal and e-Auctions application component must be created for data exchange and performance of e-Auction functions.</p>
<p>1.7.3. Link No 3 - link of &ldquo;Saulė&rdquo; Portal with the Saulė IS integration platform to receive / provide data from / to external system (s) or registers (s).</p>
<p>1.7.4. Link No 4 - link between Portal &ldquo;Saulė&rdquo; and CMS (Content Management System) application component for data exchange for displaying, control and management of public information.</p>
<p>1.7.5. CMS must have an administrator user interface for the system administrator.</p>
<p>1.7.6. Link No 5 - link of &ldquo;Saulė&rdquo; Portal with the software component of the recording / reading software of the Large Data Platform. &ldquo;Saulė&rdquo; Portal must transfer the data created / received on the portal to the Large Data Platform to the extent defined in the detailed analysis and design phase.</p>
<p>1.7.7. Link No 6 - &ldquo;Saulė&rdquo; Portal application link with Large Data Platform indexing (search) software. The link must ensure the possibility to access the data stored on the large data platform during the searches in &ldquo;Saulė&rdquo; Portal.</p>
<p>1.7.8. Link No 7 - link of &ldquo;Saulė&rdquo; Portal with &ldquo;Saulė&rdquo; DBMS for the purpose of structured portal data management.</p>
<p>1.7.9. Link No 8 - link of &ldquo;Saulė&rdquo; Portal with templates and e-form creation software to ensure the functionality of creating and further processing the documents used in the portal.</p>
<p>1.7.10. Link No 9 - link of &ldquo;Saulė&rdquo; Portal with e-documentation component (or service) to be implemented during the Installation Agreement. The link must ensure the possibility to perform e-document generation, verification and signing functions on &ldquo;Saulė&rdquo; Portal. The method of realizing the link must be detailed in the installation proposal depending on the proposed e-document component solution.</p>
<p>1.7.11. Link No 10 - data exchange interface between the Internal Portal and &ldquo;Saulė&rdquo; Portal. The interface must be implemented during the installation agreement in order to receive procurement data from &ldquo;Saulė&rdquo; Portal, to communicate with external portal users, perform procurement verification and report on the results, obtain data for risk calculations, other project authorities to receive project procurement data only for those of the internal portal users who have such a right to perform maintenance functions. The method of communication implementation between the Internal Portal and the external &ldquo;Saulė&rdquo; Portal must be implemented using RESTful or equivalent interfaces to the extent defined in the analysis and design phase.</p>
<p>1.7.12. Link No 11 - link of &ldquo;Saulė&rdquo; Portal application with the helpdesk software (ZenDesk, currently used by the Contracting Authority) in order to implement the functions of &ldquo;live chat&rdquo;, request registration and FAQs of the users of &ldquo;Saulė&rdquo; Portal.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>2. e-Auctions</p>
</td>
<td width="66%">
<p>2.1. The component to be created during the Installation Agreement to ensure the execution of the e-Auction, to provide information on the renewed procurement announced in the e-Auction (notice information, auction deadline and initial price information), to receive data on participants and to ensure the participation of suppliers in the provision of the e-Auction price.</p>
<p>2.2. This component shall implement the processes and functions specified in Section 7.6.8.2.</p>
<p>2.3. The data exchange interface with &ldquo;Saulė&rdquo; Portal (link No 2) must be implemented to the extent that the functions and data are required for the execution of e-Auctions.</p>
<p>2.4. E-Auctions component must be implemented using the advanced web application development technologies.</p>
<p>2.5. The implementation of a multi-tier architecture must ensure a minimum link between the application layer and the database level, avoiding the implementation of logic rules at the database level.</p>
<p>2.6. E-Auctions component must be developed based on microservice-oriented architecture or equivalent principles.</p>
<p>2.7. Users participating in the electronic auction must be able to log in to the e-Auctions module (without requiring re-authentication from their &ldquo;Saulė&rdquo; Portal account) and after the system checks whether the User has the right to compete, submit e-Auction data and allow to perform specified actions.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>3. Internal portal</p>
</td>
<td width="66%">
<p>3.1. Internal SAULĖ IS portal must be created during the Installation Agreement. The internal portal is intended for PPO employees and other supervisory and implementing agencies (hereinafter referred to as IA) to log in and receive data from &ldquo;Saulė&rdquo; Portal to perform the supervisory and control functions of these agencies.</p>
<p>3.2. This component must implement the processes and functions described in Section 7.8.</p>
<p>3.3. Internal portal must be implemented using the advanced web application development technologies.</p>
<p>3.4. The implementation of a multi-tier architecture must ensure a minimum link between the application layer and the database level, avoiding the implementation of logic rules at the database level.</p>
<p>3.5. Internal portal must be developed based on microservice-oriented architecture or equivalent principles.</p>
<p>3.6. Separate user interfaces (environments) must be created for authorized PPO employees (and system administrator) and employees of other supervisory and implementing agencies on the internal portal, where the environment implements the functions intended for the target group.</p>
<p>3.7. PPO employees must be authenticated on the internal portal using the PPO Single Sign On (SSO) and Active Directory solution to verify the employee login data (Link No 20 is shown in the diagram).</p>
<p>3.8. During the execution of this Contract, the following interfaces of the Internal Portal must be realized:</p>
<p>3.8.1. Link No 12 &ndash; link of the Internal Portal application with the helpdesk software (ZenDesk, currently used by the Contracting Authority) in order to implement the functions of &ldquo;live chat&rdquo;, request registration and FAQs.</p>
<p>3.8.2. Link No 13 &ndash; link of the Internal Portal with e-documentation component (or service) to be implemented during the Installation Agreement. The link must ensure the possibility to perform e-document generation, verification and signing functions on &laquo;Saulė&raquo; Portal. The method of realizing the link must be detailed in the installation proposal depending on the proposed e-document component solution.</p>
<p>3.8.3. Link No 14 - link of the internal portal application with templates and e-form creation software to ensure the functionality of creating and further processing the documents used on the portal.</p>
<p>3.8.4. Link No 15 &ndash; the link of the internal portal application to the Large Data Platform Indexing (Search) Software. The link must be able to search the data stored on the large data platform and save the data on the large data platform.</p>
<p>3.8.5. Link No 16 &ndash; internal portal link to Analytics (BI) software. The established link must be able to perform data selection and analysis by users of the Internal Portal using BI software.</p>
<p>3.8.6. Link No 17 &ndash; the link of the internal portal to the DBMS of the internal portal for the purpose of management of the structured portal data.</p>
<p>3.8.7. Link No 18 &ndash; internal portal link to Artificial (AI) software. The link must be established during the Installation Agreement in order to provide the users of the Internal Portal with the data necessary for risk management and analysis and for the use of other results of artificial intelligence.</p>
<p>3.8.8. Link No 19 &ndash; the link of the internal portal to the integration platform to receive / provide data from / to external system (s) or registers (s).</p>
<p>3.8.9. Link No 20 &ndash; the internal portal and PPO SSO (with Active Directory) data verification interface for verifying employee login credentials. The link must be established during the Installation Agreement.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>4. Relational DBMS and DB</p>
</td>
<td width="66%">
<p>4.1. Databases (DBs) must be installed in SAULĖ IS, which must ensure the management of structured data of SAULĖ IS components. The following DBs must be installed:</p>
<p>4.2. DB of &ldquo;Saulė&rdquo; Portal;</p>
<p>4.3. Internal portal DB;</p>
<p>4.4. Analytics Tool (BI) DB;</p>
<p>4.5. Artificial Intelligence (AI) Software DB.</p>
<p>4.6. In the detailed analysis and design phase, it must be decided how many independent (separate) database management systems (DBMS) must be installed in order to implement the above databases, while ensuring the performance and security of the DBMS and the DBs managed by it. The DBMS of the internal portal and &ldquo;Saulė&rdquo; Portal must be separate.</p>
<p>4.7. The Contracting Authority will provide the necessary DBMS licenses (DBMS services) provided by the State Cloud Service Provider (hereinafter - SCSPS) (it is preliminary expected that SCSPS will provide the following DBMS services: Microsoft SQL Server, Oracle Database Server, PostgreSQL, MySQL / MariaDB, SAP HANA). The Installer must submit DBMS licenses if the DBMS licenses provided by SCSPS are not suitable for its proposed SAULĖ IS installation solution.</p>
<p>4.8. AI and BI DBs must be installed and links must be made to the Artificial Intelligence (AI) and Analytics (BI) software components (links No 21 and 22 shown on the diagram).</p>
<p>4.9. Links must be made to the write / read component of the large data platform (link No 26 shown on the diagram) to ensure the possibility of data exchange between relational DBs and large data platforms for the purposes defined in the analysis and design phase.</p>
<p>4.10. The links between the SAULĖ IS relational DBMS and the API and / or DB type data exchange module component implemented in the Integration Platform (link No&nbsp; 33 shown on the diagram) must be implemented to provide / receive data from / to SAULĖ IS DB.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>5. Large data platform</p>
</td>
<td width="66%">
<p>5.1. The Large Data File System (LDFS or equivalent) (hereinafter referred to as LDFS) must be installed.</p>
<p>5.2. LDFS must implement a high-reliability data storage platform. LDFS must be installed to ensure high reliability of management servers (Name Node) and sufficient distribution of data servers (Data Node).</p>
<p>5.3. Resource management software must be installed in the LDFS, which has several levels of management and may include not only resource management, but also work allocation / monitoring and other resource management mechanisms.</p>
<p>5.4. The NoSQL-type database (link No 23) must be installed on the large data platform to store and manage large amounts of structured and unstructured information (large amounts of records, documents, other files), which must be defined in the detailed analysis and design phase.</p>
<p>5.5. The LDFS and NoSQL database must be used to store unstructured data in SAULĖ IS. The following data must be stored preliminarily: documents created by SAULĖ IS, received documents (procurement documents, their annexes), vector and raster data, BIM (Building Information Pivoting) data, video / audio material of meetings, extensions of database structures, through integration data received from interfaces, etc.</p>
<p>5.6. Extract Transform Load (ELL) / Extract Load Transform (ELT) software component (s) shall be installed to ensure the receipt, transformation and recording of data from data sources / external and internal Saulė IS portals or other external information systems and registers and store that data on a large data platform to the required extent and format. More than one component can be used to provide interfaces, depending on the data flows, format and data usage objectives defined in the detailed analysis and design phase. Appropriate links / interfaces between this component and the other listed data sources / and the data storage LDFS must be established to ensure performance:</p>
<p>5.6.1. Link No 24 &ndash; link of data recording / reading software component to LDFS for storage and / or retrieval of data received from various sources.</p>
<p>5.6.2. Link No 25 &ndash; link of data recording / reading software component to NoSQL type database for storage and / or reading of data received from various sources.</p>
<p>5.6.3. Link No 26 &ndash; link of data recording / reading software component with SAULĖ IS relational databases (Saulė portal DB, internal portal DB, AI DB, BI DB), which must be implemented if a meaningful use of such data flow is identified in the detailed analysis and design phase.</p>
<p>5.7. A specialized data analysis software must be installed to perform the analysis and statistical calculations of the various data stored in the LDFS and NoSQL data type databases. The most appropriate analysis software must be selected according to the data analysis tasks identified and defined in the analysis and design phase.</p>
<p>5.8. The following links must be implemented:</p>
<p>5.8.1. Link No 27 - the link of the analysis software component to the NoSQL type database for data analysis and storage.</p>
<p>5.8.2. Link No 28 - the link of the analysis software component to the LDFS for data analysis and storage. The link must be created during the Installation Agreement.</p>
<p>5.8.3. The PPO data analyst must be able to connect to the analysis software through the user interface.</p>
<p>5.9. A data indexing (search) software must be installed, which would enable the components of the Portal Saulė IS or the Internal Portal to save (index) documents and perform document search and download via integrated interfaces. The indexing software must provide an indexing service for incoming data and ensure a fast full-text search of documents.</p>
<p>5.10. The following links must be implemented:</p>
<p>5.10.1. Link No 29 - the link of data indexing (search) software component to NoSQL type database, if documents and / or document contents will be stored in NoSQL or equivalent DB.</p>
<p>5.10.2. Link No 30 - the link of data indexing (search) software component with LDFS if documents and / or document contents will be stored in LDFS.</p>
<p>5.11. Links between data writing / reading software and API and DB type data exchange module components implemented in the Integration Platform must be implemented in the large data platform (link No 32 shown on the diagram), if the data flow from the Integration Platform to the Large Data Platform is identified and defined in the detailed analysis and design phase and vice versa - from Large Data Platform to Integration Platform (for data provision).</p>
<p>5.12. For the monitoring and management of large data platforms, a management and monitoring software must be installed, enabling centralised monitoring and management of key components of large data.</p>
<p>5.13. Software must be installed to ensure the security of the large data platform:</p>
<p>5.14. user administration (including role management) and identification (unified link to large data platform components) component;</p>
<p>5.15. security parameter administration component;</p>
<p>5.16. a centralised component for recording and management of audit records of large data platform components.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>6. Analytical (BI) software</p>
</td>
<td width="66%">
<p>6.1. Business Intelligence software must be developed or made available for use, enabling the users of the internal portal to perform analytics in various sections, to prepare reports based on sections from selected / prepared data models. There must be access for the system administrator and PPO experts.</p>
<p>6.2. Link No 22 must be implemented - Analytical (BI) software link to analytical DB.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>7. Artificial Intelligence (AI) software</p>
</td>
<td width="66%">
<p>7.1. Artificial Intelligence software must be developed or made available to perform alternative risk assessments of procurement and contracts. There must be access for the system administrator and PPO experts.</p>
<p>7.2. Link No 21 must be implemented &ndash; Link of the Artificial Intelligence (AI) software to the AI database.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>8. Active Directory, PPO SSO</p>
</td>
<td width="66%">
<p>8.1. PPO employees must be logged in to the internal portal without having to re-enter their login details if the PPO employee has already identified himself / herself on the workstation. PPO SSO (Single Sign On) software must be used to ensure the solution.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>9. Helpdesk software</p>
</td>
<td width="66%">
<p>9.1. The PPO Helpdesk software ZenDesk must be used.</p>
<p>9.2. The ZenDesk software must provide the functionality of the Help Subsystem features required for the Live PPO Consulting process to register problems and inquiries. Users of the external portal do not need to log in to the ZenDesk software portal again in order to request information. The RESTful interfaces of ZenDesk functions must be used for the implementation solution on &ldquo;Saulė&rdquo; Portal.</p>
<p>9.3. Communication implementation methods between external &ldquo;Saulė&rdquo; Portal / Internal portal with ZenDesk software will have to be detailed during analysis and design phase.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>10. CMS</p>
</td>
<td width="66%">
<p>10.1. Content Management System Software, designed for the content management of the external portal &ldquo;Saulė&rdquo; and for the implementation of the functions of the public information subsystem (see Section 7.6.12 Requirements&nbsp; for Published Information Subsystem), must be created or made available for use by.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>11. Document management subsystem</p>
</td>
<td width="66%">
<p>11.1. The Document Management Subsystem must be developed and installed. The subsystem is designed for users of organisations and internal portal for preparation, signing (with the help of e-documents component), storage and archiving of documents. The subsystem must be able to perform the following actions:</p>
<p>11.2. Create a document according to a template or create a new document;</p>
<p>11.3. Assign a registration number, manage, save in the required formats, coordinate, sign, if necessary, export the document, send to SAULĖ IS users;</p>
<p>11.4. Create tasks;</p>
<p>11.5. Keep the document for a set period of time;</p>
<p>11.6. Archive SAULĖ IS documents.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>12. E-document component</p>
</td>
<td width="66%">
<p>12.1. E-document component, that must be able to format, sign, and verify e-documents according to ADOC, PDF-LT, ASiC specifications, must be installed.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>13. Software for creation of templates and e-forms</p>
</td>
<td width="66%">
<p>13.1. Software for creation of templates and e-forms, designed for&nbsp; administration, creation, management and use of templates and data entry forms used by &ldquo;Saulė&rdquo; portal and the internal portal (for example, contracts, procurement conditions, other procurement documents, protocols and other e-forms and document templates), must be created or submitted.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>14. Centralised auditing software</p>
</td>
<td width="66%">
<p>14.1. A centralised audit software (Balabit) available at the PPO must be used. A link of the relational DBMS, SAULĖ IS applications and integration platform to the centralised audit software must be established (link No 36 and 37 are shown on the diagram, respectively), which would ensure centralised auditing of the operation and use of SAULĖ IS applications.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>15. SAULĖ IS integration platform</p>
</td>
<td width="66%">
<p>15.1. The component must be implemented during the Installation Agreement. SAULĖ IS integration platform must implement a separate architectural level of integration. SAULĖ IS integration platform must implement all interfaces with external systems and registers and internal SAULĖ IS components.</p>
</td>
</tr>
</tbody>
</table>

## 7.3	FUNCTIONAL DIAGRAM OF “SAULĖ” PORTAL

52. Below one can find the functional diagram of “Saulė” portal. In the detailed analysis and design phase, the components demonstrated on the diagram can be decomposed by splitting them into other separate physical and logical components, ensuring that all functional and non-functional requirements for the component are met.

![image](https://user-images.githubusercontent.com/61745726/92297311-b7e1d000-ef46-11ea-8212-e444c2e8bc80.png)

Fig. 7.3. Functional diagram of “Saulė” portal

Table 7.3. Description of “Saulė” portal functional components

<table width="100%">
<thead>
<tr>
<td width="33%">
<p>Component</p>
</td>
<td width="66%">
<p>Description</p>
</td>
</tr>
</thead>
<tbody>
<tr>
<td width="33%">
<p>1. Search subsystem</p>
</td>
<td width="66%">
<p>1.1. Search Subsystem must be developed and implemented to provide a one-window search for both notice metadata and full-text search of published documents (for example, in pdf and docx, doc formats).</p>
<p>1.2. Advanced search functionality must be developed to allow searching by selecting more than one SAULĖ IS item (contracts, notices, plans) and searching by different metadata by selecting from a list of values or specifying a search fragment, respectively.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>2. Public information subsystem</p>
</td>
<td width="66%">
<p>2.1. A public information subsystem must be developed and implemented. The subsystem must be able to view all publicly available procurement information published by users and established in legal acts on procurement, from the plan to the execution of the contract, with the exception of confidential information, filter, subscribe to surveys, conduct surveys and view FAQs. The subsystem must implement the following processes:</p>
<p>2.1.1. SAULĖ IS viewing public data by groups / areas, filtering data;</p>
<p>2.1.2. SAULĖ IS subscription order;</p>
<p>2.1.3. News management and review;</p>
<p>2.1.4. Conducting surveys;</p>
<p>2.1.5. Public information is managed with the help of a content management system (CMS).</p>
</td>
</tr>
<tr>
<td width="33%">
<p>3. Helpdesk subsystem</p>
</td>
<td width="66%">
<p>3.1. A helpdesk subsystem must be designed and implemented. The subsystem must provide the functionality for:</p>
<p>3.2. View of FAQs and tutorial movies;</p>
<p>3.3. Live (online (live chat)) correspondence with a PPO specialist;</p>
<p>3.4. Registration and submission of requests / problems to the PPO.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>4. Communication system</p>
</td>
<td width="66%">
<p>4.1. A communication subsystem must be developed and implemented. In the communication subsystem of procurement participants, the options to reach all users registered in SAULĖ IS must be implemented.</p>
<p>4.2. The following processes must be implemented in the communication subsystem of the procurement participants:</p>
<p>4.3. Sending a message (mass, standard) to registered System users;</p>
<p>4.4. Sending a reply to a received message;</p>
<p>4.5. Communication of Procurement Executors (PE) during claim processing;</p>
<p>4.6. Sending a system message to the users registered in the System.</p>
<p>4.7. A link must be established between the communication subsystem and the components in the field of procurement executors and suppliers (link No 12 and 13 are shown on the diagram).</p>
</td>
</tr>
<tr>
<td width="33%">
<p>5. Organisation domain and user administration subsystem</p>
</td>
<td width="66%">
<p>5.1. An organisation domain and user administration subsystem must be developed and implemented. The subsystem is intended for all organisations of &ldquo;Saulė&rdquo; portal (Procurement Executors and Suppliers) to administer the data of their organisation.</p>
<p>5.2. The purpose of the subsystem is to register organisations, users and manage their roles and rights, manage data and templates in the organisation domain. This part of the system is only available to registered users.</p>
<p>5.3. Functionality must be created in the organisation domain and user administration subsystem for the implementation of the following processes:</p>
<p>5.4. Registration of organisations;</p>
<p>5.5. User authentication;</p>
<p>5.6. Management of organisation users;</p>
<p>5.7. Management of the transfer of functions of the administrator of the organisation;</p>
<p>5.8. Authorization of Contracting Authorities, Suppliers in the action system (assignment of rights);</p>
<p>5.9. Deactivation of organisations and users;</p>
<p>5.10. Management of parameters and templates in an organisation domain.</p>
<p>5.11. A link must be established between the organisation domain and the components of the user administration subsystem and the procurement executors and suppliers domain (links No 11 and 14 shown on the diagram).</p>
</td>
</tr>
<tr>
<td width="33%">
<p>6. Subsystem of contract</p>
</td>
<td width="66%">
<p>6.1. The subsystem of contracts must be designed and implemented. The subsystem must implement the functionality for the management of procurement contracts from the moment of concluding the contract to the end of the contract.</p>
<p>6.2. The following processes must be implemented with the help of the subsystem:</p>
<p>6.3. Conclusion, signing, entry into force, execution, and termination of the contract (together with the actual amount of the contract);</p>
<p>6.4. Contract amendment;</p>
<p>6.5. Termination of the contract or its amendment;</p>
<p>6.6. Inclusion of suppliers in lists of unreliable suppliers and / or list of suppliers who provided false information;</p>
<p>6.7. A link must be established between the contract subsystem and the components and suppliers in the area of procurement executors (links No 9 and 10 on the diagram).</p>
</td>
</tr>
<tr>
<td width="33%">
<p>7. Subsystem of preliminary contracts</p>
</td>
<td width="66%">
<p>7.1. A subsystem of preliminary contracts must be developed and implemented. The subsystem must implement the functionality for the execution of procurements under preliminary contracts, placing orders with suppliers and concluding main contracts.</p>
<p>7.2. The functions of the subsystem must ensure the electronic management of the preliminary contracts and the main contracts concluded on the basis thereof and the organisation of a renewed competition for the Procurement Executor. The preparation of draft main contracts must also be created according to the templates created by SAULĖ IS.</p>
<p>7.3. The following processes must be implemented with the help of the subsystem:</p>
<p>7.4. Procurement under a preliminary contract from one supplier;</p>
<p>7.5. Procurement under a preliminary contract from several suppliers without renewed competition;</p>
<p>7.6. Procurement under a renewed tender procedure under a preliminary contract;</p>
<p>7.7. Inclusion of suppliers in lists of unreliable suppliers and / or list of suppliers who provided false information;</p>
<p>7.8. Conclusion, signing and publication of the contract.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>8. Subsystem of E-Auctions</p>
</td>
<td width="66%">
<p>8.1. A subsystem of e-Auctions must be developed and implemented to organise and execute e-Auctions. The subsystem must implement functionality for:</p>
<p>8.2. E-Auction organisation;</p>
<p>8.3. E-Auction notice;</p>
<p>8.4. E-Auction management;</p>
<p>8.5. Execution of the E-Auction through the e-Auctions application;</p>
<p>8.6. Queuing;</p>
<p>8.7. Determination of a successful tenderer.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>9. Planning subsystem</p>
</td>
<td width="66%">
<p>9.1. The Procurement Planning Subsystem must be developed and implemented. The subsystem must implement the functionality for the implementation of the following processes:</p>
<p>9.2. Procurement planning data management and storage, i.e. the needs of initiators are registered and accumulated;</p>
<p>9.3. Calculation of values and provision of recommendations to the PE on the choice of procurement method;</p>
<p>9.4. Systematisation of information and data;</p>
<p>9.5. Drawing and approval of procurement plans based on the systematised information and data;</p>
<p>9.6. Formation of summary tables for publication based on the data of the approved procurement plans;</p>
<p>9.7. Ensuring of control of the execution of procurement plans and automatic movement of data to other SAULĖ IS subsystems.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>10. Subsystem of procurement procedure</p>
</td>
<td width="66%">
<p>10.1. A Subsystem of Procurement Procedures must be created and implemented to ensure the execution of procurement procedures for different types of procurement and their use, as well as the use of data collected during these procedures in other SAULĖ IS subsystems.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>11. Procurement notice subsystem</p>
</td>
<td width="66%">
<p>11.1. 63.1. A procurement notice subsystem must be created and implemented. The subsystem must implement functionality for:</p>
<p>11.2. 63.1.1. Procurement notice according to different types of procurement;</p>
<p>11.3. 63.1.2. Creation of a procurement notice.</p>
<p>11.4. 63.2. A link must be established between the procurement notice subsystem and the planning and tender assessment subsystems (links No 4 and 5 shown on the diagram).</p>
</td>
</tr>
<tr>
<td width="33%">
<p>12. Tender assessment subsystem</p>
</td>
<td width="66%">
<p>12.1. A tender assessment subsystem must be developed and implemented to ensure the implementation of the tender assessment procedures and their use, as well as the use of the data collected during these procedures in other SAULĖ IS subsystems. The subsystem must have automated tender assessment functionality based on the criteria and formulas published in the notice.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>13. Subsystem for organisation and planning of PC meetings</p>
</td>
<td width="66%">
<p>13.1. A subsystem for organisation and planning of PC meetings must be developed and implemented to ensure organisation and taking of minutes of PC meetings.&nbsp; The user must have an option to:</p>
<p>13.1.1. Create a PC meeting;</p>
<p>13.1.2. Create an agenda for the PC meeting - a structured list of issues and link it to the meeting materials and documents;</p>
<p>13.1.3. Send invitations to PC members to attend the meeting;</p>
<p>13.1.4. PC members to authenticate and attend the meeting, vote for or against the issue (s);</p>
<p>13.1.5. Where appropriate, the members of the PC to express their views on a specific issue;</p>
<p>13.1.6. If necessary, organise remote video or audio conferences;</p>
<p>13.1.7. Record and save remote video or audio conferences as needed;</p>
<p>13.1.8. If necessary, automatically fill in the selected minutes filling the fields using voice recognition software. Detailed requirements are described in Item 1235.7.</p>
<p>13.2. A link must be established between the PC meeting subsystem and the procurement notice, tender assessment, planning subsystems (links No 1, 2 and 3 shown on the diagram) and other subsystems that require the functions of organising the meeting and drawing up minutes.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>14. Tender submission subsystem</p>
</td>
<td width="66%">
<p>14.1. A tender submission subsystem shall be developed and implemented for Suppliers to register for participation in tenders, submit tenders, participate in tender renewal procedures and participate in the e-Auction (via e-Auctions module) provision.</p>
<p>14.2. The subsystem must provide the functionality that is intended for:</p>
<p>14.2.1. For supplier registration and login (supplier&rsquo;s organisation creation, user assignment and account administration are performed through the organisation domain and user administration subsystem);</p>
<p>14.2.2. Submission and signing of tenders by electronic signature;</p>
<p>14.2.3. Provision of updated tenders;</p>
<p>14.2.4. Receiving and sending of messages (using the communication subsystem);</p>
<p>14.2.5. Participation in the e-Auction (performed through the e-Auction module).</p>
<p>14.3. A link must be established between the tender submission subsystem and the tender assessment, e-Auctions module, communication, contracts, organisation subsystems (the links No 15, 13, 14 and 10 shown on the diagram). The method of realization of the link and a detailed description will have to be provided during the analysis and design phase.</p>
</td>
</tr>
</tbody>
</table>

#### 7.4	FUNCTIONAL DIAGRAM OF INTERNAL PORTAL

67. Below one can find the functional diagram of SAULĖ IS internal portal. In the detailed analysis and design phase, the components demonstrated on the diagram can be decomposed by splitting them into other separate physical and logical components, ensuring that all functional and non-functional requirements for the component are met.

![image](https://user-images.githubusercontent.com/61745726/92297327-e069ca00-ef46-11ea-8c90-6c46dae835a5.png)

Fig. 7.4. Functional diagram of the internal portal
Table 7.4. Description of functional components of the internal portal 

<table width="100%">
<thead>
<tr>
<td width="33%">
<p>Component</p>
</td>
<td width="66%">
<p>Description</p>
</td>
</tr>
</thead>
<tbody>
<tr>
<td width="33%">
<p>1. Control and offence subsystem</p>
</td>
<td width="66%">
<p>1.1. The control and offence subsystem must be designed and implemented. The subsystem is intended to assess the implementation of procurement control and offence prevention from receipt to dispatch of the assessment report. The following processes must be implemented with the help of the subsystem:</p>
<p>1.2. Review of the list of contracts to be assessed, assessed, evaluated, contracts and organisations to be verified and verified;</p>
<p>1.3. Creation of a procurement, contract or Procurement Executor assessment task and allocation of resources;</p>
<p>1.4. Preparation and approval of the procurement, contract or the Procurement Executor assessment report;</p>
<p>1.5. Submission of an Inquiry to the Procurement Executor or other organisation and receipt of a response;</p>
<p>1.6. Approval of the procurement, contract, the Procurement Executor assessment report, the Inquiry or the requests of the Procurement Controller;</p>
<p>1.7. Stop procedures;</p>
<p>1.7.1. Form a task for another Procurement Controller;</p>
<p>1.7.2. Submission of an assessment report and control of the implementation of obligations or recommendations;</p>
<p>1.7.3. Receipt of a request for confirmation of consent to perform the procurement and approval or rejection of consent.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>2. Verification subsystem</p>
</td>
<td width="66%">
<p>2.1. The verification subsystem must be developed and implemented. The subsystem is intended for:</p>
<p>2.2. Institutions responsible for the selection and supervision of the implementation of projects financed by the European Union (hereinafter referred to as the EU), other international financial support or state funds (hereinafter referred to as the Implementing Agencies);</p>
<p>2.3. Institutions which function is to supervise procurements financed from the state budget (for example, the State Audit Office and Audit Service, the Competition Authority, STT, etc.) (hereinafter referred to as the Supervisory Agencies).</p>
<p>2.4. The subsystem must have functionality to implement the following processes:</p>
<p>2.5. Preliminary verification of the procurement package by the Implementing Agencies;</p>
<p>2.6. Ex-post verification of the procurement by the Implementing Agencies;</p>
<p>2.7. Search and analysis of procurements, procurement data of the supervisory agencies, data of suppliers / procurement executors.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>3. Risk management subsystem</p>
</td>
<td width="66%">
<p>3.1. The Risk Management Subsystem must be designed and implemented for:</p>
<p>3.1.1. PPO specialists performing the functions of risk assessment and management of procurement, contracts and Procurement Executors.</p>
<p>3.2. Risk management processes:</p>
<p>3.3. Listing of risky procurements, contracts or Procurement Executors;</p>
<p>3.4. Compilation of &ldquo;White&rdquo; and &ldquo;Black&rdquo; lists;</p>
<p>3.5. Managements of risks related to procurement, contracts or Procurement Executors;</p>
<p>3.6. Management of risk assessment and risk management model.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>4. Administration and configuration subsystem</p>
</td>
<td width="66%">
<p>4.1. The Administration and Configuration Subsystem must be created and implemented. The subsystem must implement the following functionality, which includes:</p>
<p>4.2. Administration of templates and forms - creation of templates and e-forms is done with the help of software;</p>
<p>4.3. Management document registers;</p>
<p>4.4. An audit module for viewing, filtering and exporting of audit records;</p>
<p>4.5. User management. Functionality for creation, management and assignment of roles to users of the internal portal must be created, providing the option for Implementing Agencies to create the necessary users and grant rights in SAULĖ IS system.</p>
<p>4.6. Functionality must also be developed for:</p>
<p>4.7. Registration of the implementing or supervisory agencies;</p>
<p>4.8. Project information management of the Implementing Agencies;</p>
<p>4.9. The establishment of users of Implementing Agencies using SFMIS or NORIS and users of Supervisory Agencies;</p>
<p>4.10. The process of creation of users for implementing agencies that do not use SFMIS or NORIS.</p>
</td>
</tr>
</tbody>
</table>

#### 7.5	GENERAL REQUIREMENTS

<ol>
<li>SAULĖ IS data entry forms shall be designed in such a way that the data entry would be as structured as possible.
<ul>
<li>Data entry forms shall be filled in as automatically as possible with data stored in SAULĖ IS or other IS and registers accessible through integration interfaces.</li>
</ul>
</li>
<li>The following shall be available in SAULĖ IS lists:
<ul>
<li></li>
<li>Functionality for marking of many records to perform certain actions (for example, export, delete the selected records). At the detailed analysis or design phase, it must be agreed which lists must allow the marking of many records.</li>
<li>It must be possible to print and export the list of objects to * .pdf, * .xlsx, or equivalent files. During the detailed analysis it must be agreed which lists should be the subject to this functionality.</li>
<li>It must be possible to filter the list of objects and sort it according to the attributes belonging to that list. Exceptions may be made in agreement with the Contracting Authority.</li>
<li>The lists must display the number of records in the list. After filtering the list, the number of records found must be displayed.</li>
</ul>
</li>
<li>All search / filtering functions, unless otherwise agreed by the Installer during the detailed analysis and design phase, shall be implemented in accordance with these rules:
<ul>
<li>In text search fields, the search must be realized by a fragment of a word or combination of numbers and a complete word;</li>
<li>The search must be performed according to Lithuanian letters and using Latin equivalents of letters instead of Lithuanian letters (for example, treating the letters &ldquo;&scaron;&rdquo; and &ldquo;s&rdquo; as one);</li>
<li>The search must be case-insensitive;</li>
<li>The search must be performed only on those components and data sets to which the external user of the EPP has the access rights;</li>
<li>Search results must be presented in the form of a list;</li>
<li>The number of search results should be displayed after the search.</li>
</ul>
</li>
<li>The validation of the data entered in the data entry forms shall be performed in accordance with the validation rules established for the forms during the detailed analysis and design phase:
<ul>
<li>Mandatory input data must be validated;</li>
<li>The format of the data (date, number, text or other established rules) must be validated;</li>
<li>Attached file extensions and file size must be validated;</li>
<li>A logical validation must be performed between the form elements - the selection (input) of one form element must be able to enable / disable other form elements, etc.</li>
</ul>
</li>
<li>For all functions described in this technical specification intended for creation of data or documents, the functions of editing and deleting or cancelling those data or documents shall be implemented, which shall be compatible with the logic of the activity.</li>
<li>Coordinated SAULĖ IS locations must allow the user with such a right to mark information or part of the text in a document or e-form data fields that are confidential (the text of confidential information must be visible to the presence of the text, but become invisible and illegible). The Installer, together with the Contracting Authority, must identify the objects in which it must be possible to mark confidential information by means of marking (document and / or e-data form).</li>
<li>Coordinated SAULĖ IS locations must use a content text editor that operates on the WYSIWYG principle (What You See Is What You Get, or "what you see matches what you get") or equivalent principle, i.e. must be able to create, format and edit tables, have basic text editing and formatting functions (alignment, paragraphs, numbering, colour, etc.), image loading functions into text.</li>
<li>The list of file formats that can be uploaded to SAULĖ IS must be agreed during the detailed analysis and design phase.</li>
<li>SAULĖ IS shall have the history of change of all created entities, which can be edited by SAULĖ IS users, by coordinating with the Contracting Authority the attributes of the entity to be protected and submitted for review. The Installer together with the Contracting Authority must identify and agree on the location of the display of the latter historical (audited) data.</li>
<li>All templates, template documents, classifiers created by SAULĖ IS must have visibility for users &ldquo;from&rdquo;, &ldquo;until&rdquo; deadlines determining when the template / classifier is presented to the user for selection, and validity &ldquo;from&rdquo;, &ldquo;until&rdquo; deadlines that determine when the selected the template / classifier can be used in the process (for example, a published procurement).</li>
<li>After the change of templates, template documents, classifiers in SAULĖ IS, a new version of the template, template document, classifier must be created in all cases.</li>
<li>The subsystem of Procurement Procedures and Communication shall be able to provide automatic translation into English. The Service Provider must create or submit the software required for the implementation of the solution (for example, https://www.tilde.lt/kalbines-technologijos/masininis-vertimas) in accordance with the requirements specified in 5 software licences. The need for functionality must be considered and the final implemented solution must be agreed with the Contracting Authority during analysis and design phase.</li>
<li>In all cases where time limits apply, the responsible person shall be automatically informed by notice of the impending expiry of the time limit and of the expiry of the time limit. Each system user must be able to determine which messages they want to receive and the channels they would like to receive messages (e-mail, SAULĖ IS message box).</li>
</ol>

#### 7.6	REQUIREMENTS FOR “SAULĖ” PORTAL

<h3><a name="_Toc50101518"></a>1.1.1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Requirements for procurement planning subsystem</h3>
<h4>1.1.1.1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; General requirements for procurement planning subsystem</h4>
<ol>
<li>SAULĖ IS Procurement Planning Subsystem shall allow:
<ul>
<li>Manage and collect data for procurement planning, i.e. to register and accumulate the needs of procurement initiators;</li>
<li>Systematize information and data of planned procurement;</li>
<li>Approve procurement plans and publish information on planned procurements.</li>
</ul>
</li>
<li>SAULĖ IS Procurement Planning Subsystem shall:
<ul>
<li>Calculate values and provides recommendations to the PE on the choice of the planned procurement method;</li>
<li>Procurement plans are formed based on the systematized information and data and there should be an option to approve them;</li>
<li>Publication summary tables are formed based on the data of the approved procurement plans;</li>
<li>Ensure control over the execution of procurement plans and automatic data flow to and from other SAULĖ IS subsystems.</li>
</ul>
</li>
<li>It must be possible to initiate the procurement planning process in SAULĖ IS:
<ul>
<li>in the current budget year (if necessary for a longer period) by starting to plan procurement of goods, services and (or) works;</li>
<li>quarterly or at other intervals set by the System Administrator, when the procurement plan is to be reviewed and, if necessary, updated / revised;</li>
<li>in case of an unforeseen need to procure a new good / service / work from suppliers / contractors that is not included in the approved procurement plan (i.e. it must first be included in the procurement plan before any procurement is started).</li>
</ul>
</li>
<li>The PPO system administrator must be able to change all terms related to procurement planning set in the System.</li>
</ol>
<h4>1.1.1.2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Requirements for implementation of Procurement Planning Subsystem process and functions</h4>
<ol start="5">
<li>The functionality of the Procurement Planning Subsystem must be implemented. Below one can find a process diagram and requirements for the process implementation.</li>
</ol>
![image](https://user-images.githubusercontent.com/61745726/92297349-27f05600-ef47-11ea-8f45-c1b4b8a5fea1.png)
Fig. 7.5. Procurement planning process diagram

Table 7.1. Requirements for implementation of procurement planning process 
<h3><a name="_Toc50101518"></a></h3>
<table width="688">
<tbody>
<tr>
<td width="74">
<p>Process No</p>
</td>
<td width="118">
<p>Process title</p>
</td>
<td width="111">
<p>Process participant</p>
</td>
<td width="384">
<p>Requirements for implementation</p>
</td>
</tr>
<tr>
<td width="74">
<p>E1</p>
</td>
<td width="118">
<p>Beginning of the process</p>
</td>
<td width="111">
<p>-</p>
</td>
<td width="384">
<p>1. The PPO system administrator must be able to set the conditions and restrictions for initiating the procurement plan (deadline for creation of the automatic procurement plan, duration of the procurement plan, number of active procurement plans in the institution, etc.).</p>
</td>
</tr>
<tr>
<td width="74">
<p>T1</p>
</td>
<td width="118">
<p>Initiate the creation of annual procurement planning environment</p>
</td>
<td width="111">
<p>PE</p>
</td>
<td width="384">
<p>2. SAULĖ IS must be able to initiate the creation of an annual procurement planning environment for the preparation of procurement plans in any future year.</p>
</td>
</tr>
<tr>
<td width="74">
<p>E2</p>
</td>
<td width="118">
<p>Beginning of the year</p>
</td>
<td width="111">
<p>SAULĖ IS</p>
</td>
<td width="384">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="74">
<p>E3</p>
</td>
<td width="118">
<p>End of the process</p>
</td>
<td width="111">
<p>-</p>
</td>
<td width="384">
<p>-</p>
</td>
</tr>
<tr>
<td width="74">
<p>T2</p>
</td>
<td width="118">
<p>Create annual procurement planning environment</p>
</td>
<td width="111">
<p>SAULĖ IS</p>
</td>
<td width="384">
<p>3. If the annual procurement planning environment has not been created upon the PE initiative, then SAULĖ IS automatically creates annual procurement planning environment.</p>
<p>4. The annual procurement planning environment must be created automatically according to the deadline set by the administrator (for example, no ex-post than by the end of the first quarter of the current year).</p>
</td>
</tr>
<tr>
<td width="74">
<p>T3</p>
</td>
<td width="118">
<p>Inform about the creation of the environment</p>
</td>
<td width="111">
<p>SAULĖ IS</p>
</td>
<td width="384">
<p>5. If the annual procurement planning environment has been created automatically, then SAULĖ IS must inform the PE about the fact of the creation of the annual procurement environment.</p>
</td>
</tr>
<tr>
<td width="74">
<p>T4</p>
</td>
<td width="118">
<p>Select a year</p>
</td>
<td width="111">
<p>PV</p>
</td>
<td width="384">
<p>6. Once the creation of the procurement plan environment has been initiated, it must be possible to select the year for which the environment is being created and to provide additional information.</p>
<p>7. It must be possible to choose only the current or the following year (it must not be possible to fill in / edit the information provided retrospectively).</p>
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="74">
<p>T5</p>
</td>
<td width="118">
<p>Manage information on the procurement demand</p>
</td>
<td width="111">
<p>PV</p>
</td>
<td width="384">
<p>8. SAULĖ IS must have an option to:</p>
<p>8.1. enter the need for the planned procurement manually;</p>
<p>8.2. import the data on creation / modification of the initiator&rsquo;s needs from:</p>
<p>8.2.1. through the integration of other systems;</p>
<p>8.2.2. template * .xls, * .xlsx or equivalent format files;</p>
<p>8.2.3. template * .pdf format files;</p>
<p>8.3. export procurement plan data to:</p>
<p>8.3.1. other systems through integrations;</p>
<p>8.3.2. * .xls, * .xlsx or equivalent format files;</p>
<p>8.3.3. * .pdf format files;</p>
<p>8.4. view compiled/imported data of planned procurement;</p>
<p>8.5. edit compiled/imported data on planned procurement;</p>
<p>8.6. delete the entered need if it becomes obsolete;</p>
<p>8.7. archive information on deleted needs, making them visible to PEs and supervisors;</p>
<p>8.8. confirm the need and submit it for processing.</p>
<p>9. It must be possible to describe the needs of the initiators with additional free-form information, but for the description one must use the same SAULĖ IS classifiers which are also used for planned procurement.</p>
</td>
</tr>
<tr>
<td width="74">
<p>&nbsp;</p>
</td>
<td width="118">
<p>Demands of initiators</p>
</td>
<td width="111">
<p>SAULĖ IS</p>
</td>
<td width="384">
<p>10. In SAULĖ IS the needs of initiators entered / imported in step T5 must be accumulated.</p>
</td>
</tr>
<tr>
<td width="74">
<p>T6</p>
</td>
<td width="118">
<p>Manage information on the procurement demand</p>
</td>
<td width="111">
<p>&nbsp;</p>
</td>
<td width="384">
<p>11. SAULĖ IS must be able to change the entered needs of initiators, manage data related to planned procurement.</p>
<p>12. There must be an option to:</p>
<p>12.1. open the window for entering / reviewing / editing the information of the planned procurement and, if necessary, change the procurement information entered in the lines that have the attribute &ldquo;Planned&rdquo;; When changing the information on planned procurement provided in the window for entering / reviewing / editing information on a planned procurement, it is not allowed to change the CPV number of the planned procurement when several procurements are made from one line and one of them has already been executed;</p>
<p>12.2. mark that the planned procurement is included in the expenditure plans approved under the financing programs for the budget year approved by the PE;</p>
<p>12.3. assign CPV number.</p>
<p>13. SAULĖ IS must:</p>
<p>13.1. provide the recommended CPV numbers of the planned procurement according to the name of the planned procurement;</p>
<p>13.2. warn PE about artificial decomposition if:</p>
<p>13.2.1. different CPV numbers have been chosen, although the object and / or names of the planned procurement coincide;</p>
<p>13.2.2. CPV numbers differ by 1 digit, although the subject of the planned procurement is the same and the names are different.</p>
<p>13.3. deactivate / activate, deactivated planned procurement;</p>
<p>13.4. group / merge selected planned procurements into one planned procurement;</p>
<p>13.5. split the planned procurement into lots;</p>
<p>13.6. delete the planned procurement if the procurement has not started;</p>
<p>13.7. postpone the planned procurement from previous years if they are not fulfilled.</p>
<p>14. If it is selected to group / combine the planned procurements, the PE shall provide recommendations for the execution of the procurement and the requirement to re-select the method of execution of the planned procurement.</p>
<p>15. If it is selected to remove a planned procurement from the procurement plan, SAULĖ IS provides the PE with a list of procurements, the procurement methods of which will have to be changed after removing the selected procurement.</p>
</td>
</tr>
<tr>
<td width="74">
<p>&nbsp;</p>
</td>
<td width="118">
<p>Data of the planned procurement</p>
</td>
<td width="111">
<p>SAULĖ IS</p>
</td>
<td width="384">
<p>16. SAULĖ IS must collect the data necessary for the preparation of the procurement plan (if necessary, the list of fields specified during the detailed analysis and design phase may be changed):</p>
<p>16.1. which year is referred to the procurement plan;</p>
<p>16.2. date of data entry;</p>
<p>16.3. initiator;</p>
<p>16.4. Procurement Executor;</p>
<p>16.5. name;</p>
<p>16.6. type (procurement of the classic sector, procurement of the utility sector, procurement of fuel, procurement of defence and security, internal transaction, other, if entered by the System Administrator);</p>
<p>16.7. name of the group which it refers;</p>
<p>16.8. &nbsp;type of energy resources (for the type of fuel procurement);</p>
<p>16.9. name of energy resources (for the type of fuel procurement);</p>
<p>16.10. the main CPV number;</p>
<p>16.11. additional CPV numbers;</p>
<p>16.12. procurement method;</p>
<p>16.13. procured quantity;</p>
<p>16.14. units of measurement;</p>
<p>16.15. planned value of the contract;</p>
<p>16.16. planned start of the procurement (quarter or month or specific date);</p>
<p>16.17. planned duration of the contract (in days, months or a specific date);</p>
<p>16.18. indication of whether the procurement will be made through CPO;</p>
<p>16.19. indication of whether the procurement will be made using CPP IS means;</p>
<p>16.20. indication of whether it is referred to social procurement;</p>
<p>16.21. indication of whether environmental requirements will be applied;</p>
<p>16.22. Project code (here the project is to be understood as any (not necessarily EU) project and the procurement belonging to the same project must be aggregated, even if the goods and works are procured separately or if the procurements do not take place in the same calendar year). If it is EU project, the user can select from a list of projects (in SAULĖ IS this list of projects is administered in the Verification subsystem);</p>
<p>16.23. indication of whether it is financed from the EU funds;</p>
<p>16.24. indication of whether EU funding can be provided;</p>
<p>16.25. source of financing (when not financed from the EU funds);</p>
<p>16.26. indication of whether an innovative procurement will be made;</p>
<p>16.27. indication of whether energy efficiency requirements apply;</p>
<p>16.28. indication of whether the energy efficiency and environmental requirements for the road vehicle apply;</p>
<p>16.29. indication of whether the procurement is authorized to be performed by another organisation;</p>
<p>16.30. indication of whether a dynamic purchasing system (DPS) / qualification system (QS) will be developed for the execution of the planned procurement;</p>
<p>16.31. indication of whether a dynamic procurement system (DPS) / qualification system (QS) will be developed for the execution of the procurement;</p>
<p>16.32. whether the dynamic procurement system (DPS) / qualification system (QS) created by the Organisation will be applied to the procurement execution (in this case, the DPS / QS created by the Organisation in the System shall be chosen);</p>
<p>16.33. whether a preliminary contract will be concluded;</p>
<p>16.34. public comments;</p>
<p>16.35. non-public comments.</p>
<p>16.36. the date of entry of the data of the procurement lot;</p>
<p>16.37. the initiator of the procurement lot;</p>
<p>16.38. type of procurement lot (procurement of the classic sector, procurement of the utility sector, purchase of fuel, procurement of defence and security, internal transaction, other, if entered by the System Administrator);</p>
<p>16.39. type of energy resources of the procurement lot (for the type of fuel procurement);</p>
<p>16.40. name of the energy resources of the procurement lot (for the type of fuel procurement);</p>
<p>16.41. CPV number of the procurement lot;</p>
<p>16.42. additional CPV numbers of the procurement lot;</p>
<p>16.43. the quantity procured under the procurement lot;</p>
<p>16.44. measurement units of the procurement lot;</p>
<p>16.45. planned value of the procurement lot;</p>
<p>16.46. planned duration of the procurement lot contract (in days, months or a specific date);</p>
<p>16.47. an indication of whether the procurement lot is classified as social procurement;</p>
<p>16.48. an indication of whether the procurement lot will be the subject to environmental requirements;</p>
<p>16.49. indication of whether the procurement lot is financed from the EU funds;</p>
<p>16.50. indication of whether the procurement lot can be financed from the EU funds;</p>
<p>16.51. source of financing of the procurement lot (when not financed from the EU funds);</p>
<p>16.52. indication of whether the energy efficiency requirements apply to the procurement lot;</p>
<p>16.53. indication of whether the procurement lot is the subject to energy efficiency and environmental requirements for the road vehicle;</p>
<p>16.54. public comments on the procurement lot;</p>
<p>16.55. non-public comments on the procurement lot.</p>
<p>17. The PPO system administrator must be able to:</p>
<p>17.1. Determine which data must be entered / specified;</p>
<p>17.2. &nbsp;Change settings by deleting / adding new required data.</p>
<p>18. Supervisory Agencies must be able to review all data in the PE procurement plan (s).</p>
</td>
</tr>
<tr>
<td width="74">
<p>&nbsp;</p>
</td>
<td width="118">
<p>Recommendation data</p>
</td>
<td width="111">
<p>&nbsp;</p>
</td>
<td width="384">
<p>19. SAULĖ IS must collect the data necessary for the submission of recommendations (if necessary, the list of fields specified during the detailed analysis and design phase can be changed):</p>
<p>19.1. CPV numbers and references to individual directories of all individual goods, services, works in CPPO directories;</p>
<p>19.2. goods, services, works of social enterprises;</p>
<p>19.3. CPV numbers of goods, services, works according to which environmental requirements, energy efficiency requirements, energy efficiency and environmental requirements for road vehicles are applied and the technical specifications of these procurement objects established by legal acts.</p>
<p>20. After the procurement is included in the procurement plan, the PE must provide implementation recommendations:</p>
<p>20.1. make a procurement through the CPO (the CPO directories related to the procurement object and the goods, services, works contained therein must be indicated);</p>
<p>20.2. make a procurement using a DPS / QS created by yourself or another PE;</p>
<p>20.3. carry out a social procurement (the directories of enterprises assigned to social enterprises and the goods, services, works contained therein related to the object of procurement shall be indicated);</p>
<p>20.4. carry out a procurement in application of energy environmental requirements (a reference to the technical specifications of energy efficiency established in legal acts for the procurement object shall be provided);</p>
<p>20.5. carry out a procurement by applying energy efficiency (a reference to the technical specifications of energy efficiency established in legal acts for the object of procurement shall be provided);</p>
<p>20.6. carry out a procurement by applying energy efficiency and environmental requirements to a road vehicle (a reference to the technical specifications of the road vehicle established in legal acts for the object of procurement shall be provided);</p>
<p>20.7. available procurement execution methods;</p>
<p>20.8. indicate the cases in which the procurement may be excluded from the procurement group.</p>
</td>
</tr>
<tr>
<td width="74">
<p>T7</p>
</td>
<td width="118">
<p>Group the procurements</p>
</td>
<td width="111">
<p>SAULĖ IS</p>
</td>
<td width="384">
<p>21. SAULĖ IS shall assign each procurement / procurement lot according to the CPV number and / or PE type and / or procurement type and / or project number of the procurement / procurement lot to the relevant procurement group in accordance with the requirements of legal acts:</p>
<p>21.1. For procurement of services and goods: SAULĖ IS automatically groups the entered procurements according to the first three digits of the CPV numbers assigned to the services and goods;</p>
<p>21.2. For work contracts: SAULĖ IS automatically groups work contracts according to the type of works and / or the characteristic, when the works, which together as a result of construction and / or engineering activities as a whole, independently perform one economic or technical function (for example, associated with a single structure project);</p>
<p>21.3. When procurements are assigned to the same project: SAULĖ IS must automatically group all procurements assigned to the same project according to the project number.</p>
<p>22. Works belonging to the same class of activity specified in Annex 1 of the LPP (procurement in accordance with the provisions of the LPP or LD) or Annex 1 of the LP (procurement in accordance with the provisions of the LP ) shall be considered identical or similar).</p>
<p>23. The value of procurement of works regulated by the LD shall be calculated without considering the values of similar works procured under other procurement procedures.</p>
</td>
</tr>
<tr>
<td width="74">
<p>T8</p>
</td>
<td width="118">
<p>Change grouping</p>
</td>
<td width="111">
<p>PE</p>
</td>
<td width="384">
<p>24. It must be possible to manually change the grouping performed by SAULĖ IS automatically.</p>
<p>25. When manually changing the grouping performed by SAULĖ IS automatically, SAULĖ IS must ask the PE to indicate the reason for the change.</p>
</td>
</tr>
<tr>
<td width="74">
<p>T9</p>
</td>
<td width="118">
<p>Provide recommendation of proposed procurement methods</p>
</td>
<td width="111">
<p>SAULĖ IS</p>
</td>
<td width="384">
<p>26. SAULĖ IS, in case of procurement of services and goods, grouping the procurements according to the CPV number, must summarize their actual and planned values and provide recommendations on selection of appropriate procurement method according to LPP, LP, KT, LC, LD, Calculation of estimated procurement methodological requirements.</p>
<p>27. The actual value of the procurement group is calculated by adding the actual value of the planned procurements / procurement lots that are not performed with the actual value of the procurements / procurement lots that have been executed.</p>
<p>28. SAULĖ IS, in the case of procurement of works, by grouping procurements by type of works and / or by characteristic, when the works, which together as a result of construction and / or engineering activities as a whole, independently perform one economic or technical function (for example, are linked to a single building project), summarizes their actual and planned values and makes recommendations on selection of a proper procurement method.</p>
<p>29. SAULĖ IS must have an option to subscribe to / edit the described procurement methods described in the LPP, LP, KT, LC or LD.</p>
</td>
</tr>
<tr>
<td width="74">
<p>T10</p>
</td>
<td width="118">
<p>Approve / change the proposed procurement methods</p>
</td>
<td width="111">
<p>PE</p>
</td>
<td width="384">
<p>30. After studying of SAULĖ IS recommendations, the PE approves / changes the proposed procurement methods.</p>
<p>31. The PE may identify procurement methods that cannot be initiated until SAULĖ IS obtains PPO consent under the conditions set out in the Procurement Procedures Subsystem.</p>
</td>
</tr>
<tr>
<td width="74">
<p>T11</p>
</td>
<td width="118">
<p>Form a procurement plan</p>
</td>
<td width="111">
<p>SAULĖ IS</p>
</td>
<td width="384">
<p>32. From the procurement data entered to SAULĖ IS, a document (list form) is formed for the approval of the procurement plan.</p>
<p>33. The procurement plan is displayed in the form of a list.</p>
<p>34. If the procurement consists of lots, then the formed procurement plan must reflect their relationship (PE must show that they are parts of the respective procurement).</p>
<p>35. In the Procurement Plan window, one can perform searches for each procurement plan data.</p>
</td>
</tr>
<tr>
<td width="74">
<p>&nbsp;</p>
</td>
<td width="118">
<p>Procurement plan</p>
</td>
<td width="111">
<p>SAULĖ IS</p>
</td>
<td width="384">
<p>36. SAULĖ IS must save the procurement plan data.</p>
<p>37. SAULĖ IS must ensure control of public procurement plan versions.</p>
</td>
</tr>
<tr>
<td width="74">
<p>T12</p>
</td>
<td width="118">
<p>Inform on the procurements under verification</p>
</td>
<td width="111">
<p>SAULĖ IS</p>
</td>
<td width="384">
<p>38. If, when developing the procurement plan, it is determined that in step T7 the PE has selected such procurement methods where procurement cannot be initiated without the PPO consent:</p>
<p>38.1. then SAULĖ IS sends a notification to the PE that the PE will need to contact the PPO and obtain PPO consent before initiation of the procurement;</p>
<p>38.2. In the procurement plan, the relevant procurement must be marked &ldquo;Procurement may not be initiated without PPO consent&rdquo;. Clicking on this label should open a notification form in the PPO, which can provide:</p>
<p>38.2.1. Free text entry field;</p>
<p>38.2.2. Automatically uploaded link to the planned procurement information; &nbsp;</p>
<p>38.2.3. Option to attach the documents.</p>
<p>39. Upon receipt of the notification that the consent of the PPO is required before the procurement can start, the PE may review the information of the relevant procurement and change the selected procurement method.</p>
</td>
</tr>
<tr>
<td width="74">
<p>&nbsp;</p>
</td>
<td width="118">
<p>Information on verified procurements</p>
</td>
<td width="111">
<p>SAULĖ IS</p>
</td>
<td width="384">
<p>40. For the purposes of prevention and control, information and data on procurement notices sent / received by SAULĖ IS must be collected in SAULĖ IS, which cannot be started without the consent of the PPO.</p>
<p>41. The following notification data must be saved:</p>
<p>41.1. Details of the sender;</p>
<p>41.2. Details of the recipient;</p>
<p>41.3. Date and time when the notification was sent;</p>
<p>41.4. Date and time the notification was read;</p>
<p>41.5. Reference to the procurement for which the notification was sent.</p>
</td>
</tr>
<tr>
<td width="74">
<p>T13</p>
</td>
<td width="118">
<p>Approve the procurement plan</p>
</td>
<td width="111">
<p>PV</p>
</td>
<td width="384">
<p>42. The procurement plan is approved by electronic signature of the PE or authorized person.</p>
<p>43. SAULĖ IS can approve the entire procurement plan or select individual procurements specified in the procurement plan for approval.</p>
<p>44. When the plan is revised, a new version of the plan is formed. SAULĖ IS stores all published versions of the plan.</p>
<p>45. When approving the procurement plan, a procurement plan container or document is formed, which contains all the information about the procurements in the procurement plan, as well as information related to the procurement plan itself (for example, date of approval, name, surname of the approver). Once approved, such a procurement plan must no longer be modified and stored in the system.</p>
<p>46. The approved procurement plan should be:</p>
<p>46.1. exported to selected format (* .xlsx, * docx, * .pdf);</p>
<p>46.2. reviewed;</p>
<p>46.3. perform a search based on each procurement plan data;</p>
<p>46.4. printed.</p>
</td>
</tr>
<tr>
<td width="74">
<p>T14</p>
</td>
<td width="118">
<p>Set the information to be displayed in the summary table</p>
</td>
<td width="111">
<p>&nbsp;</p>
</td>
<td width="384">
<p>47. It must be administered which data of planned procurements have or can be disclosed (the set of data to be disclosed below is indicative and will have to be agreed with the PPO).</p>
<p>48. Before compiling the summary table, the PE may determine whether the estimated procurement volumes (values) will be exceeded.</p>
<p>49. According to the LPP, KT, LC or LP the summary table must contain the information about:</p>
<p>49.1. international, simplified (except for low value) procurements;</p>
<p>49.2. procurements made through the CPO (except in the case of low value procurements);</p>
<p>49.3. simplified procurement in accordance with Article 25 (3) and (4) of the LPP;</p>
<p>49.4. local transactions.</p>
<p>50. According to the LD the summary table must contain the information about:</p>
<p>50.1. international, simplified (except for low value) procurements not related to confidential information.</p>
<p>* It will be mandatory to publish low value procurements in the summary table from 01/01/2023.</p>
<p>51. <em>When purchases are made under the </em>LPP, KT, LC or LP, in SAULĖ IS <em>it is automatically marked that th</em><em>e following</em><em> information will be displayed in the summary table</em>:</p>
<p><em>51.1. </em><em>procurement method;</em></p>
<p><em>51.2. </em><em>PE name, address and contact details;</em></p>
<p><em>51.3. </em><em>Name of the procurement object;</em></p>
<p><em>51.4. </em><em>Type of procurement (goods, services, works);</em></p>
<p><em>51.5. </em><em>CPV number;</em></p>
<p><em>51.6. </em><em>Volume of the intended procurement (procurement value or quantity (volume), or both value and quantity (volume). If the PE has indicated that the procurement value will be indicated, it is provided without VAT);</em></p>
<p><em>51.7. </em><em>Duration of supply of goods, provision of services or performance of works with extensions;</em></p>
<p><em>51.8. </em><em>Expected start of procurement procedures;</em></p>
<p><em>51.9. </em><em>Will an internal transaction be concluded;</em></p>
<p><em>51.10. </em><em>Will it be acquired from or through a CPO?</em></p>
<p>51.11. <em>Will a reserved procurement be made</em><em>.</em></p>
<p>52. <em>When procurements are made under the L</em><em>G,</em> in SAULĖ IS <em>it is automatically marked that th</em><em>e following</em><em> information will be displayed in the summary table</em><em>:</em></p>
<p>52.1. <em>Procurement method</em>;</p>
<p>52.2. indication: one or more procurements from one procurement line will be made;</p>
<p>52.3. <em>PE name, address and contact details</em>;</p>
<p>52.4. <em>Name of the procurement object</em>;</p>
<p>52.5. <em>Type of procurement (goods, services, works</em>);</p>
<p>52.6. <em>CPV number</em>;</p>
<p>52.7. Project code if the procurement is referred to the project;</p>
<p>52.8. <em>Volume of the intended procurement (procurement value or quantity (volume), or both value and quantity (volume). If the PE has indicated that the procurement value will be indicated, it is provided without VAT</em>);</p>
<p>52.9. <em>Duration of supply of goods, provision of services or performance of works with extensions</em>;</p>
<p>52.10. <em>Expected start of procurement procedures</em>;</p>
<p>52.11. <em>Will it be acquired from or through a CPO</em>,</p>
<p>52.12. <em>Will a reserved procurement be made</em>.</p>
</td>
</tr>
<tr>
<td width="74">
<p>T15</p>
</td>
<td width="118">
<p>Include the procurement into the plan of the authorised PE</p>
</td>
<td width="111">
<p>SAULĖ IS</p>
</td>
<td width="384">
<p>53. If the approved procurement plan provides for procurement through an authorized PE, SAULĖ IS shall include the planned procurement in the authorized PE plan.</p>
<p>54. When the authorizing PE in its procurement plan marks which procurements it requests to be included in the Authorized PE&rsquo;s procurement plan, additional lines in the Procurement Plan appear in the Authorized PE&rsquo;s procurement plan. Only with the consent of the Authorized PE, procurement of the Authorizing PE will be included in the Procurement Plan of the Authorized PE.</p>
<p>55. Procurement that is assigned to an Authorized PE will be additionally included by SAULĖ IS in the Authorized PE&rsquo;s procurement plan, indicating that it is a Procurement by Authorisation.</p>
</td>
</tr>
<tr>
<td width="74">
<p>&nbsp;</p>
</td>
<td width="118">
<p>Authorized PE Procurement Plan</p>
</td>
<td width="111">
<p>SAULĖ IS</p>
</td>
<td width="384">
<p>56. SAULĖ IS must save the data of the authorised procurement plan.</p>
<p>57. SAULĖ IS must ensure the control of the procurement plan versions.</p>
</td>
</tr>
<tr>
<td width="74">
<p>T16</p>
</td>
<td width="118">
<p>Inform the authorized PE</p>
</td>
<td width="111">
<p>SAULĖ IS</p>
</td>
<td width="384">
<p>58. Message is sent to the authorized PE that SAULĖ IS has additionally included in the procurement plan of the authorized PE, authorizing PE procurements based on the information and data provided by the authorizing PE.</p>
</td>
</tr>
<tr>
<td width="74">
<p>T17</p>
</td>
<td width="118">
<p>Form a summary table</p>
</td>
<td width="111">
<p>SAULĖ IS</p>
</td>
<td width="384">
<p>59. SAULĖ IS must have an option to form summary tables based on the data of the approved procurement plan according to PE parameters specified in step T14.</p>
<p>60. The summary table must have options to:</p>
<p>60.1. Export to the selected format (*.xlsx, *.docx, *.pdf or equivalent);</p>
<p>60.2. review;</p>
<p>60.3. perform a search based on each procurement plan data;</p>
<p>60.4. print.</p>
</td>
</tr>
<tr>
<td width="74">
<p>&nbsp;</p>
</td>
<td width="118">
<p>Summary table</p>
</td>
<td width="111">
<p>SAULĖ IS</p>
</td>
<td width="384">
<p>61. SAULĖ IS must save summary table data.</p>
<p>62. SAULĖ IS must ensure the control of the summary table versions.</p>
</td>
</tr>
<tr>
<td width="74">
<p>T18</p>
</td>
<td width="118">
<p>Publish a summary table</p>
</td>
<td width="111">
<p>PE</p>
</td>
<td width="384">
<p>63. The summary table, except for information on low value procurement*, must be made public no ex-post than on 15 March of the current calendar year.</p>
<p>64. Summary tables published in previous years cannot be deleted from the System.</p>
<p>65. If before 15 March the PE intends to carry out procurements but has not approved the procurement plan planned for the current calendar year, it must approve the plan for known procurements before the start of these procurements and which it intends to start by 15 March, and publish them in the summary table no ex-post than 15 March. The PE will be required to disclose the remaining information on known future procurements.</p>
<p>66. In cases when the entity becomes a PE during the current budget year (after 15 March), it must published a summary table for the remaining period of the budget year no ex-post than in 5 business days after the approval of the planned procurement plan.</p>
<p>67. If the summary table is not published by 15 March, then new procurements should not be allowed to start and a delay message should be displayed each time (until the summary table is published) when you log in to your PE account.</p>
<p>* It will be mandatory to publish low value procurements in the summary table from 01/01/2023.</p>
</td>
</tr>
<tr>
<td width="74">
<p>E4</p>
</td>
<td width="118">
<p>Required change of the Procurement Plan</p>
</td>
<td width="111">
<p>PE</p>
</td>
<td width="384">
<p>68. After updating the procurement plan, its new version must be created in the system.</p>
<p>69. Upon revision of the procurement plans planned to be performed in the current budget year, the Summary Table shall be automatically formed and published.</p>
<p>70. Information on a specific procurement is updated in the procurement plan and the summary table is updated and published before the start of this procurement. This means that once the procurement has started, the information in the procurement plan and the summary table based on it cannot be corrected.</p>
<p>71. If the PE decides not to execute a specific procurement or internal transaction, such procurement or internal transaction is not deleted from the summary table. In this case, the PE notes in the summary table that the procurement or internal transaction will not be implemented.</p>
<p>72. It must be administered which data of the procurement plan may be changed after the approval of the procurement plan.</p>
<p>73. Technical or grammatical errors must be allowed to be corrected in all cases, but the PE must ensure that these changes do not alter the content of the information provided.</p>
<p>74. When correcting the data of the procurement plan, the corrected information must be displayed in track changes (visible difference from the previous version). The track changes must be visible only to the specialists of the PPO, IA, the Supervisory Agency and specialists of the procuring PE.</p>
<p>75. Approved procurement plans and / or their data cannot be removed from the System.</p>
</td>
</tr>
<tr>
<td width="74">
<p>E5</p>
</td>
<td width="118">
<p>The year is over</p>
</td>
<td width="111">
<p>-</p>
</td>
<td width="384">
<p>76. Changes to the procurement plan are not available when the year is over.</p>
</td>
</tr>
<tr>
<td width="74">
<p>E6</p>
</td>
<td width="118">
<p>Process completion</p>
</td>
<td width="111">
<p>-</p>
</td>
<td width="384">
<p>-</p>
</td>
</tr>
<tr>
<td width="74">
<p>E7</p>
</td>
<td width="118">
<p>Time to publish summary tables</p>
</td>
<td width="111">
<p>-</p>
</td>
<td width="384">
<p>77. As the deadline for publishing the summary tables approaches (in 14 days before 15 March), the sending of the message is initiated.</p>
<p>78. The time for sending messages is set by the PPO System Administrator.</p>
</td>
</tr>
<tr>
<td width="74">
<p>T19</p>
</td>
<td width="118">
<p>Remind about the deadline for publishing the summary tables</p>
</td>
<td width="111">
<p>SAULĖ IS</p>
</td>
<td width="384">
<p>79. SAULĖ IS must send an automatic message to the PE, if the System Administrator has not made public the summary table by the start of the deadline set by the System Administrator (for example, in 3 days before 15 March).</p>
</td>
</tr>
<tr>
<td width="74">
<p>E8</p>
</td>
<td width="118">
<p>Process completion</p>
</td>
<td width="111">
<p>&nbsp;</p>
</td>
<td width="384">
<p>-</p>
</td>
</tr>
<tr>
<td width="74">
<p>E9</p>
</td>
<td width="118">
<p>In case of failure to publish summary tables before the set term</p>
</td>
<td width="111">
<p>-</p>
</td>
<td width="384">
<p>80. If the summary table has not been published by 15 March, the sending of the message is initiated.</p>
<p>81. The time for sending messages is set by the PPO System Administrator.</p>
</td>
</tr>
<tr>
<td width="74">
<p>T20</p>
</td>
<td width="118">
<p>Remind about the missed term</p>
</td>
<td width="111">
<p>SAULĖ IS</p>
</td>
<td width="384">
<p>82. SAULĖ IS must send an automatic message to the PE, if on 15 March the summary table has not yet been published.</p>
<p>83. The time for sending messages and recipients shall be set by the PPO System Administrator:</p>
<p>83.1. in 14 days before the end of the term, SAULĖ IS sends a reminder to the responsible specialist of the PE;</p>
<p>83.2. in 5 days before the end of the term, SAULĖ IS sends a reminder to the PE manager;</p>
<p>83.3. on 15 March it sends a message to the PE manager and to the Risk subsystem;</p>
<p>83.4. If the summary table has not been published by 15 March, then the actions specified in the requirement 156 of step T18 shall be taken and additionally, at intervals set by the System Administrator (for example, every 5 days), messages shall be sent to the PE and to the Risk Subsystem until the summary table is published.</p>
</td>
</tr>
<tr>
<td width="74">
<p>E10</p>
</td>
<td width="118">
<p>Process completion</p>
</td>
<td width="111">
<p>-</p>
</td>
<td width="384">
<p>-</p>
</td>
</tr>
<tr>
<td width="74">
<p>E11</p>
</td>
<td width="118">
<p>On quarterly basis</p>
</td>
<td width="111">
<p>-</p>
</td>
<td width="384">
<p>84. Messages shall be sent periodically on a quarterly basis.</p>
<p>85. The time for sending messages is set by the PPO System Administrator.</p>
</td>
</tr>
<tr>
<td width="74">
<p>T21</p>
</td>
<td width="118">
<p>Remind of the obligation to update procurement plans</p>
</td>
<td width="111">
<p>SAULĖ IS</p>
</td>
<td width="384">
<p>86. SAULĖ IS must send messages reminding of the obligation to regularly assess the need for changes in the procurement plans and update the procurement plans if necessary. &nbsp;</p>
</td>
</tr>
<tr>
<td width="74">
<p>E12</p>
</td>
<td width="118">
<p>Process completion</p>
</td>
<td width="111">
<p>-</p>
</td>
<td width="384">
<p>-</p>
</td>
</tr>
</tbody>
</table>

<h4>1.1.1.1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Other requirements for the Procurement Planning Subsystem</h4>
<ol>
<li>There must be an option from the procurement plan line to initiate:
<ul>
<li>formation and publication of a prior procurement notice;</li>
<li>publication of a market consultation;</li>
</ul>
</li>
<li>The procurement plan must have an option to change the procurement status automatically:
<ul>
<li>When one procurement is made from one procurement line:
<ul>
<li>Until the procurement procedures have started, the procurement plan shows the status &ldquo;Planned&rdquo;;</li>
<li>Once the procurement procedures have started, the status of the plan must be changed from &ldquo;Planned&rdquo; to &ldquo;In progress&rdquo;.</li>
<li>Upon completion of procurement procedures (conclusion of contracts, termination of procedures, rejection of all tenders, failure to receive of tenders at all, when all suppliers refuse to conclude the contract, etc.), the procurement plan must change the status from &ldquo;Planned&rdquo; or &ldquo;In progress&rdquo; to &ldquo;Completed&rdquo;.</li>
<li>After starting the assessment of the received tenders, SAULĖ IS must send a message to the specific line of the procurement plan (line of the procurement plan &ldquo;Planned contract value&rdquo;), if the price of the received tender exceeds the planned value or is 30% lower than planned value.</li>
<li>After the PE concludes a contract with the Supplier, the procurement plan must change the status of the procurement from &ldquo;Planned&rdquo; or &ldquo;In progress&rdquo; to &ldquo;Completed&rdquo; and automatically record the actual value of the contract concluded after the completed procurement.</li>
</ul>
</li>
<li>When more than one procurement is made from one procurement line:
<ul>
<li>Until any procurement procedures from this type of procurement line have been initiated, the status &ldquo;More than one procurement planned&rdquo; is displayed in the procurement plan;</li>
<li>Once at least one procurement procedure has been initiated, the status of the procurement plan must change from &ldquo;More than one procurement planned&rdquo; to &ldquo;At least 1 procurement in progress&rdquo;;</li>
<li>Upon completion of at least one procurement procedure, the status in the procurement plan must be changed to &ldquo;Partially Redeemed&rdquo;;</li>
<li>If one procurement procedure has been completed and the other has started, then statuses of both procurements must be displayed next to this procurement plan line, i.e. &ldquo;Partially redeemed&rdquo;, &ldquo;At least 1 procurement in progress&rdquo;;</li>
<li>When all procurements from this procurement line have been completed, the status changes to &ldquo;Completed&rdquo;.</li>
</ul>
</li>
<li>If a contract / preliminary contract is concluded at the end of the procurement procedures, then the sequence of actions in the System shall be as described in Requirement 177.2, and if the procurement is not successful (no contract / preliminary contract is concluded) and more than one procurement is made from one procurement line, then in the plan, for the first procurement from the procurement line, the status must be changed to &ldquo;Planned&rdquo;, and for the second and subsequent ones - to &ldquo;Partially redeemed&rdquo;.</li>
<li>At the end of unsuccessful procurement (no contract / preliminary contract is concluded), the procurement on that line can be re-initiated without changing the procurement value, as the planned procurement value remains the same and at the end of the unsuccessful procurement the actual procurement value is not fixed.</li>
</ul>
</li>
</ol>
<p>&nbsp;</p>
<h3><a name="_Toc50101519"></a>1.1.2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Requirements for the Procurement Procedure Subsystem</h3>
<h4>1.1.2.1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; General requirements for the Procurement Procedure Subsystem</h4>
<ol start="3">
<li>The object that combines all the data on a specific procurement - the procurement project must be implemented (the basic diagram of the procurement project data is presented in Section 8.2.6 Requirements for the data model).</li>
<li>The procurement project must be developed from the procurement plan. This requirement does not apply to concessions.</li>
<li>It must be possible to create a procurement project for a concession without including it in the procurement plan.</li>
<li>If the desired procurement is not included in the procurement plan, it must be ensured that the PE first includes it in the procurement plan. This requirement does not apply to concessions.</li>
<li>It must be permitted to create several procurement projects from one line of the procurement plan and to link the procurement project with several lines of the procurement plan.</li>
<li>When creating a procurement project, known fields must be filled in automatically (for example, according to the data of the procurement plan, the name of the procurement, planned value, purchase method, etc. are filled in automatically).</li>
<li>When a procurement project is created based on a previous failed procurement (such a justification for the choice of the procurement method is selected), the developed procurement project shall be linked with the failed procurement. When linking a procurement project to a failed procurement:
<ul>
<li>The conditions of a failed procurement must be automatically transferred to the procurement project under development.</li>
<li>Special conditions must be changed according to the template selected by the PE.</li>
<li>Changes made to the conditions transferred by the PE during the changes must be marked and clearly visible when reviewing the procurement conditions.</li>
</ul>
</li>
<li>It must be possible to copy the data of the previous procurement (part of the procurement, procurement terms and conditions, requirements) when creating a new procurement project (without justification that it is being created on the basis of a previous procurement). In this case, the procurements may not be linked.</li>
<li>The procurement number must be assigned to the procurement project automatically (according to the numbering template agreed during the detailed analysis phase). The procurement number assigned to the procurement project is assigned to all notices, reports, contracts related to the procurement project, i.e. the procurement project is given one number and the same number applies to all data objects of that project from planning to contract execution.</li>
<li>When creating a project for which a justification is required according to the administrator&rsquo;s settings, the PE must select one of the justifications (must be selected from the list of possible justifications set by the administrator).</li>
<li>The Entities involved in the procurement shall be allowed to change the automatically transferred procurement project data in the procurement project. The PPO system administrator must be able to specify which data transferred from the procurement plan may be changed. The CPV code cannot be changed - it can only be detailed (i.e. the first three digits of the CPV code must not change (a lower level classification entry may be selected, but it must not be allowed to select an entry from another branch of the classification)). The history of changes made must be saved. Specialists of the procuring PE and PPO must see the changes made from the procurement plan.</li>
<li>Corrected data shall not be transferred to the procurement plan. Additional data of the procurement process must be transferred to the procurement plan (for example, procurement status, actual procurement value, etc. - the list of fields must be agreed during the detailed analysis phase).</li>
<li>After creating the procurement project, a procurement calendar must be created, in which, when filling in the procurement documents, important dates for the procurement must be indicated (for example, deadline for submission of tenders, recommended deadline for submission of inquiries, deadline for submission of claims, etc.). The final list of dates visible in the calendar must be agreed during the detailed analysis phase.</li>
<li>During the procurement, the persons performing the procurement must be allowed to upload various documents related to the procurement (not only those specified in the process) and to revise the already uploaded documents.</li>
<li>The actions performed by the PE must be recorded during the audit and visible to the suppliers, the PE, the Supervisory Agencies. When appointing the persons responsible for the procurement for the procurement project, it must be allowed to choose from SAULĖ IS registered users belonging to the respective authority.</li>
<li>It must be possible to appoint other persons (outside the institution). In this case, the user must enter the ID of the system user to be assigned. Once the system has found a matching system user, you should be asked to confirm that it is indeed the person you are looking for.</li>
<li>It must be possible for the PE to appoint a Procurement Specialist, Initiator, Organiser, Members of the Commission (specifying the Chairman of the Commission), Experts, Supervisors and the person responsible for the performance of the Contract. The final list of specialists must be agreed upon during the detailed analysis phase.</li>
<li>It must be possible to choose whether to appoint the Commission or the Organiser. The functions of the Commission and the Organiser in the procurement coincide.</li>
<li>It must be possible to change the list of Entities/persons involved in the procurement as necessary throughout the procurement before the conclusion of the contract with the supplier (or termination of the procurement).</li>
<li>When appointing or changing responsible persons, it must be possible to provide (attach) the basis for the appointment of responsible persons.</li>
<li>If the PE provides for the conclusion of an oral contract, the PE must be able to indicate in the procurement contract that the contract will be awarded orally and to state the reasons for such a decision.</li>
<li>The PE must be able to publish market consultations both from the procurement project and not from a specific procurement.</li>
<li>If market consultations related to the procurement have been published, the PE must be able to link the consultations to the procurement project after creating the procurement project.</li>
<li>It must be possible to link several market consultations to the procurement and to link market consultations to several procurements.</li>
<li>It must be possible to publish the TS referred to the procurement project several times and to assign the consultations on the TS project to several procurement projects.</li>
<li>The PE must be able to set a deadline for the submission of applications or tenders, but the PE must not be allowed to set a deadline shorter than those provided for in laws.</li>
<li>Where the contract is awarded in lots, each lot must be allowed to set different time limits for the submission of tenders or requests to participate.</li>
<li>Suppliers must be given the opportunity to submit separate tenders or tenders for each lot in which they wish to participate, in accordance with the rules laid down in the procurement documents. Tenders or tenders for different lots of the contract may be submitted at different times.</li>
<li>Upon completion of the procurement (when the contract is signed or when the procurement is terminated):
<ul>
<li>Modifications to the procurement data must no longer be allowed;</li>
<li>Additional documents must be allowed to be uploaded before the deadline for archiving;</li>
<li>Claims must be allowed to be submitted and answered before the deadline for archiving.</li>
<li>The PPO system administrator must be able to configure the deadline for archiving. The default value is 4 years after the end of the procurement (when the contract is signed or when the procurement is terminated).</li>
<li>Upon expiry of the deadline for archiving, the procurement project must be archived - the procurement project must become inactive, no further actions must be allowed with it.</li>
</ul>
</li>
<li>The PPO system administrator must be able to configure procurement type value thresholds. Value thresholds must be configured by sector (classic sector, utilities, defence sector, fuel procurement, concessions), type of procurement object (procurement of works, procurement of goods, procurement of services, procurement of social and other special services, procurement of goods) when Annex 6 of the LLP applies)), type of procurement executor (central authority, non-central authority, national defence system PE). The values of the specified lists must be configured by the PPO system administrator.</li>
<li>The PPO system administrator must be able to configure the procurement method selection settings. It must be possible to determine which procurement methods can be selected depending on the sector and the type of procurement (by value).</li>
<li>The PPO system administrator must be able to configure the conditions for justifying the selection of the procurement method. It must be possible to determine which sectors and types of procurement (by value) may be the subject to specific justifications, for which sectors and types of procurement the selection of procurement method is not restricted (no justification required).</li>
<li>The PPO system administrator must be able to determine, according to the procurement sector, procurement method, type of procurement object and PE type, whether the use of appropriate tools (for example, market consultations, e-auctions, advance information notices (separately for each purpose of such publication) is allowed) and etc.). The final list of configurable tools must be agreed upon during the detailed analysis phase.</li>
<li>The PPO system administrator must be able to configure the minimum deadlines from the publication of the prior notice to the publication of the contract notice. Minimum deadlines provided:
<ul>
<li>International procurement&ndash; 35 calendar days;</li>
<li>Simplified procurement&ndash; 15 calendar days;</li>
<li>Low value procurement&ndash; 15 calendar days;</li>
<li>Defence sector procurement (all) &ndash; 52 calendar days.</li>
</ul>
</li>
<li>The PPO system administrator shall be able to configure the minimum deadlines for the submission of applications or tenders. Minimum deadlines for submission of applications or tenders must be configured according to the procurement parameters: procurement method, procurement type (by value), whether a prior information notice is published to shorten deadlines, whether urgency applies, whether procurement documents are published in SAULĖ IS, tender submission method.</li>
<li>In case of restricted procurement, non-central government PEs must be able to agree with the selected candidates on a shorter deadline for the submission of tenders. The anonymity of suppliers must be ensured during the agreement of the deadline. The agreed deadlines may not be shorter than:
<ul>
<li>International procurement &ndash; 10 calendar days;</li>
<li>Simplified procurement &ndash; 7 calendar days.</li>
</ul>
</li>
<li>The PPO system administrator must be able to edit the grounds for not informing suppliers about the procurement results. Expected grounds:
<ul>
<li>The tender was presented orally;</li>
<li>The procurement contract is concluded orally.</li>
</ul>
</li>
<li>The deferral period shall be set in the procurement documents by the PE, but may not be shorter than:
<ul>
<li>International procurement &ndash; 10 calendar days;</li>
<li>Simplified procurement &ndash; 5 business days;</li>
<li>Low value procurement &ndash; 0 business days;</li>
<li>Concession - 15&nbsp;calendar days.</li>
</ul>
</li>
<li>The PPO system administrator must be able to configure the planned deferral periods. When preparing procurement documents, SAULĖ IS must automatically offer the minimum delay period set by the PPO system administrator.</li>
<li>The PPO system administrator must be able to edit the grounds for non-application of the deferral period. Expected grounds:
<ul>
<li>the only interested tenderer is the one with whom the procurement contract is concluded and there are no interested candidates;</li>
<li>the procurement contract is concluded orally.</li>
</ul>
</li>
<li>When the PE chooses not to apply a deferral period, information on potentially risky procurements must be transmitted to the Risk Management Module.</li>
<li>The grounds for oral conclusion of the contract must be configured by the PPO system administrator. The grounds must be linked to the maximum amount of the contract to which they may apply. Where the actual procurement value exceeds the stated amount, the choice of the ground should not be allowed. Expected grounds:
<ul>
<li>the value of the simplified procurement contract is less than EUR 3 000 excluding VAT;</li>
<li>the value of the contract does not exceed EUR 10 000 excluding VAT and the simplified procurement is performed by diplomatic missions of the Republic of Lithuania in foreign countries, missions of the Republic of Lithuania to international organisations, consular posts and special missions, as well as other contracting authorities procuring goods, services or works abroad, for their units, military representatives or special attach&eacute;s abroad or for development cooperation and other projects abroad;</li>
<li>the value of the contract does not exceed EUR 10 000, excluding VAT, and the simplified procurement is made for the procurement of goods, services or works required for the organisation of critical international events.</li>
<li>In all cases where SAULĖ IS has deadlines for the performance of the activity, SAULĖ IS must remind the person responsible for the performance of the activity about the approaching deadline.</li>
</ul>
</li>
</ol>
<h4>1.1.2.2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Requirements for implementation of process &ldquo;PP1. Open tender procurement&rdquo; and functions</h4>
<ol start="45">
<li>The functionality of open procurement must be implemented. Below one can find a process diagram and requirements for the process implementation.</li>
</ol>
<p>&nbsp;</p>

![image](https://user-images.githubusercontent.com/61745726/92297388-7a317700-ef47-11ea-93d6-6c76b89b32d0.png)
Fig. 7.6. Diagram of the process “PP1. Open tender procurement” (part 1)

![image](https://user-images.githubusercontent.com/61745726/92297395-8584a280-ef47-11ea-8a79-fed2ad50d006.png)
Fig. 7.7. Diagram of the process “PP1. Open tender procurement” (part 2)

Table 7.2. Requirements for the implementation of the process “Open tender procurement” 
<table width="688">
<thead>
<tr>
<td width="73">
<p>Process No</p>
</td>
<td width="176">
<p>Process title</p>
</td>
<td width="107">
<p>Process participant</p>
</td>
<td width="332">
<p>Requirements for implementation</p>
</td>
</tr>
</thead>
<tbody>
<tr>
<td width="73">
<p>E1</p>
</td>
<td width="176">
<p>Process beginning</p>
</td>
<td width="107">
<p>-</p>
</td>
<td width="332">
<p>1. In the case of procurement in the classic or municipal sectors, the selection of an open tender must be allowed in all cases. In the defence sector, the selection of open tendering should only be allowed through simplified procurement.</p>
</td>
</tr>
<tr>
<td width="73">
<p>T1</p>
</td>
<td width="176">
<p>Create the procurement project</p>
</td>
<td width="107">
<p>Procurement Specialist</p>
</td>
<td width="332">
<p>2. The procurement specialist (or other PE employee who has been granted such a right) in SAULĖ IS must be able to create the required procurement project from the procurement plan.</p>
</td>
</tr>
<tr>
<td width="73">
<p>T2</p>
</td>
<td width="176">
<p>Appoint persons responsible for the procurement implementation</p>
</td>
<td width="107">
<p>Procurement Specialist</p>
</td>
<td width="332">
<p>3. The procurement specialist (or other PE employee who has been granted such a right) in SAULĖ IS must be able to appoint persons responsible for the procurement.</p>
</td>
</tr>
<tr>
<td width="73">
<p>BP1</p>
</td>
<td width="176">
<p>Prepare procurement documents</p>
</td>
<td width="107">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="332">
<p>4. Using SAULĖ IS, the PE must be able to prepare the procurement documents actual for the procurement. For more details see the Process requirements &ldquo;BP1. Prepare the procurement documents&rdquo;.</p>
<p><strong>Note: all procurement documents are covered except for notices - these are detailed separately</strong>.</p>
</td>
</tr>
<tr>
<td width="73">
<p>BP2</p>
</td>
<td width="176">
<p>Publish a preliminary notice (information)</p>
</td>
<td width="107">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="332">
<p>5. If necessary, the PE must be able to publish a prior information notice in SAULĖ IS. For more details see the Requirements for the implementation of the process &ldquo;BP2. Publish a preliminary notice (information)&rdquo;.</p>
</td>
</tr>
<tr>
<td width="73">
<p>BP3</p>
</td>
<td width="176">
<p>Publish a preliminary notice (terms)</p>
</td>
<td width="107">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="332">
<p>6. If necessary, the PE must be able to publish a prior information notice in SAULĖ IS, stating that the purpose of this notice is to reduce the term for the submission of tenders. For more details see the Requirements for the implementation of the process &ldquo;BP3. Publish a preliminary notice (terms)&rdquo;.</p>
</td>
</tr>
<tr>
<td width="73">
<p>E2</p>
</td>
<td width="176">
<p>Minimum term between preliminary notice and contract notice</p>
</td>
<td width="107">
<p>-</p>
</td>
<td width="332">
<p>7. SAULĖ IS must ensure that in order to take advantage of the reduction of terms, a minimum period is elapsed between the prior notice and the contract notice.</p>
<p>8. The PE should not be prohibited from publishing a contract notice before this deadline, but in this case the reduced procedural terms should not apply (in this case the system must warn of the consequences before approving the action and treat this notice in the same way as a preliminary notice&nbsp; (information)).</p>
</td>
</tr>
<tr>
<td width="73">
<p>T3</p>
</td>
<td width="176">
<p>Linked market consultations</p>
</td>
<td width="107">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="332">
<p>9. If market consultations related to the procurement have been published, the PE must be able to link them to the procurement project.</p>
</td>
</tr>
<tr>
<td width="73">
<p>BP6</p>
</td>
<td width="176">
<p>Publish market consultations</p>
</td>
<td width="107">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="332">
<p>10. Where appropriate, the PE should be able to issue a request to get a consultation from independent experts, institutions, market participants or the public. For more details see the Requirements for the implementation of the process &ldquo;BP6. Publish market consultations&rdquo;.</p>
</td>
</tr>
<tr>
<td width="73">
<p>BP7</p>
</td>
<td width="176">
<p>Publish draft TS</p>
</td>
<td width="107">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="332">
<p>11. Where appropriate, the PE must be able to publish the draft technical specification in advance. For more details see the Requirements for the implementation of the process &ldquo;BP7. Publish draft TS&rdquo;.</p>
</td>
</tr>
<tr>
<td width="73">
<p>BP8</p>
</td>
<td width="176">
<p>Publish a procurement notice (project tender)</p>
</td>
<td width="107">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="332">
<p>12. The PE must be able to publish a procurement notice. For more details see the Requirements for the implementation of the process &ldquo;BP8. Publish a procurement notice (project tender)&rdquo;.</p>
<p>13. Publication of the notice in SAULĖ IS (in the case of international procurement - publication TED) must be considered as the beginning of procurement procedures.</p>
</td>
</tr>
<tr>
<td width="73">
<p>SP1</p>
</td>
<td width="176">
<p>Determine successful tenderers</p>
</td>
<td width="107">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="332">
<p>14. The sub-process must cover activities from the assessment of tenders to the publication of results.</p>
<p>15. It must be possible to carry out the activities of this sub-process for the whole procurement (if the procurement is not divided into lots), synchronously (activities related to each lot of the procurement are performed simultaneously) or asynchronously (each lot of the procurement is performed at its own pace).</p>
</td>
</tr>
<tr>
<td width="73">
<p>E3</p>
</td>
<td width="176">
<p>Flow beginning</p>
</td>
<td width="107">
<p>-</p>
</td>
<td width="332">
<p>-</p>
</td>
</tr>
<tr>
<td width="73">
<p>BP10</p>
</td>
<td width="176">
<p>Get tenders of suppliers</p>
</td>
<td width="107">
<p>SAULĖ IS</p>
</td>
<td width="332">
<p>16. The option to receive tenders of suppliers through SAULĖ IS must be available. For more details see the Requirements for the implementation of the process &ldquo;BP10. Get tenders of suppliers&rdquo;.</p>
<p>17. Any interested supplier registered in the system must be able to submit a tender. The number of participants cannot be limited.</p>
</td>
</tr>
<tr>
<td width="73">
<p>E4</p>
</td>
<td width="176">
<p>Flow end</p>
</td>
<td width="107">
<p>-</p>
</td>
<td width="332">
<p>-</p>
</td>
</tr>
<tr>
<td width="73">
<p>BP11</p>
</td>
<td width="176">
<p>Assess tenders</p>
</td>
<td width="107">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="332">
<p>18. The PE must be able to assess the tenders received through SAULĖ IS. For more details see the Requirements for the implementation of the process &ldquo;BP11. Assess tenders&rdquo;.</p>
</td>
</tr>
<tr>
<td width="73">
<p>E5</p>
</td>
<td width="176">
<p>Flow end</p>
</td>
<td width="107">
<p>-</p>
</td>
<td width="332">
<p>-</p>
</td>
</tr>
<tr>
<td width="73">
<p>E6</p>
</td>
<td width="176">
<p>Make a procurement by way of published negotiations (without a notice)</p>
</td>
<td width="107">
<p>-</p>
</td>
<td width="332">
<p>19. If none of the tenders received is acceptable and the PE has decided to proceed with the procurement by way of published negotiations, the procurement process must be initiated PP3a. Make a procurement by way of published negotiations (without a notice)PP3a. Make a procurement by way of published negotiations (without a notice).</p>
<p>20. The initiated procurement (carried out by way of published negotiations) must be linked to the closing of the open tender and to the same line (s) of the procurement plan).</p>
<p>21. When creating an initiated procurement project on this basis, the procurement project must be automatically filled in with the data of the open tender, and the user must be warned that during the negotiations on this basis it cannot change the essential conditions.</p>
<p>22. A mechanism for the transfer of procurement project data must be created, allowing the administration of the rules for linking the transferred project data (for example, linking the changed general conditions, specifying the data to be transferred or not to be transferred, etc.).</p>
<p>23. When correcting the procurement data, the changed information (visible difference from the open tender) must be in track changes. The exclusion of changes must be visible only to the specialists of the PPO and procuring PE.</p>
</td>
</tr>
<tr>
<td width="73">
<p>E7</p>
</td>
<td width="176">
<p>Procurement by way of non-published negotiations</p>
</td>
<td width="107">
<p>-</p>
</td>
<td width="332">
<p>24. If no tender has been received by the deadline for submission of tenders or none of the tenders received is eligible and the PE has decided to carry out the procurement by way of non-published negotiations, one should initiate the process according to the Requirements for the implementation of the process &ldquo;PP5. Procurement by way of non-published negotiations&rdquo;.</p>
<p>25. The initiated procurement (carried out by way of non-published negotiations) must be linked to the closing of the open tender and to the same line (s) of the procurement plan).</p>
<p>26. When creating an initiated procurement project on this basis, the procurement project must be automatically filled in with the data of the open tender, and the user must be warned that during the negotiations on this basis it cannot change the essential conditions.</p>
<p>27. A mechanism for the transfer of procurement project data must be created, allowing the administration of the rules for linking the transferred project data (for example, linking the changed general conditions, specifying the data to be transferred or not to be transferred, etc.).</p>
<p>28. When correcting the procurement data, the changed information (visible difference from the open tender) must be in track changes. The exclusion of changes must be visible only to the specialists of the PPO, IA, the Supervisory Agency and specialists the procuring PE.</p>
</td>
</tr>
<tr>
<td width="73">
<p>BP12</p>
</td>
<td width="176">
<p>Carry out electronic auction</p>
</td>
<td width="107">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="332">
<p>29. Where necessary (if such a procedure was provided for in the procurement documents), it must be possible to use an electronic auction to determine the successful tenderer. For more details see the Requirements for the implementation of e-Auction management and execution process and functions.</p>
<p>30. Electronic auction must be allowed only when such procedure is provided in the procurement documents.</p>
</td>
</tr>
<tr>
<td width="73">
<p>BP13</p>
</td>
<td width="176">
<p>Inform about the results</p>
</td>
<td width="107">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="332">
<p>31. After assessment of tenders and determining the potential successful tenderer, the PE must be able to inform the suppliers about the results. For more details see the Requirements for the implementation of the process &ldquo;BP13. Inform about the results&rdquo;.</p>
</td>
</tr>
<tr>
<td width="73">
<p>T4</p>
</td>
<td width="176">
<p>Provide grounds for non-information</p>
</td>
<td width="107">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="332">
<p>32. If suppliers are not informed of the results of the procurement, the PE must be able to select at least one of the possible grounds for such a decision.</p>
</td>
</tr>
<tr>
<td width="73">
<p>E8</p>
</td>
<td width="176">
<p>Deferral term</p>
</td>
<td width="107">
<p>-</p>
</td>
<td width="332">
<p>33. SAULĖ IS must ensure that the contract is not signed before the set deferral term has expired.</p>
</td>
</tr>
<tr>
<td width="73">
<p>T5</p>
</td>
<td width="176">
<p>Provide the grounds for non-application of the term</p>
</td>
<td width="107">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="332">
<p>34. If the PE thinks that it may not apply the deferral term, it must specify the grounds for such decision. The grounds must be specified selection at least one of the possible grounds.</p>
</td>
</tr>
<tr>
<td width="73">
<p>SVP1</p>
</td>
<td width="176">
<p>Conclude a contract</p>
</td>
<td width="107">
<p>PE Manager</p>
</td>
<td width="332">
<p>35. The PE must be able to conclude a contract (contracts) with the successful supplier (s) in SAULĖ IS. For more details see Requirements for the Subsystem of Contracts.</p>
</td>
</tr>
<tr>
<td width="73">
<p>SVP2</p>
</td>
<td width="176">
<p>Conclude a preliminary contract</p>
</td>
<td width="107">
<p>PE Manager</p>
</td>
<td width="332">
<p>36. Where preliminary contract applies, the PE must be able to conclude a preliminary contract (contracts) with the successful supplier (s) in SAULĖ IS. For more details see Requirements for the Subsystem of Preliminary Contracts.</p>
</td>
</tr>
<tr>
<td width="73">
<p>T6</p>
</td>
<td width="176">
<p>Conclude an oral contract</p>
</td>
<td width="107">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="332">
<p>37. If the PE concludes an oral contract with the successful supplier (s), then the PE must be able to mark in SAULĖ IS about the fact of concluding the oral contract and justify such decision by selecting one of the possible grounds for oral award.</p>
</td>
</tr>
<tr>
<td width="73">
<p>BP14</p>
</td>
<td width="176">
<p>Publish the results of the procurement (project tender)</p>
</td>
<td width="107">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="332">
<p>38. The PE must be able to publish a notice of the procurement results, a contract award notice, procedural reports. For more details see the Requirements for the implementation of the process &ldquo;BP14. Publish the results of the procurement (project tender)&rdquo;.</p>
</td>
</tr>
<tr>
<td width="73">
<p>E9</p>
</td>
<td width="176">
<p>Flow end</p>
</td>
<td width="107">
<p>-</p>
</td>
<td width="332">
<p>39. The PE must be able to fix the procurement completion fact in SAULĖ IS.</p>
</td>
</tr>
<tr>
<td width="73">
<p>E10</p>
</td>
<td width="176">
<p>Process end</p>
</td>
<td width="107">
<p>-</p>
</td>
<td width="332">
<p>-</p>
</td>
</tr>
<tr>
<td width="73">
<p>EP1</p>
</td>
<td width="176">
<p>Ask for justification that competition has not been distorted</p>
</td>
<td width="107">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="332">
<p>40. The PE must be able to initiate the sub-process when it considers that the measures taken by the PE (for example, to publish all data provided by market consultations or consultations to the TS project participants) may not be sufficient to prevent distortions of competition. For more details see the Requirements of the process &ldquo;EP1. Ask for justification that competition has not been distorted&rdquo;.</p>
</td>
</tr>
<tr>
<td width="73">
<p>EP2.</p>
</td>
<td width="176">
<p>Check compliance of the supplier with the requirements</p>
</td>
<td width="107">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="332">
<p>41. The PE must be able to initiate a sub-process an unlimited number of times from the time the tenders are examined until the contract is signed. For more details see the Requirements for the implementation of the process EP2. Check the compliance of the supplier with the requirements.</p>
<p>42. The PE must check the compliance of the successful supplier with the requirements at least once in 1 day (term is configurable by the PPO system administrator) before the suppliers are informed about the procurement results.</p>
</td>
</tr>
<tr>
<td width="73">
<p>EP3</p>
</td>
<td width="176">
<p>Reject a tender</p>
</td>
<td width="107">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="332">
<p>43. The sub-process may be initiated at any time when the PE defined a demand.</p>
</td>
</tr>
<tr>
<td width="73">
<p>EP4</p>
</td>
<td width="176">
<p>Ask to extend the tender validity period</p>
</td>
<td width="107">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="332">
<p>44. The PE must be able to initiate a sub-process when there is a risk that tenders may expire before the contract is signed.</p>
<p>45. The term of validity of tenders shall be extended until the validity of tenders has expired.</p>
<p>46. The system must remind the PE representatives about the expiry date of tenders and propose to apply for extension of tenders.</p>
</td>
</tr>
<tr>
<td width="73">
<p>EP5</p>
</td>
<td width="176">
<p>Terminate the procurement</p>
</td>
<td width="107">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="332">
<p>47. The PE must be able to initiate this sub-process if there is a need to terminate the procurement and if the contract has not yet been signed.</p>
<p>48. Options to terminate all or part of the procurement must be available. If part of the procurement is terminated, the other parts must continue to be executed.</p>
</td>
</tr>
<tr>
<td width="73">
<p>KP2</p>
</td>
<td width="176">
<p>Examine the claim</p>
</td>
<td width="107">
<p>-</p>
</td>
<td width="332">
<p>49. The Sub-process is performed when a message with the indication &ldquo;Claim&rdquo; is received from the supplier. For more details see KP2. Examine the claim.</p>
</td>
</tr>
</tbody>
</table>

**7.6.2.3	Requirements for the implementation of the process “PP2. Procurement by restricted tender” and functions**

270. The functionality of restricted procurement must be implemented. Below one can find a process diagram and requirements for process implementation.
![image](https://user-images.githubusercontent.com/61745726/92297423-c086d600-ef47-11ea-97ff-ec95c28f9f34.png)
Fig. 7.8. Process “PP2. Procurement by restricted tender” diagram (part 1)

![image](https://user-images.githubusercontent.com/61745726/92297425-cb416b00-ef47-11ea-9243-9c5e1fcad7bc.png)
Fig. 7.9. Process “PP2. Procurement by restricted tender” diagram (part 2)

Table 7.3. Requirements for the implementation of the process “Procurement by restricted tender” 

<table width="688">
<thead>
<tr>
<td width="68">
<p>Process No</p>
</td>
<td width="155">
<p>Process title</p>
</td>
<td width="97">
<p>Process participant</p>
</td>
<td width="368">
<p>Requirements for implementation</p>
</td>
</tr>
</thead>
<tbody>
<tr>
<td width="68">
<p>E1</p>
</td>
<td width="155">
<p>Process beginning</p>
</td>
<td width="97">
<p>-</p>
</td>
<td width="368">
<p>1. &nbsp;Restricted tendering must be possible in all cases without restrictions.</p>
</td>
</tr>
<tr>
<td width="68">
<p>T1</p>
</td>
<td width="155">
<p>Create the procurement project</p>
</td>
<td width="97">
<p>Procurement Specialist</p>
</td>
<td width="368">
<p>2. The procurement specialist (or other PE employee who has been granted such a right) in SAULĖ IS must be able to create the required procurement project from the procurement plan.</p>
</td>
</tr>
<tr>
<td width="68">
<p>T2</p>
</td>
<td width="155">
<p>Appoint persons responsible for the procurement</p>
</td>
<td width="97">
<p>Procurement Specialist</p>
</td>
<td width="368">
<p>3. The procurement specialist (or other PE employee who has been granted such a right) must be able to appoint persons responsible for the procurement.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP1</p>
</td>
<td width="155">
<p>Prepare procurement documents</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>4. Using SAULĖ IS, the PE must be able to prepare the procurement documents actual for the procurement. For more details see the Process requirements &ldquo;BP1. Prepare the procurement documents&rdquo;.</p>
<p>Note: The requirement refers to all procurement documents except for notices - these are detailed separately.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP2</p>
</td>
<td width="155">
<p>Publish a prior notice (information)</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>5. If necessary, the PE must be able to publish a prior information notice. For more details see the Requirements for the implementation of the process &ldquo;BP2. Publish a preliminary notice (information)&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP3</p>
</td>
<td width="155">
<p>Publish a prior notice (terms)</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>6. If necessary, the PE must be able to publish a prior information notice stating that the purpose of this notice is to reduce the term for the submission of tenders. For more details see the Requirements for the implementation of the process &ldquo;BP3. Publish a preliminary notice (terms)&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>E2</p>
</td>
<td width="155">
<p>Minimum term from prior notice to procurement notice</p>
</td>
<td width="97">
<p>-</p>
</td>
<td width="368">
<p>7. In order to take advantage of the reduction of terms, a minimum period is elapsed between the prior notice and the contract notice.</p>
<p>8. The PE should not be prohibited from publishing a contract notice before this deadline, but in this case the reduced procedural terms should not apply (in this case the system must warn of the consequences before approving the action and treat this notice in the same way as a preliminary notice&nbsp; (information)).</p>
</td>
</tr>
<tr>
<td width="68">
<p>T3</p>
</td>
<td width="155">
<p>Linked market consultations</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>9. If market consultations related to the procurement have been published, the PE must be able to link them to the procurement project.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP6</p>
</td>
<td width="155">
<p>Published market consultations</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>10. Where appropriate, the PE should be able to issue a request to get a consultation from independent experts, institutions, market participants or the public. For more details see the Requirements for the implementation of the process &ldquo;BP6. Publish market consultations&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP7</p>
</td>
<td width="155">
<p>Publish draft TS</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>11. Where appropriate, the PE must be able to publish the draft technical specification in advance. For more details see the Requirements for the implementation of the process &ldquo;BP7. Publish draft TS&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP4</p>
</td>
<td width="155">
<p>Publish a prior notice (invitation)</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>12. Where appropriate, the PE must be able to issue a prior notice (invitation) instead of a contract notice. For more details see Requirements for the implementation of the process &ldquo;BP4. Publish a prior notice (invitation)&rdquo;.</p>
<p>13. The option to publish a prior notice (invitation) must be configured by the administrator (see requirement 210). It should be provided that a prior notice (invitation) may be published in the following cases:</p>
<p>13.1. In the case of procurement in the classical sector, if the PE is a central authority, in the case of procurement of social and other special services;</p>
<p>13.2. In the case of public procurement under the LPP, if the PE is not a central authority, in all cases;</p>
<p>13.3. When procurement is performed in the municipal sector - in all cases;</p>
<p>13.4. When procurement is performed in the defence sector - not applicable.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP8</p>
</td>
<td width="155">
<p>Publish a procurement notice (project tender)</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>14. The PE must be able to publish a procurement notice. For more details see the Requirements for the implementation of the process &ldquo;BP8. Publish a procurement notice (project tender)&rdquo;.</p>
<p>15. Publication of the notice in SAULĖ IS (in the case of international procurement - publication TED) must be considered as the beginning of procurement procedures.</p>
</td>
</tr>
<tr>
<td width="68">
<p>T4</p>
</td>
<td width="155">
<p>Invite to confirm interest</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>16. The PE must be able at the same time to send an invitation for expressions of interest to all suppliers who have expressed an interest.</p>
<p>17. In the invitation, the PE must specify the requirements for suppliers (qualification, quality management systems, etc.) and other requirements for the submission of the application, if not published, submit the procurement documents.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP9</p>
</td>
<td width="155">
<p>PP2</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>18. The PE must be able to check the qualifications of suppliers upon receipt of applications and reject those suppliers who do not meet the requirements. Where appropriate (if provided for in the procurement documents), the PE must be able to apply for qualifying and invite eligible suppliers to submit tenders. For more details see the Requirements for the implementation of the process &ldquo;BP9. Select suppliers".</p>
</td>
</tr>
<tr>
<td width="68">
<p>SP1</p>
</td>
<td width="155">
<p>Define successful tenderers</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>19. The sub-process must cover activities from the assessment of tenders to the publication of results.</p>
<p>20. It must be possible to carry out the activities of this sub-process for the whole procurement (if the procurement is not divided into lots), synchronously (activities related to each lot of the procurement are performed simultaneously) or asynchronously (each lot of the procurement is performed at its own pace).</p>
</td>
</tr>
<tr>
<td width="68">
<p>E3</p>
</td>
<td width="155">
<p>Flow beginning</p>
</td>
<td width="97">
<p>-</p>
</td>
<td width="368">
<p>-</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP10</p>
</td>
<td width="155">
<p>Get tenders of suppliers</p>
</td>
<td width="97">
<p>SAULĖ IS</p>
</td>
<td width="368">
<p>21. The PE must be able to get tenders of suppliers through SAULĖ IS. For more details see the Requirements for the implementation of the process &ldquo;BP10. Get tenders of suppliers&rdquo;.</p>
<p>22. Only suppliers who have submitted tenders and been invited by the PE must be able to submit a tender.</p>
</td>
</tr>
<tr>
<td width="68">
<p>E4</p>
</td>
<td width="155">
<p>Flow end</p>
</td>
<td width="97">
<p>-</p>
</td>
<td width="368">
<p>-</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP11</p>
</td>
<td width="155">
<p>Assess tenders</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>23. The PE must be able to assess the received tenders. For more details see the Requirements for the implementation of the process &ldquo;BP11. Assess tenders&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>E5</p>
</td>
<td width="155">
<p>Flow end</p>
</td>
<td width="97">
<p>-</p>
</td>
<td width="368">
<p>-</p>
</td>
</tr>
<tr>
<td width="68">
<p>E6</p>
</td>
<td width="155">
<p>Make a procurement by way of published negotiations (without a notice)</p>
</td>
<td width="97">
<p>-</p>
</td>
<td width="368">
<p>24. If none of the tenders received is acceptable and the PE has decided to proceed with the procurement by way of published negotiations, the procurement process must be initiated PP3a. Make a procurement by way of published negotiations (without a notice)</p>
<p>25. The initiated procurement (carried out by way of published negotiations) must be linked to the closing of the restricted tender and to the same line (s) of the procurement plan).</p>
<p>26. When creating an initiated procurement project on this basis, the procurement project must be automatically filled in with the data of the restricted tender, and the user must be warned that during the negotiations on this basis it cannot change the essential conditions.</p>
<p>27. A mechanism for the transfer of procurement project data must be created, allowing the administration of the rules for linking the transferred project data (for example, linking the changed general conditions, specifying the data to be transferred or not to be transferred, etc.).</p>
<p>28. When correcting the procurement data, the changed information (visible difference from the open tender) must be in track changes. The exclusion of changes must be visible only to the specialists of the PPO, AI, the Supervisory Agency and specialists the procuring PE.</p>
</td>
</tr>
<tr>
<td width="68">
<p>E7</p>
</td>
<td width="155">
<p>Procurement by way of non-published negotiations</p>
</td>
<td width="97">
<p>-</p>
</td>
<td width="368">
<p>29. If no tender has been received by the deadline for submission of tenders or none of the tenders received is eligible and the PE has decided to carry out the procurement by way of non-published negotiations, one should initiate the process according to the Requirements for the implementation of the process &ldquo;PP5. Procurement by way of non-published negotiations&rdquo;.</p>
<p>30. The initiated procurement (carried out by way of non-published negotiations) must be linked to the closing of the restricted tender and to the same line (s) of the procurement plan).</p>
<p>31. When creating an initiated procurement project on this basis, the procurement project must be automatically filled in with the data of the restricted tender, and the user must be warned that during the negotiations on this basis it cannot change the essential conditions.</p>
<p>32. A mechanism for the transfer of procurement project data must be created, allowing the administration of the rules for linking the transferred project data (for example, linking the changed general conditions, specifying the data to be transferred or not to be transferred, etc.).</p>
<p>33. When correcting the procurement data, the changed information (visible difference from the open tender) must be in track changes. The exclusion of changes must be visible only to the specialists of the PPO, AI, the Supervisory Agency and specialists the procuring PE.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP12</p>
</td>
<td width="155">
<p>Carry out electronic auction</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>34. Where necessary (if such a procedure was provided for in the procurement documents), it must be possible to use an electronic auction to determine the successful tenderer. For more details see the Requirements for the implementation of e-Auction management and execution process and functions.</p>
<p>35. Electronic auction must be allowed only when such procedure is provided in the procurement documents.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP13</p>
</td>
<td width="155">
<p>Inform about the results</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>36. After assessment of tenders and determining the potential successful tenderer, the PE must be able to inform the suppliers about the results. For more details see the Requirements for the implementation of the process &ldquo;BP13. Inform about the results&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>T5</p>
</td>
<td width="155">
<p>Provide grounds for non-information</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>37. If suppliers are not informed of the results of the procurement, the PE must be able to select at least one of the possible grounds for such a decision.</p>
</td>
</tr>
<tr>
<td width="68">
<p>E8</p>
</td>
<td width="155">
<p>Deferral term</p>
</td>
<td width="97">
<p>-</p>
</td>
<td width="368">
<p>38. SAULĖ IS must ensure that the contract is not signed before the set deferral term has expired.</p>
</td>
</tr>
<tr>
<td width="68">
<p>T6</p>
</td>
<td width="155">
<p>Provide the grounds for non-application of the term</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>39. If the PE thinks that it may not apply the deferral term, it must specify the grounds for such decision. The grounds must be specified selection at least one of the possible grounds.</p>
</td>
</tr>
<tr>
<td width="68">
<p>SVP1</p>
</td>
<td width="155">
<p>Conclude a contract</p>
</td>
<td width="97">
<p>PE Manager</p>
</td>
<td width="368">
<p>40. The PE must be able to conclude a contract (contracts) with the successful supplier (s) in SAULĖ IS. For more details see Requirements for the Subsystem of Contracts.</p>
</td>
</tr>
<tr>
<td width="68">
<p>SVP2</p>
</td>
<td width="155">
<p>Conclude a preliminary contract</p>
</td>
<td width="97">
<p>PE Manager</p>
</td>
<td width="368">
<p>41. Where preliminary contract applies, the PE must be able to conclude a preliminary contract (contracts) with the successful supplier (s) in SAULĖ IS. For more details see Requirements for the Subsystem of Preliminary Contracts.</p>
</td>
</tr>
<tr>
<td width="68">
<p>T7</p>
</td>
<td width="155">
<p>Conclude an oral contract</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>42. If the PE concludes an oral contract with the successful supplier (s), then the PE must be able to mark in SAULĖ IS about the fact of concluding the oral contract and justify such decision by selecting one of the possible grounds for oral award.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP14</p>
</td>
<td width="155">
<p>Publish the results of the procurement (project tender)</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>43. The PE must be able to publish a notice of the procurement results, a contract award notice, procedural reports. For more details see the Requirements for the implementation of the process &ldquo;BP14. Publish the results of the procurement (project tender)&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>E9</p>
</td>
<td width="155">
<p>Flow end</p>
</td>
<td width="97">
<p>-</p>
</td>
<td width="368">
<p>44. The PE must be able to fix the procurement completion fact in SAULĖ IS.</p>
</td>
</tr>
<tr>
<td width="68">
<p>E10</p>
</td>
<td width="155">
<p>Process end</p>
</td>
<td width="97">
<p>-</p>
</td>
<td width="368">
<p>-</p>
</td>
</tr>
<tr>
<td width="68">
<p>EP1</p>
</td>
<td width="155">
<p>Ask for justification that competition has not been distorted</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>45. The PE must be able to initiate the sub-process when it considers that the measures taken by the PE (for example, to publish all data provided by market consultations or consultations to the TS project participants) may not be sufficient to prevent distortions of competition. For more details see the Requirements of the process.</p>
</td>
</tr>
<tr>
<td width="68">
<p>EP2</p>
</td>
<td width="155">
<p>Check compliance of the supplier with the requirements</p>
</td>
<td width="97">
<p>&nbsp;</p>
</td>
<td width="368">
<p>46. The PE must be able to initiate a sub-process an unlimited number of times from the time the tenders are examined until the contract is signed. For more details see the Requirements for the implementation of the process EP2. Check the compliance of the supplier with the requirements.</p>
<p>47. The PE must check the compliance of the successful supplier with the requirements at least once in 1 day (term is configurable by the PPO system administrator) before the suppliers are informed about the procurement results.</p>
</td>
</tr>
<tr>
<td width="68">
<p>EP3</p>
</td>
<td width="155">
<p>Reject a tender</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>48. The PE must be able to initiate this Sub-process at any time when there is a need. For more details see EP3. Reject a tender.</p>
</td>
</tr>
<tr>
<td width="68">
<p>EP4</p>
</td>
<td width="155">
<p>Ask to extend the tender validity period</p>
</td>
<td width="97">
<p>&nbsp;</p>
</td>
<td width="368">
<p>49. The PE must be able to initiate the sub-process when there is a risk that tenders may expire before the contract is signed. For more details see EP4. Ask for extension of tenders.</p>
<p>50. The term of validity of tenders shall be extended until the validity of tenders has expired.</p>
<p>51. The system must remind the PE representatives about the expiry date of tenders and propose to apply for extension of tenders.</p>
</td>
</tr>
<tr>
<td width="68">
<p>EP5</p>
</td>
<td width="155">
<p>Terminate the procurement</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>52. The PE must be able to initiate this sub-process if there is a need to terminate the procurement and if the contract has not yet been signed. For more details see the Requirements for the implementation of the process &ldquo;EP5. Terminate the procurement&rdquo;.</p>
<p>53. The procurement may be terminated in whole or in part. If a part of the procurement is terminated, the other parts must continue to be executed.</p>
</td>
</tr>
<tr>
<td width="68">
<p>KP2</p>
</td>
<td width="155">
<p>Examine the claim</p>
</td>
<td width="97">
<p>-</p>
</td>
<td width="368">
<p>54. The Sub-process is performed when a message with the indication &ldquo;Claim&rdquo; is received from the supplier. For more details see KP2. Examine the claim</p>
</td>
</tr>
</tbody>
</table>

**7.6.2.4	Requirements for the implementation of the process “PP3. Procurement by way of published negotiations” and functions**
325. The functionality of procurement execution by way of published negotiations must be implemented. Below one can find a process diagram and requirements for process implementation.

![image](https://user-images.githubusercontent.com/61745726/92297444-fd52cd00-ef47-11ea-95d1-9732e6540352.png)
Fig. 7.10. Process “PP3. Procurement by way of published negotiations” diagram (part 1)

![image](https://user-images.githubusercontent.com/61745726/92297446-05127180-ef48-11ea-839c-ac6f09714e7b.png)
Fig. 7.11. Process “PP3. Procurement by way of published negotiations” diagram (part 2)

Table 7.4. Requirements for the implementation of the process “PP3. Procurement by way of published negotiations”
<table width="688">
<tbody>
<tr>
<td width="68">
<p>Process No</p>
</td>
<td width="150">
<p>Process title</p>
</td>
<td width="96">
<p>Process participant</p>
</td>
<td colspan="2" width="374">
<p>Requirements for implementation</p>
</td>
</tr>
<tr>
<td width="68">
<p>E1</p>
</td>
<td width="150">
<p>Process beginning</p>
</td>
<td width="96">
<p>-</p>
</td>
<td colspan="2" width="374">
<p>1. The PE must be able to perform the procurement by way of published negotiations when at least one of the grounds established by the PPO system administrator is met.</p>
</td>
</tr>
<tr>
<td width="68">
<p>T1</p>
</td>
<td width="150">
<p>Create the procurement project</p>
</td>
<td width="96">
<p>Procurement Specialist</p>
</td>
<td colspan="2" width="374">
<p>2. The Procurement Specialist (or other PE employee who has been granted such a right) in SAULĖ IS must be able to create the required procurement project from the procurement plan</p>
</td>
</tr>
<tr>
<td width="68">
<p>T2</p>
</td>
<td width="150">
<p>Appoint persons responsible for the procurement</p>
</td>
<td width="96">
<p>Procurement Specialist</p>
</td>
<td colspan="2" width="374">
<p>3. The procurement specialist (or other PE employee who has been granted such a right) must be able to appoint persons responsible for the procurement.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP1</p>
</td>
<td width="150">
<p>Prepare procurement documents</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td colspan="2" width="374">
<p>4. The PE must be able to prepare procurement documents relevant to the procurement by means implemented by SAULĖ IS. For more details see Requirements of the implementation of the process &ldquo;BP1. Prepare procurement documents&rdquo;.</p>
<p>Note: all procurement documents are covered except for notices - these are detailed separately.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP2</p>
</td>
<td width="150">
<p>Publish a prior notice (information)</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td colspan="2" width="374">
<p>5. If necessary, the PE must be able to publish a prior information notice. For more details see the Requirements for the implementation of the process &ldquo;BP2. Publish a preliminary notice (information)&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP3</p>
</td>
<td width="150">
<p>Publish a prior notice (terms)</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td colspan="2" width="374">
<p>6. If necessary, the PE must be able to publish a prior information notice stating that the purpose of this notice is to reduce the term for the submission of tenders. For more details see the Requirements for the implementation of the process &ldquo;BP3. Publish a preliminary notice (terms)&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>E2</p>
</td>
<td width="150">
<p>Minimum term from prior notice to procurement notice</p>
</td>
<td width="96">
<p>-</p>
</td>
<td colspan="2" width="374">
<p>7. In order to take advantage of the reduction of terms, a minimum period is elapsed between the prior notice and the contract notice.</p>
<p>8. The PE should not be prohibited from publishing a contract notice before this deadline, but in this case the reduced procedural terms should not apply (in this case the system must warn of the consequences before approving the action and treat this notice in the same way as a preliminary notice&nbsp; (information)).</p>
</td>
</tr>
<tr>
<td width="68">
<p>T3</p>
</td>
<td width="150">
<p>Linked market consultations</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td colspan="2" width="374">
<p>9. If market consultations related to the procurement have been published, the PE must be able to link them to the procurement project.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP6</p>
</td>
<td width="150">
<p>Published market consultations</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td colspan="2" width="374">
<p>10. Where appropriate, the PE should be able to issue a request to get a consultation from independent experts, institutions, market participants or the public. For more details see the Requirements for the implementation of the process &ldquo;BP6. Publish market consultations&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP7</p>
</td>
<td width="150">
<p>Publish draft TS</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td colspan="2" width="374">
<p>11. Where appropriate, the PE must be able to publish the draft technical specification in advance. For more details see the Requirements for the implementation of the process &ldquo;BP7. Publish draft TS&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP4</p>
</td>
<td width="150">
<p>Publish a prior notice (invitation)</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td colspan="2" width="374">
<p>12. Where appropriate, the PE must be able to issue a prior notice (invitation) instead of a contract notice. For more details see Process Requirements &ldquo;BP4. Publish a prior notice (invitation)&rdquo;.</p>
<p>13. The option to publish a prior notice (invitation) must be configured by the administrator (see requirement 210). It should be provided that a prior notice (invitation) may be published in the following cases:</p>
<p>13.1. In the case of procurement in the classical sector, if the PE is a central authority, in the case of procurement of social and other special services;</p>
<p>13.2. In the case of public procurement under the LPP, if the PE is not a central authority, in all cases;</p>
<p>13.3. When procurement is performed in the municipal sector - in all cases;</p>
<p>14. When procurement is performed in the defence sector - not applicable.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP8</p>
</td>
<td width="150">
<p>Publish a procurement notice (project tender)</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td colspan="2" width="374">
<p>15. The PE must be able to publish a procurement notice. For more details see the Requirements for the implementation of the process &ldquo;BP8. Publish a procurement notice (project tender)&rdquo;.</p>
<p>16. Publication of the notice in SAULĖ IS (in the case of international procurement - publication TED) must be considered as the beginning of procurement procedures.</p>
</td>
</tr>
<tr>
<td width="68">
<p>T4</p>
</td>
<td width="150">
<p>Invite to confirm interest</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td colspan="2" width="374">
<p>17. The PE must be able at the same time to send an invitation for expressions of interest to all suppliers who have expressed an interest.</p>
<p>18. In the invitation, the PE must specify the requirements for suppliers (qualification, quality management systems, etc.) and other requirements for the submission of the application, if not published, submit the procurement documents.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP9</p>
</td>
<td width="150">
<p>Select suppliers</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td colspan="2" width="374">
<p>19. The PE must be able to check the qualifications of suppliers upon receipt of applications and reject those suppliers who do not meet the requirements. Where appropriate (if provided for in the procurement documents), the PE must be able to apply for qualifying and invite eligible suppliers to submit tenders. For more details see the Requirements for the implementation of the process &ldquo;BP9. Select suppliers&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>SP1</p>
</td>
<td width="150">
<p>Define successful tenderers</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td colspan="2" width="374">
<p>20. The sub-process must cover activities from the assessment of tenders to the publication of results.</p>
<p>21. It must be possible to carry out the activities of this sub-process for the whole procurement (if the procurement is not divided into lots), synchronously (activities related to each lot of the procurement are performed simultaneously) or asynchronously (each lot of the procurement is performed at its own pace).</p>
</td>
</tr>
<tr>
<td width="68">
<p>E3</p>
</td>
<td width="150">
<p>Flow beginning</p>
</td>
<td width="96">
<p>-</p>
</td>
<td colspan="2" width="374">
<p>-</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP10</p>
</td>
<td width="150">
<p>Get tenders of suppliers</p>
</td>
<td width="96">
<p>SAULĖ IS</p>
</td>
<td colspan="2" width="374">
<p>22. The option to receive tenders of suppliers through SAULĖ IS must be available. For more details see the Requirements for the implementation of the process &ldquo;BP10. Get tenders of suppliers&rdquo;.</p>
<p>23. Only the tenderers who has submitted their application and invited by the PE may submit their tenders.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP11</p>
</td>
<td width="150">
<p>Assess tenders</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td colspan="2" width="374">
<p>24. The PE must be able to assess the tenders received through SAULĖ IS. For more details see the Requirements for the implementation of the process &ldquo;BP11. Assess tenders&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>E4</p>
</td>
<td width="150">
<p>Flow end</p>
</td>
<td width="96">
<p>-</p>
</td>
<td colspan="2" width="374">
<p>25. -</p>
</td>
</tr>
<tr>
<td width="68">
<p>E5</p>
</td>
<td width="150">
<p>Procurement by way of non-published negotiations</p>
</td>
<td width="96">
<p>-</p>
</td>
<td colspan="2" width="374">
<p>26. If no tender has been received by the deadline for submission of tenders or none of the tenders received is eligible and the PE has decided to carry out the procurement by way of non-published negotiations, one should initiate the process according to the Requirements for the implementation of the process &ldquo;PP5. Procurement by way of non-published negotiations&rdquo;.</p>
<p>27. Does not apply to procurement in the classical sector.</p>
<p>28. The initiated procurement (carried out by way of non-published negotiations) must be linked to the previous procurement based on which the negotiations are conducted and to the same line (lines) of the procurement plan.</p>
<p>29. When creating an initiated procurement project on this basis, the procurement project shall be automatically filled in with the published negotiation data, and the user shall be warned that during the negotiations on this basis it may not change the essential conditions.</p>
<p>30. A mechanism for the transfer of procurement project data must be created, allowing the administration of the rules for linking the transferred project data (for example, linking the changed general conditions, specifying the data to be transferred or not to be transferred, etc.).</p>
<p>31. When correcting the procurement data, the corrected information (differ from the published negotiations) must be in track change. The track changes must be visible only to the specialists of the PPO, AI, the Supervisory Agency and the procuring PE.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP15</p>
</td>
<td width="150">
<p>Negotiate with suppliers</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td colspan="2" width="374">
<p>32. The PE must be able to negotiate through SAULĖ IS with tenderers whose initial and subsequent tenders meet the minimum requirements set out in the procurement documents and ask them to submit final tenders. For more details see the Requirements for the implementation of the process &ldquo;BP15. Negotiate with suppliers&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP12</p>
</td>
<td width="150">
<p>Carry out electronic auction</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="366">
<p>33. Where necessary (if such a procedure was provided for in the procurement documents), it must be possible to use an electronic auction to determine the successful tenderer. For more details see the Requirements for the implementation of e-Auction management and execution process and functions.</p>
<p>34. Electronic auction must be allowed only when such procedure is provided in the procurement documents.</p>
</td>
<td width="7">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP13</p>
</td>
<td width="150">
<p>Inform about the results</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td colspan="2" width="374">
<p>35. After assessment of tenders and determining the potential successful tenderer, the PE must be able to inform the suppliers about the results. For more details see the Requirements for the implementation of the process &ldquo;BP13. Inform about the results&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>T5</p>
</td>
<td width="150">
<p>Provide grounds for non-information</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td colspan="2" width="374">
<p>36. If suppliers are not informed of the results of the procurement, the PE must be able to select at least one of the possible grounds for such a decision.</p>
</td>
</tr>
<tr>
<td width="68">
<p>E6</p>
</td>
<td width="150">
<p>Deferral term</p>
</td>
<td width="96">
<p>-</p>
</td>
<td colspan="2" width="374">
<p>37. SAULĖ IS must ensure that the contract is not signed before the set deferral term has expired.</p>
</td>
</tr>
<tr>
<td width="68">
<p>T6</p>
</td>
<td width="150">
<p>Provide the grounds for non-application of the term</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td colspan="2" width="374">
<p>38. If the PE thinks that it may not apply the deferral term, it must specify the grounds for such decision. The grounds must be specified selection at least one of the possible grounds.</p>
</td>
</tr>
<tr>
<td width="68">
<p>SVP1</p>
</td>
<td width="150">
<p>Conclude a contract</p>
</td>
<td width="96">
<p>PE Manager</p>
</td>
<td colspan="2" width="374">
<p>39. The PE must be able to conclude a contract (s) with the successful supplier (s). For more details see the Requirements for the Subsystem of Contracts.</p>
</td>
</tr>
<tr>
<td width="68">
<p>SVP2</p>
</td>
<td width="150">
<p>Conclude a preliminary contract</p>
</td>
<td width="96">
<p>PE Manager</p>
</td>
<td colspan="2" width="374">
<p>40. Where preliminary contract applies, the PE must be able to conclude a preliminary contract (contracts) with the successful supplier (s) in SAULĖ IS. For more details see Requirements for the Subsystem of Preliminary Contracts.</p>
</td>
</tr>
<tr>
<td width="68">
<p>T7</p>
</td>
<td width="150">
<p>Conclude an oral contract</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td colspan="2" width="374">
<p>41. If the PE concludes an oral contract with the successful supplier (s), then the PE must be able to mark in SAULĖ IS about the fact of concluding the oral contract and justify such decision by selecting one of the possible grounds for oral award.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP14</p>
</td>
<td width="150">
<p>Publish the results of the procurement (project tender)</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td colspan="2" width="374">
<p>42. The PE must be able to publish a notice of the procurement results, a contract award notice, procedural reports. For more details see the Requirements for the implementation of the process &ldquo;BP14. Publish the results of the procurement (project tender)&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>E7</p>
</td>
<td width="150">
<p>Flow end</p>
</td>
<td width="96">
<p>-</p>
</td>
<td colspan="2" width="374">
<p>43. The PE must be able to record the end of the procurement in SAULĖ IS.</p>
</td>
</tr>
<tr>
<td width="68">
<p>E8</p>
</td>
<td width="150">
<p>Process end</p>
</td>
<td width="96">
<p>-</p>
</td>
<td colspan="2" width="374">
<p>-</p>
</td>
</tr>
<tr>
<td width="68">
<p>EP1</p>
</td>
<td width="150">
<p>Ask for justification that competition has not been distorted</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="366">
<p>44. The PE must be able to initiate the sub-process when it considers that the measures taken by the PE (for example, to publish all data provided by market consultations or consultations to the TS project participants) may not be sufficient to prevent distortions of competition. For more details see the Requirements of the process.</p>
</td>
<td width="7">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="68">
<p>EP2.</p>
</td>
<td width="150">
<p>Check compliance of the supplier with the requirements</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="366">
<p>45. The PE must be able to initiate a sub-process an unlimited number of times from the time the tenders are examined until the contract is signed. For more details see the Requirements for the implementation of the process EP2. Check the compliance of the supplier with the requirements.</p>
<p>46. The PE must check the compliance of the successful supplier with the requirements at least once in 1 day (term is configurable by the PPO system administrator) before the suppliers are informed about the procurement results.</p>
</td>
<td width="7">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="68">
<p>EP3</p>
</td>
<td width="150">
<p>Reject a tender</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="366">
<p>47. The PE must be able to initiate this Sub-process at any time when there is a need. For more details see EP3. Reject a tender.</p>
</td>
<td width="7">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="68">
<p>EP4.</p>
</td>
<td width="150">
<p>Ask to extend the tender validity period</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="366">
<p>48. The PE must be able to initiate the sub-process when there is a risk that tenders may expire before the contract is signed. For more details see the Requirements for the implementation of the process &ldquo;EP4. Ask for extension of tenders&rdquo;. &nbsp;</p>
<p>49. The term of validity of tenders shall be extended until the validity of tenders has expired.</p>
<p>50. The system must remind the PE representatives about the expiry date of tenders and propose to apply for extension of tenders.</p>
</td>
<td width="7">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="68">
<p>EP5.</p>
</td>
<td width="150">
<p>Terminate the procurement</p>
</td>
<td width="96">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="366">
<p>51. The PE must be able to initiate this sub-process if there is a need to terminate the procurement and if the contract has not yet been signed. For more details see the Requirements for the implementation of the process &ldquo;EP5. Terminate the procurement&rdquo;.</p>
<p>52. All or part of the procurement may be terminated. If a part of the procurement is terminated, the other parts continue to be executed.</p>
</td>
<td width="7">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="68">
<p>KP2</p>
</td>
<td width="150">
<p>Examine the claim</p>
</td>
<td width="96">
<p>-</p>
</td>
<td colspan="2" width="374">
<p>53. The Sub-process is performed when a message with the indication &ldquo;Claim&rdquo; is received from the supplier. For more details see KP2. Examine the claim.</p>
</td>
</tr>
</tbody>
</table>

**7.6.2.5	Requirements for the implementation of the process “PP3a. Make a procurement by way of published negotiations (without a notice)” and functions** 
379. Functionality of the process “PP3a. Make a procurement by way of published negotiations (without a notice)” must be implemented. Below one can find a process diagram and requirements for the process implementation.

![image](https://user-images.githubusercontent.com/61745726/92297463-2a06e480-ef48-11ea-8fc8-b3788930068b.png)
Fig. 7.12. Process “PP3a. Make a procurement by way of published negotiations (without a notice)” diagram 
Table 7.5. Requirements for the implementation of the process “PP3a. Make a procurement by way of published negotiations (without a notice)”

<table width="688">
<tbody>
<tr>
<td width="69">
<p>Process No</p>
</td>
<td width="119">
<p>Process title</p>
</td>
<td width="87">
<p>Process participant</p>
</td>
<td width="413">
<p>Requirements for implementation</p>
</td>
</tr>
<tr>
<td width="69">
<p>E1</p>
</td>
<td width="119">
<p>Process beginning</p>
</td>
<td width="87">
<p>-</p>
</td>
<td width="413">
<p>1. The process must be initiated if the PE carries out the procurement by means of published negotiations based on prior failed procurement.</p>
</td>
</tr>
<tr>
<td width="69">
<p>T1</p>
</td>
<td width="119">
<p>Process beginning</p>
</td>
<td width="87">
<p>-</p>
</td>
<td width="413">
<p>2. The process must be initiated if the PE carries out the procurement by means of published negotiations based on prior failed procurement.</p>
<p>3. If the project is created from a prior failed procurement project by way of published negotiations, the justification for the selection of the procurement method shall be automatically selected for the developed project.</p>
<p>4. When a project of the procurement by way of published negotiations is developed from a procurement plan, the PE must link the procurement to the corresponding previously failed procurement if it chooses the justification that the procurement is based on a prior failed procurement.</p>
<p>5. The terms of an open or restricted tender must be automatically copied into the published draft negotiations.</p>
<p>6. During the procurement, the Entities/persons involved in the procurement must be allowed to upload various documents related to the procurement (not only those specified in the process) and revise the already uploaded documents. Any changes to the terms of an open or restricted tender must be clearly marked.</p>
</td>
</tr>
<tr>
<td width="69">
<p>T2</p>
</td>
<td width="119">
<p>Invite for negotiations</p>
</td>
<td width="87">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="413">
<p>7. The PE must be able to invite all suppliers who have participated in a prior failed procurement and who have met the requirements set out by the PE regarding the grounds for exclusion, qualification, quality management system and / or environmental management system standards and formal procurement procedure, to negotiate.</p>
</td>
</tr>
<tr>
<td width="69">
<p>SP1</p>
</td>
<td width="119">
<p>Define successful tenderers</p>
</td>
<td width="87">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="413">
<p>8. The sub-process must cover activities from the assessment of tenders to the publication of results.</p>
<p>9. It must be possible to carry out the activities of this sub-process for the whole procurement (if the procurement is not divided into lots), synchronously (activities related to each lot of the procurement are performed simultaneously) or asynchronously (each lot of the procurement is performed at its own pace).</p>
</td>
</tr>
<tr>
<td width="69">
<p>E4</p>
</td>
<td width="119">
<p>Flow beginning</p>
</td>
<td width="87">
<p>-</p>
</td>
<td width="413">
<p>10. -</p>
</td>
</tr>
<tr>
<td width="69">
<p>BP10</p>
</td>
<td width="119">
<p>Get tenders of suppliers</p>
</td>
<td width="87">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="413">
<p>11. The option to receive tenders of suppliers through SAULĖ IS must be available. For more details see the Requirements for the implementation of the process &ldquo;BP10. Get tenders of suppliers&rdquo;.</p>
<p>12. Only suppliers invited to the negotiations by the PE may submit a tender.</p>
</td>
</tr>
<tr>
<td width="69">
<p>E3</p>
</td>
<td width="119">
<p>Flow end</p>
</td>
<td width="87">
<p>-</p>
</td>
<td width="413">
<p>-</p>
</td>
</tr>
<tr>
<td width="69">
<p>E4</p>
</td>
<td width="119">
<p>Procurement by way of non-published negotiations</p>
</td>
<td width="87">
<p>-</p>
</td>
<td width="413">
<p>13. If no tender has been received by the deadline for submission of tenders or none of the tenders received is eligible and the PE has decided to carry out the procurement by way of non-published negotiations, one should initiate the process according to the Requirements for the implementation of the process &ldquo;PP5. Procurement by way of non-published negotiations&rdquo;.&nbsp; &nbsp;</p>
<p>14. Does not apply to procurement in the classical sector.</p>
<p>15. The initiated procurement (carried out by way of non-published negotiations) must be linked to the previous procurement based on which the negotiations are conducted and to the same line (lines) of the procurement plan.</p>
<p>16. When creating an initiated procurement project on this basis, the procurement project is automatically filled in with the data of the conducted restricted tender, and the user is warned that during the negotiations on this basis it cannot change the essential conditions.</p>
<p>17. A mechanism for the transfer of procurement project data must be created, allowing the administration of the rules for linking the transferred project data (for example, linking the changed general conditions, specifying the data to be transferred or not to be transferred, etc.).</p>
<p>18. When correcting the procurement data, the corrected information (differ from the restricted tender) must be in track change. The track changes must be visible only to the specialists of the PPO, IA, the Supervisory Agency and the procuring PE</p>
</td>
</tr>
<tr>
<td width="69">
<p>BP15</p>
</td>
<td width="119">
<p>Negotiate with suppliers</p>
</td>
<td width="87">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="413">
<p>19. The PE must be able to negotiate through SAULĖ IS with tenderers whose initial and subsequent tenders meet the minimum requirements set out in the procurement documents and ask them to submit final tenders. For more details see &ldquo;BP15. Negotiate with suppliers&rdquo;.</p>
</td>
</tr>
<tr>
<td width="69">
<p>BP12</p>
</td>
<td width="119">
<p>Carry out electronic auction</p>
</td>
<td width="87">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="413">
<p>20. Where necessary (if such a procedure was provided for in the procurement documents), it must be possible to use an electronic auction to determine the successful tenderer. For more details see the Requirements for the implementation of e-Auction management and execution process and functions.</p>
<p>21. Electronic auction must be allowed only when such procedure is provided in the procurement documents.</p>
</td>
</tr>
<tr>
<td width="69">
<p>BP13</p>
</td>
<td width="119">
<p>Inform about the results</p>
</td>
<td width="87">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="413">
<p>22. After assessment of tenders and determining the potential successful tenderer, the PE must be able to inform the suppliers about the results. For more details see &ldquo;BP13. Inform about the results&rdquo;.</p>
</td>
</tr>
<tr>
<td width="69">
<p>T3</p>
</td>
<td width="119">
<p>Provide grounds for non-information</p>
</td>
<td width="87">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="413">
<p>23. If suppliers are not informed of the results of the procurement, the PE must be able to indicate the reasons for such a decision.</p>
</td>
</tr>
<tr>
<td width="69">
<p>E5</p>
</td>
<td width="119">
<p>Deferral term</p>
</td>
<td width="87">
<p>-</p>
</td>
<td width="413">
<p>24. The contract may not be signed until the deferral term has expired.</p>
</td>
</tr>
<tr>
<td width="69">
<p>T4</p>
</td>
<td width="119">
<p>Provide the grounds for non-application of the term</p>
</td>
<td width="87">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="413">
<p>25. If the PE considers that it may waive the deferral term, the PE must be able to indicate the reasons for this decision in SAULĖ IS.</p>
</td>
</tr>
<tr>
<td width="69">
<p>SVP1</p>
</td>
<td width="119">
<p>Conclude a contract</p>
</td>
<td width="87">
<p>PE Manager</p>
</td>
<td width="413">
<p>26. The PE must be able to conclude a contract (contracts) with the successful supplier (s) in SAULĖ IS. For more details see Requirements for the Subsystem of Contracts.</p>
</td>
</tr>
<tr>
<td width="69">
<p>SVP2</p>
</td>
<td width="119">
<p>Conclude a preliminary contract</p>
</td>
<td width="87">
<p>PE Manager</p>
</td>
<td width="413">
<p>27. Where preliminary contract applies, the PE must be able to conclude a preliminary contract (contracts) with the successful supplier (s) in SAULĖ IS. For more details see Requirements for the Subsystem of Preliminary Contracts.</p>
</td>
</tr>
<tr>
<td width="69">
<p>T5</p>
</td>
<td width="119">
<p>Conclude an oral contract</p>
</td>
<td width="87">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="413">
<p>28. If the PE concludes an oral contract with the successful supplier (s), then the PE must be able to mark in SAULĖ IS about the fact of concluding the oral contract and justify such decision by selecting one of the possible grounds for oral award.</p>
</td>
</tr>
<tr>
<td width="69">
<p>BP14</p>
</td>
<td width="119">
<p>Publish the results of the procurement (project tender)</p>
</td>
<td width="87">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="413">
<p>29. The PE must be able to publish a notice of the procurement results, a contract award notice, procedural reports. For more details see the Requirements for the implementation of the process &ldquo;BP14. Publish the results of the procurement (project tender)&rdquo;.</p>
</td>
</tr>
<tr>
<td width="69">
<p>E6</p>
</td>
<td width="119">
<p>Flow end</p>
</td>
<td width="87">
<p>-</p>
</td>
<td width="413">
<p>30. Procurement completion.</p>
</td>
</tr>
<tr>
<td width="69">
<p>E7</p>
</td>
<td width="119">
<p>Process end</p>
</td>
<td width="87">
<p>-</p>
</td>
<td width="413">
<p>-</p>
</td>
</tr>
<tr>
<td width="69">
<p>EP1</p>
</td>
<td width="119">
<p>Ask for justification that competition has not been distorted</p>
</td>
<td width="87">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="413">
<p>31. The PE must be able to initiate the sub-process when it considers that the measures taken by the PE (for example, to publish all data provided by market consultations or consultations to the TS project participants) may not be sufficient to prevent distortions of competition. For more details see the Requirements of the process.</p>
</td>
</tr>
<tr>
<td width="69">
<p>EP2</p>
</td>
<td width="119">
<p>Check compliance of the supplier with the requirements</p>
</td>
<td width="87">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="413">
<p>32. The PE must be able to initiate a sub-process an unlimited number of times from the time the tenders are examined until the contract is signed. For more details see the Requirements for the implementation of the process EP2. Check the compliance of the supplier with the requirements.</p>
<p>33. The PE must check the compliance of the successful supplier with the requirements at least once in 1 day (term is configurable by the PPO system administrator) before the suppliers are informed about the procurement results.</p>
</td>
</tr>
<tr>
<td width="69">
<p>EP3</p>
</td>
<td width="119">
<p>Reject a tender</p>
</td>
<td width="87">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="413">
<p>34. The PE must be able to initiate this Sub-process at any time when there is a need. For more details see the Requirements for the implementation of the process &ldquo;EP3. Reject a tender&rdquo;.</p>
</td>
</tr>
<tr>
<td width="69">
<p>EP4</p>
</td>
<td width="119">
<p>Ask to extend a tender validity period</p>
</td>
<td width="87">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="413">
<p>35. The PE must be able to initiate the sub-process when there is a risk that tenders may expire before the contract is signed. For more details see the Requirements for the implementation of the process &ldquo;EP4. Ask for extension of tenders&rdquo;.</p>
</td>
</tr>
<tr>
<td width="69">
<p>EP5</p>
</td>
<td width="119">
<p>Terminate the procurement</p>
</td>
<td width="87">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="413">
<p>36. The PE must be able to initiate this sub-process if there is a need to terminate the procurement and if the contract has not yet been signed. For more details see the Requirements for the implementation of the process &ldquo;EP5. Terminate the procurement&rdquo;.</p>
</td>
</tr>
<tr>
<td width="69">
<p>KP2</p>
</td>
<td width="119">
<p>Examine the claim</p>
</td>
<td width="87">
<p>-</p>
</td>
<td width="413">
<p>37. The Sub-process is performed when a message with the indication &ldquo;Claim&rdquo; is received from the supplier. For more details see KP2. Examine the claim.</p>
</td>
</tr>
</tbody>
</table>

**7.6.2.6	Requirements for the implementation of the process “PP4. Procurement by way of competitive dialogue” and functions** 

417. The functionality of procurement by way of competitive dialogue must be implemented. Below one can find a process diagram and requirements for the process implementation.

![image](https://user-images.githubusercontent.com/61745726/92297487-53277500-ef48-11ea-90a1-73c4488d9c9c.png)
Fig. 7.13. Process “PP4. Procurement by way of competitive dialogue” diagram (part 1)

![image](https://user-images.githubusercontent.com/61745726/92297489-5b7fb000-ef48-11ea-971a-97c85ccc8e1b.png)

Fig. 7.14. Process “PP4. Procurement by way of competitive dialogue” diagram (part 2)

_Table 7.6. Requirements for the implementation of the process “PP4. Procurement by way of competitive dialogue”_

<table width="688">
<tbody>
<tr>
<td width="68">
<p>Process No</p>
</td>
<td width="154">
<p>Process title</p>
</td>
<td width="97">
<p>Process participant</p>
</td>
<td width="368">
<p>Requirements for implementation</p>
</td>
</tr>
<tr>
<td width="68">
<p>E1</p>
</td>
<td width="154">
<p>Process beginning</p>
</td>
<td width="97">
<p>-</p>
</td>
<td width="368">
<p>1. The PE must be able to procure by way of competitive dialogue when at least one of the justifications established by the POO system administrator is met.</p>
</td>
</tr>
<tr>
<td width="68">
<p>T1</p>
</td>
<td width="154">
<p>Create the procurement project</p>
</td>
<td width="97">
<p>Procurement specialist</p>
</td>
<td width="368">
<p>2. The procurement specialist (or other PE employee who has been granted such a right) in SAULĖ IS must be able to create the required procurement project from the procurement plan.</p>
</td>
</tr>
<tr>
<td width="68">
<p>T2</p>
</td>
<td width="154">
<p>Appoint persons responsible for the procurement</p>
</td>
<td width="97">
<p>Procurement specialist</p>
</td>
<td width="368">
<p>3. The procurement specialist (or other PE employee who has been granted such a right) must be able to appoint persons responsible for the procurement.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP1</p>
</td>
<td width="154">
<p>Prepare procurement documents</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>4. The PE must be able to prepare procurement documents relevant to the procurement. For more details see the Requirements of the implementation of the process &ldquo;BP1. Prepare procurement documents&rdquo;.</p>
<p>Note: The requirement refers to all procurement documents except for notices - these are detailed separately.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP2</p>
</td>
<td width="154">
<p>Publish a prior notice (information)</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>5. If necessary, the PE must be able to publish a prior information notice. For more details see the Requirements for the implementation of the process &ldquo;BP2. Publish a preliminary notice (information)&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>T3</p>
</td>
<td width="154">
<p>Linked market consultations</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>6. If market consultations related to the procurement have been published, the option for the PE to link them to the procurement project must be available.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP6</p>
</td>
<td width="154">
<p>Published market consultations</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>7. Where appropriate, the PE should be able to issue a request to get a consultation from independent experts, institutions, market participants or the public. For more details see the Requirements for the implementation of the process &ldquo;BP6. Publish market consultations&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP7</p>
</td>
<td width="154">
<p>Publish draft TS</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>8. Where appropriate, the PE must be able to publish the draft technical specification in advance. For more details see the Requirements for the implementation of the process &ldquo;BP7. Publish draft TS&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP8</p>
</td>
<td width="154">
<p>Publish a procurement notice (project tender)</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>9. The PE must be able to publish a procurement notice. For more details see the Requirements for the implementation of the process &ldquo;BP8. Publish a procurement notice (project tender)&rdquo;.</p>
<p>10. Publication of the notice in SAULĖ IS (in the case of international procurement - publication TED) must be considered as the beginning of procurement procedures.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP9</p>
</td>
<td width="154">
<p>Select suppliers</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>11. The PE must be able to check the qualifications of suppliers upon receipt of applications and reject those suppliers who do not meet the requirements. Where appropriate (if provided for in the procurement documents), the PE must be able to apply for qualifying and invite eligible suppliers to submit tenders. For more details see the Requirements for the implementation of the process &ldquo;BP9. Select suppliers".</p>
</td>
</tr>
<tr>
<td width="68">
<p>SP1</p>
</td>
<td width="154">
<p>Define successful tenderers</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>12. The sub-process must cover activities from the assessment of tenders to the publication of results.</p>
<p>13. It must be possible to carry out the activities of this sub-process for the whole procurement (if the procurement is not divided into lots), synchronously (activities related to each lot of the procurement are performed simultaneously) or asynchronously (each lot of the procurement is performed at its own pace).</p>
</td>
</tr>
<tr>
<td width="68">
<p>E2</p>
</td>
<td width="154">
<p>Flow beginning</p>
</td>
<td width="97">
<p>-</p>
</td>
<td width="368">
<p>-</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP10</p>
</td>
<td width="154">
<p>Get tenders of suppliers</p>
</td>
<td width="97">
<p>SAULĖ IS</p>
</td>
<td width="368">
<p>14. The option to receive tenders of suppliers through SAULĖ IS must be available. For more details see the Requirements for the implementation of the process &ldquo;BP10. Get tenders of suppliers&rdquo;.</p>
<p>15. Only the tenderers who has submitted their application and invited by the PE may submit their tenders.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP11</p>
</td>
<td width="154">
<p>Assess tenders</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>16. The PE must be able to assess the received tenders in SAULĖ IS environment. For more details see the Requirements for the implementation of the process &ldquo;BP11. Assess tenders&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>SP2</p>
</td>
<td width="154">
<p>Conduct a dialogue</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>17. The PE must be able to engage in a dialogue through SAULĖ IS with tenderers whose initial and subsequent tenders meet the minimum requirements set out in the procurement documents and ask them to submit final tenders. For more details see the Requirements for the implementation of the process &ldquo;SP2. Conduct dialogue&rdquo; and functions.</p>
</td>
</tr>
<tr>
<td width="68">
<p>E3</p>
</td>
<td width="154">
<p>Procurement by way of non-published negotiations</p>
</td>
<td width="97">
<p>-</p>
</td>
<td width="368">
<p>18. If no tender has been received by the deadline for submission of tenders or none of the tenders received is eligible and the PE has decided to carry out the procurement by way of non-published negotiations, one should initiate the process according to the Requirements for the implementation of the process &ldquo;PP5. Procurement by way of non-published negotiations&rdquo;.</p>
<p>19. This option should not apply to procurement in the classical sector.</p>
<p>20. The initiated procurement (carried out by way of non-published negotiations) must be linked to the previous procurement based on which the negotiations are conducted and to the same line (lines) of the procurement plan.</p>
<p>21. When creating an initiated procurement project on this basis, the procurement project shall be automatically filled in with the competitive dialogue data, and the user shall be warned that during the negotiations on this basis it may not change the essential conditions.</p>
<p>22. A mechanism for the transfer of procurement project data must be created, allowing the administration of the rules for linking the transferred project data (for example, linking the changed general conditions, specifying the data to be transferred or not to be transferred, etc.).</p>
<p>23. Corrections to procurement data the corrected information must distinguish (differ from competitive dialogue).</p>
</td>
</tr>
<tr>
<td width="68">
<p>E4</p>
</td>
<td width="154">
<p>Flow end</p>
</td>
<td width="97">
<p>-</p>
</td>
<td width="368">
<p>-</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP13</p>
</td>
<td width="154">
<p>Inform about the results</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>24. After assessment of tenders and determining the potential successful tenderer, the PE must be able to inform the suppliers about the results. For more details see the Requirements for the implementation of the process &ldquo;BP13. Inform about the results&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>T4</p>
</td>
<td width="154">
<p>Provide grounds for non-information</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>25. If suppliers are not informed of the results of the procurement, the PE must be able to select at least one of the possible grounds for such a decision.</p>
</td>
</tr>
<tr>
<td width="68">
<p>E5</p>
</td>
<td width="154">
<p>Deferral term</p>
</td>
<td width="97">
<p>-</p>
</td>
<td width="368">
<p>26. SAULĖ IS must ensure that the contract is not signed before the set deferral term has expired.</p>
</td>
</tr>
<tr>
<td width="68">
<p>T5</p>
</td>
<td width="154">
<p>Provide the grounds for non-application of the term</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>27. If the PE thinks that it may not apply the deferral term, it must specify the grounds for such decision. The grounds must be specified selection at least one of the possible grounds.</p>
</td>
</tr>
<tr>
<td width="68">
<p>SVP1</p>
</td>
<td width="154">
<p>Conclude a contract</p>
</td>
<td width="97">
<p>PE Manager</p>
</td>
<td width="368">
<p>28. The PE must be able to conclude a contract (contracts) with the successful supplier (s) in SAULĖ IS. For more details see Requirements for the Subsystem of Contracts.</p>
</td>
</tr>
<tr>
<td width="68">
<p>SVP2</p>
</td>
<td width="154">
<p>Conclude a preliminary contract</p>
</td>
<td width="97">
<p>PE Manager</p>
</td>
<td width="368">
<p>29. Where preliminary contract applies, the PE must be able to conclude a preliminary contract (contracts) with the successful supplier (s) in SAULĖ IS. For more details see Requirements for the Subsystem of Preliminary Contracts.</p>
</td>
</tr>
<tr>
<td width="68">
<p>T6</p>
</td>
<td width="154">
<p>Conclude an oral contract</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>30. If the PE concludes an oral contract with the successful supplier (s), then the PE must be able to mark in SAULĖ IS about the fact of concluding the oral contract and justify such decision by selecting one of the possible grounds for oral award.</p>
</td>
</tr>
<tr>
<td width="68">
<p>BP14</p>
</td>
<td width="154">
<p>Publish the results of the procurement (project tender)</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>31. The PE must be able to publish a notice of the procurement results, a contract award notice, procedural reports. For more details see the Requirements for the implementation of the process &ldquo;BP14. Publish the results of the procurement (project tender)&rdquo;.</p>
</td>
</tr>
<tr>
<td width="68">
<p>E6</p>
</td>
<td width="154">
<p>Flow end</p>
</td>
<td width="97">
<p>-</p>
</td>
<td width="368">
<p>32. The PE must be able to fix the procurement completion fact in SAULĖ IS.</p>
</td>
</tr>
<tr>
<td width="68">
<p>E7</p>
</td>
<td width="154">
<p>Process end</p>
</td>
<td width="97">
<p>-</p>
</td>
<td width="368">
<p>-</p>
</td>
</tr>
<tr>
<td width="68">
<p>EP1</p>
</td>
<td width="154">
<p>Ask for justification that competition has not been distorted</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>33. The PE must be able to initiate the sub-process when it considers that the measures taken by the PE (for example, to publish all data provided by market consultations or consultations to the TS project participants) may not be sufficient to prevent distortions of competition. For more details see the Requirements of the process.</p>
</td>
</tr>
<tr>
<td width="68">
<p>EP2</p>
</td>
<td width="154">
<p>Check compliance of the supplier with the requirements</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>34. The PE must be able to initiate a sub-process an unlimited number of times from the time the tenders are examined until the contract is signed. For more details see the Requirements for the implementation of the process &ldquo;EP2. Check the compliance of the supplier with the requirements&rdquo;.</p>
<p>35. The PE must check the compliance of the successful supplier with the requirements at least once in 1 day (term is configurable by the PPO system administrator) before the suppliers are informed about the procurement results.</p>
</td>
</tr>
<tr>
<td width="68">
<p>EP3.</p>
</td>
<td width="154">
<p>Reject a tender</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>The PE must be able to initiate this Sub-process at any time when there is a need.</p>
</td>
</tr>
<tr>
<td width="68">
<p>EP4.</p>
</td>
<td width="154">
<p>Ask to extend the tender validity period</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>36. The PE must be able to initiate the sub-process when there is a risk that tenders may expire before the contract is signed.</p>
<p>37. The term of validity of tenders shall be extended until the validity of tenders has expired.</p>
<p>38. The system must remind the PE representatives about the expiry date of tenders and propose to apply for extension of tenders.</p>
</td>
</tr>
<tr>
<td width="68">
<p>EP5.</p>
</td>
<td width="154">
<p>Terminate the procurement</p>
</td>
<td width="97">
<p>Entities/persons involved in the procurement</p>
</td>
<td width="368">
<p>39. The PE must be able to initiate this sub-process if there is a need to terminate the procurement and if the contract has not yet been signed. For more details see the Requirements for the implementation of the process &ldquo;EP5. Terminate the procurement&rdquo;.</p>
<p>40. All or part of the procurement may be terminated. If a part of the procurement is terminated, the other parts continue to be executed.</p>
</td>
</tr>
<tr>
<td width="68">
<p>KP2</p>
</td>
<td width="154">
<p>Examine the claim</p>
</td>
<td width="97">
<p>-</p>
</td>
<td width="368">
<p>41. The Sub-process is performed when a message with the indication &ldquo;Claim&rdquo; is received from the supplier. For more details see KP2. Examine the claim.</p>
</td>
</tr>
</tbody>
</table>
