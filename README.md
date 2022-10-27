# ExecRemoteAssembly
Execute Remote Assembly with args passing and with AMSI and ETW patching  

1 - the ExecRemoteAssembly is created only to run .NET assemblies , that are based on C# , to run binaries that are based on C/C++/ASM u can use the other project https://github.com/D1rkMtr/FilelessRemotePE  
2 - the ExecRemoteAssembly accept only URI of type https://domain.name/PathToUri not [https/http]://ip:port/pathtoUri nor [https/http]://ip/pathtoUri  

![ExecAMSI](https://user-images.githubusercontent.com/110354855/190879568-2f8587a6-59f8-4d4f-8954-cbeea472c5e2.png)

# Credits
All the Credits goes to:  
https://github.com/mez-0/InMemoryNET  
This is an improved version of this project that supports AMSI & ETW patching and URI parsing
