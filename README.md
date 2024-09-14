## Getting the code on your computer

Need to authenticate your terminal with your Github account.
1. Create a personal access token: https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-personal-access-token-classic
2. In your Terminal where you want the repository paste:
   ```
   git clone https://github.com/tinyxknife/slc-diy-shows.git
   ```
3. When promped for `Username:` type your github handle (tinyxknife in my case).
4. When promped for `Password:` paste in your personal access token from step 2.
5. Type `cd slc-diy-shows` to change into the repository or open it in a IDE.

## Running the app locally

1. Make sure you have node.js installed: `https://nodejs.org/en/download/package-manager`
2. You can test you have it installed by typing `node -v` into the terminal and should see `v22.7.0` (version number may vary which is okay)
3. From inside the `slc-diy-show` repository, install libraries
   ```
   npm install
   ```
4. Start up the server. This will occupy the terminal so you need a new window or tab for future commands and leave this running.
   ```
    npm run dev
   ```
5. Open a web browser and navigate to `http://localhost:5173/`
6. You should see the template website!
  <img width="1207" alt="Screenshot 2024-09-14 at 2 09 12 PM" src="https://github.com/user-attachments/assets/a58ae6d4-4780-4632-83a3-4aea429cc7e5">

## Making contributions

Once you have some code changes you want to share, they can be be pushed up to the repository.
1. You can type `git status` to see what changes you have that haven't been commited yet.
    <img width="805" alt="Screenshot 2024-09-14 at 2 16 01 PM" src="https://github.com/user-attachments/assets/dde63a38-5a88-462e-a50b-988775ce4671">
  
2. To add files you want to commit, type `git add <file-path>`. This path can match how it is shown in the `git status` output. You also can from `diy-slc-shows` typed `git add .` to add everything at once.
3. Typing `git status` again will show you what you've added that is ready to commit.
   <img width="649" alt="Screenshot 2024-09-14 at 2 15 23 PM" src="https://github.com/user-attachments/assets/9d282987-da46-478b-894d-713a5c3ba831">
   
4. Now type `git commit -m "some commit message"` and it will bundle all the changes you've added into a commit.
5. Finally to push that commit up to the internet shared repo, you can do `git push`.
6. Now you can navigate to `https://github.com/tinyxknife/slc-diy-shows` to confirm your files made it to the internet.
7. In the future we can use branches but this will get us going.

