MQAdapter
=========

Message Queue Adapter for ActiveMQ dotnet client

## Environment
.Net Framework 4.6.1 or later

.Net Core 2.0 or later

.Net Standard 2.0 

AppVeyor: [![Build status](https://ci.appveyor.com/api/projects/status/r3af7vruiridp7xn/branch/master?svg=true)](https://ci.appveyor.com/project/megadotnet/mqadapter/branch/master)

## Latest Builds

Channel  | Core Framework 
-------- | :------------: 
NuGet | <a href="https://www.nuget.org/packages/Megadotnet.MessageMQ.Adapter"><img src="https://img.shields.io/nuget/v/Megadotnet.MessageMQ.Adapter.svg?style=flat"></a>


## Features
- Retry logic
- Simple API 

## Deployment
 For .nNet Core
  1. Install CentOS 7 or later version.
  2. Install .NET Core on CentOS 7 now using the following steps:

    yum install centos-release-dotnet 
    yum install rh-dotnet20
    
  To use it:

    scl enable rh-dotnet20 bash
    dotnet --info
  3. Push files to folder then FTP to target folder. Run with following stetps: 
    
    dotnet DotnetCoreClientDemo.dll

## License
Copyright (c) 2012-2018 Megadotnet Contributors

Other software included in this distribution is owned and
licensed separately, see the included license files for details.

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
