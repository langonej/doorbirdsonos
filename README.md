# Project Title

Integrate Doorbird into Sonos.  Push Doorbird button on the doorbell and have a doorbell chime .mp3 play on Sonos in a given room or zone.

## Getting Started

1) Configure DoorBird app to make an HTTP call to the URL in the [get] node ( eg 192.168.91.11:1880/doorbird )
2) Schedule the HTTP call in the Doorbird app to ALWAYS make the call any time of day
3) Configure your SONOS end points
4) Configure your doorbill chime mp3/playlist
5) You can test by hitting the URL directly and it should play the doorbell chime
6) Then test with hitting the actual button on the DoorBird

### Prerequisites

Functioning Node-RED, Doorbird, and Sonos.  Using OpenHab2 here as inventory management but could do calls directly to Sonos as well.

## Authors

* Jason Langone
