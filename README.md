# Installation

This project uses **ROS 2 Jazzy**.

## Windows (with WSL 2)

1. Open **a terminal as an administrator**, then install Ubuntu 24.04 and WSL 2:

   ```powershell
   wsl --install -d Ubuntu-24.04
   ```

2. Restart Windows. Then launch **Ubuntu 24.04**
   and complete the Linux account setup.
3. In the **Ubuntu** terminal, install Pixi (You only need to install pixi : https://pixi.prefix.dev/latest/installation/.):

   ```bash
   curl -fsSL https://pixi.sh/install.sh | sh
   ```
> [!WARNING]
> Make sure you're using the Ubuntu terminal you installed in step 1; otherwise, the commands won't work.

Close and reopen the Ubuntu terminal so Pixi is added to your `PATH`.
   
4. Clone the project to a known path:

   ```bash
   git clone https://github.com/lmmans/pixi_tp_ros.git
   cd pixi_ros_tp
   ```

5. Activate the environment:

   ```bash
   pixi shell
   ```

To leave the environment, run `exit`.

## macOS

1. Open the **Terminal** application.
2. Install Pixi:

   ```bash
   curl -fsSL https://pixi.sh/install.sh | sh
   ```

   Close and reopen the terminal so Pixi is added to your `PATH`.
3. Clone the project where you want it to be:

   ```bash
   git clone https://github.com/lmmans/pixi_tp_ros.git
   cd pixi_ros_tp
   pixi shell
   ```

This project is configured for both Intel and Apple Silicon Macs.

## Linux

The project is configured for **x86_64** Linux. Use a recent Linux distribution
with `curl` installed.

1. Open a terminal and install Pixi:

   ```bash
   curl -fsSL https://pixi.sh/install.sh | sh
   ```

   Close and reopen the terminal so Pixi is added to your `PATH`.
   
3. Clone the project where you want it to be:

   ```bash
   git clone https://github.com/lmmans/pixi_tp_ros.git
   cd pixi_ros_tp
   pixi shell
   ```
