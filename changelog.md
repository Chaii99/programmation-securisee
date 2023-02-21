# Changelog:

## Discover Flask

## Fixed error that appeared when loading the time/ page.

- Old code: return flask.render_template('XXXX.html')
- New code: return flask.render_template('time.html')

## Added link between CSS and HTML of the application.
- Old code (line 8 of the index.html file):  filename='css/XXXX.css') }}" />
- New code (line 8 of the index.html file): filename='css/main.css') }}" />

## Improved display of date and time on the time/ page.
- Old code: date=None, hour=None
- New code: date=date, hour=hour


## Add "review_folder" directory


- The "review_folder" directory is used to give user opinion.
- Added "review_folder" directory with templates folder.
