# sf-land 

## Welcome to the VS Code Extension - sf-land!

- [Install sf-land ](https://marketplace.visualstudio.com/items?itemName=mohanChinnappan.sf-land)

## Features
### Salesforce specific - Login required
-  [Login into Salesforce and create an Auth JSON file](#login1)
-  [Login with Auth JSON File](#login2)
-  [Runs a given SOQL and provides results output in HTML](#sfquery)

### Code Scan (Salesforce Login not required)
-  [Runs PMD Scan](#pmdscan)

### i18n
- [Translate Using Google Translate](#gtranslate)

### Word Cloud
- [Draw Word Cloud](#wordcloud)


### GraphViz
- [Draw GraphViz Graph](#gviz)

### REST client
- [Rest Client for Salesforce and Generic](#restc)

---

<a name='login1'></a>
### SF-Land Login into Salesforce to get Auth File
- Login into Salesforce and create an Auth JSON file
    - Uses SFDX for this operation

<a name='login2'></a>
### SF-LAND Login with Auth JSON File
- Login into the Salesforce Org with the given Auth JSON file

<a name='sfquery'></a>
### SF-LAND Run SOQL Query
- Runs a given SOQL and provides results output in HTML
![query results](https://raw.githubusercontent.com/mohan-chinnappan-n/sf-land-docs/master/img/sf-land-query-results-1.png)
![query results - 2](https://raw.githubusercontent.com/mohan-chinnappan-n/sf-land-docs/master/img/sf-land-query-results-2.png)


<a name='sflimits'></a>
### SF-LAND Run Org Limits
-  Display Limits info in your org
![limits results](https://raw.githubusercontent.com/mohan-chinnappan-n/sf-land-docs/master/img/sf-land-org-limits-1.png)

---
<a name='pmdscan'></a>
### SF-LAND Run PM Scan
- Runs PMD Scan
    - Setup PMD executable as per this [Doc](https://github.com/mohan-chinnappan-n/cli-dx/blob/master/mdapi/pmd-codescan.md)

- Demo
- ![PMD Report Demo](https://raw.githubusercontent.com/mohan-chinnappan-n/kural-docs/master/img/new_pmd-report-1.gif)
---
<a name='gtranslate'></a>
### SF-LAND Google Translate
- Translate the current editor text using Google Translate 


<a name='wordcloud'></a>
### SF-LAND Draw Word Cloud
- Draws Word Cloud for  the current editor text
![WC-1](https://raw.githubusercontent.com/mohan-chinnappan-n/sf-land-docs/master/img/sf-land-wc-1.png)

<a name='gviz'></a>
### SF-LAND Draw graphViz graph
- Draws graphViz graph for the current editor text
![WC-1](https://raw.githubusercontent.com/mohan-chinnappan-n/sf-land-docs/master/img/sf-land-graphviz-1.png)

<a name='restc'></a>
### SF-LAND REST Client
- input
```json
{
    "method": "SFGET",
    "url":  "sobjects/Opportunity/describe"
}
```
- Response will be rendered in a VS Code window
![Demo restc](https://raw.githubusercontent.com/mohan-chinnappan-n/sf-land-docs/master/img/sf-land-restc-1.webm.gif)



---
#### Stay tuned... More coming...
---

**Enjoy!**
- Built by [Mohan Chinnappan](https://www.linkedin.com/in/mohan-chinnappan-232ab632/) with ♥


