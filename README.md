OpenWRT package for VyprVPN

To use these packages you need to add this feed to your openwrt feeds list dy adding following line in openwrt_source_tree/feeds.conf.default file: src-git vpn https://github.com/scherbenokk/vpn.git

Update/download all feeds: ./scripts/feeds update

Install all (-a) packages from this feed (-p) vpn: ./scripts/feeds install -a -p vpn

Then select needed packages in menuconfig and make the firmware.
