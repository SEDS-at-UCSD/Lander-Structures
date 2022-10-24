%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
// SEDS at UC San Diego
// Director of Engineering
// October 24, 2022

> Hey Besties, 
>
> It's Jonathan. We are going to be using Github for CAD from now on!(YAY)
> Now go out there and do some great work.
>
> Love,
> Jonathan

------------------------------------------------------------------------
GET STARTED:

Download github desktop, (which my now I am assuming you have already done) and "clone repository." This repository is "LANDER STRUCTURES." Find a place on your computer that you feel happy with and save the folder there. From there on out, all you have to do is make sure you are saving your files to the folder that is your personal github "clone" on your local computer. When you are all done making changes for the day, you can commit those changes and push them to the cloud with a two clicks of a button. You dont have to do any extra steps (no uploading to google drive or anything!).  

-----------------------------------------------------------------------
HOW TO USE: 

1. {Creating Branches} 
Never CAD directly into the main branch. For any new component or version, create a new branch! Only make a merge to main once you are very confident in your design. You can make branches and sub branch all the way to hell and gone. Make a new one for every version if you like. Each branch is like a seperate folder. You can switch between them at will. Your branches do not need to have all the same folders as main.

2. {Pull Requests}
Always start by making a pull request. This will check to see if you are using the most up to date version of your files. NEVER FORGET THIS. Otherwise you may lose valuable work. Making a pull request after you have started making changes will most likely overide your changes. 

3. {Saving Your Work} 
When you are done for the day, you can make a commit. A commit tells Github that you are happy with the changes you've made. Everytime you make a commit github requires that you right a summary of what you changed. Please don't right nonsence. Even if its just "bolt size change," that is good enough. Please note that making a commit will NOT push anything to the cloud. After making a commit, you still have to press "push" to upload your files.

4. {Collaboration} 
Two people should never work in the same branch at the exact same time. Why? Because if I make a change to the strut at the same time that you make a change, one of our changes will overide the other and github will go bork. Just make an extra branch, compare progress, and fight to the death over who did it better. 

5. {Merging} 
If you want to get up to date with changes that are on another branch, you can merge that other branch into yours. Some branches will get too far away from the original to be ever merged again. Thats okay, all good things must come to an end. 

6. {Merging to Main}
Once you are happy with an entire branch, you can solidify its place in history by making a merge to main. Once something is in main, try not to change it too much. Any changes in main will be carried over to every new branch that is created. In this way, be careful with parent child relationships between parts. If both of our assemblies rely on the same "Bulkhead1" file, we have to make sure that both of our "Bulkhead1" files are actually the same (on the inside). If not, whoever merges second will overide "Bulkhead1" and potentially reck the other assembly. In reality, Its always best to stay in your branch till things are 100% sorted out and you are 100% confident you know what you are doing. Then theres no issue. 

-------------------------------------------------------------------------
IMPORTANT NOTES:

1. Github will remember all of your file names, file locations, and file paths ONLY WHEN YOU SAVE FROM WITHIN SOLIDWORKS. If you move a file or rename it on your own in file explorer, SOLIDWORKS may lose track of it and will not be able to locate it the next time you try to open an assembly. You will have to "seach for file" by hand. This can get tedious, especially when you start getting to large numbers of parts. So, consider the following...

2. Be mindful of where you are saving and what you are naming your files in the first place. DO IT RIGHT THE FIRST TIME. It will save you later pain.

3. Put individual assemblies with all of their components alone in one folder. Best not to have to many assemblies in one folder, it just makes it harder to change things without creating weird errors. If doing this requires you to have multiple compies of the same part at times, that is okay! As long as they have the same name and are actually the same part it wont make a difference when making commmiments and merging (they will become one). 

4. You may want to save some subassemblies internally in the larger assembly. This will keep the number of extra files to a minimum and make orgonizaion easier. 

5. If the SOLIDWORKS paths do get messed up, its okay, as long as you remeber where each part is saved you can manually assign your way back to victory, even if it is a bit tedious. 

6. Remember not to switch branches while any parts are open in SOLIDWORKS. That will make a doo doo beause the file is still in use.


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

IF YOU EVER ENCOUTER AN ERROR THAT YOU DO NOT UNDERSTAND - FIND JONATHAN - DO NOT TRY AND FIX IT YOURSELF YOU MIGHT LOSE SHIT AND IT WILL BE VERY SADGE

*** Moral of the story, Github works great, but it has a low tolerance for stupidity ***

