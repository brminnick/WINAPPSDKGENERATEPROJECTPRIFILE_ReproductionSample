# WINAPPSDKGENERATEPROJECTPRIFILE_ReproductionSample
This sample reproduces the `WINAPPSDKGENERATEPROJECTPRIFILE` error in CommunityToolkit.Maui-pre7 

> 1>WINAPPSDKGENERATEPROJECTPRIFILE : error : PRI175: 0x80073b0f - Processing Resources failed with error: Duplicate Entry.
> 1>WINAPPSDKGENERATEPROJECTPRIFILE : error : PRI222: 0x80073b0f - Unspecified error occurred.
> 1>Done building project "MauiApp1.csproj" -- FAILED.

### Reproduction Steps
1. Download/Clone this repository
2. In Visual Studio 2022 Preview, open `MauiApp1.sln`
3. In Visual Studio 2022 Preview, select framework `net6.0-windows10.0.19041`
4. In Visual Studio 2022 Preview, build 
4. Confirm `WINAPPSDKGENERATEPROJECTPRIFILE` error

