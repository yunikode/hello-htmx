# Building the GoTH Stack

Building websites should be fun again and not the current convoluted JSON mess oroginating from JS frameworks trying to do god's business on the isomorphic level.
We approach this by going back in time to simple AJAX requests and sending simple HTML down the wire. No more dehydrating/rehydrating states and preloading everthing, including the kitchen sink

## Step 1: Starting with Go and HTMX

For the first iteration we use the standard library provided tools from Go for the server and routing, and HTMX as a frontend library

