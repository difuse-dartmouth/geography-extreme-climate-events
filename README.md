# data-migration-template
Template used for data migration, DIFUSE 23W.

## SOCY 00 DIFUSE Module (Spring 2020) ##

#### Contributors: Jane Doe ('24), Muhammad Aronno ('23), and Professor Craig Silsby (PI) ####

![Sample title slide for a DIFUSE module.](additional/repository_assets/sample_module.JPG)

##### Module Description #####
This module is used to learn and then apply dyad interaction modeling using an R-based programming module, with the help of the package 'dyAddon' and open-sourced datasets from the Data of Sets.

This module was developed through the DIFUSE project at Dartmouth College and funded by the National Science Foundation award IUSE-1917002.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

##### Folder Structure #####

The repository is structured with the module development timeline in mind. It is organized according to development milestones.

For instructors and interested parties, the history of this repository (with detailed commits), can be found [here](https://github.com/difuse-dartmouth/data-migration-template/commits/main/).

```
main\
    preliminary\
        difuse_scaffolding\
        course_materials\
    development\
    completed_module\
        public\
            logistics\
                installation.docx
            data\
                assignment1_data.csv
                assignment2_data.m
                assignment2_data.mlx
                assignment3_data.xlsx
            components\
                assignment1\
                    assignment1_instructions.docx
                    assignment1_instructions.pdf
                    assignment1_data.csv
                assignment2\
                assignment3\
        solutions\
            components\
                assignment1\
                    assignment1_solutions.mlx
                assignment2\
                    assignment2_solutions.pdf
                assignment3\
                    assignment3_solutions.ipynb

    additional\
        sample_datasets\
            sample_data1.csv
            sample_data2.csv
            sample_data3.xlsx
        repository_assets\
            difuse_logo.png
            creative_commons.jpg
        notes.txt
```

**On Repository Structure:**
* **Preliminary**: Contains all files pre-requisite to module development. ```difuse_scaffolding``` is provided by DIFUSE, and ```course_materials``` (including course syllabus, relevant assignments, etc.) are provided by course instructor.
* **Development**: Contains all files that developers deem necessary to be stored on GitHub. Given the uniqueness of each module and the abstraction that DIFUSE provides, the development team is allowed to use the platform they prefer (or as discussed with instructor)
* **Completed_Module**: DIFUSE is committed to increasing data science education, and shares its work publicly as an NSF-funded grant. In order for these modules to remain usable by course instructors, DIFUSE removes the solutions to module assignments in its public release. Thus, the public repository will have the ```solutions\``` folder removed.
* **Additional**: At the discretion of module developers, contains sample datasets and other materials. May include on-ramp tutorials for module platforms (e.g. MATLAB Onramp), or anecdotes of challenges in implementation (e.g. data sources that were inaccessible or difficult to acquire).
