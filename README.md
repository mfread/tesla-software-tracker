# tesla software tracker
* Displays a tree (with branches and leaves) or a table view of Tesla car firmware end-points and highlights the selected car's firmware history.
* Data comes from various apps, including Teslascope, Tessie, Not A Tesla, TeslaFi, TeslAnt, X and Grok. Credit for the data goes to these organisations.
* Not all the countries where Tesla cars are sold into is captured (as this would slow down the UI). Countries included in the nightly data refresh are:
  - AE: United Arab Emirates
  - AT: Austria
  - AU: Australia
  - BE: Belgium
  - CA: Canada
  - CH: Switzerland
  - CN: China
  - DE: Germany 
  - DK: Denmark
  - FR: France 
  - GB: Great Britain
  - KR: Korea (South)
  - MX: Mexico
  - NL: Netherlands
  - NO: Norway 
  - NZ: New Zealand
  - SE: Sweden
  - TW: Taiwan 
  - US: USA
* snapshot.json updated 5am Australian Eastern Standard Time.

# why this app?
I developed this web app so I could merge and visualise the dozens of code branches Tesla has on-the-go at any one time. Yes, I could view this data by visiting several websites that track this information, but I could not find a central location for all this data. So I built one. The data is not 100% accurate because Tesla does not record or maintain such information.

# how to use
* Simply add up to 5 cars via the left hand panel and the versions of software you've had over the past few months / years (if you don't keep track of this info, open your Tesla app on your smartphone, scroll down to the bottom and click on Release Notes).
* Select the car you'd like to view data on. What you see in the Tree or Table view can be influenced by the View Options in the left pane.
* Cars collection can be exported to a csv file.
* Also under View Options select up to 5 countries you'd like to see data for. For example I live in Australia so I'm keen to see what firmwares have been seen by the trackers in Australia, and I'll also include US as this is the source of most firmware releases. These 2 letter ISO codes must come from the list above.
* The left side panel can be hidden by clicking/tapping on the top left < icon. Click/tap on the > icon to reveal the side panel.
* Click on the Tree or Table button along the top ribbon bar.
* The Tree view can be zoomed in or out of. However over the leaves to reveal the info panel about that firmware you are viewing.
* The Table view has filters to focus on the data you wish to see, and sortable columns. Click/tap on any row to see the info panel pop up.
* The Predicted Next section under each car is based on the firmware history of the car when matched to all other cars with the same history and what software version they jumped next to. Not 100% accurate but provides a weighted guess which is typically accurate. If you do not provide the car's firmware history then the Predicted Next version will be less accurate.
* When switching between Tree and Table views, be sure to click on the Refresh Data button.

# data security
* All data entered by you stays on your device and not on a central server somewhere. So if you run this webapp on multiple devices you'll need to enter each car's details and firmware history again.

# license
Australian/US default copyright applies. You must ask permission to copy, modify, or republish. You may not commercialize my work.
