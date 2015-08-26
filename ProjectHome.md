Instead of creating separate project for each widget/plugin, I decided to store all of my plugins under one project. Most of the plugins are created for JQuery, but I have also created a few for YUI and Dojo. I also moved all of my previous projects to this location. The list below displays all of my plugins and widgets with a description of each.

Demos for all widgets/plugins can be found at:

http://grasshopperpebbles.com/demos/



<h1>JQuery Plugins</h1>


<strong>imAnimTabber</strong>

This plugin was based upon the imUpSideDownTabber that I created a few months ago. The imUpSideDownTabber is a tabbed interface that displays tabs underneath the content. Much of the functionality for this new plugin is the same as the imUpSideDownTabber, but I decided to rename it because it does more than just up-side-down tabbing. This tabbing plugin can be used to display content with the following animated options:

slide (imUpsideDownTabber) height width fade carousel

As with the imUpSideDownTabber, the tabs can be created dynamically, but I added a ‘manual’ mode so that the imAnimTabber plugin can function when the tabbing interface is already created. Unlike the imUpSideDownTabber, the tabs can be individually styled. Also, unlike imUpSideDownTabber, I created a true demo page.

To view the documentation, go to: http://grasshopperpebbles.com/ajax/jquery-plugin-imanimtabber/




<strong>imBannerRotater</strong>

I created simple plugin that rotates images on a page. There are two modes. In the default mode, the plugin will display a randomly selected image. In the other mode, the plugin will rotate images on a page (fading in/out). In this mode, you can select the speed of the rotation. The image data can be retrieved ajaxally (json or a comma separated list). If the data is Json, a url can be added for each image.

Recently added a Carousel and a Portfolio mode.

To view the documentation, go to: http://grasshopperpebbles.com/ajax/jquery-plugin-imbannerrotater/




<strong>imBookFlip</strong>

I was asked by a client to create a bookflip (Page Turn) effect that did not require Flash.  The imBookFlip plugin can load a book in an iframe or directly on the page. The book's pages can be set to turn when manually clicked only, begin auto flip (turn automatically) as soon as the html page loads, or begin auto flip when first page (front cover is clicked). Sound Manager can be used with the plugin to add audio to the book.



<strong>imCheckBoxDB</strong>

There are a number of repetitive tasks that developers perform when creating web sites, especially as it relates to the gui. I was developing a web site where the owner wanted multiples lists of checkboxes on various pages of his website. On most the pages where these checkboxes appeared, the owner wanted the check boxes to have a 4-column display, but there were other pages where he wanted a 3-columns display. I got tired of copying/pasting the php/html structure from page to page, so I decided to create a JQuery plugin (imCheckBoxDB), that would layout the check box lists for me. The checkbox list is created "Ajaxally". Both an id and label can be retrieved for each checkbox.

To view documentation, go to: http://grasshopperpebbles.com/ajax/jquery-plugin-imcheckboxdb/




<strong>imGoogleMaps - 0.5</strong>

Although there are other JQuery plugins that enable a developer to integrate Google maps API into websites, I wanted to create a simpler implementation, one that did not have all the options, only the basics. I think that in most situations, a website owner only wants an end-user to be able to view the owner’s address and be able to map directions to that address. In addition, I wanted a plugin that displayed a map interface that is similar to what one would see on Google Maps (auto mode) while also giving the developer the ability to style their own interface (manual mode). This plugin will also display certain Google Map errors codes. In addition, this plugin will allow you to use Ajax to retrieve an address as well as Reverse Geocoding.


<strong>imGoogleMaps - 0.9</strong>

Added Street View Overlay, Street View Panorama and the ability to plot multiple addresses

To view documentation, go to: http://grasshopperpebbles.com/ajax/jquery-plugin-imgooglemaps-0-9-multiple-addresses-street-view/

<strong>imGoogleMaps - 0.9.2</strong>

Now you can display custom marker icons on the maps. You can also display a phone number and description in the infoWindow. imProgressBar is bundled with this release.

<strong>imGoogleMaps - 0.9.3</strong>

You can display images in the infoWindow. You must supply the image\_loc, width, and height. You can optionally add a class\_name, url, and new\_line. The new\_line option is used when you have multiple images in the infoWindow and you want each image to appear on a line of it's own. So the image that appears after the record with the new\_line option will be pushed to the next line.

To view documentation, go to: http://grasshopperpebbles.com/ajax/jquery-plugin-imgooglemaps-0-9-2-custom-marker-icons/

<strong>imGoogleMaps - 1.0</strong>

1. Upgraded to Google Maps V3
  1. API key is no longer needed - 

&lt;script src="http://maps.google.com/maps/api/js?sensor=false" type="text/javascript"&gt;



&lt;/script&gt;


