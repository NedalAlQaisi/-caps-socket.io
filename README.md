# caps-socket.io


# Lab Summary:
*  I created three different Apps.
* The first one is caps (server) which will open a global connection to the other clients.
* The second is driver(client) the third one is Vendor(client).


* created three events the first one is pickup event it will be emited with an order from the vendor client and then the server will create an action on this event to log the "EVENT" and the object data from the emitting side  and then emit this event to the driver client which will create an action also based on this event and emit in-transit and dilevered events from the driver client.


*  The second one is in-transit event it will be emited  with an order from the driver client and then the server will create an action on this event to log the "EVENT  and the data from the emitting side.

* The third one is dilevered event it will be emited with an order from the driver client and then the server will create an action on this event to log the "EVENT" and the object data from the emitting side  and then emit this event to the vendor client which will create an action also based on this event .

# Terminal Output:
![](./caps-socket.png)

# Links:

* [PR](https://github.com/NedalAlQaisi/caps-socket.io/pull/2)

* [Actions](https://github.com/NedalAlQaisi/caps-socket.io/actions)
