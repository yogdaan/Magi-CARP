# Magi-CARP
Community At Random Places 

The project is generic for any community to use. The project is wild idea by the ILUGD members for fun and colobration, but is available for anyone to fork and use it to their needs.
It uses Openstreet maps API and is forked from Sflc.in website and fsug.in website. 

**May the FOSS be with you!**



## Todo

* Use HTML5 semantic elements wherever possible
* QR sticker generator for the communities
* Image generation with a standard name (ulid)
* Pop up content function
* Marker function
* GeoJSON data
* License
* Consent by the uploader of the picture to be available in Creative Commons license.
* Picture credit option in the form while submitting.
* SEO optimisation



## Set up

This project is made for fun and uses simple HTML website with OSM API to render the map on the website.
Single page webapp.

Infrastructure:
* Github for hosting static htmls and js
* heroku for hosting or github only
* Github API, telegram API and Open Street Map API
* Recaptcha to prevent bot attacks
* Add disclaimer on the website, about using osm, google recaptcha and requiring github account to put the PR in queue.



## Contributing

Want to add any feature on the website or help us look more cool? Just create an issue for the same and request a merge for your pull request.



## How it works

* Create a PR directly on our github issue page or use the form on our website.
* Add the required details to put up the place, its cordinates, date and the event with the picture and upload.
* Submitting the form will create a POST request to the github issue with all the details filled in.
* This will create a PR on our issue which will merged once reviewed by the maintainers. 
* Once merged, the website will be updated with the image and map point for the location, ILUG-D marked its presence.
* One can use the telegram bot for the same that uses telegram bot API and github API



## Disclaimer

Uses OSM API, Telegram API, requires Github account, google recaptcha. If you want to create a request without any of these problem, share the email on our mailing list. We would be happy to help.



## LICENSE

GPLV3.0



## Future Plans

* Create a logo for magi-carp
* Magi-carp will highlight many communities on the single map. People can select the community and see their presence all over the world.
* Gallery section for all the communities in the world, takes the feed from all the communities gallery.
* Twitter feed from all the communities in india or world (can be extended to fsug.in).
