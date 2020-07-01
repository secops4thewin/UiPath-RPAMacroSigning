# UiPath-RPAMacroSigning
This project is a file that runs you through the process of automatically signing office files


## High Level Steps
- Download and install community edition of UIPath
- Install a certificate into your personal store so that you can sign macros.  [Steps to create self-signed cert](https://www.groovypost.com/howto/create-self-signed-digital-certificate-microsoft-office-2016/)
- Create the following directories on your machine
  - `D:\AutomatedMacroSigning`
  - `D:\AutomatedMacroSigning\Processed`
  - `D:\AutomatedMacroSigning\Unprocessed`
- Place all files to be signed into unprocessed folder.  
- Run playbook and now all of your files have been signed.


### Bugs
Help me help you by reporting issues.  I am happy to chat and work through problems with this.  I have tested this on my own machine but would love to see what happens in a production environment.
