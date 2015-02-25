# views_map
Map format for Drupal Views

Views_Map provids a formatter for Drupal Views that displays points on a map based on data passed to the view. 
Current objectivs are to get google maps working with the futur intent to have options for other map APIs to be intagrated in. 
Setting a small image/icon on the content will be pulled in to use as the icon on the map along with the ability to highlight 
areas of the map and show radiel searches. 


Taxonomy will be used to make map groups that can be highlighted on the map.

It will also add a new Drupal field type called geoLocation This field type will hold the latitude and longitude of a location/point. views_map will use the points to map out points on the map. 
