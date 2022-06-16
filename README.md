# hls_downloader

A posix compliant highly fast and efficient Asynchronous stable m3u8 links dowloader that uses shell jobs for controlling parallel download...

# Increase Parallel Downloads..

Currently its set to my internet speed * 3 in [line 72](https://github.com/CoolnsX/hls_downloader/blob/main/hls#L72) in script

```
Internet Speed = 12 MByte per seconds..
36 (Internet Speed * 3)..
```

# Dependency

- ffmpeg for conversion
- openssl for decrypting streams
