
<h1 align="center">Instagram Bot</h1>

<p align="center">
  <a href="https://github.com/mustafadalga/Instagram-Bot">
    <img src="https://www.pngkey.com/png/detail/561-5619368_wall-e-transparent-png-wall-e-robot-cartoon.png" alt="Instagram Bot" width="300">
  </a>
</p>


## Introduction
**An Instagram bot developed using the Selenium Framework**

## Features
  :large_blue_circle: **Download all posts of a single user**  
  :large_blue_circle: **Like or unlike all posts of a single user**  
  :large_blue_circle: **Bulk unfollow**  
  :large_blue_circle: **Bulk comments on a single post**  
  :large_blue_circle: **Bulk unfollow all users that do not follow back**  
  :large_blue_circle: **Delete messages in bulk**  
  :large_blue_circle: **Download highlighted stories**  
  :large_blue_circle: **Download stories**  
  :large_blue_circle: **Download a single post**  
  :large_blue_circle: **Download an IG TV Video**  
  :large_blue_circle: **Follow all the followers of a single user**  
  :large_blue_circle: **Follow all listed users in a file**  
  :large_blue_circle: **Follow all users that have liked a single post**  
  :large_blue_circle: **Follow users based on tag**  
  :large_blue_circle: **Like posts based on tag**  
  :large_blue_circle: **Like or unlike a single post**  
  :large_blue_circle: **Comment on a single post**  
  :large_blue_circle: **Follow or unfollow a user**  
  :large_blue_circle: **Block or unblock a user**  


## Other Features
  :large_blue_circle: Support for two languages: English and Turkish.  
  :large_blue_circle: Option of running browser window in normal or incognito modes has been granted.  
  :large_blue_circle: A settings menu has been included. Settings menu features language and browser settings.  


## Details

:large_blue_diamond:	 You may use the features above by logging into your Instagram account.  
:large_blue_diamond:	 Instagram login for accounts with 2-factor authentication is also possible.  
:large_blue_diamond:	 As the project is currently under development, the 2-factor authentication feature has been set to assume that the 2Fa code is sent to the user's phone number.  
:large_blue_diamond:	 Default language has been set as English.  

## Configuration Settings
 :gear:	 Project utilizes Firefox browser as webdriver. This requires Firefox to be installed for the application to work properly.  
 :gear:	 In order to use Firefox [webdriver](https://github.com/mozilla/geckodriver/releases) needs to be downloaded and the directory path for the downloaded webdriver needs to be set within [config.json](https://github.com/mustafadalga/Instagram-Bot/blob/master/config.json).  


* ### Config Options

:gear: **driver_path:** Denotes the Webdriver directory path.  
:gear: **headless:** Denotes if the browser is visible or not. Default value:**true**  
:gear: **language:** Denotes the language of the application.  
:gear: **languages:** Includes the settings, menu and warning messages for all language options.  
:gear: **time:** denotes the operation waiting times for all the  operations where **time.sleep()** has been used.  



* ### Package installation for Windows users
```
python -m pip install -r .\requirements.txt
```

## Usage
:small_blue_diamond:  '**menu**' commands needs to be used for returning to the main menu from any prompt that asks the user for input.

```
python instagram.py
```



### Notes
:small_blue_diamond: Operation intervals has been set for a length of time that prevents your account from getting banned for bulk operations of post-likes, user-follows or commenting.  
:small_blue_diamond: The operation intervals may be changed from within [config.json](https://github.com/mustafadalga/Instagram-Bot/blob/master/config.json).  
:small_blue_diamond: Has been tested only under Windows.  
:small_blue_diamond: Python version: 3.8.1  


### Technologies used
 :small_blue_diamond: Python  
 :small_blue_diamond: Selenium  
 :small_blue_diamond: Javascript  


## Follow on INSTAGRAM

https://instagram.com/hacking_worm?utm_medium=copy_link 
Guys , you all can dm me in instagram for any queries or suggestion 

##  ???? I HOPE YOU LIKE THIS TOOL ???? 