> 2. Street View button control must be opted when map is initialized (show\_streetview\_overlay)
> 2. Removed auto mode (mode option no longer needed)
> 3. Removed directions option - now popup window only
> 4. Removed show\_directions\_menu option - now show\_directions (in infoWindow)
> 5. Changed imBusinessName to infoWindowBusinessName and imDescription to infoWindowDescription (css)
> 6. json is now the default data\_type option (was 'text')
> 7. Removed menu\_class, print\_class, button\_class, and search options.
> 8. Added URL to info window.  class = infoWindowUrl (see item #8)
> 9. Added show\_infowindow\_url option. If true (the default), url will display in info window (if exists).
> > If false, url link will be added to business name (or name).
> > When false, class = .infoWindowBusinessName a
  1. . Removed mapIconMaker - http://groups.google.com/group/google-chart-api/web/map-pins-sticky-notes-information-bubbles-text-with-outline
  1. . Added show\_traffic and show\_bicycling
  1. . Added kml and georss support
    1. data\_type = 'layer'
> > 2. For multiple layers, add: is\_layer\_url = true to json record



<strong>imList</strong>

imList is a JQuery plugin that began as a way to ajaxally create html tables using JQuery. After creating the table plugin, I realized that I could apply much of the same functionality to any type of list that is displayed on a web page, to include: ul/ol, comboboxes, lists, and divs. The power of this plugin is it’s regular expression functionality that will allow developers to display anything they wish within a list. I have also built in a delete row capability that can, not only delete the row that is displayed on the web page, but also allow the developer to delete the record from the server (ajaxally, of course).

Documentation for this plugin can be found at: http://grasshopperpebbles.com/ajax/jquery-plugin-imlist/




<strong>imPagePopulate</strong>

Depending upon the number of elements on a page, retrieving data from a database and populating a web page with the data can be a very tedious task. In the past, I have always used server-based technologies (PHP, Coldfusion, etc) to populate a page. After growing tired of creating the structures over and over again, I decided to create a JQuery plugin that would do the work for me. Most of the page population plugins I have seen only populate form elements. The imPagePopulate plugin will not only populate form elements, it will populate any HTML element on a page.

To view the documentation, go to: http://grasshopperpebbles.com/ajax/jquery-plugin-impagepopulate/



<strong>imProgressBar</strong>

A Progress Bar that can be displayed inline or as a popup. The imProgressBar is bundled with over 20 different bar graphics, so it can match the color scheme of a variety of websites. The bar graphics don't have to be used because the progress bar can easily be styled by the developer.

To view the documentation, go to: http://grasshopperpebbles.com/ajax/a-jquery-progress-bar-plugin/





<strong>imValidateForm</strong>

Prior to using JQuery, I had developed Javascript object that validated forms prior to submission. I got the basic concept (and some code) from the book, “Beginning Ajax with PHP” by Lee Babin. I modified it a great deal. Once I began using JQuery, I converted the Javascript object to a JQuery plugin. Unlike most validation plugins which validate input on exit of the field (onBlur), the imValidateForm plugin validates the entire form once the user clicks the submit button. The plugin also handles the submission (ajaxally, of course) and allows you to disable the submit button to prevent double-clicking.

The imValidate plugin will validate the following:

Required Fields/Exclude Values Valid Email Either/Or (Either input 1 or input 2 must be entered) Valid values (Must be equal to) Checked Values (is the field checked) Is Numeric Is Alpha Only Meets Condition (==, !=, <, <=, >, >=)

To view the documentation, go to: http://grasshopperpebbles.com/ajax/jquery-plugin-imvalidateform/



<h1>JQuery UI Widgets</h1>

<strong>imFeedBack</strong>

A JQuery UI Feedback widget. The Feedback tab can be displayed on the right or left of the web page. By default, the feedback form slides into view. You can optionally display a dialog. The widget will automatically use the styles created with the JQuery UI ThemeRoller, but can optionally change the styling to anything you wish.

The widget will build the contact form for you. Email address, Subject, and Message are displayed by default, but you have the option of adding name fields (first name, first and last.

To view the documentation, go to: http://grasshopperpebbles.com/ajax/ui-imfeedback-a-jquery-ui-feedback-widget/



<h1>YUI Widgets</h1>


<strong>imInputCal</strong>

I was working on a project that required an input calendar field. This widget can be used with a one or multiple input fields. When a user clicks on the input field, the calendar appears. Select a date and the date is automatically inserted into the input field.

To view the documentation, go to: http://grasshopperpebbles.com/ajax/yui-an-input-field-calendar-widget/





<strong>imYUILogin</strong>

The imYUILogin widget was originally created for an intranet project that I was working on. I originally created it using YUI's <a href='http://developer.yahoo.com/yui/container/dialog/index.html'>Dialog Container</a>, but I recently updated it so that it could be configured as a <a href='http://developer.yahoo.com/yui/container/panel/index.html'>Panel</a> or a <a href='http://developer.yahoo.com/yui/container/module/index.html'>Module</a>. Logging in is done ajaxally, of course.

To view the documentation, go to: http://grasshopperpebbles.com/ajax/a-yui-login-widget/






<strong>imSliderMenu</strong>

This YUI widget is based on my imAnimTabber JQuery Plugin. The imSliderMenu displays content by animating the height or the width of the contents container. I use the imSliderMenu widget on my marketing site, http://1st-steps-to-success.com. The slider menu is handy in that I am able hide content on a page until it is needed and still maintain the look and feel of my website design. As with imAnimTabber, The imSliderMenu dynamically creates the menu items based on CSS and a few lines of code.

To view the documentation, go to: http://grasshopperpebbles.com/yui/yui-widgets/yui-imslidermenu-widget/





<h1>Dojo Widgets</h1>

<strong>imRichEditor</strong>

This Dojo widget enables a developer to easily integrate TinyMCE's text editor into a web page.

To view the documentation, go to: http://grasshopperpebbles.com/ajax/dojo-and-tinymce-creating-a-widget/


