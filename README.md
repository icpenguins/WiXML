# WiXML
Do you package large...?

## PROJECT SUNSET
Over the years I have not seen a high volume of users on this project. However, the heat.exe tool in WiX has grown. This is where I will be focusing the development efforts and looking for support from the community and others to get package automation correct. Please find me at https://blogs.msdn.microsoft.com/icumove/.

## PLEASE READ
Please use at your own risk. The project is still in a prototype stage. Please read the note below.

## Project Home Page
The combination of Windows Installer XML (WiX) and MSBuild has lead to a successful venture into automated package creation. The goal of the project was to use as many toolsets that are already available to the community in order to create robust Windows Installer packages inside the build environment. The project, now termed WiX Markup Language or WiXML, does exactly that. The foundation of the project is built on the Microsoft .NET 2.0 Framework for close integration to MSBuild and to use the rich new feature sets that are available.

Please review the WiXML Overview.doc for any additional information about the product.

## Notes
Currently WiXML does not handle component GUIDs for patching and upgrades (http://blogs.msdn.com/robmen/archive/2003/10/18/56497.aspx). There is an effort to enable this feature in upcoming releases of the product. What this means, for those of you that don't know, is that you will need to managed the GUIDs created by the application in order to do an upgrade or patch. The other options is that you require a full, manual, uninstall of each MSI you release.
