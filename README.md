# Thank you for joining us at CommunityLive 2024!
It was our pleasure meeting and sharing information with you. We hope to see you again and safe travels back to your place of origin! 

### Instructors
Greg Bousley - Instructional Designer
Logan Jensen - Technical Trainer

**Please see below for a link to each class' presentations and references to materials.**

### References by Class:
**ACS Out of Process Extensions with ActiveMQ**
  * [Presentation](https://github.com/GBHyland/Alfresco-CommunityLive-Class-Guide/blob/main/ACS-extension-activemq.pptx)
  * [Out of Process Overview](https://docs.alfresco.com/content-services/latest/develop/oop-ext-points/)
  * [Platform Architecture](https://docs.alfresco.com/content-services/latest/develop/software-architecture/)
  * [Out-of-Process SDK](https://docs.alfresco.com/content-services/latest/develop/oop-sdk/)

**Enriching Content with Alfresco Intelligence Services**
  * [Presentation](https://github.com/GBHyland/Alfresco-CommunityLive-Class-Guide/blob/main/2024%20CLIVE%20AIS%20Presentation%20-%20WIP%20copy.pptx)

**APS Workflow Automation with Alfresco Intelligence Services**
  * [Presentation](https://github.com/GBHyland/Alfresco-CommunityLive-Class-Guide/blob/main/aps-ais-textract.pptx)
  * [Alfresco Intelligence Services](https://docs.alfresco.com/intelligence-services/latest/)
  * [AIS Architecture](https://docs.alfresco.com/intelligence-services/latest/admin/)
  * [Amazon Textract](https://docs.aws.amazon.com/textract/latest/dg/what-is.html)

**Developing Modern Business Applications with Alfresco Development Platform**
  * [Presentation](https://github.com/GBHyland/Alfresco-CommunityLive-Class-Guide/blob/main/ADF%202024%20PPT%202.pptx)
  * [Alfresco NG2 Components Github](https://github.com/Alfresco/alfresco-ng2-components)

## Alfresco Preparation by Class:
Class prep guide for Alfresco TechQuest attendees. 
Find the class(es) that you will attend from this list and ensure you have the proper programs and services installed. Follow the instructions to install if necessary.


### Alfresco Out-of-Process Extension Project with ActiveMQ Messaging
1. Quay.io Alfresco account (to pull enterprise images)
   * If you do not have a Quay.io account, obtain trial credentials by following these steps:
     * Visit the following url and submit the form. Provide an email address you can access. Quay.io trial credentials will be emailed to the address you provide.
         ```
           https://www.hyland.com/en/resources/alfresco-ecm-download
         ```
3. IntelliJ Software (JDE Environment) - (https://www.jetbrains.com/idea/download)  -  (The Community version is fine)
4. Java installed on your machine:
   * Check if you have Java installed by running the following command in your Terminal / CMD prompt: ```java --version```. The output should show the version of Java you have and if so you are done with this step. If not found, follow the steps below to install Java.
   ### MAC OS
   * https://www.oracle.com/java/technologies/downloads/?er=221886#jdk22-mac
   * To check if Java is installed enter the following command in Terminal:
     ```
        java -version
     ```
   ### Windows:
     [https://www.youtube.com/watch?v=SQykK40fFds](https://www.youtube.com/watch?v=SQykK40fFds)
5. Maven installed on your machine. (Follow these steps to install - **Note:** Java must be installed first.)
   * Check if you have Maven installed on your machine by entering this command into your Terminal / CMD prompt: ```mvn --version```. The output should show the version of Maven you have and if so you are done with this step. If not found, follow the steps below to install Maven.
    ### Mac OS
    1. In terminal window enter the following command:
    ```
      /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```
    2. in the feedback of the Brew installation find the two commands under the **Next Steps:** header and enter each one of those commands into Terminal.
    3. Enter the final command to install Maven:
    ```
      brew install maven
    ```
    4. To check that Maven is installed, enter the following command:
    ```
      mvn -version
    ```
    ### Windows
     [https://www.youtube.com/watch?v=YTvlb6eny_0](https://www.youtube.com/watch?v=YTvlb6eny_0)
6. Docker installed on your machine:
   * [Install Docker Desktop here](https://www.docker.com/products/docker-desktop/)

   
### Developing Modern Business Applications with Alfresco Development Framework (ADF)
1. Visual Studio Code application installed:
   * https://code.visualstudio.com/download
2. SSH Plugin for Visual Studio Code:
   * Open the Extensions Marketplace by pressing Ctrl+Shift+X or clicking the icon with four squares in a box and the top right square exploding out
   * Search for Remote-SSH in the Search Extensions in Marketplace search bar
   * Select the plugin and click the Install button
  
