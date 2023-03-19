# Belly Button Biodiversity Dashboard

## Background

The Belly Button Biodiversity dataset is a collection of information about the microbes that inhabit human navels.
This dataset has revealed that a small group of microbial species, known as operational taxonomic units (OTUs), are present in more than 70% of individuals, while the remaining species are relatively uncommon.
In this assignment, I will create an interactive dashboard to explore this dataset and visualize the prevalence of different OTUs in the human navel microbiome.

## Instructions

Complete the following steps to build the dashboard:

 **1-** Use the D3 library to read in ***samples.json*** from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

**2-** Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

* Use ***sample_values*** as the values for the bar chart.

* Use ***otu_ids*** as the labels for the bar chart.

* Use ***otu_labels*** as the hovertext for the chart

**3-** Create a bubble chart that displays each sample.

* Use ***otu_ids*** for the x values.

* Use ***sample_values*** for the y values.

* Use ***sample_values*** for the marker size.

* Use ***otu_ids*** for the marker colors.

* Use ***otu_labels*** for the text values

**4-** Display the sample metadata, i.e., an individual's demographic information.

**5-** Display each key-value pair from the metadata JSON object somewhere on the page.
**6-** Update all the plots when a new sample is selected.

## How to Use

To use the dashboard, open the ***index.html*** file in a web browser. You will see the sample selection dropdown menu,
and the corresponding horizontal bar chart, bubble chart, and metadata information.
Use the dropdown menu to select a new sample and see the plots and metadata update accordingly.

## Credits

This dashboard was built using ***D3.js***, ***Plotly.js***, with data provided by the Belly Button Biodiversity project from the Public Science Lab.
