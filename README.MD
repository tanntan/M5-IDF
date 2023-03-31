# GET STATED

## Clone the repository, and its submodules
git clone https://github.com/ropg/m5core2_esp-idf_demo.git
cd m5core2_esp-idf_demo
git submodule update --init --recursive

## Build it, flash it, and see the serial output
idf.py build flash monitor