# UPWORK ANDROID PROGRAMMING TEST 2016


1. What is the correct way to fix if checking the status of the GPS_PROVIDER throws SecurityException?  
  Answers:
  * request permission for ACCESS_COARSE_LOCATION
  * request permission for ACCESS_FINE_LOCATION
  * request permission for INSTALL_LOCATION_PROVIDER
  * None of the above

2. Consider the code snippet below:  
  >MediaPlayer mp = new MediaPlayer();  
  mp.setDataSource(PATH_TO_FILE);  
  &#60;Some code here>  
  mp.start();  
  Which of the following should be placed at &#60;Some code here>?  
  
  Answers:
  * mp.prepare();
  * mp.prepareAsync();
  * mp.loadMedia();
  * mp.loadSource();
  * mp.loadSource(); mp.prepare();
  * No code is required at &#60;Some code here> to start playback.

3. Which of the following would you have to include in your project to use the APIs and classes required to access the camera on the mobile device?  
  Answers:
  * import android.drivers;
  * import android.hardware.camera;
  * import android.camera;
  * import android.util;
  * import android.hardware;

4. Which of the following can be accomplished by using the TelephoneNumberUtil class?  
  Answers:
  * Save a phone number to the contacts in the phone device.
  * Retrieve a phone number from the contacts in the phone device.
  * Delete a phone number from the contacts in the phone device.
  * Format an international telephone number.
  * Setting and retrieving the call forwarding phone number on the phone device.

5. Which of the following are UI elements that you can use in a window in an Android application?
  Answers:
  * TextBox
  * TextView
  * TextField
  * TextElement
  * EditText
  * RichText

6. Which of the following is not Content Provider?  
  Answers:
  * Contacts
  * Contacts
  * Shared Preferences
  * MediaStore
  * Bookmarks
  * Settings

7. What does the following code do?  
  >SensorManager mgr = (SensorManager) getSystemService(SENSOR_SERVICE);  
  List&#60;Sensor> sensors = mgr.getSensorList(Sensor.TYPE_ALL);  
  for (Sensor sensor : sensors) {  
  System.out.println(""+sensor.getName());  
  }  
  
  Answers:
  * prints names of all available sensors in device
  * prints names of all available sensor types in device
  * prints names of all sensors which are not available
  * none of above

8. Which of the following is correct to use for data transfer regularly and efficiently, but not instantaneously?  
  Answers:
  * AsyncTask
  * IntentService
  * Sync adapters
  * All of these

9. What is the ListActivity class used for?  
  Answers:
  * Create a view to display a list of items from a data source.
  * List all the activities currently running on the Android device.
  * List all the activites that are installed on the Android device.
  * List the activities whose IntentFilters match with a particular Intent type.

10. Which of the following would you have to include in your project to use the SimpleAdapter class?  
  Answers:
  * import android.content;
  * import android.widget;
  * import android.database;
  * import android.database.sqlite;
  * import android.util;

11. Which of the following is the best way to request user permission if an Android application receives location updates from both NETWORK_PROVIDER and GPS_PROVIDER?  
  Answers:
  * Adding this line to the Android manifest file: &#60;uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
  * Adding these two lines to the Android manifest file: &#60;uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" /> &#60;uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />
  * Adding this line to the Android manifest file: &#60;uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
  * Adding this line to the Android manifest file: &#60;uses-permission android:name="android.permission.CONTROL_LOCATION_UPDATES" />

12. Which of the following can you use to display an HTML web page in an Android application?  
  Answers:
  * WebBrowser
  * BrowserView
  * WebView
  * Browser
  * HtmlView

13. Which of the following statements are correct with regards to signing applications?  
  a) All applications must be signed.  
  b) No certificate authority is needed.  
  c) When releasing application special debug key that is created by the Android SDK build tools can be used.  
  Answers:
  * a) and b) are true
  * a) and c) are true
  * b) and c) are true
  * all statements are true

14. Which of the following is the immediate base class for Activity and Service classes?  
  Answers:
  * Application
  * ApplicationContext
  * Context
  * Component
  * Object

15. Which of the following statement is correct regarding StrictMode?  
  Answers:
  * StrictMode detects improper layouts
  * StrictMode detects operation which blocks UI
  * StrictMode detects the speed of the connection
  * All of the above

