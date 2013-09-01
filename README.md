Reader Android Project
===========

Components
----------

1) Home Activity ( List of Feed Sites ) - pull from RSS feed to SQLite - DONE
- YahooRSSActivity.java
- activity_yahoo_rss.xml


2) Feed Items List Activity - Individual Items from a specific RSS Feed.  List should display Items from RSS feed.  Maybe bold or highlight unread (not clicked) items.  Must update the Feed unread count.
On click of an individual Item should spawn an Intent to go to Item Full Details View.  Must pass Item with Intent.
- ItemsActivity.java
- activity_items.xml - DONE


3) Item Full Details View - Once an individual Feed Item is clicked, a new Activity (or Fragment) should be be launched with the Title, Description, Url (and possibly published date) with the ability to launch an Intent to load the Url in a web browser.
- RSSReaderDetails.java
- activity_rssreader_details.xml - DONE



4) Edit Feed - save to SQLIte - DONE


4.5) Files:
- RSSReaderApplication.java is used to initialize the sqlite database

Bonus / Additional Features

5) Search feature for other available RSS sites
6) Long Click to delete feed. - DONE
7) Or to mark an item as read. 
8) Other features?

