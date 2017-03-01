# Air quality data from Palestine (collected by IoT devices)
* Notes
 * The files listed here are air quality data from sensors collecting either NO2 and CO or particulate matter (PM25) in addition to temperature and relative humidity. 
 * Devices are located indoors with limited indirect exposure to ambient atmosphere.
 * The significant colums are time stamp, temperature [deg C], relative humidity [%] and either PM25 [micro gram/m3] or NO2 [parts per billion or ppb] and CO [parts per million or ppm]. 
 * Data in csv format (after decompression) provided under the __Creative Commons Non Commercial License__: [CC BY-NC 4.0] (https://creativecommons.org/licenses/by-nc/4.0/). For more information about __Open Data__, see [The Open Data Charter](http://opendatacharter.net/), [Open Knowledge Int'l](https://okfn.org/), [Open Data Institute](http://theodi.org/) and [the Open Data Barometer](http://webfoundation.org/our-work/projects/open-data-barometer/). For data in general, see [School of Data](https://schoolofdata.org/).
 * We will try to provide additional sensor data and increment available datasets but there is no guarantee this will happen on regular basis. For air quality globally, try [WHO database](http://www.who.int/phe/health_topics/outdoorair/databases/cities/en/), [AQICN](http://aqicn.org/city/jerusalem/) and [AirVisual](https://airvisual.com/earth) with various degrees of coverage and accuracy.
 * In case data has discontinuity, this is mostly due to power outage or network issues
 * The PM25 sensors reading frequency is once every 60 seconds, the NO2/CO units every 30 seconds or less (see dataset). 
 * An example visualizing one sensor's NO2 values over the past hour in [Power BI](https://app.powerbi.com/view?r=eyJrIjoiNTk0MWZlNzgtNTE5NS00NjgyLWIxMWEtYWQzM2JjZDhiYTZjIiwidCI6IjQ3MjI2Y2Q0LWYyZjctNGMwNS1hMzg0LWRmZTcxZGE0YjM1OSIsImMiOjEwfQ%3D%3D) and another example of [4 sensors charted and mapped](https://app.powerbi.com/view?r=eyJrIjoiMDg1ODY1YzQtYTU5Yy00MzQxLWJkYzgtZGU2NjczYjRmNDBmIiwidCI6IjQ3MjI2Y2Q0LWYyZjctNGMwNS1hMzg0LWRmZTcxZGE0YjM1OSIsImMiOjEwfQ%3D%3D). Locations are not exact. A copy of a [Power BI file](AllNO2-pub.pbix) is included __without API Key__ (it will not refresh) - just in case you need to see the actual queries. Here's also a [blog post](https://www.linkedin.com/pulse/tracking-air-quality-iot-sensors-publishing-open-data-abed-khooli) about this activity.
 * Data is provided as is and __may not be suitable for scientific research__
 * If you find data here useful or use it for common good, kindly let us know (mention [@akhooli](https://twitter.com/akhooli) and [@ddiMENA](https://twitter.com/ddimena) on Twitter)

*Last updated: March 1, 2017*
