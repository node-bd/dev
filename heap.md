## Heap allocation failed and crash
```js

{
  "header": {
    "event": "Allocation failed - JavaScript heap out of memory",
    "trigger": "FatalError",
    "filename": "report.20190430.134409.10260.0.001.json",
    "dumpEventTime": "2019-04-30T13:44:09Z",
    "dumpEventTimeStamp": "1556610249515",
    "processId": 10260,
    "cwd": "C:\\Users\\amran",
    "commandLine": [
      "node",
      "--max-old-space-size=8192"
    ],
    "nodejsVersion": "v12.0.0",
    "wordSize": 64,
    "arch": "x64",
    "platform": "win32",
    "componentVersions": {
      "node": "12.0.0",
      "v8": "7.4.288.21-node.16",
      "uv": "1.28.0",
      "zlib": "1.2.11",
      "brotli": "1.0.7",
      "ares": "1.15.0",
      "modules": "72",
      "nghttp2": "1.38.0",
      "napi": "4",
      "llhttp": "1.1.1",
      "http_parser": "2.8.0",
      "openssl": "1.1.1b",
      "cldr": "34.0",
      "icu": "63.1",
      "tz": "2018e",
      "unicode": "11.0"
    },
    "release": {
      "name": "node",
      "headersUrl": "https://nodejs.org/download/release/v12.0.0/node-v12.0.0-headers.tar.gz",
      "sourceUrl": "https://nodejs.org/download/release/v12.0.0/node-v12.0.0.tar.gz",
      "libUrl": "https://nodejs.org/download/release/v12.0.0/win-x64/node.lib"
    },
    "osName": "Windows_NT",
    "osRelease": "10.0.17763",
    "osVersion": "Windows 10 Pro",
    "osMachine": "x86_64",
    "host": "netcse"
  },
  "javascriptStack": {
    "message": "No stack.",
    "stack": [
      "Unavailable."
    ]
  },
  "nativeStack": [
    {
      "pc": "0x00007ff606484f99",
      "symbol": "std::basic_ostream<char,std::char_traits<char> >::operator<<+9161"
    },
    {
      "pc": "0x00007ff606488986",
      "symbol": "std::basic_ostream<char,std::char_traits<char> >::operator<<+23990"
    },
    {
      "pc": "0x00007ff606487915",
      "symbol": "std::basic_ostream<char,std::char_traits<char> >::operator<<+19781"
    },
    {
      "pc": "0x00007ff60656f852",
      "symbol": "uv_loop_fork+47890"
    },
    {
      "pc": "0x00007ff60689c7ae",
      "symbol": "v8::internal::Parser::ReportMessageAt+206"
    },
    {
      "pc": "0x00007ff60687082a",
      "symbol": "v8::internal::wasm::StreamingDecoder::Fail+666"
    },
    {
      "pc": "0x00007ff606906c9c",
      "symbol": "v8::internal::Heap::CreateFillerObjectAt+2972"
    },
    {
      "pc": "0x00007ff606c6b68b",
      "symbol": "v8::internal::OptimizingCompileDispatcher::Unblock+119403"
    },
    {
      "pc": "0x00007ff607103916",
      "symbol": "v8::internal::NativesCollection<0>::GetScriptsSource+660214"
    }
  ],
  "javascriptHeap": {
    "totalMemory": 2999549952,
    "totalCommittedMemory": 2999549952,
    "usedMemory": 2963237896,
    "availableMemory": 5657975784,
    "memoryLimit": 8640266240,
    "heapSpaces": {
      "read_only_space": {
        "memorySize": 524288,
        "committedMemory": 524288,
        "capacity": 523976,
        "used": 31712,
        "available": 492264
      },
      "new_space": {
        "memorySize": 33554432,
        "committedMemory": 33554432,
        "capacity": 16767232,
        "used": 0,
        "available": 16767232
      },
      "old_space": {
        "memorySize": 2744320,
        "committedMemory": 2744320,
        "capacity": 1867384,
        "used": 1867384,
        "available": 0
      },
      "code_space": {
        "memorySize": 688128,
        "committedMemory": 688128,
        "capacity": 190528,
        "used": 190528,
        "available": 0
      },
      "map_space": {
        "memorySize": 1052672,
        "committedMemory": 1052672,
        "capacity": 227200,
        "used": 227200,
        "available": 0
      },
      "large_object_space": {
        "memorySize": 2088452096,
        "committedMemory": 2088452096,
        "capacity": 2088436824,
        "used": 2088436824,
        "available": 0
      },
      "code_large_object_space": {
        "memorySize": 49152,
        "committedMemory": 49152,
        "capacity": 3456,
        "used": 3456,
        "available": 0
      },
      "new_large_object_space": {
        "memorySize": 872484864,
        "committedMemory": 872484864,
        "capacity": 872480792,
        "used": 872480792,
        "available": 0
      }
    }
  },
  "resourceUsage": {
    "userCpuSeconds": 18.5,
    "kernelCpuSeconds": 12.296,
    "cpuConsumptionPercent": 1.10261,
    "maxRss": 5334269952,
    "pageFaults": {
      "IORequired": 5789917,
      "IONotRequired": 0
    },
    "fsActivity": {
      "reads": 1,
      "writes": 90
    }
  },
  "libuv": [
  ],
  "environmentVariables": {
    "=::": "::\\",
    "=C:": "C:\\Users\\amran",
    "=ExitCode": "00000000",
    "ALLUSERSPROFILE": "C:\\ProgramData",
    "ANDROID_HOME": "C:\\android\\sdk",
    "APPDATA": "C:\\Users\\amran\\AppData\\Roaming",
    "CommonProgramFiles": "C:\\Program Files\\Common Files",
    "CommonProgramFiles(x86)": "C:\\Program Files (x86)\\Common Files",
    "CommonProgramW6432": "C:\\Program Files\\Common Files",
    "COMPUTERNAME": "NETCSE",
    "ComSpec": "C:\\Windows\\system32\\cmd.exe",
    "DOTNET_ROOT": "C:\\Programs\\Dotnet",
    "DriverData": "C:\\Windows\\System32\\Drivers\\DriverData",
    "GIT_LFS_PATH": "C:\\Program Files\\Git LFS",
    "GRADLE_HOME": "C:\\Tools\\Gradle",
    "HOMEDRIVE": "C:",
    "HOMEPATH": "\\Users\\amran",
    "JAVA_HOME": "C:\\Program Files\\Java\\jdk1.8.0_212",
    "LOCALAPPDATA": "C:\\Users\\amran\\AppData\\Local",
    "LOGONSERVER": "\\\\NETCSE",
    "MOZ_PLUGIN_PATH": "C:\\Program Files (x86)\\Foxit Software\\Foxit Reader\\Foxit Reader\\plugins\\",
    "NUMBER_OF_PROCESSORS": "4",
    "OneDrive": "C:\\Users\\amran\\OneDrive",
    "OS": "Windows_NT",
    "Path": "C:\\Tools\\Python37\\;C:\\Tools\\Python37\\Scripts\\;C:\\Windows\\system32;C:\\Windows;C:\\Windows\\System32\\Wbem;C:\\Windows\\System32\\WindowsPowerShell\\v1.0\\;C:\\Windows\\System32\\OpenSSH\\;C:\\Tools\\Node;C:\\Program Files\\Java\\jdk1.8.0_202\\bin;C:\\Tools\\Gradle\\bin;C:\\Tools\\Php7.1.28;C:\\Programs\\QtSDK\\Tools\\mingw730_64\\bin;C:\\database\\MySQL\\bin;C:\\android\\sdk\\platform-tools;C:\\Program Files\\Git\\cmd;C:\\Program Files\\Git\\mingw64\\bin;C:\\Program Files\\PuTTY\\;C:\\Tools\\Cmake\\bin;C:\\Tools\\OpenCV\\x64\\mingw\\bin;C:\\Tools\\Netcat;C:\\Tools\\Redis;C:\\Tools\\FFmpeg\\bin;C:\\Program Files\\Git\\usr\\bin;C:\\Programs\\Dotnet;C:\\Windows\\Microsoft.NET\\Framework64\\v4.0.30319;C:\\database\\Mongo\\bin;C:\\Program Files (x86)\\Windows Kits\\10\\Windows Performance Toolkit\\;C:\\Program Files\\dotnet\\;C:\\Program Files\\Microsoft SQL Server\\130\\Tools\\Binn\\;C:\\Program Files\\Java\\jdk1.8.0_212\\bin;C:\\Tools\\apache\\bin;C:\\Program Files\\Git LFS;C:\\Programs\\Octave;C:\\ProgramData\\ComposerSetup\\bin;C:\\Program Files\\Mercurial;C:\\Users\\amran\\AppData\\Local\\Microsoft\\WindowsApps;C:\\Programs\\Microsoft VS Code\\bin;C:\\Users\\amran\\.dotnet\\tools;C:\\Users\\amran\\AppData\\Roaming\\Composer\\vendor\\bin;C:\\Users\\amran\\AppData\\Local\\GitHubDesktop\\bin",
    "PATHEXT": ".COM;.EXE;.BAT;.CMD;.VBS;.VBE;.JS;.JSE;.WSF;.WSH;.MSC;.PY;.PYW",
    "PROCESSOR_ARCHITECTURE": "AMD64",
    "PROCESSOR_IDENTIFIER": "Intel64 Family 6 Model 61 Stepping 4, GenuineIntel",
    "PROCESSOR_LEVEL": "6",
    "PROCESSOR_REVISION": "3d04",
    "ProgramData": "C:\\ProgramData",
    "ProgramFiles": "C:\\Program Files",
    "ProgramFiles(x86)": "C:\\Program Files (x86)",
    "ProgramW6432": "C:\\Program Files",
    "PROMPT": "$P$G",
    "PSModulePath": "C:\\Program Files\\WindowsPowerShell\\Modules;C:\\Windows\\system32\\WindowsPowerShell\\v1.0\\Modules",
    "PUBLIC": "C:\\Users\\Public",
    "SESSIONNAME": "Console",
    "SystemDrive": "C:",
    "SystemRoot": "C:\\Windows",
    "TEMP": "C:\\Users\\amran\\AppData\\Local\\Temp",
    "TMP": "C:\\Users\\amran\\AppData\\Local\\Temp",
    "USERDOMAIN": "NETCSE",
    "USERDOMAIN_ROAMINGPROFILE": "NETCSE",
    "USERNAME": "amran",
    "USERPROFILE": "C:\\Users\\amran",
    "windir": "C:\\Windows"
  },
  "sharedObjects": [
    "C:\\Tools\\Node\\node.exe",
    "C:\\Windows\\SYSTEM32\\ntdll.dll",
    "C:\\Windows\\System32\\KERNEL32.DLL",
    "C:\\Windows\\System32\\KERNELBASE.dll",
    "C:\\Windows\\System32\\WS2_32.dll",
    "C:\\Windows\\System32\\RPCRT4.dll",
    "C:\\Windows\\System32\\ADVAPI32.dll",
    "C:\\Windows\\System32\\msvcrt.dll",
    "C:\\Windows\\System32\\sechost.dll",
    "C:\\Windows\\SYSTEM32\\dbghelp.dll",
    "C:\\Windows\\System32\\USER32.dll",
    "C:\\Windows\\System32\\ucrtbase.dll",
    "C:\\Windows\\System32\\win32u.dll",
    "C:\\Windows\\System32\\GDI32.dll",
    "C:\\Windows\\System32\\gdi32full.dll",
    "C:\\Windows\\System32\\msvcp_win.dll",
    "C:\\Windows\\System32\\PSAPI.DLL",
    "C:\\Windows\\System32\\CRYPT32.dll",
    "C:\\Windows\\System32\\MSASN1.dll",
    "C:\\Windows\\SYSTEM32\\IPHLPAPI.DLL",
    "C:\\Windows\\System32\\bcrypt.dll",
    "C:\\Windows\\SYSTEM32\\USERENV.dll",
    "C:\\Windows\\System32\\profapi.dll",
    "C:\\Windows\\SYSTEM32\\WINMM.dll",
    "C:\\Windows\\SYSTEM32\\WINMMBASE.dll",
    "C:\\Windows\\System32\\cfgmgr32.dll",
    "C:\\Windows\\System32\\IMM32.DLL",
    "C:\\Windows\\System32\\powrprof.dll",
    "C:\\Windows\\system32\\uxtheme.dll",
    "C:\\Windows\\System32\\combase.dll",
    "C:\\Windows\\System32\\bcryptPrimitives.dll",
    "C:\\Windows\\system32\\mswsock.dll",
    "C:\\Windows\\System32\\kernel.appcore.dll",
    "C:\\Windows\\system32\\napinsp.dll",
    "C:\\Windows\\system32\\pnrpnsp.dll",
    "C:\\Windows\\SYSTEM32\\DNSAPI.dll",
    "C:\\Windows\\System32\\NSI.dll",
    "C:\\Windows\\System32\\winrnr.dll",
    "C:\\Windows\\system32\\NLAapi.dll",
    "C:\\Windows\\system32\\wshbth.dll"
  ]
}
```
