# Ease Entertainment
## Summary
Functionality 1: The given project will save the community from all the spoilers of their favourite tv series hovering around and to recommend top five movies according to their genre. The main aim of the project is to send an email to the user that contains the information about the Air Date of episode of the TV series a user likes ( air date = Date on which the episode will be broadcasted). It enables user to register for themself.
Functionality 2: This will recommend movies on the basis of user choice of genre. It enables user to register for themself.
Scrapped 10000 movie data from imdb and processed it to recommend movie to user.
Web Scraping in Python : Scraped Site imdb
https://www.imdb.com/
## Input 
 ##### For TV Series Status
  User email
  List of Tv series user like
 ##### For Movie Recommendation
  User email
  List of genre user like
## Getting Started

### Dependencies

#### 1. Make sure these libraries are installed in your system
##### Libraries:
smtplib
urllib
bs4 ( BeautifulSoup)
datetime
Mysql.connector
##### Installation
Installing dependencies:
sudo apt-get install python3-mysql.connector
sudo apt-get install python3-bs4

###### Enter your Credentials at config.py code.
EmailAddress="Your_Email_Address"
Enter your email address through which you want to email all the users
Password="Your_Password"
Enter Password of your email address

Enter host name, username and password of your mysql
Mysql
MysqlHost="Your_Host_Name"
MysqlUser="Your_User_Name"
MysqlPassword="Your_password"
Example:
MysqlHost=”local host”
MysqlUser="User"
MysqlPassword="My password"
Your Gmail should allow third party apps(Less secure apps) to send mails.

Usage
Run main.py in terminal and enter your choice of function.
For TV Series format to enter data:
Enter user email address
example: sample@gmail.com
Enter tv series information requirement separating with comma
example: Game of thrones, black mirror, da vinci demons, breaking bad
For Movies format to enter data:
Enter your genre list seperated with ","(comma)
ScrapedDataTxt
 <p align="center">
  <img src="https://github.com/Parulshandilya/Ease-Entertainment/blob/master/Images/ScrapedDataTxt.png" width="500" title="hover text">
</p>
 

TVSeriesDataBase

<p align="center">
    <img src="https://github.com/Parulshandilya/Ease-Entertainment/blob/master/Images/TVSeriesDataBase.png" width="500" title="hover text">
  </p>


dataInCSV

<p align="center">
  <img src="https://github.com/Parulshandilya/Ease-Entertainment/blob/master/Images/dataInCSV.png" width="500" title="hover text">
</p>
 
interface
 <p align="center">
  <img src="https://github.com/Parulshandilya/Ease-Entertainment/blob/master/Images/interface.png" width="500" title="hover text">
</p>
 
 
movieRecommendation
 <p align="center">
  <img src="https://github.com/Parulshandilya/Ease-Entertainment/blob/master/Images/movieRecommendation.jpg" width="500" title="hover text">
</p>

recommendedMovie
 <p align="center">
  <img src="https://github.com/Parulshandilya/Ease-Entertainment/blob/master/Images/recommendedMovie.png" width="500" title="hover text">
</p>

scrappedTxtFile
 <p align="center">
  <img src="https://github.com/Parulshandilya/Ease-Entertainment/blob/master/Images/scrappedTxtFile.png" width="500" title="hover text">
</p>
