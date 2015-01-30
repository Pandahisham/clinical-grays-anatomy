**grays-anatomy** adds Grays Anatomy image assets to your Clinical Meteor app.


------------------------
### Installation

First, install the grays-anatomy package from the command line, like so:

````
meteor add clinical:grays-anatomy
````



------------------------
### Default User Record Schema  

The user objects are have a fairly simple document schema that looks like the following:
````js
// schema
{
  name: String,
  image: String,
  thumbnail: String
}

// example
{
  name: 'abdominalArteries',
  image: '/packages/clinical_grays-anatomy/grays.anatomy.tiles/abdominalArteries.png',
  thumbnail: '/packages/clinical_grays-anatomy/grays.anatomy.thumbnails/abdominalArteries.png'
}
````

------------------------
### License

All images are in the public domain.  Code in MIT license.  