16. Which of the following is/are appropriate for saving the state of an Android application?  
  Answers:
  * Activity.onFreeze()
  * Activity.onPause()
  * Activity.onStop()
  * Activity.onDestroy()

17. Which of the following are true about enabling/disabling menu items from an Activity class?  
  Answers:
  * onCreateOptionsMenu can be used to enable/disable some menu items in an Android application.
  * onPrepareOptionsMenu can be used to enable/disable some menu items in an Android application.
  * onShowOptionsMenu can be used to enable/disable some menu items in an Android application.
  * The menu items in an Android application cannot be disabled.

18. Using a content provider, which of the following operations are able to perform?  
  a) create  
  b) read  
  c) update  
  d) delete  
  Answers:
  * a, b and c
  * b, c and d
  * all of these
  * none of these

19. What does the following code do?
  >try {  
  String token = GoogleAuthUtil.getToken(this, email,   "https://www.googleapis.com/auth/devstorage.read_only");  
  System.out.println(token);  
  } catch (IOException e) {  
  System.out.println("IOException");  
  } catch (UserRecoverableAuthException e) {  
  System.out.println("UserRecoverableAuthException");  
  } catch (GoogleAuthException e) {  
  System.out.println("GoogleAuthException");  
  }  
  
  Answers:
  * prints token
  * prints IOException
  * prints UserRecoverableAuthException
  * prints GoogleAuthException

20. Which of the following should be used to save the unsaved data and release resources being used by an Android application?  
  Answers:
  * Activity.onStop()
  * Activity.onPause()
  * Activity.onDestroy()
  * Activity.onShutdown()
  * Activity.onFreeze()

21. Which of the following are true?  
  Answers:
  * startActivity and startActivityForResult can both be used to start a new activity from your activity class.
  * Only startActivityForResult can be used to launch a new activity from your activity class.
  * startActivity(myIntent); and startActivityForResult(myIntent, -1); have the same result.
  * startActivity(myIntent); and startActivityForResult(myIntent, 0); have the same result.
  * When startActivity is used to launch a new activity from your activity class then your activity class gets notified when the new activity is completed.
  * When startActivityForResult is used to launch a new activity from your activity class then your activity class gets notified when the new activity is completed.

22. Consider the XML fragment below, which is taken from one of the files in an Android project:  
  >&#60;MyElement xmlns:"http://schemas.androd.com/apk/res/android"  
  android:layout_width = "fill_parent"  
  android:layout_height = "fill_parent"  
  android:text = "Some Text">  
  &#60;/MyElement>  
  
  Which of the following are true about the XML fragment above?  
  Answers:
  * It is taken from the manifest XML file of the Android project.
  * It is taken from an XML file used to define a view.
  * It is taken from the package file (.apk) of the Android project.
  * The xmlns: attribute is a compulsory attribute.
  * If this is not the outer most tag in the XML file then it need not contain the xmlns: attribute.
  * MyElement should be the name of a class derived, directly or indirectly, from the View class.

23. Which of the following are true about Intent.CALL_ACTION and Intent.DIAL_ACTION?  
  Answers:
  * Both of them are used to dial a phone number on the device.
  * Intent.action == Intent.CALL_ACTION is true when a phone call is received on the device.
  * Intent.action = Intent.CALL_ACTION is used when a phone number is to be dialled without showing a UI on the device.
  * Intent.action = Intent.DIAL_ACTION is used when a phone number is to be dialled without showing a UI on the device.
  * Intent.action = Intent.CALL_ACTION is used when a phone number is to be dialled without the user having to explicitly initiate the call.
  * Intent.action = Intent.DIAL_ACTION is used when a phone number is to be dialled without the user having to explicitly initiate the call.

24. Suppose Screen1 is the main screen of an Android application MyAndroid. Now if another screen, Screen2 has to be opened from Screen1, then which of the following are true?  
  Answers:
  * Screen2 has to be a part of MyAndroid.
  * Screen2 can exist in any other Android application installed on the device.
  * Screen2 will always be launched asynchronously.
  * Screen2 can be launched synchronously.
  * Screen2 can return a result code to Screen1 if launched with startActivity.
  * Screen2 can return a result code to Screen1 if launched with startActivityForResult.

