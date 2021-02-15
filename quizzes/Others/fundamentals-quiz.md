# Android Kotlin fundamentals quiz

#### Q1. You can create an emulator to simulate the configuration of a particular type of Android device using a tool like _____

- [ ] Theme Editor
- [ ] Android SDK Manager
- [x] AVD Manager
- [ ] Virtual Editor

Note: You can use the AVD manager to create a virtual device (an emulator). The virtual device simulates the configuration for a particular type of Android device. Then, you may use that virtual device to run the app.

#### Q2. Fill-in-the-blanks
*Enter one or more words to complete the sentence.*

A `click` `handler` is a method that is invoked each time the user clicks or taps on cickable UI element, such as a button. 

#### Q3. What parameter specifies the Android API level that Gradle should use to complie your app?

- [ ] minSdkVersion
- [x] compileSdkVersion
- [ ] targetSdkVersion
- [ ] testSdkVersion

Note: The parameter, compileSdkVersion, specifies the Android API level that Gradle should use to compile your app. This is the newest version of Android your app can support. That is, your app can use the API features included in this API level and lower.

#### Q4. True or false? Scroll view can contain only one view, or view group, as a child.

- [x] True 
- [ ] False

Note: Scroll view is a view group that allows the view hierarchy placed within it to be scrolled. Scroll view can contain only one other view, or view group, as a child. The child view is commonly a linear layout. Inside a linear layout, you can add other views.

#### Q5. You can show or hide a view in your app by setting its visibility. Which of the following are valid visibility values?
*Choose as many answers as you see fit.*

- [x] VISIBLE
- [x] GONE
- [ ] CLEAR
- [x] INVISIBLE
- [ ] NONE

#### Q6. Fill-in-the-blanks
*Enter one or more words to complete the sentence.*

A `chain` is a group of views that are linked together with bidirectional constraints. 

Note: A chain is a group of views that are linked to each other with bidirectional constraints. The views within a chain can be distributed either vertically or horizontally.

#### Q7. What phase means that the compiler validates types while compiling?

- [x] Type safety 
- [ ] Data binding
- [ ] Type validation
- [ ] Wrong text

Note: Type safety means that the compiler validates types while compiling and it throws an error if you try to assign the wrong type to a variable.

#### Q8. Which of the following is not true about fragments?

- [ ] A fragment has its own lifecycle and receives its own input events.
- [x] It is not possible to remove a fragment while the activity is running.
- [ ] A fragment is defined in a Kotlin class.
- [ ] A fragment's UI is defined in an XML layout file.

Note: Think of a fragment as a modular section of an activity, like a sub-activity that you can also use in other activities:A fragment has its own lifecycle and receives its own input events. You can add or remove a fragment while the activity is running. A fragment is defined in a Kotlin class. A fragment's UI is defined in an XML layout file.

#### Q9. Fill-in-the-blanks
*Enter one or more words to complete the sentence.*

The `action``bar` is a dedicated space for app branding and identity.

#### Q10. Fill-in-the-blanks
*Enter one or more words to complete the sentence.*

The `Safe``Args` plugin of the Navigation component makes passing parameters between fragments safer. 

#### Q11. Which of the following are methods in the activity and fragment lifecycles? Slelect all that apply. 
*Choose as many answers as you see fit.*

- [x] onCreate()
- [ ] onDraw()
- [ ] onClick()
- [x] onStart()
- [x] onPause()

#### Q12. True or false? When your app goes into the background, it's not guaranteed to be destroyed. It may only be stopping and waiting for the user to return to it.

- [x] True 
- [ ] False

#### Q13. Fill-in-the-blanks
*Enter one or more words to complete the sentence.*

A `ViewModel` holds data to be displayed in a fragment or activity, and it can do simple calculations and transformation on data prepare the data to be displayed by the UI controller. 

Note: A ViewModel holds data to be displayed in a fragment or activity associated with the ViewModel. A ViewModel can do simple calculations and transformations on data to prepare the data to be displayed by the UI controller.

#### Q14. ____ is a way to restrict direct access to some of an object's fields. 

- [ ] Score
- [ ] LiveData
- [x] Encapsulation
- [ ] GameViewModel

Note: Encapsulation is a way to restrict direct access to some of an object's fields. When you encapsulate an object, you expose a set of public methods that modify the private internal fields. Using encapsulation, you control how other classes manipulate these internal fields.

#### Q15. Fill-in-the-blanks
*Enter one or more words to complete the sentence.*

A(n) `entity` represents an object or concept, and its properties, to store in a database. 

Note: An entity represents an object or concept, and its properties, to store in the database. An entity class defines a table and each instance of that class represents a row in the table. Each property defines a column.

#### Q16. To keep the UI running smoothly, use ____ for long-running tasks, such as all database operations. 

- [x] coroutines
- [ ] ViewModels
- [ ] returns
- [ ] managed threads

Note: To keep the UI running smoothly, use coroutines for long-running tasks, such as all database operations. Coroutines are asynchronous and non-blocking. They use suspend functions to make asynchronous code sequential.

#### Q17. True or false? When used, the enabled attribute determines if a view is visible.

- [ ] True
- [x] False

Note: The enabled attribute is not the same as the visibility attribute. The enabled attribute only determines whether the view is enabled, not whether the view is visible.

#### Q18. Fill-in-the-blanks
*Enter one or more words to complete the sentence.*

When a user scrolls through a large list, `RecyclerView` figures out what new items should be on the screen and does just enough work to display those items.

Note: By default, RecyclerView only does work to process or draw items that are currently visible on the screen. For example, if your list has 1,000 elements, but only 10 elements are visible, RecyclerView does only enough work to draw 10 items on the screen. When the user scrolls, RecyclerView figures out what new items should be on the screen and does just enough work to display those items.

#### Q19. A ____ represents, by default, the items in a row or column when using GridLayout. 

- [ ] grid
- [ ] layout
- [ ] list
- [x] span

Note: Span can mean either "row" or "column." With GridLayoutManager, you use spanCount to indicate how many columns or rows a grid has, and also how much grid space an item takes up horizontally or vertically.

#### Q20. Fill-in-the-blanks
*Enter one or more words to complete the sentence.*

When using RecyclerView, you should handle clicks in the `ViewHolder` because it has access to the data and logic for determining what needs to happen in response to the click. 

Note: When using RecyclerView, the ViewHolder is a great place to listen for clicks, but it's not usually the right place to handle them. An Adapter displays data items in views, so you could handle clicks in the adapter. However, the adapter's job is to adapt data for display, not deal with app logic. You should usually handle clicks in the ViewModel because the ViewModel has access to the data and logic for determining what needs to happen in response to the click.

#### Q21. Which of the following are Android RecyclerView layout managers? Select all that apply. 
*Choose as many answers as you see fit.*

- [x] GridLayoutManager
- [ ] RecyclingManager
- [x] LinearLayoutManager
- [ ] CircularLayoutManager

