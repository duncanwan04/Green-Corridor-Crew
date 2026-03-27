# Green Corridor Crew: Empowering Smarter, Greener Mobility Choices in Toronto
![Screenshot](images/thumbnail.png)

## User Guide

Green Corridor Crew is an interactive mapping application that helps users explore sustainable transportation accessibility across census tracts in Toronto. The app compares **cycling**, **walking**, and **public transit** and helps users understand which transportation mode is most practical, safe, and accessible in different neighborhoods.

Users can either **search for an address** or **click directly on the map** to select a census tract and view transportation scores.

---

## Overview

The MoveGreen TO  app is an interactive mapping tool designed to help users explore sustainable transportation methods across census tracts in Toronto. The app allows users to compare the sustainable modes of transportation, such as cycling, walking, and public transit, and to decide which mode is most practical, safe, and accessible for their neighborhood. Users can either search for an address or click directly on the map to select a census tract and view its transportation scores.

---

## Main Pages

The app contains **four main pages**:

### 1. All Page
The **All** page gives users an overall view of transportation methods. After selecting a census tract, the left panel displays the **Cycling Score, Walking Score, and Public Transit Score** allowing users to identify which transportation mode performs best in that tract.

![Screenshot](images/all-page-mode)

After selecting a census tract, the left panel displays:

- Cycling Score
- Walking Score
- Public Transit Score

This page also includes three filter toggles:

- Best Mode: Cycling
- Best Mode: Walking
- Best Mode: Public Transit

These filters highlight census tracts where one transportation mode has the strongest score among the three, according to levels of accessibility, safety, and the presence of infrastructure that allows for that mode of transportation. This helps users quickly identify which areas are best served by cycling, walking, or public transit.


---

### 2. Cycling Page
![Screenshot](images/cycling-page.png)

The **Cycling** page focuses on cycling accessibility.

After selecting a census tract, users can view:

- Cycling Score
- Cycling Collision Rank (where available)
- % of Cycling Commute
- legend information for the cycling layer

![Screenshot](images/cycling-top-and-worse.png)

This page also includes filter buttons for:

- Best CTs for Cycling (Top 10%)
- Worst CTs for Cycling (Bottom 10%)

These filters help users identify the highest- and lowest-performing census tracts for cycling accessibility.

![Screenshot](images/switch-section.png)

It also contains a **swipe comparison tool**:

- **Left side:** cycling accessibility
- **Right side:** actual cycling commute usage

Users can drag the vertical swipe bar to compare accessibility and actual cycling behavior.

---

### 3. Walking Page
![Screenshot](images/walking.png)
The **Walking** page focuses on walking accessibility.

After selecting a census tract, users can view:

- Walking Score
- % of Walk Commute
- legend information for the walking layer

![Screenshot](images/best-worst-walking.png)

This page also includes filter buttons for:

- Best CTs for Walking (Top 10%)
- Worst CTs for Walking (Bottom 10%)

It also contains a **swipe comparison tool**:

- **Left side:** walking accessibility
- **Right side:** actual walking commute usage

Users can drag the swipe bar to compare accessibility and actual walking behavior.

---

### 4. Public Transit Page
![Screenshot](images/public-trasnit.png)
The **Public Transit** page focuses on transit accessibility.

After selecting a census tract, users can view:

- Public Transit Score
- % of CT with Subway Coverage and GO Train Coverage
- % of Public Transit Commute
- legend information for the transit layer

![Screenshot](images/ttc-section.png)

This page also includes filter buttons for:

- Best CTs for Public Transit (Top 10%)
- Worst CTs for Public Transit (Bottom 10%)
- Has Subway Access

The **Has Subway Access** filter helps identify census tracts with subway coverage.

The Has Subway Access filter allows users to identify census tracts with subway access coverage. Based on your notes, public transit scoring includes bus routes, subway lines, and GO train access, and subway and GO stations are represented using 800-metre buffer zones to capture service areas. The transit index is built from a transit coverage component plus an accessibility component, with the transit coverage component weighted across GO Train, Bus, and Subway.


This page also contains a **swipe comparison tool**:

- **Left side:** public transit accessibility
- **Right side:** actual public transit commute usage

Users can drag the swipe bar to compare accessibility and actual public transit behavior.

---

## How to Use the App
![Screenshot](images/on-step1.png)
### Step 1: Choose a page

Use the navigation tabs at the top of the app to switch between:

- All
- Cycling
- Walking
- Public Transit

The **All** page is best for a general overview, while the other three pages provide more detailed mode-specific information.

### Step 2: Find a census tract
There are *two ways* to locate a census tract:
![Screenshot](images/on-step2.png)

#### Option A: Search by address
Type an address into the search bar. The map will zoom to that location so the corresponding census tract can be identified.

#### Option B: Click directly on the map
Click on any census tract directly on the map. The information panel on the left will update automatically.
![Screenshot](images/option-B.png)

## How to Interpret the App
The app is intended to help users answer questions such as:
Which transportation mode is strongest in a given census tract?
Does high accessibility correspond to high real-world usage?
Are there census tracts where infrastructure and behavior do not match?
Which areas appear well served, and which appear underserved?
## Tips for Users
Start on the All page if you want a broad overview.
Use the search bar if you want to examine a specific address.
Use the map click function if you want to compare different parts of Toronto quickly.
Use the swipe tool on the three mode-specific pages to better understand the gap between accessibility and real commuting behavior. 


## What the App Helps Users Explore

This app helps answer questions such as:

- Which transportation mode is strongest in a given census tract?
- Does high accessibility correspond to high real-world usage?
- Are there census tracts where infrastructure and commuting behavior do not match?
- Which areas appear well served, and which appear underserved?

---

## Methodological Notes

The transportation scores are based on a weighted combination of:

- **Infrastructure**
- **Safety**
- **Accessibility**

### Infrastructure
Practicality is measured based on the presence of transportation infrastructure, such as:

- sidewalks for walking
- cycling networks for biking
- transit infrastructure for public transit

Public transit infrastructure includes:

- Subway
- Light Rail Transit (LRT)
- Bus Rapid Transit (BRT)
- GO Train
- Priority bus corridors

A transportation option is considered practical when most of the census tract can access the nearest stop or network within about **10 to 15 minutes**, or roughly **800 metres**.

### Safety
Safety for cycling and walking is measured using the frequency of severe or fatal collisions involving cyclists and pedestrians in each census tract.

### Accessibility
Accessibility is measured using spatial access indicators that estimate how easily residents can reach important destinations, including:

- health care facilities
- employment
- sports and recreation
- education
- cultural and arts facilities
- child care
- grocery stores

These measures are combined into a standardized composite accessibility index.

### Final Scores
The final **Walking**, **Cycling**, and **Public Transit** scores are weighted averages of standardized infrastructure, safety, and accessibility measures. Standardization ensures that no single measure dominates the index due to scale differences.

---

## Features Summary

- address search
- clickable census tracts
- overall comparison page
- three mode-specific pages
- top 10% and bottom 10% filters
- subway access filter on public transit page
- swipe comparison between accessibility and actual usage

---

## Project Goal

The goal of this app is to support smarter and greener mobility choices in Toronto by making sustainable transportation patterns easier to understand and compare at the census tract level.
