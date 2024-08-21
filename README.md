# Optimizing Water Bottle Filling Station Placement

## Overview

This project aims to optimize the placement of water bottle filling stations across Boston University’s campus. The goal is to identify high-priority locations for new installations based on various factors, including foot traffic, proximity to existing plumbing, and the presence of air conditioning in buildings. The project leverages BU's Wi-Fi data, building inventory data, and geospatial analysis techniques to provide data-driven recommendations that enhance campus sustainability efforts.

## Table of Contents

1. [Project Goal](#project-goal)
2. [Data Sources](#data-sources)
3. [Methodology](#methodology)
4. [Results](#results)

## Project Goal

The primary objective of this project is to analyze the current distribution of water bottle filling stations and recommend new locations that would best serve the Boston University community. The analysis considers factors such as:

- Foot traffic data (based on Wi-Fi usage)
- Proximity to existing plumbing to reduce installation costs
- Building usage and the presence of air conditioning
- Existing water sources such as kitchens and water coolers

## Data Sources

- **BU Map of Water Filling Stations:** An interactive map showing current water bottle filling station locations on the Charles River Campus. Note that this map covers approximately 80% of existing stations.
- **Inventory of Campus Buildings and Rooms:** Detailed inventory of campus buildings, including rooms with kitchens and mechanical ventilation.
- **BU Wi-Fi Data:** Data representing foot traffic patterns across campus, providing insights into high-usage areas.
- **BU Floor Descriptions:** Useful for understanding the layout of buildings and traffic flow.
- **BU High Volume Event Spaces:** Information on areas with high event traffic, which may require additional water bottle filling stations.

## Methodology

1. **Data Collection and Pre-Processing:**
   - Gathered and cleaned datasets from BU’s internal resources.
   - Merged datasets to create a comprehensive overview of current station locations, foot traffic, and building attributes.

2. **Geospatial Analysis:**
   - Used geospatial tools to map current station locations and analyze gaps in coverage.
   - Applied a set of criteria to prioritize new station locations, considering proximity to plumbing, foot traffic density, and building amenities.

3. **Recommendations and Visualization:**
   - Developed a set of recommendations for new station installations.
   - Created a geospatial map with highlighted priority areas for easy reference.

## Results

- The analysis identified key areas on campus where new water bottle filling stations would have the greatest impact.
- The geospatial map and final report provide actionable insights for BU Sustainability to make informed decisions on resource allocation.
