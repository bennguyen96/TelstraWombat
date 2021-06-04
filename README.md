# TelstraWombat
SWEN90009 Team Wombat

## Table of Contents:

<a href="#Intro">Introduction</a><br>
<a href="#Description">Product Description</a><br>
<a href="#Links">Key Links</a><br>
<a href="#Structure">Folder Structure</a><br>
<a href="#Changelog">Changelog</a><br>

<h2 id="Intro">Introduction:</h2>

At Telstra, large and varied data sets are used to detect security threats and anomalies. The data, generated from multiple technologies and vendors, come in different shapes and forms, as a result of different naming conventions, configurations, logging standards or simply different file formats. For example, with NGFW (next generation firewall data) there exists a number of vendors in this space (e.g. Palo Alto, Cisco, Fortinet, ...) with each having different log formats of similar data. Hence, before the data can be used for analysis, it must be normalized to extract common fields and convert data into a standard format. This process requires human effort to understand the logs and map them to common schema manually, which is not only time consuming but is also prone to human error. A more scientific and consistent approach to the problem is needed.



In this project, students will be researching, experimenting, designing and assessing different data normalization approaches that are used in the industry & research, subsequently designing and implementing a smart tool that automates or semi-automates the data extraction and normalization process.  

<h2 id="Description">Product Description:</h2>

Team Wombat created a tool that simplifies the process of normalising log data, by providing a UI that assists in the creation of regular expressions for unstructured files, suggesting column types for structured files and a central repository for these data normalisation efforts to reduce redudant work.


<h2 id="Links">Key Links:</h2>

- High Fidelity Prototype: https://www.figma.com/file/CtGsgE63wCEwT7mReOemoP/Log-Normalisation-Tool?node-id=0%3A1
- User Story Map: https://miro.com/app/board/o9J_lIQx0X4=/

<h2 id="Structure">Folder Structure:</h2>

- data sample: Contains the data samples used in the digital prototype
  * Data Sources.pdf: A file listing the data used in our prototype and their origins
  * structured_data.csv: A data file containing the structured data used in our prototype
  * unstructured_data.log: A data file containing the unstructured data used in our prototype
- docs: Contains all product and requirement elicitation documentation files
- tests: Contains Acceptance Tests, Acceptance Criterion, Traceability Matrix
  * User Story Acceptance Criterias.pdf: Contain the acceptance criteria fo every user story listed in the user story list
  * User Story Acceptance Tests.pdf: Contain the acceptance tests for each user story listed in the user story list
  * Traceability Matrix.pdf: Contains the traceability matrix mapping each acceptance criteria to the associated acceptance test
- prototypes/low fidelity: Contains files for the paper prototype
  * Paper Prototype.pdf: Contain the paper prototype design pages exported from Figma
  * Paper Prototype.fig: Contains the Figma files for the paper prototype, to open this, import it to Figma on your web browser
- prototypes/high fidelity: Contains files for the digital prototype
  * Digital Prototype.pdf: Contain the digital prototype design pages exported from Figma
  * Digital Prototype.fig: Contains the Figma files for the digital prototype, to open this, import it to Figma on your web browser
- ui: Contains images and assets used for the digital prototype, including moodboard
  * Components - Assets.pdf: A file listing the components used in the digital prototype
  * Moodboard 1 - Classic Telstra Colours.pdf: Moodboard based on the main blue Telstra logo 
  * Moodboard 2 - Classic Computers Colours: Moodboard based on a more retro computer theme
  * Moodboard 3 - Green Telstra Colours.pdf: Moodboard based on one of the alternative colours the 

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
