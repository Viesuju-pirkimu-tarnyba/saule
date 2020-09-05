## 6	DESCRIPTION OF SAULĖ IS CURRENT SITUATION AND PROBLEMS TO BE SOLVED BY SAULĖ IS MODIFICATION PROJECT 

* [DESCRIPTION OF PPO INFORMATION SYSTEMS ](#user-content-61description-of-ppo-information-systems)
* [6.2 STATISTICAL INFORMATION OF PPO INFORMATION SYSTEMS](#user-content-62statistical-information-of-ppo-information-systems)
* [6.3 PROBLEMS SOLVED BY THE MODIFICATION PROJECT](#user-content-63problems-solved-by-the-modification-project)




#### 6.1	DESCRIPTION OF PPO INFORMATION SYSTEMS 
<ol>
<li><strong>The purpose of CPP IS </strong>is to identify and authenticate contracting authorities or other purchasing organisations authorized by them, institutions responsible for the selection of EU-funded projects, supervision of their implementation, providing applicants and project implementers with information on project preparation and implementation requirements (hereinafter - Implementing Agencies), and representatives of suppliers by enabling them to use the tools provided by CPP IS for public procurement, procurement, fuel procurement and concession award procedures, process information system data electronically, provide information to data recipients for the purpose of performing procedures, identify potential conflicts of interest, identify whether suppliers meet the requirements of the Law on Public Procurement in the field of grounds for exclusion.
<ul>
<li>Key CPP IS functions:</li>
<li>Administer and systematise data of Procurement Implementers, Supervisory Agencies and Suppliers;</li>
<li>receive, manage, store, process and publish data on public procurement, procurement, fuel procurement and concessions;</li>
<li>create, send and store internal and external system messages;</li>
<li>collect, store, transfer and analyse the information on planned and ongoing public procurements, concluded procurement contracts and results of procurement contracts;</li>
<li>store and archive procurement and concession award documents.</li>
<li>Processes and auxiliary processes related to current procurement and control take place in:</li>
<li>CPPIS;</li>
<li>Public Procurement Risk Management Information System (hereinafter referred to as the PPRM IS);</li>
<li>Using other organisational means - DMS, PPO website, e-mail, using Office Software (* .doc, * .docx, etc. format files) and etc.</li>
</ul>
</li>
<li>Below one can find a diagram of the PPO information systems infrastructure and a description of its components. Renewal of worn-out equipment is planned for the second quarter of the year 2020.</li>
</ol>

![image](https://user-images.githubusercontent.com/61745726/92297107-8cf67c80-ef44-11ea-9f90-87d04911b0c0.png)

Fig. 6.1. Diagram of the PPO information systems infrastructure.

20. Below one can find a logical diagram of the PPO information systems and its description.

![image](https://user-images.githubusercontent.com/61745726/92297117-967fe480-ef44-11ea-9172-e06ff6dc293c.png)

Fig. 6.2. Logical diagram of the PPO information systems

Table 6.1. Description of a logical diagram of the PPO information systems
<table width="100%">
<thead>
<tr>
<td width="21%">
<p>Component</p>
</td>
<td width="53%">
<p>Purpose</p>
</td>
<td width="24%">
<p>Software used</p>
</td>
</tr>
</thead>
<tbody>
<tr>
<td width="21%">
<p>PPM IS</p>
</td>
<td width="53%">
<p>Public Procurement Monitoring Information System (hereinafter referred to as the PPM IS), designed for satisfaction of needs of PPO and other official (municipal) authorities, Procurement Implementers, suppliers (Implementers) and public. PPM IS covers the following functions:</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; posting, searching, and filtering of advertisements, entering of advertisements, editing, publishing, and archiving;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; entering, editing and archiving of reports;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; entering, editing and archiving contracts.</p>
</td>
<td width="24%">
<p>Microsoft IIS, Microsoft ASP Classic, Microsoft SQL Server 2005 (integrations created using Microsoft BizTalk Server 2006).</p>
</td>
</tr>
<tr>
<td width="21%">
<p>CPPP (old and new)</p>
</td>
<td width="53%">
<p>Central Public Procurement Portal (hereinafter referred to as the CPPP), designed for publication of public procurement advertisements and reports. CPPP covers the following functions:&nbsp;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp; management and publication of a summary table of planned public procurements;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp; publication and management of technical specifications, publication of notices, reports and contracts;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp; management and publication of a list of goods, services and works provided by social companies;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp; management and administration of the information on suppliers who failed to perform or improperly performed the procurement contract, when the procurement contract has been terminated due to a material breach of the procurement contract as defined in the Civil Code of the Republic of Lithuania, or when a court decision satisfying the Implementer&rsquo;s requirements to declare non-performance or improper performance of the procurement contract and indemnification of the related losses comes into force;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; publication of tenders of successful tenderers, concluded contracts and amendments of the terms and conditions of the contracts in accordance with the provisions of the Law on Legal Protection of Personal Data.</p>
</td>
<td width="24%">
<p>Microsoft IIS, Joomla CMS, My SQL, (integrations created using Microsoft BizTalk Server 2006).</p>
</td>
</tr>
<tr>
<td width="21%">
<p>Integration platform</p>
</td>
<td width="53%">
<p>Component designed to ensure data exchange between information systems used by the PPO (PPM IS, CPPP, CTM).</p>
</td>
<td width="24%">
<p>Microsoft BizTalk Server 2006.</p>
</td>
</tr>
<tr>
<td width="21%">
<p>CTM</p>
</td>
<td width="53%">
<p>Public Procurement Procedure Implementation Sub-System (hereinafter referred to as the CTM), which covers the following functions:</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Data entry, deactivation, editing, publishing, checking, entering template settings, generating, editing and deactivating, setting required fields, setting optional fields, setting confidentiality, sending messages, displaying alerts, assigning purchases, importing files;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; management, which includes functions that allow organisation, storage, transfer, deletion and other processing of electronic documents and their metadata;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; creation, management, deletion of procurement groups, creation, management, termination of electronic procurement, establishment of electronic procurement procedure templates, including functions enabling to set rules, logical and quantitative settings and restrictions for electronic procurement procedures, creation, management, import and export of electronic procurement objects, management of qualification issues, review of electronic procurement audit sequence, management and submission of electronic procurement tenders, management of tender documents, management of price submission settings, analysis and assessment of tenders;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; digital signing of tender documents with electronic signature, approval and submission of tenders;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; functions for creation, messaging, sending and storage of internal and external system messages and e-mails.</p>
</td>
<td width="24%">
<p>-</p>
</td>
</tr>
<tr>
<td width="21%">
<p>PPRM IS</p>
</td>
<td width="53%">
<p>Public Procurement Risk Management Information System (hereinafter referred to as PPRM IS) designed for assessment and management of the risk of risk objects using information technology tools. PPRM IS has the following functions:</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; collect data required for risk management of risk objects;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; collect, process and display information necessary for risk management (calculation, assessment, monitoring and other actions) of risk objects;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; process information on changes in the risk of risk objects;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; form lists of risk objects for assessment and verification and risk maps required for risk management of risk objects.</p>
</td>
<td width="24%">
<p>Microsoft SQL Server 2012 Standard Edition</p>
<p>Java 1.7</p>
<p>JBoss AS 7.1.1</p>
<p>Java Server Faces 2.1 , Java Servlet, XHTML, Ajax components (using JSF technology), JavaScript, JQuery</p>
<p>Primefaces 3.5</p>
<p>Eclipse Link 2.5.0</p>
<p>JBoss ESB 4.12</p>
<p>MS SQL Server 2012 Reporting Services</p>
<p>MS SQL Server 2012 Reports Builder 3.0</p>
<p>Apache CXF 2.7.6</p>
</td>
</tr>
<tr>
<td width="21%">
<p>DMS</p>
</td>
<td width="53%">
<p>Document Management System (hereinafter referred to as DMS) designed for processing, management, storage and convenient access to document information.</p>
</td>
<td width="24%">
<p>&ldquo;Kontora&rdquo;</p>
</td>
</tr>
</tbody>
</table>

#### 6.2	STATISTICAL INFORMATION OF PPO INFORMATION SYSTEMS 

21. Volumes of data stored in CPPIS:
21.1. Currently, the data stored in CPPIS occupies 495494.40 MB.
21.2. Over the year (2019-2020), the data volumes increased, respectively:
21.3. DB data has increased from 350GB to 498GB over the year.
21.4. File cache data increased from 18.4TB to 21.73TB.

![image](https://user-images.githubusercontent.com/61745726/92297150-df379d80-ef44-11ea-9bb3-6b4e132d0507.png)
Fig. 6.3. Volumes of data stored in CPPIS in 2019-2020.

22. According to the data available in 2019, 40675 Procurement Implementers and 9652 Suppliers were registered as users in CPPIS.
![image](https://user-images.githubusercontent.com/61745726/92297152-eb235f80-ef44-11ea-929f-2fbde984ebc7.png)
Fig. 6.4. Number of CPPIS users in 2019.

23. In 2019 average number of logged in users (sessions) per day was 10451. Below one can find the average number of users (sessions) logged in per day in different months.
![image](https://user-images.githubusercontent.com/61745726/92297157-f6768b00-ef44-11ea-8386-ec7ee5fa120e.png)
Fig. 6.5. Average number of users (sessions) logged in per day in 2019.

<ol>
<li>CPPIS speed / performance information:
<ul>
<li>The average time (in seconds) to upload a page to a user is up to 3 seconds.</li>
<li>The main known problematic functions of CPPIS, which speed is insufficient:</li>
<li>Filling in notices, reports, if there are more than 50 lots.</li>
<li>Uploading of large documents (~ 30 MB and more).</li>
<li>Signing of a tender if large number of files is uploaded (~ 50 files and more).</li>
<li>Submission of a tender, if many lots have been created in the procurement (more than 15 lots)).</li>
</ul>
</li>
</ol>


#### 6.3	PROBLEMS SOLVED BY THE MODIFICATION PROJECT 

<ul>
<li>Problems of the current situation:</li>
<li>The National Anti-Corruption Program of the Republic of Lithuania for 2015-2025, approved by Resolution No XII-1537 of the Seimas of the Republic of Lithuania of 10 March 2015 &ldquo;On the Approval of the National Anti-Corruption Program of the Republic of Lithuania for 2015&ndash;2025&rdquo; (hereinafter referred to as the Program) identifies 8 priority areas where the possibility of the spread of corruption is the highest. One of these areas is public procurement.</li>
<li>Reasons for high levels of corruption in public procurement:</li>
<li>Lack of transparency and publicity,</li>
<li>Significant impact of public procurement on the country&rsquo;s economy and business entities,</li>
<li>Insufficiently effective control mechanism,</li>
<li>Insufficient liability for offences committed,</li>
<li>Influence of politicians, etc.</li>
<li>In specific cases, corruption is still affected by informal preliminary agreements, adaption of qualification requirements for protected companies, procurement of unnecessary goods, services or additional works, improper performance and supervision of contracts, abuse of rights of suppliers to defend their interests, insufficient competition of social enterprises, unlawful agreements between such enterprises and abuse of social enterprise status, competition restrictive (cartel) agreements. Suppliers participating in public procurement enter into unlawful agreements, and it is difficult to exclude such suppliers from public procurement under the current legal framework. Suppliers participating in public procurement enter into illegal agreements and it is difficult to exclude such suppliers from public procurement under the current legal framework.</li>
<li>Main problems to be solved:</li>
<li>Insufficiently automated public procurement system, which creates conditions for various manifestations of corruption. The development of electronic management is one of the tools for transparency, openness and citizen involvement in management and democratic processes;</li>
<li>Insufficiently structured data on Procurement Contracts and their implementation;</li>
<li>Insufficiently public, transparent, easy to find and systematized information covering all procurement-related processes and contract implementation;</li>
<li>The integration with other state information systems required for automatic data submission has not been developed.</li>
<li>Considering the problems listed above and in accordance with the legal acts, it is planned to computerise the following activities by CPP IS modification:</li>
<li>Maximum structuring;</li>
<li>Integrate the system with the systems of other institutions which data are relevant in the public procurement procedure and control institutions - this would allow to refuse to receive paper documents from the competent authorities, prevent forgery of documents.</li>
<li>Automate the procurement process from the planning of the procurement to the conclusion of the contract, so that there would be minimum human factors and to avoid providing incorrect information or forgery of documents.</li>
<li>Develop tools for greater publicity. Publicity is a key tool in the fight against corruption;</li>
<li>Develop tools for low-value procurement in order to ensure fair and convenient selection of suppliers, especially in case of unpublished procurement. Low-value procurement accounts for a significant proportion of public procurement and must be provided with convenient and anti-abuse tools;</li>
<li>Develop interfaces with systems or functionalities to trace potential conflicts of interest;</li>
<li>Prevent corruption schemes in public procurement contracts - one of the possibilities for corruption in public procurement is to set contract terms when one of the suppliers is not ready to perform them, therefore stricter contract supervision and measures in the system are needed. It is provided that the contract will be electronic, filled in the system, and will also include amendments to the contract, which would allow more accurate and urgent identification of breaches of the contract performance;</li>
<li>Automate the procedure for issuing certificates of successful contracts;</li>
<li>Develop automatic tools for exclusion of suppliers included to &ldquo;blacklists&rdquo; from the procurement procedure;</li>
<li>Implement other measures to prevent acts of corruption.</li>
</ul>
<ol start="2">
<li><strong>The main identified problems related to the procurement execution processes of the Procurement Implementers:</strong>
<ul>
<li>The need to optimize the execution and forming of procedures;</li>
<li>Ineffectiveness of tender publication;</li>
<li>Inefficiency of tender assessment;</li>
<li>It is impossible to use / select templates of procurement documents and contracts in CPPIS;</li>
<li>CPPIS usually performs only the function of information transfer;</li>
<li>The Procurement Plan exists as a separate, fixed list, which is difficult to prepare, and its data are linked only to the Procurement Notice, but not to the entire Procurement procedure and the public procurement contract or concession contract;</li>
<li>Different documents repeat the information that needs to be entered each time, for example: Fixed parts of the procurement conditions for different procurements;</li>
<li>Repeating procurement data through different procurement process documents;</li>
<li>Upon completion of the procurement, several separate reports must be submitted - a separate procurement contract, a report form to be filled in, contract award notices in the case of international procurement, publicly available documents are not linked (the completed procurement report is not linked to the signed contract).</li>
</ul>
</li>
<li><strong>The main problems identified by representatives of suppliers:</strong>
<ul>
<li>The unified code does not link the entry in the procurement plan, market consultation, technical specification notice, procurement notice, therefore there is no specific procurement traceability, it is impossible to follow the selected procurement progress - status changes;</li>
<li>Lack of information in procurement plans (filters, procurement updates, date updates according to the real situation, procurement values, etc.);</li>
<li>Execution of market consultations - unification of published data, publication of questions and answers, publication of changes;</li>
<li>Updated competitions for the same procurement appear on a single page in the overall list, so there is confusion in distinguishing between updated competition procedures;</li>
<li>Submission of absence of grounds for exclusion and submission of qualification data (large volumes, does not receive data automatically from other IS);</li>
<li>Information from previous procurements and trusted information is not reused;</li>
</ul>
</li>
</ol>
