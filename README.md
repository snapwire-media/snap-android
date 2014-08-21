#Snap Android
Take a snapshot of your device through ADB with this simple bash script. 


##Usage
Attach your device through USB and run snap in commandline:

    ./snap mysnap
    
This will create a file called mysnap.png. Using ```./snap``` with no arguments wil create a png file with a timestamp. 



For ease of use, add the script to a shell profile such as .bash_profile: 

    export SNAP-ANDROID=${HOME}/path/to/snap-android
    export PATH=$SNAP-ANDROID:$PATH