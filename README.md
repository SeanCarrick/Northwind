# Overview
Northwind Traders Complete Accounting Project is being designed to fill a niche for accounting packages in an industry that has vastly different needs for financial breakdown of information - the trucking industry.

The trucking industry is a *per mile* industry, where the only financial information that matters is based upon the number of miles a unit may travel. These miles are either logged as __empty__ or __loaded__, depending upon whether the unit is hauling a load from Point A to Point B, or *deadheading* from Point B to Point C to pick up another load. Regardless of whether the truck is loaded or empty, there are multiple costs involved in the unit movement, such as fuel, maintenance, tolls/parking, etc. Even when the unit is not actively hauling a load, if it is moving, it is incurring these costs. This is why the financial breakdown that makes the most sense to the trucking industry is the *per mile* breakdown. While empty, units typically get higher fuel economy and lower maintenance costs than when loaded. However, every mile moved costs the company money. All of the expenses that have been mentioned so far don't even take into account the pay for the driver of the unit, who is usually paid per mile when the unit is empty, as well as when the unit is loaded.

Northwind Traders Complete Accounting Project aims to answer this lack of software that tracks revenue and expenses *per mile*.

## The Development System
Northwind Traders Complete Accounting Project is being developed using the Java&trade; Programming Language, as it is system independent. By using Java&trade; we will be able to design and code the project once and it will be able to be used on any operating system that supports a Java&trade; Virtual Machine (JVM).

Furthermore, the Project will be designed in a __*modular*__ fashion. In this way, end users will only need to purchase those portions of the application that make sense for their business setup and structure. For this reason, not only are we developing the Project in the Java&trade; Programming Language, but we are using Java 12, which is modular by design.

Since our Project is to have a graphical user interface (GUI), and we don't want to spend a decade or more creating a modular windowing system, the Project is based upon the NetBeans Platform and is being designed as a Rich Client Program (RCP). The NetBeans Platform provides a rich, customizable windowing system that supports a pluggable architecture. Therefore, we will be able to add features by supplying new modules that can be "dropped in" on the existing application.

## Modules
Northwind Traders Complete Accounting Project will be made up of multiple modules, and divided into three Editions, depending upon what is needed by the client for properly managing their trucking company. The three Editions are: Basic, Corporate, and Enterprise.

### Basic Edition
Northwind Traders Complete Accounting Basic Edition is focused on the single-truck owner/operator truck driver. This system will have all of the features that an owner/operator will need to manage his/her company and know his/her company's numbers, down to the mile. The modules that make up the Basic Edition are:
* Base Module - The entry and configuration module for the application.
* Customer Mangement Module - Provides the means of storing and locating customers that are shipping or receiving the loads.
* Vehicle/Unit Management Module - Provides a way for the owner/operator to maintain the information for their truck(s) and trailer(s).
* Loads Module - The handling of all load information.
* Accounting Module - The module that performs all of the accounting calculations for the application.
* General Ledger Module - The module that handles the entry of financial information into the application.
* Service Management Module - Manages and maintains records of repairs and maintenance on the vehicles/units.
* Reporting Module - Provides all of the reports the system is set up to create.

### Corporate Edition
Northwind Traders Complete Accounting Corporate Edition is focused on small- to medium-sized trucking companies, from 5 to 200 trucks. The Corporate Edition includes the modules of the Basic Edition, but also adds the following modules:
* Employees Module - Provides all functionality for maintaining and tracking employees of the company.
* Payroll Module - Provides all functionality required for generating and running payroll for drivers, mechanics, and administrative support staff.
* Accounts Receivable Module - Provides the ability to track invoices sent to customers and receive the funds into the General Ledger.
* Time and Billing Module - Provides the capability of tracking time and pay for hourly employees, such as mechanics and administrative support staff.
* Dispatching Module - Provides the ability of the company to dispatch its drivers onto the loads that have been booked with its customers.

### Enterprise Edition
Northwind Traders Complete Accounting Enterprise Edition is focused on large- to mega-sized carriers, which typically have hundreds to thousands of power units and trailers. The Enterprise Edition includes everything found in the Basic and Corporate Editions, as well as:
* Accounts Payable Module - Provides the ability for the company to pay on time bills and purchases.
* Communications Module - Provides a method of communicating with drivers in their assigned trucks for communications other than dispatch-related communications.
* GIS Tracking Module - Provides the ability for the company to see where all of their trucks and trailers are currently located.
* eLogging Module - Provides integration of the system with the drivers' eLog systems.
