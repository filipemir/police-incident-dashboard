# Suffolk County DAO Police Incident Dashboard

A map representation of real time data on police incidents in Suffolk County (Boston).

## Background Information
* District Attorney Rachael Rollins was elected in Fall 2018 on a progressive platform of choosing public health approaches to handling incidents of criminal activity, instead of a carceral approach. In March 2019, she released a policy memo outlining the beginning of a progressive vision of declining to prosecute.

* The Suffolk County District Attorney’s Office is the largest prosecutor’s office in the Commonwealth of Massachusetts and handles tens of thousands of cases every year to prosecution or diversionary outcomes. To meet DA Rollins’ policy goals of reducing racial disparities and bringing a public health approach for misdemeanor and low-level felony offenses, SCDAO must use data to measure whether or not its efforts are successful in real time. Such metrics will ensure that all of the office’s decision-making promotes public safety, and will allow our partner agencies, and the public, to hold us accountable.

## Problem Statement
How can the Suffolk County District Attorney’s Office use public data sources like the Boston Police Incident Report Data to get live updates on how law enforcement is coming in contact with the community?

## Project Goals
To build a live or frequently updating dashboard of crime incident reports in the City of Boston that the DAs office to be displayed at their office.
This visualization ideally would be visible on a large TV.

## Users
* Suffolk County DA senior staff (assistant DAs and bureau chiefs, investigators)
* Criminal Legal Advocates, Watchdogs: such a tool is not only useful for the Suffolk County DA’s Office, but also the public.

## Notes and ideas
A web based application that polls for updates in data, then color codes them by “offense code group” and displays new police incidents as color coded dots on a full-screen map. The application resets every Sunday morning. As incidents are tallied by offense code group, a legend displaying the count of each incident is overlaid on the side of the map.

## Viz Wish List
* Real-time Map of Incidents
* Change in Incident Rates (by type) over time
* Impact of DA office actions (layer of Data to add)
* Overlay Boston Police neighborhoods SHP files
* Court loads by jurisdiction (aggregate by Nasser's SHP files)
* Field Interrogation and Ovservation (FIO) -> Stop and Frisk => data.boston.gov (*stale data no update since Dec2016)

## Preliminary Stories
As a member of the DAs senior staff, I want to be able to see live crime report data in Boston, so that I can prepare my staff for an influx of cases, or so we can understand trends in law enforcement contact with communities and how our prosecution trends correlate.
As a member of the DAs senior staff, I want to be able to see live crime report data in Boston by location and type, so that I can see if there are correlations in police activity in particular neighborhoods.
We want to be able to understand how changes in prosecutorial policy impact community policing, and be able to in real-time measure upticks or downticks in contact with law enforcement.

## Requirements
Ideally, this would be done in R or Python, or D3.js, since that is what the DAs technical staff is familiar with.
Otherwise platform agnostic, as long as we can deploy it in a docker container.

## Resources
The Boston Police Incident Report Database, publicly available on data.boston.gov: https://data.boston.gov/dataset/crime-incident-reports-august-2015-to-date-source-new-system/resource/12cb3883-56f5-47de-afa5-3b1cf61b257b
