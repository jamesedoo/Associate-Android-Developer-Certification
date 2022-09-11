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
example exist in work manager codelab, also in [watermeapp](https://github.com/jamesedoo/Associate-Android-Developer-Certification/tree/main/WaterMe/src/main/java/com/example/waterme)

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
codelab -> dicoding intermediate custom view

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
```xml
<!-- Use string resources for easier localization. -->
<!-- The en-US value for the following string is "Inspect". -->
<ImageView
    ...
    android:contentDescription="@string/inspect" />
```
```kotlin
data class MovieRating(val title: String, val starRating: Integer)

class MyMovieRatingsAdapter(private val myData: Array<MovieRating>):
        RecyclerView.Adapter<MyMovieRatingsAdapter.MyRatingViewHolder>() {

    class MyRatingViewHolder(val ratingView: ImageView) :
            RecyclerView.ViewHolder(ratingView)

    override fun onBindViewHolder(holder: MyRatingViewHolder, position: Int) {
        val ratingData = myData[position]
        holder.ratingView.contentDescription = "Movie ${position}: " +
                "${ratingData.title}, ${ratingData.starRating} stars"
    }
}
```

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

#### [2.9 Be able to bind local data to a RecyclerView list using the Paging library](https://developer.android.com/topic/libraries/architecture/paging)
codelab -> dicoding intermediate paging 2
```kotlin
@Dao
interface ConcertDao {
    // The Int type parameter tells Room to use a PositionalDataSource
    // object, with position-based loading under the hood.
    @Query("SELECT * FROM concerts ORDER BY date DESC")
    fun concertsByDate(): DataSource.Factory<Int, Concert>
}

class ConcertViewModel(concertDao: ConcertDao) : ViewModel() {
    val concertList: LiveData<PagedList<Concert>> =
            concertDao.concertsByDate().toLiveData(pageSize = 50)
}

class ConcertActivity : AppCompatActivity() {
    public override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        // Use the 'by viewModels()' Kotlin property delegate
        // from the activity-ktx artifact
        val viewModel: ConcertViewModel by viewModels()
        val recyclerView = findViewById(R.id.concert_list)
        val adapter = ConcertAdapter()
        viewModel.concertList.observe(this, PagedList(adapter::submitList))
        recyclerView.setAdapter(adapter)
    }
}

class ConcertAdapter() :
        PagedListAdapter<Concert, ConcertViewHolder>(DIFF_CALLBACK) {
    fun onBindViewHolder(holder: ConcertViewHolder, position: Int) {
        val concert: Concert? = getItem(position)

        // Note that "concert" is a placeholder if it's null.
        holder.bindTo(concert)
    }

    companion object {
        private val DIFF_CALLBACK = object :
                DiffUtil.ItemCallback<Concert>() {
            // Concert details may have changed if reloaded from the database,
            // but ID is fixed.
            override fun areItemsTheSame(oldConcert: Concert,
                    newConcert: Concert) = oldConcert.id == newConcert.id

            override fun areContentsTheSame(oldConcert: Concert,
                    newConcert: Concert) = oldConcert == newConcert
        }
    }
}
```

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
nav graph based

[example](https://medium.com/@syahrizalakbar1/membuat-navigation-drawer-di-kotlin-b3869c1cbfb9) intent based
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
or 
```kotlin
override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)

        binding = ActivityMainBinding.inflate(layoutInflater)
        setContentView(binding.root)

        setSupportActionBar(binding.appBarMain.toolbar)

        binding.appBarMain.fab.setOnClickListener { view ->
            Snackbar.make(view, "Replace with your own action", Snackbar.LENGTH_LONG)
                .setAction("Action", null).show()
        }
        val drawerLayout: DrawerLayout = binding.drawerLayout
        val navView: NavigationView = binding.navView
        val navController = findNavController(R.id.nav_host_fragment_content_main)
        // Passing each menu ID as a set of Ids because each
        // menu should be considered as top level destinations.
        appBarConfiguration = AppBarConfiguration(
            setOf(
                R.id.nav_home, R.id.nav_gallery, R.id.nav_slideshow
            ), drawerLayout
        )
        setupActionBarWithNavController(navController, appBarConfiguration)
        navView.setupWithNavController(navController)
    }
```

### [3. Data Management:](https://developer.android.com/jetpack/docs/guide)
![](https://developer.android.com/topic/libraries/architecture/images/final-architecture.png)

#### 3.1 Understand how to define data using Room entities
```kotlin
@Entity
data class User(
    @PrimaryKey val uid: Int,
    @ColumnInfo(name = "first_name") val firstName: String?,
    @ColumnInfo(name = "last_name") val lastName: String?
)
```

#### 3.2 Be able to access Room database with data access object (DAO)

database
```kotlin
@Database(entities = [Item::class], version = 1, exportSchema = false)
abstract class ItemRoomDatabase : RoomDatabase() {

   abstract fun itemDao(): ItemDao

   companion object {
       @Volatile
       private var INSTANCE: ItemRoomDatabase? = null
       fun getDatabase(context: Context): ItemRoomDatabase {
           return INSTANCE ?: synchronized(this) {
               val instance = Room.databaseBuilder(
                   context.applicationContext,
                   ItemRoomDatabase::class.java,
                   "item_database"
               )
                   .fallbackToDestructiveMigration()
                   .build()
               INSTANCE = instance
               return instance
           }
       }
   }
}
```

dao
```kotlin
@Dao
interface UserDao {
    @Query("SELECT * FROM user")
    fun getAll(): List<User>

    @Query("SELECT * FROM user WHERE uid IN (:userIds)")
    fun loadAllByIds(userIds: IntArray): List<User>

    @Query("SELECT * FROM user WHERE first_name LIKE :first AND " +
           "last_name LIKE :last LIMIT 1")
    fun findByName(first: String, last: String): User

    @Insert
    fun insertAll(vararg users: User)

    @Delete
    fun delete(user: User)
}
```

#### [3.3 Know how to observe and respond to changing data using LiveData](https://developer.android.com/topic/libraries/architecture/livedata)
[codelab](https://developer.android.com/courses/pathways/android-basics-kotlin-unit-5-pathway-2#codelab-https://developer.android.com/codelabs/basic-android-kotlin-training-persisting-data-room)

#### 3.4 Understand how to use a Repository to mediate data operations
[codelab](https://developer.android.com/codelabs/basic-android-kotlin-training-repository-pattern?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-basics-kotlin-unit-5-pathway-2%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fbasic-android-kotlin-training-repository-pattern#4)

#### 3.5 Be able to read and parse raw resources or asset files
?

#### [3.6 Be able to create persistent Preference data from user input](https://developer.android.com/training/data-storage/shared-preferences)
[codelab](https://developer.android.com/codelabs/basic-android-kotlin-training-preferences-datastore?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-basics-kotlin-unit-5-pathway-2%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fbasic-android-kotlin-training-preferences-datastore#3)

#### [3.7 Understand how to change the behavior of the app based on user preferences]()
[codelab](https://developer.android.com/codelabs/basic-android-kotlin-training-preferences-datastore?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-basics-kotlin-unit-5-pathway-2%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fbasic-android-kotlin-training-preferences-datastore#5)


### 4. Debugging:

#### 4.1 Understand the basic debugging techniques available in Android Studio
#### 4.2 Know how to debug and fix issues with an apps functional behavior and usability
#### 4.3 Be able to use the System Log to output debug information
#### 4.4 Understand how to use breakpoints in Android Studio
#### 4.5 Know how to inspect variables using Android Studio

### [5. Testing](https://developer.android.com/training/testing/fundamentals)：

![](https://developer.android.com/static/training/testing/fundamentals/test-scopes.png)
![](https://developer.android.com/static/training/testing/fundamentals/instru-vs-local.png)
![](https://developer.android.com/images/training/testing/pyramid_2x.png)

#### [5.1 Thoroughly understand the fundamentals of testing](https://developer.android.com/codelabs/advanced-android-kotlin-training-testing-basics#0)
#### 5.2 Be able to write useful local JUnit tests
#### [5.3 Understand the Espresso UI test framework](https://developer.android.com/training/testing/espresso):
![](https://developer.android.com/images/training/testing/espresso-cheatsheet.png)
#### 5.4 Know how to write useful automated Android tests

#### Example:
- [lemonadeapp test](https://github.com/jamesedoo/Associate-Android-Developer-Certification/tree/main/LemonadeApp/src/androidTest/java/com/example/lemonade)
matching view and perform click
- [waterme test](https://github.com/jamesedoo/Associate-Android-Developer-Certification/tree/main/WaterMe/src/main/java/com/example/waterme)
activityRule, notification test, ui device test(press home, open notif, etc.), click notif
- instrumentation test
```kotlin
@RunWith(AndroidJUnit4::class)
class CalculatorTests {

   @get:Rule()
   val activity = ActivityScenarioRule(MainActivity::class.java)

   @Test
   fun calculate_20_percent_tip() {
       onView(withId(R.id.cost_of_service_edit_text))
           .perform(typeText("50.00"))

       onView(withId(R.id.calculate_button)).perform(click())

       onView(withId(R.id.tip_result))
           .check(matches(withText(containsString("$10.00"))))
   }
}
```
- [dogglers test](https://github.com/jamesedoo/Associate-Android-Developer-Certification/tree/main/DogglersApp/src/androidTest/java/com/example/dogglers)
recyclerview item match test, scroll to position, swipe up/left, item count
- adapter mock
![](https://developer.android.com/static/codelabs/android-basics-kotlin-affirmations-test-lists-and-adapters/img/f81a27f5c1cf055e.png)
- viewmodel test
```kotlin
class ViewModelTests {
    @get:Rule
    var instantTaskExecutorRule = InstantTaskExecutorRule()

    @Test
    fun quantity_twelve_cupcakes() {
        val viewModel = OrderViewModel()
        viewModel.quantity.observeForever {}
        viewModel.setQuantity(12)
        assertEquals(12, viewModel.quantity.value)
    }

    @Test
    fun price_twelve_cupcakes() {
        val viewModel = OrderViewModel()
        viewModel.price.observeForever {}
        viewModel.setQuantity(12)
        assertEquals("IDR27.00", viewModel.price.value)
    }
}
```
- [lunchtray test](https://github.com/jamesedoo/Associate-Android-Developer-Certification/tree/main/LunchTray/src/androidTest/java/com/example/lunchtray)
navHost, menu content, order flow(entree, side, accompaniment), snackbar test

- [amphibians test](https://github.com/jamesedoo/Associate-Android-Developer-Certification/tree/main/Amphibians/src/androidTest/java/com/example/amphibians)
waitforview

- [forage test](https://github.com/jamesedoo/Associate-Android-Developer-Certification/tree/main/ForageApp/src/androidTest/java/com/example/forage)
replaceText, doesnotexist
