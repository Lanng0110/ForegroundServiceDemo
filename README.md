# ForegroundServiceDemo

This repository contains a demo app of a foreground service for Android Jelly Bean to Android Oreo (API 26).

This service will run even when the app is shutdown.

If you are looking for alternatives to a started service, take a look at my blog post: https://lanng.me/wordpress/android-oreo-the-problems-i-encountered-and-how-to-work-around-them/

When Changing the notification icon (setSmallIcon()) make sure to use an adaptive icon, as a non-adaptive icon will result in a system error "System UI has stopped".
