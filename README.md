<div align="center">

# Tamer Ali Assaf

### Geospatial Software Engineer • GIS Specialist • GIS Automation & Spatial Data Engineering • Full-Stack Developer

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=20&duration=3000&pause=900&color=00C9B1&center=true&vCenter=true&repeat=true&width=1000&height=55&lines=Geospatial+Software+Engineering;GIS+Automation+%26+Spatial+Data+Engineering;Operational+GIS+%26+Real-Time+Systems;Web+GIS+%26+Full-Stack+Development;GeoAI+%26+Decision+Intelligence" alt="Professional focus"/>

<br/>

<img src="https://komarev.com/ghpvc/?username=tamer-Assaf2&style=for-the-badge&color=00c9b1&label=PROFILE+VIEWS" alt="Profile Views"/>
<img src="https://img.shields.io/github/followers/tamer-Assaf2?style=for-the-badge&color=d4a843&labelColor=0a1628&label=FOLLOWERS" alt="Followers"/>

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Tamer%20Ali%20Assaf-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tamer-ali-assaf-704548153/)
[![GitHub](https://img.shields.io/badge/GitHub-tamer--Assaf2-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tamer-Assaf2)
[![YouTube](https://img.shields.io/badge/YouTube-TamerAssaf--FullStackDev-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@TamerAssaf-FullStackDev)

<br/><br/>

> **Building geospatial systems where maps, software, spatial data, automation, real-time operations, and intelligent decision support meet.**

</div>

---

## 👨‍💻 About Me

```javascript
const tamer = {
  name: "Tamer Ali Assaf",
  location: "Ramallah, Palestine",

  roles: [
    "Geospatial Software Engineer",
    "GIS Specialist",
    "GIS Automation & Spatial Data Engineer",
    "Full-Stack GIS Developer"
  ],

  expertise: [
    "GIS Automation",
    "Spatial Data Engineering",
    "Operational GIS",
    "Spatial Algorithms",
    "Real-Time Tracking",
    "Web GIS",
    "Spatial Databases",
    "Full-Stack Development",
    "Decision Support Systems",
    "GeoAI"
  ],

  geospatialStack: [
    "ArcGIS Enterprise",
    "ArcGIS Pro",
    "ArcPy",
    "Arcade",
    "Attribute Rules",
    "ArcGIS CIM V3",
    "QGIS",
    "GeoServer",
    "PostGIS"
  ],

  developmentStack: [
    "Python",
    "JavaScript",
    "Node.js",
    "Express.js",
    "React",
    "PostgreSQL",
    "MongoDB",
    "SQL Server",
    "OpenLayers",
    "Leaflet"
  ],

  currentResearch: "GeoCommand AI"
};
```

I am a **Geospatial Software Engineer and GIS Specialist** focused on designing and developing systems that connect spatial databases, enterprise GIS, automation, web applications, real-time data, operational workflows, and intelligent decision support.

My work goes beyond traditional map production. I build **GIS logic, spatial automation, database workflows, geospatial algorithms, real-time tracking platforms, APIs, dashboards, and full-stack applications** that transform geographic data into operational systems.

Since 2021, I have worked on GIS solutions supporting operational requirements within the **Palestinian Police**, including large-scale national operations, spatial planning, operational mapping, real-time monitoring, security assessment workflows, interactive dashboards, and geospatial decision-support systems.

Alongside institutional GIS work, I develop public and commercial solutions using **Node.js, Express, PostgreSQL/PostGIS, MongoDB, OpenLayers, Leaflet, ArcGIS technologies, and mobile/web application architectures**.

My current applied research direction is **GeoCommand AI** — a modular GeoAI and geospatial decision-intelligence platform exploring how Artificial Intelligence can enhance spatial analysis, data integration, risk assessment, early warning, resource optimization, workflow automation, and **Human-in-the-Loop** decision support.

---

# 🧭 Core Engineering Expertise

| Area | Capabilities |
|---|---|
| 🌍 **GIS Engineering** | Enterprise GIS, geodatabase design, spatial workflows, spatial data integration |
| ⚙️ **GIS Automation** | ArcPy, Arcade, Attribute Rules, automated validation, feature updates, batch processing |
| 🧠 **Spatial Algorithms** | Graph construction, Dijkstra shortest path, nearest-neighbor search, KD-tree workflows |
| 🗃️ **Spatial Data Engineering** | PostgreSQL/PostGIS, SQL Server Spatial, GeoJSON, ETL, audit/history workflows |
| 🗺️ **Web GIS** | OpenLayers, Leaflet, GeoServer, ArcGIS web technologies, interactive mapping |
| 📡 **Real-Time Systems** | GPS tracking, fleet monitoring, live spatial data, event-driven updates |
| 💻 **Full-Stack Engineering** | Node.js, Express, React, MongoDB, PostgreSQL, REST APIs, authentication |
| 📊 **Decision Support** | GIS dashboards, operational monitoring, reporting, situational awareness |
| 🤖 **GeoAI** | Geospatial AI, AI-assisted analysis, explainable recommendations, human oversight |

---

# 🧩 GIS Development & Automation

## 🟢 Arcade & Attribute Rules

I use **Arcade Attribute Rules** to implement business logic directly inside enterprise geodatabases, including:

- Parent / child hierarchy automation
- Automatic child counting and derived attributes
- Cross-layer and cross-table lookups
- Automatic attribute propagation
- Validation and normalization rules
- Date and timestamp transformation
- Dynamic feature updates using `edit`
- Advanced `FeatureSetByName`, `Filter`, `First`, and `Count` workflows

```text
Feature Edit
    ↓
Attribute Rule
    ↓
Lookup / Filter / Validation
    ↓
Derived Business Logic
    ↓
Automatic Feature Updates
```

---

## 🐍 Python / ArcPy Automation

I develop Python and ArcPy workflows for automating ArcGIS Pro and geodatabase operations, including:

- File geodatabase scanning
- Feature-class discovery
- Field and ObjectID diagnostics
- ArcGIS Pro `.aprx` layer scanning
- Automated table and feature-class export
- Geodatabase preparation and migration
- Batch geoprocessing
- GeoJSON and spatial-data utilities
- ArcGIS project diagnostics

Common ArcPy patterns used include:

```python
arcpy.Exists(...)
arcpy.Describe(...)
arcpy.ListFields(...)
arcpy.ListFeatureClasses(...)
arcpy.management.CopyFeatures(...)
arcpy.management.CopyRows(...)
arcpy.management.MultipartToSinglepart(...)
arcpy.management.Integrate(...)
arcpy.management.FeatureToLine(...)
arcpy.management.DeleteIdentical(...)
```

---

## 🎨 ArcGIS Pro CIM & Symbology Engineering

I have worked with the **ArcGIS Pro Cartographic Information Model (CIM V3)** to inspect and extract map-layer configuration beyond what standard ArcPy properties expose.

### Capabilities

- ArcGIS Pro layer inspection
- CIM V3 extraction
- Renderer discovery
- Symbol-layer inspection
- RGB / HEX / Alpha extraction
- Outline and symbol metadata extraction
- Label and renderer metadata inspection
- JSON export of full CIM structures
- Excel-based symbology documentation

Example engineering pipeline:

```text
ArcGIS Pro Project (.aprx)
        ↓
Layer Discovery
        ↓
CIM V3 Definition
        ↓
Renderer / Symbol Inspection
        ↓
JSON Normalization
        ↓
Excel / Documentation Export
```

This work is especially useful for **GIS auditing, cartographic standardization, project migration, automated documentation, and enterprise GIS governance**.

---

# 🧠 Spatial Algorithms & Network Analysis

## 🛣️ Road-Network Routing Engine

I implemented shortest-path routing workflows using real road networks without relying exclusively on ArcGIS Network Analyst.

### Engineering Components

- OpenStreetMap road processing
- Road geometry preprocessing
- Multipart-to-singlepart conversion
- Network segmentation
- Graph construction
- Dijkstra shortest-path search
- KD-tree nearest-node matching
- Spatial snapping between geographic points and graph nodes
- Route geometry reconstruction

### Core Stack

`Python` `ArcPy` `heapq` `SciPy cKDTree` `OSM` `Graph Algorithms`

```text
Raw Road Network
      ↓
Geometry Cleanup
      ↓
Network Segmentation
      ↓
Graph Construction
      ↓
Nearest Node Search (cKDTree)
      ↓
Dijkstra
      ↓
Shortest Route Geometry
```

These techniques are applicable to:

- Fleet management
- Emergency response
- School transportation
- Delivery routing
- Municipal services
- Nearest-facility analysis
- Smart-city applications

---

# 🗃️ Spatial Database Engineering

I work with spatial and operational databases as a core part of GIS system architecture.

### PostgreSQL / PostGIS

- Spatial schemas
- Geometry storage
- Spatial queries
- GeoJSON workflows
- GIS application backends
- Multi-user geospatial systems

### SQL Server Spatial

- Enterprise geodatabase integration
- Geometry-aware database logic
- History / audit tables
- `INSERT`, `UPDATE`, and `DELETE` tracking
- SQL triggers
- Operational data archiving
- Live spatial-data integration

### Audit Pattern

```text
INSERT → Store New State
DELETE → Store Previous State
UPDATE → Store Previous + New State
```

Audit records can include:

```text
ActionType
ActionDate
ActionUser
```

This approach supports **traceability, GIS data governance, historical analysis, quality assurance, and operational auditing**.

---

# 🔌 GIS Integration & Data Interoperability

I work across desktop GIS, enterprise GIS, spatial databases, APIs, and application layers.

### Integration Experience

- ArcGIS REST Feature Services
- ArcGIS Enterprise
- GeoServer
- WMS / WFS / WMTS
- REST APIs
- GeoJSON
- PostgreSQL/PostGIS
- SQL Server Spatial
- MongoDB
- CSV / Excel data integration
- Cross-system ID matching
- Data validation and reconciliation

---

# 🚀 Selected Operational & Applied Projects

## 🧠 GeoCommand AI
### Geospatial Decision Intelligence Platform

> **Current Applied Research Project**

**GeoCommand AI** is a modular geospatial decision-intelligence concept that explores the integration of GIS, operational databases, real-time data, AI agents, analytics, and human decision-making inside a unified geospatial environment.

### Research Focus

- 🧠 Dynamic spatial risk assessment
- ⚠️ Predictive and early-warning analytics
- 📍 Context-aware geospatial recommendations
- 📊 Resource optimization
- 🗺️ Scenario analysis
- 🔍 Explainable AI
- 🤖 AI-assisted data governance
- 🔗 Multi-system data integration
- 👤 Human-in-the-Loop decision support

The framework is designed around the principle that **AI supports analysis and recommendations while authorized human users retain decision-making authority**.

![Geospatial AI](https://img.shields.io/badge/Geospatial-AI-00c9b1?style=flat-square)
![GIS](https://img.shields.io/badge/Enterprise-GIS-589632?style=flat-square)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-d4a843?style=flat-square)
![Decision Intelligence](https://img.shields.io/badge/Decision-Intelligence-2C7AC3?style=flat-square)

---

## 🗺️ Large-Scale Operational GIS Platform

Designed and developed GIS workflows and command-oriented mapping solutions supporting large-scale operational planning and coordination.

### Core Capabilities

- Operational geography
- Resource visualization
- Spatial planning
- Movement and route analysis
- Field-data integration
- Operational KPIs
- Interactive GIS dashboards
- Map-based situational awareness
- Decision-support workflows

The system concept transforms operational data into a unified spatial environment supporting planning, monitoring, coordination, and command-level visibility.

> 🔒 **Public descriptions intentionally exclude sensitive deployment, personnel, and operational information.**

`Operational GIS` `Command Systems` `Spatial Analysis` `Resource Management` `GIS Dashboards`

---

## 🎓 Tawjihi Operations GIS
### General Secondary Education Examination Operations

Developed an interactive GIS-based operational management solution supporting planning and field coordination during Palestinian General Secondary Education Examination (**Tawjihi**) operations.

### Supported Workflows

- Examination locations
- Geographic operational distribution
- Resource allocation
- Assignment mapping
- Mission planning
- Route support
- Field coordination
- Situational awareness
- Interactive map-based monitoring

`Mission Management` `Operational GIS` `Interactive Maps` `Resource Coordination` `Decision Support`

---

## 🛡️ Operational GIS & Geospatial Decision-Support Systems

Developed a portfolio of internal GIS applications supporting authorized operational planning, emergency preparedness, geospatial analysis, and decision-support workflows.

### Applied GIS Areas

- 👥 Authorized personnel-support mapping
- 🏥 Emergency and medical-facility mapping
- 🚧 Movement and accessibility analysis
- 🏦 Facility security-assessment workflows
- 🗺️ Interactive operational maps
- 📊 GIS dashboards and spatial decision support
- 📍 Field and asset visualization

These systems combine spatial information with operational data to improve planning, visibility, coordination, and decision support.

> 🔒 **Sensitive personnel, deployment, security, and operational information is intentionally excluded from public descriptions.**

`Enterprise GIS` `Spatial Analysis` `Decision Support` `ArcGIS Enterprise` `PostGIS`

---

## 🚌 Rawabi Bus Tracking System
### School Trips Platform | Rawabi English Academy

Designed and developed an integrated **school transportation and trip-management platform** for Rawabi English Academy.

The platform manages buses, students, parents, supervisors, drivers, routes, stops, and daily school trips.

### Key Capabilities

- 📍 Real-time vehicle tracking
- 🗺️ Interactive GIS maps
- 🎓 Student boarding and drop-off workflows
- 🔔 Alerts and notifications
- 💬 Parent-supervisor communication
- 📊 Operational dashboards
- 📱 Role-based mobile applications
- 🌐 Web-based administration
- 🔐 Authentication and role-based access
- 🔌 API and system integration

The platform combines **Full-Stack Development + GIS + Real-Time Tracking + Mobile/Web Applications + Spatial Databases** into an end-to-end transportation-management system.

`Node.js` `Express.js` `PostgreSQL` `PostGIS` `MongoDB` `OpenLayers` `REST APIs` `Real-Time Tracking`

---

## 💰 Falcon GIS
### Cash & Security Mission Management Platform

Designed and developed a GIS-enabled operational platform for managing transportation and mission workflows involving mobile assets and field resources.

### Platform Scope

- Mission management
- Vehicle management
- Operational locations
- Route management
- Resource coordination
- GIS dashboards
- Geospatial monitoring
- Real-time operational visibility

The platform integrates GIS and software workflows to improve mission visibility, coordination, resource management, and spatial awareness.

> 🔒 **Public descriptions intentionally exclude sensitive procedures and operational details.**

`GIS` `Mission Management` `Real-Time Tracking` `Route Management` `Resource Management` `Operational Dashboards`

---

# 🧪 Geospatial Engineering Projects

These engineering projects represent reusable technical capabilities extracted from real GIS problem-solving and rebuilt as general-purpose portfolio concepts.

## 🔍 ArcGIS Pro Project Inspector

**Stack:** `Python` `ArcPy` `CIM V3` `JSON` `Excel`

A GIS inspection and documentation toolkit for analyzing ArcGIS Pro projects, map layers, renderers, symbols, and cartographic metadata.

### Features

- Scan `.aprx` projects
- Discover maps and layers
- Inspect renderer types
- Extract CIM definitions
- Parse symbology metadata
- Convert color models to RGB / HEX / Alpha
- Export structured metadata to JSON
- Generate Excel documentation

---

## ⚙️ Enterprise GIS Rule Engine

**Stack:** `Arcade` `Attribute Rules` `Enterprise Geodatabase`

A reusable business-rule architecture for automating relationships and attribute logic inside GIS datasets.

### Features

- Parent-child hierarchy management
- Automatic child counting
- Cross-layer attribute lookup
- Derived values
- Data validation
- Automatic feature updates
- Timestamp normalization
- Enterprise geodatabase rule execution

---

## 🛣️ Open Road Routing Engine

**Stack:** `Python` `ArcPy` `OSM` `Dijkstra` `cKDTree`

A network-routing workflow that converts road geometry into a searchable graph for shortest-path analysis.

### Features

- OSM road preprocessing
- Geometry cleanup
- Graph construction
- Nearest-node matching
- Dijkstra routing
- Route geometry generation

---

## 🗂️ Spatial Database Audit Engine

**Stack:** `SQL Server` `Spatial Geometry` `Triggers` `Enterprise GIS`

A database-auditing architecture for preserving historical states of geospatial records.

### Features

- INSERT history
- UPDATE before/after state tracking
- DELETE history
- Action metadata
- Geometry-aware database handling
- Historical GIS analysis

---

# 🔥 Technologies & Tools

<div align="center">

### 🌍 Geospatial Technologies

<img src="https://img.shields.io/badge/ArcGIS-Enterprise-2C7AC3?style=for-the-badge&logo=esri&logoColor=white"/>
<img src="https://img.shields.io/badge/ArcGIS-Pro-67ACDA?style=for-the-badge&logo=esri&logoColor=white"/>
<img src="https://img.shields.io/badge/ArcPy-Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Arcade-Attribute_Rules-00C9B1?style=for-the-badge"/>
<img src="https://img.shields.io/badge/ArcGIS-CIM_V3-d4a843?style=for-the-badge"/>
<img src="https://img.shields.io/badge/QGIS-589632?style=for-the-badge&logo=qgis&logoColor=white"/>
<img src="https://img.shields.io/badge/PostGIS-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/GeoServer-4B9CD3?style=for-the-badge"/>
<img src="https://img.shields.io/badge/OpenLayers-1F6B75?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Leaflet.js-199900?style=for-the-badge&logo=leaflet&logoColor=white"/>

### 💻 Development Stack

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white"/>
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/>

### 🧮 Spatial Algorithms & Data

<img src="https://img.shields.io/badge/Dijkstra-Shortest_Path-2C7AC3?style=for-the-badge"/>
<img src="https://img.shields.io/badge/cKDTree-Nearest_Neighbor-7b5ea7?style=for-the-badge"/>
<img src="https://img.shields.io/badge/OSM-Road_Networks-7EBC6F?style=for-the-badge&logo=openstreetmap&logoColor=white"/>
<img src="https://img.shields.io/badge/GeoJSON-Spatial_Data-d4a843?style=for-the-badge"/>

### 🔧 Dev Tools & Cloud

<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>

</div>

---

## 🧰 Technical Capability Map

### GIS Automation

`ArcPy` `Arcade` `Attribute Rules` `CIM V3` `Batch Geoprocessing` `Geodatabase Automation`

### Spatial Databases

`PostgreSQL` `PostGIS` `SQL Server Spatial` `MongoDB` `Geometry` `Spatial Queries` `Audit History`

### Web GIS

`OpenLayers` `Leaflet` `GeoServer` `ArcGIS Enterprise` `WMS` `WFS` `WMTS` `GeoJSON`

### Backend & Integration

`Node.js` `Express.js` `REST APIs` `Authentication` `RBAC` `API Integration` `Real-Time Systems`

### Spatial Algorithms

`Graph Algorithms` `Dijkstra` `Nearest Neighbor` `cKDTree` `OSM Processing` `Network Analysis`

### Data Engineering

`ETL` `Data Validation` `Data Reconciliation` `Cross-System Matching` `Excel Automation` `JSON` `CSV`

### Operational Applications

`GIS Dashboards` `Real-Time Monitoring` `GPS Tracking` `Reporting Systems` `Data Visualization` `Interactive Maps`

---

# 🌐 Featured Public Web Projects | أبرز مشاريع الويب

> Additional public-facing projects demonstrating production web development, bilingual interfaces, SEO, UI implementation, and deployment.

## 💧 SuperPlus — Water Purification Company Website

<table>
<tr>
<td width="62%">

**📌 Tech Stack:** HTML + CSS + JavaScript

A professional corporate website for a Palestinian water-purification company, featuring bilingual Arabic/English content, products and services, responsive interfaces, and SEO-oriented implementation.

**🚀 Key Features**
- ✅ Bilingual Arabic / English
- ✅ Products & services showcase
- ✅ SEO & structured metadata
- ✅ Social sharing metadata
- ✅ Mobile responsive

</td>
<td width="38%" align="center">

[![Visit SuperPlus](https://img.shields.io/badge/🌐_Visit-SuperPlus.ps-00c9b1?style=for-the-badge)](https://superplus.ps)

<br/>

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

</td>
</tr>
</table>

---

## 🎬 Ramallah Digital — Media Production Company Website

<table>
<tr>
<td width="62%">

**📌 Tech Stack:** HTML + CSS + JavaScript + Bootstrap

A professional media-production website featuring bilingual content, services and portfolio presentation, responsive interfaces, custom UI implementation, and SEO-oriented structure.

**🚀 Key Features**
- ✅ Bilingual Arabic / English
- ✅ Services & portfolio showcase
- ✅ SEO & structured metadata
- ✅ Responsive interface
- ✅ Production deployment

</td>
<td width="38%" align="center">

[![Visit Ramallah Digital](https://img.shields.io/badge/🌐_Visit-RamallahDigital.ps-00c9b1?style=for-the-badge)](https://ramallahdigital.ps)

<br/>

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

</td>
</tr>
</table>

---

## 🍕 PerfectMood — Restaurant Website

<table>
<tr>
<td width="62%">

**📌 Tech Stack:** HTML + CSS + JavaScript + Bootstrap

A responsive restaurant website featuring menu information, delivery information, social metadata, and search-oriented structured content.

**🚀 Key Features**
- ✅ Interactive menu presentation
- ✅ Restaurant & menu SEO
- ✅ Social metadata
- ✅ Mobile responsive
- ✅ Production deployment

</td>
<td width="38%" align="center">

[![Visit PerfectMood](https://img.shields.io/badge/🌐_Visit-PerfectMood.ps-00c9b1?style=for-the-badge)](https://perfectmood.ps)

<br/>

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

</td>
</tr>
</table>

---

# 🎬 YouTube Content | محتوى يوتيوب

> Tutorials, project walkthroughs, and technical content on **Full-Stack, GIS, geospatial development, and software engineering** — in Arabic and English.
>
> دروس تعليمية وشرح مشاريع ومحتوى تقني حول تطوير **Full-Stack وGIS والبرمجة الجغرافية المكانية** — بالعربية والإنجليزية.

<div align="center">

### 📺 Featured Videos | فيديوهات مختارة

<table>
<tr>
<td align="center" width="50%">

[![Full-Stack GIS Project Walkthrough](https://img.youtube.com/vi/7UhE0534TqQ/hqdefault.jpg)](https://youtu.be/7UhE0534TqQ)

**[🎬 Full-Stack GIS Project Walkthrough](https://youtu.be/7UhE0534TqQ)**

*شرح مشروع Full-Stack GIS متكامل*

</td>
<td align="center" width="50%">

[![MERN Stack Development Tutorial](https://img.youtube.com/vi/rBdk15H4CmU/hqdefault.jpg)](https://youtu.be/rBdk15H4CmU)

**[🎬 MERN Stack Development Tutorial](https://youtu.be/rBdk15H4CmU)**

*درس تطوير MERN Stack*

</td>
</tr>

<tr>
<td align="center" width="50%">

[![GIS and Geospatial Tech Deep Dive](https://img.youtube.com/vi/DG_SDkot7lQ/hqdefault.jpg)](https://youtu.be/DG_SDkot7lQ)

**[🎬 GIS & Geospatial Deep Dive](https://youtu.be/DG_SDkot7lQ)**

*شرح معمق لتقنيات GIS والجغرافيا المكانية*

</td>
<td align="center" width="50%">

[![Quick Dev Tip](https://img.youtube.com/vi/8b0w6u5kE1w/hqdefault.jpg)](https://youtube.com/shorts/8b0w6u5kE1w?feature=share)

**[🎬 Quick Dev Tip ⚡ #Shorts](https://youtube.com/shorts/8b0w6u5kE1w?feature=share)**

*نصيحة تقنية سريعة*

</td>
</tr>
</table>

<br/>

[![YouTube Channel](https://img.shields.io/badge/Subscribe-TamerAssaf--FullStackDev-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@TamerAssaf-FullStackDev)

</div>

---

# 📊 GitHub Activity

<div align="center">

<img width="58%" src="https://streak-stats.demolab.com/?user=tamer-Assaf2&theme=tokyonight&hide_border=true&background=0a1628&ring=00c9b1&fire=d4a843&currStreakLabel=ffffff&sideLabels=ffffff&dates=888888" alt="GitHub Streak"/>

</div>

> **Note:** Public GitHub activity does not reflect private, institutional, or client development work.

---

# 🏆 Professional Focus

<div align="center">

<img src="https://img.shields.io/badge/Geospatial-Software_Engineer-00c9b1?style=for-the-badge&labelColor=0a1628"/>
<img src="https://img.shields.io/badge/GIS-Automation-d4a843?style=for-the-badge&labelColor=0a1628"/>
<img src="https://img.shields.io/badge/Spatial_Data-Engineering-2C7AC3?style=for-the-badge&labelColor=0a1628"/>

<br/>

<img src="https://img.shields.io/badge/Operational_GIS-Decision_Support-589632?style=for-the-badge&labelColor=0a1628"/>
<img src="https://img.shields.io/badge/Full--Stack-GIS_Developer-7b5ea7?style=for-the-badge&labelColor=0a1628"/>
<img src="https://img.shields.io/badge/GeoAI-Applied_Research-e63946?style=for-the-badge&labelColor=0a1628"/>

</div>

---

# 🎯 What I Build

I am particularly interested in building systems that combine:

```text
Spatial Data
    +
Enterprise GIS
    +
Automation
    +
Spatial Algorithms
    +
APIs & Backend Systems
    +
Web / Mobile Applications
    +
Real-Time Data
    +
AI-Assisted Analysis
    ↓
Operational Geospatial Systems
```

My long-term direction is to bridge **GIS engineering and modern software engineering** — creating systems that do more than display maps: systems that **understand spatial relationships, automate workflows, integrate data, monitor real-world activity, and support better human decisions**.

---

# 🌍 Let's Connect! | تواصل معي

<div align="center">

*Feel free to reach out for professional collaboration, GIS engineering, spatial-data projects, GeoAI research, full-stack development, or technical discussions.*

*للتعاون المهني، هندسة نظم GIS، مشاريع البيانات المكانية، GeoAI، تطوير البرمجيات، أو النقاشات التقنية.*

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Tamer%20Ali%20Assaf-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tamer-ali-assaf-704548153/)
[![GitHub](https://img.shields.io/badge/GitHub-tamer--Assaf2-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tamer-Assaf2)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@TamerAssaf-FullStackDev)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://facebook.com/tamtechgis)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/tamer.assaf44)
[![TikTok](https://img.shields.io/badge/TikTok-010101?style=for-the-badge&logo=tiktok&logoColor=white)](https://tiktok.com/@tamerassaf3)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/TamTech43281)

</div>

---

<div align="center">

## Thanks for visiting! | شكراً لزيارتك!

### Geospatial Software Engineering • GIS Automation • Spatial Data Engineering • Full-Stack Development • GeoAI

**Building systems where geography, data, software, automation, and intelligence meet.**

**Ramallah, Palestine**

<br/>

[![GitHub stars](https://img.shields.io/github/stars/tamer-Assaf2?style=social&label=Star%20my%20repos)](https://github.com/tamer-Assaf2?tab=repositories)

</div>
