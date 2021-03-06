# TelstraWombat
SWEN90009 Team Wombat

## Table of Contents:

<a href="#Intro">Introduction</a><br>
<a href="#Description">Product Description</a><br>
<a href="#Links">Key Links</a><br>
<a href="#Structure">Folder Structure</a><br>
<a href="#Changelog">Changelog</a><br>
<a href="#Matrix">Traceability Matrix</a><br>

<h2 id="Intro">Introduction:</h2>

At Telstra, large and varied data sets are used to detect security threats and anomalies. The data, generated from multiple technologies and vendors, come in different shapes and forms, as a result of different naming conventions, configurations, logging standards or simply different file formats. For example, with NGFW (next generation firewall data) there exists a number of vendors in this space (e.g. Palo Alto, Cisco, Fortinet, ...) with each having different log formats of similar data. Hence, before the data can be used for analysis, it must be normalized to extract common fields and convert data into a standard format. This process requires human effort to understand the logs and map them to common schema manually, which is not only time consuming but is also prone to human error. A more scientific and consistent approach to the problem is needed.



In this project, students will be researching, experimenting, designing and assessing different data normalization approaches that are used in the industry & research, subsequently designing and implementing a smart tool that automates or semi-automates the data extraction and normalization process.  

<h2 id="Description">Product Description:</h2>

Team Wombat created a tool that simplifies the process of normalising log data, by providing a UI that assists in the creation of regular expressions for unstructured files, suggesting column types for structured files and a central repository for these data normalisation efforts to reduce redudant work.


<h2 id="Links">Key Links:</h2>

- High Fidelity Prototype: https://www.figma.com/file/CtGsgE63wCEwT7mReOemoP/Log-Normalisation-Tool?node-id=0%3A1
- User Story Map: https://miro.com/app/board/o9J_lIQx0X4=/

<h2 id="Structure">Folder Structure:</h2>

- data samples: Contains the data samples used in the digital prototype
  * [Data Sources.pdf](data%20samples/Data%20Sources.pdf): A file listing the data used in our prototype and their origins
  * [structured_data.csv](data%20samples/structured_data.csv): structured_data.csv: A data file containing the structured data used in our prototype
  * [unstructured_data.log](data%20samples/unstructured_data.log): A data file containing the unstructured data used in our prototype
- docs: Contains all product and requirement elicitation documentation files
  * [Do Be Feel Table.pdf](docs/Do%20Be%20Feel%20Table.pdf): A table that summarises the goals of the product based on client expectations
  * [Goal Model.png](docs/Goal%20Model.png): Image of a motivational model which helps to visualise the design thinking based on the goals
  * [Paper Prototype - Task scenarios + Feedback.pdf](docs/Paper%20Prototype%20-%20Task%20scenarios%20+%20Feedback.pdf): File which includes the task scenarios used to walk through the digital prototype with the client. Also includes client feedback
  * [Personas.pdf](docs/Personas.pdf): Contains the process of constructing personas, persona definitions, and our final created persona images
  * [Project Overview.pdf](docs/Project%20Overview.pdf): Overview of the problem, system as-is, and scope of the solution
  * [Requirements Elicitation.pdf](docs/Requirements%20Elicitation.pdf): The documentation for an initial interview conducted with the client. Contains details on the interview strategy and consequent Q&A
  * [User Journey Map.pdf](docs/User%20Journey%20Map.pdf): A visualisation of the journey through two user story 'epics'
  * [User Stories List.pdf](docs/User%20Stories%20List.pdf): List of all user stories for the system
  * [User Story Map.pdf](docs/User%20Story%20Map.pdf): A roadmap for development created by splitting up user stories into sprints
  * [Final Presentation.pdf](docs/Final%20Presentation.pdf): The slides for our final presentation delivered to the client
- tests: Contains Acceptance Tests, Acceptance Criterion, Traceability Matrix
  * [User Story Acceptance Criteria.pdf](tests/User%20Story%20Acceptance%20Criteria.pdf): Contain the acceptance criteria fo every user story listed in the user story list
  * [User Story Acceptance Tests.pdf](tests/User%20Story%20Acceptance%20Tests.pdf): Contain the acceptance tests for each user story listed in the user story list
  * [Traceability Matrix.pdf](tests/Traceability%20Matrix.pdf): Contains the traceability matrix mapping each acceptance criteria to the associated acceptance test
- prototypes/low fidelity: Contains files for the paper prototype
  * [Paper Prototype.pdf](prototypes/low%20fidelity/Paper%20Prototype.pdf): Contain the paper prototype design pages exported from Figma
  * [Paper Prototype.fig](prototypes/low%20fidelity/Paper%20Prototype.fig): Contains the Figma files for the paper prototype, to open this, import it to Figma on your web browser
- prototypes/high fidelity: Contains files for the digital prototype
  * [Digital Prototype.pdf](prototypes/high%20fidelity/Digital%20Prototype.pdf): Contain the digital prototype design pages exported from Figma
  * [Digital Prototype.fig](prototypes/high%20fidelity/Digital%20Prototype.fig): Contains the Figma files for the digital prototype, to open this, import it to Figma on your web browser
- ui: Contains images and assets used for the digital prototype, including moodboard
  * [Components - Assets.pdf](ui/Components%20-%20Assets.pdf): A file listing the components used in the digital prototype
  * [Moodboard 1 - Classic Telstra Colours.pdf](ui/Moodboard%201%20-%20Classic%20Telstra%20Colours.pdf): Moodboard based on the main blue Telstra logo 
  * [Moodboard 2 - Classic Computers Colours.png](ui/Moodboard%202%20-%20Classic%20Computers%20Colours.png): Moodboard based on a more retro computer theme
  * [Moodboard 3 - Green Telstra Colours.pdf](ui/Moodboard%203%20-%20Green%20Telstra%20Colours.pdf): Moodboard based on one of the alternative colours the Telstra logo appears in 
  * [Moodboard.pdf](ui/Moodboard.pdf): Contains all three Moodboards presented to the client

<h2 id="Changelog">Changelog:</h2>

**Sprint 1**:
- Project Overview
- Requirements Elicitation

**Sprint 2**:
- Do/Be/Feel Table
- Goal Model
- Personas

**Sprint 3**:
 - User Stories
 - Paper Prototypes

**Sprint 4**:
 - Acceptance Criterion
 - Acceptance Tests
 - Traceability Matrix
 - High Fidelity Prototype
 - Moodboard

**Sprint 5**:
- Product Handover

<h2 id="Matrix">Traceability Matrix:</h2>

[Traceability Matrix.pdf](tests/Traceability%20Matrix.pdf): Contains the traceability matrix mapping each acceptance criteria to the associated acceptance test