25. What is the best way of opening camera as sub-activity?  
  Answers:
  * Intent takePictureIntent = new Intent(MediaStore.ACTION_IMAGE_CAPTURE); startActivity(takePictureIntent);
  * Intent takePictureIntent = new Intent(MediaStore.ACTION_IMAGE_CAPTURE); if (takePictureIntent.resolveActivity(getPackageManager()) != null) { startActivityForResult(takePictureIntent, 1); }
  * Intent takePictureIntent = new Intent(MediaStore.ACTION_IMAGE_CAPTURE); startActivityForResult(takePictureIntent, 1);
  * Intent takePictureIntent = new Intent(MediaStore.ACTION_IMAGE_CAPTURE); if (takePictureIntent.resolveActivity(getPackageManager()) != null) { startActivityForResult(takePictureIntent, -1); }

26. What is the correct way to restrict app visibility on Google Play to devices that have a camera?  
  Answers:
  * &#60;uses-feature android:name="android.hardware.camera"/>
  * &#60;uses-feature android:name="android.hardware.camera" android:required="true" />
  * &#60;uses-feature android:name="android.hardware.camera.front" android:required="true" />
  * &#60;uses-permission android:name="android.permission.CAMERA"/>

27. Which of the following sensors is only hardware-based?  
  Answers:
  * linear acceleration sensor
  * gravity sensor
  * rotation vector sensor
  * accelerometer sensor

28. Which of the following formats is not supported in Android?  
  Answers:
  * MP4
  * MPEG
  * AVI
  * MIDI

29. Consider the code snippet below:  
  >public class MyReceiver extends PhoneStateIntentReceiver  
  {  
  @Override  
  public void onReceiveIntent(Context context, Intent intent)  
  {  
  if (intent.action == Intent.CALL_ACTION)  
  {  
  }  
  }  
  }  
  
  Assuming that notifyPhoneCallState has been called to enable MyReceiver to receive notifications about the phone call states, in which of the following cases will the code in get executed?  
  Answers:
  * When the device receives an incoming phone call.
  * When an outgoing phone call is initiated on the device.
  * When the user presses the CALL button on the device.
  * The code in will never get executed.

30. Which of the following packages provide the classes required to manage the Bluetooth functionality on an Android device?  
  Answers:
  * android.hardware
  * android.bluetooth
  * android.bluez
  * org.bluez

31. What is the purpose of the ContentProvider class?  
  Answers:
  * To play rich media content files.
  * To create and publish rich media files.
  * To share data between Android applications.
  * To access the global information about an application environment.
  * To maintain global application state.

32. Which of the following permissons is needed to perform the network operations through internet?  
  a) INTERNET
  b) ACCESS_NETWORK_STATE
  Answers:
  * a
  * b
  * both
  * none

33. What is "Android-Positron"?  
  Answers:
  * A command line tool to create Android project files.
  * A framework to create unit tests for Android projects.
  * A resource editor to create user interface for Android applications.
  * A tool to generate Android byte code from .class files.
  * An emulator to execute and debug Android projects.

34. Which of the following are true?  
  Answers:
  * Both startActivity and startSubActivity start an activity synchronously.
  * Both startActivity and startActivityForResults start an activity asynchronously.
  * startActivity is an asynchronous call, but startSubActivity is synchronous.
  * startActivity is a synchronous call, but startSubActivity is asynchronous.

35. Which of the following statements are correct with regards to Content Providers?  
  A) A content provider allows applications to access data.  
  B) A content provider must be declared in the AndroidManifest.xml file.  
  Answers:
  * Statement A is true, while Statement B is false.
  * Statement B is true, while Statement A is false.
  * Both statements are true.
  * Both statements are false.

36. Which of the following are Android build modes?  
  Answers:
  * Debug mode
  * Release mode
  * Production mode
  * Development mode

37. What is "Android-activityCreator"?  
  Answers:
  * A command line tool to create Android project files.
  * A framework to create unit tests for Android projects.
  * A resource editor to create user interface for Android applications.
  * A tool to generate Android byte code from .class files.
  * An emulator to execute and debug Android projects.

