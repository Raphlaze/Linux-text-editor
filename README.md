# Linux Text Editors
 In this project we would be talking about Linux text editors and the various text editors in linux ecosystem.
  A linux text editor is a software application specifically designed for creating, modifying and managing text files on a linux-based operating system.
  I would be writting about two various and commonly used text editors namely:
  1. VIM Text Editor
  2. NANO Text Editor

 1. ## VIM Text Editors
 The Linux vim editor, short "VI Improved", is a powerful and versatile text editing tool deeply ingrained in the Unix and Linux ecosystems. Vim builds upon the foundation of the original Vi editor, offering an extensive set of features, modes and commands that empower users to manipulate text efficiently.
 ### Working With VIM Editor
  #### Task 1. Open a new file named "exercise.txt" using the following command below:
  vim exercise.txt
  below is the img of the created file while empty
  ![vim](./Img/vim1.png)

  #### Task 2. Enter Insert Mode to edit the file.
  * to achieve this i press letter 'i' on the keyboard
  
  #### Task 3. Type the following text into the file:
  * Hello, this is a Vim hands-on project.
  Welcome to darey.io.
  The text above was written in the Vim text editor.
  img is shown below:
  ![hello](./Img/vim-hello.png)

  #### Task 4. Moving Around: 
  * To navigate through the text using the arrow keys or h(left), j(down), k(up), and i(right).

 #### Task 5. Deleting a Character
 * pressed 'esc' on the keyboard to exit the 'insert mode', then i positioned the cursor on a character and pressed x to delete it.
 The img below shows where i deleted hello from my initial write up of task 3.
 ![delete](./Img/esc-delete-x.png)

 #### Task 6. Deleting a Line
 * Making sure i am on the normal mode, i placed the cursor on a line i intend deleting and pressed 'd' twice on the keyboard to delete the entire line.
 The img below shows me deleting the first line of my write up from task 3 remaining only the second line.
 ![Line](./Img/row-delete-d.png)

 #### Task 7. Undoing Changes
 * Still in Normal mode i pressed 'u' on the keyboard to undo all the changes i made while deleting lines and characters on the text editor.
 The img below shows the results after undoing all changes.
 ![undo](./Img/undo-changes-u.png)

 #### Task 8. Saving Changes 
 * After i finished writing into the file, to save it i pressed 'esc',then typed :wq and 'Enter' on the keyboard. This saves all the work done and returns to the terminal.
 the command :wq stands for w: write while q: quit.
![save](./Img/save-quit-wq.png)

 #### Task 9. Quitting Without Saving
 * i also tried this exercise quitting without saving, all changes and write up done will not be saved, by simply typing this command in the normal mode.
:q! and Enter. its quits without saving and goes back to the terminal.

 ### 2. NANO Text Editor
 Nano serves as a versatile and lightweight text editor, ideal for performing quick edits, writing scripts and making configuration changes directly from the command line.

 ### Working with Nano Editor
 #### Task 1. Opening a File
 * I created and named a file using nano text editor with the command below:
 nano nano_file.txt
 below is the img of the terminal and command written
 ![file](./Img/nano-file.png)

 #### Task 2. Entering and Editing Text
 * I typed few lines of text into the file, nano has a simple interface.
 The img below shows the write up and what nano editor looks like.
 ![nano](./Img//nano-editor.png) 

 #### Task 3. Saving Changes
 * I simply save changes on nano by pressing 'ctrl' + 'o', it then prompt me to confirm the file name, then i pressed 'Enter' to confirm and the file was saved
 #### Task 4. Exiting Nano
 To exit nano without saving the file i pressed 'ctrl' + 'x', it then prompts you to either save or not (yes/no) before exiting.
 The img below shows the prompt message by nano before exiting.
 ![ctrl-x](./Img/nano-crtl-x.png)

 #### Task 5. Opening an Existing File
  * I simply opened one of the files creeated earlier for this project using the command below:
 nano nano_file.txt
 The display is same result as what i wrote in it earlier.
 ![open](./Img/nano-editor.png).

 Thanks for your time and Lectures.
 Bye for now.
