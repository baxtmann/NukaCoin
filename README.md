----
# Welcome to NUK! #
Glad you made it!
----
## What is NUK? ##
NUK is a cryptocurrency to challenge convention. (or something that sounds as arrogant as that) 

----
##The Secret Plans##
NukaCoin is going to be a legit cryptocurrency. Utilizing true distributed computing, NukaCoin will only be controlled by those who choose to use it. At least that's the plan. We are still figuring out what we envision for this, but this is a very good start for us. Currently, there is no way to buy the crypto - hence why we consider it in pre-prod. for the first 100 users we will be giving each user 1000 NUK to get the blockchain started! After that, there are big plans to give away 10's and even 100's of millions of NUK! But that is once this gets to a point we are confident in pushing it out to the masses - so not for a little bit at least. 

#WE ARE CURRENTLY PRE-PROD SO USE AT YOUR OWN RISK!#

----
## Get it! ##

  - *dependencies*:
    - You will need JDK, but since oracle requires you to create a damn account, we have it hosted here: http://edge.nukaco.in/ DISCLAIMER: We do not claim to have any ownership rights to Java or any related technologies, and all rights go to Oracle/Java k thx
    - If you are just trying to run the wallet, this is the only dep you will need you are welcome 

----
## Run it! ##

  - Run via NukaCoin.exe on Windows, and on Linux, via run.sh (sudo sh ./run.sh) 

  - Open http://localhost:5588/ in a browser

  - *JavaFX based wallet coming when full windows compile actually works don't @ me*

  - On windows, almost every antivirus will flag this, so make sure that the software dir has an exception. On linux this most likely will not be an issue. 
----
## Compile it! ##

  - if necessary with: `./compile.sh`
  - you need jdk-8 as well

----
## Troubleshooting the NRS (NUK Reference Software) ##

  - How to Stop the NRS Server?
    - click on NUK Stop icon, or run `./stop.sh`
    - or if started from command line, ctrl+c or close the console window

  - UI Errors or Stacktraces?
    - report on Github

  - Permissions Denied?
    - no spaces and only latin characters in the path to the NRS installation directory
    - known jetty issue
  
  - Way too much ram being used??
    - Yeah this isn't a bug or problem this is how Java is (can I get a MEGA OOF over here?)
----
## Further Reading ##

  - in this repository:
    - USERS-GUIDE.md
    - DEVELOPERS-GUIDE.md
    - OPERATORS-GUIDE.md
    - In the doc folder

----

## License
* This program is distributed under the terms of the Jelurida Public License version 1.1 for the Ardor Public Blockchain Platform.
* This source code has been generated by CoinGenerator - https://coingenerator.sh
* Distributed Java/JDK/JSDK under the terms of the Oracle Java Licence, all rights reserved for Oracle
* NukaCoin is delivered by Jumpstart Innovation Labs, and is provided for free use, and can be redistributed as long as the NRS (NUK Reference Software) has not been redistributed without any significant changes
* Made by Zoomers, for zoomers.
