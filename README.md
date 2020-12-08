# LG-34BK95U Monitor Fix
LG 34BK95U

This patch adds hi-dpi scaled resolutions for LG34BK95U Monitor. 

Usage:

Enter Recovery mode and disable csrutil:

```
csrutil disable
```

Make system directory writeable:

```
sudo mount -uw /
```

Then:

```
sudo cp ~/Downloads/DisplayProductID-7721 /System/Library/Displays/Contents/Resources/Overrides/DisplayVendorID-1e6d/DisplayProductID-7721

```
