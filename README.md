# termsize
Utility for limiting the terminal's scroll margin.

## Installation
```
git clone https://github.com/tovicheung/termheight
cd termheight
chmod +x termheight
mv termheight /usr/local/bin
cd ..
rm -rf termheight
```
one-liner:
```
git clone https://github.com/tovicheung/termheight && cd termheight && chmod +x termheight && mv termheight /usr/local/bin && cd .. && rm -rf termheight
```

## Usage

```
termsize <height>
```
Sets terminal scroll margin to provided value

```
termsize help
```
Shows help text

```
termsize reset
```
Resets terminal scroll margin to default