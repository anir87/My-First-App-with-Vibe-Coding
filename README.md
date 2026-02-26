# Welcome to the My-First-App-with-Vibe-Coding!

Kudos to [Farza Majeed](https://www.linkedin.com/in/farza-majeed-76685612a/) & Julian for the session on Wednesday.

I was able to ship a minimal viable game with slight twist of mine, in less than an hour

* MVP1: https://skill-deploy-g677zii17j-codex-agent-deploys.vercel.app/
* MVP2: https://skill-deploy-t671zysiyi-codex-agent-deploys.vercel.app/

Steps are mentioned below:
1. Follow the steps mentioned in https://www.makesomething.so/start
2. Since I have a Windows Laptop, I opened the Powershell Terminal in Windows as an administrator
3. Copy & Paste: irm https://raw.githubusercontent.com/filip-pilar/makesomething/main/scripts/setup-windows.ps1 | iex
4. You may face the below error. Then just type: npm run dev
> <img width="1202" height="270" alt="image" src="https://github.com/user-attachments/assets/5d86c225-d8b9-4972-81e4-762028fcee57" />

  
5. You may see the following terminal screen. Your server is running successfully. Once the script finishes, codex is going to launch right there in your terminal
> <img width="1144" height="977" alt="image" src="https://github.com/user-attachments/assets/50df5031-cc88-4677-8b76-39a41d0bb9b8" />


6. Go to: http://localhost:3000. You should see the app running
7. Open another Powershell terminal and type: cd $HOME\Desktop\make-something
8. If you type : $start [followed by your instruction] and see the following screenshot, then you need to change the model from GPT 5.2 to 5.3 using \model (Tip: if you restart the terminal, just type "codex" to restart)
> <img width="1120" height="442" alt="image" src="https://github.com/user-attachments/assets/cae11118-ad0b-42e9-aa72-70768347ab2e" />

9. Use the Skill commands to build, edit & deploy as shown in https://www.makesomething.so/start (see examples below)
> <img width="855" height="300" alt="image" src="https://github.com/user-attachments/assets/d6b94010-211a-4d9a-acf6-64ec4f96d9de" />

The skills that is given ($start, $imlost, $fixit, $deploy) are just the beginning. there's actually a whole open library of skills at [skills.sh](https://skills.sh/).
 it's like an app store for AI agent abilities. people build skills and share them, and you can install any of them with a single command. there are hundreds of them — for design, debugging, deployment, marketing, and more.

some popular ones:
* web-design-guidelines — teaches your agent to make things look great
* frontend-design — best practices for building user interfaces
* systematic-debugging — a smarter way to find and fix bugs









