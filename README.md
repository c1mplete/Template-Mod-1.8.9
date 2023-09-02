# Template Mod 1.8.9

Enhance the appearance and readability of your GitHub repository's README:

Made using [**this repository**](https://github.com/DxxxxY/mcp1.8.9op) with MCP 1.8.9 and Optifine combined into a single installation.

---

## Installation & Setup

Follow these steps to install and set up the Template Mod 1.8.9:

1. **Download or Clone the Repository**
   - You can either download the ZIP file or clone the repository to your local machine.

2. **Using IntelliJ IDEA**
   - Open IntelliJ IDEA and navigate to `File > Open > Project from Existing Sources...`.
   - Select "Import from External Model" and choose "Eclipse."
   - Proceed with the installation using the default settings.

3. **Configuring Project**
   - After the project is built, go to `File > Project Structure... > Modules > Dependencies`.
   - Change the Module SDK to 1.8 if it's not already set.

4. **Library Setup**
   - Within the same window, double-click on `1.8.8.jar` (highlighted in red).
   - Delete the classes by clicking once on them and then clicking the "-" button above.
   - Repeat the same process for the Native Library Locations.

5. **Adding JAR Files**
   - Click on the "+" button and navigate to the project folder.
   - Go to `jars > versions > 1.8.9` and select both `1.8.9-natives` and `1.8.9.jar`.

6. **Edit Configurations**
   - Click on `Edit Configurations...` in IntelliJ.
   - Click the "+" button to add a new configuration.
   - Set the main class to "Start" and the working directory to your client's JARs folder.

By following these steps, you'll successfully install and set up the Template Mod 1.8.9 in your development environment. Happy modding!
