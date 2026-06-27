# The Cathode Ray Tube (CRT)

## Overview

The **Cathode Ray Tube (CRT)** is an electronic display device that converts **electrical signals** into **visual images** on a phosphor-coated screen. It works by generating an electron beam, controlling its movement, and directing it onto the screen to create images.


## Functions of CRT Components

| Component | Function |
|-----------|----------|
| **Pin** | Provides the electrical power supply to the CRT. |
| **Cathode** | Produces electrons when heated. |
| **Heater** | Heats the cathode so it can emit electrons. |
| **Grid** | Controls the flow of electrons. It adjusts the number of electrons reaching the screen, which controls the screen brightness. |
| **Pre-Accelerating Anode** | Increases the speed of electrons as they move away from the cathode. |
| **Focusing Anode** | Focuses the electron beam and prevents it from spreading. |
| **Electron Gun** | A combination of the cathode, heater, grid, and anodes. It generates, accelerates, and controls the electron beam. |
| **Electron Beam** | Travels toward the screen at high speed and produces the image when it strikes the phosphor coating. |
| **Vertical Deflection Plate** | Moves the electron beam upward and downward. |
| **Horizontal Deflection Plate** | Moves the electron beam left and right. |
| **Aquadag Coating** | Reduces unwanted electron effects, collects secondary electrons, and improves overall CRT performance. |
| **Phosphor Screen** | Emits light when struck by the electron beam, creating the visible image. |


## Working Principle

The CRT operates through the following steps:

1. The **heater** heats the **cathode**.
2. The heated cathode emits electrons.
3. The **grid** controls the number of electrons passing through.
4. The **pre-accelerating anode** increases the speed of the electrons.
5. The **focusing anode** narrows the electron beam.
6. The **vertical** and **horizontal deflection plates** direct the beam to the required position on the screen.
7. The electron beam strikes the **phosphor screen**.
8. The phosphor emits light, producing the required image.

### Summary

A **Cathode Ray Tube (CRT)** converts electrical signals into visible images by generating and controlling an electron beam. Different components inside the CRT work together to accelerate, focus, and direct the beam toward the phosphor-coated screen, where light is produced to display images.

---

# Fluorescence, Phosphorescence and Persistence

## Overview

These are important properties of the **phosphor coating** inside a **Cathode Ray Tube (CRT)**. They determine how the screen produces and maintains visible images.

---

## Fluorescence

**Fluorescence** is the light produced by the phosphor **while the electron beam is striking the screen**.

### Characteristics

- Appears instantly when the electron beam hits the phosphor.
- Lasts for **less than 1 millisecond**.
- Produces the immediate visible image on the screen.

---

## Phosphorescence

**Phosphorescence** is the light that **remains after the electron beam stops striking the screen**.

### Characteristics

- Continues glowing even after the electron beam is removed.
- Gradually fades away.
- Usually lasts for **15–20 milliseconds**.

---

## Persistence

**Persistence** is the **time required for the phosphor's brightness to decrease to 10% of its original intensity after the electron beam is removed.**

### Types of Persistence

| Type | Description |
|------|-------------|
| **High Persistence** | The light remains visible for a longer time, resulting in **less flicker** and allowing a **lower refresh rate**. |
| **Low Persistence** | The light fades quickly, causing **more flicker** and requiring a **higher refresh rate**. |

---

## Flicker

**Flicker** is the visible **blinking or flashing effect** on the screen that occurs when the **refresh rate is too low**.

### Cause

- Low refresh rate
- Fast fading of phosphor light (low persistence)

### Solution

- Increase the refresh rate.
- Use a phosphor with higher persistence.


### Summary

| Term | Definition | Duration |
|------|------------|----------|
| **Fluorescence** | Light produced while the electron beam is hitting the phosphor. | Less than **1 ms** |
| **Phosphorescence** | Light that remains after the electron beam is removed. | About **15–20 ms** |
| **Persistence** | Time taken for brightness to fall to **10%** after the beam is removed. | Depends on the phosphor material |
| **Flicker** | Blinking effect caused by a low refresh rate. | Occurs when refresh rate is insufficient |

---

# Raster Display

## Overview

A **Raster Display** is a display system where the screen is divided into many small picture elements called **pixels (or pels)**. Images are created by controlling the brightness of these pixels.


## Main Features

- The screen is made up of **thousands or millions of pixels**.
- Information about every pixel is stored in a **frame buffer memory**.
- Pixels are represented using **binary values**:
  - **1 = ON**
  - **0 = OFF**
- Images are formed by arranging pixels in **rows and columns**.
- The display scans the screen **line by line**, starting from the **top-left corner** and moving to the **bottom-right corner**.

---

## Pixel Representation

Each pixel contains the following information:

| Property | Description |
|----------|-------------|
| **Coordinates (x, y)** | Specifies the pixel's position on the screen. |
| **Intensity Value** | Determines the brightness of the pixel. |

---

# Vertical and Horizontal Retrace

After drawing the image, the electron beam must return to continue scanning. This return movement is called **retrace**.

## Horizontal Retrace

**Horizontal Retrace** is the process in which the electron beam **returns to the beginning of the next line** after completing one horizontal scan line.

### Characteristics

- Happens after each horizontal line is drawn.
- Moves the beam from the **end of one line** to the **start of the next line**.
- No image is drawn during this movement.

---

## Vertical Retrace

**Vertical Retrace** is the process in which the electron beam **returns to the top-left corner of the screen** after scanning the entire display.

### Characteristics

- Occurs after the whole screen has been scanned.
- Moves the beam from the **bottom-right corner** back to the **top-left corner**.
- A new screen refresh begins after the retrace is completed.



### Summary

| Term | Description |
|------|-------------|
| **Raster Display** | A display system that creates images using a grid of pixels. |
| **Pixel** | The smallest picture element of a display. |
| **Frame Buffer** | Memory that stores information about every pixel on the screen. |
| **Horizontal Retrace** | Returns the electron beam to the beginning of the next line. |
| **Vertical Retrace** | Returns the electron beam to the top-left corner after the entire screen is scanned. |

---
# Color CRT Monitors

## Overview

**Color CRT (Cathode Ray Tube) Monitors** use special techniques to produce different colors on the screen. There are **two main methods** used in color CRT displays:

1. **Beam Penetration Method**
2. **Shadow Mask Method**

---

## 1. Beam Penetration Method

### Working Principle

The **Beam Penetration Method** uses **two layers of phosphor** inside the CRT screen:

- **Red**
- **Green**

The color displayed depends on the **speed (energy)** of the electron beam.


### Color Production

| Electron Beam Speed | Color Produced |
|---------------------|----------------|
| **Low Speed** | Red |
| **Medium Speed** | Orange or Yellow |
| **High Speed** | Green |

### Advantages

- Simple design
- Less expensive
- Easy to manufacture


### Disadvantages

- Produces only a limited number of colors
- Lower image quality


## Colors Produced

The Beam Penetration Method can produce only **four colors**:

- Red
- Green
- Orange
- Yellow

---

