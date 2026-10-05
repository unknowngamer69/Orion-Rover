# Rover: Orion

**Orion** is an AI-Powered rover built for exploration, robotics, ane mainly for Funn!!!

This is a group project made by:
- **Krish** designed the 3D body and mechanical parts (**CAD** & **Web UI**).
- **Shaurya** designed the custom brain and electronics (**GREG SBC & Motor Driver**).
 **Electronics Repository (GREG):** [github.com/GoTouchGra55/GREG](https://github.com/GoTouchGra55/GREG)  
 **CAD Repository (Orion Rover):** [github.com/unknowngamer69/Orion-Rover](https://github.com/unknowngamer69/Orion-Rover)

---

## What We Have Built So Far (CAD, Body & Software)

The **V1 CAD design is now 100% complete! yay** The outer shell and structural parts of the rover are divided into these sections:

### 1. Main Base & Internal Floors
The Main Base is the main body of the rover(obviously) that holds the electronics, screen, lights, and sensors.
- **Cool Shape & Smooth Edges:** Designed using chamfers and fillets for a clean, cool look.
- **2 Floor System:** The inside is divided into two floors. **Floor 1** is fixed on lower chamfers and will hold a large, powerful battery and main components and PCB, **Floor 2** has side support structures to hold the Top electronics part. Both floors has circular cutouts for easy wire routing.
- **Sensors & Cameras:** Includes cutouts for down-faced 2MP cameras (front & rear) and distance sensors (ToF) on the corners to prevent falling or crashinh into walls and objects.
- **5-Inch Screen Mount:** Holds a 5" non-touch LCD screen on the body.
- **Lighting System:** Cutouts for 2 front lights and 2 bottom lights at front and back 6 lighgs jn totoal and 1 light extra near camera.
- **Cooling Fan:** A dedicated mounting spot for a cooling fan to keep the internals from overheating.

### 2. Main-Top (Lid)
The top cover encloses the rover and has crucial sensory and audio sensors.
- **LiDAR Mount:** A cutout and screw-nut mounting system for a LiDAR sensor that sits exposed on top of the rover.
- **Spatial Audio (4 Mics):** This has four small microphones (one on each side) to accurately detect the direction of voice commands.
- **Stereo Speakers:** Includes Left and Right speaker cutouts with internal support structures for audio.

### 3. Lower Base & Wheels
The Lower Base is screwed underneath the Main Base and handles movement.
- **Motor Mounts:** Has simplified, strong structural holders for DC motors, 2 on both sides.
- **Custom Wheels:** Uniquely designed curved wheels having a custom blended 3D shape with triangular cutout for aesthetics and weight reduction.
- **Clean Wiring & Assembly:** Includes holes for passing motor wires up into the Main Base and screw mounts to fix the Upper and Lower bases together.

### 4. Top Camera Mount
- Holds the primary USB camera angled upward (for seeing faces of ita handsome creators lol) and a night light above it, with wires hidden inside its internal part.

### 5. Web Interface (Software)
- **HTML Web App:** A browser-based control panel to log into the rover.
- **Features:** Live camera feed viewing, remote movement control via arrow keys, and the ability to change the rover's digital face/emotions on the screen.

---

## Electronics: Meet GREG

The rover is powered by **GREG**, a custom Single Board Computer (SBC) and Motor Driver system designed from scratch by Shaurya.

### Main Computer (GREG SBC)
- **Processor (SoC):** Allwinner T527
- **RAM:** 2 GB Samsung LPDDR4
- **Power Management:** AXP717-family PMIC
- **Storage:** MicroSD card slot
- **Ports & Networking:** Ethernet, 2× USB-A, 1× USB-C
- **Display Support:** HDMI + 5" LCD interface
- **Cameras:** Supports up to 3 cameras (2 with multiplexing)
- **Sensors:** 6× ToF (Time-of-Flight) distance sensors + LiDAR

### Motor Driver Board
- **Microcontroller (MCU):** STM32G4
- **Motor Drivers:** 3× DRV8262
- **Motors:** Supports 6× brushed DC motors with built-in encoders

---

##  To-Do next:

- [x] Main Base CAD Design
- [x] Lower Base & Motor Mounts CAD Design
- [x] Top Camera Mount CAD Design
- [x] Wheels & Main-Top (Lid) CAD Design
- [x] Internal Compartments (Battery & Electronics Floors)
- [x] GREG SBC & Motor Driver Schematics
- [x] Initial Web UI (Camera, Movement, Emotion Control)
- [ ] PCB Routing for GREG
- [ ] Physical Assembly & Printing
- [ ] Full Autonomous Navigation Software

---

## Credits & Authors

- **Krish (CAD, 3D Design, Web UI & Component Research)** – [@unknowngamer69](https://github.com/unknowngamer69)
- **Shaurya (Electronics & Custom GREG SBC)** – [@GoTouchGra55](https://github.com/GoTouchGra55)
