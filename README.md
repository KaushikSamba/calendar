# Calendar

This is a simple calendar with the full year on a single page. Designed to be printed, it will automatically adjust to any paper size or direction (though it looks best in landscape orientation).

By default, the current year is used. You can override the year by supplying a `year` parameter, e.g. ``https://neatnik.net/calendar/?year=2027``.

You can also switch to a weekday-aligned rendering by setting the `layout` parameter value to `aligned-weekdays`, ``https://neatnik.net/calendar/?layout=aligned-weekdays``

Unabashedly written in PHP. Print it here: https://neatnik.net/calendar

## Instructions to run 

In WSL, `apt install php7.4-cli`. This provides the PHP CLI that can be used to run a single file, and also contains a builtin webserver. 

Once you've done that, 
```
php -S localhost:8000 calendar.php
```

Open `localhost:8000` in a browser window to see the calendar.