# Frontier Silicon API for Python

Only tested with Agron iNet 3+ and latest firmware.

## Example Usage

```python
services = ssdp.discover('urn:schemas-frontier-silicon-com:argon_001:fsapi:1')
if not len(services):
    print 'No server found on network'
    sys.exit(1)

fs = FSAPI(services[0].location, 123)

fs.volume = 12
fs.mode = 'dab'
fs.power = True

print 'Name: %s' % fs.friendly_name
print 'Version: %s' % fs.version
print 'Mute: %s' % fs.mute
print 'Mode: %s' % fs.mode
print 'Power: %s' % fs.power
print 'Volume: %s' % fs.volume
print 'Play status: %s' % fs.play_status
print 'Track name: %s' % fs.play_info_name
print 'Track text: %s' % fs.play_info_text
```
