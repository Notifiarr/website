# Notifiarr

At this time, Notifiarr is not self hosted so this repo will be used for bug tracking and feature requests.

This is not something we are trying to get hundreds of thousands of users using, so you wont see it being announced or advertised. Use it if it is helpful, dont if it isn't! The info here is more of a quick high level overview, you can visit the site for full details or hop on Discord.

[![Discord chat](https://img.shields.io/discord/492590071455940612?style=flat-square&color=4051B5&logo=discord)](https://discord.gg/AURf8Yz)

## Purpose

This was built about 2 years ago for me and used by only me locally until about August of 2020 when I opened it up for others to use. My goal is to have a single location for common notification needs so i am not jumping around 20 apps to do things.

## Integrations

### *arr

* Lidarr
* Radarr
* Readarr
* Sonarr

### *arr Companions

* Bazarr
* Unpackerr

### Media Requests

* Lidarr
* Radarr
* Readarr
* Sonarr

### Media Management

* Jellyfin
* Plex

### Network

* Monitor any TCP/HTTP app on your network
* Snapshots

### Websites

* Better Uptime
* Website Monitoring (Native implementation)

### Misc

* Reddit subreddit
* Hotio: Pullio

This may not always be a full list, but covers most things at the time of posting.

## Some Features

* Fully configurable on what triggers to get notifications for. Each integration and many triggers in them can go to their own channels.
* Layout configuration for some notifications
* Content configuration for most notifications (color, content, etc)
* Media requests for all 4 *arr apps with user permissions, approvals, sonarr profiles, default options, show following options, etc
* Only port open that is needed is for the client to communicate with the site. No *arr apikeys or anything of the sort is used or saved on the site. All requests to the client are verified with your Notifiarr apikey and thrown out if they dont match up
* Automated continous add/sync for the custom formats TRaSH has made to use with Radarr
* A fully automated way to monitor all your Radarr collections with auto add new items to your library as they are put into the collection on TMDb for any monitored collections, etc