38. Which of the following permissions and configurations must be added in manifest file for implementing GCM Client?  
  A) com.google.android.c2dm.permission.RECEIVE  
  B) android.permission.INTERNET  
  C) android.permission.GET_ACCOUNTS  
  D) android.permission.WAKE_LOCK  
  E) applicationPackage + ".permission.C2D_MESSAGE"  
  F) A receiver for com.google.android.c2dm.intent.RECEIVE, with the category set as applicationPackage. The receiver should require the com.google.android.c2dm.SEND permission  
  Answers:  
  * A, B, C and D  
  * C, D, E and F  
  * A, B, E and F  
  * all of these  

39. Consider the following snippet of code:  
  >@Override  
  protected void onStop  
  {  
  Super.onStop();  
  SharedPreferences setting = getSharedPreferences("MyPrefs", 0);  
  SharedPreferences.Editor editor = settings.edit();  
  editor.putBoolean("MyBool", true);  
  &#60;some more code here>  
  }  
  Which of the following should be used &#60;some more code here>?  
  Answers:
  * editor.save(); editor.close();
  * editor.save(); editor.finish();
  * editor.commit();
  * editor.save();
  * editor.close();
  * editor.finish();

40. Which of the following are valid features that you can request using requestWindowFeature?  
  Answers:
  * FEATURE_NO_TITLE
  * FEATURE_NO_ICON
  * FEATURE_RIGHT_ICON
  * FEATURE_NO_MENU
  * FEATURE_TRANSPARENT_WINDOW

41. Which of the following fields of the Message class should be used to store custom message codes about the Message?  
  Answers:
  * tag
  * what
  * arg1
  * arg2
  * userData

42. What is the interface Spannable used for?  
  Answers:  
  * Manipulate text that can span across multiple pages.
  * Manipulate text that can span across multiple TextView windows.
  * This is the interface for text to which markup objects can be attached and detached.
  * String parsing.

43. Which of the following can be used to handle commands from menu items in an Android application?  
  Answers:
  * commandAction
  * onMenuItem
  * onMenuItemSelected
  * onMenuItemClicked
  * onOptionsItemSelected

44. Which of the following are classes that can be used to handle the Bluetooth functionality on a device?  
  Answers:
  * Adapte
  * Manage
  * Matche
  * BluetoothAdapte

45. Which of the following can be used to bind data from an SQL database to a ListView in an Android application?  
  Answers:
  * SimpleCursor
  * SimpleCursorAdapter
  * SimpleAdapter
  * SQLiteCursor
  * SQLLiteAdapter

46. Which of the following statements are correct with regards to calling place GoogleAuthUtil.getToken()?  
  A) call getToken() on the UI thread  
  B) call getToken() on AsyncTask  
  Answers:  
  * Statement A is true, while Statement B is false.
  * Statement B is true, while Statement A is false.
  * Both statements are true.
  * Both statements are false.

47. Which of the following Integrated Development Environments can be used for developing software applications for the Android platform?  
  Answers:
  * Android IDE
  * Eclipse
  * Visual Studio 2005
  * Visual Studio 2008

48. Which of the following functions will return all available Content Providers?  
  Answers:
  * List&#60;ProviderInfo> returnList = new ArrayList&#60;ProvderInfo>(); for (PackageInfo pack : getPackageManager().getInstalledPackages(PackageManager.GET_PROVIDERS)) { ProviderInfo[] providers = pack.providers; if (providers != null) { returnList.addAll(Arrays.asList(providers)); } } return returnList;
  * return getContext().getPackageManager().queryContentProviders("com.google", Process.myUid(), 0);
  * List&#60;ActivityInfo> returnList = new ArrayList&#60;ActivityInfo>(); for (PackageInfo pack : getPackageManager().getInstalledPackages(PackageManager.GET_RECEIVERS)) { ActivityInfo[] providers = pack.receivers; if (providers != null) { returnList.addAll(Arrays.asList(providers)); } } return returnList;
  * None of these.

49. What is Android?  
  Answers:
  * A new programming language that can be used to develop applications for mobile devices.
  * A new IDE that can be used to develop applications for mobile devices.
  * A software stack for mobile devices that includes an operating system, middleware and key applications.
  * A new mobile device developed by Google.

