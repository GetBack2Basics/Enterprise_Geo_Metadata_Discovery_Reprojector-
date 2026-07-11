# Enterprise Geo Metadata Discovery Reprojector

An ESRI ArcPy and SQL-based workflow to discover enterprise spatial metadata, plan the cleanup of duplicate and archived data, and perform reprojection (such as GDA94 to GDA2020).

It also discovers, reports on, and quality-assures ESRI SDE complex data, including:

- Versioning and archiving
- Metadata
- Attachments and relationships
- Subtypes
- Coordinate columns (uses AI to identify columns that may contain hard-coded spatial data)
- Schemas and projections to automate migration to GDA2020 (or GDA2020 + zone), or leave WGS84 unchanged
- Programmatic and HTML-based QA reporting for easy review
- Node-based reprojection checks on a configurable percentage of each feature class
- Input controls to process selected files only, and continue, overwrite, or skip based on logic requirements

© NSW DPHI

---

## Notes

**Author's role:**  
Created all code using AI tools and professional experience, then improved it through consultation and implementation across staging, development, test, and production environments in collaboration with senior staff and program teams (data ...).

Code is maintained in an internal repository and may be accessed via official requests through **coreagc@gmail.com**, where corporate approval will be sought.

© NSW DPHI
