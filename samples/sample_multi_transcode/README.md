To run this sample, after you have built it, make sure you create a `.par` text file, and in it, put this in:

```
-sw -i::h264 test_stream.264 -o::h264 output.264
```

Next, the produced executable will be called `sample_multi_transcode.exe`. Run it like this:

```
$ ./sample_multi_transcode.exe -par transcoder.par
```
