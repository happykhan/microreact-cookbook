---
title: Exploring sequence types
description:  What are the dominating sequence types (STs) in Colombia?
authors:
    - Nabil-Fareed Alikhan
date: 2024-03-25
---

In this recipe we will revisit aspects of the previous recipes in this section and try to interpret the data. In particular, we will chart and review the collected information regarding the isolates' sequence type. The final output will be this chart below. 

![ST Chart](tutorial/st-shart.png)


!!! info "What is a sequence type (ST)?"
    The **sequence type (ST)** refers to a unique combination of alleles at the sequenced loci. Each unique ST represents a distinct strain or clone within the bacterial species under study. MLST data can be used for various purposes, including epidemiological studies, tracking the spread of infectious diseases, and understanding bacterial population dynamics. Sequence types are defined by MLST, which stands for Multi-Locus Sequence Typing. It is a molecular typing method used to characterize the genetic diversity of bacterial strains within a species. In MLST, several housekeeping genes are sequenced from each bacterial isolate. These genes are generally conserved across strains but can accumulate mutations over time. By comparing the sequences of these genes, we can determine the genetic relatedness between different isolates.

## Microreact features demonstrated

* Creating a new chart
* Customising a chart
* Updating an existing view
* Saving changes to a Microreact project

## Tutorial

You should be using the project we opened in the previous steps. Please see [Creating an editable project](./step-1.md) and follow the instructions if not. Now that you've created one chart, you can create another one! Click on the Pen symbol on the right hand side and click on "Create New Chart".

![Task 3: What are the dominating STs in Colombia? Now that you've created one chart, you can create another one! Step 1: Go to the "Pen: symbol on the right hand side and click on the"Create New Chart".](tutorial/create%20new%20chart.png){width="60%"}

The new chart can stay right on top of the previously created one. Notice a white canvas on top of the previously generated chart.

![Task 3: What are the dominating STs in Colombia? Step 2: The new chart can stay right on top of the previously created one.](tutorial/drag%20new%20chart.png){width="80%"}

![Task 3: What are the dominating STs in Colombia? Step 3: Notice a white canvas on top of the previously generated chart.](tutorial/new%20chart.png){width="80%"}

Once again, from the Chart Type dropdown menu, select "Bar Chart", and when the new view shows up on the "X Axis Column", select ST.

![Task 3: What are the dominating STs in Colombia? Step 4: Once again, from the Chart Type dropdown menu, select "Bar Chart", and when the new view shows up on the "X Axis Column", select ST.](tutorial/chart_STs.png){width="80%"}

A new chart will appear. The labels on the x-axis appear squished and they are hard to read. Drag the panel divider on the left hand side of the chart, to increase the width of the panel.

![Task 3: What are the dominating STs in Colombia? Step 5: A new chart will appear. The labels on the x-axis appear squished and they are hard to read. Drag the panel divider on the left hand side of the chart, to increase the width of the panel.](tutorial/STs%20squished.png){width="80%"}

The information on the x-axis should be readable now. The 3 most abundant STs are ST11, ST258 and ST512.

![Task 3: What are the dominant STs in Colombia? Step 6: The information on the x-axis should be readable now. The 3 most abundant STs are ST11, ST258 and ST512.](tutorial/STs%20wide.png){width="80%"}

Click the "Views" panel on the left hand side, hover over "Kpn Colombia", click on the three dots on the corner of the view and hit "Update View". And finally go to the Save icon on the right corner, press the icon and choose "Update This Project.

![Task 3: What are the dominant STs in Colombia? Step 7: Click the "Views" panel on the left hand side, hover over "Kpn Colombia", click on the three dots on the corner of the view and hit "Update View"](tutorial/update%20view.png){width="40%"}

![Task 3: What are the dominant STs in Colombia? Step 8: Go to the Save icon on the right corner, press the icon and choose "Update This Project"](tutorial/save%20project.png){width="60%"}