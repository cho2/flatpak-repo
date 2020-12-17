# Flatpak Repo

## Chrome

```
wget https://blog.kukuh.syafaat.id/flatpak-repo/gpg/flatpak.gpg
flatpak remote-add chrome https://blog.kukuh.syafaat.id/flatpak-repo/google-chrome/repo --gpg-import=flatpak.gpg
flatpak install chrome com.google.Chrome
git clone git@github.com:cho2/eos-google-chrome-app.git
cd eos-google-chrome-app
chmod +x eos-google-chrome-app
./eos-google-chrome-app
```

## Kstars

```
wget https://blog.kukuh.syafaat.id/flatpak-repo/gpg/flatpak.gpg
flatpak remote-add kstars https://blog.kukuh.syafaat.id/flatpak-repo/kstars/repo --gpg-import=flatpak.gpg
flatpak install kstars org.kde.kstars
flatpak run org.kde.kstars
```

## Edge

```
wget https://blog.kukuh.syafaat.id/flatpak-repo/gpg/flatpak.gpg
flatpak remote-add edge https://blog.kukuh.syafaat.id/flatpak-repo/edge/repo --gpg-import=flatpak.gpg
flatpak install edge com.microsoft.Edge
flatpak run com.microsoft.Edge
```
