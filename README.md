# Generator of web pages KRS-LK
Based on Jinja2 and Questiroud logic (both open-source applications).

## Sites generation
Use the script `generate.py` in `generator` folder. Python in version 3.8+ is
required.

## Requirements
There is just one requirement
```
pip3 install Jinja2
```
## Content
The generator source code of pages is in Jinja2-based files in folders
`generator/TEMPLATES/`.

Pictures, scripts and CSS styles (generally all resources) are in
the folder `generator/RESOURCES/`.

## Processing of questionnaire
Is located in `questroud/` folder (based on
[Questiroud](https://github.com/david-salac/Questiroud-simple-quiz-application)
application). Script has to run on server with PHP in version 5.6+.

It is also necessary to configure the end-point in the file
`generator/RESOURCES/js/questiroud.js` to point-out on this server-side
application.
