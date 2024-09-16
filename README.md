# DLL Loading Abuse
This repository is dedicated to documenting different library files (DLLs) susceptible to exploitation through search order hijacking, including side-loading and phantom DLLs. I am initializing this repository with three CSV files:


* Phantom DLL
* Phantom driver
* Search order hijack


For phantom DLL I put anything that appeared to not exist in the search order. Phantom driver was for imports of driver files that did not exist on disk. Search order hijack is where the DLL exists, but you could place a DLL higher in the search order to hijack execution flow. 
