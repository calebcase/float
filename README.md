# float

A utility for [Sway][sway] that will start an application in floating mode.

The typical way to configure sway for auto-floating applications requires
knowing the app id ahead of time and adding something like `for_window
[app_id="SOME_ID"] floating enable` to the sway config. This works fine if the
`app_id` is set and you *always* want the application floated.

However, if your application doesn't set `app_id` or you only want it to
sometimes start up floating, then this is the tool for you!

```
float your_app with_some_args
```

---

[sway]: https://swaywm.org/
