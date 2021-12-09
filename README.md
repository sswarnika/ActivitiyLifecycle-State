# ActivityLifecycle-State

Added the two activity app from the previous tasks,
Added lifecycle callbaks to the Main Activity,
Added lifecycle callbacks to the Second Activity,
Added Save and Restrore to the ACtivity instance State.

Homework Questions:

Question 1
If you run the homework app before implementing onSaveInstanceState(), what happens if you rotate the device?
The counter is reset to 0, and the EditText no longer contains the text you entered.

Question 2
What Activity lifecycle methods are called when a device-configuration change (such as rotation) occurs?
Android shuts down your Activity by calling onPause(), onStop(), and onDestroy(), and then starts it over again, calling onCreate(), onStart(), and onResume().

Question 3
When in the Activity lifecycle is onSaveInstanceState() called?
onSaveInstanceState() is called before the onStop() method.

Question 4
Which Activity lifecycle methods are best to use for saving data before the Activity is finished or destroyed?
onPause() or onStop()

