# Caselle-Installer
Installer for my workflow apps (supports auto updating)  
Not done yet, just design phase

## Supported apps
* Copy File Path  
* Open Command Prompt Here  
* Attask Helper  
* Menu Lookup  

## Required features
* Command line support  
* Arguments to run specific applications  
  * This will be used to pipe auto-update through  
* Download all checked apps  
  * `%Program Files%\Aluhadora` seems like a good place to store apps  
* Create shortcuts  
  * This will need to be configurable for certain apps that support multiple profiles  
  * Some apps won't need shortcuts at all (Copy File Path/Open Command Prompt)  
* Wizard installation will probably be the way to go  
* Probably always install and run Caselle-Profiles  

## Work Flow
* First page will be to select which apps you want installed  
  * Include github pages for each so that descriptions can be read there  
* We'll need to run Caselle-Profiles to provide options for shortcuts to create (eg Attask-Helper Connect vs just Attask-Helper)  
* Iterate through each application to look for wizard pages  
