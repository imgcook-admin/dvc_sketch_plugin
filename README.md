# dvc_sketch_plugin

You can use this plugin to export the metadata of the sketch file and then use it for web layout (absolute)

### 

<img width="535" alt="screen shot 1" src="https://img.alicdn.com/tfs/TB1tKrivIbpK1RjSZFyXXX_qFXa-1340-850.png">
<img width="1291" alt="screen shot 2" src="https://img.alicdn.com/tfs/TB1dULkvFzqK1RjSZFoXXbfcXXa-1123-640.png">

## Installation

### From a release (simplest)

* [Download](https://github.com/mathieudutour/sketch-primitive/releases/latest) the latest release of the plugin
* Un-zip
* Double-click on primitive.sketchplugin


# export data example

``` json
{
  "type": "Block",
  "id": "Block-1",
  "__VERSION__": "2.0",
  "props": {
    "style": {
      "width": 702,
      "height": 200
    },
    "attrs": {
      "x": 0,
      "y": 0
    }
  },
  "children": [{
    "__VERSION__": "2.0",
    "props": {
      "style": {
        "width": 702,
        "height": 200,
        "backgroundColor": "rgba(255,255,255,1)",
        "borderRadius": 12
      },
      "attrs": {
        "x": 0,
        "y": 0
      }
    },
    "children": [],
    "type": "Shape",
    "id": "Shape-0"
  }, {
    "__VERSION__": "2.0",
    "props": {
      "style": {
        "width": 174,
        "height": 200
      },
      "attrs": {
        "x": 13,
        "y": 0,
        "source": "http://ai-sample.oss-cn-hangzhou.aliyuncs.com/test/FgxJZc5mQEWncoaunbI5kaf89crJ.png"
      }
    },
    "children": [],
    "type": "Image",
    "id": "Image-1"
  }, {
    "__VERSION__": "2.0",
    "props": {
      "style": {
        "width": 99,
        "height": 24,
        "fontFamily": "PingFangSC",
        "fontSize": "30",
        "color": "#FF5000",
        "lineHeight": "24rem",
        "fontWeight": 500
      },
      "attrs": {
        "x": 314,
        "y": 158,
        "text": "666.00",
        "fixed": false,
        "lines": 1
      }
    },
    "type": "Text",
    "id": "Text-5"
  }, {
    "__VERSION__": "2.0",
    "props": {
      "style": {
        "width": 20,
        "height": 20,
        "fontFamily": "PingFangSC",
        "fontSize": "20",
        "color": "#FF5000",
        "lineHeight": "20rem",
        "fontWeight": 500
      },
      "attrs": {
        "x": 294,
        "y": 162,
        "text": "￥",
        "fixed": false,
        "lines": 1
      }
    },
    "type": "Text",
    "id": "Text-7"
  }, {
    "__VERSION__": "2.0",
    "props": {
      "style": {
        "width": 164,
        "height": 26,
        "backgroundColor": "rgba(255,255,255,0.1)",
        "borderWidth": "1",
        "borderStyle": "solid",
        "borderColor": "#FF5000",
        "borderRadius": 4
      },
      "attrs": {
        "x": 215,
        "y": 56
      }
    },
    "children": [],
    "type": "Shape",
    "id": "Shape-9"
  }],
  "artboardImg": "http://ai-sample.oss-cn-hangzhou.aliyuncs.com/test/FmR0vOY7e5w_N5BQAE05HK5ulVmJ.png"
}
```
