# CV Dévekoppeur java junior 
maj 21Nov2021

#    cmd git     
-- publier sur le depot distant de GitHub de cv-dev
-- dépot distant créé sur URL
$ git init   
$ git add .
$ git commit -m "création cv-dev CR commentaires"
$ git branch -M master
$ git remote add srvdist https://github.com/garaixm/cvdev.git
$ git remote -v

$ git config --global user.name "garaixm"
$ git config --global user.email "goomytue@gmail.com"  

  -- TOKEN =  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

$ git remote set-url srvdist "https://garaixm:TOKEN@github.com/reps"

$ git push srvdist master  –- vers rpsydist

         URL  =   "https://github.com/reps" 
		 URLn =  "https://user.name:TOKEN@github.com/reps"
         reps = garaixm/cvdev.git
	   
	   --  $ git remote add srvdist URL  sinon  $ git remote set-url srvdist URLn 
        
URL = https://github.com/garaixm/cvdev.git
URLn = https://garaixm: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@github.com/garaixm/cvdev.git
 