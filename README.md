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

adb -s 192.168.1.4 shell pm revoke com.axis.net android.permission.RECEIVE_BOOT_COMPLETED
```bash
adb -s 192.168.1.4 shell pm revoke com.axis.net android.permission.RECEIVE_BOOT_COMPLETED
```



adb -s 192.168.1.4 shell pm list packages -d | grep com.axis.net
```bash
adb -s 192.168.1.4 shell pm list packages -d | grep com.axis.net
```

adb -s 192.168.1.4 shell pm disable-user com.axis.net
```bash
adb -s 192.168.1.4 shell pm disable-user com.axis.net
```

## menonaktifkannya di user tertentu
adb -s 192.168.1.4 shell pm disable-user --user 10 com.axis.net
```bash
adb -s 192.168.1.4 shell pm disable-user --user 10 com.axis.net
````

adb -s 192.168.1.4 shell pm enable com.axis.net
```bash
adb -s 192.168.1.4 shell pm enable com.axis.net
```
