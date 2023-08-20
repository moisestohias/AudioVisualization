# Audio Visualization
## What is this? 
This is a collection kind like the [awesome](https://github.com/sindresorhus/awesome) that focuses on audio visualization tools, (mostly on fast and headless tools and libraries).

## Why? 
Who the hell don't love beatiful audio visualization. The awesome collection already has audio visualization section, but mostly JS libraries and tools, but not stuff that can actually be useful without browser or a canvas.

### Scope
This collection tries to focus on ready to use tools, so the following are either not discussed
+ (Unity/C#)[youtube.com/c/PeerPlay/playlists]
+ **JavaScript** base visualizers: although the visual flair that you can do with JS can be astonishing, they all run either in the browser or in a canvas, and not portable.
+ **After effect**: [Although powerfull](videobolt.net/templates/music-visualization), but not in my scope
+ **Blender** or any of the GUI tools (Although blender and Houdini are great tools)

## Just to give a bit of context. There are two main motors for audio visualization:
To provide a clearer context, there are two primary methods for audio visualization: waveforms and Short-Time Fourier Transform (STFFT). Let's delve into each of these methods to uncover potential improvements for better visualization.

1. **Waveform:**
   A waveform is a straightforward representation of audio samples over time. To enhance this visualization, we can consider implementing the following improvements:
   
   - **Fundamental Frequency Detection:** One key enhancement involves detecting the fundamental frequency of the loudest sound within the audio. By identifying this frequency, we can dynamically adjust the synchronization window of the waveform. This adjustment ensures that the waveform accurately represents the dominant sounds, resulting in a more informative visualization.
   
2. **STFFT (Short-Time Fourier Transform):**
   The STFFT is a fundamental audio transformation technique that yields a spectrogram, which can be presented in various ways. Here are some ways to enhance the STFFT-based audio visualization:

   - **Spectrogram Enhancement:** The spectrogram obtained through STFFT is a natural output, but applying a logarithmic scale can significantly improve the representation to match our auditory perception. Additionally, experimenting with different color maps can offer diverse perspectives on the audio content. Furthermore, exploring 3D representations of the spectrogram can lead to visually captivating and informative results.

   - **Spectrum Sequence:** Another approach is to represent the FFT of individual windows over time, resulting in what's known as a spectrum. By arranging these spectra consecutively, we obtain a moving spectrum that reflects the audio characteristics at each moment. This method provides a dynamic insight into how the audio evolves over time.

In conclusion, enhancing audio visualization involves implementing specific strategies for both waveform and STFFT-based representations. By incorporating fundamental frequency detection, adjusting synchronization windows, applying logarithmic scales, experimenting with color maps, and exploring 3D representations, we can create more insightful and engaging visualizations of audio content.


+ [synesthesia](http://www.synesthesia.live/): realtime shaders visualization similar to __MilkDrop__
    + The visualization are not only based on audio input, but can be control and changed with MIDI in real-time. This is mostly for live-performance music-visual artists.
    + Import your own videos and logos and transform them in real-time.
    + Generate real-time video output to send directly to a projector..
    + Import shaders from Shadertoy and ISF to add fresh content.
    + Live coding environment for creating your own shaders.
    + New content available through the in-app marketplace.
    + Available for Windows/Macos free and paid.
+ [MilkDrop](http://www.geisswerks.com/about_milkdrop.html) The Godfather of audio visualization, If you remember the glory days of WinAmp audio player and its mesmerizing visual flair, this was the engine behind it.
+ [ProjectM](https://github.com/projectM-visualizer/projectm):
    + open-source cross-platform reusable library for audio visualization
    + Stand Alone: get input from Mic or system's audio

+ [Butterchurn](github.com/jberg/butterchurn) :
    + A WebGL implementation of the Milkdrop Visualizer

+ plane9: The visualizer can be used either as standalone window, screensaver, oculus rift or HTC Vive VR visualizer. It is sound sensitive and reacts to what your currently listening to, be it from spotify, iTunes or any another sound source, it can even react to what you record from a microphone or other input.
It uses OpenGL meaning you can expect all the psychodalic pattern, you are familiar with from old WinMap and windows media player, but a lot more.
 plane9.com/

+ [FL studio zgameeditor](youtube.com/channel/UCV4oqyhk2L9HvOfjlraNtEQ/videos) : Is an audio visualization tool that ships natively with FL-Studio producer version (I guess), it's relatively powerful considering that it is just an add-on to a DAW and especially when copared to what other DAW has to offer in this area.
I would say that, it is a bit clunky TBH and not super flexible, It requires some talent and time to get good versatile results.

+ [vzx-visualizer](vzx-visualizer.com/): similar to plane9, but with a lot more features, that allows you to build your own visualization.

+ Online tools:
    + **musicvid.org**/: is a [FOSS](github.com/AlexVestin/musicvid.org) tool for professional visuals directly in your browser. Made by [AlexVestin](github.com/AlexVestin) 


+ [NestDrop - Advanced VJ tool for Milkdrop - Tutorial](youtube.com/watch?v=uYdNv0JrPbU)
+ [OBS stuf](reddit.com/r/DJs/comments/qlzab0/looking_for_a_simple_audio_visualizer/)

