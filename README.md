Desolé monsieur,j'ai essayé de faire un push mais j'arrive toujours pas a resoudre cela:
\Movies> git branch -M main
PS C:\Users\USER\OneDrive\Documents\Movies> git  remote add origin https://github.com/Kabyr2Ndiaye/Services_Movies.git
PS C:\Users\USER\OneDrive\Documents\Movies> git checkout main
Already on 'main'
PS C:\Users\USER\OneDrive\Documents\Movies> git push -u origin  main
remote: Permission to Kabyr2Ndiaye/Services_Movies.git denied to kabyrNdiaye.
fatal: unable to access 'https://github.com/Kabyr2Ndiaye/Services_Movies.git/': The requested URL returned error: 403
PS C:\Users\USER\OneDrive\Documents\Movies> git congif user.email
git: 'congif' is not a git command. See 'git --help'.

The most similar command is
        config
PS C:\Users\USER\OneDrive\Documents\Movies> git config user.email
sokhnamaimounatoukabyrndiaye@esp.sn
PS C:\Users\USER\OneDrive\Documents\Movies> git config user.name 
Kabyr2Ndiaye
PS C:\Users\USER\OneDrive\Documents\Movies> ^C
PS C:\Users\USER\OneDrive\Documents\Movies> git remote set-url origin git@github.com:Kabyr2Ndiaye/Services_Movies.git
PS C:\Users\USER\OneDrive\Documents\Movies> git push -u origin  main                        
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository. 

Please make sure you have the correct access rights
and the repository exists.
