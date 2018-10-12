# Bowery-2.0

### Pre and Post Earthquake Image Analysis

An Application to aid the survivors as well as recue workers in a city environment in the aftermath of an earthquake.

It analyses pre and post images of eathquake affected region to :
1) Create a relative scale of damage in an area of a region to help direct rescue efforts in the most needed area.
2) To locate the area with maximum casualties.
3) Detect undamaged and safe areas in the aftermath of disaster to guide the survivors towards safety.
4) To discover the safest route to evacuate to the safety zone from an affected buiding.


The application takes in the aerial images of a bigger region(a colony or a sector) before and after the earthquake. It identifies all the building in the pre image and compares their presence in the post image. If the building is found to be damaged the application marks it as a casuality zone.

&nbsp; &nbsp;The casuality zones are also classified as high, medium and low based on the previously available population density and traffic statistics, in order to point the recue services to the most needed region.

&nbsp;&nbsp;  Also the application finds out the shortest and safest routes between the building to reach a user specified location and also integrating it with mobile maps to help navigate the user.

For preprocessing of the image we'll be using python and associated libraries like tensorflow etc to compare the images. Currently we are thinking of breaking the images into grids and comparing the pixels in each grid with its counter part. We'll be integarting the live mobile maps available to analyze the traffic statistics before the disaster so as to predict the casuality level  in a grid. 

&nbsp;&nbsp; All of this will be integrated into a small handy mobile or web app which could be reeadily deployed in the field.
 
