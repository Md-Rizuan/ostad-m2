1. Repo Init:

   git init
   git remote add origin <repo-url>

   git push -u origin main

2. New Branch Creation:
   git checkout -b develop
   git push origin develop

   git checkout -b feature/login
   git push origin feature/login
3. After Changing the files then commit and push:
   git add .
   git commit -m "first commit"
   git push origin main

    I used merged in Github manually with compare and using pull request.
 4. Rebase strategy:
	   git checkout feature/login
	   git rebase main
	   *** Don't understand yet perfectly***

       and use interactive rebase using 
       git rebase -i HEAD~5

     ***** inside editor *****
  reword <commit1>
  squash <commit2>
  squash <commit3>
  squash <commit4>
  squash <commit5>

  After Rebase:

	  git push origin feature/profile --force
	
	  and I did mistake many times and this third repo and submit this one

Screenshot link: https://drive.google.com/drive/folders/1l4ikD0fN_8FD-Lhp5pLv3SQS25iTWTWw?usp=sharing
  
  
