<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Welcome file</title>
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__left">
    <div class="stackedit__toc">
      
<ul>
<li><a href="#welcome-to-our-git-workshop">Welcome to our Git Workshop</a></li>
<li><a href="#lets-start-with-git-💪">Let’s Start with Git 💪</a>
<ul>
<li><a href="#how-git-works">how Git Works:</a></li>
<li><a href="#now-lets-start">now let’s Start</a></li>
<li><a href="#how-diff--its-work-in-git">How diff  it’s work in git</a></li>
</ul>
</li>
<li><a href="#github-time-👀👍👌">GitHub Time 👀👍👌</a>
<ul>
<li></li>
<li><a href="#📜-this-is-a-list-of-some-usual-commands-line-">📜 this is a list of some usual commands line :</a></li>
</ul>
</li>
<li><a href="#welcome-to-our-git-workshop-1">Welcome to our Git Workshop</a></li>
<li><a href="#lets-start-with-git-💪-1">Let’s Start with Git 💪</a>
<ul>
<li><a href="#how-git-works-1">how Git Works:</a></li>
<li><a href="#now-lets-start-1">now let’s Start</a></li>
<li><a href="#how-diff--its-work-in-git-1">How diff  it’s work in git</a></li>
</ul>
</li>
<li><a href="#github-time-👀👍👌-1">GitHub Time 👀👍👌</a>
<ul>
<li></li>
<li><a href="#📜-this-is-a-list-of-some-usual-commands-line--1">📜 this is a list of some usual commands line :</a></li>
</ul>
</li>
</ul>

    </div>
  </div>
  <div class="stackedit__right">
    <div class="stackedit__html">
      <h1 id="welcome-to-our-git-workshop">Welcome to our Git Workshop</h1>
