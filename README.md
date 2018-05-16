# Welcome

Welcome to the Maker Map - World Map of the World's Makers.

I'm mostly interested in wood working so that is where I'm starting. I also like metal work and fabrication.
Anything that you would find at a Maker Faire or Makers Central is a good fit. I like tools too.

I'm from New Zealand so I love and support local guys - the maps starts down under. 

### Why?
For the longest time thought there were only two New Zealand channels:
- Joey Chalk @ KingPost TimberWorks
- Tim Lee @ The Offcut

Next I discovered Aussie:
- Vic @ DownUnderWoodWorks


These three are my favourites (still) but there are a whole heap more Aus/NZ channels.
When I started my own channel [Takami Woodshop](https://www.youtube.com/channel/UCHQSI_bZ8xYy0hva1J-_U9g), 
I started developing a _mental_ map of everyone's physical location in the world. This _real_ map is just ... for my amusement ... and I hope you like it too.

### The Map
You can see the map here - go on and check it out: [Maker Map (*beta)](https://trautvetter.github.io/maker-map/map.html)

# Additions and changes to the map
### New channels
New channels can be added of course. That's what I want the most. Not limited to Aus/NZ. 

If you know of a channel that isn't on the map just head over to [my YouTube channel](https://www.youtube.com/channel/UCHQSI_bZ8xYy0hva1J-_U9g)
and post a comment with the details (see guidelines below).

### Edits & corrections
If I have you wrong let me know over at [my YouTube channel](https://www.youtube.com/channel/UCHQSI_bZ8xYy0hva1J-_U9g)
and post a comment with the details (see guidelines below).

### Delete me
If you want to be removed from the map just let me know with a comment at [my YouTube channel](https://www.youtube.com/channel/UCHQSI_bZ8xYy0hva1J-_U9g).

### Map info guidelines
1. It's a map - so a location is required. As close as you are comfortable with but no exact addresses please. 
This isn't a 'guide map' for tool thieves. Choose a public area or a river or something near your place.
2. Name: can be real, pseudo, full, partial, or just channel name.
3. Label: optional - two initials to go on your map marker. 

**The best way** is to head over to [http://geojson.io](http://geojson.io/#new) and "Draw a marker". Then send me the JSON - it looks 
like this - you'll need to manually add the properties section entries. **Important - don't drop the marker on your _house_ - see above.
```markdown
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {
         "ytChannelId": "UCFfX6eWhulmrTEhMbXYhZMA",
          "name": "Joe Bloggs - My Awesome Channel",
          "markerLabel": "JB"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          169.8046875,
          13.239945499286312
        ]
      }
    }
  ]
}
```
**Another way** is just to send me the information - the coordinates are easy to get on [https://www.google.com/maps](Google Maps) ... right click on 
the location, select "What's here?" and copy from the box that appears at the bottom.

**Git savvy?** add to map-data.json, and throw me a pull request.
