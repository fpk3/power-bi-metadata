# power-bi-metadata
Power BI - document Power BI metadata using localhost connection

Template Description: 
(1) Open a report in Power BI Desktop. 
(2) Open DAX Studio and connect to the open report. 
  PARAMETERS: 
  (a) localhost is displayed in the bottom frame of DAX Studio. Type the full localhost:xxxxx or just the number part. 
  (b) catalog_name is a long string of characters, which can be found by running this query in DAX Studio and using the result: SELECT [CATALOG_NAME] FROM $SYSTEM.DBSCHEMA_CATALOGS • DAX Studio is available at https://daxstudio.org/

The technique used in this template is documented at: 
Chris Webb's BI Blog: Analysing Power BI DMV Queries In Power BI Desktop
https://blog.crossjoin.co.uk/2016/02/01/analysing-power-bi-dmv-queries-in-power-bi-desktop/

Documents 1-to-many relationships in Power BI models. 
• Many-to-many relationships not supported.
• Bi-directional filtering and bi-directional security not supported.
• Inactive relationships not supported. 
