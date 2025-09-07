

#  &nbsp;Jed’s Other Poem <br>(Beautiful Ground)<br>&nbsp;music video

<img src="./misc/jed.jpg?raw=true" width="100%" style="border-radius: 24px;">

[Music video for “Jed’s Other Poem (Beautiful Ground)”](https://stewartsmith.io/work/jed)—a song by indie rockers [Grandaddy](https://grandaddymusic.com), from their sophomore record [The Sophtware Slump](https://en.wikipedia.org/wiki/The_Sophtware_Slump) (2000). Programmed in [Applesoft BASIC](https://en.wikipedia.org/wiki/Applesoft_BASIC) on a vintage [1979 Apple `][+` computer](https://en.wikipedia.org/wiki/Apple_II_Plus), this is the [world’s first open-source music video](https://stewartsmith.io/work/jed#first-open-source-music-video) (2005).
Enjoy the video and read a complete description of its creation and reception here: 
https://stewartsmith.io/work/jed

<br>

| Element                       | Party |
|:------------------------------|:------|
| Music                         | [Grandaddy](https://grandaddymusic.com) | 
| Concept, direction, execution | [Stewart Smith](https://stewartsmith.io) | 
| Camera                        | [Jeff Bernier](https://jeffbernier.se) |
| Lighting                      | [John Paul Chirdon](http://johnpaulchirdon.shoutabl.com) |




<br><br>




##  20th anniversary

<img src="./misc/formats.jpg?raw=true" width="100%" style="border-radius: 24px;">

On the occasion of this music video’s 20th anniversary (September 2005–2025), I’ve decided to take the long-overdue step of publishing its code to GitHub. Originally open-sourced in December 2005 (only a few months after [Linus](https://en.wikipedia.org/wiki/Linus_Torvalds) created [Git](https://en.wikipedia.org/wiki/Git)—and well before [GitHub](https://en.wikipedia.org/wiki/GitHub) existed), the ZIP file containing the code was available solely from my own website. This new repository retains those original source files: 

| File name | Description |
|:----------|:------------|
| `jed.bas` | Applesoft BASIC source code as plain text. |
| `jed.dsk` | Binary disk image for emulators. |
| `jed.aif` | Code as audio for use with [`BLOAD` command](https://stewartsmith.io/work/jed#data-as-audio) on vintage Apples. |

The original `README` message is included here below. I’ve updated the `LICENSE` to the most recent version of the [Creative Commons BY-NC-SA license](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en), which applies to the three original files listed above. (The `LICENSE` file accompanies them in the `code` folder.) Note that this code package does __not__ include (and has never included) the music track. Go buy that from [Grandaddy](https://grandaddymusic.com/)! Thank you to V2 Records’ legal team for [granting me permission to showcase my work](https://stewartsmith.io/work/jed#avoiding-a-lawsuit) twenty years ago. And [thank you to Jason Lytle, Grandaddy, and fans of this video](https://stewartsmith.io/work/jed#legacy).




<br>




##  Original README

__Monday, 12 December 2005.__  

After many requests for Jed’s source code I finally figured out a *simple* way to get it off the Apple `][+` without transcribing it. The old Apple has an audio-out for saving data to cassette tape—the data is encoded in tones that sound like a traditional modem. I plugged the old Apple’s audio-out into my PowerBook and recorded the noise. Then I loaded this into my [Virtual II emulator](https://www.virtualii.com) as a virtual cassette. Perfect. 

For your enjoyment I’ve exported the code as an AIF audio file (like a cassette), a binary disk image for emulators, and a plain text (BASIC code) file. Have fun running and tweaking as you see fit. Although some spots of code are embarrassingly inefficient, or are commented out entirely, I’ve made no effort to clean it up and have left everything exactly as it was during filming. You’ll also notice that the emulation falls slightly out of sync with the music, which is not provided—go out and buy the record yourself! Despite best efforts to scale the timing variables appropriately I was thrown off by numerous immutable factors. Minor post-production edits were required to keep it all together. I don’t think this diminishes from the project’s “hardcore” status.



