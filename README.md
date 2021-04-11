\[MS-ERREF]: [Windows Error Codes][ms-erref]
===========================================

Package `mserr` provides types and values for Microsoft Windows error
codes for use in Go programs.

Types provided:

- `HResult`:    [`HRESULT`][hresult]
- `NTStatus`:   [`NTSTATUS`][ntstatus]
- `Win32Error`: [Win32 Error][win32error]

The values are fairly naïvely scraped from Microsoft's Open Specifications
[documentation][openspecs].

[ms-erref]:   https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-erref/1bc92ddf-b79e-413c-bbaa-99a5281a6c90
[openspecs]:  https://docs.microsoft.com/en-us/openspecs/main/ms-openspeclp/3589baea-5b22-48f2-9d43-f5bea4960ddb

[hresult]:    https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-erref/705fb797-2175-4a90-b5a3-3918024b10b8
[ntstatus]:   https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-erref/596a1078-e883-4972-9bbc-49e60bebca55
[win32error]: https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-erref/18d8fbe8-a967-4f1c-ae50-99ca8e491d2d
