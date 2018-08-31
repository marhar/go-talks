# go-talks
talks in go present format

$ present

:autocmd BufWritePost \*.slide !chrome-reload

```
$ cat chrome-reload
osascript -e '
tell application "Google Chrome" to tell the active tab of its first window
    reload
end tell
'
```

