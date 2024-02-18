# YouTube Clone
#### Video Demo:  <https://www.youtube.com/watch?v=ZabxKI1qeUY>
#### Description:

## HTML and JavaScript for YouTube Clone
The HTML code creates the structure for a YouTube homepage. Here, components, such as the sidebar, are used to imitate the layout of the actual homepage. At the very top is the **head section**. In this section, “YouTube.com Clone” is labeled as the title of the webpage. Next, the provided Google Font links allow the homepage to be formatted in Roboto. Near the end, the links of the created CSS files are linked to change the appearance of the homepage, including the general, sidebar, header, and video styles.

Next is the **header section**. This section is split into three subsections: **left**, **middle**, and **right**. The left section provides the icons for the hamburger menu and the YouTube logo. In the middle section, the search bar, along with the icons and tooltips for the search button and voice search button, is provided. Lastly, the right section contains the icons that would be clicked on if the user wanted to create content, check notifications, or edit their profile. 

After the **header section** is the **sidebar** section. On YouTube’s homepage, this would be the vertical menu on the left. The contents of this section include labels and icons for Home, Explore, Subscriptions, Originals, YouTube Music, and Library. 

Then, it’s the **video grid** section. This section is the main body of the webpage. The **video grid** portrays a sequence of video previews, including the thumbnail, a playtime overlay, and a video information grid. The video information grid contains the channel profile picture, the video title, the name of the creator, and the view statistics (such as view count and when it was posted). 

The last section is the **script section**. Here, a function called **’redirectToLink’** is used. This function allows the user to when clicked, be directed to the provided link. For example, when clicking on one of the video previews, that user will be sent to the corresponding YouTube video.

To wrap it all up, this HTML portion of the code is used as the blueprint for creating the YouTube homepage. Using custom stylesheets and JavaScript, the clone can successfully mimic the format of the actual homepage, creating a user-friendly and aesthetically pleasing interface. 


## CSS for YouTube Clone
The CSS portion consists of four stylesheets: general, header, sidebar, and video. Each of these CSS files changes the layout of the HTML page and allows for a more visually appealing interface. 

The **general** stylesheet styles the general body of the webpage. Each paragraph is written in the Roboto font, with a margin-top and margin-bottom of zero. In the body portion, the overall margin is zero, with the **padding-top** being 80 pixels, **padding-left** being 96 pixels, and **padding-right** being 24 pixels. Any portions of code using the **body** style will have all of these attributes, including a **background-color** of white.

The **header** stylesheet styles the header of the webpage. Many components have their unique style, including different padding, color, and font size. For example, the **.hamburger-menu** has a height, **margin-left**, and **margin-right** of 24 pixels. Another example is the notification counter. Here, the style of its **position**, **padding**, **background-color**, and **font-size** alter the notification number enough to a point where it looks almost identical to the actual homepage. 

The **sidebar** stylesheet styles the sidebar of the webpage. The entire sidebar has a **background-color** of white, a fixed **position**, and a **width** of 72 pixels. Each component in the sidebar has unique styles as well. For example, the icons on the sidebar will be under the **sidebar-link img** class, having a **height** of 24 pixels and a **margin-bottom** of 4 pixels. 

The **video** stylesheet styles each video preview on the homepage. Several components have different styles. The **.thumbnail** class has a **width** of 100%. The **.video-author** and **.video-stats** classes have a **font-size** of 12 pixels and a color of grey. The **video-time** class is the small video length in time on the side of the video preview. To achieve the style of the small time count on the side of the video preview, the **video-time** class is provided. Here, the **background-color** of the text must be black, along with the text being white. The padding for the top, left, right, and bottom are all 4 pixels. The **font-weight** of 500 creates a more bold text, allowing it to stick out more on the video preview. 

Using the power of CSS, HTML, and JavaScript, a recreation of the YouTube homepage is possible. These tools provide a way to create a visually appealing and user-friendly interactive interface. Paying careful attention to creating the styles was crucial for the success of this project. This success demonstrates the potential for creating user-friendly and interactive interfaces for any application. 
