# Maisi-Dashcam-GPS-Data-Extractor

This python script will convert a subtitles file generated by a Maisi Dashcam with a GPS module installed, into a more useful GPX file.
The script is incomplete, so please be patient as I work on it! The current state should work with subtitle files that haven't been modified in any way.

## Using the script

Follow the instructions for usage of the script. I will include sample data and sample output in the future.

### Prerequisites

* Python 3
* ffmpeg (installed for system wide access, or binary in same path as script if not installed)

### Usage

See ```-h``` or ```--help```

### Output

The script will output a GPX file (or files) with the same name as the video file in the same directory the file came from (or in a directory called gpx if batch processing videos).

## Future Development Plans / TODO list

What I hope to add to the script in the future

* More parameters
   * Specify output location
   * Specify output format (other than GPX)
   * Option to embed speed data (included by default)