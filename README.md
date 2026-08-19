# Technical-Documentation

# BOL (Business/Data Object Layer)

**Platform:** Procify/KloBase
**Jira Component:** BOL — *"Data Transactions"*

BOL is a core framework component of the Procify/KloBase platform. Based on the KT (Knowledge Transfer) breakdown and related tickets, it covers the following areas:

## Coverage Areas

### Entity
- Entity types
- Validation rules
- Naming conventions
- Flow / callbacks
- MapKeys
- Caching
- Stub / DP concepts

### Query
- Supported query types
- Validation / callback rules
- "Expand All" handling
- Network modes and runtime flow

### Value Help (VH)
- VH types
- Dependent VH configuration
- Filtering / sorting
- Row-wise authorization VH (RW VH)
- Loading / caching

### EntitySet
- Overview
- Methods
- Functions

### RW ACS (Row-Wise Access Control)
- Configuration
- Runtime flow / handling

## In Practice

- BOL is the layer apps build on to **load and manage transaction data** — e.g., a ReactJS app in Procify uses BOL to load transaction data.
- The **BOL Editor** is a tool/component built on top of BOL for configuring these entities.
- BOL has an **event mechanism** (e.g., tracking attachment upload status).
- BOL is a **running service** that can require restarts (as seen in *"Request for BOL component restart"*).



  - [BOL](./) 
  
  

