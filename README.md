# holodeck-configs
Contains the configuration files for Holodeck's downloadable packages.

Please file all issues with the [holodeck](https://github.com/BYU-PCCL/holodeck)
master project.

## Documentation
Documentation for each package and scenario can be found at Holodeck's 
ReadTheDocs site.

[Package Docs](https://holodeck.readthedocs.io/en/latest/packages/packages.html)
 - [DefaultWorlds](https://holodeck.readthedocs.io/en/latest/packages/DefaultWorlds/DefaultWorlds.html)
 - [Dexterity](https://holodeck.readthedocs.io/en/latest/packages/Dexterity/Dexterity.html)

## Structure
Each folder corresponds to a package name. Inside each folder there must be at 
least one package-level configuration file, `config.json`, and at least one 
scenario config file for each world in that package, following the format 
`WorldName-ScenarioName.json`.

This repository is used in the automated building process, every `.json` file in 
the package folder is copied to the root of the `.zip` output file.
