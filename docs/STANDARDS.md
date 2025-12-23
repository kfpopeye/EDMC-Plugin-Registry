# EDMC Plugin Browser Standards for Listing

Welcome, plugin developer! We're excited to have you here. In order for your plugin to be listed in the official EDMC plugin browser, your plugin must meet certain standards and expectations. These standards exist to help keep the EDMC environment clean, functional, and easy to use for all of our users. 

When submitting your plugin for listing, you agree to follow these standards on an ongoing basis. Failure to uphold the standards may result in your plugin being de-listed from the plugin browser. 

## Compatibilty
You are responsible for keeping your plugin compatible with the most recent versions of EDMC. When EDMC adds or removes functionality, you are responsible for keeping your plugin updated in a timely manner. If a plugin is not updated between versions or significant numbers of users report the plugin is not compatible with the most recent versions of EDMC, your plugin will be removed.

## Licensing
EDMC is licensed under the GNU GPL v2 license. To be listed, your plugin must also be open source and compatible with the GNU GPL v2 license. Generally speaking, this means your code must also use the GNU GPL v2 license.

## Respect for the Ecosystem
You agree that your plugin will be a good steward of the Elite: Dangerous community's resources. Plugins may not perform actions that break Frontier's EULA, provide malicious content or functionality, or cause a disruption to other community services. For example, scraping community webpages instead of using API calls may be cause for a plugin listing to be denied. 

Similarly, impersonation or squatting on valuable namespace will not be allowed. Plugins should be named and use namespaces that generally reflect te purpose of the plugin. Plugins should not be written to "jump to the top" of the directory structure (such as "1TheBestPlugin") or add tags that give the impression that the plugin provides more functionality than it actually provides.

## Least Privilege 
Plugins may not bundle, package, or include more resources or content than is required for the plugin to perform its functions. As an example, plugins may not include content that scrapes browser history if the plugin has no cause for this access. Similarly, plugins may not bundle extra Python modules that aren't needed for the plugin's purpose. 

Furthermore, plugins shall be written so as to not request more system privileges than required. 

## Coding Standards
Code must generally be written to a high standard. This means that code should be readable, well-documented, and conform to the best practices of the language in use. All code must be manually reviewed prior to a plugin submission being accepted for listing. If our manual reviewers can't understand the code or follow it, we can't list it. 

In general, plugins who use Python code should be written generally inline with PEP8 standards, and should use Python 3 coding standards. 

## Version Control
Plugins must use Semantic Versioning in order to be listed in the EDMC plugin browser. This version must be available in a VERSION constant in the plugin's load.py. 