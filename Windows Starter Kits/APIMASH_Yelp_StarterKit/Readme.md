#APIMASH Yelp Starter Kit
##Date: 5.10.2013
##Version: v1.0.0
##Author(s): Chris Bowen
##URL: http://github.com/apimash/starterkits

----------
###Description
The Yelp Starter Kit is a XAML-based Windows 8 app that demonstrates calling a Web Service that returned a simple JSON payload. The JSON payload is deserialized into a View Model.

![Yelp Starter Kit Screenshot][1] 

###Features
 - Invokes the Yelp API (http://www.yelp.com/developers)
 - Demonstrates how to deserialize JSON to C#
 - Uses a binding object model for data binding to UI
 - Provides a baseline for a Windows 8 Store App

###Requirements

 - Windows 8
 - Visual Studio 2012 Express for Windows 8 or higher
 - JSON.NET from Newtonsoft (https://json.codeplex.com/)
 - Yelp API Developer Key (http://www.yelp.com/developers)

###Setup

 - Request a Developer Key from Yelp (http://www.yelp.com/developers)
 - Download the Starter Kit Zip Portfolio from (http://apimash.github.io/StarterKits/)
 - Open the Solution in Visual Studio
 - Obtain JSON.NET from Newtonsoft (https://json.codeplex.com/)
    - Use NuGet in Visual Studio to add JSON.NET to the APIMASHLib project
    - Alternatively, download/install and add reference to JSON.NET in APIMASHLib project
 - Add your Developer Key MainPage.xaml.cs, replacing the [YOUR-DEV-KEY-HERE] placeholder
 - Compile and Run

###DISCLAIMER: 

This sample is licensed under the Microsoft Public License (MS-PL) - http://opensource.org/licenses/ms-pl

The sample code described herein is provided on an "as is" basis, without warranty of any kind, to the fullest extent permitted by law. Both Microsoft and I do not warrant or guarantee the individual success developers may have in implementing the sample code on their development platforms or in using their own Web server configurations. 
Microsoft and I do not warrant, guarantee or make any representations regarding the use, results of use, accuracy, timeliness or completeness of any data or information relating to the sample code. Microsoft and I disclaim all warranties, express or implied, and in particular, disclaims all warranties of merchantability, fitness for a particular purpose, and warranties related to the code, or any service or software related thereto. 

Microsoft and I shall not be liable for any direct, indirect or consequential damages or costs of any type arising out of any action taken by you or others related to the sample code.

----------

##Change Log
###v1.0.0
  
  [1]: https://raw.github.com/apimash/StarterKits/master/APIMASH_Yelp_StarterKit/screenshot_main.png "Yelp Starter Kit Screenshot" 
