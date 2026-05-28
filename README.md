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

## Wheels & Rims
<img width="34%" alt="IMG_2936" src="https://github.com/user-attachments/assets/4b19484b-3e7f-4ce7-b1a8-5903d8facbe6" align="left" />
<img width="40%" alt="IMG_2935" src="https://github.com/user-attachments/assets/689ddea6-2a44-4c56-b480-5cbdcd3a9f81" />
<br><br>
Overcoming uneven terrain requires more than just power — it demands exceptional grip, stability, and precise control. To achieve this, we developed a set of custom-designed rims specifically engineered to integrate seamlessly with the [DDSM115 hub motors](https://github.com/wggRobotic/Team-Docs/wiki/4.-Quac-%E2%80%93-All-Terrain-Crawler#wheel-motors) and the selected wheel assemblies. By tailoring the rim geometry to both the motor interface and the tire specifications, we were able to maximize traction, improve load distribution, and ensure reliable performance across challenging surfaces such as gravel, dirt, grass, and rocky terrain.
This custom solution not only enhances the vehicle’s ability to maintain stability on unpredictable ground, but also improves durability and overall driving confidence. The tight integration between the rims, hub motors, and wheels minimizes mechanical play and optimizes torque transfer, allowing the system to respond efficiently even under demanding off-road conditions.






<br><br>

### [Waveshare UGV-Suspension](https://www.waveshare.com/wiki/UGV_Suspension_(A)):
<img width="40%" alt="Waveshare_Suspension" src="https://github.com/user-attachments/assets/167d4213-5d03-4482-a3f2-472adbbdbb28" align="left"/>

The robot uses the Waveshare suspension system to improve terrain adaptability and maintain wheel contact on uneven surfaces.
This passive suspension allows better force distribution across all wheels, increasing traction and stability in rough terrain.

We also experimented with custom springs, extending the suspension travel by approximately 2 cm.
While this improves obstacle handling, especially on uneven terrain, it is still under evaluation as it slightly reduces lateral stability.


<br><br><br><br><br><br>


## Flipper
<img width="40%" src="https://github.com/user-attachments/assets/3af55b8b-20af-4682-9292-9e8bb0463f8e" />
<img width="36%" src="https://github.com/user-attachments/assets/81d0e3f3-e6a9-4ce5-892d-2e4980ccf305" />
<br><br>
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
<img width="40%" src="https://github.com/user-attachments/assets/a1b6f383-7b2a-4640-b64e-8ee4dd69a811" align="left" />
<img width="40%"  src="https://github.com/user-attachments/assets/2cc44060-0e77-4ef3-ad3f-62780b761d6d" />


The camera mount is a small 3d-printed plate that is necessary to atatch both the Intelrealsense and the thermal camera to the gripper. 
<br><br>

### Gripper
The custom gripper design was inspired by Festo’s bionic [Fin Ray gripper](https://www.youtube.com/watch?v=JAyPTIIpFiA). It utilizes a triangular structure based on the geometry of fish fins, which provides passive compliance. This flexibility allows the gripper to conform seamlessly to the contours of an object. Furthermore, the inherent flexing mechanism protects the servo motors from damage, preventing mechanical strain if the gripper over-closes.

<img width="50%" alt="Gripper-A-Fisch v16" src="https://github.com/user-attachments/assets/431c462f-9136-4871-943b-17a5f320799e" />
 

<img width="40%" alt="FischGripperBacke5FinnenFlach v7" src="https://github.com/user-attachments/assets/61ef3fad-5496-4e1f-96c8-3fcd966949ae" align="left"/>

Through many iterations, we learned which geometric facts matter by constructing the gripper. It is important that the cross-connections are perpendicular to the angle bisector of the tip. Also, you can change the stiffness of the gripper with the number of cross-connections. We tried at first 7 cross-connections, which was too rigid. So we decreased them through many iterations and finished with the iteration with just 5 cross-connections, which seemed to be a nice compromise.

<br><br>

### Connection plates
### Arm mount

## Aluminum parts
### Profiles
<img width="40%" src="https://github.com/user-attachments/assets/9a70c280-6737-491d-b4bf-fc5be021f89a" align="left" />
The upper body frame is constructed from aluminium profiles and reinforced with corner brackets to ensure a lightweight yet stable structure.
The two long horizontal profiles measure 300 × 20 × 20 mm and form the main supporting structure of the upper body. Mounted onto them are several vertical profiles measuring 60 × 20 × 20 mm, which provide additional rigidity and serve as mounting points for other components.
Corner brackets are installed between the horizontal and vertical elements to strengthen the joints, improve stiffness, and maintain precise alignment throughout the frame.
<br><br>

### Base plate
<img width="50%"  alt="base_plate" src="https://github.com/user-attachments/assets/9a459aa7-ccb5-4802-8134-30ae9322fccd" align="left" />
<img width="40%" alt="Zeichnung_Aluplatte_WGG" src="https://github.com/user-attachments/assets/8eaa1301-78a4-48b5-a0a6-b8fe71e946ba" />

The baseplate was custom-manufactured by Dehn in cooperation with our team based on our technical design specifications. It is made from a 165 × 300 × 5 mm aluminium plate and forms the central structural foundation of the robot.
The plate includes precisely machined mounting holes for attaching structural components as well as dedicated openings for cable routing, enabling clean and organized wiring throughout the system. Due to its thickness and material choice, the baseplate provides excellent rigidity and stability while still maintaining a relatively low weight. The exact dimensions and hole positions can be taken from the technical drawing.


### Bottom cover plates
<img width="40%" alt="bottom_cover_plates" src="https://github.com/user-attachments/assets/c0f34376-d220-4b9a-b499-64e8d355e7d5" align="left" />


### Top cover plate
#### Lidarhub mount

### servo bus & IMU mount

## PCBs

| Name | Beschreibung | Status |
|---|---|---|
| Idefix | Quadruped-Roboter | in Arbeit |
| N10 | Rover | getestet |
| Quac | Crawler | geplant |
