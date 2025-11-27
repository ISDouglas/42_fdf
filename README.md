
# FdF — Wireframe Model (42 School)

A lightweight 3D wireframe renderer built with **MiniLibX**, capable of displaying and manipulating 3D landscapes based on elevation maps.
This project introduces the fundamentals of computer graphics: projecting points in space, connecting them, and rendering them from a chosen viewpoint.

## 📌 **Project Overview**

The goal of FdF is the 3D representation of a landscape using a wireframe model.
Such visualizations are essential in fields like:

* **Cartography**
* **Space exploration**
* **Geology & tectonic studies**

Using **MiniLibX**, this project demonstrates:

* Window creation
* Pixel and image manipulation
* Keyboard handling
* 3D-to-2D projection
* Rendering a mesh based on map data

---

## 🚀 **Features**

### ✔️ Mandatory

* Parse `.fdf` height maps
* Render a 3D wireframe representation
* Implement **isometric projection**
* Efficient line drawing (Bresenham)
* Real-time rendering with MiniLibX

### ⭐ Bonus (Fully implemented)

* Extra projection mode
* Zoom in / zoom out
* Model translation
* Model rotation
* Height scaling
* Additional transformations
* Fully custom key control system

---

## 🛠️ **Installation & Compilation**

Clone the repository:

```bash
git clone git@github.com:ISDouglas/42_fdf.git
cd fdf
```

Compile with bonus:

```bash
make bonus
```

Clean:

```bash
make fclean
```

Rebuild:

```bash
make re
```
---

## 🕹️ **Controls**

### **Your specific implemented key bindings**

| Key       | Function                  |
| --------- | ------------------------- |
| **ESC**   | Quit window               |
| **Y / H** | Adjust height (Z-scale)   |
| **A / Z** | Adjust X-axis translation |
| **T / R** | Adjust model scale        |

---

## 🙌 **Credits**

Project completed as part of **42 School’s curriculum**.
Developed using **MiniLibX** and standard C.

---
