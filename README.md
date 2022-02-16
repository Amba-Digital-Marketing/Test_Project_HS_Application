# Test_Project_HS_Application
#Kemboi

 Test for Play Store Deployment

AMBA DIGITAL APP PROGRESS REPORT
Date 10/2/2022
-Finshing up on documenting the current application

-Creating a simple template to mirror the same functionality so as to be able to publish the application to IOS and Android Play Store

-Making technical inquisitions of all the Required-functionality to mirror on the Multi-platform version

-Checking and resolving all the API issues including the OTP sign-up module


Current Discussions
-Remaking the application to a more simpler version with the reuired functionality so as to be able to minimise the room for errors that cause the current application to fail

-What are the key functionalities that should be mirrored through to  the Multi-platform version

-Writing a comprehensive documentation to help in the future maintenance efforts of the application

CURRENT PROGRESS 
Date 14/10/2022

-Technical Project Documentation

-Tree Structure Code Analysis

-Code Review

-Code Refactoring Methodologies

PROJECT STRUCTURE
 

## Directory Structure

```
lib
Android HS Application
            |
            |-----app
            |      |
            |      |----manifest
            |      |       |--AndroidManifest.xml
            |      |      
            |      |----java
            |      |      |--com.microfinance.hsmicrofinance 
            |      |      |       |--holders
            |      |      |       |    |--Billsholder.java
            |      |      |       |
            |      |      |       |--LocalDatabase
            |      |      |       |    |--UserDao.java (Interface class)
            |      |      |       |    |--UserDb.java
            |      |      |       |    |UserEntity.java
            |      |      |       |
            |      |      |       |
            |      |      |       |--Network
            |      |      |       |   |--Data
            |      |      |       |   |    |--Constants.java
            |      |      |       |   |    |--LoansDescription.java
            |      |      |       |   |
            |      |      |       |   |--entity
            |      |      |       |   |    |--All retrofit response classes are located here
            |      |      |       |   |
            |      |      |       |   |--models
            |      |      |       |   |    |--All model java classes located here.
            |      |      |       |   |
            |      |      |       |   |--ApiService.java (Interface class)
            |      |      |       |   |--RetrofitInstance.java
            |      |      |       |   |--TokenInterceptor.java
            |      |      |       |
            |      |      |       |--permisionsHelper
            |      |      |       |
            |      |      |       |--Services
            |      |      |       |
            |      |      |       |----UI
            |      |      |       |    |--Adapters
            |      |      |       |    |       |--All adapter classes are here
            |      |      |       |    |
            |      |      |       |    |--Billings
            |      |      |       |    |       |--All Billings java files are located here
            |      |      |       |    |
            |      |      |       |    |--fragments 
            |      |      |       |    |       |--All fragments are located here in folders with java files
            |      |      |       |    |
            |      |      |       |    |--viewmodels
            |      |      |       |            |--All ViewModel classes are located here.
            |      |      |       |
            |      |      |       
            |      |      |       
            |      |      |--com.microfinance.hsmicrofinance(androidTest) 
            |      |      |                   |--All the UI frontend test runs will be located here 
            |      |      |--com.microfinance.hsmicrofinance(test)
            |      |      |                   |--All backend test runs will be located here
            |      |      
            |      |      
            |      |      
            |      |      
            |      |
            |      |----java generated
            |      |         |----androidx.databinding
            |      |         |----com.microfinance.hsmicrofinance
            |      |         |----com.microfinance.hsmicrofinance
            |      |
            |      |
            |      |
            |      |--------res  
            |      |         |--anim 
            |      |         |    |--bottom_up.xml 
            |      |         |    |--from_left.xml 
            |      |         |    |--from_right.xml 
            |      |         |    |--to_left.xml 
            |      |         |    |--to_right.xml
            |      |         |   
            |      |         |--color
            |      |         |    |--color.xml
            |      |         |
            |      |         |--drawable
            |      |         |      |---All drawables here
            |      |         |
            |      |         |--font
            |      |         |    |--opensansregular.ttf
            |      |         |                 
            |      |         |--layout
            |      |         |     |---All layouts With all UI frontend located here
            |      |         |    
            |      |         |
            |      |         |--menu
            |      |         |    |--basic_nav_drawer_menu.xml
            |      |         |    |--bottom_nav_menu.xml
            |      |         |
            |      |         |--mipmap 
            |      |         |     |--ic_launcher 
            |      |         |     |--ic_launcher_round
            |      |         |     |--logo_launcher
            |      |         |
            |      |         |--navigation       
            |      |         |       |---basic_nav_graph.xml
            |      |         |     
            |      |         |--raw
            |      |         |--values 
            |      |         |     |--colors.xml 
            |      |         |     |--dimensions.xml 
            |      |         |     |--google_maps_api.xml 
            |      |         |     |--strings.xml --styles.xml
            |      |         |--xml
            |      |             |--provider_paths.xml
            |      |
            |      |----res generated
            |      |       |--values
            |                   |--com_crashlytics_build_id.xml 
            |
            |
            |--------gradle Scripts
```
