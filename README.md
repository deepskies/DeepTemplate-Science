This template is designed to give a framework for public distributions of "science" projects. 
It is a guideline, showing the minimum things recommended to include with your public repository, 
to make your results easily replicable. 
It is not exhaustive by any means, nor is everything here strictly required in all cases! 
Please consider this as a loose list of things considered "nice to have", and as reference material above all. 

# DeepSkies Science Repo Template 
Include status links to different outside resources, such as build info, paper info, license, etc. 
You can select your license from the [choose a license page.](https://choosealicense.com/licenses/), and then change the name of the license in the badge and link included. 
For workflows, change the name of the repo listed in the img.shields link to point to your repo and workflows.

[![status](https://img.shields.io/badge/arXiv-000.000-red)](arxiv link if applicable)
[![status](https://img.shields.io/badge/PyPi-0.0.0.0-blue)](pypi link if applicable)
[![status](https://img.shields.io/badge/License-MIT-lightgrey)](MIT or Apache 2.0 or another requires link changed)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/owner/repo/build-repo)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/owner/repo/test-repo?label=test)

Your overview should contain a brief summary of the project, and figures and examples showing input and output. 

## Installation 
Information about install. 
Please consider using the pip distribution workflow included in this template to streamline install for other users. 

Example: 

To install with pip: 
> pip install git+https://github.com/DeepSkies/science_template.git
>
This will set up a virtual environment, which can b  e run with on mac or linux
> source venv/bin/activate
>
Or on windows with 
> venv\Scripts\activate.bat

Verify installation is functional is all tests are passing
> pytest

Additionally, include how to install from source (via git clone)

## Quickstart
Description of the immediate steps to replicate your results, pointing to a script with cli execution. 

Example: 

To run full model training: 
> python3 train.py --data /path/to/data/folder

To evaluate a single ""data format of choice""
> python3 eval.py --data /path/to/data

## Documentation 
Please include any further information needed to understand your work. 
This can include an explanation of different notebooks, basic code diagrams, conceptual explanations, etc. 
If you have a folder of documentation, summarize it here and point to it. 

## Citation 
Include a link to your bibtex citation for others to use. 

```
@article{key , 
    author = {You :D}, 
    title = {title}, 
    journal = {journal}, 
    volume = {v}, 
    year = {20XX}, 
    number = {X}, 
    pages = {XX--XX}
}

```

## Acknowledgement 
Include any acknowledgements for research groups, important collaborators not listed as a contributor, institutions, etc. 
