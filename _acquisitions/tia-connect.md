---
title: "TIA CONNECT"
date: 2018-11-18T12:33:46+10:00
weight: 4
description: "TIA CONNECT enable non-experts to create data stream pipes that end with Cassandra and Fiware."
license: "https://img.shields.io/badge/license-Apache2.0-blue"
trl: "https://img.shields.io/badge/TRL-8-green"
---

TIA CONNECT enable non-experts to create data stream pipes that end with Cassandra and Fiware.

## Name
MAI - Collection of weather data
## Defined in Task
Task 5.1: Plant Digital Twins with ML/AI
## Short description
The MET API Interface (MAI for short) is a user interface to FROST, the API developed by the Norwegian Meteorological Institute (MET) which enables public access to weather data. MAI is a software bundle written in Python and is intended to be used as a standard Python module.

The purpose of MAI is to simplify data retrieval from FROST by providing a streamlined user interface. A user can select a location, a time interval, and a series of measurements, and MAI takes care of contacting the correct access point in FROST, submitting a properly composed request, and receiving and handling the response. MAI allows querying FROST for three main purposes: 1) Retrieve all available weather-stations names in a given area (at municipality level); 2) retrieve a list of all available measurements at a selected location or municipality; 3) retrieve all data available for the selected measurements at a chosen location and time interval. The weather data is collected in a properly formatted Pandas DataFrame for ease of use.

The modularity of MAI allows for flexible development and extension of its features.