# Associate Android Developer Certification Cheat Sheet
Associate Android Developer Certification Cheat Sheet

## Project Reference
1. [LemonadeApp](https://developer.android.com/codelabs/basic-android-kotlin-training-project-lemonade?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-basics-kotlin-four%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fbasic-android-kotlin-training-project-lemonade#3)
2. [DogglersApp](https://developer.android.com/codelabs/basic-android-kotlin-training-project-dogglers-app?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-basics-kotlin-unit-2-pathway-3%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fbasic-android-kotlin-training-project-dogglers-app#2)
3. [LunchTray](https://developer.android.com/codelabs/basic-android-kotlin-training-project-lunch-tray?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-basics-kotlin-unit-3-pathway-5%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fbasic-android-kotlin-training-project-lunch-tray#2)
4. [Amphibians](https://developer.android.com/codelabs/basic-android-kotlin-training-project-amphibians?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-basics-kotlin-unit-4-pathway-2%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fbasic-android-kotlin-training-project-amphibians#2)
5. [ForageApp](https://developer.android.com/codelabs/basic-android-kotlin-training-project-forage?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-basics-kotlin-unit-5-pathway-2%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fbasic-android-kotlin-training-project-forage#3)
6. [WaterMe](https://developer.android.com/codelabs/basic-android-kotlin-training-project-water-me?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-basics-kotlin-unit-6-pathway-1%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fbasic-android-kotlin-training-project-water-me#3)

## Study Guide
https://developers.google.com/training/certification/associate-android-developer/study-guide/

## Topics List

- [1. Android Core:](#1-android-core)
	- [1.1 Understand the architecture of the Android system](#11-understand-the-architecture-of-the-android-system)
	- [1.2 Be able to describe the basic building blocks of an Android app](#12-be-able-to-describe-the-basic-building-blocks-of-an-android-app)
	- [1.3 Know how to build and run an Android app](#13-know-how-to-build-and-run-an-android-app)
	- [1.4 Display simple messages in a popup using a Toast or a Snackbar](#14-display-simple-messages-in-a-popup-using-a-toast-or-a-snackbar)
		- [1.4.1 Toast](#141-toast)
		- [1.4.2 Snackbar](#142-snackbar)
	- [1.5 Be able to display a message outside your app's UI using Notifications](#15-be-able-to-display-a-message-outside-your-apps-ui-using-notifications)
		- [1.5.1 Builder](#151-builder)
		- [1.5.2 Set Channel](#152-set-channel)
		- [1.5.3 Show](#153-show)
	- [1.6 Understand how to localize an app](#16-understand-how-to-localize-an-app)
	- [1.7 Be able to schedule a background task using WorkManager](#17-be-able-to-schedule-a-background-task-using-workmanager)
		- [1.7.1 CodeLab](#171-codelab)
		- [1.7.2 Worker](#172-worker)
		- [1.7.3 Work Request](#173-work-request)
		- [1.7.4. Work Manager](#174-work-manager)
- [2. User Interface:](#2-user-interface)
	- [2.1 Understand the Android activity lifecycle](#21-understand-the-android-activity-lifecycle)
		- [2.1.1 Activity lifecycle](#211-activity-lifecycle)
		- [2.1.2 Fragment lifecycle](#212-fragment-lifecycle)
	- [2.2 Be able to create an Activity that displays a Layout](#22-be-able-to-create-an-activity-that-displays-a-layout)
	- [2.3 Be able to construct a UI with ConstraintLayout](#23-be-able-to-construct-a-ui-with-constraintlayout)
	- [2.4 Understand how to create a custom View class and add it to a Layout](#24-understand-how-to-create-a-custom-view-class-and-add-it-to-a-layout)
	- [2.5 Know how to implement a custom app theme](#25-know-how-to-implement-a-custom-app-theme)
	- [2.6 Be able to add accessibility hooks to a custom View](#26-be-able-to-add-accessibility-hooks-to-a-custom-view)
	- [2.7 Know how to apply content descriptions to views for accessibility](#27-know-how-to-apply-content-descriptions-to-views-for-accessibility)
	- [2.8 Understand how to display items in a RecyclerView](#28-understand-how-to-display-items-in-a-recyclerview)
	- [2.9 Be able to bind local data to a RecyclerView list using the Paging library](#29-be-able-to-bind-local-data-to-a-recyclerview-list-using-the-paging-library)
	- [2.10 Know how to implement menu-based navigation](#210-know-how-to-implement-menu-based-navigation)
	- [2.11 Understand how to implement drawer navigation](#211-understand-how-to-implement-drawer-navigation)
- [3. Data Management:](#3-data-management)
	- [3.1 Understand how to define data using Room entities](#31-understand-how-to-define-data-using-room-entities)
	- [3.2 Be able to access Room database with data access object (DAO)](#32-be-able-to-access-room-database-with-data-access-object-dao)
	- [3.3 Know how to observe and respond to changing data using LiveData](#33-know-how-to-observe-and-respond-to-changing-data-using-livedata)
	- [3.4 Understand how to use a Repository to mediate data operations](#34-understand-how-to-use-a-repository-to-mediate-data-operations)
	- [3.5 Be able to read and parse raw resources or asset files](#35-be-able-to-read-and-parse-raw-resources-or-asset-files)
	- [3.6 Be able to create persistent Preference data from user input](#36-be-able-to-create-persistent-preference-data-from-user-input)
	- [3.7 Understand how to change the behavior of the app based on user preferences](#37-understand-how-to-change-the-behavior-of-the-app-based-on-user-preferences)
- [4. Debugging:](4-#debugging)
	- [4.1 Understand the basic debugging techniques available in Android Studio](#41-understand-the-basic-debugging-techniques-available-in-android-studio)
	- [4.2 Know how to debug and fix issues with an app's functional behavior and usability](#42-know-how-to-debug-and-fix-issues-with-an-apps-functional-behavior-and-usability)
	- [4.3 Be able to use the System Log to output debug information](#43-be-able-to-use-the-system-log-to-output-debug-information)
	- [4.4 Understand how to use breakpoints in Android Studio](#44-understand-how-to-use-breakpoints-in-android-studio)
	- [4.5 Know how to inspect variables using Android Studio](#45-know-how-to-inspect-variables-using-android-studio)
- [5. Testing：](#5-testing)
	- [5.1 Thoroughly understand the fundamentals of testing](51-thoroughly-understand-the-fundamentals-of-testing)
	- [5.2 Be able to write useful local JUnit tests](#52-be-able-to-write-useful-local-junit-tests)
	- [5.3 Understand the Espresso UI test framework](#53-understand-the-espresso-ui-test-framework)
	- [5.4 Know how to write useful automated Android tests](#54-know-how-to-write-useful-automated-android-tests)
	
		
## Topic Descriptions
### 1. Android Core:

#### [1.1 Understand the architecture of the Android system](https://developer.android.com/guide/components/fundamentals)

#### [1.2 Be able to describe the basic building blocks of an Android app](https://developer.android.com/guide/components/fundamentals)

#### [1.3 Know how to build and run an Android app](https://developer.android.com/guide/components/fundamentals)

#### 1.4 Display simple messages in a popup using a Toast or a Snackbar

##### [1.4.1 Toast](https://developer.android.com/guide/topics/ui/notifiers/toasts):

```kotlin
val text = "Hello toast!"
val duration = Toast.LENGTH_SHORT

val toast = Toast.makeText(applicationContext, text, duration)
toast.show()
```

##### [1.4.2 Snackbar](https://developer.android.com/develop/ui/views/notifications/snackbar/showing):

```kotlin
Snackbar.make(
        findViewById(R.id.myCoordinatorLayout),
        R.string.email_sent,
        Snackbar.LENGTH_SHORT
).show()
```



#### [1.5 Be able to display a message outside your app's UI using Notifications](https://developer.android.com/guide/topics/ui/notifiers/notifications)
[codelab](https://developer.android.com/codelabs/advanced-android-kotlin-training-notifications#3)

```
val core_version = "1.6.0"
dependencies {
    implementation("androidx.core:core-ktx:$core_version")
}
```

##### 1.5.1 Builder
```kotlin
var builder = NotificationCompat.Builder(this, CHANNEL_ID)
        .setSmallIcon(R.drawable.notification_icon)
        .setContentTitle(textTitle)
        .setContentText(textContent)
        .setPriority(NotificationCompat.PRIORITY_DEFAULT)
```

##### 1.5.2 Set Channel
```kotlin
private fun createNotificationChannel() {
    // Create the NotificationChannel, but only on API 26+ because
    // the NotificationChannel class is new and not in the support library
    if (Build.VERSION.SDK_INT >= Build.VERSION_CODES.O) {
        val name = getString(R.string.channel_name)
        val descriptionText = getString(R.string.channel_description)
        val importance = NotificationManager.IMPORTANCE_DEFAULT
        val channel = NotificationChannel(CHANNEL_ID, name, importance).apply {
            description = descriptionText
        }
        // Register the channel with the system
        val notificationManager: NotificationManager =
            getSystemService(Context.NOTIFICATION_SERVICE) as NotificationManager
        notificationManager.createNotificationChannel(channel)
    }
}
```

##### 1.5.3 Show
```kotlin
with(NotificationManagerCompat.from(this)) {
    // notificationId is a unique int for each notification that you must define
    notify(notificationId, builder.build())
}
```


#### [1.6 Understand how to localize an app](https://developer.android.com/guide/topics/resources/localization)

#### [1.7 Be able to schedule a background task using WorkManager](https://developer.android.com/topic/libraries/architecture/workmanager/basics)

##### [1.7.1 CodeLab](https://developer.android.com/codelabs/android-workmanager?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-basics-kotlin-unit-6-pathway-1%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fandroid-workmanager#11)

##### 1.7.2 Worker
```kotlin
class UploadWorker(appContext: Context, workerParams: WorkerParameters):
       Worker(appContext, workerParams) {
   override fun doWork(): Result {

       // Do the work here--in this case, upload the images.
       uploadImages()

       // Indicate whether the work finished successfully with the Result
       return Result.success()
   }
}
```

##### 1.7.3 Work Request
```kotlin
val uploadWorkRequest: WorkRequest =
   OneTimeWorkRequestBuilder<UploadWorker>()
       .build()

```

##### 1.7.4 Work Manager
```kotlin
WorkManager
    .getInstance(myContext)
    .enqueue(uploadWorkRequest)

```

### 2. User interface:

#### 2.1 Understand the Android activity lifecycle

##### [2.1.1 Activity lifecycle](https://developer.android.com/guide/components/activities/activity-lifecycle)

![activity](https://developer.android.com/guide/components/images/activity_lifecycle.png)

##### [2.1.2 Fragment lifecycle](https://developer.android.com/guide/fragments/lifecycle)

![fragment2](https://developer.android.com/static/images/guide/fragments/fragment-view-lifecycle.png)
![fragment1](https://developer.android.com/images/fragment_lifecycle.png)

#### 2.2 Be able to create an Activity that displays a Layout

#### [2.3 Be able to construct a UI with ConstraintLayout](https://developer.android.com/training/constraint-layout/)

#### [2.4 Understand how to create a custom View class and add it to a Layout](https://developer.android.com/guide/topics/ui/custom-components)

[codelab](https://developer.android.com/codelabs/advanced-android-kotlin-training-custom-views#3)

#### [2.5 Know how to implement a custom app theme](https://developer.android.com/develop/ui/views/theming/themes)

[codelab](https://developer.android.com/codelabs/basic-android-kotlin-training-change-app-theme#2)

#### [2.6 Be able to add accessibility hooks to a custom View](https://developer.android.com/guide/topics/ui/accessibility/custom-views)

```kotlin
override fun onKeyUp(keyCode: Int, event: KeyEvent): Boolean {
    return when(keyCode) {
        KeyEvent.KEYCODE_DPAD_LEFT -> {
            currentValue--
            sendAccessibilityEvent(AccessibilityEvent.TYPE_VIEW_TEXT_CHANGED)
            true
        }
        ...
    }
}
```

#### [2.7 Know how to apply content descriptions to views for accessibility](https://developer.android.com/guide/topics/ui/accessibility/apps)

#### [2.8 Understand how to display items in a RecyclerView](https://developer.android.com/guide/topics/ui/layout/recyclerview)
[codelab](https://developer.android.com/courses/pathways/android-basics-kotlin-unit-2-pathway-3#codelab-https://developer.android.com/codelabs/basic-android-kotlin-training-recyclerview-scrollable-list)

adapter
```kotlin
class ItemAdapter(
    private val context: Context,
    private val dataset: List<Affirmation>
) : RecyclerView.Adapter<ItemAdapter.ItemViewHolder>() {

    // Provide a reference to the views for each data item
    // Complex data items may need more than one view per item, and
    // you provide access to all the views for a data item in a view holder.
    // Each data item is just an Affirmation object.
    class ItemViewHolder(private val view: View) : RecyclerView.ViewHolder(view) {
        val textView: TextView = view.findViewById(R.id.item_title)
    }

    /**
     * Create new views (invoked by the layout manager)
     */
    override fun onCreateViewHolder(parent: ViewGroup, viewType: Int): ItemViewHolder {
        // create a new view
        val adapterLayout = LayoutInflater.from(parent.context)
            .inflate(R.layout.list_item, parent, false)

        return ItemViewHolder(adapterLayout)
    }

    /**
     * Replace the contents of a view (invoked by the layout manager)
     */
    override fun onBindViewHolder(holder: ItemViewHolder, position: Int) {
        val item = dataset[position]
        holder.textView.text = context.resources.getString(item.stringResourceId)
    }

    /**
     * Return the size of your dataset (invoked by the layout manager)
     */
    override fun getItemCount() = dataset.size
}
```

activity
```kotlin
class MainActivity : AppCompatActivity() {

    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main)

        // Initialize data.
        val myDataset = Datasource().loadAffirmations()

        val recyclerView = findViewById<RecyclerView>(R.id.recycler_view)
        recyclerView.adapter = ItemAdapter(this, myDataset)

        // Use this setting to improve performance if you know that changes
        // in content do not change the layout size of the RecyclerView
        recyclerView.setHasFixedSize(true)
    }
}
```

#### 2.9 Be able to bind local data to a RecyclerView list using the Paging library
[codelab](https://developer.android.com/codelabs/android-paging?index=..%2F..%2Findex#3)
[paging3](https://developer.android.com/topic/libraries/architecture/paging/v3-overview)
[paging2](https://developer.android.com/topic/libraries/architecture/paging)

#### [2.10 Know how to implement menu-based navigation](https://developer.android.com/guide/topics/ui/menus)

menu layout
```xml
<?xml version="1.0" encoding="utf-8"?>
<menu xmlns:android="http://schemas.android.com/apk/res/android">
    <item android:id="@+id/file"
          android:title="@string/file" >
        <!-- "file" submenu -->
        <menu>
            <item android:id="@+id/create_new"
                  android:title="@string/create_new" />
            <item android:id="@+id/open"
                  android:title="@string/open" />
        </menu>
    </item>
</menu>
```

create option menu
```kotlin
override fun onCreateOptionsMenu(menu: Menu): Boolean {
    val inflater: MenuInflater = menuInflater
    inflater.inflate(R.menu.game_menu, menu)
    return true
}
```

handling click events
```kotlin
override fun onOptionsItemSelected(item: MenuItem): Boolean {
    // Handle item selection
    return when (item.itemId) {
        R.id.new_game -> {
            newGame()
            true
        }
        R.id.help -> {
            showHelp()
            true
        }
        else -> super.onOptionsItemSelected(item)
    }
}
```

#### [2.11 Understand how to implement drawer navigation](https://developer.android.com/training/implementing-navigation/nav-drawer)
```
dependencies {
  implementation 'com.android.support:appcompat-v7:28.0.0'
  implementation 'com.android.support:design:28.0.0'
}
```

layout
```xml
<?xml version="1.0" encoding="utf-8"?>
<!-- Use DrawerLayout as root container for activity -->
<android.support.v4.widget.DrawerLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:id="@+id/drawer_layout"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:fitsSystemWindows="true">

    <!-- Layout to contain contents of main body of screen (drawer will slide over this) -->
    <FrameLayout
        android:id="@+id/content_frame"
        android:layout_width="match_parent"
        android:layout_height="match_parent" />

    <!-- Container for contents of drawer - use NavigationView to make configuration easier -->
    <android.support.design.widget.NavigationView
        android:id="@+id/nav_view"
        android:layout_width="wrap_content"
        android:layout_height="match_parent"
        android:layout_gravity="start"
        android:fitsSystemWindows="true"
        app:menu="@menu/drawer_view"
        app:headerLayout="@layout/nav_header" />

</android.support.v4.widget.DrawerLayout>
```

menu
```xml
<?xml version="1.0" encoding="utf-8"?>
<menu xmlns:android="http://schemas.android.com/apk/res/android" >
    <group android:checkableBehavior="single">
        <item
            android:id="@+id/nav_camera"
            android:icon="@drawable/ic_menu_camera"
            android:title="@string/import" />
        <item
            android:id="@+id/nav_gallery"
            android:icon="@drawable/ic_menu_gallery"
            android:title="@string/gallery" />
        <item
            android:id="@+id/nav_slideshow"
            android:icon="@drawable/ic_menu_slideshow"
            android:title="@string/slideshow" />
        <item
            android:id="@+id/nav_manage"
            android:icon="@drawable/ic_menu_manage"
            android:title="@string/tools" />
    </group>
</menu>
```

headerlayout
```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="192dp"
    android:background="?attr/colorPrimaryDark"
    android:padding="16dp"
    android:theme="@style/ThemeOverlay.AppCompat.Dark"
    android:orientation="vertical"
    android:gravity="bottom">

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="My header title"
        android:textAppearance="@style/TextAppearance.AppCompat.Body1"/>

</LinearLayout>
```

activity
```kotlin
override fun onCreate(savedInstanceState: Bundle?) {
    setContentView(R.layout.activity_main)

    ...

    val navHostFragment =
        supportFragmentManager.findFragmentById(R.id.nav_host_fragment) as NavHostFragment
    val navController = navHostFragment.navController
    findViewById<NavigationView>(R.id.nav_view)
        .setupWithNavController(navController)
}
```

### 3. Data Management:

[AppArchitecture](https://developer.android.com/jetpack/docs/guide)

![](https://developer.android.com/topic/libraries/architecture/images/final-architecture.png)

#### 3.1 Understand how to define data using Room entities

```java
@Entity(tableName = "word_table")
public class Word {

   @PrimaryKey
   @NonNull
   @ColumnInfo(name = "word")
   private String mWord;

   public Word(@NonNull String word) {this.mWord = word;}

   public String getWord(){return this.mWord;}
}
```

#### 3.2 Be able to access Room database with data access object (DAO)

Database:
```java
@Database(entities = {Word.class}, version = 1, exportSchema = false)
public abstract class WordRoomDatabase extends RoomDatabase {

   public abstract WordDao wordDao();
   private static WordRoomDatabase INSTANCE;

   static WordRoomDatabase getDatabase(final Context context) {
       if (INSTANCE == null) {
           synchronized (WordRoomDatabase.class) {
               if (INSTANCE == null) {
                   INSTANCE = Room.databaseBuilder(context.getApplicationContext(),
                           WordRoomDatabase.class, "word_database")
                             // Wipes and rebuilds instead of migrating
                             // if no Migration object.
                            // Migration is not part of this practical.
                           .fallbackToDestructiveMigration()
                           .build();                
               }
           }
       }
       return INSTANCE;
   }
}
```

Dao:
```java
@Dao
public interface WordDao {

   @Insert
   void insert(Word word);

   @Query("DELETE FROM word_table")
   void deleteAll();

   @Query("SELECT * from word_table ORDER BY word ASC")
   List<Word> getAllWords();
}
```

#### [3.3 Know how to observe and respond to changing data using LiveData](https://developer.android.com/topic/libraries/architecture/livedata)

#### 3.4 Understand how to use a Repository to mediate data operations

```java
public class WordRepository {

   private WordDao mWordDao;
   private LiveData<List<Word>> mAllWords;

   WordRepository(Application application) {
       WordRoomDatabase db = WordRoomDatabase.getDatabase(application);
       mWordDao = db.wordDao();
       mAllWords = mWordDao.getAllWords();
   }

   LiveData<List<Word>> getAllWords() {
       return mAllWords;
   }

   public void insert (Word word) {
       new insertAsyncTask(mWordDao).execute(word);
   }

   private static class insertAsyncTask extends AsyncTask<Word, Void, Void> {

       private WordDao mAsyncTaskDao;

       insertAsyncTask(WordDao dao) {
           mAsyncTaskDao = dao;
       }

       @Override
       protected Void doInBackground(final Word... params) {
           mAsyncTaskDao.insert(params[0]);
           return null;
       }
   }
}
```

#### [3.5 Be able to read and parse raw resources or asset files](https://www.google.com)

#### 3.6 Be able to create persistent Preference data from user input

```java
public class MainActivity extends AppCompatActivity {
  // Key for current count
    private final String COUNT_KEY = "count";
    // Key for current color
    private final String COLOR_KEY = "color";
    // Shared preferences object
    private SharedPreferences mPreferences;

    // Name of shared preferences file
    private String sharedPrefFile =
            "com.example.android.hellosharedprefs";
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        mPreferences = getSharedPreferences(sharedPrefFile, MODE_PRIVATE);
        // Restore preferences
        mCount = mPreferences.getInt(COUNT_KEY, 0);
        mShowCountTextView.setText(String.format("%s", mCount));
        mColor = mPreferences.getInt(COLOR_KEY, mColor);
        mShowCountTextView.setBackgroundColor(mColor);
    }

    public void reset(View view) {
        // Clear preferences
        SharedPreferences.Editor preferencesEditor = mPreferences.edit();
        preferencesEditor.clear();
        preferencesEditor.apply();
    }

    /**
     * Callback for activity pause.  Shared preferences are saved here.
     */
    @Override
    protected void onPause() {
        super.onPause();

        SharedPreferences.Editor preferencesEditor = mPreferences.edit();
        preferencesEditor.putInt(COUNT_KEY, mCount);
        preferencesEditor.putInt(COLOR_KEY, mColor);
        preferencesEditor.apply();
    }
}
```

#### 3.7 Understand how to change the behavior of the app based on user preferences

AppSettings:

styles.xml

```xml
<item name="preferenceTheme">@style/PreferenceThemeOverlay</item>
```

preference.xml:
```xml
<PreferenceScreen xmlns:android="http://schemas.android.com/apk/res/android">

    <!-- NOTE: Hide buttons to simplify the UI. Users can touch outside the
    dialog to dismiss it. -->
    <android.support.v7.preference.SwitchPreferenceCompat
        android:defaultValue="true"
        android:key="example_switch"
        android:summary="@string/switch_summary"
        android:title="@string/switch_title" />
    <!-- NOTE: ListPreference's summary should be set to its value by the
    activity code. -->
    <ListPreference
        android:defaultValue="US"
        android:entries="@array/pref_market_titles"
        android:entryValues="@array/pref_market_values"
        android:key="sync_frequency"
        android:negativeButtonText="@null"
        android:positiveButtonText="@null"
        android:title="@string/pref_title_account" />

    <!-- This preference simply launches an intent when selected. Use this UI
    sparingly, per design guidelines. -->
    <Preference android:title="@string/pref_title_account_settings">
        <intent android:action="android.settings.SYNC_SETTINGS" />
    </Preference>

</PreferenceScreen>
```
View:
```java
public class SettingFragment extends PreferenceFragmentCompat {
    public SettingFragment() {
    }

    @Override
    public void onCreatePreferences(Bundle savedInstanceState, String rootKey) {
            setPreferencesFromResource(R.xml.setting_preference,rootKey);
    }
}

```

getPreference:

```java
public static final String
            KEY_PREF_EXAMPLE_SWITCH = "example_switch";
SharedPreferences sharedPref =   
           android.support.v7.preference.PreferenceManager
                      .getDefaultSharedPreferences(this);
Boolean switchPref = sharedPref.getBoolean
           (SettingsActivity.KEY_PREF_EXAMPLE_SWITCH, false);
```

### 4. Debugging:

#### 4.1 Understand the basic debugging techniques available in Android Studio
#### 4.2 Know how to debug and fix issues with an apps functional behavior and usability
#### 4.3 Be able to use the System Log to output debug information
#### 4.4 Understand how to use breakpoints in Android Studio
#### 4.5 Know how to inspect variables using Android Studio

### [5. Testing](https://developer.android.com/training/testing/fundamentals)：

![](https://developer.android.com/images/training/testing/testing-workflow.png)

![](https://developer.android.com/images/training/testing/pyramid_2x.png)


#### 5.1 Thoroughly understand the fundamentals of testing

#### 5.2 Be able to write useful local JUnit tests

CheatSheet: https://www.roguewave.com/sites/rw/files/resources/junit-cheat-sheet_0.pdf

mockito: https://www.jianshu.com/p/a3b59fad17e6

* [Basic](https://github.com/googlesamples/android-testing/tree/master/unit/BasicSample/app/src/test/java/com/example/android/testing/unittesting/BasicSample)

* [Service](https://github.com/googlesamples/android-testing/blob/master/integration/ServiceTestRuleSample/app/src/androidTest/java/com/example/android/testing/ServiceTestRuleSample/LocalServiceTest.java)

#### [5.3 Understand the Espresso UI test framework](https://developer.android.com/training/testing/espresso):

![](https://developer.android.com/images/training/testing/espresso-cheatsheet.png)

Gradle:
```
apply plugin: 'com.android.application'

android {
    compileSdkVersion 28

    defaultConfig {
        applicationId "com.my.awesome.app"
        minSdkVersion 15
        targetSdkVersion 28
        versionCode 1
        versionName "1.0"

        testInstrumentationRunner "androidx.test.runner.AndroidJUnitRunner"
    }
}

dependencies {
    androidTestImplementation 'androidx.test:runner:1.1.0
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.1.0'
}
```

* [Basic Test](https://github.com/googlesamples/android-testing/blob/master/ui/espresso/BasicSample/app/src/androidTest/java/com/example/android/testing/espresso/BasicSample/ChangeTextBehaviorTest.java)

* [Custom matcher](https://github.com/googlesamples/android-testing/tree/master/ui/espresso/CustomMatcherSample/app/src/androidTest/java/com/example/android/testing/espresso/CustomMatcherSample)

* [Data Adapter](https://github.com/googlesamples/android-testing/blob/master/ui/espresso/DataAdapterSample/app/src/androidTest/java/com/example/android/testing/espresso/DataAdapterSample/LongListActivityTest.java)

* [Idleing Resource](https://github.com/googlesamples/android-testing/tree/master/ui/espresso/IdlingResourceSample/app/src)

* [Intents Basic](https://github.com/googlesamples/android-testing/blob/master/ui/espresso/IntentsBasicSample/app/src/androidTest/java/com/example/android/testing/espresso/BasicSample/DialerActivityTest.java)

* [Intents Advance](https://github.com/googlesamples/android-testing/tree/master/ui/espresso/IntentsAdvancedSample/app/src/androidTest/java/com/example/android/testing/espresso/intents/AdvancedSample)

* [Multi Process](https://github.com/googlesamples/android-testing/blob/master/ui/espresso/MultiProcessSample/app/src/androidTest/java/com/example/android/testing/espresso/multiprocesssample/ExampleInstrumentedTest.java)

* [Multi Window](https://github.com/googlesamples/android-testing/blob/master/ui/espresso/MultiWindowSample/app/src/androidTest/java/com/example/android/testing/espresso/MultiWindowSample/MultiWindowTest.java)

* [RecyclerView](https://github.com/googlesamples/android-testing/blob/master/ui/espresso/RecyclerViewSample/app/src/androidTest/java/com/example/android/testing/espresso/RecyclerViewSample/RecyclerViewSampleTest.java)

* [Web Basic](https://github.com/googlesamples/android-testing/blob/master/ui/espresso/WebBasicSample/app/src/androidTest/java/com/example/android/testing/espresso/web/BasicSample/WebViewActivityTest.java)

#### 5.4 Know how to write useful automated Android tests

https://github.com/googlesamples/android-testing/tree/master/ui/uiautomator/BasicSample

