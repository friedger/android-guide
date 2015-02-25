# [Activity Lifecycle and Data](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730)

*This chapter has been revised in February 2015 to reflect the updated course materials used with Sunshine-v2.*

### **Goals**:
1. Understand Activity Lifecyle
2. What to do in different callbacks (onPause, onStop..)
3. Saving/Restoring State (Bundles)
4. Storing Data (SQLite)
5. Data Contracts & SQLiteOpenHelper
6. Instrument for simple Unit Testing

### **Code Steps (Sunshine v2) **
1. [Life Cycle](https://github.com/udacity/Sunshine-Version-2/tree/4.01_life_cycle)
2. [Start Code For Lesson 4](https://github.com/udacity/Sunshine-Version-2/tree/4.02_start_code_for_lesson_4)
3. [Define Contract Constants](https://github.com/udacity/Sunshine-Version-2/tree/4.03_define_contract_constants)
4. [Location Database](https://github.com/udacity/Sunshine-Version-2/tree/4.04_location_database)
5. [Test Location Table](https://github.com/udacity/Sunshine-Version-2/tree/4.05_test_location_table)
6. [Test Weather Table](https://github.com/udacity/Sunshine-Version-2/tree/4.06_test_weather_table)


### **SubChapters**:
1. [Introduction to Lesson 4](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/m-1620448626) (0:43)
2. [Why We Need an Activity Lifecycle](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/m-1589798633) (1:41)
3. [The Android Activity Lifecycle](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/m-1583638626) (1:23)
4. [Active and Visible Lifetimes](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/m-1583638627) (1:58)
5. [Lifecycle Events Quiz](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3607628747/m-1601448690) (0:22) [(Task)](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3607628747/m-1575878724) [(*Solution*)](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3607628747/m-1601448691)
6. [Activity Termination](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3606388753/m-1606918620) (0:21) [(Task)](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3606388753/m-1648718609) [(*Solution*)](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3606388753/m-1640278568)
7. [How to Prepare for Termination](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/m-1638468930) (1:02)
8. [What To Do in OnPause/OnStop Quiz](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3607248728/m-1633698589) (0:28) [(Task)](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3607248728/m-1575878726) [(*Solution*)](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3607248728/m-1633698590)
9. [Activity Lifecycle Recap](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/m-1615278580) (0:45)
10. [Maintaining State](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/m-1623188629) (1:10)
11. [Storing Data in Android: Intro](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/m-3677608539) (2:07)
12. [Optional SQLite Tutorial](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/m-2602608541)
13. [Storing Data: SQLite DB Quiz](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3629689170/m-3627479031) (3:04) [(Task)](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3629689170/m-2450948548) [(*Solution*)](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3629689170/m-3666188698)
14. [Storing Data in Android: Conclusion](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/m-3677438574) (0:53)
15. [How We're Changing Sunshine](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/m-3602748953) (0:47)
16. [Get The Starter Code](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/m-3617349500) [GitHub Repo](https://github.com/udacity/Sunshine-Version-2/tree/lesson_4_starter_code)
17. [Intro to WeatherContract](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/m-3661228653) (1:28)
18. [Weather Table Columns Quiz](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3641159006/m-3602719481) (0:31) [(Task)](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3641159006/m-3600409885) [(*Solution*)](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3641159006/m-3621979749)
19. [Weather and Location Tables](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/m-3644178948) (1:12)
20. [Two Tables Quiz](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3651328774/m-3641928933) (0:13) [(Task)](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3651328774/m-3613579161) [(*Solution*)](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3651328774/m-3677748544)
21. [Our Weather Contract](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/m-3635768772) (1:42)
22. [Define Constants in Contract](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3597819307/m-3671828649) (0:48) [(Task)](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3597819307/m-3648328762) [(*Solution*)](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3597819307/m-3614578817)
23. [SQLiteOpenHelper and Sunshine Database](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/m-3625419128) (5:41)
24. [Create Sunshine Location Database Quiz](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3651679153/m-3636879012) (0:58) [(Task)](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3651679153/m-3619939598) [(*Solution*)](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3651679153/m-3651629136)
25. [SQLiteOpenHelper onUpgrade()](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/m-3657678767) (1:10)
26. [Read/Write from a Database](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/m-3600288930) (3:36)
27. [Test Read/Write from Location Table](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3610188901/m-3617879357) (0:24) [(Task)](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3610188901/m-3663378724) [(*Solution*)](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3610188901/m-3644818769)
28. [Test Read/Write from Weather Tbl](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3638128844/m-3647399078) (0:19) [(Task)](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3638128844/m-3653188827) [(*Solution*)](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/e-3638128844/m-3628158744)


### **Lesson Resources**

1. [Android Activity Cycle](http://developer.android.com/training/basics/activity-lifecycle/starting.html) (Android Developers)
2. [When to include an Exit Button in Your Android App](https://www.youtube.com/watch?v=631T7B8HOv4) (Reto Meier, Android Developers on YouTube)
3. [SQL Lite Tutorial ](https://www.udacity.com/course/viewer#!/c-ud853/l-3621368730/m-2602608541) (replicated in Appendix C)
4. [Using sqlite3](http://developer.android.com/tools/help/sqlite3.html) (Android Developers)
5. [Storage Options](http://developer.android.com/guide/topics/data/data-storage.html) (Android Developers)
6. [Contacts Contract](http://developer.android.com/reference/android/provider/ContactsContract.html)
7. [SQL Tutorial](http://www.w3schools.com/sql/) (W3Schools) - see Foreign Keys
8. [BaseColumns](http://developer.android.com/reference/android/provider/BaseColumns.html) (base for derived tables in a Contract)
9. [Android Testing Fundamentals](http://developer.android.com/tools/testing/testing_android.html)
10. [JUnit Testing](http://www.tutorialspoint.com/junit/junit_quick_guide.htm)
11. [SQLiteOpenHelper](http://developer.android.com/reference/android/database/sqlite/SQLiteOpenHelper.html)
12. [ALTER TABLE reference](https://www.sqlite.org/lang_altertable.html)
13. [SQLite Database Docs](http://developer.android.com/reference/android/database/sqlite/SQLiteDatabase.html) (Android Developers)
14. [Test Values for Location Test (Gist)](https://gist.github.com/anonymous/c758e97765f2ca48fbc6)




### **Notes**

**Understanding the Android Activity Lifecyle** -

Note the presence of two cyclic paths here.

The first (active-paused-active) reflects an activity going in and out of focus (e.g., as a dialog or other view obscures part of the activity, leaving it visible but not in focus).

The second (active-paused-stopped-restarting-visible-active) reflects an activity being covered by another activity, leaving it invisible (but potentially still "alive" in the background) but ready to resurface when the top level activity is terminated.

![](https://s3.amazonaws.com/content.udacity-data.com/course/ud853/Android_Activity_LifeCyle.png)



### **Issues (Q&A)**

*We'll use this section to document and answer popular questions from study participants about this lesson.*