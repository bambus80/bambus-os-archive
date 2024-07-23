![icon](https://media.discordapp.net/attachments/1165612747128582146/1265238016268570705/bambus_os_icon.png?ex=66a0c83a&is=669f76ba&hm=12ce6d1535ea833051348a017db792c6ae09fe7bdf684b314928ea12fb8f27be&=&format=webp&quality=lossless&width=308&height=308)

# Bambus OS Archive
Archive of public Micro Consen-based versions of Bambus OS in the form of deployable system images (`.dsi`) installable on pure Micro Consen kernels.

### Layout
System images are stored in the `/dsi` folder. Each release is in a seperate folder with `index.json` and `image.dsi` files.
The `index.json` file contains information about the version while `image.dsi` is the OS image itself. There may be a `sys.dsi` file containing kernel dependencies that, depending on the installation, may have to be installed.

### Avaliable versions
- Bambus OS 5.00 (`os.bambus_os-5.00`, 20.07.2024)