[sch](https://www.google.com/search?q=chromeos+change+root+password)

from: https://github.com/chromebrew/chromebrew?tab=readme-ov-file#prerequisites

```
sudo chromeos-setdevpasswd
```

# After Powerwash the Root Password will be Reset!
on Boot, use VT "<Ctrl> + <Alt> + Refresh(F2)" to acces Developer Console:
login with: "root"

then change it with:
```
sudo chromeos-setdevpasswd
```

relation: https://support.google.com/chromebook/answer/6204310?hl=en
