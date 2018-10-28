# Extra Life Banner

Track progress towards you or your team's Extra Life goal and display last three donors. For use as an overlay with OBS or other streaming clients.

All of the required images (SVG), CSS and JS are embedded in the HTML file.

##  Usage

* Clone or download index.html to your local computer.
* Change the participantID in the <script> to your Extra Life participantID. You can find this in the URL for your team page. OR
* If you want to track your team's progress and donations, delete the participantID constant in the <script> and change the teamID to your Extra Life teamID. You can find this in the URL for your team page.
* Change the donationURL in the <script> to your URL.
* Change the socialName in the <script> to your Twitter/Twitch username. (You can delete either of the social icons from the HTML if they aren't applicable.)
* In your streaming client, create a browser source with your local copy of index.html.
* Set the dimensions of the browser source to 1920 x 1080.
* The script should refresh automatically every 30 seconds.
