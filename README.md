# Rover: Orion

**Orion** is an AI-Powered rover built for exploration, robotics, ane mainly for Funn!!!
![Orion Image](https://cdn.hackclub.com/01a1d407-dc29-7359-b8d8-0c4ef0f3f68b/image.png)
---

## Its Features (CAD, Body & Software)

The V1 CAD design is now 100% complete! yay, the outer shell and all cad parts of the rover are divided into these parts:

### 1. Main Base & Internal Floors:
The Main Base is the main body of the rover(obviously) that holds the electronics, screen, lights, and sensors. It has floors in it to keep various things seprate, Mounts and holes for various sensors and cameras and lights and cooling fan and a screen.

### 2. Main-Top (Lid)
The top cover encloses the rover and has crucial sensory and audio sensors. It has holes and mounts for speakers, mic and LiDAR.

### 3. Lower Base & Wheels
The Lower Base is screwed underneath the Main Base and handles movement. It has mounts and holes for motors and we made wheels for it as well with holes for wire passing.

### 4. Top Camera Mount
Holds the primary USB camera angled upward (for seeing faces of its handsome creators lol) and a night light above it, with wires hidden inside its internal part.

### 5. Web Interface (Software)
A browser-based control panel to log into the rover. It has features of Live camera feed viewing, remote movement control via arrow keys, and the ability to change the rover's digital face/emotions on the screen.

---

## Electronics- GREG

The rover has GREG, a custom Single Board Computer (SBC) and Motor Driver system designed from scratch by Shaurya.

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

## Credits & Authors

- **Krish (CAD, 3D Design, Web UI & Component Research)** – [@unknowngamer69](https://github.com/unknowngamer69)
- **Shaurya (Electronics & Custom GREG SBC)** – [@GoTouchGra55](https://github.com/GoTouchGra55)