50. Which of the following can you use to add items to the screen menu?  
  Answers:
  * Activity.onCreate
  * Activity.onCreateOptionsMenu
  * Constructor of the Activity class.
  * Activity.onCreateMenu
  * Activity.onStart
  * Activity.onPrepareOptionsMenu

51. Which of the following are valid ways to deploy an Android application to a device?  
  Answers:
  * Using the "adb install /path/to/apk" command from the command prompt/terminal, when USB Debugging Mode is enabled in the device.
  * Exporting and signing the package, then browsing it to install.
  * Launching the application from an IDE, when USB Debugging Mode is enabled in the device.
  * All of these.

52. Which of the following tools can be used to reduce apk package size?  
  Answers:
  * lint
  * ProGuard
  * zipalign
  * etc1tool

53. Which of the following widgets helps to embed images in activities?  
  Answers:
  * ImageView
  * ImageButton
  * both of above
  * none of these

54. What is "Android-dx"?  
  Answers:
  * A command line tool to create Android project files.
  * A framework to create unit tests for Android projects.
  * A resource editor to create user interface for Android applications.
  * A tool to generate Android byte code from .class files.
  * An emulator to execute and debug Android projects.

55. Which of the following protocols are provided by Google for GCM Connection Servers?  
  A) HTTP  
  B) XMPP  
  C) SOAP  
  D) RMI  
  Answers:
  * A and B
  * A, B, C
  * C, D
  * all of these

56. ____ makes appropriate list of application data for the other applications  
  Answers:
  * service provider
  * content provider
  * application provider
  * resource

57. Which of the following 4 classes does not relate to others?  
  ApplicationInfo, SyncInfo, ActivityInfo, PackageInfo
  Answers:
  * ApplicationInfo
  * SyncInfo
  * ActivityInfo
  * PackageInfo

58. The simplest widget is the label, referred to in Android as a ____________  
  Answers:
  * TextView
  * grid view
  * lableview
  * none of these

59. Which of the following can you use to display a progress bar in an Android application?  
  Answers:
  * ProgressBar
  * ProgressDialog
  * ProgressItem

60. Which of the following statements are correct with regards to publishing updates of apps on Google Play?  
  Answers:
  * The android:versionCode attribute in the manifest file must be incremented and the APK file must be signed with the same private key.
  * The android:versionCode attribute in the manifest file must be same and the APK file must be signed with the same private key.
  * The android:versionCode attribute in the manifest file must be incremented and the APK file must be signed with the new private key.
  * The android:versionCode attribute in the manifest file must be same and the APK file must be signed with the new private key.

61. Which of the following 4 classes does not relate to other?  
  SQLiteOpenHelper, SQLiteDatabase, Cursor, ContentProvider  
  Answers:  
  * SQLiteOpenHelper
  * SQLiteDatabase
  * Cursor
  * ContentProvider

62. What does the following statement define?  
  It provides query(), insert(), update(), and delete() methods for accessing data from a content provider and invokes identically-named methods on an instance of a concrete content provider.  
  Answers:  
  * CursorLoader
  * ContentResolver
  * ContentProvider
  * Loader

63. What is the advantage of using AsyncTaskLoader instead of AsyncTask?  
  Answers:
  * a bit easier to work with
  * the possibility easily update progress bar
  * no comparison, because it implements completely different functionality
  * less work with the configuration of application

64. What does the following code do?  
  >public boolean isOnline() {  
  ConnectivityManager connMgr = (ConnectivityManager)   getSystemService(Context.CONNECTIVITY_SERVICE);  
  NetworkInfo networkInfo = connMgr.getActiveNetworkInfo();  
  return (networkInfo != null && networkInfo.isConnected());  
  }  
  
  Answers:
  * checking Network connection.
  * checking only WIFI network connectivity.
  * checking only Bluetooth data connection.
  * checking only Ethernet data connection

65. Which of the following statements are correct with regards to running of the Sync Adapter?  
  A) Running sync adapter in response to a user request.
  B) Running sync adapter periodically by setting a period of time to wait between runs, or by running it at certain times of the day, or both.
  Answers:
  * Statement A is true, while Statement B is false.
  * Statement B is true, while Statement A is false.
  * Both statements are true.
  * Both statements are false.

