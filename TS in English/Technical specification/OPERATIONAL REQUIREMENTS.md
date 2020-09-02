* [FUNCTIONAL DIAGRAM](#user-content-functional-diagram)
* [EXTERNAL AND INTERNAL DATA FLOWS](#user-content-external-and-internal-data-flows)
* [CONCEPTUAL DATA MODEL](#user-content-conceptual-data-model)
* [DATA PROVISION AND USE](#user-content-data-provision-and-use)
* [NON-FUNCTIONAL REQUIREMENTS](#user-content-non-functional-requirements)

## OPERATIONAL REQUIREMENTS

### FUNCTIONAL DIAGRAM

CPP IS functional diagram is provided in fig 1.


CVP IS | CPP   IS
-- | --
  |  
Procedūrų vykdymo posistemis   CTM | Procedure   Implementation Subsystem CTM
«component»   Sistemos naudotojų modulis | «component»   System   User Module
«component»   Elektroninių pirkimų   dokumentų modulis | «component»   Module   of Electronic Procurement Documents
«component»   Elektroninių pirkimų modulis | «component»   Electronic   Procurement Module
«component»   Pasiūlymų pateikimo modulis | «component»   Tender   Submission Module
«component»   Pranešimų modulis | «component»   Message   Module
  |  
Viešųjų pirkimų monitoringo   posistemis VPM IS | Public   Procurement Monitoring Subsystem PPM IS
«component»   Supaprastintų viešųjų pirkimų   taisyklių viešinimo modulis | «component»   Module   for Publication of Simplified Public Procurement Rules
«component»   Skelbimų modulis | «component»   Module   of Notices
«component»   Sutarčių modulis | «component»   Module   of Contracts
«component»   Ataskaitų modulis | «component»   Module   of Reports
  |  
Centrinis viešųjų pirkimų   portalo posistemis CVPP | Central   Public Procurement Portal Subsystem CPPP
«component»   Metinių pirkimų planų modulis | «component»   Module   of Annual Procurement Plans
«component»   Publikavimo modulis | «component»   Publishing   Module
«component»   Socialinių įmonių sąrašo   modulis | «component»   Module   of the List of Social Enterprises
«component»   Informacijos apie pirkimo   sutarties neįvykdžiusius ar netinkamai ją įvykdžiusius tiekėjus modulis | «component»   Module of Information on Suppliers who Failed   to Perform or Improperly Performed the Procurement Contract
«component»   Sutarčių modulis | «component»   Module   of Contracts

![image](https://user-images.githubusercontent.com/61745726/91891729-3239f800-ec9a-11ea-8d43-bb09f627d837.png)
Fig. 1. CPP IS functional diagram

Table 3 provides summarised descriptions of CPP IS subsystems and implemented functionalities.
_Table 3. Description of CPP IS subsystems_

Subsystem | Purpose
-- | --
Procedure   implementation subsystem CTM | Procedure   implementation subsystem CTM consists of:   ·        System user module, the functions of which   are identification, registration, activation, suspension, deletion and   management of user data, recording and storage of user actions and events;   ·        Module of electronic   procurement documents, the functions of which are management, including functions enabling   the organisation, storage, transmission, deletion and other management of   electronic documents and their metadata;   ·        Electronic procurement   module, the functions of which are creation, management, deletion of   procurement groups, creation, management, termination of electronic   procurement procedures, definition of templates for electronic procurement   procedures, including functions enabling setting of rules, logical and   quantitative settings and restrictions for electronic procurement procedures,   compilation, management, import and export of the list of electronic   procurement objects, management of qualification issues, review of the   electronic procurement audit sequence, management and submission of   electronic procurement tenders, management of tender documents, management of   price submission settings, analysis and assessment of tenders;   ·        Tender submission module: digital signing of tender   documents with electronic signature, approval and submission of tenders;   ·        Module of message, the functions of which   are creation, sending and storage of internal and external system messages   and e-mails.
Public   Procurement Monitoring Subsystem PPM IS | Public Procurement   Monitoring Subsystem PPM IS consists of:   ·        Module for publication   simplified public procurement rules, the functions of which are introduction, editing   and publication of simplified public procurement rules   ·        Module of notices, the functions of which   are posting, subscribing, searching and filtering of notices, entering,   editing, publishing and archiving of notices;   ·        Module of reports, the functions of which   are entering, editing and archiving of reports;   ·        Module of contracts, the functions of which   are entering, editing and archiving of contracts.
Central   Public Procurement Portal Subsystem CPPP | Central Public   Procurement Portal Subsystem CPPP consists of:   ·        Module of annual   procurement plans, the functions of which are management and publication of a summary   table of planned public procurement;   ·        Publishing module, the functions of which   are the publication and management of technical specifications, the   publication of notices, reports and contracts;   ·        Module of the list of   social enterprises, the functions of which are management and publication of the list of   goods, services and works provided by social enterprises;   ·        Module of information on   suppliers who failed to perform or improperly performed the procurement   contract, the functions of which are management and administration of the   information on suppliers who failed to perform or improperly performed the   procurement contract, when the procurement contract has been terminated due   to a material breach of the procurement contract as defined in the Civil Code   of the Republic of Lithuania, or when a court decision satisfying the   Executor`s requirements to declare non-performance or improper performance of   the procurement contract and indemnification of the related losses comes into   force;   ·       Module of contracts, the functions of which are publication of tenders of successful   tenderers, concluded contracts and amendments of the terms and conditions of   the contracts in accordance with the provisions of the Law on Legal   Protection of Personal Data.

### EXTERNAL AND INTERNAL DATA FLOWS


####	External data flows 
CPP IS external data flows (hereinafter referred to as EDF) are demonstrated on figure 

![image](https://user-images.githubusercontent.com/61745726/91891882-6ca39500-ec9a-11ea-8728-aede98f066c7.png)


Informacinė   sisteme „E. sąskaita“ | Information System “E. sąskaita”
-- | --
IDS1/   IDS 4 | EDF1/EDF4
JAR | REL
IDS2 | EDF2
SFMIS | SFMIS
IDS3 | EDF3
Išorinės   verslo IS | External Business IS
IDS10 | EDF10
CVP   IS | CPP IS
Priežiūros   institucijų IS | Supervisory Agency IS
IDS9 | EDF9
TED   (EK) | TED (EK)
IDS5 | EDF5
ANR   (IRD) | RAO (IRD)
IDS6 | IDS6
PAIIS   (RC) | ISSA (RC)
IDS7 | EDF7
CPO   IS (CPO) | CPO IS (CPO)
IDS8 | EDF8
  |  
Informacinė   sisteme „E. sąskaita“ | Information System “E. sąskaita”
IDS1/   IDS4 | EDF1/EDF4
JAR | REL
IDS2 | EDF2
Įgaliojimų   registras | Register of Powers of Attorney
IDS11 | EDF11
SFMIS | SFMIS
IDS3 | EDF3
Išorinės   verslo IS | External Business IS
IDS10 | EDF10
CVP   IS | CPP IS
GR | PR
IDS12 | EDF12
Priežiūros   institucijų IS | Supervisory Agency IS
IDS9 | EDF9
TED   (EK) | TED (EK)
IDS5 | EDF5
ANR   (IRD) | RAO (IRD)
IDS6 | EDF6
PAIIS   (RC) | ISSA (RC)
IDS7 | EDF7
CPO   IS (CPO) | CPO IS (CPO)
IDS8 | EDF8

Fig. 2. External information flows

CPP IS EDF, demonstrated in fig. 2., are described in Table 4

_Table 4. External data flows_ 

Flow identifier | IS receiving the data | IS providing the data | Institution providing the data | Data description | Frequency | Data format | Transfer method
-- | -- | -- | -- | -- | -- | -- | --
EDF1 | CPP IS | Information System “E.   sąskaita” | RC | Details of invoices meeting the EU standard:    • the series and number of the credit and debit document and the advance   invoice;   • date of issue of the VAT invoice, credit and debit   document and advance invoice;   • seller (seller`s legal entity code, seller`s name,   seller`s address, VAT payer`s code);   • buyer (buyer`s legal entity code, buyer`s name,   buyer`s address, VAT payer`s code);   • contract number; contract identifier;   • goods or services (name, quantity, price per unit   of the supplied goods or services (excluding VAT), VAT rate (rates) and code   (codes), VAT amount), amount;   ·        • currency. | Upon demand | Structured data SOAP/XML format (network services) | Authorized access
EDF2 | CPP IS | RLE | RC | Data on legal entities registered in CPP IS:   • object   code (9 digits);   • code   before the establishment of the Register of Legal Entities (7 digits);   • current   name of the object; legal form code;   • legal status   code; the date of registration of the object;   • date of   establishment of the object (for traditional religious communities and labour   organisations);   • date of   deregistration;   • address   of the registered office (text and address elements according to the   classification of the Address Register - identifiers of the administrative   unit, place of residence, street, house, premises or former number);   • name,   surname, position title of the manager;   ·        • contact details of the object (telephone, fax,   e-mail address, website address). | Upon demand | Structured data SOAP/XML format (network services) | Authorized access
EDF3 | CPP IS | SFMIS | Ministry of Finance of the Republic of Lithuania | ·        Data of the European Union Structural Assistance Subsystem for 2007-2013:   Project Code, Operational Program Code, Priority Code, Measure Code, Project   Name, Project Executor Name, Project Executor Code, Implementing Agency,   Intermediate Authority Name, Funding Value, Project Cost Value, Project   financing and administration agreement effective date, Project activities   implementation commencement date, Project activities implementation   completion date, Project stage, Project status, Partner name, Partner code,   Suspicion identification SFMIS code, Project code, Suspicion registration   date, Suspicion investigation status (0 - in progress, 1 - completed),   Suspicion investigation completion date, Description of the suspicion, Is an   offence found? (0 - no, 1 - yes), Offence identification SFMIS code, Offence   unique code, Offence detection date, Offence type code (classification in the   system), Offence additional type code (classification in the system);   ·        European Union Structural Funds data for 2014-2020: user data (SFMIS   username, date of removal, user status, name, surname, institution, position,   telephone number, e-mail, Project Code, Operational Program Code, Priority   Code, Measure Code, Project Name, Project Executor Name, Project Executor   Code, Implementing Agency, Intermediate Authority Name, Funding Value,   Project Cost Value, Project financing and administration agreement effective   date, Project activities implementation commencement date, Project activities   implementation completion date, Project stage, Project status, Partner name,   Partner code, Suspicion identification SFMIS code, Project code, Suspicion   registration date, Suspicion investigation status (0 - in progress, 1 -   completed), Suspicion investigation completion date, Description of the   suspicion, Is an offence found? (0 - no, 1 - yes), Offence identification SFMIS   code, Offence unique code, Offence detection date, Offence type code   (classification in the system), Offence additional type code (classification   in the system)). | Upon demand | Structured data SOAP/XML format (network services) | Authorized access
EDF4 | Information System “E.   sąskaita” | CPP IS | PPO | Data provided by IS “E.   sąskaita” to CPP IS:   ·           data of registered contracting authorities   (legal entity code, name of the legal entity);   ·          details   of public procurement contracts:   o     procurement   number;   o     contract   number or identification number (if available);   o     legal   entity code of the contracting authority;   o     legal   entity code of the supplier;   o     general   code of the supplier;   o     the   status of the procurement contract;   o     country   code of the supplier;   o     the   date of conclusion of the contract. | Upon demand | Structured data SOAP/XML format (network services) | Authorized access
EDF5 | TED | CPP IS | PPO | TED provides data on   the procurement and the content of its notice in accordance with the intended   TED integration specification. | Upon demand | Structured data SOAP/XML format (network services) | Authorized access
EDF6 | RAO | CPP IS | PPO | The RAO transfers to the CPP IS the data of reports on the person who   has committed an administrative offense (natural or legal person):   • If LE- LE code;   • If NP- NP code;   • data on administrative offense:   • date and time of the administrative   offense;   o      the essence of the administrative offense (brief description of the   administrative offense) (if it cannot be decided from the ANC Article whether   the penalties referred to in Article 46 (4) (7) were present, then a   description is required);   o      item, paragraph, Article of the Code of Administrative Offenses, which   establishes administrative liability for the committed administrative   offense, level of seriousness of the offence;   o      title, article, paragraph, item, sub-paragraph of another legal act   under which the person is subject to administrative liability;   o    information and indication that a   low-risk act has been committed, as provided for in Article 12 of the Code of   Administrative Offenses “Low-risk act”. | Upon demand | Structured data SOAP/XML format (network services) | Authorized access
EDF7 | ISSA (RC) | CPP IS | PPO | Data provided by CPP IS   (according to the requirements of the integration specification provided by   ISSA):   • data of the economic operator (LE code);   • details of the inspection plan of economic operators:   o    the economic operator to be   inspected (LE name, code, name (s) of NP);   o    the business address of the   inspected operator;   o    deadline for inspection;   o    inspection purpose;   o    information of economic operators   (NP telephone number, e-mail address);   o    details of the activity inspection   order;   • activity inspection data:   o   the economic operator to be   inspected (LE name, code, name (s) of NP);   o   type of activity inspection;   o   place of inspection;   • data on the employees of the Supervisory   Agency who performed the activity inspection;   • data on the facts found during the activity   inspection;   • control questionnaire data. | Upon demand | Structured data SOAP/XML format (network services) | Authorized access
EDF8 | CPO IS (CPO) | CPP IS | PPO | It is planned to receive data from the CPO IS according to the   submitted SAULĖ IS inquiry (organisation LE code and procurement number (for   those LE procurements where the CPO is indicated as the Executor of the   procurement in the procurement plan). | Upon demand | Structured data SOAP/XML format (network services) | Authorized access
EDF9 | IS for Supervisory Agencies | CPP IS | PPO | Transfer data in an agreed manner (on data medium or via a data   transfer interface). | Upon demand | Structured data SOAP/XML format (network services) | Authorized access
EDF10 | External Business IS (Executors of procurement) | CPP IS | PPO | Provide from CPP IS   (universal interface for all):   • CPPV code classifier;   • Correspondence data;   • Data of claims;   • Data of proposals;   • Proposal / tender assessment data;   • Publicity data of the successful tender;   • Contract data / amendment / termination /   status data;   • Procurement status data;   • Details of commission members and   commission minutes;   • Data from PPO conclusions;   • Lists of suppliers who have provided false information   and unreliable suppliers;   • Trial data;   ·        • Data of consolidation with other Contracting Authorities. | Upon demand | Structured data SOAP/XML format (network services) | Authorized access
EDF11 | CPP IS | Register    of Powers of Attorney | RC | Details   of the natural or legal entity entitled (authorised) to represent legal   persons / powers:   ·          date of authorisation;   ·          place of authorisation;   ·          principal (natural person   number, name, surname, address of place of residence, if the natural person   is not registered in Population Register, - date of birth, name, surname,   address of place of residence; legal form and name of the legal person,   registered office, legal entity code, if the legal person is registered   abroad - legal entity code or registration number, foreign state where the   legal entity is registered, legal form and name of the legal entity,   registered office);   ·          agent (natural person   number, name, surname, address of place of residence, if the natural person   is not registered in Population Register, - date of birth, name, surname,   address of place of residence; legal form and name of the legal person,   registered office, legal entity code, if the legal person is registered   abroad - legal entity code or registration number, foreign state where the   legal entity is registered, legal form and name of the legal entity,   registered office);   ·          term of authorisation   (defined or indefinite). | Upon demand | Structured data SOAP/XML format (network services) | Authorized access
EDF12 | CPP IS | Population Register | RC | Data on   natural persons (personal number (object identification code), name (s),   surname (s), date of birth, place of residence (address), date of death). | Upon demand | Structured data SOAP/XML format (network services) | Authorized access

####	Internal data flows
CPP IS does not implement internal data flows, i.e. there is no data exchange between the CPP IS subsystems. CPP IS subsystems read and make records independently in one CPP IS database.

### CONCEPTUAL DATA MODEL

CPP IS data groups and data are described in Table 5.
Table 5. CPP IS data groups and data

<table width="100%">
<thead>
<tr>
<td width="8%">
<p>No</p>
</td>
<td width="23%">
<p>Data group</p>
</td>
<td width="68%">
<p>Data description</p>
</td>
</tr>
</thead>
<tbody>
<tr>
<td width="8%">
<p><strong>1.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong><strong>&nbsp;</strong></p>
</td>
<td width="23%">
<p>Electronic procurement data</p>
</td>
<td width="68%">
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Data on legal entities registered in CPP IS: object code (9 digits); code before the establishment of the Register of Legal Entities (7 digits); current name of the object; legal form code; legal status code; the date of registration of the object; date of establishment of the object (for traditional religious communities and labour organisations); date of deregistration; address of the registered office (text and address elements according to the classification of the Address Register - identifiers of the administrative unit, place of residence, street, house, premises or former number); name, surname, position title of the manager; contact details of the object (telephone, fax, e-mail address, website address);</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Data of persons using CPP IS: departments, user groups, user rights; data on natural persons registered in CPP IS: name, first letter of middle name, surname, position, e-mail address, telephone number, mobile telephone number, fax number, username, password, user role in the organisation (organisation account user, organisation account administrator);</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; unique identified of the electronic procurement &ndash; CTM number;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; basic data of electronic procurement - description; electronic procurement method; an indication of whether the electronic procurement is subdivided into lots; electronic signature setting (options: no signature or XAdES); tender assessment criteria; the number of steps in the electronic procurement procedure;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; data of recipients of notices (name and surname);</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; common Public Procurement Vocabulary (hereinafter referred to as the CPPV) data (code, name);</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; electronic procurement procedure date;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; notice place data (CVPP; CPP IS, official EU publications);</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; note whether this project refers to the EU Structural Funds;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; price presentation settings (total price; prices of purchased objects);</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; data of the electronic procurement object - components of the object, price, comments, additional documents;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; questions for suppliers - minimum qualification requirements, other questions, comments;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; electronic procurement documents;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; composition of the electronic procurement commission (names and surnames of the commission members);</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; the procedure of opening the envelopes (names, surnames, date of opening of the commission members, IP address of the commission member);</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; assessment of tenders;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; data on contract award settings (supplier`s name, price);</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; tender data: answers to questions, documents, tender price data (price, currency), electronic certificate data (name, surname, e-mail address, name of the unit of the organisation, name of the organisation, country, term of validity of the certificate, serial number of the certificate);</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; details of correspondence between the contracting authority and the supplier: notice number, subject, sender, date; notice, attached documents;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; electronic procurement audit data: date, time, type of action, details of the subject of the action (name and surname of the internal user of the organisation).</p>
</td>
</tr>
<tr>
<td width="8%">
<p><strong>2.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong><strong>&nbsp;</strong></p>
</td>
<td width="23%">
<p>Data on simplified public procurement rules, electronic procurement notices, reports and public procurement contracts</p>
</td>
<td width="68%">
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; details of simplified procurement rules: name of the contracting authority, code of the contracting authority, title of the rules, description, files, date of receipt, date of publication, date of validity, reason for cancellation;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; data on electronic procurement notice forms established in the Law on Public Procurement, the Law on Public Procurement in the Field of Defence and Security, the Law on the Energy Resources Market and by-laws, approved by Commission Implementing Regulation (EU) 2015/1986 of 11 November 2015 establishing standard forms for the publication of notices in the field of public procurement and repealing Implementing Regulation (EU) No 842/2011, Order No 1S-178 of the Director of the Public Procurement Office 2015 October 30 by order no.&nbsp; &ldquo;On Approval of the Description of the Procedure for Preparation and Submission of Notices on Procurement of Energy or Fuel Needed for the Generation of Electricity and Heat Energy&rdquo;:</p>
<p>o&nbsp;&nbsp;&nbsp; simplified procurement notice;</p>
<p>o&nbsp;&nbsp;&nbsp; procurement notices;</p>
<p>o&nbsp;&nbsp;&nbsp; project competition notices;</p>
<p>o&nbsp;&nbsp;&nbsp; advance notices;</p>
<p>o&nbsp;&nbsp;&nbsp; changes of notices;</p>
<p>o&nbsp;&nbsp;&nbsp; cancellation of notices;</p>
<p>o&nbsp;&nbsp;&nbsp; contract award notices;</p>
<p>o&nbsp;&nbsp;&nbsp; notices about the results of the project competition;</p>
<p>o&nbsp;&nbsp;&nbsp; qualification systems;</p>
<p>o&nbsp;&nbsp;&nbsp; buyer profile notices;</p>
<p>o&nbsp;&nbsp;&nbsp; work concessions;</p>
<p>o&nbsp;&nbsp;&nbsp; notices of changes and cancellations;</p>
<p>o&nbsp;&nbsp;&nbsp; information messages;</p>
<p>o&nbsp;&nbsp;&nbsp; a report on voluntary ex-ante transparency;</p>
<p>o&nbsp;&nbsp;&nbsp; subcontracting notices;</p>
<p>o&nbsp;&nbsp;&nbsp; fuel notice of energy companies;</p>
<p>o&nbsp;&nbsp;&nbsp; advance fuel notice of the energy company;</p>
<p>o&nbsp;&nbsp;&nbsp; personal data processed in notices: name, surname.</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Data of electronic procurement reports established in the Law on Public Procurement, the Law on Public Procurement in the Field of Defence and Security, the Law on the Energy Resources Market and by-laws, approved by Order No 1S-152 of the Director of the Public Procurement Office of 20 October 2010 &ldquo;On declaration Order No 1S-53 of the Director of the Public Procurement Office of 14 April 2010 &ldquo;On amendment of Order No 1S-4 of the Director of the Public Procurement Office under the Government of the Republic of Lithuania of 19 January 2006 &ldquo;On approval of the description of the procedure on preparation and submission of procurement reports and forms of public procurement reports&ldquo; null and void&rdquo;, Order No 1S-250&nbsp; of the Director of the Public Procurement Office of 17 December 2013 &ldquo;On the approval of the description of the procedure for preparation and submission of reports on public procurement in the field of defence and security&rdquo;, Order No 1S-179 of the Director of the Public Procurement Office of 30 October 2015 &ldquo;On approval of the Description of the Procedure for Preparation and Submission of the Report on Procurement Procedures for Energy or Fuel Needed for the Generation of Electricity and Heat Energy&rdquo;:</p>
<p>o&nbsp;&nbsp;&nbsp; reports on public procurement procedures in the field of defence and security;</p>
<p>o&nbsp;&nbsp;&nbsp; reports on public procurement contracts completed or terminated in the field of defence and security procurement;</p>
<p>o&nbsp;&nbsp;&nbsp; public procurement reports for procurements in the field of defence and security;</p>
<p>o&nbsp;&nbsp;&nbsp; a description of the procedures for preparing and submitting reports on public procurement in the field of defence and security;</p>
<p>o&nbsp;&nbsp;&nbsp; reports on public procurement procedures;</p>
<p>o&nbsp;&nbsp;&nbsp; reports on project tender procedures;</p>
<p>o&nbsp;&nbsp;&nbsp; completed or terminated procurement contract reports;</p>
<p>o&nbsp;&nbsp;&nbsp; public procurement reports;</p>
<p>o&nbsp;&nbsp;&nbsp; reports on procurement procedures for energy or fuel required for the generation of electricity and heat energy;</p>
<p>o&nbsp;&nbsp;&nbsp; personal data processed in the reports: name, surname.</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Data on contracts - the link with the public procurement, the successful tender, the concluded contract and changes to the terms of the procurement contract (specify what is included in the uploaded contract):</p>
<p>o&nbsp;&nbsp;&nbsp; contracts awarded for cross-border and simplified procurement subject to reporting on procurement procedures;</p>
<p>o&nbsp;&nbsp;&nbsp; contracts for low value purchases;</p>
<p>o&nbsp;&nbsp;&nbsp; main contracts awarded on the basis of framework contracts;</p>
<p>o&nbsp;&nbsp;&nbsp; contracts concluded in accordance with Article 85 (6) of the Law on Public Procurement;</p>
<p>o&nbsp;&nbsp;&nbsp; contract amendments.</p>
</td>
</tr>
<tr>
<td width="8%">
<p><strong>3.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong><strong>&nbsp;</strong></p>
</td>
<td width="23%">
<p>CTM classifiers</p>
</td>
<td width="68%">
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; list of electronic procurement method templates;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; CPPV code classifier;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; message template classifier;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; classifier of qualification issues;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; work list classifier;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; classifier of Articles of the Law on Public Procurement;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; classifier of electronic procurement methods;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; list of type codes of contracting authorities;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; classifier of the Common Public Procurement Vocabulary;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; classifier of economic activities;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; list of service categories;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; classifier of product types;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; classifier of types of work;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; country classifier;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; currency classifier;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; time zone classifier;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; classifier of the field of activity;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; language classifier.</p>
</td>
</tr>
<tr>
<td width="8%">
<p><strong>4.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong><strong>&nbsp;</strong></p>
</td>
<td width="23%">
<p>Data for publication</p>
</td>
<td width="68%">
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; name of the procurement;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; type of notice;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; name of the organisation;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; date of publication;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; in accordance with the provisions of the LLPPD, information on suppliers who failed to perform or improperly performed the procurement contract is published when the procurement contract has been terminated due to a material breach of the contract, as defined in the Civil Code of the Republic of Lithuania (hereinafter - material breach of the contract) or when a court decision satisfying the Executor`s requirements to declare non-performance or improper performance of the procurement contract and indemnification of the related losses comes into force (date of data entry, date of the term of three years during which the supplier is in list of unreliable suppliers, name of the contracting authority, name of responsible person, name of supplier, supplier`s (legal entity`s) code, name of the procurement object, type, code according to CPPV, procurement number, procurement contract index, date of termination of the procurement contract or effective date of the court decision, reasons for termination of the procurement contract, documents conforming the breach);</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; list of officially approved suppliers is published in accordance with the provisions of the LLPPD (serial number, group of economic operators, name, code, date of listing, date of validity of the certificate, certificate number);</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; CVPP subscription for data from the network (RSS subscription);</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; judgments / decrees are published in accordance with the provisions of the LLPPD (digital copies of documents);</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; list of companies specified in Article 91 of the Law on Public Procurement;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; information: news, links, statistics, useful information;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; consents to negotiations without publication;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; data on the contracting authority: organisation code, organisation name, organisation address, telephone number, organisation type code;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; data on the electronic procurement object: object code, object name; description of the lots of the procurement object;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; data on the method of public procurement: method of procurement; Article, paragraph, item of the Law on Public Procurement, according to which the method of electronic procurement was chosen; number and date of the resolution of the Government of the Republic of Lithuania on the consent to apply the chosen public procurement method;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; data on public procurement funds: code of procurement funds;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; details of the award of public contracts: date of the decision on the successful tender; concluded contracts - description of the lots of the procurement object, names of suppliers (Executors), dates of concluding contracts, prices specified in the contracts; non-concluded contracts - lot numbers of the procurement object, reasons;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; supplier details: supplier code; name of the supplier; supplier`s address, telephone number, fax, e-mail address;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &bull; data on the procurement documents submitted by the contracting authority: description - a brief description of the procurement document; specific file (attached to the procurement document file);</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &bull; news data: headline; date of publication; a brief description of the news; news content;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &bull; details of the supplier`s representative: name, surname; e-mail address; workplace telephone number; workplace internet address; Username; user password.</p>
</td>
</tr>
<tr>
<td width="8%">
<p><strong>5.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong><strong>&nbsp;</strong></p>
</td>
<td width="23%">
<p>Invoice data</p>
</td>
<td width="68%">
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; the series and number of the credit and debit document and the advance invoice; date of issue of the VAT invoice, credit and debit document and advance invoice; seller (seller`s legal entity code, seller`s name, seller`s address, VAT payer`s code); buyer (buyer`s legal entity code, buyer`s name, buyer`s address, VAT payer`s code); contract number; contract identifier; goods or services (name, quantity, price per unit of the supplied goods or services (excluding VAT), VAT rate (rates) and code (codes), VAT amount), amount; currency</p>
</td>
</tr>
<tr>
<td width="8%">
<p><strong>6.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong><strong>&nbsp;</strong></p>
</td>
<td width="23%">
<p>Data received from the European Union Structural Assistance Subsystem for 2007-2013</p>
</td>
<td width="68%">
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Project Code, Operational Program Code, Priority Code, Measure Code, Project Name, Project Executor Name, Project Executor Code, Implementing Agency, Intermediate Authority Name, Funding Value, Project Cost Value, Project financing and administration agreement effective date, Project activities implementation commencement date, Project activities implementation completion date, Project stage, Project status, Partner name, Partner code, Suspicion identification SFMIS code, Project code, Suspicion registration date, Suspicion investigation status (0 - in progress, 1 - completed), Suspicion investigation completion date, Description of the suspicion, Is an offence found? (0 - no, 1 - yes), Offence identification SFMIS code, Offence unique code, Offence detection date, Offence type code (classification in the system), Offence additional type code (classification in the system).</p>
</td>
</tr>
<tr>
<td width="8%">
<p><strong>7.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong><strong>&nbsp;</strong></p>
</td>
<td width="23%">
<p>Data received from European Union Structural Funds for 2014-2020</p>
</td>
<td width="68%">
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; user data (SFMIS username, date of removal, user status, name, surname, institution, position, telephone number, e-mail, Project Code, Operational Program Code, Priority Code, Measure Code, Project Name, Project Executor Name, Project Executor Code, Implementing Agency, Intermediate Authority Name, Funding Value, Project Cost Value, Project financing and administration agreement effective date, Project activities implementation commencement date, Project activities implementation completion date, Project stage, Project status, Partner name, Partner code, Suspicion identification SFMIS code, Project code, Suspicion registration date, Suspicion investigation status (0 - in progress, 1 - completed), Suspicion investigation completion date, Description of the suspicion, Is an offence found? (0 - no, 1 - yes), Offence identification SFMIS code, Offence unique code, Offence detection date, Offence type code (classification in the system), Offence additional type code (classification in the system).</p>
</td>
</tr>
</tbody>
</table>

### DATA PROVISION AND USE

The data available and provided to CPP IS user according to access authorisation are described in Table 6.

_Table 6. Data available/provided to CPP IS users_

No | CPP IS users | Provided information/data
-- | -- | --
1. | PPO employees | All data provided in Table 5 according to access authorisation.
2. | Public | Data for CPP IS publication specified in row 4 of   Table 5.
3. | Executors of the   procurement | Data for CPP IS publication specified in row 4 of   Table 5 and data on simplified public procurement rules,   electronic procurement notices, reports and public procurement contracts   specified in row 2 of Table 5 and electronic procurement data specified in row 1   of Table 5 according to access authorisation.
4. | Implementing Agencies | Data for CPP IS publication specified in row 4 of   Table 5 and data on simplified public procurement rules,   electronic procurement notices, reports and public procurement contracts   specified in row 2 of Table 5 and electronic procurement data specified in row 1   of Table 5 according to access authorisation.
5. | Supervisory Agencies | All data provided in Table 5.
6. | Suppliers | Data for CPP IS publication specified in row 4 of   Table 5 and data on simplified public procurement rules,   electronic procurement notices, reports and public procurement contracts   specified in row 2 of Table 5 and electronic procurement data specified in row 1   of Table 5 according to access authorisation.

### NON-FUNCTIONAL REQUIREMENTS

####	Security and confidentiality requirements 
Priority directions of CPP IS electronic information security:
•	CPP IS must be upgraded in accordance with the security requirements of the specified legal acts applicable to CPP IS, the importance of the information processed by CPP IS and the category of CPP IS for information systems;
•	CPP IS must ensure security at the application level, database level, network level, hardware level; 
•	CPP IS must be protected from vulnerabilities published in the “OWASP Top Ten Project”, which periodically analyses and publishes ten most critical vulnerabilities found in web-based applications. Prior to the start of the test run, the installer will be required to provide a declaration stating that the application has been tested for the most critical vulnerabilities published in “OWASP Top Ten Project”;
•	CPP IS must provide protection against malicious code loading into the application (for example, limited ability to upload files with extensions .com, .exe, .bat, etc.);
•	CPP IS connection to workstations (web browsers and / or applications) must be encrypted using SSL (Secure Socket Layer) or other equivalent encryption tools:
o	The installer must provide and install SSL certificates that are trusted by web browsers;
o	and depending on CPP IS architecture, the Installer must provide the required number of certificates to encrypt the transferred / received information;
o	the certificate used for encryption must be confirmed by a qualified certificate (for example: Veri Sign or similar), which can be verified automatically by popular web browsers, i.e. the workstation user does not need to self-add the certificate to the browser or operating system`s trusted certificate store;
•	Users logging in to CPP IS authorized user domains must be protected against unauthorized access, i.e. these domains can only be accessed by properly identified, authenticated and authorized users (as described in the functional requirements of this specification).

####	Ergonomic requirements

CPP IS user interface shall meet the following ergonomic requirements:
•	The installer must design CPP IS using best UX (User experience) and UI (User interface) practices in order to make the user interface as intuitive and understandable as possible, avoiding any unnecessary actions. The user interface of CPP IS must be developed in accordance with the methodological document of the user-friendliness of public administrative electronic services "Guidelines for Solving Eligibility Problems".
•	3 different versions of CPP IS external and internal portal design sketches with information display examples for different types of device screens must be submitted to PPO for assessment.
•	Once one version of the design sketch has been agreed with the PPO, the Installer must create a prototype (for example, using https://www.axure.com/) and get feedback from the PPO and other interested parties (at least 20 users) before developing the new design (surveys, interviews, etc.). The opinion of users must be considered when designing the user interface. Meetings, surveys must be documented and submitted to the PPO.
•	During the test run, the Installer will have to make all changes to the user interface specified by the PPO, without deviating from the harmonized design, if required.
•	User interface of CPP IS components must be accessible via a web browser (exceptions may apply to standard licensed software, if provided (for example, reporting and statistics software, database administration software, etc.)).
•	CPP IS external portal must be constructed according to the principles of “responsive web design”. The detailed analysis must determine which CPP IS functions are to be available using mobile devices (lower resolution screens) and which are to be available using a computer (higher resolution screens).
•	CPP IS components accessible via a web browser must function in the same way and be displayed in the PPO agreed web browsers. Preliminary CPP IS must function in the latest versions of these web browsers:
o	Microsoft Internet Explorer / Edge;
o	Mozilla Firefox;
o	Safari;
o	Google Chrome.
•	User interface of CPP IS external portal designed for the public must be in Lithuanian and English (including classifiers and related components (for example, English version of SIPIR portal must be provided when logging in or making payments)). The user interface of the internal portal for the PPO personnel must be in Lithuanian. The language must be used in accordance with the general rules of the Lithuanian language. Software designed for CPP IS administrators (for example, Administration application) and messages must be in Lithuanian or English.
•	User interface error messages must be worded in such a way that it is clear to the user what has happened and what further action he needs to take in order to continue working.
•	The installer must ensure the correct operation of CPP IS by accurately processing and saving the data entered in Lithuanian.
•	CPP IS user interface must be intuitive, understandable and easy to use for users with the required level of computer literacy (ECDL or higher) and meet modern ergonomic requirements. 
•	CPP IS content, in the context of the implementation of the Web Content Accessibility Guidelines (WCAG), must be presented in a form that allows hearing and visually impaired people to use CPP IS functionalities freely. In order to ensure access to film content for the hearing impaired people, modification of CPP IS must include measures to transcribe films hosted by the CPP IS and to provide CPP IS users with films with the option to display or turn off subtitles. For this purpose, the IT solution “Lithuanian Phonograms Automatic Text Transcription Service” must be used, which is designed to automatically decode the text encoded in the sound source of a continuous, freely formulated speech. The service provider will have to set up automatic means to obtain a transcript of the film stored in the CPP IS database and to link it to a specific film stored in the database and E-KINE. If the format of the transcription received from the IT solution “Lithuanian Phonograms Automatic Text Transcription Service” does not comply with WebVTT or an equivalent format, the Service Provider will have to create automatic means to convert the received transcription to WebVTT or an equivalent format suitable for displaying transcripts when watching films.
•	The user interface of CPP IS components accessible through a web browser must comply with the W3C XHTML or equivalent specification and must use at least 1.0 W3C XHTML or equivalent. At least Level 2.1 CSS2 or equivalent technology must be used for implementation (Cascading Style Sheets Language 2 Revision 1, www.w3.org/Style/CSS/).
•	E-KINE for film playback and interactive control (resolution selection, subtitle on, subtitle language selection, audio track selection, play, pause, rewind, desired film location selection, audio, mute, full screen expansion, video compression) HTML5, Media Source Extensions, WebVTT or equivalent technology, DASH or equivalent protocol must be used.
•	User interface control must be based on mouse and keyboard device.
•	User-friendly functionality must be implemented:
o	online data search tools;
o	TAB key sequence when going through data entry fields;
o	providing hints and explanations when the mouse pointer is hovered over the graphic object;
o	automatic saving of entered data when changing active windows, fields or when a user session is terminated;
o	in the data entry forms, the data fields must be filled in automatically if the relevant data is stored in CPP IS;
o	User interface elements that cannot be used according to the logic implemented in CPP IS must be marked inactive and / or hidden;
o	fields where a lot of text has been entered should only display part of the text with the option to expand the hidden text. It must be possible to administer how much text is to be displayed, depending on where in CPP IS that field is displayed.
•	Data lists should be:
o	paged, with the option to specify how many rows to display on the list page. One can return to the previous page using the browser`s “Back” button. When one enters and returns to a selected list object from a specific data list page, the same data list page from which one went to the selected list object must be displayed;
o	filtered according to criteria relevant to the list. The installer, after a year of detailed analysis, will need to identify the filtering criteria for each list and implement them;
o	sorted by the items to be sorted in the list;
o	exported to files (.pdf, .docx, .xlxs, or equivalent). A detailed analysis must determine which lists need the latter function;
o	open in print mode. The detailed analysis must determine which lists and forms require the latter status;
o	data consisting of Lithuanian characters must be sorted according to the Lithuanian alphabet.
•	For the records created by CPP IS, the functions of editing, deleting and cancelling those records must be available.
•	Longer processes (functions) must be indicated in CPP IS so that it is clear to the user that CPP IS is working and there is no need to call the same functions several times. If the process is such that it is necessary to wait for CPP IS to process the required data in order to continue, then the user must be restricted from initiating further actions, unless the user initiates a longer process cancellation in a message indicating that the process may take time.
•	Requirements for information of users:
o	The messages sent to the CPP IS user must be worded in such a way that the user would understand the reason for the message. Information on the reason for the message must be provided by specifying specific CPP IS data objects (for example, field names);
o	the error message sent to the user must specify the actions that the user must take in order to eliminate the reasons for the message and to continue working with CPP IS;
o	the user must be provided with success messages indicating that the actions taken by the user are successful (for example, information that the record has been saved / deleted / modified, data has been successfully uploaded, etc.);
o	error messages, success messages and informational messages must be highlighted in different colours or with different symbols to be distinguished visually;
o	if the results of the action taken by the user will have a significant impact, CPP IS must send a notification and ask the user to confirm that the action is indeed intended before the action is taken.
•	The user must be provided with aids to help him learn to use CPP IS more quickly (for example, help buttons, user manual). 
•	The data entry fields in the user interface must have data validation rules and check the correctness of the input data logic. Fields and field validation rules shall be agreed with the Contracting Authority during the detailed analysis and design phases. Preliminary will have to be:
o	the required input data is checked;
o	verification of data format (date, number, text or other established rules);
o	checking of file extensions and sizes;
o	logical check is performed between the form elements - the selection (input) of one form element must enable / disable other form elements and perform other actions that will have to be agreed with the Contracting Authority.
•	CPP IS must ensure that the data conforms to the defined data model (“validation”) and the integrity of the data. These control means must ensure the compatibility and integrity of the data entered, processed or deleted manually or automatically. When trying to perform an unauthorized action, such as failing to complete a required field or providing data that is inconsistent with a specified data type, control measures shall generate and provide informative system messages to the CPP IS user.

#### 	Requirements for compliance with international and good practice standards
CPP IS complies with the following international and good practice standards:  
•	ODBC (Open Database Connectivity) or JDBC (Java Database Connectivity) or equivalent application programming interface (API) for connecting to databases.
•	Simple Object Access Protocol (SOAP) (www.w3.org/TR/soap/) v1.1.
•	Web Services Description Language (WSDL) (http://www.w3.org/TR/wsdl) ir equivalent.
•	Simple Mail Transfer Protocol (SMTP) (http://tools.ietf.org/html/rfc821).
•	Web Services Interoperability (WS-I) (http://www.ws-i.org/) or equivalent standards and specifications must be used.
•	SSL (Secure Sockets Layer) or an equivalent cryptographic protocol must be used to secure the information transmitted over the Internet in the following communication scenarios: system-user and system-system.
•	Web Services Security (WS-Security) (www.oasis-open.org/committees/wss/) or equivalent standards and specifications must be used.  
•	To ensure the security and reliability of CPP IS data exchange, web services implemented in CPP IS must use WS- * standards groups or equivalent protocols such as: WS-Security, WS-Secure Conversation, WS-Security Policy, WS-Metadata Exchange, WS-Trust, WS-Atomic Transaction, WS-Reliable Messaging.

#### 	Requirements for technical means, performance characteristics, additional software, implementation technologies
Requirements for CPP IS architecture:
•	Architectural solution must ensure high availability of CPP IS, which can be implemented with the functionality of operating systems, hardware capabilities or other software. High availability must be achieved at the application level, integration level, and data level.
•	High availability solutions must work automatically (in case of incidents). Human intervention may only be required to restore the operation of CPP IS to the state it was in before the incident.
•	High availability solution must be described in the design document and approved by the PPO.
•	The installer must propose and agree with the PPO backup processes, tools and rules.
•	CPP IS must allow data to be restored from backup data. The Installer must propose and agree with the Contracting Authority the processes, means and rules for restoring backups.
•	CPP IS must comply with the principle of scalability, i.e. it must be possible to increase the capacity of the system by adding hardware and / or increasing the capacity of existing equipment and without changing the source code of the software, the software must not be a limiting factor in increasing performance.
•	Solutions for monitoring the operation of the system and its components and for early warning must be implemented. Users with system administrator authorisation must be able to monitor the performance of the system and its individual components (active users, memory usage, CPU load and other important indicators) by web means and receive messages when components fail or when critical values are reached.
•	Measures must be implemented to ensure centralized collection of logs from all components created by the system.
•	The implementation of CPP IS solution must be focused on compliance (compatibility) with open but reliable standards.
•	During CPP IS installation, one must follow the guidelines for the use of open electronic document standards.
•	Open formats must be used to provide information, i.e. officially registered international file standards (for example, HTML, PDF / A, PDF, ADOC, TIFF, JPEG, PNG, ODF formats, OOXML formats, XML, etc.).

Requirements for speed:
•	CPP IS installation must ensure that when 500 users work with CPP IS (performing information searching, viewing, insertion, modification, deletion and other operations, the execution time of which does not depend on the interfaces with external systems) simultaneously and each of them performs random action every 5 seconds, the response in the browser should not exceed 2 seconds. There may be exceptional cases that need to be agreed with the PPO (for example, report generation, actions including requests and responses from third country systems, etc.).
•	Installation of network interfaces (WS or RESTful) must ensure that the integration scenarios defined during the design will take place within a rational time frame and will not in any way negatively affect the ease of use and performance of CPP IS.
•	During the acceptance testing phase (or at another agreed time), the Installer must provide all necessary facilities to the PPO specialists to carry out performance and speed testing. If necessary, the Installer will have to perform the configuration or programming work that will be necessary to test the performance of CPP IS in various scenarios of its use. 
•	The Installer will have to carry out the necessary CPP IS programming and / or configuration works, considering the results of performance and speed tests performed by the PPO specialists, if the test results do not meet the performance and speed requirements specified above.

Requirements for CPP IS data optimisation:
•	CPP IS data in the database must be indexed to ensure the speed of request processing.
•	CPP IS databases must be normalized, data structure must be clearly defined, data integrity constraints must be established;
•	During the analysis and design, the Installer will have to determine for which CPP IS data compression solutions must be used and implement them, ensuring CPP IS speed.

Requirements for CPP IS licenses:
•	Commercial Off-The-Shelf Software (application servers, monitoring software, reporting software, programming frameworks, content management systems, etc.) provided by the Installer, which is required for CPP IS operation, must be provided with all necessary licenses (if licensed) so that the PPO would not need to acquire additional licenses (or otherwise incur costs) for the operation of the software for at least 3 years.
•	Licensed software must have manufacturer support for the period of at least 3 years: downloading and installing updates, introducing new components.
•	If the offered software is licensed depending on the number of users (people or systems) using the system, server parameters, etc., then the Installer must provide licenses to ensure the rational and efficient operation and use of CPP IS in 3 year perspective.
•	All costs of the required software must be included in the tender.
•	All necessary licenses must be obtained on behalf of the PPO. All licenses required for the operation of the CPP IS must be provided to the PPO. The licenses (and certificates) provided must be valid no earlier than the start of the pilot phase and no later than the start of the after-sales phase.

#### 	Requirements for technical documentation

The Installer will have to prepare the following documentation: Service Provision Regulation, sign Handover Certificate for the first stage, Detailed Analysis Document, Design Document, Integration Interface Specification (s), Internal Test Report, Acceptance Test Scenario and Test Methodology Plan, User Manual, Administration Manual , training plan, training materials, warranty procedure documents, interim and final reports.
All documents prepared by the Installer will have to be agreed with the PPO. Detailed principles of document coordination will have to be presented and harmonized in the project implementation regulation prepared by the Installer. 
Requirements for result provision and agreement terms:  
1.	The exact deadline for the submission of documents must be agreed in the Service Provision Regulation. All documents for the stage must be submitted and agreed with the PPO by the stage end date. All documents must be updated and agreed by the date of signing the final CPP IS Handover Certificate.
2.	When fulfilling the obligation to agree the document within the specified term, the Installer must consider the deadlines for agreement of documents and his ability to correct the documents according to the comments. The PPO undertakes to comment on the documents submitted for harmonization within the following terms:
2.1.	Document with up to 100 pages:  
2.1.1.	First revision – within 8 business days, 
2.1.2.	Document revision after elimination of comments – within 5 business days,
2.2.	Document with more than 100 pages: 
2.2.1.	First revision – within 10 business days, 
2.2.2.	Document revision after elimination of comments – within 8 business days.
3.	The results of the Installer are coordinated with the PPO in no more than 2 (two) iterations. 
4.	The PPO shall have the right to refuse to provide comments on the first version of the document within the terms set for harmonization if it is not suitable for harmonization and comments:
4.1.	The document does not cover the entire volume vertically, i.e. all necessary sections and parts of such a document have not been provided;
4.2.	The document does not cover the entire scope horizontally, i.e. the document does not cover all CPP IS modules or functions that must be included in this document. 
5.	If the PPO refused to provide comments on the document, the document shall be deemed not to have been submitted for harmonization and comments.
6.	Documents agreed with the PPO must (may) be amended at a later stage if changes are made to the information system under development, considering the results of acceptance testing and trial operation, other project activities and circumstances related to the content of the submitted documentation. The project documentation must be updated, and the final versions must be submitted before the end of the CPP IS acceptance stage (signing of Final CPP IS Handover Certificate).
7.	The final versions of the documents must be submitted electronically (in MS Word or another editable format agreed with the PPO by recording the document (s) on CD, DVD or other digital medium).
8.	Preliminary (design) versions must be submitted in electronic format by electronic means. Comments and corrections in draft documents must be provided with the track changes and commenting functions of the MS Office software package (or equivalent). Versioning (version control) of submitted documents must be performed.

#### 	Requirements for CPP IS user training 

The Installer must train future users to operate CPP IS according to a procedure and order agreed in the training plan. 
At least 25 users must be trained to use the CPP IS, including:
•	At least 5 CPP IS Administrators;
•	At least 20 PPO employees. 

The Installer must agree with the PPO on the exact number of participants in the training and indicate this in the training plan.
•	The PPO is responsible for the location of the training, and the Installer is responsible for the development of training materials and tools.
•	The Installer must prepare instructions for using CPP IS and instructions for administering CPP IS.
•	Users must be trained to use upgraded / created CPP IS functionalities. Detailed training fields will need to be agreed upon by the Installer when preparing the training plan and materials.
•	Training must be completed before the beginning of the trial run. 
