# filenotify

Stand-alone repository for [Docker](https://github.com/docker/docker)'s [filenotify](https://github.com/docker/docker/tree/master/pkg/filenotify). Combines `fsnotify` with fallback to polling.

> Package `filenotify` provides a mechanism for watching file(s) for changes. Generally leans on `fsnotify`, but provides a poll-based notifier which `fsnotify` does not support. These are wrapped up in a common interface so that either can be used interchangeably in your code.
