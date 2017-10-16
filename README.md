# Boom Beach TF API

I decided to get the ball rolling with a simple task force API in the hopes that maybe SC will launch an official one. While that time comes people can use this API for either recruiting or keeping track of their family TFs. 

My system will run every 24 hours and record your task force data in a file for archiving purposes. So the data is not live.

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

You can then access this data using API calls.

**Please visit the [wiki](https://github.com/Techployee/bb-tf-api/wiki) to get started.**


Live examples can be found:
* [http://api.techployee.com/boombeach/size/tfsize.html](http://api.techployee.com/boombeach/size/tfsize.html)
* [http://api.techployee.com/boombeach/chart/chart.html](http://api.techployee.com/boombeach/chart/chart.html)

## 2017-10-16
* Added task force [comparing](https://github.com/Techployee/bb-tf-api/wiki/Task-Force-Compare).
* Updated the [date ranges](https://github.com/Techployee/bb-tf-api/wiki/Task-Force-Tag#task-force-details-between-dates) array, the date is placed inside the array as a property instead of being the key. 

## 2017-10-15
* Json properties now use camel case, sorry if this has caused any inconveniences.
* Added date/time of data import in response called lastUpdated.
* Added task force details between [date ranges](https://github.com/Techployee/bb-tf-api/wiki/Task-Force-Tag#task-force-details-between-dates) to calculate growth.

## 2017-10-14
Project was created.
