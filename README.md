# 3d-printed-spectrograms
**By Nathan Wolek - [@LowkeyNW](http://twitter.com/lowkeynw) - [nathanwolek.com](https://www.nathanwolek.com)**  
**and Grace McEllroy - [gracemcellroy.wixsite.com](https://gracemcellroy.wixsite.com/home)** 

A set of spectrograms designed to teach about common features of sound events (duration, intensity, pitch, timbre, pattern, speed). The digital files are provided so that anyone can 3D print these models for their own lessons or projects.

![3D model based on a short field recording from Canaveral. It features a few sharp peaks in the lower right corner created by an owl hooting, some wide vertical ridges created by a frog croak in the middle left, and a horizontal ridge toward the upper edge created by crickets.](cricket-owl-frog-1200.png)


## Background

Visual representations of recorded sound waves enable computer users to make useful insights into the sound they are hearing. A three-dimensional graph known as a spectrogram can convey how frequency and amplitude are changing through time, providing listeners with opportunities to view with their eyes details that might be missed by their ears alone. However, these opportunities are not accessible to blind persons. While developing lessons about sound for the blind and partially-sighted students in [Young Sound Seekers](https://atlanticcenterforthearts.org/youngsoundseekers/), we experimented with 3D-printing techniques to produce tactile learning aids based on spectrograms. A set of 3D-printed spectrograms was designed for a lesson about common features of sound events (duration, intensity, pitch, timbre, pattern, speed). We describe the models from this set in detail and provide instructions for downloading the associated digital files so that anyone can 3D print these models for their own projects.

This research project was accepted for presentation at [ICMC 2022](https://icmc2022.org). For more details about our design process, background research, and wisdom we learned along the way, please see our full paper: 

Wolek, Nathan, and Grace McEllroy. 2022. “[Designing 3D-Printed Spectrograms for Blind Students](http://nathanwolek.com/docs/2022/designing-3d-printed-spectrograms.pdf).” In *Proceedings of the International Computer Music Conference*. Univ. of Limerick, Ireland.


## How to Download

If you are not familiar with git, it is probably easiest to simply [download the latest version here](https://github.com/nwolek/3d-printed-spectrograms/archive/refs/heads/main.zip). 

If you are a more experienced git user who would like to take advantage of its features, you can easily download these to your desktop using something like following terminal commands:

```
cd ~/Desktop
git clone https://github.com/nwolek/3d-printed-spectrograms.git
```

## How to Use

Each spectrogram model in this collection has been given its own folder. To enable 3D printing these spectrogram models by anyone (and provide some additional context), each folder contains the following digital files:

- [STL file](https://www.loc.gov/preservation/digital/formats/fdd/fdd000504.shtml) - Description of the spectrogram object for 3D printing. This is an open format that can be easily loaded into programs like [Ultimaker Cura](https://ultimaker.com/software/ultimaker-cura) or [MakerBot Print](https://www.makerbot.com/3d-printers/apps/makerbot-print/).
- [WAV file](https://www.loc.gov/preservation/digital/formats/fdd/fdd000001.shtml) - Sound recording used to generate the spectrogram. This uncompressed audio can also be used to hear the sound associated with each model while teaching.
- [PNG file](https://www.loc.gov/preservation/digital/formats/fdd/fdd000153.shtml) - Photo that documents what the the printed spectrogram should look like. This image provides a visual reference.
- [MD file](https://en.wikipedia.org/wiki/Markdown) - Descriptive text of the finished model and how its key features connect to the sound recording. This text provides a verbal reference.

## Acknowledgements

- Young Sound Seekers is supported through a cooperative agreement with the [National Park Service's Natural Sounds and Night Skies Division](https://www.nps.gov/orgs/1050/index.htm)
- Grace McEllroy's initial research was supported by the [Stetson Undergraduate Research Experience](https://www.stetson.edu/other/research/sure.php) program
- Raw STL models were generated using Tim Toplak's [3DPrintedSound](https://github.com/TimToplak/3DprintedSound) project
- Printing support for our 3D models was provided by the [Innovation Lab of the duPont-Ball Library](https://www2.stetson.edu/library/innovation-lab/)
