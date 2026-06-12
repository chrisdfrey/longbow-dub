# longbow-dub

A work-in-progress fan dub of *Conquests of the Longbow*. See this Trello board for progress: https://trello.com/b/YrzBQYkU/longbow-dub

A demonstration of the first outlaw conversation outside the cave (with voice lines from OneShortEye's video): https://www.youtube.com/watch?v=yohRlvoitBI

For more information, see the #longbow-dub channel in the Kings Quest Speedruns Discord: https://discord.gg/Skk98WrTma

## Prerequisites

- GoatVM executable: https://github.com/chrisdfrey/GoatVM/releases
- Game files for *Conquests of the Longbow* (can be purchased on GOG)

## How to run

1. Download a [ZIP file](https://github.com/chrisdfrey/longbow-dub/archive/refs/heads/main.zip) of this repo and extract it, or clone this repo.
2. Copy the "dub" folder to your *Conquests of the Longbow* folder.
3. Run GoatVM and run *Conquests of the Longbow* (add the game folder if you haven't done so in another version of ScummVM).

## How to add new lines

See files.csv; dub files are referenced by offset and index.

The offset is the number of the selected text resource in SCI Companion, and the index is the 0-based index of the line in the pane on the right. For example, the dub files for the first outlaw conversation outside the cave have offset 1151, indexes 0 through 9 (see below).

<img width="884" height="614" alt="sci_companion_dub" src="https://github.com/user-attachments/assets/95d4f311-b7dc-4e51-8848-9dda58213f48" />
