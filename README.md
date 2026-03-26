This repository contains (or will contain) all CAD files related to the QUAC robot project. The files are primarily provided in standard formats such as .STEP, making them compatible with most CAD software and easy to modify if needed.

In addition to 3D-printable components, the repository may also include parts that are not intended for 3D printing (e.g. aluminium profiles, servos and motors, or other external parts). Please refer to the file names and context to distinguish between printable and non-printable elements.

The file QUAC_fullbild shows the complete assembly of the robot and serves as a visual reference for how all components fit together. It can be used as a guide during the assembly process.

The full assembly is illustrated below:

<img src="https://github.com/user-attachments/assets/ec49fdd4-b157-44e3-a749-89fc4d332dfb" width="80%">

Note that the exact appearance may vary slightly depending on revisions or updates to individual parts.

Further updates, refinements, and additional files may be added over time as the project evolves.


<br><br>

**Lower_Body-Structure**:

The lower body is mainly built from 20×40 aluminum profiles, providing a strong and robust base structure for the robot.
A custom-shaped 19.2 V NiMH battery pack was specifically designed and 3D-printed to fit efficiently into the available space.
This layout enables a very low center of gravity, which improves overall stability, especially in rough terrain and on obstacle elements.

<img width="700" height="555" alt="Lowerbody" src="https://github.com/user-attachments/assets/dc225dc1-d2f2-4c86-b440-4b1d3ab72397" />



<br><br>

[Waveshare UGV-Suspension](https://www.waveshare.com/wiki/UGV_Suspension_(A)):

The robot uses the Waveshare suspension system to improve terrain adaptability and maintain wheel contact on uneven surfaces.
This passive suspension allows better force distribution across all wheels, increasing traction and stability in rough terrain.

We also experimented with custom springs, extending the suspension travel by approximately 2 cm.
While this improves obstacle handling, especially on uneven terrain, it is still under evaluation as it slightly reduces lateral stability.

<img width="700" height="525" alt="Waveshare_Suspension" src="https://github.com/user-attachments/assets/167d4213-5d03-4482-a3f2-472adbbdbb28" />



<br><br>

**Upper_Body-Structure**:

The upper body serves as the central platform for all high-level components, including the NVIDIA Jetson Orin Nano Developer Kit, perception sensors such as the Intel RealSense D435 depth camera, and additional electronics.
Structural stability is achieved using 20×20 aluminum profiles, providing a lightweight yet rigid frame.
The design is modular and easily accessible, enabling fast iteration, maintenance, and component replacement during development and competition.
The elevated placement improves sensor field of view and system organization, while still aiming to keep the overall center of mass as low as possible.

<img width="700" height="618" alt="Upperbody" src="https://github.com/user-attachments/assets/8d4b1d3f-6975-43ff-9635-82144e072d5e" />


<br><br>

**Manipulator Arm**:

The manipulator arm is primarily composed of 3D-printed components, enabling rapid prototyping and easy customization.
It is actuated using Waveshare ST3215 servos and equipped with a Waveshare gripper for object interaction.
To enable precise perception during manipulation tasks, multiple sensors are mounted directly on the gripper, including depth, thermal, and magnetic field sensing.
This setup allows the robot to detect and interact with objects in close proximity in a targeted and efficient manner.
<img width="773" height="890" alt="Arm" src="https://github.com/user-attachments/assets/82a73261-ec0b-41cb-8917-b3727e566d5b" />

