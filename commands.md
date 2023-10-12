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
