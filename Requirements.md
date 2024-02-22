# Requirements

Listed below are both functional and non-functional requirements that we should aim to meet by the end of this project. The formatting follows:

- An identifying value, and title
- A description of the requirement, why it is needed
- If it depends on any other requirements as a pre-requisite

## Functional Requirements

### FR1.1 Report Generation

- **DESC:** The system must be able to create reports for countries, cities, and city capitals based on given criteria, such as region.
- **DEP:** None

### FR1.2 Data Accessibility

- **DESC:** Users should be able to access information on population stats at different levels, of world, continent, region, country, district, and city.
- **DEP:** None

### FR1.3 Language Population

- **DESC:** The system must be able to provide information about the number of speakers of a language and what percentage of the world population they make up.
- **DEP:** None

### FR1.4 Adding Data

- **DESC:** Users should be able to edit information to the database, e.g., adding or removing data.
- **DEP:** None

### FR1.5 Security Measures

- **DESC:** The system should provide a login to ensure secure access to data.
- **DEP:** None

## Non-Functional Requirements

### NFR1.1 Performance

- **DESC:** The system should be able to generate reports efficiently and responsively, even with a large dataset. Retrieval must be optimized for speed and scalability.
- **DEP:** FR1.1

### NFR1.2 Usability

- **DESC:** The user interface should be intuitive and easy to navigate. It should cater to all users, regardless of technical background, and any potential visual or physical disabilities. Clear instructions and guidance must be provided for report generation and data access.
- **DEP:** None

### NFR1.3 Reliability

- **DESC:** The system must ensure that data is accurate and reliable in all generated reports and statistics.
- **DEP:** FR1.1

### NFR1.4 Security

- **DESC:** User authentication must be in place to prevent unwanted access/changes to data.
- **DEP:** None

### NFR1.5 Scalability

- **DESC:** The system must be designed to allow for the future expansion of data volume. It should not compromise performance.
- **DEP:** None

### NFR1.6 Flexibility

- **DESC:** The system should be modular and flexible to allow for changes in requirements or the addition of future functionalities.
- **DEP:** None

### NFR1.7 Documentation

- **DESC:** Documentation must be written throughout the process of developing the system. User manuals will also have to be made to facilitate system understanding and usage.
- **DEP:** None

### NFR1.8 Compliance

- **DESC:** The system must comply with data protection regulations. Best practices for development and database management should also be followed.
- **DEP:** FR1.5
