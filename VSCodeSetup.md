# VSCode Setup

1. Go to the plugin page on VSCode

<img width="49" alt="Screenshot 2024-02-10 at 6 41 08 pm" src="https://github.com/RubenSystems/OSCWeek5/assets/37454706/13af76b3-a340-4d62-8505-a2ef14a564e3">

2. Type in **Remote - SSH** and install that plugin:

<img width="912" alt="Screenshot 2024-02-10 at 6 49 22 pm" src="https://github.com/RubenSystems/OSCWeek5/assets/37454706/04d09927-a799-4e3b-accd-2971e2843f60">

3. Hit Command + Shift + P
4. Type in **Remote SSH: Connect to Host**
5. Click **+ Add New Host**
6. Type this in (remember to change your knumber) `ssh -J k1234567@bastion.nms.kcl.ac.uk k1234567@5CCS2OSC.nms.kcl.ac.uk`
7. Choose a SSH Config File to add to (the ones that show up depend on your system)
8. Something should come up saying **Host Added!**. Press the Connect Button

This should work. If it doesn't, ask for help. 
