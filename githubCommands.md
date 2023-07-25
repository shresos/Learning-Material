### create a new repository on the command line
echo "# chat_gpt_resume" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:shresos/chat_gpt_resume.git
git push -u origin main

push an existing repository from the command line
git remote add origin git@github.com:shresos/chat_gpt_resume.git
git branch -M main
git push -u origin main
