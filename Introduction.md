# Railway Galore

## About
  Railway Galore is a web based tool for designing and visualizing railway corridors, possible railway projects, and 
  custom or fictional railway/railroads. This website is based purely on the idea of perfect auto-smoothing of curves that can 
  be inputted inside Google Earth Pro when making railway corridors. All code was made by Gemini Free Version (idk how to code 
  yall, im just experimenting).

## Current Features
  - Automatic curve smoothing on lines
  - Railway corridor drawing (railway track based line design)
  - Branch Lines (needs further improvement for distinction from Main Line)
  - Placeable stations with varying length (when imported to GEP, the stations will appear as placemarks)
  - KML Export (for importing inside GEP)
  - Mirror track when enabling Double track (can be used while sketching lines)
  - Auto placing of a station based on the direction of the track/line
  - Editable name of line and station
  - Undo button
  - Clear Saved Data
  - Data automatically saved without signing in (probably)

## Why I made this

  I created this project when I got a liking about trains, most specifically its railway corridors. I have heard of a proposed
  railway project that is in a feasibility study in my country and I wanted to sketch its proposed railway corridors on a map. I used GEP for 
  this and it worked well until my perfectionist self wanted the curves to be an actual smooth curve instead of a bunch of 
  straight lines connected to each other which makes the curves look jagged. I thought there could have been an app or website that
  can be able to plot lines while making the curves smooth in the process. I eventually found MapLineDraw, which was great but it gave 
  me the urge to create my own. So I got into Gemini AI to make me a website specifically to make lines automatically curve, I have 
  used the free version of Gemini (it works so much better than free ChatGPT). 

## Status

 It is currently still in development, there are some inconsistencies that needs to be fixed. For example, making a new curve/line
 affects the line/curve before it, Im hoping we could make it so that each line segment will be of a individual identity that wouldnt
 be easily affected by the auto smoothing engine. The past two days, I was also hoping to add a coordinate searchbar so that a user
 can punch in coordinates which is useful for placing stations in an exact location. But for some reason, the line editor/placer wouldnt
 work so that's one thing I am aiming to figure out and fix.

## Future Plans
 - Improved curving engine
 - Independent status of each line segment to avoid warping
 - Coordinate search bar
 - Max speed indicator based on the intensity of a curve

If you have any suggestions, don't be afraid to tell me because I am deeply in need of feedback. Also, don't expect that I will 
keep updating this everyday. I may only update a few times every week. This is a hobby project that I am willing to expand to satisfy
my needs and the needs of others who are in the same position as me.
