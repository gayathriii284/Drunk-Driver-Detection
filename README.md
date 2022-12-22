# Drunk-Driver-Detection
Detects the traffic on the road(June 2,3,4,5) and catches drunk drivers that start randomly from different locations.<br> This project uses python along with main open source libraries:<br>
<ol>
1.Folium (for plotting and visualizations on maps)<br>
2.Geopy (to calculate distances between two points in a map etc.)<br>
</ol>

Two free APIs used are:<br>
<ol>
1.Openrouteservice API (for the points of interest (POI) service that helps finding coordinates of all places with liquor licenses like restaurants,bars,clubs etc)<br>
2.Route and Directions (Rapid API) (for finding routes along with duration and distance between 10000 pairs of randomly selected pairs, provides free service for 30,000 requests/month)<br>
</ol>

Here, two learning algorithms are used to find the best locations and times for the detectors to catch maximum drunk drivers:<br>
<ol>
1.Genetic Algorithm<br>
2.Particle Swarm Optimization<br>
</ol>
