<h1>Some issues when developing with Nucleo board</h1>

**GPIO and SWD:** A nucleo board uses ST-LINK as debugger, and some GPIO pins are shared with SWD signals connected to ST-LINK (which ones may depend on board, see documentation for more info). For example, a Nucleo-L496ZG uses PA13 and PA14 to share with SWD signals, so in short: **Don't do shit with these pins!** 2 hours of work were wasted because of that!
