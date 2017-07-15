# Introduction
This is a fork of the excellent file-upload element here https://github.com/winhowes/file-upload

I have modified the fileUpload function to work with Firebase.

2 new parameters need to be defined for uploads to work - app and path.

Your element should look like this (refer to original doco on file-upload for more parameters):

```
<firebase-upload app="test" path="/images/folder"></firebase-upload>
```

The instance of firebase defined by "app" must also have a storageBucket assigned to it. This has been added on this pull request to polymerfire https://github.com/firebase/polymerfire/pull/30 which will hopefully be merged to master soon.

It supports multi-file selection as well as optional drop zones for drag-and-drop. The element is designed for use in Polymer 1.0.

Check out the demo and docs for the original file-upload element here: https://winhowes.github.io/file-upload/components/file-upload/.
