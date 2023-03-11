Annex of FLINT Analysis
=======================

FLINT Model Implementations:
----------------------------

-   `GCBM Carpathiams <https://github.com/moja-global/GCBM.Carpathians>`__

-   `GCBM Belize <https://github.com/moja-global/GCBM.Belize>`__

-   `GCBM Colombia <https://github.com/moja-global/GCBM.Colombia>`__

-   `GCBM Chile Implementation <https://github.com/moja-global/GCBM.Colombia>`__

-   `GCBM Pudget Implementation <https://github.com/mHienp/GCBM.Puget>`__ 

Data Processings:
-----------------

-   `Data Preprocessing for GCBM.EmeraldEdge <https://github.com/mHienp/GCBM.EmeraldEdge.Data>`__ 

-   `Data preprocessing for GCBM.Carpathians <https://github.com/derha/GCBM.Carpathians.Data>`__ 

-   `Data preprocessing for the GCBM implementation in Chile <https://github.com/moja-global/GCBM.Chile.Data_Preprocessing>`__ 


Investigation of Forest Ecosystems using Moja Global Land Sector Datasets:
--------------------------------------------------------------------------

-   `Exploratory Data Analysis of Carpathian Montane Forests <https://github.com/derha/moja-global/blob/main/carpathian_montane_forests.ipynb>`__

-   `Getting familiar with Moja Global Datasets <https://github.com/Shubhams-2002/MojaGlobalDatasets/blob/main/Moja_global_datasets_done.ipynb>`__

-   `Study of Climatic Shifts and Emission Scenarios of Western Ghats of India <https://github.com/Shubhams-2002/MojaGlobalDatasets/blob/main/WesternGhats.ipynb>`__

-   `Deccan Thorn Scrub Forest Analysis <https://github.com/anamika-yadav99/moja-global_task/blob/main/Forest_analysis.ipynb>`__

-   `Exploratory Data Analysis of Congo Basin <https://github.com/saranda-2811/moja-global22/blob/main/moja_global_forest1.ipynb>`__

-   `Exploratory Data Analysis of World Heritage Sinhara Forest <https://github.com/thushariii/MojaGlobal2022/blob/main/sinharaja_Rain_forest.ipynb>`__

-   `Exploratory Data Analysis of Białowieża Forest <https://github.com/coloeus-monedula/moja-global-22/blob/main/forest.ipynb>`__

-   `Exploratory Data Analysis of Cross River Forests of Nigeria <https://github.com/Boluwape/Outreachy_Boluwape_2022./tree/main/2022-10_Contribution-Outreachy>`__

-   `Exploratory Data Analysis of Ecological Zones of New Zealand <https://github.com/maazingly/Outreachy-mojaglobal-EDA-NZ/blob/main/Geo%20EDA%20-%20New%20Zealand.ipynb>`__

-   `Study of types of forests in Malawi vs location of planted forests <https://github.com/Iman-L/Outreachy_iman_linje_2022/blob/main/2.%20Forest%20Types%20of%20Malawi.ipynb>`__

-   `Exploratory Data Analysis of areas of Himachal Pradesh of India <https://github.com/aldeav/Outreachy_Ananyashree_2022/blob/main/1_Data_Analysis.ipynb>`__

-   `Exploratory Data Analysis of New Guinea Freshwater Swamp Forests <https://github.com/Hafsah2020/Outreachy_Hafsah_Anibaba_2022/blob/main/favourite_forest_analysis.md>`__

-   `Exploratory Data Analysis of Yukon Interior Dry Forests <https://github.com/mHienp/mojaglobal/blob/main/Yukon%20Interior%20dry%20forests.ipynb>`__





Please make use of the Project Structure when contributing to this Handbook to save time -

1. To understand the Handbook's blueprint, take a look at the Project Structure.

2. After that, you can browse the website to see which sections need improvement.

3. Rather than searching linearly through folders, use this Project Structure again to locate the file you want to improve.

4. Submit a pull request after navigating directly to the file you wish to edit.

```text

  ├── Chapter 1                     # Understanding Climate Science and Carbon Models
       ├── index.rst                # Landing page of Chapter 1
       ├── section_one.rst          # The Organisations behind the Climate Mitigation Steps
       └── section_two.rst          # How does FLINT help solve issues arising from Climate Change
  ├── Chapter 2                     # Chapter 2: Introduction to the Full Lands Integration Tool
       ├── index.rst                # Landing page of Chapter 2
       ├── section_one.rst          # Modules
       ├── section_two.rst          # Inputs 
       └── section_three.rst        # Output
  ├── Chapter 3                     # Introduction to Generic Carbon Budget Model
       ├── index.rst                # Landing page of Chapter 3
       ├── section_one.rst          # End-to-end workflow for the GCBM Analysis
       ├── section_two.rst          # Post-processing
       └── section_three.rst        # What is the effect of running the model without disturbance?
  ├── Chapter 4                     # The Work DVC Plays in the Land Sector Repo
       ├── index.rst                # Landing page of Chapter 4
       └── section_one.rst          # How to create a reproducible pipeline with Moja Global Dataset.
  ├── Chapter 5                     # Running a GCBM Simulation
       ├── index.rst                # Landing page of Chapter 5
       ├── section_one.rst          # Project structure and directory hierarchy overview
       ├── section_two.rst          # Setting up our GCBM environment
           ├── index.rst            # Landing page of Section 2
           ├── section_twoa.rst     # Installing Python
           ├── section_twob.rst     # Installing Microsoft Access Database Driver
           ├── section_twoc.rst     # Installing Visual C++ Redistributable Packages
           └── section_twod.rst     # Update GCBM Run Script
       ├── section_three.rst        # Spatial data preparation(jupyter notebook)
       └── section_four.rst         # Tiler Configuration
  ├── Chapter 6                     # Climate Projections
       ├── index.rst                # Landing page of Chapter 6
       ├── section_one.rst          # How do we expect our world to change?
       ├── section_two.rst          # What does the increase in CO2 mean for forests?
       └── section_three.rst        # Changing Patterns
  ├── static                        # Folder with static files 
       ├── custom.css               # CSS styles of Handbook
  ├── .gitignore                    # ensures that certain files remain untracked by Git
  ├── Appendices.rst                # Vision: The reproducible science stack
  ├── Conclusion.rst                # Conclusion of the Handbook
  ├── Makefile                      # Defines which parts of program needs to recompile
  ├── README.md                     # Gives an overview of the entire Handbook 
  ├── conf.py                       # Contains all configurations needed to customize Sphinx input output
  ├── index.rst                     # Home page of the Handbook
  ├── make.bat                      # Batch file that automates routine tasks with scripts
  └── requirements.md               # Contains all required dependencies to run the project  
```
  
```website 
  ├──  blog                                                # blogs of contributors
  ├──  case studies                                        # contents of case studies
  │    ├── introduction to FLINT modules                   # contents of intro to FLINT
  │    ├── introduction                                    # contents of intro
  │    └── powering deforestation prediction using AI      # contents of powering deforestation
  ├──  community                                           # contents of community
  │    ├── writing groups                                  # contents of writing group
  │    
  ├──  docs                     # Data for site metadata and static blog such as images
  ├── scripts                     # Scripts used in the build and dev processes
  ├── next.config.js              # Next.js configuration file
  ├── netlify                     # Code that runs on Netlify
  │    ├── edge-functions         # Netlify Edge-Functions code
  ├── postcss.config.js           # PostCSS configuration file
  └── tailwind.config.js          # TailwindCSS configuration file
```
