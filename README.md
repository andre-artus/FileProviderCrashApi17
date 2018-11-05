# FileProviderCrashApi17
Application to showcase FileProvider crash on API &lt; 21

Checkout the following tags

## Tag `before_crash`
A basic Android app referencing `FileProvider`, without subclassing `Application` or having multi-Dex enabled.

## Tag `after_crash`
Subclassing `Application` and having multi-Dex enabled causes the app to crash on start-up.

## Tag `MultiDexApplication`
Subclassing `MultiDexApplication` instead of `Application` seems to solve the problem.