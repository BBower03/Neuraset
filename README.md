This is a copy of the final repository for COMP 3004 (Object-Oriented Software Engineering). This was a team project where my team was responsible for developing a "product" from a set of specifications given to us by the professor, who was acting as a client. The device is a simplified version of a neurofeedback EEG device. This device was to simulate the reading of electromagnetic brainwave signals, and deliver a small shock to the patient's brain, causing high-frequency brainwaves to lower the frequency. These types of devices are used to help treat mental health disorders like ADHD and ADD. I still don't fully understand exactly how and why the therapy itself works, but the specifics were not important to the development of our device. The client provided us with the frequencies of the shocks that are delivered to the patient, and implemented them as required, double-checking the numbers with our client as needed throughout the development process.

As a team we had to design and implement a program that functioned to our client's specifications, complete with an interface for the device itself, and a seperate PC program that provided more information about the devices current state. We were able to ask questions to the client regarding their wishes with functionality and general user interface preferences. 

Team 37:  
Brendan Bower (Myself)
Aly Matrawy  
Edwin Lau  
Matt Czarnowski  

Youtube demonstration video link: https://youtu.be/z4jCoe2tmPk

What each member worked on:

  - Brendan Bower
      - EEG waveform generation, EEG wave graphing. EEG testing buttons and functionality (Test Gamma, alpha, beta wave etc...), administering treatment, Electrode class and integrating the electrode class backend with the ui and mainwindow functionality. UML class diagram
    
  - Aly Matrawy
      - PC GUI and Buttons, saving data from session to a file, accessing date and time from file to show on session log, implemented therapy history viewing on pc, 2 Sequence Diagrams (Normal Operation of Treatment, Therapy History Viewing)
  - Edwin Lau
      - Device GUI and Buttons, New Session control flow, Time and Date settings, Use Cases, Use Case Diagram, State Diagram, 2 Sequence Diagrams (Low Battery Response, and Connection Loss)
  
  - Matt Czarnowski
      - "EEG Site Contact" UI and code, linking EEG site contact code with main device (disconnects, timer, etc), initial "external factors" panel and battery replacement code, requirements traceability matrix

Organization of the submission:
  - The directory where this README is in contains the source code
  - The 'Documentation' directory contains the documentation for the project
  - *NOTE*: QCustomPlot.h and QCustomPlot.cc are library files from the QCustomPlot library, they were not written by anyone in the group. They can be found on the QCustomPlot website. The class is used for graphing the EEG waveform within the PC interface.
