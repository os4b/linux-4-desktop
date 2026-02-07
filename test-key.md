Tester une clé USB
> Trouver le nom de la clé
```
dmesg |grep removable
```

> Lancer Quemu
```
sudo apt install qemu-system-x86
sudo qemu-system-x86_64 -enable-kvm -m 2G -hda /dev/sdc
```
