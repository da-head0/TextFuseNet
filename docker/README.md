# TextFuseNet Docker
## Requirements
- docker with Nvidia GPU Support
- docker-compose

## Config
You can configure the paths and models in the [.env](.env) file.
I would recommend trying it with the default settings before.

## Installation
1. Download models as described in [here](models/README.md) (Default: model_ic15_r101.pth).
2. Add some image files to the [input_images](../input_images) folder. (JPG format)
3. Run
```docker-compose up --force-recreate``` in this directory.
4. You can find the processed images the [output_images](output_images) directory.