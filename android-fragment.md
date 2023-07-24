#### Activity and Fragment

1. **What is `Activity`?**

2. **What is `Activity's` lifecycle?**
  
![Activity Lifecycle](https://github.com/parthika2027/Android-Interview-Question/blob/main/img/activity_lifecycle.png)

3. **What is `Fragment` and its lifecycle.**

4. **What is the difference between FragmentPagerAdapter vs FragmentStatePagerAdapter?**
    - FragmentPagerAdapter: Each fragment visited by the user will be stored in the memory but the view will be destroyed. When the page is revisited, then the view will be created not the instance of the fragment.
    - FragmentStatePagerAdapter: Here, the fragment instance will be destroyed when it is not visible to the user, except the saved state of the fragment.
5. **Compare Activity Lifecycle with Fragment Lifecycle**

![all txt](https://github.com/parthika2027/Android-Interview-Question/blob/main/img/activity_fragment.png)

Fragment and Activity lifecycles work in parallel. The linear dependence between their lifecycle ends as soon as both activity and fragment are created
Note that onStart and onResume (and similarly, onStop and onPause) for both fragment and activity execute in parallel and there is no guarantee of order. Sometimes fragment will take precedence over activity, and vice versa.
The only guarantee is that activity's onCreate will always be called first. After that, the fragment acts on its own.

7. **What are the activity lifecycle methods that trigger when the user clicks the home button?**

Ans: OnPause and OnStop

8. **What are the activity lifecycle methods that trigger when the user clicks the back button and then again brings back the app to the foreground?**

Ans: //When clicking the back button 
OnPause 
OnStop 
//When bringing back the app to foreground 
OnRestart 
onStart 
OnResume

9. **What are the activity lifecycle methods that trigger when the user clicks the back button?**

Ans: OnPause
OnStop
OnDestroy

10. **What are the activity lifecycle methods that trigger when user navigate from ActivityA to ActivityB?**

Ans: 
- A — onPause 
- B — onCreate 
- B — onStart 
- B — onResume 
- A — onStop

11. **What happens if the user clicks the back button in ActivityB?**

Ans: 
- B — onPause 
- A — onRestart 
- A — onStart 
- A — onResume 
- B — onStop 
- B — onDestroy

12.  **When onDestroy calls?**

Ans: Perform any final cleanup before an activity is destroyed. This can happen either because the activity is finishing (someone called finish() on it)
