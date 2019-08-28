# Package Manager Client

[![Gitter](https://img.shields.io/badge/chat-on%20telegram-blue.svg)](https://t.me/joinchat/FoZ4Mw58zQJwtbLzQrty3Q)


Package Manager Client for InterSystems IRIS

# Install Package Manager Client:

1. Download the  [latest version](https://pm.community.intersystems.com/packages/zpm/latest/installer) of zpm from the registry
2. Import the zpm.xml into IRIS and compile via any desired way (Managemenet Portal, Studio or Terminal)
 
 After that you can use PackageManager to install modules from [community repository](pm.community.intersystems.com) in any namespace.
 
# How to Install a Module:

1. Call this command to open zpm shell:
> USER> zpm  

2. See the list of available modules:
> zpm: USER>repo -list-modules -n registry
>  
> deepseebuttons 0.1.7
> dsw 2.1.35
> holefoods 0.1.0
> isc-dev 1.2.0
> mdx2json 2.2.0
> objectscript 1.0.0
> pivotsubscriptions 0.0.3
> restforms 1.6.1
> thirdpartychartportlets 0.0.1
> webterminal 4.8.3
> zpm 0.0.6

3. You can load any module that resides in any of the defined repos into IRIS. E.g. here is the way to install webterminal:
> zpm: USER> install webterminal  

# To uninstall a module:
> USER> zpm  
>
> zpm: USER> uninstall webterminal

# Support and Collaboration
ZPM Package Manager client for ObjectScript is community supported and open to collaboration with Pull Requests.
Issues and feature requests are very welcome
