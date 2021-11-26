# ags4-to-LAS
code to extract some data from AGS4 files (geotechnical data) to LAS format so these can be read into our software.

This is a first version, proof of concept. 
Task:
- read AGS4 files,
- extract data for all locations in file
- export (selected) data for each location to LAS files (one per location)

References:
- Definition of AGS4 data format:
  https://www.ags.org.uk/data-format/ags4-data-format/
- Gitlab project to read AGS4 files with python:
  https://gitlab.com/ags-data-format-wg/ags-python-library 
