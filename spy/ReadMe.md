### This will break time synch
```
0.0.0.0 time.windows.com
```
### This will break internet detection:
```
0.0.0.0 www.msftconnecttest.com
0.0.0.0 dns.msftncsi.com
```
### This may break msStore:
```
0.0.0.0 a-0001.a-msedge.net
0.0.0.0 a-0002.a-msedge.net
0.0.0.0 a-0003.a-msedge.net
0.0.0.0 a-0001.dc-msedge.net
0.0.0.0 a-msedge.net
```

### This WILL break msStore:
```
0.0.0.0 store-images.s-microsoft.com
0.0.0.0 storecatalogrevocation.storequality.microsoft.com
0.0.0.0 storeedgefd.dsx.mp.microsoft.com
0.0.0.0 licensing.mp.microsoft.com
```

### This WILL trigger MS antivirus:
```
0.0.0.0 settings-win.data.microsoft.com
0.0.0.0 spynet2.microsoft.com
0.0.0.0 support.microsoft.com
0.0.0.0 wdcp.microsoft.com
```
