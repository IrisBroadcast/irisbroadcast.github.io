![IRIS Broadcast](../logo-iris.png)

[Home](../README.md) - [IRIS Platform](../README_IRIS.md) - [Ophrys Signage](../ophrys/README.md) - Larkspur EmBER+ Provider - [Contributers](../README_CONTRIBUTERS.md)

# Larkspur EmBER+ Web Provider

* Web Site: https://www.irisbroadcast.org
* Github: https://github.com/IrisBroadcast/LarkspurEmberWebProvider

Creates an EmBER+ tree with custom leafs and nodes. The information/nodes
is also available to access with SignalR and a REST application interface (API).

It's a standalone .NET Core Worker Service.

Could be used to bridge EmBER+ information and control to and from the web.

EmBER+ is a control protocol developed and maintained by [Lawo](https://github.com/Lawo).
Control and status is represented as nodes in a tree (XML-structure). You can
have your device or application to be a provider or consumer. This application
is a provider with a web-API backbone. Make your custom nodes writable or just readable.

## Get started
Use Visual Studio, there is a community edition. And just go ahead and open up the "Solution" file "LarkspurEmberWebProvider.sln". There is a section where you put in your changes, for customization.

Check out the documentation in the project for more information.
