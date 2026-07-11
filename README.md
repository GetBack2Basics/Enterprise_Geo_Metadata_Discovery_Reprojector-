# Enterprise_Geo_Metadata_Discovery_Reprojector-
An ESRI arc-python (arcpy) and SQL based workflow to discover enterprise spatial metadata, plan cleaning of duplicate and archive data and perform reprojection (such as GDA 94 to 2020). It also discovers file use in user workflows and corporate systems (such as GeoCortex and Experience Builder) and either fixes them automatically or provides instructions to users on how to update there systems.

Critically it discovers, reports on and QA's ESRI SDE complex data such as
-Versioning/Archiving
-Metadata
-Attachments and Relationships
-Subtypes
-Cordinate columns (uses AI to find columns that may contain spatial hard coded data)
-Schemas and Projections to automate the GDA 2020 or GDA 2020 plus zone or leave WGS 84 as is
-QA's changes programittically and via html reports for easy review
-Checks node based reprojection on x% of each feature class
-Contains input controls to work only on some files, continue, overwrite or skip based on logic requirements

(c)(r) NSW DPHI

Code is maintained in internal repository and may possibly be accessed via official requests through coreagc@gmail.com

Authors role: Created all code using AI tools and experience. Improved via consultation and implementing in stg-dev-test-prod environments through engagement with senior staff and program teams (data owners) and data users.
