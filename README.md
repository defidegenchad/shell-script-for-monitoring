# Shell Script - Linux System Management

This project contains a shell script for monitering network, disk usage, uptime, load average, RAM usage and so on. It is assumed that the base Linux install is generic in nature.

This project can serve as a prelude that the Script don’t contains any malicious contents and it can be run using Normal user Account. In-fact it is recommended to run this script as user and not as root.

# Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Usage](#usage)
- [Code of Conduct](#code-of-conduct)
- [Contributions](#contributions)
- [License](#license)
- [History](#history)
- [Credits](#credits)


## Features

- A configurable shell script which may be helpful at places and specially for those newbies who can get most of the information they require about their System, Network, Users, Load, Ram, host, Internal IP, External IP, Uptime, etc.

## Requirements

1. Any working Linux setup. 

## Usage

`ssh` to your server or VM.

First, let's use following wget command to download the monitor script "shell-moniter.sh" and make it executable by setting appropriate permissions.

     wget https://raw.githubusercontent.com/muzikmyth/shell-script-for-monitoring/master/shell-monitor.sh
     chmod 755 shell-monitor.sh
      
It is strongly advised to install the script as user and not as root. It will ask for root password and will install the necessary components at required places.
  
To install "shell-moniter.sh" script, simple use -i (install) option as shown below.
      
    ./shell-monitor.sh -i 
      
Enter root password when prompted. If everything goes well you will get a success message like shown below.

    Password: 
    Congratulations! Script Installed, now run monitor Command
      
After installation, you can run the script by calling command 'monitor' from any location or user. If you don’t like to install it, you need to include the location every-time you want to run it.

    # ./Path/to/script/shell-monitor.sh
    
Now run monitor command from anywhere using any user account simply as:

    $ monitor
    
    
As soon as you run the command you get various System related information which are:

Internet Connectivity
OS Type
OS Name
OS Version
Architecture
Kernel Release
Hostname
Internal IP
External IP
Name Servers
Logged In users
Ram Usages
Swap Usages
Disk Usages
Load Average
System Uptime     

## Code of Conduct

You are free to use/modify/redistribute the below piece of code by giving proper credit to the author.

## License

Please note that this project is released with a MIT License.

## Credits

Developed by [Abhijit Kumar](https://abhijitkrm.site). Connect to me at abk@abhijitkrm.site
