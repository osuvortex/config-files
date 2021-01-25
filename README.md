this is the config and db used by osu!vortex. you can use these to setup your own server. but nothing will work right out of the bat. 
you must modify them according to your own domain and your setup.

generate 2 api keys. they will be used for peppy-lets and api-hanayo.
replace ci-key in peppy-config.ini and lets-config.py. make sure they are the same.
now replace hanayo-key in api.conf and hanayo.conf. again make sure they are the same.

get a api key from osu! and replace osu-api-key with that.

copy lets-config.py to lets/helpers/config.py and peppy-config.ini to peppy/config.ini . also don't forget to copy api.conf and hanayo.conf to their folders
now modify your the domains etc. 
