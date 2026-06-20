# Processes and Signals


This project covers shell scripting concepts related to processes and signals in Linux.

## Scripts


- **0-what-is-my-pid**: Displays the script's own PID
- **1-list_your_processes**: Displays all running processes with hierarchy
- **2-show_your_bash_pid**: Displays lines containing the word bash
- **3-show_your_bash_pid_made_easy**: Displays PID and name of bash processes
- **4-to_infinity_and_beyond**: Infinite loop printing a message every 2 seconds
- **5-dont_stop_me_now**: Stops the 4-to_infinity_and_beyond process using kill
- **6-stop_me_if_you_can**: Stops the process without kill or killall
- **7-highlander**: Infinite loop that catches SIGTERM and prints "I am invincible!!!"
- **67-stop_me_if_you_can**: Stops the 7-highlander process
- **8-beheaded_process**: Kills the 7-highlander process with SIGKILL
- **10-process_and_pid_file**: Manages a PID file and handles multiple signals
- **manage_my_process**: Daemon that writes "I am alive!" to a file every 2 seconds
- **11-manage_my_process**: Init script to start, stop, and restart manage_my_process
