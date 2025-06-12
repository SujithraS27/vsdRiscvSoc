✅ Task 1: Install & Sanity Check the Toolchain
🎯 Objective
Install the RISC-V GNU toolchain, configure the environment, and verify the setup.

🛠️ Commands
bash
Copy
Edit
tar -xzf riscv-toolchain-rv32imac-x86_64-ubuntu.tar.gz
cd opt/riscv
ls bin
Add to PATH Temporarily:

bash
Copy
Edit
export PATH=$HOME/riscv/bin:$PATH
Make PATH Permanent:

bash
Copy
Edit
nano ~/.bashrc
# Add the following line at the end:
export PATH=$HOME/riscv/bin:$PATH

# Save and apply:
source ~/.bashrc
echo $PATH
✅ Verification
bash
Copy
Edit
riscv32-unknown-elf-gcc --version       # ✅ GCC 14.2.0
riscv32-unknown-elf-objdump --version   # ✅ Binutils 2.43.1
riscv32-unknown-elf-gdb --version       # ✅ GDB 15.2
