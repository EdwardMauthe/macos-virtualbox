# for cygwin set PATH to
### need cmd.exe
PATH=$PATH:/cygdrive/c/windows/system32
### need vboxmanage.exe
PATH=$PATH:"/cygdrive/c/Program Files/Oracle/VirtualBox"
### if on a newer CPU
vboxmanage modifyvm "macOS" --cpu-profile "Intel Core i7-3960X"

# disk size all VDI 80GB (dynamically allocated)
## 10.15 (new install)
23.8GB
