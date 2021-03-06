## ttnctl devices register personalized

Create or update ABP registrations on the Handler

### Synopsis


ttnctl devices register personalized creates or updates an ABP
registration on the Handler

```
ttnctl devices register personalized [DevAddr] [NwkSKey] [AppSKey]
```

### Options

```
      --relax-fcnt   Allow frame counter to reset (insecure)
```

### Options inherited from parent commands

```
      --app-eui string              The app EUI to use
      --config string               config file (default is $HOME/.ttnctl.yaml)
      --mqtt-broker string          The address of the MQTT broker (default "staging.thethingsnetwork.org:1883")
      --ttn-account-server string   The address of the OAuth 2.0 server (default "https://account.thethingsnetwork.org")
      --ttn-handler string          The net address of the TTN Handler (default "staging.thethingsnetwork.org:1782")
      --ttn-router string           The net address of the TTN Router (default "staging.thethingsnetwork.org:1700")
```

### SEE ALSO
* [ttnctl devices register](ttnctl_devices_register)	 - Create or Update registrations on the Handler

###### Auto generated by spf13/cobra on 20-May-2016
