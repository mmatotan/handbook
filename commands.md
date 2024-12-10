### Download file via SSH
```
scp -P port user@ip_add:file_path_on_server .
```

### neovim appimage
```
mv nvim.appimage nvim
chmod +x nvim
sudo chown root:root nvim
sudo mv nvim /usr/bin
mkdir -p ~/.config/nvim
```

### openpn
```
openvpn3 config-import --config file.ovpn
openvpn3 configs-list
sudo openvpn3 session-start --config ovpn_config.ovpn
sudo openvpn3 sessions-list
```
