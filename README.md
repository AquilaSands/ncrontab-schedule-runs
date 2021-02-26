# NCrontab Schedule Runs
Very simple single page website for showing the next scheduled run times of a NCrontab (Cron with a sixth field for seconds) expression as used by Microsoft Azure Functions timer trigger.

No framework used. JS in a script tag and CSS in a style tag. Pure heresy but super small and fast to load.

Uses Later (https://github.com/breejs/later) to parse the Cron expression, minified version included directly in the html in a script tag.

Live version at https://ncrontabruns.azureedge.net
