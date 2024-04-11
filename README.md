# HW5 Bearthing LED
## B10901110 林萬荃

### Description
This is a PWM demo on L475E-IOT01A board. The LED will be controlled by PWM signal. 
I used CubeMX to generate the code and I chose cmake as the build system because it is fast and easy to use.

## How to build
Clone the project to your local machine.
```bash
git clone https://github.com/EricLin0123/BreathLED.git
```
Run the following commands in the root directory of the project to generate the build files.
```bash
cmake -B ./build/Debug/ -S .
```
Then run the following command to build the project.
```bash
cmake --build ./build/Debug
```

## How to flash
I use CubeProgrammer to flash the binary file to the board. After you have falshed the binary file to the board, you can see the LED is Breathing.