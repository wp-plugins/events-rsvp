=== Events RSVP ===
Author URI: http://julienklepatch.com
Plugin URI: http://julienklepatch.com
Tags: events, event, rsvp, organization, form
Requires at least: 4.1
Tested up to: 4.1

Stable Tag: 1.0

License: GNU Version 2 or Any Later Version

Easily create an RSVP form and manage registrations

== Description ==

Events RSVP is a plugin to create RSVP forms for events and manage registrations.

Events are created from a custom menu in the admin and integrated to the website
thanks to a custom widget, located in the widget menu.

Users can:

* Register for the event
* Register for the waiting list if the max registration limit has been reached
* Receive confirmation emails after successful registration for the event or
for the waiting list

Admin can:

* See the list of people registered for the event and for the waiting list
* Modify the max registration limit
* Cancel any registration

== Installation ==

1. Install ERSVP via WordPress.org plugin directory
2. Activate the plugin

Congrats, the plugin is now active !

To display a registration form in the front end, you need to:

1. Create an event
2. Setup the Event Registration Widget

1. Create an event
  * Go to the `Events` menu, then click on the `Add New` sub-menu
  * Create a new event with a title, max registrations limit (how many people can register) and date
2. Setup the Event Registration widget
  * Go to Widgets menu 
  * In the `Available Widgets` pane, you should see a new widget called `Events Registration`
  * Drag and drop this widget to one of the widget area of your theme, on the right-hand side (sometime called sidebar)
  * Click on the down arrow of the widget to expand it
  * Set the title that will appear on the front-end
  * select the event you want from the drop-down list
  * Click on Save

Congrats, you have just setup your first event !
You just need to refresh the page where the widget area or sidebar is active, and you should see the event registration form.

Optionally, you can also configure the emails sent to users upon registration for the event or for the waiting list.
For this, go to the Events menu, then Settings sub-menu, and you will find the relevant settings.

== Frequently Asked Questions ==

= How to change the max registration limit? =

1. Go to the event menu
2. Click on the event you want to modify
3. Update the max registration field with the new limit
4. Click on the Update button 

That's it ! The new max registration limit has been saved.

= How to cancel a registration ? =

1. Go to the event menu
2. Click on the event you want to modify
3. In the Registrations table, check the registrations to delete in the Delete column
4. Click on the Update button 

That's it ! The registration(s) you checked has(have) been deleted and the waiting list has been re-calculated

= How to change the event date? =

1. Go to the event menu
2. Click on the event you want to modify
3. Update the date field with the new date
4. Click on the Update button

= How to change the title that appear above the RSVP form? =

1. Go to the widget menu
2. On the right-hand side, you should see a Widget Area or a Sidebar pane
3. Find the ERSVP widget, and click on the down arrow to expand it
4. Change the title field
5. Click on Save 

That's it ! The new title has been saved

= How to change the emails sent to users after successful registration? =

1. Go to the Event menu
2. Go to the Settings menu
3. Find the ERSVP widget, and click on the down arrow to expand it
4. Change the title field
5. Change the subject and message fields for emails sent after a successful registration
for the event (registration Succesful section) and for the waiting list (Waiting List section) 

= How to change the form elements (Name, phone number, etc...)? =

This feature has not been implemented yet, but it will be in a future release

== Changelog ==

= 1.0: Apr 6, 2015 =

* First version !
