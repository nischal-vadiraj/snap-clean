### Cleanup Script

Running out of space in your linux machine? you also use snap packages in your distro? well try cleaning some old snap gook that it left behind.

This Bash script is designed to remove old revisions of snaps. It helps keep your system tidy and reclaim your sweet ssd space by removing outdated versions of installed snap packages.

**Usage Instructions:**
1. Ensure all snaps are closed before proceeding.
2. Open a terminal window and clone the repo.
   ```bash
   git clone https://github.com/nischal-vadiraj/snap-clean.git
   ```
   OR
   ```bash
   git clone git@github.com:nischal-vadiraj/snap-clean.git
   ```
3. Navigate to the directory where the script is located

   ```bash
   cd snap-clean/
   ```
4. Make the script executable if needed:

    ```bash
    chmod +x clean-snap.sh
    ```
5. Run the script by typing:
    ```bash
    ./clean-snap.sh
    ```

**Note:**
- Use caution as this script permanently removes old revisions of snaps.
- Ensure you understand the implications before running it.


