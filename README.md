# dissertation-synthesizer

# Overview
This project was developed for my dissertation on usable and accessible design in software synthesizers. Software synthesizers are one of the main tools for music creation and can be heard in almost all modern music. However, their complex workflows can turn away many users. The aim was to develop a software synthesizer that was intuitive to new users and accommodated those with additional accessibility needs without alienating experienced users. The finished product tested favorably among both user groups, and can be considered to have been a success.

# Features
- 3 oscillators, with modifiers for pitch, waveform, and volume, with a visual interface
- Low, high, band and notch pass filters
- Volume envelope (attack, decay, sustain, release), with a visual interface
- Preset menu supporting saving and loading
- Built in keyboard (in standalone mode)
- Documentation integrated into tooltips and info boxes
- Consistent visual language and color palette for ease of understanding, including high contrast mode

# How to Use
This project was developed with C++ using the [JUCE](https://juce.com/) framework. Builds can be found in:

`Builds\VisualStudio2022\x64\Release`

There are two builds provided:
- Standalone (x64): can be run out of the box on compatible machines.
- Plugin (VST3): must be run from within a digital audio workstation or equivalent. Cross-platform compatible.

The JUCE project file is only set up to support compilation for these formats. JUCE also only supports a limited range of IDEs, with this project being set up for Visual Studio 2022. To use other IDEs or compile for other platforms or plugin formats, the project file must be updated to enable these. This requires installing JUCE. Learn more [here](https://juce.com/tutorials/tutorial_new_projucer_project/).
