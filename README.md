Kivy-MinorProject
=================
PyShare

It's a  file sharing app which can be used for a collaborative project management.
Since Kivy is cross-platform, this app runs on both Windows as well as Linux platform.

Based on Twisted Server-Clietn Model, this app helps team members to collaborate their work simultaneoulsy with others.
http://twistedmatrix.com/documents/12.2.0/core/examples/

Basic file transmission, searching and accessing among the members.
A Repository is automatically generated on client's machine which is under watch for any file operation. 
Any such event triggers the notification to be braodcasted to all the client's.
This helps everyone working if, on same project, to know the status and work of others.
Python module Watchdog helps in triggering pop-ups upon any file event.
https://github.com/gorakhargosh/watchdog

Yet more to develop...