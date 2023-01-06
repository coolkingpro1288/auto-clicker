# auto-clicker
fast auto clickerBuild started
git clone -q --branch=master https://github.com/Limitedparty/TipClicker.git C:\projects\tipclicker
git checkout -qf 61fb4d8904d0d506fca00e7f23c7bab6e62b7661
msbuild "C:\projects\tipclicker\TipClicker.csproj" /verbosity:minimal /logger:"C:\Program Files\AppVeyor\BuildAgent\Appveyor.MSBuildLogger.dll"
Microsoft (R) Build Engine version 14.0.25420.1
Copyright (C) Microsoft Corporation. All rights reserved.
Manager.cs(44,25): warning CS0162: Unreachable code detected [C:\projects\tipclicker\TipClicker.csproj]
  TipClicker -> C:\projects\tipclicker\bin\Debug\TipClicker.exe
Discovering tests...OK
Collecting artifacts...
Found artifact 'bin\Debug\TipClicker.exe' matching 'bin\Debug\TipClicker.exe' path
Uploading artifacts...
[1/1] bin\Debug\TipClicker.exe (10,752 bytes)...100%
Build success
