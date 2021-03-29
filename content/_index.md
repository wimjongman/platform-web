---
title: "The Eclipse Project"
hide_page_title: false
hide_sidebar: true
hide_breadcrumb: true
date: 2020-03-01T16:09:45-04:00
layout: "single"
---

## About the Eclipse Project
The Eclipse Project is an open source project of eclipse.org, overseen by a Project Management Committee (PMC) and project leaders. 
The work is done in subprojects working against Git repositories. The Eclipse Project Charter describes the organization of the project, 
roles and responsibilities of the participants, and top level development process for the project. 
The JDT and PDE are plug-in tools for the Eclipse Platform. Together, these three pieces form the Eclipse SDK download, a complete 
development environment for Eclipse-based tools, and for developing Eclipse itself.

[Eclipse Project Development](https://projects.eclipse.org/projects/eclipse.platform/developer)
: Release plans and other information about the Eclipse Project development process.
<!-->

[Downloads](http://download.eclipse.org/eclipse/)
: Download the Eclipse SDK, Eclipse RCP, SWT, the Eclipse Java compiler, and many more. You can find the current release here. Or, download the latest stable and integration builds if you want to try out 
the newest features under development, or get started with contributing to the project.
<!-->  

[Documentation](http://help.eclipse.org)
: Browse the documentation included with Eclipse Project releases.
<!-->

## Subprojects
### [Platform](http://wiki.eclipse.org/Platform)
The Platform defines the set of frameworks and common services that collectively make up "integration-ware" required to support the use of Eclipse as a component model, as a rich client platform (RCP) 
and as a comprehensive tool integration platform. These services and frameworks include a standard workbench user interface model and portable native widget toolkit, a project model for managing 
resources, automatic resource delta management for incremental compilers and builders, language-independent debug infrastructure, and infrastructure for distributed multi-user versioned resource 
management. 

### [JDT - Java development tools](http://www.eclipse.org/jdt/) 
The JDT provides the tool plug-ins for the platform that implement a Java IDE for power-users, that supports the development of any Java application, including 
Eclipse plug-ins. The JDT adds the notion of Java projects and a Java perspective to the Eclipse platform, as well as a number of views, editors, wizards, builders, and code merging and refactoring 
tools. The JDT allows Eclipse to be a development environment for itself. The JDT plug-ins themselves can also be further extended by other tool builders. 

### [PDE - Plug-in development environment The PDE](http://www.eclipse.org/pde/) 
project provides a number of views and editors that make is easier to build plug-ins for Eclipse. Using the PDE, you can create your plug-in manifest file (plugin.xml), specify your plug-in runtime and 
other required plug-ins, define extension points, including their specific markup, associate XML Schema files with the extension point markup so extensions can be validated, create extensions on other 
plug-in extension points, etc. The PDE makes integrating plug-ins easy and fun. 

### [e4 - the next generation of the Eclipse platform](http://www.eclipse.org/e4/)
The e4 project is an incubator for developing the next generation of the 
Eclipse platform. The mission of the e4 project is to build a platform for pervasive, component-based applications and tools.


<!-- {{/*< pages/home/content > */ }} -->
