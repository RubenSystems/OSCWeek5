# Git setup

If you are comfortable using git and your own personal computer (and you know how to install stuff), but you don't want to bother using SSH all the time, follow this tutorial 

1. login to 5CCS2OSC.nms.kcl.ac.uk using the instructions on the labsheet
2. Create two new repos on github (MAKE THEM PRIVATE). One for the userspace folder (infos-user) and infos. 

Repeat this for both folders: 
  1. cd {infos, infos-user} 
  2. git remote add personal <INSERT THE URL OF THE GIT REPO HERE>
  3. Add everything (`git add .`), commit everything (`git commit -m "meaningful message here (jk just say inital commit)"`) and push (`git push personal main`)

From your computer, create a new folder (`mkdir osc-coursework`) go into it (`cd osc-coursework`) and then clone both repos into them (`git clone <URL OF REPO HERE>`)


### Things to worry about 
- Make both repos private otherwise you will be invited to a meeting with academic misconduct
- Don't waste your time trying to install stuff. Unless you know what you are doing, you may want to follow the VSCode tutorial in this repo
- To submit your work, you need to push from your personal computer and then pull from the 5CCS2OSC.nms.kcl.ac.uk computer. Then submit
