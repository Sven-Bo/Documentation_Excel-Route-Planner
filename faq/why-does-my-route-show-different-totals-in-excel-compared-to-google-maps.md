# Why does my route show different totals in Excel compared to Google Maps?

When you calculate a route in Excel and then view it in Google Maps, you may notice different distance and time values. This is expected behavior due to several factors:

**Different Routing Engines:**

* Excel uses the Google Routes API for optimization
* Google Maps uses its own web-based routing engine
* Each may choose slightly different paths between waypoints

**Traffic Data Timing:**

* The Routes API calculates based on conditions at the time you click "Calculate Route"
* Google Maps recalculates using current traffic when you open the link
* Time differences between calculation and viewing cause variations

**Route Optimization:**

* The Routes API optimizes the waypoint order using advanced algorithms
* Google Maps displays the waypoints in the optimized order but recalculates the actual paths

**Bottom Line:** The Excel results are your planned route based on the Routes API optimization. Use these figures for planning. Google Maps provides a visual reference but may show slightly different totals.
