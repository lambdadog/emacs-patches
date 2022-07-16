# Collection of patches for emacs
Patches for my personal use, all based on emacs master.

## [`display-line-numbers-pad.patch`](./patches/display-line-numbers-pad.patch)
Adds a customization variable (`display-line-numbers-pad`) which adds
a single space as padding following the line number. Essentially
`left-margin-width` but after the line numbers (when
`display-line-number-mode` is enabled).

![An image displaying `display-line-numbers-pad` being set to `t`](./images/display-line-numbers-pad.png)
