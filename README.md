# YourDocks - A Rainmeter Skin

**YourDocks** is a highly customizable Rainmeter skin that adds a visually appealing and functional dock to your desktop. The icons feature a stylish linear gradient of different colors, and they expand with a dock-like hover effect, mimicking popular dock applications on macOS and Linux desktops. This skin is designed to give users easy access to their most-used applications, files, and folders while enhancing their desktop aesthetics.

![Preview Image](https://github.com/NSTechBytes/Projects-Templates/blob/main/RainmeterSkins/YourDocks/Screenshot%20(91).png)

---

## Features

- **Gradient Icons:** Each icon in YourDocks is designed with unique linear gradients to add a modern and colorful touch to your desktop.
- **Dock-Like Hover Effect:** When you hover over an icon, it expands in size, just like a dock, making the interaction smooth and visually satisfying.
- **Customizable Layout:** Easily adjust the number of icons, their sizes, spacing, and layout to fit your desktop setup.
- **Lightweight:** Designed to be resource-efficient and fast, ensuring it doesn’t slow down your system.
- **Open Source:** Completely open for modifications and improvements.

---

## Installation

### Prerequisites

To use YourDocks, you must have **Rainmeter** installed on your computer. Rainmeter is a desktop customization platform that allows you to run skins like YourDocks.

1. **Download Rainmeter:**
   - If you don’t already have Rainmeter installed, download it from the official website: [Rainmeter.net](https://www.rainmeter.net/).

2. **Clone or Download YourDocks:**
   - You can download the skin files from the [YourDocks GitHub repository](https://github.com/NSTechBytes/YourDocks/releases/tag/YourDocks).
   - Either clone the repository using Git:
     ```bash
     https://github.com/NSTechBytes/YourDocks.git
     ```
   - Or download the ZIP file and extract it manually.

3. **Install the Skin:**
   - Once downloaded, extract the contents of the `YourDocks` folder into your Rainmeter `Skins` folder.
   - The path should look like this: `Documents\Rainmeter\Skins\YourDocks`.

4. **Activate the Skin:**
   - Open the Rainmeter application and navigate to the `Skins` tab.
   - Find `YourDocks` in the list of installed skins, and load it by clicking on the skin name.

---

## Usage

Once YourDocks is installed and active, you will see a series of icons arranged like a dock on your desktop. Each icon will grow in size when hovered over, creating a dock-like effect similar to what you see in macOS or Linux desktop environments.

### Adding/Removing Icons

To customize the dock and add or remove icons:

1. Navigate to the `YourDocks` folder inside `Documents\Rainmeter\Skins\YourDocks`.
2. Open the `YourDocks.ini` file with a text editor.
3. You will see sections labeled `[Image1]`, `[Image2]`, etc. Each one represents an individual icon.
4. To add more icons:
   - Copy an existing `[Image]` section and paste it below the others.
   - Change the `X` and `Y` values to position the new icon and update the `ImageName` to the new icon file.
5. To remove icons, simply delete the corresponding `[Image]` section.

### Customizing the Appearance

You can easily change the appearance of YourDocks by modifying the variables in the `.ini` file:

- **Icon Size:**
  - The default icon size is set by the `DockSize` variable.
  - The expanded size on hover is set by the `HoverSize` variable.
  - You can adjust these values in the `[Variables]` section of the `.ini` file.

- **Spacing Between Icons:**
  - Adjust the `X` values for each icon to change the horizontal spacing between them.

- **Linear Gradient Icons:**
  - To change the icon images, replace the `.png` files inside the `Icons` folder with your own images.
  - Make sure the new image files are saved in PNG format to preserve transparency and gradients.

---

## Advanced Customization

For those who want to take full advantage of Rainmeter’s powerful skinning engine, you can further customize YourDocks by:

1. **Adding Animations:** Incorporate advanced animations or effects using Lua scripts.
2. **Modifying Hover Behavior:** Change how the hover effect works or add additional actions (e.g., changing colors, playing sounds) by editing the `MouseOverAction` in each icon’s section.
3. **Resizing the Dock:** Change the overall size of the dock by adjusting the `X`, `Y`, and size values of each icon.

For more detailed information on Rainmeter’s skin structure and customization options, visit the [official documentation](https://docs.rainmeter.net/).

---

## Troubleshooting

If you encounter any issues while using YourDocks, try the following steps:

1. **Icons Not Expanding:** Ensure that the `MouseOverAction` and `MouseLeaveAction` are correctly configured for each icon.
2. **Skin Not Loading:** Double-check that the folder structure is correct. The main `.ini` file should be located at `Documents\Rainmeter\Skins\YourDocks\YourDocks.ini`.
3. **Performance Issues:** YourDocks is lightweight, but if you experience performance issues, reduce the number of icons or decrease the `HoverSize` to reduce system load.

---

## Contributing

YourDocks is an open-source project, and contributions are welcome! Whether it's adding new features, fixing bugs, or improving the documentation, feel free to submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

---

## Acknowledgments

- **Rainmeter:** Special thanks to the Rainmeter development team for creating such an amazing desktop customization platform.
- **Icon Authors:** The default icons used in this skin are modified versions of open-source icon sets. If you would like to replace them with your own, feel free to do so.
- **Community:** Thank you to the Rainmeter community for providing inspiration and tutorials that helped in the creation of this skin.

---

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/NSTechBytes/YourDocks/blob/main/LISENCE.md) file for details.

---

With YourDocks, you can make your desktop both functional and visually stunning. Enjoy customizing your desktop with icons that not only look good but also interact with you in a delightful way!
