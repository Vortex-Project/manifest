<div align="center"><img src="https://gitlab.com/proyecto-vortex/manifest/raw/pie/snippets/new_vortex_logo.png" alt="" /></div>

# Vortex Project #

Introduction
---------------

It is a project designed with the idea of ​​keeping everything clean and simple. Without neglecting the necessary updates to maintain a stable, secure and fast system. 
At the moment this work is only thought to work with the specific model that you want to compile. Characteristics of other rom of the community have been selected, which are grateful for their contribution. (See credits)


### Sync ###

```bash

# Initialize local repository
repo init -u https://gitlab.com/proyecto-vortex/manifest -b pie

# Sync
repo sync  --force-sync --current-branch --no-tags --no-clone-bundle --optimized-fetch --prune -j$(nproc --all)
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Build the code
$ brunch device-codename
```

Credits
---------------

- PixelExperience
- Evolution X
- Havoc OS
- Bootleggers ROM
- ABC ROM
- AOSiP
- OMNI ROM
- Nitrogen OS
- nysadev
- kjjjnob
- Luis Chaves
- And to anyone who has crossed on my way and offered their help, thanks!
