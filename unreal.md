# Unreal

## Table of contents

- [Project Structure And Naming Conventions](#project-structure-and-naming-conventions)
  - [Project Structure and Asset Naming](#project-structure-and-asset-naming)
  - [Asset Naming](#asset-naming)


## Project Structure And Naming Conventions

### Project Structure and Asset Naming

Project Structure and  Asset naming is critical when working with teams of people.   It is even more critical when using Unreal Engine, as all the assets live within a single project.     Teams should establish Project Structure and Naming conventions early in the pre-production stage and stick with it. 
Luckily, your team does not need to come up with their own.    Michael Allar’s UE5 Style Guide presents comprehensive and principled naming conventions along with a framework for structuring an Unreal Engine project.

[ue5-style-guide](https://github.com/Allar/ue5-style-guide)

### Asset Naming

**Naming conventions should be followed strictly and enforced as the law.** 
A project with a detailed naming convention that is strictly adhered to is able to have its assets managed, searched and maintained. The key to a successful project with any style guide is that everyone gets familiar with it: “All structure, assets, and code in any Unreal Engine 5 project should look like a single person created it, no matter how many people is work on it.”

#### The naming conventions assets should follow the formula: 

**Prefix_BaseAssetName_Variant_Suffix** with the following describing the variables:
  - Prefix - the Prefix is generally an acronym based on the asset type, (e.g. SM_ for Static Mesh).
  - Suffix - the Suffix is generally an acronym based on a specific asset sub-type, (e.g. _S for specular texture).
