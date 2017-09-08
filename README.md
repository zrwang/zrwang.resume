# For installing the missing font
## Ubuntu 14.04

```bash
upzip garamond.zip
sudo mkdir /usr/local/texlive/2016/texmf-dist/fonts/type1/urw/garamond
sudo cp ~/Download/garamond/*.pfb /usr/local/texlive/2016/texmf-dist/fonts/type1/urw/garamond
sudo -H mktexlsr
```

## Ubuntu 16.04

```bash
sudo mkdir /usr/share/texlive/texmf-dist/fonts/type1/urw/garamond
cd /usr/share/texlive/texmf-dist/fonts/type1/urw/garamond
sudo cp ~/Downloads/garamond/*.pfb ./
sudo -H mktexlsr
```

