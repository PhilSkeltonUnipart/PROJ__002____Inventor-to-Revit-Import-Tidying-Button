# PROJ__002____Inventor-to-Revit-Import-Tidying-Button
**Automated Revit Geometry Cleanup – Autodesk Inventor iLogic**

An Autodesk Inventor iLogic tool designed to automatically clean up imported Revit models within an assembly environment.

When Revit models are imported into Inventor, they can contain additional repaired geometry, often represented as *GeoSets*, wireframes and other non-physical reference geometry. These can clutter the assembly browser, make models harder to navigate and create unnecessary visual complexity.

This tool aims to automate the removal of these unwanted GeoSets and associated repaired geometry once an imported Revit model has been loaded into Inventor, leaving only the actual physical model geometry behind.

**Key objectives:**
- Automatically identify unwanted GeoSets within imported Revit models.
- Remove redundant repaired geometry and associated wireframes.
- Retain the physical model geometry and components.
- Keep the Inventor assembly browser clean and organised.
- Reduce manual cleanup time when working with large imported Revit models.

**Purpose:** To streamline the workflow between Autodesk Revit and Autodesk Inventor by automating repetitive geometry cleanup tasks through a simple, accessible iLogic button.
