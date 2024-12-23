<div align="center">
    <img alt="Image" src="assets/icon.png" width="128"/>
    <h3 align="center">README template</h3>
    <img alt="Version" src="https://img.shields.io/github/v/release/mekb-turtle/readme-template?style=flat&logoColor=f5c2e7&labelColor=1e1e2e&color=f5c2e7" />
    <img alt="Stars" src="https://img.shields.io/github/stars/mekb-turtle/readme-template?style=flat&logoColor=f5c2e7&labelColor=1e1e2e&color=f5c2e7" />
    <img alt="License" src="https://img.shields.io/github/license/mekb-turtle/readme-template?style=flat&logoColor=f5c2e7&labelColor=1e1e2e&color=f5c2e7" />
</div>

---
<br/>

<img alt="Preview" src="assets/preview.png"/>

## About The Project
Generic description of project

## Features
- Feature 1
- Feature 2

## Dependencies
- `example-dependency-1`
- `example-dependency-2`

<br />

## Installing
### Arch-based
If you use an AUR helper, use it instead, e.g `paru -S example` or `paru -S example-git`
```bash
git clone https://aur.archlinux.org/example # use example-git instead for latest commit
cd example
makepkg -si
```

### Debian-based
```bash
sudo apt install build-essential meson example-dependency-1 example-dependency-2
```
Then follow the instructions below

### Other distros
Find [dependencies listed above](#dependencies) in your package manager or elsewhere:

```bash
git clone https://github.com/mekb-turtle/readme-template.git
cd readme-template
git checkout "$(git describe --tags --abbrev=0)" # checkout to latest tag, omit for latest commit
meson setup build
meson install -C build
```

