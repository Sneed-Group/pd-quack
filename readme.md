# Parallels Desktop *QUACK*

Crack for Parallels Desktop 18.0.1 破解版

##### ✅ - Support Intel

##### ✅ - Support Apple Silicon (M1 & M2)

##### ✅ - Network

##### ✅ - USB

###### 🎉EPIC🎉

# Usage

1. Install Parallels Desktop 18.0.1-53056.

    [https://download.parallels.com/desktop/v18/18.0.2-53056/ParallelsDesktop-18.0.2-53056.dmg](https://download.parallels.com/desktop/v18/18.0.1-53056/ParallelsDesktop-18.0.1-53056.dmg)
2. Exit parallels.

3. Download this repo file.

4. Extract and run Terminal in this directory.

5. `chmod +x ./install.sh && sudo ./install.sh`


# Manual

1. Exit Parallels Desktop

```
killall -9 prl_client_app
killall -9 prl_disp_service
```

2. Copy crack file

```
sudo cp -f prl_disp_service "/Applications/Parallels Desktop.app/Contents/MacOS/Parallels Service.app/Contents/MacOS/prl_disp_service"
sudo chown root:wheel "/Applications/Parallels Desktop.app/Contents/MacOS/Parallels Service.app/Contents/MacOS/prl_disp_service"
sudo chmod 755 "/Applications/Parallels Desktop.app/Contents/MacOS/Parallels Service.app/Contents/MacOS/prl_disp_service"
```

3. Copy licenses.json

```
sudo rm -f "/Library/Preferences/Parallels/licenses.json"
sudo cp licenses.json "/Library/Preferences/Parallels/licenses.json"
sudo chown root:wheel "/Library/Preferences/Parallels/licenses.json"
sudo chmod 444 "/Library/Preferences/Parallels/licenses.json"
```

4. Sign

```
sudo codesign -f -s - --timestamp=none --all-architectures --deep --entitlements ParallelsService.entitlements "/Applications/Parallels Desktop.app/Contents/MacOS/Parallels Service.app/Contents/MacOS/prl_disp_service"
```

# Notice

Parallels Desktop may upload client info or logs to server.

You can use a firewall block there domains.

Or use Hosts, AdGuardHome filter DNS resolve.

## BLOCK:

```
download.parallels.com
update.parallels.com
desktop.parallels.com
download.parallels.com.cdn.cloudflare.net
update.parallels.com.cdn.cloudflare.net
desktop.parallels.com.cdn.cloudflare.net
www.parallels.cn
www.parallels.com
reportus.parallels.com
parallels.com
parallels.cn
pax-manager.myparallels.com
myparallels.com
my.parallels.com
```


## HOSTS

```
0.0.0.0 download.parallels.com
0.0.0.0 update.parallels.com
0.0.0.0 desktop.parallels.com
0.0.0.0 download.parallels.com.cdn.cloudflare.net
0.0.0.0 update.parallels.com.cdn.cloudflare.net
0.0.0.0 desktop.parallels.com.cdn.cloudflare.net
0.0.0.0 www.parallels.cn
0.0.0.0 www.parallels.com
0.0.0.0 reportus.parallels.com
0.0.0.0 parallels.com
0.0.0.0 parallels.cn
0.0.0.0 pax-manager.myparallels.com
0.0.0.0 myparallels.com
0.0.0.0 my.parallels.com
```
