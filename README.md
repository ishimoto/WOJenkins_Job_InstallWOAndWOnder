Install\_WebObjects\_And\_Wonder
================================
<br /><br />

Before you do this installation read the 'InstallJenkins' documentation in WOdkaTemplates/Jenkins

also you have to read the 'InstallGit' documentation in WOdkaTemplates/Documents

* Jenkins has to be installed
* Plugin has to be installed
* Git has to be installed as jenkins user
* your connection to the github has to be done
* setup of Jenkins has to be checked

---

**1.** Change directories into JENKINS\_HOME/jobs

>$ cd /Users/Shared/Jenkins/Home/jobs/

**2.** Clone job configuration from github.com repository

>$ sudo git clone https://github.com/ishimoto/WOJenkins_Job_InstallWOAndWOnder.git Install\_WebObjects\_And\_Wonder

**3.** Set correct ownership and permissions - If you used the Mac OSX Jenkins installer, the user and group that it will be using are both "jenkins"
 
>$ sudo chown -R jenkins:jenkins Install\_WebObjects\_And\_Wonder

**4.** Open Jenkins and tell it to reload the configuration files so it will see the new job

>Jenkins -> Manage Jenkins -> Reload Configuration from Disk

**5.** Open the new Job

>You should see a new job called Install\_WebObjects\_And\_Wonder.

**6.** Build

**注意：** https://issues.jenkins-ci.org/browse/JENKINS-16523
