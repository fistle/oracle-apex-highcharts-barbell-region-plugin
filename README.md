# oracle-apex-highcharts-barbell-region-plugin
An oracle APEX region plugin to show a HighCharts barbell chart

Demo
Add a High chart dumbbell chart to your Oracle APEX app. 

https://kjwvivmv0n5reuj-apexkqor.adb.uk-london-1.oraclecloudapps.com/ords/r/test1/apex-plugins/highchart-dumbbell

Data points defined in the SQL query, chart options defined in attributes

Tested on APEX version 22.1

Please note that commercial use of Highcharts requires a commercial license. For testing and demonstration purposes (POC), Highcharts can be used free of charge. Non-profit organisations, schools and personal websites are qualified for the free license.

Instructions 
---------------------------------------------------
Download the plugin

Install the plugin - Shared Components->plugins->import
Create a new region with type highcharts-dumbell
Change source type to SQL Query then copy the demo SQL in.
You can leave attributes blank to start as it will use default settings.

Demo SQL
---------------------------------------------------
select 'Australie' as VALUE_1, 60 as VALUE_2, 70 as VALUE_3 from DUAL

UNION

select 'New Zealand' as VALUE_1, 70 as VALUE_2, 80 as VALUE_3 from DUAL

UNION

select 'Scotland' as VALUE_1, 80 as VALUE_2, 90 as VALUE_3 from DUAL

UNION

select 'England' as VALUE_1, 50 as VALUE_2, 70 as VALUE_3 from DUAL

UNION

select 'France' as VALUE_1, 55 as VALUE_2, 90 as VALUE_3 from DUAL

UNION

select 'Spain' as VALUE_1, 67 as VALUE_2,98 as VALUE_3 from DUAL

UNION

select 'United States' as VALUE_1, 82 as VALUE_2, 89 as VALUE_3 from DUAL

UNION

select 'Peru' as VALUE_1, 70 as VALUE_2, 79 as VALUE_3 from DUAL

UNION

select 'Portugal' as VALUE_1, 55 as VALUE_2, 95 as VALUE_3 from DUAL

UNION

select 'India' as VALUE_1, 65 as VALUE_2, 85 as VALUE_3 from DUAL

UNION

select 'Senegal' as VALUE_1, 45 as VALUE_2, 65 as VALUE_3 from DUAL


Attributes
---------------------------------------------------
Chart name - empty shows no title

Chart sub name- empty shows no sub title

Series name - empty shows no series name

Show credits - false to remove credits on bottom right



