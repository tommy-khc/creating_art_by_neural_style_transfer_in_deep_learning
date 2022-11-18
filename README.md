# Creating Art by Neural Style Transfer in Deep Learning

This project is applying the style of drawing from an art piece to another by deep learning algorithm in Python.

## Motivation
This program is to visually have a taste of the power of deep leanring.

## Features

- Generating an image by blending two different images

## Build status

Project is completed

## Code style

[Google Python Style](https://google.github.io/styleguide/pyguide.html)

## Screenshots
Input </br>
Content Image </br>
![Content Image](https://user-images.githubusercontent.com/66003316/202600849-799fbac9-3966-4830-b766-042bfeace287.png) </br>
Style Image </br>
![Style Image](https://user-images.githubusercontent.com/66003316/202600906-543ffe77-54a1-4777-9662-01346b45369e.png) </br>
Output </br>
![output](https://user-images.githubusercontent.com/66003316/202601103-04d04241-5e8c-4b8d-bbde-8adc95902840.png) </br>

## Tech/framework used

**Built with**
- tensorflow

## How to use?

Choose two .jpg as input, one as content image, the other one as style image.
Style image is the image whose style would be transfer to content image.
Write the following code in main.ipynb.
```sh
content_path = '{path of content image}'
style_path = '{path of style image}'
target_path = '{path of output image}'
best_{output image name}, best_loss = run_style_transfer(content_path, style_path, num_iterations = 300)
Image.fromarray(best_{output image name}).save(target_path)
Image.fromarray(best_{output image name})
show_results(best_{output image name}, '{path of content image}', '{path of style image}')
```
It is a Jupyter Notebook. You can also read the code I wrote at block 76 to 78 as a demonstration.

## Credits
Thanks for providing art pieces, Tsz Wai, my friend in Hong Kong.

## License

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
