# 2021/22 Software Engineering *Project Wide Standards* XML Schema
This repository contains the XML Schema for the PWS document that needs to be agreed between all groups.
It should hopefully be as generic as possible, so as to not get in the way of the implementation of specific features in different group's projects.
> Each group may, of course, introduce additional features suited to their product/market niche.

I followed roughly what was set down in [this](https://docs.google.com/document/d/1gtq-B1WeleKX0ulZakJPy3qUrz87qYwA7frx8K8Qr_8/edit?usp=sharing) document, which mostly fits with the Project Description.

To add your own extensions in an `<xsd:any>` block, add your extension schema to your XML document and ensure your extensions are in the PWS_Exts namespace.

The Schema is targetting XML 1.0, because xmlls (and several other parsers) *still* do not fully support 1.1 

Email me (dm1306) and I'll add you as a collaborator if you want to commit directly - otherwise you should be able to fork this repository, make your changes in a work branch, then open a Pull request.
