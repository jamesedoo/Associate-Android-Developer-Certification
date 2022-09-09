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
	- [3.7 Understand how to change the behavior of the app based on user preferences](#37understand-how-to-change-the-behavior-of-the-app-based-on-user-preferences)
- [4. Debugging:](4-#debugging)
- [5. Testing：](#5-testing)
	- [5.1 Espresso:](#51-espresso)
	- [5.2 UI Automator:](#52-ui-automator)
	- [5.3 JUnit:](#53-junit)
		
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

#### [2.1 Understand the Android activity lifecycle](https://developer.android.com/guide/components/activities/activity-lifecycle)

##### 2.1.1 Activity lifecycle

![lifecycle](https://developer.android.com/guide/components/images/activity_lifecycle.png)

##### 2.1.2 Fragment lifecycle

![](https://developer.android.com/images/fragment_lifecycle.png)

#### 2.2 Be able to create an Activity that displays a Layout

#### [2.3 Be able to construct a UI with ConstraintLayout](https://developer.android.com/training/constraint-layout/)

#### [2.4 Understand how to create a custom View class and add it to a Layout](https://developer.android.com/guide/topics/ui/custom-components)

[CodeLab](https://codelabs.developers.google.com/codelabs/advanced-android-training-custom-view-from-scratch/index.html)

```java
public class DialView extends View {

    private static int SELECTION_COUNT = 4; // Total number of selections.
    private float mWidth;                   // Custom view width.
    private float mHeight;                  // Custom view height.
    private Paint mTextPaint;               // For text in the view.
    private Paint mDialPaint;               // For dial circle in the view.
    private float mRadius;                  // Radius of the circle.
    private int mActiveSelection;           // The active selection.
    // String buffer for dial labels and float for ComputeXY result.
    private final StringBuffer mTempLabel = new StringBuffer(8);
    private final float[] mTempResult = new float[2];
    public DialView(Context context) {
        super(context);
        init();
    }

    public DialView(Context context,  @Nullable AttributeSet attrs) {
        super(context, attrs);
        init();
    }

    public DialView(Context context,  @Nullable AttributeSet attrs, int defStyleAttr) {
        super(context, attrs, defStyleAttr);
        init();
    }

    @Override
    protected void onDraw(Canvas canvas) {
        super.onDraw(canvas);
        // Draw the dial.
        canvas.drawCircle(mWidth / 2, mHeight / 2, mRadius, mDialPaint);
        // Draw the text labels.
        final float labelRadius = mRadius + 20;
        StringBuffer label = mTempLabel;
        for (int i = 0; i < SELECTION_COUNT; i++) {
            float[] xyData = computeXYForPosition(i, labelRadius);
            float x = xyData[0];
            float y = xyData[1];
            label.setLength(0);
            label.append(i);
            canvas.drawText(label, 0, label.length(), x, y, mTextPaint);
        }
        // Draw the indicator mark.
        final float markerRadius = mRadius - 35;
        float[] xyData = computeXYForPosition(mActiveSelection,
                markerRadius);
        float x = xyData[0];
        float y = xyData[1];
        canvas.drawCircle(x, y, 20, mTextPaint);
    }

    @Override
    protected void onSizeChanged(int w, int h, int oldw, int oldh) {
        // Calculate the radius from the width and height.
        mWidth = w;
        mHeight = h;
        mRadius = (float) (Math.min(mWidth, mHeight) / 2 * 0.8);
    }
}
```

Custom Attribute:

attrs.xml
```xml

<resources>
    <declare-styleable name="DialView">
        <attr name="fanOnColor" format="reference|color" />
        <attr name="fanOffColor" format="reference|color" />
    </declare-styleable>
</resources>
```
get Attributes
```java
// Get the custom attributes (fanOnColor and fanOffColor) if available.
if (attrs! = null) {
    TypedArray typedArray = getContext().obtainStyledAttributes(attrs,
                            R.styleable.DialView,
                            0, 0);
    // Set the fan on and fan off colors from the attribute values.
    mFanOnColor = typedArray.getColor(R.styleable.DialView_fanOnColor,
                    mFanOnColor);
    mFanOffColor = typedArray.getColor(R.styleable.DialView_fanOffColor,
                    mFanOffColor);
    typedArray.recycle();
```




#### [2.5 Know how to implement a custom app theme](https://developer.android.com/guide/topics/ui/look-and-feel/themes)



[CodeLab](https://codelabs.developers.google.com/codelabs/android-training-drawables-styles-and-themes/index.html)

#### [2.6 Be able to add accessibility hooks to a custom View](https://developer.android.com/guide/topics/ui/accessibility/custom-views)

```java
@Override
public boolean onKeyUp (int keyCode, KeyEvent event) {
    if (keyCode == KeyEvent.KEYCODE_DPAD_LEFT) {
        currentValue--;
        sendAccessibilityEvent(AccessibilityEvent.TYPE_VIEW_TEXT_CHANGED);
        return true;
    }
    ...
}

```

#### 2.7 Know how to apply content descriptions to views for accessibility

关爱残障人士从我做起

#### [2.8 Understand how to display items in a RecyclerView](https://developer.android.com/guide/topics/ui/layout/recyclerview)

Activity:

```java
public class MyActivity extends Activity {
    private RecyclerView recyclerView;
    private RecyclerView.Adapter mAdapter;
    private RecyclerView.LayoutManager layoutManager;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.my_activity);
        recyclerView = (RecyclerView) findViewById(R.id.my_recycler_view);

        // use this setting to improve performance if you know that changes
        // in content do not change the layout size of the RecyclerView
        recyclerView.setHasFixedSize(true);

        // use a linear layout manager
        layoutManager = new LinearLayoutManager(this);
        recyclerView.setLayoutManager(layoutManager);

        // specify an adapter (see also next example)
        mAdapter = new MyAdapter(myDataset);
        recyclerView.setAdapter(mAdapter);
    }
    // ...
}
```

Adapter.java:

```java

public class MyAdapter extends RecyclerView.Adapter<MyAdapter.MyViewHolder> {
    private String[] mDataset;

    // Provide a reference to the views for each data item
    // Complex data items may need more than one view per item, and
    // you provide access to all the views for a data item in a view holder
    public static class MyViewHolder extends RecyclerView.ViewHolder {
        // each data item is just a string in this case
        public TextView textView;
        public MyViewHolder(TextView v) {
            super(v);
            textView = v;
        }
    }

    // Provide a suitable constructor (depends on the kind of dataset)
    public MyAdapter(String[] myDataset) {
        mDataset = myDataset;
    }

    // Create new views (invoked by the layout manager)
    @Override
    public MyAdapter.MyViewHolder onCreateViewHolder(ViewGroup parent,
                                                   int viewType) {
        // create a new view
        TextView v = (TextView) LayoutInflater.from(parent.getContext())
                .inflate(R.layout.my_text_view, parent, false);
        ...
        MyViewHolder vh = new MyViewHolder(v);
        return vh;
    }

    // Replace the contents of a view (invoked by the layout manager)
    @Override
    public void onBindViewHolder(MyViewHolder holder, int position) {
        // - get element from your dataset at this position
        // - replace the contents of the view with that element
        holder.textView.setText(mDataset[position]);

    }

    // Return the size of your dataset (invoked by the layout manager)
    @Override
    public int getItemCount() {
        return mDataset.length;
    }
}

```




#### 2.9 Be able to bind local data to a RecyclerView list using the Paging library

![](https://codelabs.developers.google.com/codelabs/android-paging/img/511a702ae4af43cd.png)

```java
@Dao
public interface ConcertDao {
    // The Integer type parameter tells Room to use a PositionalDataSource
    // object, with position-based loading under the hood.
    @Query("SELECT * FROM concerts ORDER BY date DESC")
    DataSource.Factory<Integer, Concert> concertsByDate();
}

public class ConcertViewModel extends ViewModel {
    private ConcertDao concertDao;
    public final LiveData<PagedList<Concert>> concertList;

    public ConcertViewModel(ConcertDao concertDao) {
        this.concertDao = concertDao;
        concertList = new LivePagedListBuilder<>(
            concertDao.concertsByDate(), /* page size */ 50).build();
    }
}

public class ConcertActivity extends AppCompatActivity {
    @Override
    public void onCreate(@Nullable Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        ConcertViewModel viewModel =
                ViewModelProviders.of(this).get(ConcertViewModel.class);
        RecyclerView recyclerView = findViewById(R.id.concert_list);
        ConcertAdapter adapter = new ConcertAdapter();
        viewModel.concertList.observe(this, 
 new Observer<PagedList<FavSong>>() {
            @Override
            public void onChanged(PagedList<FavSong> favSongs) {

                    adapter.submitList(favSongs);

            }
        });
        recyclerView.setAdapter(adapter);
    }
}

public class ConcertAdapter
        extends PagedListAdapter<Concert, ConcertViewHolder> {
    protected ConcertAdapter() {
        super(DIFF_CALLBACK);
    }

    @Override
    public void onBindViewHolder(@NonNull ConcertViewHolder holder,
            int position) {
        Concert concert = getItem(position);
        if (concert != null) {
            holder.bindTo(concert);
        } else {
            // Null defines a placeholder item - PagedListAdapter automatically
            // invalidates this row when the actual object is loaded from the
            // database.
            holder.clear();
        }
    }

    private static DiffUtil.ItemCallback<Concert> DIFF_CALLBACK =
            new DiffUtil.ItemCallback<Concert>() {
        // Concert details may have changed if reloaded from the database,
        // but ID is fixed.
        @Override
        public boolean areItemsTheSame(Concert oldConcert, Concert newConcert) {
            return oldConcert.getId() == newConcert.getId();
        }

        @Override
        public boolean areContentsTheSame(Concert oldConcert,
                Concert newConcert) {
            return oldConcert.equals(newConcert);
        }
    };
}
```

If the source is from Network or other sources, you should create and inherent the Datasource.class and Datasource.Factory.class yoruself


#### [2.10 Know how to implement menu-based navigation](https://developer.android.com/guide/topics/ui/menus)

Menu item:
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

Activity:

```java
@Override
public boolean onCreateOptionsMenu(Menu menu) {
    MenuInflater inflater = getMenuInflater();
    inflater.inflate(R.menu.game_menu, menu);
    return true;
}

@Override
public boolean onOptionsItemSelected(MenuItem item) {
    // Handle item selection
    switch (item.getItemId()) {
        case R.id.new_game:
            newGame();
            return true;
        case R.id.help:
            showHelp();
            return true;
        default:
            return super.onOptionsItemSelected(item);
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

layout:

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

menu:

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

HeaderLayout：

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

Activity:

```java
public class MainActivity extends AppCompatActivity {

    private DrawerLayout drawerLayout;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        drawerLayout = findViewById(R.id.drawer_layout);

        NavigationView navigationView = findViewById(R.id.nav_view);
        navigationView.setNavigationItemSelectedListener(
                new NavigationView.OnNavigationItemSelectedListener() {
                    @Override
                    public boolean onNavigationItemSelected(MenuItem menuItem) {
                        // set item as selected to persist highlight
                        menuItem.setChecked(true);
                        // close drawer when item is tapped
                        drawerLayout.closeDrawers();

                        // Add code here to update the UI based on the item selected
                        // For example, swap UI fragments here

                        return true;
                    }
                });
    }
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

略

### [5. Testing](https://developer.android.com/training/testing/fundamentals)：

![](https://developer.android.com/images/training/testing/testing-workflow.png)

![](https://developer.android.com/images/training/testing/pyramid_2x.png)



#### [5.1 Espresso](https://developer.android.com/training/testing/espresso):

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

#### 5.2 UI Automator:

https://github.com/googlesamples/android-testing/tree/master/ui/uiautomator/BasicSample

#### 5.3 JUnit:

CheatSheet: https://www.roguewave.com/sites/rw/files/resources/junit-cheat-sheet_0.pdf

mockito: https://www.jianshu.com/p/a3b59fad17e6

* [Basic](https://github.com/googlesamples/android-testing/tree/master/unit/BasicSample/app/src/test/java/com/example/android/testing/unittesting/BasicSample)

* [Service](https://github.com/googlesamples/android-testing/blob/master/integration/ServiceTestRuleSample/app/src/androidTest/java/com/example/android/testing/ServiceTestRuleSample/LocalServiceTest.java)
