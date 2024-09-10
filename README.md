# Ghidra in Kali
Installing and using Ghidra Software Reverse Engineering Framework in Kali Linux

The installation guide didnt worked for me, i found a workaround and manage to succesfully get the software running 

Original guidance provided at: https://github.com/NationalSecurityAgency/ghidra

<html>
<h2>Download</h2>

* Go to the <a href="https://www.oracle.com/java/technologies/downloads/">Oracle website</a> and download the .deb 

* Download Ghidra from the official source <a href="https://github.com/NationalSecurityAgency/ghidra/releases">here</a>
</html>

<h2> Install and run </h2>

* Install the Java JDK that we just downloaded with the command: " sudo dpkg -i jdk-22_linux-x64_bin.deb " <br>

* On the terminal you can check that the JDK in installed with this command: update-java-alternatives -l
  <br>It will display something like this:
    
        java-1.21.0-openjdk-amd64      2111       /usr/lib/jvm/java-1.21.0-openjdk-amd64
        java-1.23.0-openjdk-amd64      2311       /usr/lib/jvm/java-1.23.0-openjdk-amd64
        jdk-22.0.2-oracle-x64          369115136  /usr/lib/jvm/jdk-22.0.2-oracle-x64
  
* Extract the ghidra compressed file that we downloaded with the command: " unzip file name ".
* Navigate to the decompressed folder with the command: " cd ghidra_XX.X.X_PUBLIC " (Change this last part after cd for the name on your folder)
* Simply run the command to execute the program: " bash ghidraRun "

### After that the program will pop at the screen and you are ready to go
