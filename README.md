
<!-- README.md is generated from README.Rmd. Please edit that file -->

# logos-stickers

<!-- badges: start -->
<!-- badges: end -->

Logos & stickers for our club!

## hex sticker

``` r
library(cowplot)
library(here)
library(hexSticker)

teal <- '#008c8c'
white <- '#FFFFFF'
dang_square <- here('input', 'sticker_11.png')
img <- ggdraw() +
    draw_image(dang_square)

sticker(img, package = '',
        s_x = 1, s_y = 1, s_width = 1.55, s_height = 1.55,
        h_fill = white, h_color = teal,
        filename = here('output', 'hex-sticker-1.png'))
```
