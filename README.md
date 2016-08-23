# Humidity

On your pi, drag "get_Humidity.py" and "record.sh" to your desktop
Goto your terminal and type in:(no quotes)

"cd Desktop"
"sudo chmod 755 record.sh"

Open up 2 new terminal windows
In both, type "cd Desktop"
On one window, type "sudo watch -n1 more humidity.csv"
In the other window, type "sudo watch -n 1 ./record.sh"
