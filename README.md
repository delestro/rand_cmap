# rand_cmap
Creates a random colormap to be used together with matplotlib, useful for segmentation tasks. You may choose the first or last colors to be black. Also, two types of colormap can be generated, 'bright' and 'soft'

## Example:
<code>new_cmap = rand_cmap(100, type='bright', first_color_black=True, last_color_black=False, verbose=True)</code>

Number of labels: 100

![alt tag](http://i.imgur.com/QO2hzOA.png)

<code>new_cmap = rand_cmap(50, type='soft', first_color_black=False, last_color_black=True, verbose=True)</code>

Number of labels: 50

![alt tag](http://i.imgur.com/8CL9N0m.png)
