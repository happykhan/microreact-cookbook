# Welcome to the Microreact Cookbook

This is a *cookbook* for Microreact. Available at https://happykhan.github.io/microreact-cookbook/ or https://microreact-cookbook.netlify.app/


## About Microreact 

Microreact is a web application designed for visualizing and sharing genomic epidemiology and phylogeography. It provides a platform for researchers to upload their genetic data, such as genomic sequences from pathogens like viruses or bacteria, and visualize them in the context of geographical and temporal information. Microreact allows users to generate interactive maps and phylogenetic trees, enabling them to explore patterns of transmission and evolution of pathogens. This tool is particularly useful in the field of infectious disease research, as it helps in tracking the spread of diseases and understanding their dynamics at a molecular level.

## Install and serve
```
# Clone the repo
git clone git@github.com:happykhan/microreact-cookbook.git
cd microreact-cookbook

python3 -m venv .venv
pip install mkdocs-material

mkdocs serve
```

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Other Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## How to contribute

Contributions are welcome, either via a direct commit or as a pull request. Recipes and tutorials are written in markdown in the `docs` folder. 

* Examples should be self contained examples, with all the required raw data. 
* Try to show one, perhaps two, features in a single example 
* Keep it brief 
* Copy and use the template in `recipe-template` for consistency. 

## Wishlist of recipe 

Please add ideas for recipe here. 

* Charting with Vega.
* Standard metadata + tree vis. 
* Tree vis + metadata blocks. 
* Building multiple views.
* Exporting images - for a publication. 
