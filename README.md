# Course-Player

### What is it?
Course Player is a simple HTML5 web application to play sequenced video files.

<br>

### Why is it?
Recently I decided to use LinkedIN Learning to begin learning about Unreal Engine 4. Unfortuntely there seems to be no provision for people whom might want to view the courses offline when they don't have any internet connectivity.

I did not like this very much and decided to make a little web application that would let me view LinkedIN Learning video courses whilst offline.

<br>

### How do I use it?

Create a folder for your Course and then create a subfolder inside that called **videos**.

Copy the **player.html** from this repository file into your folder and rename it to index.html if you prefer. Note: There is also a minified version of the player present in this repository for those who think tey need the faster load time ;)

Download all of the videos that you want to view offline into the **videos** folder.

If you want to segment your videos into chapters then you can create a blank text file with the chapter title.

If you look at the example **data.txt** file you will see how I've named my files as to have some semblance of an ordered layout.

Copy the **data.txt** file to your course folder.

Edit the **data.txt** file (which is actually a Javascript file) and edit it as required.

It should be fairly easy to see how it is structured and what each variable inside it is doing... please open an issue if you REALLY can't figure it out :D

If you download the repository then you can open **player.html** which will play the sequenced example videos.
