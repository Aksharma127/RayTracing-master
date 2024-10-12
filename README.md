
# Ray Tracing Project

## Overview

This project is a real-time ray tracing engine written in C++, designed to render realistic lighting, shadows, and reflections using ray tracing techniques. It aims to provide an accessible and performant implementation of ray tracing that can be built and run on modern hardware.

The foundation of this project was built using knowledge from various notable resources, including:

- **Cherno's YouTube Channel**: A fantastic resource for learning graphics programming, especially for C++.
- **[Ray Tracing in One Weekend](https://raytracing.github.io/books/RayTracingInOneWeekend.html)**: This book provides an excellent introduction to ray tracing and was instrumental in developing the core algorithms.
- Additional references from various advanced graphics programming texts available online.

## Features

- **Real-Time Rendering**: Supports real-time updates with adjustable lighting and material properties.
- **Physically-Based Materials**: Includes support for reflective, refractive, and emissive surfaces.
- **Configurable Scene Parameters**: Customize scene objects, materials, and lighting using intuitive controls.
- **Multi-Platform Support**: Currently supports Windows 10/11 with Visual Studio 2022. Additional platform support is in progress.

## Building and Running the Project

### Requirements

- **Visual Studio 2022** (or higher)
- **Windows 10/11**
- **[Vulkan SDK](https://vulkan.lunarg.com/)**: Make sure the Vulkan SDK is installed.

### Instructions

1. Clone the repository recursively:

   ```bash
   git clone --recursive https://github.com/Aksharma127/RayTraacing.git
   ```

2. Run the setup script:

   ```bash
   scripts/Setup.bat
   ```

3. Open the project:

   - Launch `RayTracing.sln` in Visual Studio.
   - Change the build configuration to **Release** (for best performance).
   - Press **F5** to run.

   > **Note:** The **Debug** configuration may be slow due to the high computational cost of ray tracing.

## Additional Resources

To explore further and enhance your understanding of ray tracing in C++, consider the following resources:

- **[Real-Time Rendering](https://www.realtimerendering.com/)**: This book covers various algorithms and techniques used in real-time rendering engines.
- **[Physically Based Rendering: From Theory to Implementation](https://www.pbr-book.org/)**: A comprehensive guide on rendering techniques.
- **[Fundamentals of Computer Graphics](https://www.amazon.com/Fundamentals-Computer-Graphics-Peter-Shirley/dp/1482229390)**: A great introduction to the mathematical and computational principles of graphics.

## Screenshots
![raytraced_image](https://github.com/user-attachments/assets/6bd296cb-5496-4e72-8c27-a4bab2cad3f7)

## License

This project is open-source and distributed under the [MIT License](LICENSE).
