### Clone
```sh
git clone --recursive https://github.com/avenaradio/esp_with_osc_test.git
```

### Configure WiFi

```sh
idf.py menuconfig
```

In the `Example Configuration` menu:

* Set the Wi-Fi configuration.
    * Set `WiFi SSID`.
    * Set `WiFi Password`.

### Build and Flash
```sh
# Activate enviroment
export IDF_PATH="$HOME/.espressif/v5.3.5/esp-idf"
source "$IDF_PATH/export.sh"

# Full build flash monitor
idf.py build flash monitor
```
