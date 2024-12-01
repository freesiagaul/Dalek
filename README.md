<div align=center><h1>Designing a Dalek: A Study in Integrating Signal Detection and Control Systems
</h1>
<p>

<img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
<a href="https://github.com/freesiagaul/monokai-pro-betterdiscord/commits/main/">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/freesiagaul/monokai-pro-betterdiscord">
</a>
<img alt="Repository size" src="https://img.shields.io/github/repo-size/freesiagaul/monokai-pro-betterdiscord">
</p>

Casey Thomas, Freesia Gaul, Sean Coulon-Clark, Aaron See, Matthew Shih,
 Jiusi Gao, Hanlin Li.

![IMG_9355](https://github.com/user-attachments/assets/a65ce7af-7dfb-46b7-94c5-c7e7d1049bf3)


<div align=left><h2></h2>


<div align=left><h2>Background</h2>

This project was a part of the DESN1000 course in 2024 at UNSW. DESN1000 is the flagship rapid prototyping course at UNSW - which brings all engineering disciplines together to work toward a common goal. The project our team focused on signal detection and control systems, taught by David Taubman. It was an incredible course for learning, and we are all grateful for him, his patience, and not lowering his standards throughout the course.

<div align=left><h2>Abstract</h2>

Signal detection and control systems are essential to electronic systems design. This report explores how these principles can be leveraged to design a Dalek. The Dalek is comprised of three key systems: a signal detector, a motor that rotates toward a target signal, and an “Extermination sequence” which audibly and visually indicates the Dalek has successfully located the target. A review of other similar projects and experimentation was conducted before describing and analysing the design concepts, which are then used to provide recommendations on replicating and furthering this design. Many methods were found to solve this problem across the analogue and digital space. Ultimately, the final design featured a signal detector that provided peak values to an Arduino, which acted as an analogue to digital converter and then carried out the signal processing. Then the Arduino output values to the control system. This value from the detector then drove the motor driver and speaker. Once the motor faces the target, the speaker breaks from signal jamming and declares “Exterminate,” with LEDs synchronised to this audio indicating the target was found. This solution worked as subsystems but could not be entirely integrated due to external factors such as time and soldering mistakes. From this, it can be determined that the provided design works in theory as subsystems and two systems. Since the problems arose from a lack of time and the testing of subsystems was positive, the design is likely functional with further work. This also means that this report may be more helpful for those beginning or actively creating a design but not for those with finished designs that require optimisation.



<div align=left><h2>Credits</h2>

This theme was inspired by:

<ul>
  <li> <a href=https://github.com/schnensch0/zelk> Zelk by schnensch0 </li>
  <li> <a href=https://github.com/refact0r/midnight-discord> Midnight by refact0r </li>
  <li> <a href=https://monokai.pro/vscode> Monokai Pro</li>
</ul>




