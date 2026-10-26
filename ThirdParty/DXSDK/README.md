# DirectX SDK (DXSDK June 2010)

Embedded DirectX SDK for D3DX9 library support.

## What is this?

Microsoft discontinued the standalone DirectX SDK after June 2010.
The D3DX9 library (d3dx9.lib) is no longer included in the Windows SDK
that ships with Visual Studio 2013+.

This embedded copy provides:
- Include/d3dx9.h and other D3DX9 headers
- Lib/d3dx9.lib for linking

## Updating

To update this copy, download DXSDK_Jun10.exe from:
https://www.microsoft.com/en-us/download/details.aspx?id=6812

Extract the contents (DXSDK90.zip) into this folder, replacing existing files.

## CMake integration

The CMake files automatically find this folder via ${CMAKE_SOURCE_DIR}/ThirdParty/DXSDK.
No DXSDK_DIR environment variable is needed.
