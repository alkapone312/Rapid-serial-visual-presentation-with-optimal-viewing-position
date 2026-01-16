# RSVP PDF/TXT Reader

## Overview

RSVP PDF/TXT Reader is a web-based application that allows rapid serial visual presentation (RSVP) reading of PDF and TXT documents. Users can load a file and read it word by word at a configurable speed (words per minute). The application highlights the optimal viewing position (OVP) of each word to facilitate faster recognition.

## Features

* Load PDF or TXT files for RSVP reading.
* Adjustable reading speed (WPM).
* Play, pause, and rewind functionality.
* Jump to a specific word via input.
* Adjustable font size.
* Dynamic word counter.
* Visual OVP markers to indicate optimal letter for recognition.

## Architecture

* **ReadingModel**: Manages the list of words and current position.
* **ReadingLoader**: Interface for loading different file types (PdfLoader, TxtLoader).
* **ReaderController**: Handles rendering, playback control, and UI updates.
* **Loader selection** based on file extension.

## Usage

1. Open the HTML file in a modern web browser.
2. Click the file picker and select a PDF or TXT file.
3. Adjust WPM and font size as desired.
4. Use the play/pause and rewind controls to navigate through the text.
5. Optionally, type a word index to jump to a specific word.

## Requirements

* Browser

## License

This project is open-source and can be used and modified freely.
