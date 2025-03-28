# script-server-start

# 📌 English

This script provides a simple command-line interface for managing a simulated VPN server. It allows users to start, stop, check the status, and configure VPN parameters.
# 🔧 Features:

    Start the VPN server (simulated)

    Stop the VPN server (simulated)

    Check the status of the VPN server

    Configure VPN server parameters (IP & Port)

    ASCII art title for aesthetics

    Interactive menu for easy navigation

# 📜 Code Explanation
# 1️⃣ Import necessary modules

    sys: Used for exiting the script.

    colorama: Adds colored output to the terminal.

    pyfiglet: Creates ASCII art for the VPN title.

    os: Executes system commands (like clearing the screen).

# 2️⃣ Clear the terminal screen

os.system("clear")

This ensures a clean interface when the script runs.
# 3️⃣ Initialize colorama

init(autoreset=True)

This allows colored text output to automatically reset after each print.
# 4️⃣ Define core functions

# ✅ start_server()

    Simulates starting the VPN server.

# ✅ stop_server()

    Simulates stopping the VPN server.

# ✅ server_status()

    Displays whether the VPN is running (simulated).

# ✅ configure_vpn()

    Prompts the user to enter an IP and Port for the VPN server.

# ✅ print_ascii_art()

    Prints the "Tunnel VPN" title in ASCII art.

# 5️⃣ Create an interactive menu

    Displays options for starting/stopping the VPN, checking its status, and configuring it.

    Takes user input to navigate through the options.

    If an invalid option is entered, it prompts the user to try again.

# 6️⃣ Run the script

if __name__ == "__main__":
    main()

This ensures that the script only runs when executed directly, not when imported as a module.
