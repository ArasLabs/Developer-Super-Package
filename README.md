# Developer Super Package

An all-in-one package for Aras Innovator developers that contains several useful Aras Labs projects.

The following Aras community projects are contained in this super package
1. [Custom Search Mode](https://github.com/ArasLabs/custom-search-mode/)
2. [Find Active Debuggers](https://github.com/ArasLabs/find-active-debuggers/)
3. [Find Parent Package](https://github.com/ArasLabs/find-parent-package/)
4. [CUI Add to Package](https://github.com/ArasLabs/cui-add-to-package)
5. [Run Client Method](https://github.com/ArasLabs/run-client-method/)
6. [Tree Grid View Sample](https://github.com/ArasLabs/tree-grid-view-sample/)

## Project Details

#### Built Using:
Aras 11.0 SP12

#### History:
Release | Notes
--------|--------
[v1](https://github.com/ArasLabs/Developer-Super-Package/releases/tag/v1) | Initial Release
[v2](https://github.com/ArasLabs/Developer-Super-Package/releases/tag/v2) | Validated in 31, Replaced Method Editor themes with CUI Add to Package
#### Versions Tested:
Release | Aras
--------|-------
[v1](https://github.com/ArasLabs/Developer-Super-Package/releases/tag/v1) | 11.0 SP12
[v2](https://github.com/ArasLabs/Developer-Super-Package/releases/tag/v2) | Release 31

#### Browsers Tested:
The tested browsers for each of the submodules can be found in the READMEs of the individual projects

## Installation

#### Important!
**Always back up your code tree and database before applying an import package or code tree patch!**

### Pre-requisites

1. Aras Innovator installed (version 14.0+ preferred)
2. Aras Update installed (version 1.3+)
3. Developer Super Package 

### Install Steps

#### Aras Update Installation

1. Open Aras Update
2. Select **Local** from the sidebar
3. Add a new package reference
4. Select the folder containing your local copy of the Developer Super Package repo
	* This folder should contain a file called `package.config`
5. Select this new Aras Developer Super Package and choose to Install it
6. Check all of the modules that you want to install and click **Next**
	* You may need to expand the window to see all of the available projects
7. Choose **Detailed Logging** and click **Next**
8. Fill in your connection information and click **Install**

#### Manual Installation

* You can find manual installation instructions for each project in the README.md of the corresponding submodule

You are now ready to login to Aras and try out all the projects contained in this Super Package.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

For more information on contributing to this project, another Aras Labs project, or any Aras Community project, shoot us an email at araslabs@aras.com.

## Credits

Original Aras community project compiled by Christopher Gillis at Aras Corp.

Documented and published by Christopher Gillis for Aras Labs. @cgillis-aras

## License

Aras Labs projects are published to Github under the MIT license. See the [LICENSE file](./LICENSE) for license rights and limitations.