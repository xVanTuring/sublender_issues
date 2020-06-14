# Sublender Doc
![Imgur](https://i.imgur.com/wsiMWIQ.jpg)
* [Installation](./installation.md)
* [Preference](./preference.md)
* [Sublender Panel](./sublender.md)
* [Material & Workflow](./workflow.md)

### Known issues
* undo crash when in Eevee preview mode with Auto Live Update enabled(caused by blender's undo system)
### Q&A
* Normal Format
> By default substance will generate Normal Map with DirectX Format, which is not compatible with Blender(OpenGL Format) Here is two thing you can do:
1. Change Normal Format Option Provided by sbsar \
![Normal Format](https://i.imgur.com/CHZ2RAj.png)
2. manually convert to OpenGL from DirectX \
![Convert](https://i.imgur.com/yem5RkV.png)


* Q: How to duplicate a substance instance
> A: simple duplicate the material in you material tab, change the name and then click the 
> `Apply workflow` button.
* Q: where is image texture stored?
> A: If you saved you blender file, sublender will create a folder named
with name of your blender file in the same directory of your blender file, otherwise it will save image texture to a temp folder provided by system

* Q: when will a video tutorial be made?
> A: I suck at English, can't speak it fluently. I will try
my best to make one asap.
