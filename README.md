# Eesysoft Messaging (Producer) {#eesysoft-messaging-producer}

EesyProducer (Messaging)

Eesysoft support = support@eesysoft.com

EesyProducer allows you to add context-sensitive custom messages, hints, web links, and resources into Blackboard. You can target specific departments, courses, or users. Eesysoft is currently a windows-based software which must be downloaded and installed on a PC or Mac running Windows. (This is being changed to a web-based application.)

**NOTE:** Major updates to the staging server may revert all Eesysoft settings on staging to the settings on the production server! This means none of the staging messages will work; only messages from production will display.

Settings are located in the Eesysoft Building Block. Easysoft Connector => Settings => URL: [https://sdsustaging.eesysoft.com](https://sdsustaging.eesysoft.com) => Key: **<<KEY>>** Support Tab: ON

◆ **Get Started:** Login to Eesysoft Producer by clicking on the software icon.

Staging Server: [https://sdsustaging.eesysoft.com](https://sdsustaging.eesysoft.com)

Production should be used with care (Server: [https://blackboard.sdsu.edu](https://blackboard.sdsu.edu))

![Macintosh HD:Users:lindawoods:Desktop:Screen Shot 2016-07-28 at 2.54.37 PM.png](export/assets/macintosh_hduserslindawoodsdeskt.png)

You can think of the entire process as three steps:

1.  Create (your message – called “Content” by Eesysoft)
2.  Capture (pages where will it appear – called “Context” by Eesysoft)
3.  Connect (publish it to the right place for the right users)

**1\. Create** (Content): Create help items in your content folder.

![Macintosh HD:Users:lindawoods:Desktop:Screen Shot 2016-04-15 at 10.45.07 AM.png](export/assets/macintosh_hduserslindawoodsdeskt.png)

1.  Click into the appropriate content folder.
2.  Use the menu icons, right click, or select “New” to create a new help item. (Roll-over the menu icons to view the type of help item.)
3.  Fill in the various fields. (Title is shown to users)
4.  Remind users at end of message that they can permanently disable the message by clicking “Don’t show this again.”
5.  ![C:\Users\Linda Woods\Desktop\assignedTo.PNG](export/assets/cuserslinda_woodsdesktopassign.png)After you create your message, click in the message row under “Assign to User” and select your users.
6.  Select Users then use the right facing arrow to move them over to Assigned. Best to use TestUsers for first; then Course_Roles for production when you’re certain the messages work. All = anyone who logs into Blackboard. Instructors = everyone with Instructor rights which includes CourseRole_Homeroom Admin, CourseRole_Instructor, CourseRole_TeachingAssistant).

![C:\Users\Linda Woods\Desktop\users.PNG](export/assets/cuserslinda_woodsdesktopusers.png)**NOTE:** You can change the size of the message window by grabbing the lower corner of the message window. You can keep adjusting the size until it looks right on the Blackboard page. Simply refresh the Blackboard page until you are satisfied.

**Help Items:**

There are 7 types of help items. They are either _pro-active_ or _on-demand_. Pro-active items are shown in Blackboard until user disables them. Pro-active messages provide quick context-relevant information (Popup Message, Hint, Systray).

On-demand items are shown in the slide-out tab (the Support Dashboard tab) on right side of course page and require clicking to access content.

| **Name** | **Type** | **Use** |
| --- | --- | --- |
| Popup Message | Pro-active | **Situation**: Urgent information for users (Types = information, warning, error, new, or none.) |
| Hint | Pro-active | **Situation**: Short message or tip related to an item on the course page. Could be roll-over only. |
| Systray | Pro-active | **Situation**: Short and relevant message |
| Embedded HTML | On demand | **Situation**: Info via embedded (YouTube) video |
| File | On demand | **Situation**: Provide file based help (docs, PDFs, etc) |
| Link | On demand | **Situation**: Provide URL to web resource |
| Video | On demand | **Situation**: Inform user via a video that has been uploaded to the EesySoft server. |

*Additional info on Embedded HTML

To use the HTML embedded code, go to YouTube, select the video you would like to share, and copy the embed code (not the URL!).

<iframe width=&quot;560&quot; height=&quot;315&quot; src=&quot;https://www.youtube.com/embed/jN183h4Uz6w&quot; frameborder=&quot;0&quot; allowfullscreen></iframe>

Paste the code into the HTML code field in the Embedded content help item. To show the video correctly, you must change the ‘width’ and ‘height’ to 100%.

<iframe **width=&quot;100%&quot; height=&quot;100%&quot;** src=&quot;https://www.youtube.com/embed/jN183h4Uz6w&quot; frameborder=&quot;0&quot; allowfullscreen></iframe>

**2\. Capture:** Screen capture (Context)

Next you need to capture the course page where the message will display. Capturing and defining the whole page is a required part of the standard capture workflow. Defining a specific elements of the page (buttons, menu items, icons, etc.) is a separate task that comes after defining a page.

1.  ![folders.PNG](export/assets/folderspng.png)Click context folder where you intend to store your captured Blackboard pages (screenshots).
2.  ![captureIcon.PNG](export/assets/captureiconpng.png)Click the screen capture icon on the menu. (Roll-over the menu icon and the label will appear saying “Create a new Screencapture.”)
3.  A new window opens. Enter your Blackboard URL ([https://sdsustaging.blackboard.com](https://sdsustaging.blackboard.com)).
4.  Save this URL by clicking on Favorites in the menu.
5.  Another window will pop up. Name the URL and click “Ok”.
6.  Click “Go” on the far right to login to Blackboard.
7.  Navigate to the Blackboard page where you want to place the message and click “Capture.”

![capture1.PNG](export/assets/capture1png.png)

1.  Give the capture a name (Example: Course Copy_Size Warning)
2.  Click “Ok.”

A new window opens with “parameters.”

**2.1 Parameters**: Define the Page Context

There are many parameters that appear depending on the screen capture. Parameters help define where the screen capture and attached content should appear. The main sections of the parameters window, called “Define Page Context,” are:

*   *   Host: Do not select in case name changes
    *   Path: **Always select this** (shouldn’t even appear then - ask Eesysoft to get rid of it)
    *   There are often many other parameters and it’s trial and error to know which to choose sometimes.
    *   Course_id restricts to just this course - do not select if you want to appear in other locations in Blackboard.

1.  Always select the Path.
2.  Select any other Parameters that seem applicable. It’s somewhat a guessing game.
3.  Click “Ok” when done.

**2.2 Refine your capture**: Select specific page elements.

So far, the capture involved the whole page. You can add content to an entire page such as the Blackboard Welcome Page; but normally you will want to further define an element to provide hints or track a specific part of a page such as a button on the navigation menu.

Defining a specific part of the page starts with selecting your screen capture.

1.  Select your context folder and double-click on the name of your screen capture not the “Page.”
2.  Click on the screen capture image on the right.
3.  This opens a new window, the Html Context Editor.

IMPORTANT NOTE: Select the screen capture and NOT the Page context to define elements!

Selecting the “BODY” tag attaches a help item or monitor to the entire page. By expanding the tags in the upper left pane, “Window structure,” you can see how the web page is built. Clicking elements on the image or the tags in the window, selects items and encloses them into a red box.

1.  Click on the item (context) you want to use for messaging.
2.  ![Macintosh HD:Users:lindawoods:Desktop:Screen Shot 2016-07-29 at 2.48.15 PM.png](export/assets/macintosh_hduserslindawoodsdeskt.png)If you haven’t already, expand the tags in the left “Window structure box
3.  Select the best HTML tag - often the Anchor or link tag for menu items. This usually involves some experimentation!
4.  You must identify and save this item by creating a unique “recognition rule.” In the “Details” panel on the lower left, click on “Recognition rules” and then right click to “Add Recognition rule.”
5.  A new Recognition Rule window opens. Select the parameters (Attribute, Rule, or Text) based on the context. The chosen attribute should be unique and static. Below is an overview of frequently used attributes. For example, “id” is a better choice than “class.” The “id” tag is very specific. Experimentation may be required!
6.  Click “Ok” when done.

**Common Attributes**

| **Attribute** | **Description** |
| --- | --- |
| id | Specifies a unique id for an element |
| url | Specifies a unique URL |
| href | Specifies the URL of the page the link goes to |
| InnerHTML | Specifies the text value of a node (element) – watch out as this text can change in a multi-lingual environment |
| class | Specifies one or more class names for an element (refers to a class in a style sheet) |
| title | Provides extra information about an element |
| src | Tells where to get the picture that should be put on the page |

1.  Select “Name” from above the recognition rule and right click to “Edit Name.” The recognition rule name should be easy to recognize, descriptive, and relevant to the element. Example: “Student Preview Button.”
2.  Click “Ok.”
3.  Click on the **Publish** button on the bottom right of the Html Content Editor window to save all of your changes and make them available.

**NOTE**: Normally, a hint won’t show until the user is near the item (page element) and activates the hint. “Scan for Content” in the Details section is used for hints that you want to show even if the user doesn’t roll over the item.

**3.0 Connect:** Connect to your message and define your audience

In this part, you will connect the screen capture (element that needs help or more info) to the actual content (the help or information resource).

1.  Select the screen capture element for which you want to attach help by clicking on it.
2.  Click the button that looks like a red push pin to connect. A new window will open.
3.  Go to the Content folder where you saved the help items
4.  Select the help item you want to attach by clicking on it once.
5.  Click “Ok” to connect the two.

**3.1 Setting the Mode (Popup messages)**.

The Hint and Systray message will, by default, always appear pro-actively; while the File, Link, and Video are always in the on-demand slide-out tab (the Support Dashboard). The Popup message will require setting the mode.

1.  Click on the popup message and the color will change from red highlight to blue.
2.  There are 3 “ball" shaped icons next to the “connect pin” which should now be active (colored)
3.  You can hover over the balls to see your choices or use the HelpItem menu to “Set Mode.”
4.  There are 3 options:

*   Provide the help item upon request of the end-user (blue)
*   Provide the help item pro-actively once (orange)
*   Provide the help item pro-actively each time a user hovers over the button (red)

**3.3 Additional properties for help items** (We are currently not using these; will update later

The following options are available for help items:

1) “Valid from” and “valid to” date to restrict display.

2) Help items to the widgets in the support dashboard. This means that these help items will be available for ‘on demand support’