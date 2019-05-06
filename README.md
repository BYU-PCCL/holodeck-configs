# holodeck-configs
Contains the configuration files for Holodeck's downloadable packages.

Each folder corresponds to a package name. Inside each folder there must be at least 
one package-level configuration file, `config.json`, and at least one scenario config
file for each world in that package, following the format `WorldName-ScenarioName.json`.

This repository is used in the automated building process, every `.json` file in the
package folder is copied to the root of the `.zip` output file.
