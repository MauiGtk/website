# MauiGtk website

The MauiGtk Community website/blog for documentations and promoting.

## Usage

### Requires

- Git
- Go
- Hugo extended
- npm

### Install Dependencies (on Debian)

```sh
wget https://github.com/gohugoio/hugo/releases/download/v0.152.2/hugo_extended_0.152.2_linux-amd64.deb
sudo dpkg -i hugo_extended_0.152.2_linux-amd64.deb)
```

```sh
sudo npm install -g sass
```

```sh
# Install tailwindcss
sudo npm install -g tailwindcss
```

### Copy Theme

```sh
cd themes
git clone https://github.com/opera7133/tella.git
```

### Run

```sh
npm i # Once
npm run start
```

<!--- 

thomiel:
    This didn't work for me.
    I think that some further submodules rituals have to be 
    performed in order to initialize them.
    (I don't like submodules anyway -- can we live without it? :)

### Build

### Update theme

```sh
git submodule update --remote --merge
```
-->

## License

[MIT](LICENSE)
