# .Net Static Web Server

In this repository are the source code and the compiled binaries for a .Net Core Statis web server. This was initially made for transferring files between computers when I could not otherwise use file sharing, but it has other potential uses. 

When using, specify the port, network adapter, and optionally the root folder that it should use. The program compiles to a binary named `www.exe.` Example usage would be 

`xf.exe urls="http://0.0.0.0:8889" webroot=c:\temp\myFolder\`

Read more at https://j2i.net