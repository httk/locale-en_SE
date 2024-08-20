# locale en_SE

Locale definition file: English locale for Sweden

Typical installation:
```
cp en_SE /usr/share/i18n/locales/.
sudo localedef -i en_SE -f UTF-8 en_SE.UTF-8
echo "en_SE.UTF-8 UTF-8" | sudo tee -a "/etc/locale.gen"
sudo locale-gen
sudo update-locale LANG=en_SE.UTF-8
```
