ansible-role-dell-printers
==========================

Role that manage dell printer with Ansible

# Supported printers :
- Dell 2150cdn Color
- Dell 2150cn Color

# Configure a printer :
    lpadmin -p "Dell-2150cdn-Color-Printer" -v "socket://192.168.0.3:9100" -m Dell/Dell_2150cdn_Color_Printer.ppd.gz -E