---
layout: project
type: project
image: img/percolates-yes.png
title: "Percolation"
date: 2022
published: true
labels:
  - java
  - algorithms
summary: "A simple Percolation Project done for the Coursera Algorithms course."
---
Before returning to college and finishing my upper level computer science courses, I thought it might be a good idea to refresh my programming skills. So, I made this percolation program in Java in Fall 2022 as a part of Coursera's free online algorithms course. 

Percolation refers whether a substance is able to flow through a material through connected pathways. For example, if water can flow through a system of rocks. A system percolates if the substance can reach a given end point from a start point. In this case, the system is represented by an nxn grid, with sites that are either open or closed. The system will percolate if an open site on the top row is connected to an open site on the bottom row. 

The program consists of two classes: Percolation and PercolationStats. Percolation has methods to open a site given a grid, check if a site is open, check if a site is full (meaning the site can connect to an open site on the top row), return the number of open sites, and lastly a boolean method to determine if the system percolates. The PercolationStats class has methods to report useful information after running experiments on different sites. The goal is to find the probability that a system will percolate with sites randomly opening with probability p. 

<img class="img-threshold" width = "300px" src="../img/percolation-threshold.png">

The "Monte Carlo simmulation" runs this computation experiment: Initiliaze all sites to be blocked, the choose a site randomly to open from sites that are blocked, and open the site. Repeat until the system percolates. The percentage of sites that are open when the system percolates gives the "percolation threshold". 

source code: <a href="https://github.com/wsdwight1/Percolation/blob/main/Percolation.java"><i class="large github icon "></i>Percolation</a>



