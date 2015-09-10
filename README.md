# rand_cmap
Creates a random colormap to be used together with matplotlib, useful for segmentation tasks. You may choose the first or last colors to be black. Also, two types of colormap can be generated, 'bright' and 'soft'. On both cases, the generated colors are restricted to never be too bright or too dark.

**keywords**: *python, ipython, matplotlib, plt, color map, random, colors, segmentation*

## Examples:

### Bright colors

Generating a colormap for 100 labels, with first as black

<code>new_cmap = rand_cmap(100, type='bright', first_color_black=True, last_color_black=False, verbose=True)</code>


![alt tag](http://i.imgur.com/QO2hzOA.png)

### Soft colors

Generating a colormap for 50 labels, with last as black

<code>new_cmap = rand_cmap(50, type='soft', first_color_black=False, last_color_black=True, verbose=True)</code>

![alt tag](http://i.imgur.com/8CL9N0m.png)
