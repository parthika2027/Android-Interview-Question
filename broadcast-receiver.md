## Broadcast Receiver

1. **What is Broadcast Receiver?**

Ans: A broadcast receiver (receiver) is an Android component that allows you to register for system or application events. Android apps can send or receive broadcast messages from the Android system and other Android apps, similar to the publish-subscribe design pattern. These broadcasts are sent when an event of interest occurs. For example, the Android system sends broadcasts when various system events occur, such as when the system boots up or the device starts charging. Apps can also send custom broadcasts, for example, to notify other apps of something that they might be interested in (for example, some new data has been downloaded).

Apps can register to receive specific broadcasts. When a broadcast is sent, the system automatically routes broadcasts to apps that have subscribed to receive that particular type of broadcast. Unlike activities, android BroadcastReceiver doesn’t contain any user interface. Broadcast receiver is generally implemented to delegate the tasks to services depending on the type of intent data that are received.

2. **Type of Broadcast Receiver with Details?**

Ans: Apps can receive broadcasts in two ways:
- Manifest-declared receivers
- Context-registered receivers

3. 
