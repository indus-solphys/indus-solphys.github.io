# Presidential Innovation Fellows website

This is the PIF website, jekyll edition (inspired by the [18F hub](https://github.com/18F/hub)). The website is currently maintained by the PIF leadership, with contributions from the fellows.

In the /_data section there are YAML files available for PIF bios, current/previous projects, and case studies. Additionally, there are specific fields for each YAML file and corresponding approved values.

**NOTE:** When adding info to YAML files, if the text added contains a , or . please use "" around the text. ALSO, if you need to quote something (using ""), use '' instead.

#### PIF bios

LOCATION: /_data/pifs/

FILENAME: lastname-firstname.yml

field | format/info
--- | ---
id: | lastname-firstname
name: | full name
year: | year joined
img: | lastname-firstname-headshot.png
hometown: | City, STATE
region: | US Census regions [map link](http://www2.census.gov/geo/pdfs/maps-data/maps/reference/us_regdiv.pdf)
bio: | 140 character bio
bio_full: | full PIF bio
skills: | list of approved terms are in Appendix

**NOTE:** It's **IMPORTANT** to use the approved values for the **SKILLS** so the filtering on the Fellows page works.

#### Case Studies

Case studies are specific PIF projects that are highlighted and used for branding and marketing.

LOCATION: /_data/case_studies/

FILENAME: case-study-name.yml

field | format/info
--- | ---
id: | case-study-name
img: | case-study.png
title: | name of case study
description: | 
challenge: |
solution: |
impact: |
date: | typically a range (e.g. 2013 - present)
quote: |
quote_source: |

#### Current and Previous Projects

Current and previous projects are within their respective subdirectories. As current projects wrap up, they should be moved to the previous projects subdirectory.

LOCATION: /_data/current_projects/ OR /_data/previous_projects/

FILENAME: project-name.yml

name: | name of project
agency: | reference name, see Appendix
description: |
pifs: | list of pifs who worked on project

**NOTE:** It's **IMPORTANT** to use the approved values for the **AGENCY** and **PIFS** so their info in other YAML files are accurately populated.

#### Agency List

This YAML file contains the reference keys for agencies

LOCATION: /_data/

FILENAME: agency_list.yml

field | info
--- | ---
short: | acronym or abbreviated name
long: | full name

**NOTE:** If you need to add an agency, make sure to add their logo (400x400) to the /images/agencies/ folder using the **SHORT** field name AND update the README.md file to include the agency in the Appendix list.

### APPENDIX

#### regions

term | name
--- | ---
northeast | Northeast
south | South
midwest | Midwest
west | West
outside | Outside the US

#### Skills

term | name
--- | ---
policy | Policy & Legislation
front | Front End Development
data | Data Visualization
product | Product Management
ux | User Experience
comm | Marketing & Communications
bd | Business Development
back | Back End Development
design | Visual Design
cyber | Cyber Security
digital | Digital Strategy

#### Agencies

term | name
--- | ---
DOC | Department of Commerce
DOE | Department of Energy
DOI | Department of Interior
DOL | Department of Labor
ED | Department of Education
FDA | Food and Drug Administration
FEMA | Federal Emergency Management Agency
GSA | General Services Administration
HHS | Health and Human Services
IRS | Internal Revenue Service
MCC | Millennium Challenge Corporation
NARA | National Archives and Records Administration
NASA | National Aeronautics and Space Administration
NIH | National Institute of Health
NIST | National Institute of Standards and Technology
NOAA | National Oceanic and Atmospheric Administration
NSF | National Science Foundatoin
OSTP | White House Office of Science & Technology, Policy
SBA | Small Business Administration
Smithsonian | Smithsonian Institution
State | State Department
Treasury | Department of the Treasury
USAID | US Agency for International Development
USDA | Department of Agriculture
USCB | Census Bureau
USCIO | US Chief Information Officer
USPTO | United States Patent and Trademark Office
VA | Veteran Affairs
