## ttnctl

Control The Things Network from the command line

### Synopsis


ttnctl controls The Things Network from the command line.

### Options

```
      --app-eui string              The app EUI to use (default "0102030405060708")
      --config string               config file (default is $HOME/.ttnctl.yaml)
      --mqtt-broker string          The address of the MQTT broker (default "localhost:1883")
      --ttn-account-server string   The address of the OAuth 2.0 server (default "https://account.thethingsnetwork.org")
      --ttn-handler string          The net address of the TTN Handler (default "0.0.0.0:1782")
      --ttn-router string           The net address of the TTN Router (default "0.0.0.0:1700")
```

### SEE ALSO
* [ttnctl applications](ttnctl_applications)	 - Show applications
* [ttnctl devices](ttnctl_devices)	 - Manage devices on the Handler
* [ttnctl downlink](ttnctl_downlink)	 - Send downlink messages to the network
* [ttnctl join](ttnctl_join)	 - Send a join requests to the network
* [ttnctl subscribe](ttnctl_subscribe)	 - Subscribe to uplink messages from a device
* [ttnctl uplink](ttnctl_uplink)	 - Send uplink messages to the network
* [ttnctl user](ttnctl_user)	 - Show the current user
* [ttnctl version](ttnctl_version)	 - Get build and version information

###### Auto generated by spf13/cobra on 2-Apr-2016