#### Activity and Fragment

1. **What is `Activity` and its lifecycle?**

2. **What is `Activity's` lifecycle?**
  
3. **What is `Fragment` and its lifecycle.**

4. **What is the difference between FragmentPagerAdapter vs FragmentStatePagerAdapter?**
    - FragmentPagerAdapter: Each fragment visited by the user will be stored in the memory but the view will be destroyed. When the page is revisited, then the view will be created not the instance of the fragment.
    - FragmentStatePagerAdapter: Here, the fragment instance will be destroyed when it is not visible to the user, except the saved state of the fragment.
