# SharedMScore
Hi ! If you are passionate in writing music and sharing musical experiences, this project is for you ! All you need is to masterize MuseScore and Git, and practice a music instrument with basic music theory aknowledge. Tutorials about Git and MuseScore are easily findable on the net.

> Discord : https://discord.gg/dM9ebAWv4Z

### Any issue ?
> Contact : Harrybreak#7531

## How to join the shared work ?

First of all, install **MuseScore** :
* **Linux** : https://musescore.org/fr/download/musescore-x86_64.AppImage
* **Mac OSX** : https://musescore.org/fr/download/mac
* **Windows 7/8/8.1/10/11** : https://ftp.osuosl.org/pub/musescore-nightlies/windows/3x/stable/MuseScore-3.6.2.548021803-x86_64.msi

If you use Windows OS, install also Git : https://github.com/git-for-windows/git/releases/tag/v2.39.2.windows.1

Once Git and MuseScore are installed, open a terminal (Git Bash for Windows users) and enter the following commands :

``git clone https://github.com/Harrybreak/SharedMScore.git``

``cd SharedMScore``

``git branch <your nickname>``

``git checkout <your nickname>``

``touch README.md``

``git commit -a -m "New user !"``

``git push --set-upstream origin <your nickname>``

Once everything is up, launch MuseScore and open any score you want from **SharedMScore** folder.

## How to add yourself in an existing score ?

* In MuseScore, open a score and add notes to your instrument (or add the instrument if it does not still appear in the score).
* Once you want to share your contribution, open Git (Git Bash for Windows open in the folder **SharedMScore**), enter:

    ``git commit -a -m "My contribution"``
    
    ``git push``.

## How to create a new score ?

**WARNING** : in order to preserve memory space, we only work on files in MSCX format (``*.mscx``), which is why it is important to follow the instructions below:

* Create a new **sub-directory** (like ``music1`` folder)
* In MuseScore, create a new score under **this sub-directory** (with anything you want, any instruments, any title, any description, etc.)
* Save it under the **sub-directory**'s name.
* Close the score from MuseScore.
* Extract files from the new file which ends with ``.mscz``
* Keep only the file with the same name of your score which ends with ``.mscx`` and move it into the **sub-directory** created earlier.
* Delete the other files and folders (like ``Thumbnails`` or ``META-INF``. Whatever, only the ``.mscx`` file will be saved and considered by Git).
* In MuseScore, open the score which now ends with ``.mscx``. **Nothing should have changed in the score ! If so, restart everything, or simplier: contact me.**
* Once you are ready and want to share your new score, open Git (Git Bash for Windows open in the folder **SharedMScore**), enter:

    ``git add --all``

    ``git commit -m "My new score"``

    ``git push``

* Mods and me will check if everything is ok with your new score before sharing it :)

## DISCLAIMER

* You can be blamed or banned for offensive language, hate speech, violence, harassment or any obscene content posted on the common workspace. No warning will be given and no canvassing will be tolerated. Respect each others and everyone is going to be happy :)
* Any score published in the common workspace can be used by anyone. This is not for private purposes :/