<p>Hi! I’m  <strong>Abdellatif Ahammad</strong>  and  This is the full documentation that i make for using <strong>Git</strong> and <strong>Github</strong><br>
enjoy 😄 😉 🙏</p>
<h1 id="lets-start-with-git-💪">Let’s Start with Git 💪</h1>
<h2 id="how-git-works">how Git Works:</h2>
<blockquote>
<p>📌<br>
this is very important</p>
</blockquote>
<p><img src="https://www.le-fab-lab.com/data/images/git-indexation-commit.png" alt="enter image description here"></p>
<h2 id="now-lets-start">now let’s Start</h2>
<ul>
<li><strong>git config --global <a href="http://user.name">user.name</a> "your_name"</strong></li>
</ul>
<blockquote>
<p>make your first configuration put first your name</p>
</blockquote>
<ul>
<li><strong>git config --global user.email "your_email"</strong></li>
</ul>
<blockquote>
<p>and here put  your email</p>
</blockquote>
<ul>
<li><strong>git config --list</strong></li>
</ul>
<blockquote>
<p>see the Git configuration list on your computer</p>
</blockquote>
<ul>
<li><strong>git init</strong></li>
</ul>
<blockquote>
<p>this command is for  create new repository (check your project to find a hidden repository .git 👌 if you are a GNU Linux user you can use <strong>ls -la</strong> on your terminal )</p>
</blockquote>
<ul>
<li><strong>git add <em>&lt;file_name&gt;</em></strong></li>
</ul>
<blockquote>
<p>add changes to INDEX(stage area) for let git track your file</p>
</blockquote>
<ul>
<li><strong>git add all</strong></li>
</ul>
<blockquote>
<p>for add all changes to INDEX (you can also use -&gt; git add *)</p>
</blockquote>
<ul>
<li><strong>git rm <em>&lt;file_name&gt;</em></strong></li>
</ul>
<blockquote>
<p>for remove or delete a file from the staging and working area</p>
</blockquote>
<ul>
<li><strong>git commit -m "#210: add function"</strong></li>
</ul>
<blockquote>
<p>this command is for commit all changes in the staging area to the repository -m it’s mean message you can write here a message for inform all the other people that you do this thing</p>
</blockquote>
<ul>
<li><strong>git log</strong></li>
<li><strong>git log -n$</strong></li>
<li><strong>git log --oneline</strong></li>
<li><strong>git log --until=2019-10-17</strong></li>
<li><strong>git log --author= 'name’</strong></li>
</ul>
<blockquote>
<p>all this commands it’s for seeing  you  commits NB:in the second one replace the $ with a number for limit the number of results, for the other one you try it your self it’s your turn 😎 😉</p>
</blockquote>
<ul>
<li><strong>git status</strong></li>
</ul>
<blockquote>
<p>this one is for see the changes in the working and the staging  directory</p>
</blockquote>
<ul>
<li><strong>git diff</strong></li>
</ul>
<blockquote>
<p>to Show changes between commits, commit and working tree this command it’s yours.<br>
for GNU Linux users you already know that hhh 💪</p>
</blockquote>
<ul>
<li><strong>git diff --cached</strong></li>
</ul>
<blockquote>
<p>in the old versions of git the people using this command to Show changes between commits, etc.<br>
NB: it’s steel working for the new version too</p>
</blockquote>
<ul>
<li><strong>git diff --staged</strong></li>
</ul>
<blockquote>
<p>is the same thing but  this one for the new versions of</p>
</blockquote>
<ul>
<li><strong>git mv <em>&lt;file_name&gt; &lt;new_dir&gt;/&lt;file_name&gt;</em></strong></li>
</ul>
<blockquote>
<p>when you want to change a the path of your file use this one</p>
</blockquote>
<ul>
<li><strong>git diff  --color-words <em>&lt;file_name&gt;</em></strong></li>
</ul>
<blockquote>
<p>to show only the words that changed in a file</p>
</blockquote>
<h2 id="how-diff--its-work-in-git">How diff  it’s work in git</h2>
<p><img src="https://sen.enst.fr/system/files/76b42e5058222fb37f960ca259ff9794/diff.svg_.png" alt="enter image description here"></p>
<h1 id="github-time-👀👍👌">GitHub Time 👀👍👌</h1>
<blockquote>
<h3 id="first-of-all-we-need-to-understand--how-github-is-working">first of all we need to understand  how GitHub is working</h3>
</blockquote>
<p><img src="https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2016/11/Git-Architechture-Git-Tutorial-Edureka-2-768x720.png" alt="enter image description here"></p>
<h2 id="📜-this-is-a-list-of-some-usual-commands-line-">📜 this is a list of some usual commands line :</h2>
<ul>
<li><strong>git remote</strong></li>
<li><strong>git remote add origin https://</strong></li>
<li><strong>git remote</strong></li>
<li><strong>get remote -v</strong></li>
<li><strong>git fetch</strong></li>
<li><strong>git merge origin/master</strong></li>
<li><strong>git pull</strong></li>
<li><strong>git push</strong></li>
<li><strong>git push -u origin master</strong></li>
<li><strong>git branch</strong></li>
<li><strong>git branch master</strong></li>
<li><strong>git branch master -a</strong></li>
<li><strong>git clone https://</strong></li>
</ul>
<h3 id="thats-all-for-now-thanks-for-visiting-my-little-documentation">that’s all for now thanks for visiting my little documentation</h3>
<blockquote>
<p>you can also check the bash file there it’s very nice</p>
</blockquote>
<h1 id="welcome-to-our-git-workshop-1">Welcome to our Git Workshop</h1>
<p>Hi! I’m  <strong>Abdellatif Ahammad</strong>  and  This is the full documentation that i make for using <strong>Git</strong> and <strong>Github</strong><br>
enjoy 😄 😉 🙏</p>
<h1 id="lets-start-with-git-💪-1">Let’s Start with Git 💪</h1>
<h2 id="how-git-works-1">how Git Works:</h2>
<blockquote>
<p>📌<br>
this is very important</p>
</blockquote>
<p><img src="https://www.le-fab-lab.com/data/images/git-indexation-commit.png" alt="enter image description here"></p>
<h2 id="now-lets-start-1">now let’s Start</h2>
<ul>
<li><strong>git config --global <a href="http://user.name">user.name</a> "your_name"</strong></li>
</ul>
<blockquote>
<p>make your first configuration put first your name</p>
</blockquote>
<ul>
<li><strong>git config --global user.email "your_email"</strong></li>
</ul>
<blockquote>
<p>and here put  your email</p>
</blockquote>
<ul>
<li><strong>git config --list</strong></li>
</ul>
<blockquote>
<p>see the Git configuration list on your computer</p>
</blockquote>
<ul>
<li><strong>git init</strong></li>
</ul>
<blockquote>
<p>this command is for  create new repository (check your project to find a hidden repository .git 👌 if you are a GNU Linux user you can use <strong>ls -la</strong> on your terminal )</p>
</blockquote>
<ul>
<li><strong>git add <em>&lt;file_name&gt;</em></strong></li>
</ul>
<blockquote>
<p>add changes to INDEX(stage area) for let git track your file</p>
</blockquote>
<ul>
<li><strong>git add all</strong></li>
</ul>
<blockquote>
<p>for add all changes to INDEX (you can also use -&gt; git add *)</p>
</blockquote>
<ul>
<li><strong>git rm <em>&lt;file_name&gt;</em></strong></li>
</ul>
<blockquote>
<p>for remove or delete a file from the staging and working area</p>
</blockquote>
<ul>
<li><strong>git commit -m "#210: add function"</strong></li>
</ul>
<blockquote>
<p>this command is for commit all changes in the staging area to the repository -m it’s mean message you can write here a message for inform all the other people that you do this thing</p>
</blockquote>
<ul>
<li><strong>git log</strong></li>
<li><strong>git log -n$</strong></li>
<li><strong>git log --oneline</strong></li>
<li><strong>git log --until=2019-10-17</strong></li>
<li><strong>git log --author= 'name’</strong></li>
</ul>
<blockquote>
<p>all this commands it’s for seeing  you  commits NB:in the second one replace the $ with a number for limit the number of results, for the other one you try it your self it’s your turn 😎 😉</p>
</blockquote>
<ul>
<li><strong>git status</strong></li>
</ul>
<blockquote>
<p>this one is for see the changes in the working and the staging  directory</p>
</blockquote>
<ul>
<li><strong>git diff</strong></li>
</ul>
<blockquote>
<p>to Show changes between commits, commit and working tree this command it’s yours.<br>
for GNU Linux users you already know that hhh 💪</p>
</blockquote>
<ul>
<li><strong>git diff --cached</strong></li>
</ul>
<blockquote>
<p>in the old versions of git the people using this command to Show changes between commits, etc.<br>
NB: it’s steel working for the new version too</p>
</blockquote>
<ul>
<li><strong>git diff --staged</strong></li>
</ul>
<blockquote>
<p>is the same thing but  this one for the new versions of</p>
</blockquote>
<ul>
<li><strong>git mv <em>&lt;file_name&gt; &lt;new_dir&gt;/&lt;file_name&gt;</em></strong></li>
</ul>
<blockquote>
<p>when you want to change a the path of your file use this one</p>
</blockquote>
<ul>
<li><strong>git diff  --color-words <em>&lt;file_name&gt;</em></strong></li>
</ul>
<blockquote>
<p>to show only the words that changed in a file</p>
</blockquote>
<h2 id="how-diff--its-work-in-git-1">How diff  it’s work in git</h2>
<p><img src="https://sen.enst.fr/system/files/76b42e5058222fb37f960ca259ff9794/diff.svg_.png" alt="enter image description here"></p>
<h1 id="github-time-👀👍👌-1">GitHub Time 👀👍👌</h1>
<blockquote>
<h3 id="first-of-all-we-need-to-understand--how-github-is-working-1">first of all we need to understand  how GitHub is working</h3>
</blockquote>
<p><img src="https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2016/11/Git-Architechture-Git-Tutorial-Edureka-2-768x720.png" alt="enter image description here"></p>
<h2 id="📜-this-is-a-list-of-some-usual-commands-line--1">📜 this is a list of some usual commands line :</h2>
<ul>
<li><strong>git remote</strong></li>
<li><strong>git remote add origin https://</strong></li>
<li><strong>git remote</strong></li>
<li><strong>get remote -v</strong></li>
<li><strong>git fetch</strong></li>
<li><strong>git merge origin/master</strong></li>
<li><strong>git pull</strong></li>
<li><strong>git push</strong></li>
<li><strong>git push -u origin master</strong></li>
<li><strong>git branch</strong></li>
<li><strong>git branch master</strong></li>
<li><strong>git branch master -a</strong></li>
<li><strong>git clone https://</strong></li>
</ul>
<h3 id="thats-all-for-now-thanks-for-visiting-my-little-documentation-1">that’s all for now thanks for visiting my little documentation</h3>
<blockquote>
<p>you can also check the bash file there it’s very nice</p>
</blockquote>

    </div>
  </div>
</body>

</html>
