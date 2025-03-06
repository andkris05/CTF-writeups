`So i just found this very cool google doc that contains soo much different country metas for geoguessr 
and some of them are really spesific. Anyways the road in the picture leads up to a very nice looking camp/hotel. 
What is the name of the camp?`

`PS: The name from the google maps point of intrest Flag format: CTFkom{NAME OF CAMP}`

`https://docs.google.com/spreadsheets/d/1UNvkoY-LaktF75nU_cP7-wVRAEvH3fSqVZet20HqxXA`

In this challenge we are met with an image taken from Google Maps. For a person like me, this could be anywhere in the world,
for all I know. I couldn't point out anything that could give us an answer. But a little digging using the docs given in
the challenge, I figured out that it was taken in Mongolia. The car you see in the picture is apperantly a dead giveaway
for geoguessr enthusiasts. With this info, I looked into car metas in Mongolia, which essentially means clues and tips
for figuring out your location in geoguessr based on the car in the photo. 

On this website: https://www.plonkit.net/mongolia I was able to figure out the general location we were in based on the
rubber inlays of our car's roof racks. Our car having a presence of rubber inlays tells us that we are either in the middle,
or northwest of Mongolia.

However, this information alone, while helpful, doesn't pinpoint any exact location. I later found another website that
explained Mongolia's car meta well: https://gwern.net/doc/cs/security/2021-kommu-themongoliangeoguessrmeta.pdf.
What I learned here, is that the car's content can give us huge hints on our whereabouts. Most places in mongolia with this
type of car seem to have a trunk-cover covering its contents. Our car however, doesn't have that. On this website I was able
to find perfect info on exactly this, and the blue sleeping bag on the left is a big hint.

This pinpoints our location to a very small area in the middle of Mongolia. And if we go to google maps, it's supposed to be
right above the Mongolia-name. If we go to Mongolia on google maps and search `Mongolia Camp Hotel`, it will give us
a few locations here and there. By zooming in right abovie the Mongolia name, we will find about 4-5 camps. One of them is
called `BAYAN GOBI`, and has a nice road leading up to it and nothing else. This ended up being the flag.

`CTFkom{BAYAN GOBI}`


