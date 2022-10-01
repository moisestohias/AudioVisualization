# What is this?
## The is a collection kind like the (awesome)[https://github.com/sindresorhus/awesome] stuff. That specifically focuses on audio visualization, mostly on fast and headless tools and libraries.

### Just to give a bit of context, -TF u saying, you must rephrase this -
There are three visualization sources:
    + Wave form: Direct representation of the audio samples.
    There are some important details in here that can be implemented to provide a better visualization. Which is detecting the fundamental frequency of the loudest sound present, and using this information to adjust the sync window, so the wave form
    + STFFT: this is the main audio transformation, it naturally spits the spectrometer, we can represent it in different ways:
        + spectrogram: is the natural output of the STFFT, most of the time we apply a log scale to get a better representation that reflect how we perceive sound, we can apply different color map, and we also can be more creative by representing the spectrogam in 3D (cool).
        + spectrum: we represent the FFT of a window at time resulting in what's called spectrum, putting the spectrum of the windows consecutively we get a moving spectrum that reflect the sound at the giving time.


#### This collection tries to focus on compiled Languages tools, so the following are either not discussed or not in details at least:
+ JavaScript base visualizers: although the visual flair that you can do with JS can be astonishing, they all run either in the browser or in a canvas, and not portable.
+ After effect:  Not discussed here but: videobolt.net/templates/music-visualization
+ Blender or any of the GUI tools (Although blender and Houdini are great tools)
+ Unity/C#: youtube.com/c/PeerPlay/playlists
+ FL studio zgameeditor: Is an audio visualization tool that ship with FL-Studio producer version (I guess), it's powerful, clunky TBH, Not super flexible, but it has a steep learning rate, requires some talent and time to get good versatile results. .
youtube.com/channel/UCV4oqyhk2L9HvOfjlraNtEQ/videos


+ (synesthesia)[http://www.synesthesia.live/]: 
+ (MilkDrop)[http://www.geisswerks.com/about_milkdrop.html] No need for definition
+ (ProjectM)[https://github.com/projectM-visualizer/projectm]: 
open-source cross-platform reusable library for audio visualization
    + Stand Alone: get input from Mic or system's audio

+ (Butterchurn) [github.com/jberg/butterchurn]: 
A WebGL implementation of the Milkdrop Visualizer

+ plane9: The visualizer can be used either as standalone window, screensaver, oculus rift or HTC Vive VR visualizer. It is sound sensitive and reacts to what your currently listening to, be it from spotify, iTunes or any another sound source, it can even react to what you record from a microphone or other input.
It uses OpenGL meaning you can expect all the psychodalic pattern, you are familiar with from old WinMap and windows media player, but a lot more.
 plane9.com/

+ vzx-visualizer: similar to plane9, but with a lot more features, that allows you to build your own visualization.
https://www.vzx-visualizer.com/

+ Online tools:
musicvid.org/: Free Open sources tool for professional visuals directly in your browser. Made by github.com/AlexVestin
renderforest.com/music-visualisations


https://www.youtube.com/watch?v=uYdNv0JrPbU

https://runwayml.com/

+ (OBS stuf)[reddit.com/r/DJs/comments/qlzab0/looking_for_a_simple_audio_visualizer/]:
OBS Shaderfilters
https://www.youtube.com/watch?v=Na-fPxoUwf0
