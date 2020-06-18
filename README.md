# Exploring-the-matplotlib-to-create-animations
Jupyter notebook, animations, python, matplotlib

Animations are an interesting way of demonstrating a phenomenon. We as humans are always enthralled by animated and interactive charts rather than the static ones. Animations make even more sense when depicting time series data like stock prices over the years, climate change over the past decade, seasonalities and trends since we can then see how a particular parameter behaves with time.

Matplotlib's animation base class deals with the animation part. It provides a framework around which the animation functionality is built. There are two main interfaces to achieve that using:

* `FuncAnimation` Makes an animation by repeatedly calling a function func.

However,  out of the two, FuncAnimation is the most convenient one to use. You can read more about them in the documentation since we will only concern ourselves with the FuncAnimation tool.

## Requirements

Modules including 'numpy' and 'matplotlib' should be installed.
To save the animation on your system as mp4 or gif imagemagick](https://sourceforge.net/projects/imagemagick/files/) is required to be installed.

![Wave](https://user-images.githubusercontent.com/54144435/84998111-4f553500-b147-11ea-8266-0406e680629a.gif)

![celluloid](https://user-images.githubusercontent.com/54144435/84998224-77449880-b147-11ea-9c92-8d310a035e1b.gif)

![celluloid2](https://user-images.githubusercontent.com/54144435/84998272-862b4b00-b147-11ea-8ec2-ebbba2a1956f.gif)

![coil](https://user-images.githubusercontent.com/54144435/84998308-90e5e000-b147-11ea-83cf-ef5bf37ff250.gif)

![MagicTriangle](https://user-images.githubusercontent.com/54144435/84998341-9b07de80-b147-11ea-882c-04c61f343119.gif)

These few above animations are from ipynb file.The above image is a simulation of Rain and has been achieved with Matplotlib library which is fondly known as the grandfather of python visualization packages. Matplotlib simulates raindrops on a surface by animating the scale and opacity of 50 scatter points. Today Python boasts of a large number of powerful visualisation tools like Plotly, Bokeh, Altair to name a few. These libraries are able to achieve state of the art animations and interactiveness. Nonetheless, the aim of this article is to highlight one aspect of this library which isn’t explored much and that is Animations and we are going to look at some of the ways of doing that.
