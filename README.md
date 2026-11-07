# Wonderland Canteen 🍔🥤

Welcome to the *Wonderland Canteen* web application repository! This project is a multi-page web platform designed to display daily canteen menu items, categorized snacks and beverages, and process user feedback.

## 👥 Team & Roles
* *Ashraf:* Base repository setup, main layout (index.html), feedback page (feedback.html), and UI/CSS animations.
* *Naif:* Page structure for Beverages (drinks.html).
* *Arief:* Page structure for snacks, repository management, and project documentation (README.md).

## 🚀 Local Development Setup (Laravel Herd)
1. Clone this repository into your local Herd directory:
Through the terminal
   ```bash
   cd ~/Herd
   git clone [https://github.com/MdAriefFirdaus/IIB_AS3_Group10.git](https://github.com/MdAriefFirdaus/IIB_AS3_Group10.git)

Or through github
   - On the main repository branch page, select code and download ZIP
   - Extract the zip and copy all the files inside and paste it inside of Laravel Herd
   - Open Laravel Herd then click on sites and Add
   - Select link existing project and select the file you copied inside of Laravel Herd
   - Laravel Herd will then create the site and it can be accessed with the URL provided

---
## How merge conflicts was resolved
* By opening up an editor interface and checking for lines of codes with conflicts highlighted, then keeping the new code and deleting the old line of code since the new code is the modified version of the previous code and saving the file

Reflections:

<ins>Ashraf</ins>

For this project, I contributed to the frontend development by designing and structuring the multi-page site layout, standardizing navigation bars across all pages, and implementing custom CSS to enhance the user experience. Through this team effort, I gained hands-on experience with a professional Git workflow, learning the importance of feature branches, Pull Requests, and collaborative code reviews under a protected main branch. A major challenge our team overcame was resolving merge conflicts that occurred when concurrent edits were pushed to shared files like snacks.html; we successfully solved this by carefully reviewing conflict markers, and coordinating our updates to ensure a seamless, cohesive website.

<ins>Naif</ins>

For my contribution regarding this project, i was tasked in creating and designing my branch about "drinks.html" via manual coding with occasional support from AI and merge the branch with the main in the group repo. I gained hands-on experience with a professional Git workflow [git pull, git push, git clone, git merge etc], understanding the important of feature branches and its consequences and collaborative reviews on members coding. A major challenge that i faced with my group was the occurrence of a git merge conflict whereby several exact files such as "Snacks.html" had concurrent edits; 3 solutions were made:
1. Perform a git pull origin to gain the latest updates of the group's main repo; this step was unsuccesful
2. Delete all the directories including the css.styles, index.html alongside other related directories from the group repo except my drinks.html file. The drinks.html file is stored in a temporary folder within the file explorer where it'll be later forwarded to the group's main repo. Copy the group's latest repo while deleting the drinks.html file in the group main repo (not the drinks.html that is stored in the temporary folder). Then, integrate the drinks.html file from the temporary folder into the latest group main repo. This step was succesful.

Additionally, another challenge i faced was a missing letter within the "drinks.html" whereby it was originally "drink.html" which missed the letter "s". This issue caused the coding fail to compile and that the webpage was unable to opened; the solution to fix this was adding "s" to the "drink.html"

Finally, another issue that i experienced was incorrect format within thee coding of the css.styles of my git branch. My collaborator Ashraf solves this issue by performing code review (modifying any necessary changes in order for the drinks page to look similarly with other pages in aesthetic and formatting). 
