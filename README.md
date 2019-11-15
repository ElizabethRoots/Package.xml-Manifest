# Package.xml Manifest
The purpose of this repo is just to unofficially collect a sample package.xml manifest and list metadata types for migrating Salesforce metadata using a package.xml manifest and the Salesforce CLI. This sample is not an exclusive list, but should be good to get started as users get familiar with writing a package.xml manifest. <br/> <br/>
Want to learn more about how to write a Package.xml Manifest? Check out Salesforce Trailhead badge [Package.xml Metadata Management](https://trailhead.salesforce.com/en/content/learn/modules/package-xml).
<br/><br/>
**DISCLAIMER:** This is not aiming to be an exhaustive list of metadata types in the package.xml manifest. This project is only sharing out a sample package.xml manifest with the wide variety of metadata types that can be used.

## Getting the Tools
Geting set up. 
1) Make sure you have the Salesforce CLI installed. If you don't have it installed you can download and install it from [here](https://developer.salesforce.com/tools/sfdxcli). If you do have it installed, then check to make sure you are on the latest by running `sfdx update` command. 
2) Install VS Code
3) Install Salesforce Extension in VS Code  

## Whats in this project?
There are many components within this project, but ultimately, the `Package.xml` file is likely what you came here for. In this project, I have included an sfdx project structure, the package.xml sample manifest, and a list of resources below for you to learn more.
* SFDX Project with sample metadata (objects, fields, classes, perm sets)
* Package.xml file related to the objects in the sfdx project
* Sample package.xml file
* Helpful resources

## Wait, can't the CLI create a package.xml for you?
With specific commands, the Salesforce CLI absolutely can create a package.xml for you! The challenge though is not all metadata types are declaratively available through the UI (such as Profiles). So when the CLI creates the package.xml manifest off of a package, the metadata is limited to just those metadata components within that package. 

Learning how to write a package.xml file and use it to retrieve and deploy metadata will also make you more of (what I affectionately call), a Legendary Salesforce Admin and Developer. The problem then becomes, what metadata type should I use? Well, thats where this project comes in! This package.xml sample is just that, a sample of metadata types and how they are written. 


## Want to be a contributor?
Awesome-sauce! You are more than welcome to contribute to this project. Please follow the development guides and best practices highlighted in the 'Resources' section of this document. 

## Resources
* [Trailhead: Package.xml Metadata Management](https://trailhead.salesforce.com/en/content/learn/modules/package-xml)
* [Salesforce Metadata API Developer Guide: Package.xml Sample Manifest](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/manifest_samples.htm)
* [Salesforce Metadata API Developer Guide: Metadata Types](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/meta_types_list.htm)


**DISCLAIMER**: This project is not official documentation in any way or form. This project is of my own words. Always refer to the official documentation and training guides provided by Salesforce.