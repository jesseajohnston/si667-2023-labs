---
title: 'Nature of the Digital'
teaching: 5
exercises: 2
---

:::::::::::::::::::::::::::::::::::::: questions 

- How can you "look" at digital files in different ways?
- What are different modalities or "materialities" that we might consider in understanding digital objects?
- What happens if you change the bitstream of various kinds of files?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Open text files and binary files with a text editor to view the file's bitstreams
- Open binary files with a hex editor to view the bitstream of the file in hexadecimal notation
- Modify and change files using these bitstream views and see what happens

::::::::::::::::::::::::::::::::::::::::::::::::

## Introduction

This Lab activity asks you to think about files in different ways and to experiment
with different methods of viewing files. These "ways of looking" can be as a binary
bitstream displayed in ASCII text, or the bitstream displayed in hexadecimal couplets.
These ways of viewing the files may not seem at first "correct," and the lab
asks you to consider these as alternative views of the files, even though when viewed
"properly" these files may render a visible image or representation that is very different
than the bitstreams we are seeing here.

As we will see, these various views have been described as different "layers" of digital 
objects (Owens 2018, and others) as well as varied "formal materialities" that are
enabled by different software views of the same bitstream (Kirschenbaum 2012).
Throughout, you should be thinking about how these different views of the files 
might be used.


:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor

The below lessons should be possible to do after the initial "digital curation"
lectures focused on binary, hex editors, the concept of bitstream and file,
and various "bit-level" concepts of files. 

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

## Getting Started

* Various candidate files for this lab may be chosen from the files in this repository (you can 
clone the repository locally or download individual files for this exercise): https://github.com/jesseajohnston/si667-2023.
  * Note: You may select files of your own choosing (but please choose images that are appropriate for sharing with others and that you don't mind sharing with the instructor).
* Choose three files, of different images types: choose at least one JPG, one PNG, one TIF and one of a different format as a fourth option (e.g., text, video, audio, etc). 
* At the beginning of your report, list the files that you are investigating.

Once you have chosen the files, work on the following questions. For each question, 
complete the activities and answer the corresponding questions. 
Record your files in a separate document (it may be a text file, formatted in 
markdown, or a doc file of another type). Please submit your answers via the 
course Canvas site. 


::::::::::::::::::::::::::::::::::::: challenge

## Q1: Choose your files

What four files have you chosen for this activity?

:::::::::::::::::::::::: solution

## Solution
 
[Q1] Answers will vary, depending on the files you choose.

:::::::::::::::::::::::: 
::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::: challenge

## Q2: Open the files with your text editor

You can try all of the following using VSCode.

1. Try opening the files with different encodings - do you have any observations? 
1. Can you save any [mojibake](https://en.wikipedia.org/wiki/Mojibake) versions?
1. Try edits (delete one character, move parts of the file around). Describe the edits
you make in your lab report. (For example, I deleted a bit at offset 0001, or changed a bit from X to Y.)
1. Rename and save the edited files (use "Save As ...") and submit them with your assignment
1. After you edit and save the files, are you able to open any of the image files
as images? Please describe what happens in your lab report.

:::::::::::::::::::::::: solution

[Q2] Answers will vary depending on the files you've chosen. Nonetheless, these are the 
sorts of things that you should find:

1. For binary files (any of the images), you should see a lot of strange character strings, which may be deciphered in small sections.
1. You may save _mojibake_ versions, but it can be complicated because the concept of this art form is to display the characters using an "incorrect" text encoding, so this is really a form that should only exist when it is displayed. (Of course, you can save the characters you see and save them into a different encoding.)
1. Your edits will likely vary. You can try deleting one byte, an entire line, a whole section, or rearranging parts of the file. As requested above, please make note of the changes that you make.
1. Please save your file with a name that makes sense, like `file01-edited.jpg`. 
1. Answers will vary. For example, when I deleted half of the `ecce-homo.jpg` file, it
was still possible to open as an image, but the colors were strange and the image was highly distored with 
many horizontal lines and skewed.

:::::::::::::::::::::::: 
::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::: challenge
## Q3: Open the files with a hex viewer

This can be done in VSCode, after you install the hex extension.

:::::::::::::::::::::::: solution

[Q3] Solution here

::::::::::::::::::::::::
:::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: keypoints 

- Use `.md` files for episodes when you want static content
- Use `.Rmd` files for episodes when you need to generate output
- Run `sandpaper::check_lesson()` to identify any issues with your lesson
- Run `sandpaper::build_lesson()` to preview your lesson locally

::::::::::::::::::::::::::::::::::::::::::::::::

