


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
