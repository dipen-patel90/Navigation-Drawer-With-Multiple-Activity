Navigation-Drawer-With-Multiple-Activity
========================================

Navigation Drawer With Multiple Activty

Now a days most of the Android application are using Navigation Drawer/Sliding Drawer like view.
Some of them are using library for doing this. Android has also provided Navigation Drawer to achieve this.
http://developer.android.com/training/implementing-navigation/nav-drawer.html

In this above link we can find demo app to add navigation drawer in our app. 
But we have to use fragment for achieving this and it is recommend to use fragment.

But in case if we don't want to use fragment or we want to add Navigation Drawer in already existing app 
which contain activities and we don't want to replace them with fragment.

We can achieve same Navigation Drawer with activities too....
I have added here demo app to add Navigation Drawer with multiple activities.


First of all we have to create on BaseActivity which will contain layout and all the code related to navigation drawer 
and then we will use this BaseActivity as parent activity to other activities.

We will extends this BaseActivity  to all the other activities rather than directly extending 
Activity class in our activities. 
This way our all the activities will contain same Navigation Drawer without adding any extra code in every activity.
