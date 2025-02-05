# ecosystem-dashboard-for-arm
The Arm Software Ecosystem Dashboard is available at https://www.arm.com/developer-hub/ecosystem-dashboard/servers-and-cloud-computing/

This repository is maintained by Arm and contains the source files for the Arm Software Ecosystem Dashboard, providing in
formation on software packages that work on Arm. 

This data is sourced from Arm and our wide software ecosystem. While we make our best efforts to keep this dashboard accu
rate, there are no guarantees of data correctness due to the ever-evolving software landscape.  

# How To Contribute:

* To contribute new package data (or improve existing package data):
    * Fork this repo and submit pull requests; follow the step by step instructions in [Contribution guidelines](/contrib.md).
* Log an issue with package data(or other general issues)
    * Log a [issue on GitHub](https://github.com/ArmDeveloperEcosystem/ecosystem-dashboard-for-arm/issues)

Note that all site content, including new contributions, is licensed under a [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/).
Source repository for arm ecosystem dashboard that lists packages that work on Arm

# Directory Structure

This site is built on the [Hugo](https://gohugo.io/) web framework, ideal for generating static websites. Below is a brief description of the key files and directories:

  * /content
    * contains all package source data
  * /themes
    * where the html elements are defined to render /content into stylized HTML
  * LICENSE files
    * where the license information is contained
  * config.toml
    * where the high-level website configuration settings are defined

