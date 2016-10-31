<h1>No ULINK device found</h1>
**Issue:** Cannot load code into device, Keil says _"No ULINK device found"_ or some similar shit. </br>
**Fix:** Of course, if you are using a STM32 Nucleo board, the debugger is ST-Link. So go to **_Options for Target.../Debug_** then pick the right debugger (ST-Link Debugger if using Nucleo board). </br>
</br>
<h1>Unknown target connected</h1>
**Issue:** Cannot load code into device, Keil says _"Unknown target connected"_. </br>
**Fix:** First of all, verify if the driver is properly installed (check in _Device Manager_). If the driver cannot be installed automatically, then download it here [driver ST-Link](http://www.st.com/content/st_com/en/products/embedded-software/development-tool-software/stsw-link009.html). </br>
If problem still occurs, then try change debug port from JTAG to SW, go to **_Options for Target.../Debug/Settings/Port_**.
