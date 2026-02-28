# MauiGtk website

The MauiGtk Community website/blog for documentations and promoting, based on the [Tella theme](https://github.com/opera7133/tella).

## Usage

### Requires

- Git
- Go
- Hugo extended (from https://github.com/gohugoio/hugo/releases/)
- npm

#### Debian

```sh
# Hugo extended
wget https://github.com/gohugoio/hugo/releases/download/v0.153.5/hugo_extended_0.153.5_linux-amd64.deb
sudo dpkg -i hugo_extended_0.153.5_linux-amd64.deb

# npm
sudo apt-get update
sudo apt-get install npm
```

### Install submodules

```sh
# After cloned this repository
# Setup for submodule
git submodule update --init --recursive
# Install npm dependencies
npm i
```

### Run

```sh
npm run start
```

### Build

> [!note]
> Currently, this will break the layout supposedly due to an issue with the tello theme. But it is usually not necessary to run build. New content is added using the `npn run start` command.

```sh
npm run build
```

### Update theme

```sh
git submodule update --remote --merge
```

## License

[MIT](LICENSE)
