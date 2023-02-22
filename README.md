# Clothing-Consultant
RPA Project : Clothing-Consultant: UiPath

### Table of Content
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Demo Video](#demo-video)
  * [Steps in the project execution](#steps-in-the-project-execution)
  * [Technical Aspect](#technical-aspect)
  * [Installation](#installation)
  

### Overview 
This robot will tell you what the weather is going to be in a location, and recommend what you should wear based on the temperature. As an example, if it's rainy outside it'll tell you to bring an umbrella so you don't get wet!
See if you can augment Clothing Consultant to help you pack for a trip. You could even have it trigger automatically whenever you book a trip online.
### Motivation
The motivation was to use UiPath to forecast and suggest clothing that’s appropriate for the day’s weather.This robot will be able to save you valuable time during the day, by checking the weather and recommending something to wear.
### Demo Video


https://user-images.githubusercontent.com/122998236/220418877-d5a4f4cb-f070-4662-960d-69e2ec72ba84.mp4


### Steps in the project execution
-Accept City Name to forecast(Input dialog Activity)</br>
-Open browser(set browser properties) and search(through type Into Activity)</br>
-Scrape web data for temperatute and weather</br>
-Use Flowcharts activity and prepare a flowchart using decision flow activity</br>
-Use conditions in flow activity (for example:if temperature<40 then its too cold)</br>
-use assign activity and String concatenation and show result</br>
### Technical Aspect
Dependencies:
![alt text](https://github.com/argadevidya/RPA-Project-Clothing-Consultant/blob/main/dependencies.png)
### Installation
### Steps:
#### Step 1: Installation of UiPath Studio Community Edition
Let us walk through the steps to install UiPath Studio Community Edition. 
Let us start by going to the UiPath Community edition page at www.uipath.com/developers/community-edition
1.	Go to the “Start Trial” or “Get Community Edition” options. 
2.	Look for “Community cloud” and click on “Try it” 
3.	Sign-up/Register with Uipath by providing the information. Once you submit the information, it would open up the UiPath portal. 
4.	In the left pane, choose “Resource Center” and then Download the “Community Edition” as shown above.
5.	An executable setup file (UiPathStudioSetup.exe) would download.
6.	Go ahead and double click this installable to install the UiPath community edition Studio. 
7.	When you get to the License screen, click on ‘Activate Community Edition’. The licenses for UiPath Studio and Robot will be activated. 
8.	Congrats! A browser tab should open up indicating that UiPath has been installed. 
9.	Go to Windows “Start” and look for “UiPath Studio”. Click on it to open the Studio.
#### Step 2:Download project folder, Unzip project folder
#### Step 3:Open UiPath Studio and open project file from folder
#### Step 4:Run main process
#### Step 5:Enter city name and see the result.
