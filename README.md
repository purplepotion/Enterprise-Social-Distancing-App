# App

 This app that promotes social distancing. The app detects the presence of other BLE handsets and devices and alarms the user to their proximity. The goal of this solution is to create a completely transparent application that can be used to save both lives and livelihoods.


We are a team of student developers. We want to help and are doing what we can. 



# Product Description and Vision
## Problem Statement
People need to get back to work eventually. Many essential workers continue to work through the COVID-19 global pandemic that we now find ourselves in. We need them not to get sick so our supply chain stays running and peoples' risk is minimized, and we can flatten the curve. We started building a contact tracing app for the Workforce Protection, and pivoted recently to help protect people and workforces. Contact tracing could easily be added on top of the social distancing features if necessary. See Roadmap below.

## Hypothesis
Individuals can use this app in groups to help them maintain social distance. 
Companies or families can deploy this app along with other measures and help protect their employees during Covid-19 and beyond. Using BLE (Bluetooth Low Energy), the app coupled with virus testing, Contact Tracing, temperature checks, symptom tracking, sick-leave pay, and other workforce protection measures (which companies are starting to implement), will all help prevent the spread of the coronavirus and any future infections, help flatten the curve, and protect people and workers.

We think there is a use case for employers, individuals, public health organizations, and governments to use the app coupled with Contact Tracing efforts put out by offical health orgs that may be delivered through App Stores on the Google/Apple API.

Contact tracing works to mitigate unknown transmisison after people are infected it is reactive. Social distancing is proactive, and may help with prevention. 

Companies can then work to protect thier teams while not saccrificing private personal data by deploying a custom version of the app with the Teams feature. Our app is made with privacy first in mind.

We have worked on improving BLE performance in our implementation, to lengthen battery life and optimize performance.
Contact tracing can easily be built by us or other teams on top of this code. The public version does not store any data centrally and keeps all data locally on the users handset.

Apple and [Google are delivering interoperable API's] (https://blog.google/inside-google/company-announcements/apple-and-google-partner-covid-19-contact-tracing-technology) that should well protect the privacy and mitigate concerns for contact tracing apps, creating a standard and a path for official organizations to create and publish apps through Apple and Google Play stores. Data Rights best practices have emerged for contact tracing that developers can comport to by the [TCN Coalition](https://tcn-coalition.org/). Our app keeps both of these strategiues and best practices in mind.


### Users Personas: Essential personnel and eventually all personnel.
Grocery Stockers checkers and workers

Caltrans road and municipal workers

Construction teams and workers

Amazon and other warehouse workers

Security Guards

Hospital Staff

Healthcare workers, dentists, Physical therapists.


### Who is our target organization to deliver this for?
Any private sector entity who would want to adopt it to ensure their workers know and are reminded about social distancing requirements and of course any Hospitals, Counties, States, Countries that would want to adopt it for educating their constiruencies about social distancing.

## Social Distancing
The app uses BLE to tell you when other app users are too close to help you maintain social distance.
The app can be deployed by an organization made available to be downloaded by individual workers. Individuals may opt in to application use and have granular and transparent data and privacy controls.

### Features
* **Active User Detection** - App notifies users when another app user is close. 4 levels of granularity. "Good Distance"= green, "Warning"= yellow, "Danger" = Orange, "Too Close"= Red
* **Alerts** - user and shows signal strength when other app user devices are detected.
* **History** - App stores a local history of the alerts from coming close to other app user devices. Displays Date and Time so that users can evaluate their social distancing performance through time.
* **Pause Detection** - user can turn off detection in app when not in use.
* **Safe Teams** - Add users to your 'Safe Team' using secure QR codes for each handset. This allows families who are safely socially distancing together to not recieve notifications of each others hansets when they are together, but out in public. E.G. A Couple shopping together in a store where all shoppers have the app downloaded and turned on.

### Roadmap
* **Set Your Social Distance** -  High risk users can set thier social distance 'radious' to be more sensitive that the local health authorities recommended distance, so that they are notified for 'Too Close' app users sooner. 
* **Data Storage for Employers** - Options could be added for users to opt in to sending location data for sessions that occured at the workplace if users wanted to contribute to mapping areas in the workplace where social distancing is not possible, per session.
* **IOS Version** - IOS version is also being built, and we are working to get this through the Apple Play store now. Contact us if you would like a download to test.

# Possible Future Versions 
## Add Contact Tracing
The App base code could be enhanced to use contact tracing to notify users when they have had contact with someone who has been tested and who's status is verified as positive for Covid-19. User can then get tested.

This app can be deployed by an organization made available to be downloaded to individual workers. Individuals may opt in to application use and have granular and transparent data and privacy control’s.

## Testing Status
The App base code could be enhanced to incorporate testing status for yourself and last date of testing. This can be compared to a history of contacts that were not social distanced for users to gain visibility into thier personal risk.

## Self Isolation/Distancing  Clock
The App base code could be enhanced to clock
Start day,
Current day
End day
Restart clock if newly exposure.
