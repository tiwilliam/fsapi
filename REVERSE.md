# List of reverse engineered calls

## Update service

```
http://update.wifiradiofrontier.com/FindUpdate.aspx
    ?mac=1122334455
    &customisation=ir-mmi-FS2026-0500-0052
    &version=2.6.17.EX53300-2RC3
```

## FSAPI

```
/device

/fsapi/GET_NOTIFIES

/fsapi/GET/netRemote.nav.state

/fsapi/LIST_GET_NEXT/netRemote.sys.caps.eqBands/-1?maxItems=100
/fsapi/LIST_GET_NEXT/netRemote.sys.caps.validModes/-1?maxItems=100
/fsapi/LIST_GET_NEXT/netRemote.sys.caps.dabFreqList/-1?maxItems=100
/fsapi/LIST_GET_NEXT/netRemote.sys.caps.eqPresets/-1?maxItems=100

/fsapi/GET/netRemote.sys.caps.volumeSteps
/fsapi/GET/netRemote.sys.caps.fmFreqRange.lower
/fsapi/GET/netRemote.sys.caps.fmFreqRange.upper
/fsapi/GET/netRemote.sys.caps.fmFreqRange.stepSize

/fsapi/GET/netRemote.sys.mode
/fsapi/GET/netRemote.sys.power
/fsapi/GET/netRemote.sys.lang
/fsapi/GET/netRemote.sys.info.radioId
/fsapi/GET/netRemote.sys.info.version
/fsapi/GET/netRemote.sys.info.friendlyName

/fsapi/GET/netRemote.sys.audio.mute
/fsapi/GET/netRemote.sys.audio.volume
/fsapi/GET/netRemote.sys.audio.eqPreset
/fsapi/GET/netRemote.sys.audio.eqLoudness
/fsapi/GET/netRemote.sys.audio.eqCustom.param0
/fsapi/GET/netRemote.sys.audio.eqCustom.param1

/fsapi/GET/netRemote.sys.net.ipConfig.dhcp
/fsapi/GET/netRemote.sys.net.ipConfig.address
/fsapi/GET/netRemote.sys.net.ipConfig.subnetMask
/fsapi/GET/netRemote.sys.net.ipConfig.gateway
/fsapi/GET/netRemote.sys.net.ipConfig.dnsPrimary
/fsapi/GET/netRemote.sys.net.ipConfig.dnsSecondary

/fsapi/GET/netRemote.sys.net.wired.interfaceEnable
/fsapi/GET/netRemote.sys.net.wired.macAddress

/fsapi/GET/netRemote.sys.net.wlan.interfaceEnable
/fsapi/GET/netRemote.sys.net.wlan.macAddress
/fsapi/GET/netRemote.sys.net.wlan.connectedSSID
/fsapi/GET/netRemote.sys.net.wlan.setEncType
/fsapi/GET/netRemote.sys.net.wlan.setAuthType
/fsapi/GET/netRemote.sys.net.wlan.rssi

/fsapi/GET/netRemote.play.caps
/fsapi/GET/netRemote.play.repeat
/fsapi/GET/netRemote.play.status
/fsapi/GET/netRemote.play.frequency
/fsapi/GET/netRemote.play.serviceIds.ecc
/fsapi/GET/netRemote.play.serviceIds.fmRdsPi
/fsapi/GET/netRemote.play.scrobble
/fsapi/GET/netRemote.play.shuffle
/fsapi/GET/netRemote.play.info.name
/fsapi/GET/netRemote.play.info.text

/fsapi/GET/netRemote.nav.action.dabScan
```
