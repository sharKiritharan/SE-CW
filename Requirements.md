# Requirements
Listed below are both functional and non-functional requirements that we should aim to meet by the end of this project. 
The formatting follows: <br>
&ensp;&ensp;An identifying value, and title<br>
&ensp;&ensp;A description of the requirement, why it is needed<br>
&ensp;&ensp;If it depends on any other requirements as a pre-requisite<br>

## Functional Requirements 
**FR1.1** Report Generation <br>
**DESC:** The system must be able to create reports for countries, cities, and city capitals based on given criteria, such as region.<br>
**DEP:** None<br>
<br>
**FR1.2** Data Accessibility<br>
**DESC:** Users should be able to access information on population stats at different levels, of world, continent, region, country, district and city.<br>
**DEP:** None<br>
<br>
**FR1.3** Language Population<br>
**DESC:** The system must be able to provide information about the number of speakers of a language, and what percentage of the world population they make up.<br>
**DEP:** None<br>
<br>
**FR1.4** Adding Data<br>
**DESC:** Users should be able to edit information to the database, eg, adding or removing data.<br>
**DEP:** None<br>
<br>
**FR1.5** Security Measures<br>
**DESC:** THe system should provide a login to ensure secure access of data.<br>
**DEP:** None<br>

## Non-Functional Requirements
**NFR1.1** Performance <br>
**DESC:** The sysytem should be able to generate reports efficiently, and responsively, even with a large dataset. Retrieval must be optimised for speed and scalability<br>
**DEP:** FR1.1 <br>
<br>
**NFR1.2** Usability <br>
**DESC:** The user interface should be intuitive, and easy to navigate. It should cater to all users, regardless of technical background, and any potential visual or 
physical disabilities. Clear instructions and guidance must be provided for report generation and data access<br>
**DEP:** None <br>
<br>
**NFR1.3** Reliability <br>
**DESC:** The system must ensure that data is accurate, and reliable in all generated reports and statistics.  <br>
**DEP:** FR1.1<br>
<br>
**NFR1.4** Security<br>
**DESC:** User authentication must be in place to prevent unwanted access/changes to data <br>
**DEP:** None <br>
<br>
**NFR1.5** Scalability <br>
**DESC:** The system must be designed to allow for future expansion of data volume. It should not compromise performance.<br>
**DEP:** None<br>
<br>
**NFR1.6** Flexibility <br>
**DESC:** The system should be modular, and flexible to allow for changes in requirements, or the addition of future functionalities. <br>
**DEP:** None<br>
<br>
**NFR1.7** Documentation<br>
**DESC:** Documentation must be written throughout the process of developing the system. User manuals will also have to bemade, to facilitate system understanding and usage.<br>
**DEP:** None <br>
<br>
**NFR1.8** Compliance<br>
**DESC:** The system must comply with data protection regulations. Best practises for development, and database management should also be followed. <br>
**DEP:** FR1.5<br>
<br>