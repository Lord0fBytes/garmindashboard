# Garmin Connect Dashboard

This will be the future home for my Garmin Dashboard site.  
Hopefully this will allow people to log into their Garmin Connect account and create a pretty dashboard of information including the main focus which will be a heat map of activities.  
___

## Privacy Policy

Limited privacy policy that is pretty generic since I am no lawyer. 

### **Caution to anyone wanting to use this:**  

Data that this application pulls will contain very personal data including, but not limited to:

- GPS location data of activities
- Device information (name and type)
- Personal information (Name, username, password (encrypted))
- Activity metrics (run times, types of activities)

I do not store anything from the data pulled. I will have scripts that clean the data as soon as you leave the session.  
You will have the ability to download the data for personal use and manually delete it from the server.  

If any of this sketches you out then be gone, no hard feelings.  

This is just a fun project I am making for some friends and have no intensions of storing or sharing any data. I do not even want to see the data personally. This is for your eyes only and whom ever you wish to show the data to is your download it.  

If you are still unsure feel free to look at my project page on Github where you can see in the code where I remove everything and encrypt information.  

___

## Getting Started

This application uses a [garmin export utility](https://github.com/petergardfjall/garminexport) from petergardfjall to access Garmin Connect data. I did not write any of it. They did an amazing job of creating this feature I am using. All credit goes to them.

When you first get to the site you will be prompted with the above Privacy Policy for you to acknowledge (I don't feel like getting sued).  

Next you will log into the site using your Garmin Connect Username and Password (all passwords are stored temporarily to access the information and then removed).

Next you will see a loading screen. Depending on the amount of activities you have in your Garmin account this could take a while (~60 seconds per 100 activities).

Once the data is loaded you will be brought to your Dashboard where you can view all the fun bells and whistles of your data. The main feature I will be designing is the Heatmap of your activities. It will show a Google Map based image with all the plots of where you have done activities.

___

## Pipeline

Features:

- Basic Import and Export of data
- Basic insights on your activities (TDB)
- Map showing all activities
- Filter for map to show only specific activities
- Hopefully lots more
