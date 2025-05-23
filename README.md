Naturalistic data collection methods play an important role in facilitating safe and reliable bicycle
infrastructure development. Bicycles, instrumented with sensors like GPS, accelerometer, power
meter, cadence sensor, heart rate monitor, and LIDAR, can provide traffic researchers with
infrastructure-specific and behavioral data. The raw sensor data is often collected unprocessed
and unstructured; and requires a framework for further usability. Proper data streamlining
manifests the ability to the researchers to access the data efficiently. However, the streamlining
process encompasses various types of implementations. Some implementations require
complicated functionalities, which may be difficult to maintain after implementation. A critical
step is that the framework must support continuous updates of new data, and any modification of
data will not impair the original functionalities.The
streamlining process includes organizing and correcting bicycle computer and sensor data, exploring statistical attributes of the data, and developing a visualization interface of the
processed data. The data visualization tools must have the compatibility to continuous update of
new data. Additionally, the sensor data of each rider can be compared to each other and against
the aggregate trend. With the sensor data, an attempt was undertaken to classify different cycling
modes along the cycling path.On
the other side, PostgreSQL, and Apache Superset were utilized as tools for database creation, sensor data visualization, and reporting purposes. 
After cleaning and smoothing all the cyclists' (29) sensor data they are visualized with the open-source dashboard tool called Apache Superset. In the dashboard 
information of the riders, sensor data with repect to time and distance has been published. 
The URL of the dashboard: http://localhost:8088/superset/dashboard/p/x3kA7WnAamd/
![bicycle-data-visualization-dashboard-2025-04-28T18-00-50 747Z](https://github.com/user-attachments/assets/f1b98d7c-d249-445f-adac-c77745b5e22f)
