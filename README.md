# yocto-ai-drone
Yocto project for AI drone

## Quick Start

1. Get the code using the Manifest and Repo tool:  
     <https://source.android.com/setup/develop/repo>  

```
$ mkdir ~/yocto-ai-drone && cd ~/yocto-ai-drone
$ repo init -u https://github.com/lukemech/yocto-ai-drone_manifest.git -b master
$ repo sync
```

2. Run "source ./oe-init-build-env" to setup bitbake environment
3. Run "bitbake core-image-minimal" to build the images
4. Flash the generated "build/tmp/deploy/\<MACHINE\>/update.img" to your device
5. Boot your device and enjoy it
