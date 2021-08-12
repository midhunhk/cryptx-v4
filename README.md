# cryptx-v4
An Encryption/Decryption app written in C++, with an HTA UI

The latest Cryptx (Version 6) source code is hosted at: https://github.com/midhunhk/cryptx

## Introduction
CryptX 4.1 is fundamentally an easy to use encryption/decryption software. The first versions were very simple but did not offer many features, the most prominent of which was a password entry field. To cover all that we bring you the next milestome development from the R & D team at Centrum inc Software Solutions, Cryptx 4.1. The core functional part of this project is a 32-bit application written in C and compiled using the 32-bit Borland C++ Compiler 5.0.5.
The UI that you see is an HTA file which has been made to simplify the working of the program. We have done this program for an educational purpose. The Javascript code that produces the correct parameters for the application, developed by our R & D team after long and hard research has been made open source. So you can learn and adapt these in your own projects. Read this documentation for further details. 

## HTA 
HTA is a Microsoft® technology that allows a developer to deploy an HTML page consisting of scripts as a desktop application on Windows. The advantage is the efforts and know how required for developing the UI of the application, which is the same as that for any HTML page. The functionality or processing is imparted through scripting. For more information on the HTA technology, refer to http://msdn.microsoft.com/library/default.asp?url=/workshop/author/hta/overview/htaoverview.asp. We used this technology because the interface design is evry easy. All we have to do is design an HTML page for the UI. You should know the level of interface that a 32 - bit C program can provid. This HTA program is run by an interpreter called MSHTA.EXE located in your WINDOWS/SYSTEM32 folder in Windows NT installations and with the same name in WINDOWS/SYSTEM folder in Windows 95/98 installations. 

## RSA's MD5 Algorithm 
In this program, we use RSA's MD5 encryption algorithm to protect passwords. This program uses "RSA Data Security, Inc. MD5 Message-Digest Algorithm" under licence from RSA by mentioning this project is derived from their algorithm. 
