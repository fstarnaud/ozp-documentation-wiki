# Taxonomy

### OZONE
The continuous effort to unite the Intelligence Community under a single computing platform.

### AppsMall
Edition of OZONE software tailored for the U.S. Government.

### OZONE Platform
New centralized software-as-a-service framework that allows for the creation and usage of applications, communication between them, scalability to accommodate large numbers of users, and increased performance.  Also consists of:
* OZONE Center [working title]: Marketplace and the HUD
* OZONE Metrics: Data gathered from the OZONE software package for software maintenance team, store maintenance team, and app developers.

### OZONE Platform Components
**Center >> App Store**  
The Virtual environment for cataloging and sharing mission and business applications.
The Center provides the capability for search and discovery of enterprise assets, similar in functionality to commercial App Stores. The Center's goal is to provide search and discovery of applications.

**HUD >> Mobile Home Screen**  
User-driven home screen with custom layouts and favorited applications similar to a mobile phone home screen for quick access to applications. 

**Webtop**  
Portal that allows users to analyze data using applications.
A web desktop or webtop is a desktop environment embedded in a web browser or a similar client application. OZP's Webtop is just one example or template of how a webtop could be developed. Other deployments of Ozone are encouraged to create their own custom webtop or modify and adapt the generic webtop to their needs. The OZP Webtop would be a default generic webtop and its functionality is purely visual, enabling persistent views of multiple applications loaded in iframes. 

**Inter-Window Communications (IWC)**  
Communication bus within the browser for applications to share data across windows or iFrames.
This allows for data to live in the browser which reduces network latency and improves reaction time. The IWC allows for options and does not bind users or applications to any one environment.  IWC is not user visible ,it works with applications that use it and users should not even know about it. IWC is meant to aid developers and for it to be successful and used developers need to know what it is and how to integrate it with their applications. IWC is as a stand-alone JavaScript library. There is no requirement for an application to use any other module of Ozone in order for applications to use IWC’s inter window communication bus.

**OZP Backend**  
A RESTful compliant API and relational database used to store user profile data and Application metadata for the App Store.
The OZP Backend will be a Python/Django based utilizing the Django REST Framework (DRF) and have modern web stack, RESTful API, swagger API documentation, with ansible deployments.
Library versions planned for initial deployment in April 2016:
  * Python 3.4
  * Django 1.8
  * DRF 3.2.2

**Other Modules**  
Ozone encourages other to contribute code, features, and capabilities in a modular fashion.  The goal is to enable “plug and play” features so that Ozone can be deployed in a lean fashion suited to that environments needs.
Modules that could be developed include:
Additional authentication and authorization 
Custom Webtops
Group, Users, App, and Webtop permission management


### Open Source
* F.O.S.S.: Free Open Source Software
* G.O.S.S.: Government Open Source Software

### UI Elements
* Widget: A widget is a stand-alone application that can be embedded into third party sites by any user on a page where they have rights of authorship, e.g. a webpage, blog, or profile on a social media site. A widget is something that can be displayed in an iFrame and is compatible with and can be displayed on a webtop
* Applications: A program or piece of software designed to perform a group of coordinated functions, tasks, or activities for the benefit of the user
* Web Application: A Web application is a program that is stored on a remote server and delivered to the user through a web browser
* Dashboard: A layout incorporating widgets and/or web applications
* Suite: A collection of applications and/or widgets within the Marketplace
* Folder: A collection of applications and/or widgets within the HUD or Webtop
* Tag: a user-defined keyword used for describing a widget, application, dashboard, or suite.
* Listing: An entry in the Marketplace (e.g. a widget, application, dashboard, or suite)