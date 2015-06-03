Heretic II and the Heretic logo are trademarks of Activision.
# Heretic II GWT Port #
The Heretic II GWT port brings the 3d gaming experience of Heretic II to the browser.

In the port, we use WebGL, the Canvas API, HTML 5 `<audio>` elements, the local storage API, and WebSockets to demonstrate the possibilities of pure web applications in modern browsers such as Safari and Chrome.

The port is based on the Jake2 project, compiled to Javascript using the Google Web Toolkit (GWT). Jake 2 is a Java port of the original Heretic II source code, which was open sourced by id software.

This project uses the [Quake II GWT Port](http://code.google.com/p/quake2-gwt-port/) for

  * reated a new WebGL based renderer
  * orted the network layer for multiplayer games from UDP to the WebSocket API
  * ade all resource loading calls asynchronous
  * reated a GWT implementation of Java nio buffers based on WebGL arrays (to be ported to ECMAScript Typed Arrays)
  * mplemented a simple file system emulation for saving games and preferences using the Web Storage API