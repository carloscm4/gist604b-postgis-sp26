# PostGIS Database Orchestration – NYC Spatial Analysis

**Student:** Carlos Castillo  
**Course:** GIST 604B – Open Source GIS  
**Module:** Module 4 – PostGIS Database Orchestration  
**University of Arizona**

---

## Project Description
In this assignment, I worked with a PostGIS-enabled PostgreSQL database to load and analyze spatial data from New York City. The goal was to get comfortable using SQL for spatial queries, working with real geographic datasets, and understanding how spatial relationships are handled inside a database.

---

## Tools and Technologies
- PostgreSQL + PostGIS  
- Docker (Codespaces environment)  
- VS Code / GitHub Codespaces  
- SQL  
- NYC shapefile data from PostGIS workshop  

---

## What I Did
- Set up a PostGIS database using Docker in GitHub Codespaces  
- Created a new database (`nyc`) and enabled the PostGIS extension  
- Imported NYC datasets including neighborhoods, census blocks, streets, and subway stations  
- Wrote and ran SQL queries to explore and analyze spatial data  
- Used spatial functions to test relationships and perform spatial joins  

---

## How to View / Run
To run this project:

1. Open the repository in GitHub Codespaces  
2. Start Docker:
   ```bash
   docker compose up -d

## Repository Structure

    .
    ├── README.md
    ├── .devcontainer
    │   ├── devcontainer.json
    │   └── Dockerfile
    ├── sql/
    │   ├── 01_basic_sql_queries.sql
    │   ├── 02_geometry_queries.sql
    │   ├── 03_spatial_relationships.sql
    │   └── 04_spatial_joins.sql
    ├── demos/
    │   ├── demo_aggregation_queries.sql
    │   ├── demo_basic_queries.sql
    │   ├── demo_filtering_queries.sql
    │   └── demo_postgis_queries.sql
    └── docker-compose.yml