66. Which of the following classes is not used in working with database?  
  Answers:
  * SQLiteOpenHelper
  * SQLiteDatabase
  * ContentProvider
  * DatabaseHelper

67. Which of the following is the parent class for the main application class in an Android application that has a user interface?  
  Answers:
  * MIDLet
  * AndroidApp
  * Activity
  * AppLet
  * Application

68. Which of the following are true about PhoneStateIntentReceiver.notifyPhoneCallState?  
  Answers:
  * notifyPhoneCallState has to be called if your application wishes to receive a notification about an incoming phone call.
  * notifyPhoneCallState is a call back function that is called when the call state changes.
  * notifyPhoneCallState is called to initiate a call from the device.
  * notifyPhoneCallState is used to send notifications about call states.
  * notifyPhoneCallState gets called when the device receives an incoming phone call.

69. How many expansion files can an APK file have? Select all correct options.  
  Answers:
  * one
  * two
  * three
  * four

70. Select the two function calls that can be used to start a Service from your Android application?  
  Answers:
  * bindService
  * startService
  * runService
  * startActivity

71. What is "Android-Positron"?  
  Answers:
  * A command line tool to create Android project files.
  * A framework to create unit tests for Android projects.
  * A resource editor to create user interface for Android applications.
  * A tool to generate Android byte code from .class files.
  * An emulator to execute and debug Android projects.

72. Which of the following is not a life-cycle methods of an Activity that can be implemented to perform various operations during the lifetime of an Activity?  
  Answers:
  * onCreate
  * onInit
  * onCompleteThaw
  * onRestart

73. What is correct regarding GCM — Google Cloud Messaging service?  
  Answers:
  * It does server to device communication.
  * It does device to server communication.
  * It does device to server communication and vice versa.
  * It does device to device communication.

74. Which of the following procedures will get the package name of an APK file?  
  Answers:
  * Looking for the package attribute’s value of the &#60;manifest> element in the manifest file.
  * Executing the command, "pm list packages -f", in the ADB shell.
  * Programmatically, using PackageManager in an installed Android app.
  * Using the AAPT platform tool, "aapt dump badging apkName.apk".

75. What is the maximum supported file size for a single APK file (excluding expansion packages) in the Google Play Store?  
  Answers:
  * 50MB
  * 2GB
  * 30MB
  * unlimited

76. Which of the following can be used to navigate between screens of different Android applications?  
  Answers:
  * Binde
  * Flow
  * Navigate
  * Intent
  * ApplicationContext

77. Fill in the blank:
Once an app is published, the ________ cannot be changed. It should be unique for each APK.  
  Answers:
  * private key
  * package name
  * main activity
  * APK file name

78. Which of the following attributes in the manifest file defines version information of an application for the Google Play Store (as opposed to defining version information for display to users)?  
  Answers:
  * android:versionCode
  * android:versionName
  * android:targetSdkVersion
  * android:maxSdkVersion

79. Suppose MyView is a class derived from View and mView is a variable of type MyView. Which of the following should be used to display mView when the Android application is started?  
  Answers:
  * Call setCurrentView(mView) in the startApp() of the main application class.
  * Call setContentView(mView) in the startApp() of the main application class.
  * Call setContentView(mView) in the onStart() of the main application class.
  * Call setContentView(mView) in the onCreate() of the main application class.

80. Which of the following programming languages can be used to develop software applications for the Android platform?  
  Answers:
  * Java
  * C# with .NET Compact Framework for mobile devices.
  * C programming language.
  * Android programming language.

81. What is the maximum supported size for a single expansion file in the Google Play Store?  
  Answers:
  * 50MB
  * 2GB
  * 30MB
  * unlimited

82. What does the following code do?  
  >public boolean isOnline() {  
  ConnectivityManager connMgr = (ConnectivityManager)   getSystemService(Context.CONNECTIVITY_SERVICE);  
  NetworkInfo networkInfo = connMgr.getActiveNetworkInfo();  
  return (networkInfo != null &amp;&amp; networkInfo.isConnected());  
  }  

  Answers:
  * checking Network connection. 
  * checking only WIFI network connectivity.
  * checking only Bluetooth data connection.
  * checking only Ethernet data connection.


