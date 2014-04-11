# Ilios Integration Block for Moodle 2

This block integrates the [Ilios](http://iliosproject.org/) calendar into Moodle.

This module is designed and developed by The University of California, San Francisco.

## Installation

1. Place this folder under the blocks directory of local Moodle
   installation, i.e. `<moodleroot>/blocks/`

2. Rename this folder to 'ilios' if it is called something else,
   i.e. `<moodleroot>/blocks/ilios`

3. Log into Moodle as administrator, and select 'Notifications' in
   Site Administration column.

4. Change any setting necessary and save it.

## Usage

The calendar may be called with an iframe placed in a label within a Moodle
page:

```html
<div>
    <iframe
        width="100%" height="816" frameborder="0"
        src="https://moodle.example.edu/blocks/ilios/calendar.php?iframe_height=800">
            Ilios Calendar
    </iframe>
</div>
```
