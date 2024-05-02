# AstraBun Photography Portfolio

## Software and License

This repository is built upon the open-source project originally created by [rampatra](https://github.com/rampatra/photography). 

### License

The original code from the [rampatra/photography](https://github.com/rampatra/photography) repository is licensed under the GNU General Public License (GPL). My modifications to the code remain under the GPL.

### Photographic Content License

The photographs featured in this portfolio are licensed under different terms. They are housed within the `images/` directory and are subject to the following terms as specified in the [LICENSE](images/LICENSE) file located in that directory:

```
Copyright (c) 2024, AstraBun
All rights reserved.
```

**These photographs may not be reused without express permission.**

## Quick Start

- Upload your pictures to `images/fulls` and `images/thumbs` directory.

## Run the website locally to test
1. `$ cd photography` - go to the project directory
2. `$ bundle install` - install gems
3. Change the `baseurl` in `_config.yml`
4. `$ bundle exec jekyll serve` - start/run the website

### Build the website
1. `$ cd photography` - go to the project directory
2. `$ npm install` - install all npm dependencies
3. `$ gulp` - minify css, js, resize images, etc.

Note: You only need to build the website if you make changes such as replacing the images, modifying the css styles, etc.
 
### Resize Images

- Install all dependencies by `$ npm install`
- Copy all your pictures (possibly jpg, the largest size available, straight from your camera) and put it inside `images` directory
- Run `$ gulp resize` to resize the images and to generate thumbnails automatically
- Push your changes
