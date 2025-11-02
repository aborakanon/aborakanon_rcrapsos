# aborakanon_rcrapsos

adb -s 192.168.1.4 shell dumpsys package moe.shizuku.privileged.api | grep "WRITE_SECURE_SETTINGS"
```bash
adb -s 192.168.1.4 shell dumpsys package moe.shizuku.privileged.api | grep "WRITE_SECURE_SETTINGS"
```

adb -s 192.168.1.4 shell pm list users -v
```bash
adb -s 192.168.1.4 shell pm list users -v
```

adb -s 192.168.1.4 shell pm list permissions -g | grep "WRITE_SECURE_SETTINGS"
```bash
adb -s 192.168.1.4 shell pm list permissions -g | grep "WRITE_SECURE_SETTINGS"
```
