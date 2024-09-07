# The Map Group

The purpose of [**The Map Group**](https://www.flickr.com/groups/the-map-group/) is to generate maps for the members, containing their geo-tagged photos, and also a map for the group itself, containing the photos posted to the [group's pool](https://www.flickr.com/groups/the-map-group/pool/), by members or by owners of invited photos.

### Group's Map

The group's map contains a panel with links to each member's _Flickr_ photostream and shows the number of markers and photos that he or she added to the group.
Clicking on a marker it is possible to see the photo(s) taken on the corresponding location. Clicking on the photo thumbnail opens the photo's page on _Flickr_.

[![Group Map](https://live.staticflickr.com/65535/50277109767_97bc59c58b_b.jpg)](https://the-map-group.top/)

### Member's Map

The member's maps contain a panel with a list of all the countries where the member have taken photos and uploaded to _Flickr_. Clicking on the country makes the map zoom to it.
The markers have the same behaviour of the group's map.

[![Member Map](https://live.staticflickr.com/65535/50276281928_9817158c15_b.jpg)](https://the-map-group.top/people/hpfilho)

## Maps Generation

### Map Data

The maps data are generated using the script [FlickrMap](https://github.com/the-map-group/flickr-map). This script uses the [_Flickr API_](https://www.flickr.com/services/api/)
to get the photos data.

### Map Renderization

The maps are provided by [_Mapbox_](https://www.mapbox.com/), using its [_Mapbox GL JS API_](https://docs.mapbox.com/mapbox-gl-js/api/) to populate it with the markers data.

### Map Update

The maps are updated every day, starting at 03:00 (UTC -03:00). The update scripts are executed in a [Raspberry Pi 3](https://www.raspberrypi.com/products/raspberry-pi-3-model-b/) device, running a [Raspbian](https://www.raspbian.org/) Linux system.

### Map Code

The following languages are used to generate the data and build the maps:

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="top" src="https://github-readme-stats.anuraghazra1.vercel.app/api/top-langs/?username=haraldofilho&layout=compact&hide_title=true&hide=jupyter%20notebook&exclude_repo=FlickrTasks,FlickrMap,ShutterNotes,haraldoalbergaria.page,nos2viajando.net,haraldofilho.github.io,HaraldoFilho,boot_mail,disk_monitor,temperature_monitor,archived_android_apps,fedora_reinstall,github-readme-stats,Computer-Vision-Nanodegree,Deep-Learning-Nanodegree,Kotlin-Bootcamp,check_ip_changes,Artificial-Intelligence-Nanodegree,CS-Labs_Unicamp,Knapsack-Problem&card_width=900" />
</a>

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="top" src="https://github-readme-stats.vercel.app/api/top-langs/?username=the-map-group&layout=compact&hide_title=true&exclude_repo=flickr-map&card_width=900" />
</a>
