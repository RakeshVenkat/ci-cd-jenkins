# ci-cd-jenkins
Everything about Jenkins.


# Steps for installing jenkins on Windows
1. Install JDK 8
2. Install Jenkins installer (downloadable via https://www.jenkins.io/download/thank-you-downloading-windows-installer-stable/)

## Installation procedure:
* Follow the installation steps in Jenkins after extracting the Jenkins contents that includes an installer.
* Jenkins is installed here: `C:\Program Files (x86)\Jenkins`
* The jenkins service is accessible locally via the 8080 port: http://localhost:8080/
* There is a temporary one time security challenge thrown where it asks to provide the secret is stored at `C:\Program Files (x86)\Jenkins\secrets` directory in the inital setup screen.
* Select all plugins to be installed. Select the defaults and go ahead.
* Now Jenkins should take you to the dashboard where you can create a new Freestyle project.

## Users:
 I have created two users locally to manage the builds
* `admin`/`admin`
* `release-manager`/`jenkins`

