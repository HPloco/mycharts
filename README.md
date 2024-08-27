# TrueNAS SCALE catalog

This is a fork of the archived TrueCharts App Catalog for TrueNAS SCALE.

Since iX-Systems will deprecate their Kubernets/Helm-based GUI app plattform in Q4 2024, TrueCharts already deprecated their TrueNAS catalog. Thus, you cannot update your already installed applications anymore although there's currently no migration to another Kubernetes plattform available. There will be a migration to their new Kubernetes-based plattform(s).  
But for now, you have to wait.

Therefore I decided to fork their archived chart repository and manually push some updates for applications I personally use. Feel free to use this chart to update your own TrueCharts applications on TrueNAS SCALE.

&nbsp;

### **Be aware that I won't continue pushing updates as soon as there's a stable migration to a new Kubernetes/Helm plattform available!**

### **!!! I am not responsible for any issues that might occur. Always backup your data! !!!**

&nbsp;

- ### How to change your TrueCharts catalog:
    
    1.  Remove your already old/deprecated TrueCharts catalog: *Apps* --> *Discover Apps* --> *Manage Catalogs* --> *TRUECHARTS* --> *Delete* (don't worry, this won't delete any of your already installed applications)
    2.  Add this repository as a new Catalog:
        1.  *Add Catalog* --> *Continue*
            - **Catalog Name:** TrueCharts
            - **Repository:** https://github.com/HPloco/mycharts.git
            - **Preferred Trains:** premium, stable, system
            - **Branch:** main

Now you should be able to update your applications again.