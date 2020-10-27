# Testing Your Seed

Once you have made the backup of a Seed, this Seed can be used to access your Skywallet. 

If you want to check, whether a Seed you have written down belongs to a given Skywallet, you can use the **Confirm Seed** button. This is a security procedure to check whether the backup has been successful.

The "Confirm Seed" button will not be available when you are using your Skywallet for the first time. Instead, you will see the button **Create Backup**.

Once you have clicked on the **Create Backup** button on the Hardware Wallet window and completed the process of the Seed backup,  the "Confirm Seed" button will replace the "Create Backup" button.

Hardware Wallet window, Before Seed backup:

![Create Backup](img/manual/Testing%20your%20Seed%20-%201.png?raw=true)

Hardware Wallet window, after Seed backup:

![Confirm Seed](img/manual/Testing%20your%20Seed%20-%202.PNG?raw=true)

To check whether a Seed belongs to a particular Skywallet, you have to connect your Skywallet first. 

!!! warning
    If you are connecting the Skywallet for the first time, please read the following manuals:<br> 
    * [Initialization of your Skywallet](./manual-2-initializing-the-wallet)<br>
    * [Personalization of your Skywallet](./manual-3-personalizing-the-wallet) <br>
    to understand how to initialize and personalize your Skywallet for its first time use.

If you see the "Confirm Seed" button on your Hardware Wallet window, then it means that you have already taken the backup of the Seed.

After clicking on the "Confirm Seed" button, the Skywallet will ask you to enter the different words in your Seed.

**However, the sequence of these word positions will be in random order.**

![Seed_Entry](img/manual/Skywallet%20Screen%20Mockup%20Edit_Skywallet%20Black_08.png?raw=true)

Along with asking you to enter the words of the Seed at a particular position, **the Skywallet may ask you to enter random words which are not part of the Seed.**

!!! info
    Both the random words and the random sequence are a security measure to ensure that a potential attacker who might have access to your computer does get neither the full Seed nor the right sequence.

Once this process is complete, the Desktop Wallet will confirm whether the Seed you have entered is the correct Seed for the connected Skywallet.