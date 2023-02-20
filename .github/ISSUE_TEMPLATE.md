## Please follow the guide below

- You will be asked some questions and requested to provide some information, please read them **carefully** and answer **honestly**
- Put an `x` into all the boxes [ ] relevant to your issue (like that [x])
- Use *Preview* tab to see how your issue will actually look like

### WARNING
All invalid issues will be rejected!!

---

### Before going further

- If your problem is a bug with **youtube-dl** or a request for new site support please report it [here](https://github.com/rg3/youtube-dl/issues)

- Make sure you are using the *latest* **youtube-dl-gui** version (Click the `Settings` icon and then `About` to view the current version)

- Make sure you are using the *latest* **youtube-dl** version (Click the `Settings` icon and then `Update` to update to the latest **youtube-dl** version)

- Make sure you searched the bugtracker for similar issues **including closed ones**

- Make sure to read the [FAQs](https://github.com/MrS0m30n3/youtube-dl-gui/blob/master/docs/faqs.md) file

  - [x] **I think** my problem is **NOT** with **youtube-dl**
  - [x] I've **verified** and **i assure** that I'm running youtube-dl-gui **0.4**
  - [x] **I assure** that i am using the latest version of **youtube-dl**
  - [x] [Searched](https://github.com/MrS0m30n3/youtube-dl-gui/issues) bugtracker
  - [x] I've read the FAQs file

---

### What is the purpose of your *issue*?

- [x] Bug report
- [ ] Feature request (request for a new functionality)
- [ ] Question
- [ ] Other

Please remove any sections between (---) if they are not related to your issue

---

### Bug report

#### If the problem occurs when downloading a URL please provide the full verbose output as follows:

1. Restart **youtube-dl-gui**
1. Go to `Options > Extra` tab
2. Enable **Debug youtube-dl**
3. Go to `Options > Advanced` tab and **Clear** your log content
4. Try to download the URL
5. Copy the **whole** log content and insert it between the ``` part below

```
[06/29/22 10:01:29] ERROR: unable to download video data: HTTP Error 403: Forbidden
[06/29/22 10:01:29] ERROR: unable to download video data: HTTP Error 403: Forbidden
[06/29/22 10:01:29] ERROR: unable to download video data: HTTP Error 403: Forbidden
[06/29/22 11:44:47] ERROR: unable to download video data: HTTP Error 403: Forbidden
[06/29/22 11:44:47] ERROR: unable to download video data: HTTP Error 403: Forbidden
[07/01/22 18:12:29] ERROR: unable to download video data: HTTP Error 403: Forbidden
[08/30/22 15:47:08] WARNING: Requested formats are incompatible for merge and will be merged into mkv.
[12/16/22 20:51:52] ERROR: unable to download video data: HTTP Error 403: Forbidden
[12/16/22 22:14:39] ERROR: unable to download video data: HTTP Error 403: Forbidden
[12/16/22 22:37:10] ERROR: unable to download video data: HTTP Error 403: Forbidden
[12/16/22 22:37:14] ERROR: unable to download video data: HTTP Error 403: Forbidden
[12/18/22 15:20:23] ERROR: unable to download video data: HTTP Error 403: Forbidden
[12/18/22 15:20:23] ERROR: unable to download video data: HTTP Error 403: Forbidden
[12/18/22 15:21:14] ERROR: Unable to download webpage: HTTP Error 404: Not Found (caused by HTTPError()); please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; type  youtube-dl -U  to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
[12/18/22 15:44:02] ERROR: unable to download video data: HTTP Error 403: Forbidden
[12/18/22 17:52:14] ERROR: unable to download video data: HTTP Error 403: Forbidden
[12/18/22 17:52:14] ERROR: unable to download video data: HTTP Error 403: Forbidden
[12/18/22 17:52:14] ERROR: unable to download video data: HTTP Error 403: Forbidden
[12/18/22 17:52:14] ERROR: unable to download video data: HTTP Error 403: Forbidden
[12/18/22 17:52:14] ERROR: unable to download video data: HTTP Error 403: Forbidden
[12/18/22 17:52:14] ERROR: unable to download video data: HTTP Error 403: Forbidden
[12/18/22 17:52:14] ERROR: unable to download video data: HTTP Error 403: Forbidden
[12/18/22 17:52:14] ERROR: unable to download video data: HTTP Error 403: Forbidden
[01/12/23 19:09:45] ERROR: unable to download video data: HTTP Error 403: Forbidden
[02/17/23 21:39:25] ERROR: Unable to extract uploader id; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; type  youtube-dl -U  to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
[02/17/23 21:39:45] ERROR: Unable to extract uploader id; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; type  youtube-dl -U  to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
[02/17/23 21:39:58] ERROR: Unable to extract uploader id; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; type  youtube-dl -U  to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
[02/17/23 21:40:16] ERROR: Unable to extract uploader id; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; type  youtube-dl -U  to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
[02/17/23 21:40:46] ERROR: Unable to extract uploader id; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; type  youtube-dl -U  to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
[02/17/23 21:44:57] ERROR: Unable to extract uploader id; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; type  youtube-dl -U  to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
[02/19/23 18:45:40] ERROR: Unable to extract uploader id; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; type  youtube-dl -U  to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
[02/19/23 18:52:21] ERROR: Unable to extract uploader id; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; type  youtube-dl -U  to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
[02/19/23 18:52:21] ERROR: Unable to extract uploader id; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; type  youtube-dl -U  to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
[02/19/23 18:55:35] ERROR: Unable to extract uploader id; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; type  youtube-dl -U  to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
[02/19/23 19:25:25] ERROR: 'youtube-dl --rm-cache-dir' is not a valid URL. Set --default-search "ytsearch" (or run  youtube-dl "ytsearch:youtube-dl --rm-cache-dir" ) to search YouTube
[02/19/23 19:26:32] ERROR: 'youtube-dl --get-url --f 137 UsyfAzTbxjA' is not a valid URL. Set --default-search "ytsearch" (or run  youtube-dl "ytsearch:youtube-dl --get-url --f 137 UsyfAzTbxjA" ) to search YouTube
[02/19/23 19:28:01] ERROR: Unable to extract uploader id; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; type  youtube-dl -U  to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
[02/19/23 19:28:27] ERROR: 'youtube-dl -U' is not a valid URL. Set --default-search "ytsearch" (or run  youtube-dl "ytsearch:youtube-dl -U" ) to search YouTube
[02/19/23 19:29:41] ERROR: Unable to extract uploader id; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; type  youtube-dl -U  to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
[02/19/23 19:32:23] ERROR: 'youtube-dl --rm-cache-dir' is not a valid URL. Set --default-search "ytsearch" (or run  youtube-dl "ytsearch:youtube-dl --rm-cache-dir" ) to search YouTube
[02/19/23 19:32:57] ERROR: Unable to extract uploader id; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; type  youtube-dl -U  to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
[02/19/23 19:34:49] [debug] System config: []
[02/19/23 19:34:49] [debug] User config: []
[02/19/23 19:34:49] [debug] Custom config: []
[02/19/23 19:34:49] [debug] Command-line args: ['--newline', '-i', '-o', 'C:\\Users\\Lemon\\%(title)s.%(ext)s', '-x', '--audio-format', 'mp3', '-v', '--ignore-config', '--hls-prefer-native', 'https://www.youtube.com/watch?v=xLFCcnYSCyE']
[02/19/23 19:34:49] [debug] Encodings: locale cp1252, fs mbcs, out cp1252, pref cp1252
[02/19/23 19:34:49] [debug] youtube-dl version 2021.12.17
[02/19/23 19:34:49] [debug] Python version 3.4.4 (CPython) - Windows-10-10.0.19041
[02/19/23 19:34:49] [debug] exe versions: ffmpeg 3.3.2, ffprobe 3.3.2
[02/19/23 19:34:49] [debug] Proxy map: {}
[02/19/23 19:34:49] ERROR: Unable to extract uploader id; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; type  youtube-dl -U  to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
[02/19/23 19:34:49] Traceback (most recent call last):
[02/19/23 19:34:49]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\YoutubeDL.py", line 815, in wrapper
[02/19/23 19:34:49]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\YoutubeDL.py", line 836, in __extract_info
[02/19/23 19:34:49]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\extractor\common.py", line 534, in extract
[02/19/23 19:34:49]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\extractor\youtube.py", line 1794, in _real_extract
[02/19/23 19:34:49]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\extractor\common.py", line 1012, in _search_regex
[02/19/23 19:34:49] youtube_dl.utils.RegexNotFoundError: Unable to extract uploader id; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; type  youtube-dl -U  to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
[02/19/23 19:34:49] 
[02/19/23 19:35:06] [debug] System config: []
[02/19/23 19:35:06] [debug] User config: []
[02/19/23 19:35:06] [debug] Custom config: []
[02/19/23 19:35:06] [debug] Command-line args: ['--newline', '-i', '-o', 'C:\\Users\\Lemon\\Downloads\\Pixel Music Playlist\\%(title)s.%(ext)s', '-x', '--audio-format', 'mp3', '-v', '--ignore-config', '--hls-prefer-native', 'https://www.youtube.com/watch?v=xLFCcnYSCyE']
[02/19/23 19:35:06] [debug] Encodings: locale cp1252, fs mbcs, out cp1252, pref cp1252
[02/19/23 19:35:06] [debug] youtube-dl version 2021.12.17
[02/19/23 19:35:06] [debug] Python version 3.4.4 (CPython) - Windows-10-10.0.19041
[02/19/23 19:35:06] [debug] exe versions: ffmpeg 3.3.2, ffprobe 3.3.2
[02/19/23 19:35:06] [debug] Proxy map: {}
[02/19/23 19:35:06] ERROR: Unable to extract uploader id; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; type  youtube-dl -U  to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
[02/19/23 19:35:06] Traceback (most recent call last):
[02/19/23 19:35:06]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\YoutubeDL.py", line 815, in wrapper
[02/19/23 19:35:06]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\YoutubeDL.py", line 836, in __extract_info
[02/19/23 19:35:06]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\extractor\common.py", line 534, in extract
[02/19/23 19:35:06]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\extractor\youtube.py", line 1794, in _real_extract
[02/19/23 19:35:06]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\extractor\common.py", line 1012, in _search_regex
[02/19/23 19:35:06] youtube_dl.utils.RegexNotFoundError: Unable to extract uploader id; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; type  youtube-dl -U  to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
[02/19/23 19:35:06] 
[02/19/23 19:36:15] [debug] System config: []
[02/19/23 19:36:15] [debug] User config: []
[02/19/23 19:36:15] [debug] Custom config: []
[02/19/23 19:36:15] [debug] Command-line args: ['--newline', '-i', '-o', 'C:\\Users\\Lemon\\Downloads\\Pixel Music Playlist\\%(title)s.%(ext)s', '-x', '--audio-format', 'mp3', '-v', '--ignore-config', '--hls-prefer-native', 'https://www.youtube.com/watch?v=xLFCcnYSCyE']
[02/19/23 19:36:15] [debug] Encodings: locale cp1252, fs mbcs, out cp1252, pref cp1252
[02/19/23 19:36:15] [debug] youtube-dl version 2021.12.17
[02/19/23 19:36:15] [debug] Python version 3.4.4 (CPython) - Windows-10-10.0.19041
[02/19/23 19:36:15] [debug] exe versions: ffmpeg 3.3.2, ffprobe 3.3.2
[02/19/23 19:36:15] [debug] Proxy map: {}
[02/19/23 19:36:15] ERROR: Unable to extract uploader id; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; type  youtube-dl -U  to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
[02/19/23 19:36:15] Traceback (most recent call last):
[02/19/23 19:36:15]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\YoutubeDL.py", line 815, in wrapper
[02/19/23 19:36:15]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\YoutubeDL.py", line 836, in __extract_info
[02/19/23 19:36:15]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\extractor\common.py", line 534, in extract
[02/19/23 19:36:15]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\extractor\youtube.py", line 1794, in _real_extract
[02/19/23 19:36:15]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\extractor\common.py", line 1012, in _search_regex
[02/19/23 19:36:15] youtube_dl.utils.RegexNotFoundError: Unable to extract uploader id; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; type  youtube-dl -U  to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
[02/19/23 19:36:15] 

```

#### What operating system do you use ?
Windows
#### List of actions to perform to reproduce the problem:

  1. 
  2.
  3. 
  
#### What is the expected behaviour ?
To download music
#### What happens instead ?
Error

---

### Feature request (request for a new functionality)

Please make sure that the requested feature is **NOT** already in the [TODO](https://github.com/MrS0m30n3/youtube-dl-gui/blob/master/TODO) list

- [x] I've **verified** and **i assure** that my requested feature is **NOT** in the TODO list

#### What operating system do you use ?
Windows

---

<!--Enter description of your issue, suggested solution and other information below. Please make sure the description is worded well enough to be understood-->

