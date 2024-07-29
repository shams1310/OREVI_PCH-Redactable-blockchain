# OREVI_PCH-Redactable-blockchain
OREVI_PCH: An Optimized Resource-Efficient Redaction Mechanism with Integrity Validation in Policy-based Chameleon Hash for IoT Applications
Welcome to the OREVI_PCH repository! This project implements a highly efficient redactable blockchain mechanism using Python and the Charm framework.

Installation Guide
Step-by-Step Guide to Install Charm on Ubuntu
To work with this project, you need to install the Charm framework. Below are the steps to install Charm on Ubuntu:

Update your package lists:

Open a terminal and update your package lists to make sure you have the latest information about available packages.

bash
Copy code
sudo apt-get update
Install dependencies:

Install the necessary dependencies for Charm. This includes Python development headers, GMP library, and CMake.

bash
Copy code
sudo apt-get install build-essential python3-dev libgmp-dev cmake
Download and install PBC library:

The Pairing-Based Cryptography (PBC) library is required by Charm.

bash
Copy code
wget https://crypto.stanford.edu/pbc/files/pbc-0.5.14.tar.gz
tar -xzf pbc-0.5.14.tar.gz
cd pbc-0.5.14
./configure
make
sudo make install
Clone the Charm repository:

Clone the Charm repository from GitHub.

bash
Copy code
git clone https://github.com/JHUISI/charm.git
cd charm
Install Charm:

Run the installation script.

bash
Copy code
./configure.sh
make
sudo make install
Verify the installation:

Check if Charm is installed correctly by running a simple test.

bash
Copy code
python3 -c "import charm"
If there are no errors, the installation was successful.

Source Code
If you need the source code or have any questions, feel free to contact me at msc.s.mahmoud@gmail.com.
