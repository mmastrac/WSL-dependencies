# Hard-to-find WSL Headers

These headers are MIT licensed, but only available through nuget. This is an extracted version of the nuget package.

## Tree

```
├── build
│   └── native
│       ├── bin
│       │   ├── wsldeps.dll
│       │   └── wsldeps.pdb
│       ├── include
│       │   ├── lxcore
│       │   │   ├── lxbusapi.h
│       │   │   └── lxcoreapi.h
│       │   ├── Windows
│       │   │   ├── p9rdr.h
│       │   │   └── wslsupport.h
│       │   └── wsldeps.h
│       └── lib
│           └── wsldeps.lib
├── doc
│   └── README.MD
├── microsoft.wsl.dependencies.amd64fre.10.0.27820.1000-250318-1700.rs-base2-hyp.nupkg
├── microsoft.wsl.dependencies.amd64fre.10.0.27820.1000-250318-1700.rs-base2-hyp.nupkg.sha512
└── microsoft.wsl.dependencies.amd64fre.nuspec
```

## Package

```
<?xml version="1.0" encoding="utf-8"?>
<package xmlns="http://schemas.microsoft.com/packaging/2011/10/nuspec.xsd">
  <metadata>
    <id>Microsoft.WSL.Dependencies.amd64fre</id>
    <version>10.0.27820.1000-250318-1700.rs-base2-hyp</version>
    <authors>Microsoft</authors>
    <owners>Microsoft</owners>
    <requireLicenseAcceptance>false</requireLicenseAcceptance>
    <license type="expression">MIT</license>
    <licenseUrl>https://licenses.nuget.org/MIT</licenseUrl>
    <readme>doc\README.MD</readme>
    <projectUrl>https://github.com/microsoft/WSL</projectUrl>
    <description>This package contains various headers and librairies needed to build WSL.</description>
    <copyright>(C) Microsoft Corporation. All rights reserved.</copyright>
  </metadata>
</package>
```
