Temperature
===========
Temperature is a native Android app to view the temperature and humidity of my apartment. The current temperature and humidity are monitored by a Spark Core and recorded to a MySQL database via a cron job. Data requests from the app are made with Retrofit. The graph is displayed using AChartEngine (a charting library for Android).

![Animated Gif](demo.gif)

Third Party Libraries
===========
+ [Retrofit](http://square.github.io/retrofit/) (used for API requests)
+ [Butterknife](http://jakewharton.github.io/butterknife/) (used for view injection)
+ [AChartEngine](https://code.google.com/p/achartengine/) (used to display the report graph)
+ [Cupboard](https://bitbucket.org/qbusict/cupboard) (will be used to cache data locally)
