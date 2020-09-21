# VGO2 Parameter Viewer

This is a viewer that displays the parameters in the VGO2 file.

![image1](https://github.com/izayoijiichan/vgo2.parameter.viewer/blob/master/images/screenshot_1.png)
![image2](https://github.com/izayoijiichan/vgo2.parameter.viewer/blob/master/images/screenshot_2.png)
![image3](https://github.com/izayoijiichan/vgo2.parameter.viewer/blob/master/images/screenshot_3.png)
![image4](https://github.com/izayoijiichan/vgo2.parameter.viewer/blob/master/images/screenshot_4.png)
![image5](https://github.com/izayoijiichan/vgo2.parameter.viewer/blob/master/images/screenshot_5.png)

## Description

Reads the specified VGO2 file and displays VGO2 information.

## Requirement

- Windows 10
- .NET Framework 4.5
- Newtonsoft.Json.dll 12.0

## Installation

Download exe and place it anywhere.

## Usage

1. Launch exe.
2. Specify VGO file.
    - Press the 'Open File' button and select the file in the dialog.
    - Drag and drop the VGO file onto the form.
    - Specify the path to the VGO file with command line arguments at startup.

## Implementation

- assetInfo
  - generator
  - right
  - extensions (unimplemented)
  - extensionsUsed

- layout
  - nodes
    - animator
      - humanAvatar (unimplemented)
    - rigidbody
    - colliders
      - collider
    - skybox (unimplemented)
    - light
    - right
  - skins
  - meshes
  - materials
  - textures
  - particles (unimplemented)
  - extensions (unimplemented)

## Data schema description

- [Asset Info](https://github.com/izayoijiichan/VGO2/blob/master/Documentation~/VGO/instructions/schema.assetInfo.json.md)
- [Layout](https://github.com/izayoijiichan/VGO2/blob/master/Documentation~/VGO/instructions/schema.layout.json.md)
- [Layout (particle)](https://github.com/izayoijiichan/VGO2/blob/master/Documentation~/VGO/instructions/schema.layout.particle.json.md)
- [Resource](https://github.com/izayoijiichan/VGO2/blob/master/Documentation~/VGO/instructions/schema.resource.json.md)

## JSON specification

- VGO JSON Schema: [2.0](https://github.com/izayoijiichan/VGO2/tree/master/Documentation~/VGO/specification/2.0/schema)

## Link
- [VGO2](https://github.com/izayoijiichan/VGO2)
- [VGO Hub](https://vgohub.azurewebsites.net)
