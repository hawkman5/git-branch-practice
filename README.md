# git-branch-practice

I was adding a new feature to a personal project and created a "mobile-test" branch separate from the "main" branch in order to work on this feature. After a few days of work in this second branch I did not see my github profile updating my chart with contributions. Obviously this frusterated me so I searched on stack overflow and reddit for answers. I had difficulty finding a suitable answer for my problem so I decided to test it myself.

I did not want to test this within my personal project, so I created this git-branch-practice repo to conduct my test. Setting up the repo, readme, and index.html took up three contributions on github, so I tracked this in my html file and added, committed, and pushed a "Contribution 4". This showed up as expected on github and in my contributions chart. I did this a few times to have a couple commits/contributions to my main branch, and then I created a "test-branch".

Within the test-branch I made a few commits and leabeled them with test branch at the end so I could keep track of where they came from. As expected, My contributions did not update in my github chart due to github only tracking the main branch of your repo. These test branch commits did push correctly to github and I could see them when I changed my branch on the github UI, but they do not show up in the chart for your daily contributions. 

Now it was time to test. In the terminal I merged my test-branch into my main branch and then did "git push origin main". The main branch on github was now updated with the test-branch commits and those commits now also showed up on my github contribution chart. 

SUCCESS!!!

