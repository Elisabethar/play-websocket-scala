# play-websocket-scala

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/c59240d53b00451a8b531acf3ae655fa)](https://www.codacy.com/app/harlamova/play-websocket-scala?utm_source=github.com&utm_medium=referral&utm_content=Elisabethar/play-websocket-scala&utm_campaign=badger)

This is an example Play application that shows how to use Play's Websocket API in Scala, by showing a series of stock tickers updated using WebSocket.

The Websocket API is built on Akka Streams, and so is async, non-blocking, and backpressure aware.  Using Akka Streams also means that interacting with Akka Actors is simple.

There are also tests showing how ScalaTest and Akka Testkit are used to test actors and flows.

For more information, please see the documentation for Websockets and Akka Streams:

* https://www.playframework.com/documentation/2.5.x/ScalaWebSockets
* http://doc.akka.io/docs/akka/current/scala/stream/stream-flows-and-basics.html#stream-materialization
* http://doc.akka.io/docs/akka/current/scala/stream/stream-integrations.html#integrating-with-actors
