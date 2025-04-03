Q1.. an introduction to github codespaces ??
--> GitHub Codespaces is a cloud-based development environment that allows you to code directly from your browser or through Visual Studio Code. It provides fully configured, containerized workspaces that integrate seamlessly with your GitHub repositories.

Q2.. its use cases and why it's important in group projects??
--> Use Cases
1.Quick prototyping without setting up a local environment.

2.Collaborative coding with teams.

3.Developing on low-powered devices like Chromebooks or tablets.

4.Running and testing code in isolated environments.

importances in group

1.Every team member gets the same development environment.

2.New contributors don’t need to install anything locally just open a Codespace and start coding 

3.Team members can share and work on the same Codespace in real time.

Q3..instruction for new users on how to set it up in vs code ??
--> 1.Go to Your GitHub Repository
2.Click on the "Code" button.
3. Select "Codespaces" → "Create Codespace on main"
4.open with the vs code 
5.write the code 
6. open the terminal and write 
   cd .git/hooks
   nano post-commit
   // a screen will appear write the below code in that
   #!/bin/bas
   git push origin main
   --to exit press ctrl+x and type Y
   // you'll be out of the screen
   // now type this code below code
   chmod +x post-commit
   /// now it will automatically push the code

   7. continue 
   nano auto-pull.sh
   // a screen will appear write the below code in that
   #!/bin/bash
   cd/path to your repo
   git pull origin main
    --to exit press ctrl+x and type Y
   // you'll be out of the screen
   // now type this code below code
   chmod +x auto-pull.sh
   now code will be automatically pulled
   


