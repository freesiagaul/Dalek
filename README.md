<div align=center><h1>Designing a Dalek: Integrating Signal Detection and Control Systems
</h1>
<p>

<img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
<a href="https://github.com/freesiagaul/Dalek/commits/main/">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/freesiagaul/Dalek">
</a>
<img alt="Repository size" src="https://img.shields.io/github/repo-size/freesiagaul/Dalek">
</p>

![IMG_9355](https://github.com/user-attachments/assets/a65ce7af-7dfb-46b7-94c5-c7e7d1049bf3)


<div align=left><h2></h2>


<div align=left><h2>Background</h2>

This project was a part of the DESN1000 course in 2024 at UNSW. DESN1000 is the flagship rapid prototyping course at UNSW - which brings all engineering disciplines together to work toward a common goal. The project our team focused on signal detection and control systems, taught by David Taubman. It was an incredible course for learning, and we are all grateful for him, his patience, and not lowering his standards throughout the course.

<div align=left><h2>Abstract</h2>

Signal detection and control systems are essential to electronic systems design. This report explores how these principles can be leveraged to design a Dalek. The Dalek is comprised of three key systems: a signal detector, a motor that rotates toward a target signal, and an “Extermination sequence” which audibly and visually indicates the Dalek has successfully located the target. A review of other similar projects and experimentation was conducted before describing and analysing the design concepts, which are then used to provide recommendations on replicating and furthering this design. Many methods were found to solve this problem across the analogue and digital space. Ultimately, the final design featured a signal detector that provided peak values to a microcontroller, which acted as an analogue to digital converter and then carried out the signal processing. Then the mictrocontroller output values to the control system. This value from the detector then drove the motor driver and speaker. Once the motor faces the target, the speaker breaks from signal jamming and declares “Exterminate,” with LEDs synchronised to this audio indicating the target was found.

Sadly, for legal reasons we cannot share substantial areas of the project (as to prevent plaigarism,) but we can give a rough overview of the work we did.



<div align=left><h2>Credits</h2>

This project was comprised of:

 <table>
  <tr>
    <th> Role </th>
    <th> Signal Detection </th>
    <th> Role </th>
    <th> Control Systems </th>
   
  </tr>
  <tr>
    <td> Leader / Signal Processing & Signal Jam Programmer / Filter and Amplification Co-Lead </td>
    <td>  <a href=https://www.linkedin.com/in/freesia-g> Freesia Gaul </td>
    <td> Leader / Programmer / Motor and Audio Control Systems  </td>
    <td> <a href=https://www.linkedin.com/in/casey-elisabeth-thomas-8b460a308/> Casey Thomas </td>
  </tr>
  <tr>
      <td> Late-stage Project Leader / Lead of Filter and Amplification Designs / Signal Processing Programmer </td>
      <td> <a href=https://www.linkedin.com/in/aaron-see-6a5a3231a/> Aaron See</td>
      <td> Lead of Exterior Shell and Gear Design / Signal-Jam Co-Programmer </td>
    <td> <a href=https://www.linkedin.com/in/sean-coulon-clark-3513712b7/> Sean Coulon-Clark</td>
   </tr>
   <tr>
    <td> Amplification </td>
    <td> Matthew Shih </td>
    <td> Head of Materials </td>
    <td> Jiusi Gao</td>
  </tr>
  <tr>
      <td> Amplification Assistant </td>
    <td> Hanlin Li</td>
  </tr>

    
</table> 
