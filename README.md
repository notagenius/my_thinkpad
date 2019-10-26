# my_thinkpad
my_thinkpad_files

# enable bluetooth
echo options thinkpad_acpi dbg_bluetoothemul=1 bluetooth_state=1 | sudo tee -a /etc/modprobe.d/thinkpad_acpi.conf
then reboot:
rfkill unblock all

# install mxnet
pip intall mxnet==1.3.1b20181014
because my target CPU doesn't support f16c
