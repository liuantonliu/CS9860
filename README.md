# CS9860
- investigated different models - no real difference due to sequential layers
- investigate different style and content layers next, also different amount of style layers
- try with different types of data, swap style and content pictures around

- future: cycleGAN

# training sets:
## baseline: vgg19, content_layers = ['conv_4'], style_layers = ['conv_1', 'conv_2', 'conv_3', 'conv_4', 'conv_5'], epoch = 50

## different models (also no difference)
vgg16, vgg19, squeezenet, alexnet

## different epochs
10, 20, 50, 100, 200

## different content layers (even though they make no difference)
- ['conv_1']
- ['conv_4']
- ['conv_10']
- ['conv_1', 'conv_2', 'conv_3', 'conv_4', 'conv_5']

## different level of style layers
- ['conv_1', 'conv_2', 'conv_3', 'conv_4', 'conv_5']
- ['conv_3', 'conv_4', 'conv_5', 'conv_6', 'conv_7']
- ['conv_5', 'conv_6', 'conv_7', 'conv_8', 'conv_9']
  
## different amount of style layers
- ['conv_1', 'conv_2', 'conv_3', 'conv_4', 'conv_5']
- ['conv_1', 'conv_2', 'conv_3', 'conv_4', 'conv_5', 'conv_6', 'conv_7', 'conv_8', 'conv_9']
- ['conv_1']
- ['conv_5']
