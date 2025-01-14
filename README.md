# ellie-ground
2022 Eillie Hot-fire Electronics Control

## Summary
**DAQboard.ino** file commands the ESP32 that reads data from sensors and commands from the COM Board, and sends data in a package to the COM Board.

**COMBoard.ino** file commands the ESP32 that receives data in a package from the DAQ  Board, sends commands to the DAQ Board, and sends data to MATLAB for plotting and data-saving purposes through the serial port.

**liveplot.m** is a MATLAB file that can receive data from the COM Board, create live plots, and save the data.

## Software requirement
**Ctrl click (Windows) or Cmd click the following links to open them in new tabs**
1. Arduino (https://www.arduino.cc/en/software)
2. MATLAB (https://software.berkeley.edu/matlab®)
    - To control the serial port, you need to install the [**Instrument Control Toolbox**](https://www.mathworks.com/products/instrument.html).
3. (optional) An external code editing software such as Atom (https://atom.io) or Visual Studio (https://visualstudio.microsoft.com/downloads/).
    - Arduino IDE and MATLAB are sufficient for all the coding
4. (recommended) GitHub Desktop (https://desktop.github.com). You can pull, push, and edit files with ease. **Step 3 required if you would like to download GitHub Desktop as the software requires an external editor.**

## How to update
### Using Github Desktop
1. Make sure you have access to this project
    - Check with you administrators
2. Go to the Github app, sign in, and click on the top left corner. You should see a pop-up window with an "Add" button. Select that button and choose "Clone repository."
3. Search in "Filter you repositories" using the keyword "ellie-ground." Select the correct repository and click "Clone."
    - If you want this cloned repository to be in a different folder, change the "Local Path."
4. After you have edited and saved the file in the local repository, GitHub Desktop will detect changes and prompt you to commit. Make sure to double check your changes before committing.
5. On the bottom left corner, put down a short summary that describes what you have changed, then click "Commit to **main**."
6. In the middle of the screen (or on the top banner) you will see "Push commits to the origin remote." If you are sure that the commit is ready, click "Push origin."
6. Check the project online and see if the changes have been reflected.

### Using Git
Please refer to https://rocketry.gitbook.io/public/tutorials/avionics/git-and-workflow for more information.
