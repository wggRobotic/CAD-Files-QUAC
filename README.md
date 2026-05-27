This repository is going to contain all CAD files related to the QUAC robot project. The files are primarily provided in standard formats such as .STEP, making them compatible with most CAD software and easy to modify if needed.

In addition to 3D-printable components, the repository may also include parts that are not intended for 3D printing (e.g. aluminium profiles, servos and motors, or other external parts). Please refer to the file names and context to distinguish between printable and non-printable elements.

The file QUAC_fullbild shows the complete assembly of the robot and serves as a visual reference for how all components fit together. It can be used as a guide during the assembly process.

The full assembly is illustrated below:

<img src="https://github.com/user-attachments/assets/ec49fdd4-b157-44e3-a749-89fc4d332dfb" width="80%">

Note that the exact appearance may vary slightly depending on revisions or updates to individual parts.

Further updates, refinements, and additional files may be added over time as the project evolves.


<br><br>

# **Lower_Body-Structure**:

The lower body is mainly built from 20×40 aluminum profiles, providing a strong and robust base structure for the robot.
A custom-shaped 19.2 V NiMH battery pack was specifically designed and 3D-printed to fit efficiently into the available space.
This layout enables a very low center of gravity, which improves overall stability, especially in rough terrain and on obstacle elements.

<img width="700" alt="Lowerbody" src="https://github.com/user-attachments/assets/dc225dc1-d2f2-4c86-b440-4b1d3ab72397" />

## Battery
The power supply for the robot is a custom-made 19.2V NiMH battery pack which 
<img src="https://github.com/user-attachments/assets/ac27ae00-7ac8-4298-969a-0c92de542e03" width="50%"/>

## Aluminum parts
<img width="40%"  alt="image" src="https://github.com/user-attachments/assets/6aa255a5-6540-4cd9-9c1e-86c7b65404e8" />
<img width="40%"  src="https://github.com/user-attachments/assets/1dfa8d8d-8d1d-4d82-b786-3bf435f516ed" />

The profiles are connected using M5 screws, which are inserted through corner brackets and fastened into trapeze nuts inside the profile grooves. This creates a stable and adjustable connection between the aluminum profiles. The single parts, which are listed below are assembled as shown in the pictures. 

### Long Alu profiles

<img width="40%" src="https://github.com/user-attachments/assets/3807b3a9-54a5-4493-9b4e-2938a3f7051e" align="left" />  The two long aluminium profiles, each measuring 300 × 40 × 20 mm, play a crucial role in ensuring the lateral stability of the overall structure. They act as key reinforcement elements that help prevent deformation and increase rigidity under load. However, to integrate proper cable management, both profiles require manual modification at two designated locations. These sections must be carefully notched out by hand during post-processing to create sufficient space for routing cables. Precision is important here, as the cut-outs need to maintain structural integrity while still allowing clean and functional cable guidance. 
<br><br>

### Short Alu profiles 
<img width="40%" src="https://github.com/user-attachments/assets/3d85de4c-afb9-454a-96ff-c173712d2b03" align="left" />
The shorter aluminium profiles are used for several specific structural and functional purposes within the assembly. One profile measures 123 × 40 × 20 mm and is installed as a transverse (crosswise) element. It functions as a front bumper component, absorbing impact and providing structural protection. In addition, there are three profiles with dimensions of 83 × 20 × 20 mm. These are also mounted transversely. They serve different roles within the mechanism, with the central one being essential for the installation of the flipper system. Finally, there are four profiles measuring 90 × 20 × 20 mm, which are mounted longitudinally. These elements act as mounting points for the suspension system. They provide the necessary attachment interface for the springs and help distribute mechanical loads evenly throughout the structure.

## Wheels
### Wheels
### Rims
<br><br>

### [Waveshare UGV-Suspension](https://www.waveshare.com/wiki/UGV_Suspension_(A)):

The robot uses the Waveshare suspension system to improve terrain adaptability and maintain wheel contact on uneven surfaces.
This passive suspension allows better force distribution across all wheels, increasing traction and stability in rough terrain.

We also experimented with custom springs, extending the suspension travel by approximately 2 cm.
While this improves obstacle handling, especially on uneven terrain, it is still under evaluation as it slightly reduces lateral stability.

<img width="700" height="525" alt="Waveshare_Suspension" src="https://github.com/user-attachments/assets/167d4213-5d03-4482-a3f2-472adbbdbb28" />

## Flipper
<img width="40%" src="https://github.com/user-attachments/assets/3af55b8b-20af-4682-9292-9e8bb0463f8e" />
<img width="36%" src="https://github.com/user-attachments/assets/81d0e3f3-e6a9-4ce5-892d-2e4980ccf305" />

The flipper mechanism consists of a single servo motor mounted to the central 83 × 20 × 20 mm aluminium profile using a metal clamp. On the other side it has two small steel ball bearings mounted via a 3d-printed part, which function as small additional wheels. Its primary purpose is to temporarily lift the robot by a few centimetres whenever it becomes stuck or obstructed. This allows the robot to free itself from obstacles or uneven terrain and improves overall mobility and reliability during operation.

<br><br>

# **Upper_Body-Structure**:

The upper body serves as the central platform for all high-level components, including the NVIDIA Jetson Orin Nano Developer Kit, perception sensors such as the Intel RealSense D435 depth camera, and additional electronics.
Structural stability is achieved using 20×20 aluminum profiles, providing a lightweight yet rigid frame.
The design is modular and easily accessible, enabling fast iteration, maintenance, and component replacement during development and competition.
The elevated placement improves sensor field of view and system organization, while still aiming to keep the overall center of mass as low as possible.

<img width="700" alt="Upperbody" src="https://github.com/user-attachments/assets/8d4b1d3f-6975-43ff-9635-82144e072d5e" />


<br><br>

## **Manipulator Arm**:

The manipulator arm is primarily composed of 3D-printed components, enabling rapid prototyping and easy customization.
It is actuated using Waveshare ST3215 servos and equipped with a Waveshare gripper for object interaction.
To enable precise perception during manipulation tasks, multiple sensors are mounted directly on the gripper, including depth, thermal, and magnetic field sensing.
This setup allows the robot to detect and interact with objects in close proximity in a targeted and efficient manner.
<img width="773"  alt="Arm" src="https://github.com/user-attachments/assets/82a73261-ec0b-41cb-8917-b3727e566d5b" />

### Camera mount
<img width="40%" src="https://github.com/user-attachments/assets/33f7db24-388b-4f4d-8967-0194cc6b7dd7" />

The camera mount is a small 3d-printed plate that is necessary to atatch both the Intelrealsense and the thermal camera to the gripper. 

### gripper
### connection plates
### arm mount

## aluminum parts
### long profiles

<img width="40%" src="https://github.com/user-attachments/assets/9a70c280-6737-491d-b4bf-fc5be021f89a" />

### short profiles (vertical)
### corner brackets
### base plate


### bottom cover plates
### top cover plate
#### lidarhub mount

### servo bus & IMU mount

## PCBs

| Name | Beschreibung | Status |
|---|---|---|
| Idefix | Quadruped-Roboter | in Arbeit |
| N10 | Rover | getestet |
| Quac | Crawler | geplant |
