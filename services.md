1. **What is a service in Android?**

Ans: Services in Android are a special component that facilitates an application to run in the background in order to perform long-running operation tasks. The prime aim of a service is to ensure that the application remains active in the background so that the user can operate multiple applications at the same time

2. **Explain service lifecycle methods**
3. **Difference between UnBound Service, Bound Service, and Intent Service?**
4. **What is the difference between bound and unbounded service?**

Ans:
- Bound Service: Service which calls indefinitely in between activity. An Android component may bind itself to a Service using bindservice (). A bound service would run as long as the other application components are bound to it. As soon as they unbind, the service destroys itself.
- Unbound Service: Service which call at the life span of calling activity. In this case, an application component starts the service, and it would continue to run in the background, even if the original component that initiated it is destroyed. For instance, when started, a service would continue to play music in the background indefinitely.


5. **Can an IntentService execute multiple tasks sequentially?**
6. **How can we make the AlarmService run forever even after device reboot?**

Ans: Once you start an AlarmService, it runs forever until your device restarts. Once your device restart, you have to start the service explicitly to run it forever again. You have to register BroadcastReceiver to handle boot event

7. **What are the key differences between a service and IntentService in Android?**
8. **What is the importance of using a sticky service?**

Ans: A sticky service is a service that remains running in the background even after the component that started it is destroyed. This is important because it allows the service to continue performing its task even if the user is no longer interacting with the app. For example, a music player service would use a sticky service so that it can continue playing music even if the user closes the app.

9. **When should you use an IntentService instead of a regular service?**

Ans: An IntentService is used when you want to perform a task in the background, but don’t need to return a result to the caller. A regular service is used when you need to perform a task in the background and return a result to the caller.

10. **What is the difference between a bound and started service?**
11. **Why is it important to restrict background processing by using Services?**

Ans: There are a few reasons why it is important to restrict background processing by using Services. First, it can help improve battery life by preventing apps from using up resources when they are not actively being used. Second, it can help improve performance by preventing apps from running in the background and slowing down the device. Finally, it can help improve security by preventing apps from accessing sensitive data or performing actions that the user may not be aware of.

12. **Can you explain how to send messages from service to other components?**
13. **Where does a service run?**

Ans: A service in Android can run either in the same process as the activity or in a separate process. If the service is running in the same process as the activity, then it will be destroyed when the activity is destroyed. If the service is running in a separate process, then it will continue to run even if the activity is destroyed.

14. **What are the differences between Service and Thread?**

15.  **What is started Service?**

Started: A service is started when an application component, such as an activity, starts it by calling startService(). Once started, a service can run in the background indefinitely, even if the component that started it is destroyed.

