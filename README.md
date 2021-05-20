# Getting started

This tutorial will be focused on the command line variant of Git. If you have it installed already move on to the next section. For those who don't have Git installed click [here](https://git-scm.com/downloads " Download Link for the command line ver.").

<h2> Tutorial</h2>

**Fork and clone the repository you want to work on**

![step1](images/Step1.png)
  
 Go to your desired repository and on the top right there is a fork button. Click that and that'll fork over a copy of the repository so you can freely make edits without making any main changes.
  
**Clone the project locally to your machine** You can grab the URL for the clone command in the code tab.
  ![url](images/clone.png)
  <br>
  <br>
  
  ![step3](images/Step3.png)

<br>git clone "remove this and insert link to repo here". For showcase purposes I'll be using a personal repo so my command will look like the picture above.

**Go to the directory you just copied and create a new branch**

  ![step4](images/Step4.png)

</p><br>Once you've moved into the directory you cloned over create a new branch. git checkout -b testbranch I called my new branch testbranch but you can name it whatever is helpful to you.</p>

**Make your edits and commit**

  ![step5](images/Step5.png)

</br> Once you've made your changes execute git add . this command will add all files to the commit or if you want to be specific and not mess with the structure add the single file you made your edits to. I'll be choosing this route so for me it'll be git add Fractions.java. After that, we will commit using git commit -m "made edits to frac.java". Then type in git push you'll receive an error, that's fine the terminal will give you a recommendation copy and paste in that command and submit.

**Create a pull request**

![step6](images/Step6.png)
<br>Go to your repo and above it you should see a button called compare & pull request. Click it and if everything looks good to you click create pull request. This will submit a request to merge your branch onto the main branch.

![step7](images/Step7.png)

Your pull will then get reviewed by the owner of the repository or any other authorized users in the repo. Once reviewed and accepted your changes should be displayed in whatever branch you pointed your changes to!

<br>Congrats You've made your first contribution!
