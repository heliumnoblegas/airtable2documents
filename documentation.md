---
layout: default
title: How it works
navigation_weight: 2
---

# How it works

1. You need to get your API key of AirTable.
Got to https://www.airtable.com/account to get your API key

2. You need to chooese which Airtable base and table as the data source
Currently, it only support one table

3. The App would pull the fields from AirTable. You need to make sure the AirTable has at least 1 record

4. Enter variables into your doc by using the syntax: {{field name}}

   Example
   
   ```
   First of all, we would like to thank you and the rest of the team at {{Official Company Name}}. We are honored to be considered for the {{Project Name}} project.
   Date of submission {%raw%}{{Date}}{%endraw%}
   Contract valid for {%raw%}{{Days}}{%endraw%}
   Description of work: {%raw%}{{Works Description}}{%endraw%}
   Case Study: {%raw%}{{Case study}}{%endraw%}
   ```
   
Press `generat` button, it would generate the document one by one, depends on how many records you have


