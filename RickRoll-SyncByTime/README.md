This is RickRoll triggered by time.

Change $t variable to set-up custom trigger.

```powershell
$t = '01/01/2024 11:00:00pm' # THIS IS TRIGGER ON 1 of Jaunary, 2024, 23:00 (11:00pm)
```

You can load it by following command:
```powershell
powershell -nop -ep bypass -W H -C irm <direct url to script> | iex
```