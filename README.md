MBAppirater
===========

By modifying to the MBAlertView UIAlertview of Appirater, 
effects such as the following has been implemented.

1. Display indicator and message.
2. Display customized alert.
3. Display short message depending on the selection.


Configuration

You can use the same fully Appirater.

[Appirater setAppId:@"552035781"];
[Appirater setDaysUntilPrompt:1];
[Appirater setUsesUntilPrompt:10];
[Appirater setSignificantEventsUntilPrompt:-1];
[Appirater setTimeBeforeReminding:2];
[Appirater setDebug:YES];

UIAlertView of Appirater modified in MBAlertView.

License

・Appirater
MIT/X11

・MBAlertView
Copyright (c) 2013 progenius (http://progeni.us)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.


