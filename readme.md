# Our Place in Space

## SETUP

## CLIENT SIDE
### Commands
npm run serve

## SERVER SIDE
### Commands
npm run server:dev

## TODO
Something doesn't work? Search TODO
As the MVP doesn't require server this set up on this has not been completed


## Project Brief
Develop an interactive browser application that will display educational content in a fun and interesting way - to help an organisation that is looking to improve its online educational offering.

## MVP
Users should be able to:
1) view educational content (images and interesting text) about space provided via NASA APIs
2) move to different parts of the content via some interaction with the page (e.g. searching content by date)

Display an image from 3 different apis, at the top level component. 
![MVP and extension diagram](./imgs/mvp-diagram.jpg)



### APIs

* [NASA Astronomy Picture APOD](https://github.com/nasa/apod-api) of the day api.
* [Mars weather](https://mars.nasa.gov/insight/weather/)
* [Mars rover](https://github.com/chrisccerami/mars-photo-api)
* [EPIC](https://epic.gsfc.nasa.gov/)
* [Earth](https://api.nasa.gov/)


### Extension
Make data from each api the same format so that it can be used on a shared component sub component "image-element".


## Mini sprint
### For monday AM
* Import images from chosen API to component
* Describe the data structure of API
