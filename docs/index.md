# Introduction

Use Provisioning Services' programming interfaces to manage your implementation from a command line or from scripts. Only users with correct administrative privileges can use programming commands. Non-administrators, that do not have elevated privileges and attempt to use these commands, will receive the ‘Invalid access’ message.

Four different programming interfaces exist:

- Management Command Line Interface (SOAP SERVER)
- Simple Object Access Protocol (SOAP) Server Programmer Interface
- PowerShell Programmer Interface with Objects
- PowerShell Programmer Interface (Deprecated)

This document provides the information needed to use this interface.

## Using the SOAP Server Interface
Use the information that follows to manage a Provisioning Service’s implementation from the SOAP SERVER interface.
The SOAP API permits you to do everything that can be done using the Console.

## Client Proxy
If Visual Basic or C# is going to be used to interface with the SOAP interface, the svcutil.exe tool, provided with Microsoft Visual Studio can be used to generate the client side proxy.

`svcutil.exe /out:CommandSet.cs http://host_name:8000/pvs/mapi/commandset`
`svcutil.exe /language:vb /out:CommandSet.bas http://host_name:8000/pvs/mapi/commandset`

Where `host_name` is the server’s hostname.

