# Bash2AppImage

Bash2AppImage is a Bash script designed to compile other Bash scripts into AppImage packages, facilitating easy distribution and execution across various Linux distributions. 

## Features

- **Bash Script Compilation**: Convert standalone Bash scripts into self-contained AppImage packages.
- **Dependency Management**: Automatically installs necessary dependencies to ensure smooth operation.

## Prerequisites

- Ensure you have `git` installed to clone the repository.

## Installation Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/PhoenixAceVFX/bash2appimage.git
   ```



2. **Navigate to the Directory**:
   ```bash
   cd bash2appimage
   ```



3. **Prepare Your Scripts**:
   - Create a directory named `Scripts` within the project root:
     ```bash
     mkdir Scripts
     ```
   - Place your `.sh` Bash script files into the `Scripts` directory.

4. **Add an Icon (Optional)**:
   - Place an `Icon.png` file in the project root directory. Ensure it's a square image to avoid display issues.
   - If no `Icon.png` is provided, a placeholder icon will be used.

5. **Run the Compiler**:
   ```bash
   bash compiler.sh
   ```



6. **Verify the AppImage**:
   - After compilation, test the generated AppImage to ensure it functions as expected.

## License

This project is licensed under the GNU General Public License v2.0. For more details, refer to the [LICENSE](https://github.com/PhoenixAceVFX/bash2appimage/blob/main/LICENSE) file.

## Acknowledgments

Bash2AppImage was originally developed for the [HyprUpld](https://github.com/PhoenixAceVFX/HyprUpld) project but is versatile enough to compile any standalone Bash script into an AppImage.

For questions or contributions, please open an issue or submit a pull request on the [GitHub repository](https://github.com/PhoenixAceVFX/bash2appimage).

*Note: AppImage is a format for distributing portable software on Linux without requiring superuser permissions to install the application.* 
