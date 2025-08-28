# Optimizing electricity self-consumption from solar panels

Building AI course project

## Summary

Self-consumption of electricity produced by solar panel is quite a challenge. If not used, the electricity is re-injected in the grid occasionning variation in voltage, sometimes disconnection from the grid due to solar peak (meaning no electicity production) or even black out in the street. This sytem would adapt dynamically to building size and occupancy, electrical equipment usage also depending on the equipment power, and weather conditions and forecast. This system would also give advice or literally organize the planning when to start high-power equipments such as washing machine or electrical boiler to optimize electricity self-consumption.


## Background

Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

Develop an AI-based system that predicts and adjusts electricity consumption patterns.

-Minimize reinjection of surplus solar energy into the grid.
-Prevent voltage variability and grid instability.
-avoid partial or full disconnection from the grid during peak solar production or blackouts.
-Adapt dynamically to building occupancy, electrical equipment usage, and weather conditions/forecasts.
-avoid the use of large storage batteries

This should also avoid oversizing of the grid, and promote sparing of materials

## How is it used?
small Houses: Tailored to individual appliances, occupancy, and daily routines.

Large Buildings: Integrates with Building Management Systems (BMS) to coordinate across multiple zones and users.

ther is a need of connected equipment or people can plan the equipment themselves.

AI Techniques Used
-Machine Learning for consumption prediction and pattern recognition.
-Reinforcement Learning to optimize real-time energy distribution.
-Forecasting Models using weather data to anticipate solar production.
-Sensor Integration to monitor occupancy and device usage.


Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods

data from the building (sensors), form the solar panels, from the weather forecasts and from some sensors in the same area (e.g.to anticipate coming clouds)

-Data Collection: Sensors track energy usage, solar production, weather, and occupancy.
-Prediction Engine: AI forecasts solar output and electricity demand.
-Optimization Algorithm: Determines the best time to run appliances, charge batteries, or store energy.
-Control System: Automatically adjusts device operation and battery storage to match solar availability.

AI Techniques Used
-Machine Learning for consumption prediction and pattern recognition.
-Reinforcement Learning to optimize real-time energy distribution.
-Forecasting Models using weather data to anticipate solar production.
-Sensor Integration to monitor occupancy and device usage.

If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

Data privacy and secure sensor integration.
Initial cost of smart devices and battery storage.
Need for user-friendly interfaces and override options.


## What next?

this is a very large project which needs a lot of human resources with specific skills: electricity, computing, weather,...


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
