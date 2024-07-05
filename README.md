# codespaces-desktop
websockify --web=/usr/share/novnc/ 6080 localhost:5900
sudo qemu-system-x86_64 -enable-kvm -cdrom ubuntu.iso -boot menu=on -drive file=Image.img -m 46 -cpu host -vga virtio -display vnc=127.0.0.1:0