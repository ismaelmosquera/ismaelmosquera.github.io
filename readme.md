
## Ismael Mosquera Rivera on GitHub   


This is my page on GitHub.  
I have some repositories in GitHub:  
>  
> - [cwmidi](https://github.com/ismaelmosquera/cwmidi/) MIDI Programming for Windows in C  
> - [linearsys](https://github.com/ismaelmosquera/linearsys/) Solving Linear Systems With C  
> - [imrlib](https://github.com/ismaelmosquera/imrlib/) Java IMR-LIB  
> - [imrsnd](https://github.com/ismaelmosquera/imrsnd/) Sound Programming for Windows With C++  
> - [mp3transfer](https://github.com/ismaelmosquera/mp3transfer/) Mp3 Transfer With Java  
> - [number](https://github.com/ismaelmosquera/number/) A comprehensive set of mathematical functions coded from the scratch.  
>  
  
### *cwmidi*  
  

The code in this repository implements a small MIDI ( Musical Instrument Digital Interface ) subsystem.  
There are types defined for any MIDI data, support for SMF ( Standard Midi File ) I/O and also a MIDI player  
capable to reproduce any SMF.  
There is also a drum machine simulator.  
  
  
### *linearsys*  
  
This small library written in C language has functionality to efficiently solve NxN linear system equations.  
In addition, there are support to compute the most common operations applied to matrices and vectors,  
and storage too.  
Skills to solve linear systems of equations:  
>  
> - Cramer's rule.  
> - Gaussian elimination.  
>  - LU decomposition.  
> - QR factorization.  
>  
  
You also can compute eigenvalues and eigenvectors.  
>  
> - Find the maximum eigen for a matrix using the Power Method.  
> - Find the hole eigensystem for a matrix using  the QR Algorithm.  
>  
  
  Compute SVD ( Singular Value Decomposition ) for a MxN matrix.  
A SVD is as follows:  
M = UDV^t  
where  
> - U is an orthonormal matrix having the left singular vectors of M.  
> - D ( Sigma ) has the singular values of M listed in its main diagonal, and the rest of values set to zero.  
> - V is an orthonormal matrix having the right singular vectors of M.  
>  
  
Compute the pseudoinverse of a MxN matrix using SVD.  
Get the nearest orthogonal matrix for a NxN ( square ) matrix.  
  
### *imrlib*  
  
This library written in the Java language has several packages ( IMR stands for Ismael Mosquera Rivera ).  
Packages in the library:  
>  
> - imr.matrix  
> - imr.plot  
> - imr.sigslot  
> - imr.sound  
> - imr.sound.audio  
> - imr.sound.audio.analysis  
> - imr.sound.audio.filter  
> - imr.sound.audio.synthesis  
> - imr.sound.audio.window  
> - imr.sound.midi  
> - imr.util  
>  
  
The imr.matrix package has functionality like the one in the 'linearsys' already mentioned repository, but this time coded in Java.  
There are also a little audio and MIDI subsystem with functionality to manage audio and MIDI.  
It has support to manage audio devices, storage, and additive synthesis and synthesis by modulation etc.  
The imr.util package contains some useful classes, like the iArray, with functionality to resize,  
clone, get chuncks for all the primitive data types.  
There are more already implemented classes and we are working to add more functionality to this library.  
There is an API ( Application Programming Interface ) with all the documentation generated with the 'javadoc' tool.
We encourage you to try the already compiled examples to know more about each subject.  
  
  
### *imrsnd*  
  
This repository contains a small subsystem to manage audio and MIDI, this time, written in C++  
  
  
### *mp3transfer*  
  
This repository has a server and a client applications working together in order to transfer and play  
mp3 transfered through a communication channel.  
It uses sockets to transfer the audio data.  
The server has a repository with mp3 files and runs listening in an already known port.  
The server has capability to response to multiple clients concurrently.  
  
  
### *number*  
  
  
This repository was created, mainly, for educational pourposes.  
Actually, it is a representation of the five number sets:  
>  
> - Natural ( N ).  
> - Integer (Z ).  
> - Rational ( Q ).  
> - Real ( R ).  
> - Complex ( C ).  
>  
  
Looking in this repository, you can know how to implement the most used mathematical functions from the scratch.  
   
We encourage you to look at the readme files to know more about how to use it.  
  
  
GitHub repositories: [github.com/ismaelmosquera](https://github.com/ismaelmosquera/)  
  
    
    Ismael Mosquera Rivera has a degree in Computer Science by Pompeu Fabra University; Barcelona - Spain.  
    He is, currently, interesting in Numerical Analysis, Audio and MIDI programming,.   
  
You can e-mail me at:  
ismael.mosquera@gmail.com  

    
    