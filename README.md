# Webservice
The Webservice application, which is run when the developer picks Web Service from the Wizards sub menu in the Visual FoxPro IDE, checks to ensure that MSSOAP.SoapClient30 is registered on the machine and that IIS is installed. It also handles Intellisense subscriptions through the use of the wsreg class in the FFC _ws3utils.vcx library and full web service publications through the wspub class in the FFC _ws3utils.vcx library.

Webservice is part of [XSource](https://github.com/VFPX/XSource), the source files for various Visual FoxPro components. The license governing XSource can be found in the XSource_EULA.txt included with all of the XSource releases.