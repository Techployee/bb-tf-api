# Boom Beach TF API

I decided to get the ball rolling with a simple TF API in the hopes that maybe SC can launch an official one. While that time comes people can use this one for either recruiting or keeping track of their family TFs. Maybe someone can make a recruiting website, I might but am a little short on time.

This is a very simple API which will pick up your TF stats but only a snapshot in a 24 hour period, not live.

It will record:

    ForcePoints
    Intel
    Size
    Players
    OperationStarted
    OperationSuccessRate
    HighestRank
    HighestForcePoints
    Age 


Each day it will run and save all of the TF data in a file where it can be accessed using API calls.


## 2017-10-15
* Json properties now use camel case, sorry if this has caused any inconveniences.
* Added date/time of data import in response called lastUpdated.

## 2017-10-14
Project was created
