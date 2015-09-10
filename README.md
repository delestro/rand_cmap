# rand_cmap
Creates a random colormap to be used together with matplotlib. Useful for segmentation tasks

<pre>
param nlabels: Number of labels (size of colormap)
param type: 'bright' for strong colors, 'soft' for pastel colors
param first_color_black: Option to use first color as black, True or False
param last_color_black: Option to use last color as black, True or False
param verbose: Prints the number of labels and shows the colormap. True or False
return: colormap for matplotlib
</pre>

## Example:
<code>
new_cmap = rand_cmap(100, type='bright', first_color_black=True, last_color_black=False, verbose=True)
</code>
