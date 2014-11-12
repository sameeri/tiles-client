This is just the front-end for the Tiles application (https://github.com/okaybenji/tiles). The original app served up the back-end Socket.IO (Node) server as well, but this and tiles-server (https://github.com/okaybenji/tiles-server) were developed to allow serving the front-end on a separate web server from the back-end. This makes it possible to update the front-end without redeploying the Node server. It also has the added benefit of allowing users to continue to enjoy the single-player Tiles experience while the Node server is down.
