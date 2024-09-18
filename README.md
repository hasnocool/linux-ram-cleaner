**README.md**
=====================================

**Linux Ram Cleaner**
====================

A simple yet effective script to clean up your Linux system's RAM and free up some valuable resources.

**Description**
---------------

Are you tired of running out of memory on your Linux machine? Do you wish there was an easy way to clear out unused data and get back some much-needed space? Well, wish no more! I built this script, **Linux Ram Cleaner**, to do just that. With a few simple commands, it'll clean up your RAM, freeing up resources for your next big project.

**Features**
------------

*   **Clear PageCache only**: Quickly free up memory by clearing out unused page cache.
*   **Clear dentries and inodes**: Go the extra mile and remove unnecessary directory entries and inode caches too!
*   **Clear PageCache, dentries, and inodes**: Why not do it all? This option is perfect for when you need to make some serious space on your system.

One cool feature is... (you guessed it!) **the swapoff trick**. By temporarily disabling and re-enabling swap, we can even clean up swap memory!

I'm thinking about adding a GUI interface for the script. Stay tuned!

**Installation**
---------------

1.  Clone this repository using `git clone`.
2.  Run `chmod +x memory_cleanup.sh` to make the script executable.
3.  Move the script to your desired location (e.g., `/usr/local/bin`) and update the path in your `.bashrc` or equivalent.

**Usage**
----------

1.  Simply run `./memory_cleanup.sh` from the terminal.
2.  Follow the prompts to select which memory types you'd like to clear.
3.  Enjoy your newfound free RAM!

### Before and After screenshots

![Before](before.png) **vs** ![After](after.png)

Please note: These images are placeholders for actual screenshots, which will be added once the project is more mature.

**Contributing**
--------------

If you'd like to contribute to this project or suggest new features, feel free to open an issue or submit a pull request. I'm always excited to collaborate with fellow developers!

**License**
----------

This project is licensed under the MIT License. See `LICENSE` for details.

**Tags/Keywords**
-----------------

*   **Linux Ram Cleaner**
*   **memory optimization**
*   **cache cleaning**
*   **swap memory management**
*   **system resource utilization**
*   **simple script**
*   **open-source software**