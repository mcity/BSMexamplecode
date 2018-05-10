# BSM Example Code
Example code of BSM analysis using Python and Jupyter Notebooks

Notebook|Description
---|---
find_nearest_road_segment|calculate the road segments traversed during a trip; *this algorithm is still a work in progress; needs more work to perfectly identify the exact road segments traverse. It will sometimes pick up roads intersecting the trip or miss a segment altogether*
weather_info|get the historical weather from Dark Sky for a given GPS coordinates and timestamp
Google_Maps_Time_Zone_API|return the time zone and time offset for a given GPS coordinates and a timestamp
geopandas_spatial_join|assign vehicle activity points to correct census tracts; plotting a complete trip over tracts
generate_road_network|generate Michigan road network
trip_dashboard|rudimentary dashboard for a trip including speed, yawrate using Bokeh (unfortunately Bokeh plots don't render on Github) with linked brushing

# BSM Documentation
It's currently at this github site: https://github.com/caocscar/ConnectedVehicleDocs
