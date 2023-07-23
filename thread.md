# Thread

1. **What is Thread?**

Ans: Thread is one of the important concepts in Android. Thread is a lightweight sub-process that provides us with a way to do background operations without interrupting the User Interface (UI). When an app is launched, it creates a single thread in which all app components will run by default.

The thread which is created by the runtime system is known as the main thread. The main thread’s primary role is to handle the UI in terms of event handling and interaction with views in the UI. If there is a task that is time-consuming and that task is run on the main thread, then it will stop other tasks until it gets completed, which in turn may result in displaying a warning “Application is unresponsive” to the user by the operating system. So we need different threads for such tasks and some other tasks.

2. **Categorize Threading?**

Ans: In Android, you’ll categorize all threading components into two basic categories: 
Threads that are attached to an activity/fragment: These threads are tied to the lifecycle of the activity/fragment and are terminated as soon because the activity/fragment is destroyed.
		Eg: AsynsTask, Loader
Threads that aren’t attached to any activity/fragment: These threads can still run beyond the lifetime of the activity/fragment (if any) from which they were spawned.
Eg. Services

3. **Types of Thread in mobile devices?**

- Main Thread
- UI Thread:
- Worker Thread
