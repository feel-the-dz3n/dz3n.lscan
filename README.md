# dz3n.lscan (Lamescan fork)

Program to bruteforce RAdmin servers. Only for scanning your own servers for vulnerabilities!
Original Lamescan seems to be dead since 2010. All links and redsh.ru website are dead.

# Building

Project is for Visual Studio 2017. Windows SDK is 8.1.
SRP is broken and project won't build.

Components:

- OpenSSL [(tutorial)](https://stackoverflow.com/questions/45494630/how-to-build-openssl-on-windows-with-visual-studio-2017)
  There are compiled libraries in lib folder.
  
- Secure Remote Password Protocol (SRP) [(repo)](https://github.com/rxwen/srp)
  Build instructions are in win32/README file

# Credits

**Lamescan** by **redsh** [(AntiChat)](https://forum.antichat.ru/members/121094/) 

**dz3n.lscan** based on Lamescan by **Dz3n** [(GitHub)](https://github.com/feel-the-dz3n)

The [original repository](https://github.com/Vulnerability-scanner/lscan3_CLI_src) where the lost source code was found
