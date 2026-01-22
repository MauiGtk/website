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
wget https://github.com/gohugoio/hugo/releases/download/v0.153.5/hugo_extended_0.153.5_linux-amd64.deb
sudo dpkg -i hugo_extended_0.153.5_linux-amd64.deb
sudo apt-get update
sudo apt-get install npm
sudo npm install -g sass
```

### Tailwind & Submodules

```sh
# Install tailwindcss
sudo npm install -g tailwindcss
npm install -D @tailwindcss/cli  # CLI no longer included in Tailwind 4

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

```sh
npm run build
```

### Update theme

```sh
git submodule update --remote --merge
```

## License

[MIT](LICENSE)
