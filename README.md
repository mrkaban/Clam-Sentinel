# ClamSentinel

The Clam Sentinel source code was hidden deep in SourceForge and wasn't easy to obtain, making it difficult for potential project contributors. So, I decided to dig it up and update it slightly for Windows 10 compatibility, as it hadn't worked on Windows 10 for a while.

More details: https://alekseycheremnykh.ru/post/clam-sentinel-123/

Delphi 7 is recommended.

The software also requires ClamWin installed.

Goal: To simplify access to the source code so that a potential project contributor can find it more easily, and also to slightly improve compatibility with Windows 10.

Changes in version 1.23:

1. ClamSentinel.manifest (new file)
- XML ​​manifest for Windows Vista/7/8/10/11
- UAC setting: requestedExecutionLevel level="asInvoker"
- DPI awareness: dpiAware="true"
- Compatibility with Windows 10 and 11 (not tested)

2. ClamSentinel.rc (new file)
- Link to manifest file: 1 24 "ClamSentinel.manifest"
- Used to add the manifest to the .exe file

I do not provide support for this project.
