---


---

<h6 id="disclaimer---this-file-is-a-copy-of-the--official-doc-by-github-with-some-changes-that-are-helpful-for-my-own-use.-please-refer-to-the-original-docs.">Disclaimer - This file is a copy of the  <a href="https://help.github.com/en/enterprise/2.14/user/articles/creating-a-new-repository">official doc by github</a> with some changes that are helpful for my own use. Please refer to the original docs.</h6>
<h2 id="creating-a-new-repository">Creating a new repository</h2>
<p>You can create a new repository on your personal account or any organization where you have sufficient permissions.</p>
<ol>
<li>
<p>In the upper-right corner of any page, click <strong>+</strong>, and then click <strong>New repository</strong>.<br>
<img src="https://github-images.s3.amazonaws.com/enterprise/2.14/assets/images/help/repository/repo-create.png" alt="new repo"></p>
</li>
<li>
<p>In the Owner drop-down, select the account you wish to create the repository on.<br>
<img src="https://github-images.s3.amazonaws.com/enterprise/2.14/assets/images/help/repository/create-repository-owner.png" alt="repository name"></p>
</li>
<li>
<p>Type a name for your repository, and an optional description.<br>
<img src="https://github-images.s3.amazonaws.com/enterprise/2.14/assets/images/help/repository/create-repository-name.png" alt="repository name"></p>
</li>
<li>
<p>Choose to make the repository either public or private. Public repositories are visible to the public, while private repositories are only accessible to you, and people you share them with. For more information, see “<a href="https://help.github.com/en/enterprise/2.14/user/articles/setting-repository-visibility">Setting repository visibility</a>.”<br>
<img src="https://github-images.s3.amazonaws.com/enterprise/2.14/assets/images/help/repository/create-repository-public-private.png" alt="public vs private"></p>
</li>
<li>
<p>There are a number of optional items you can pre-populate your repository with. If you’re importing an existing repository to GitHub Enterprise, don’t choose any of these options, as you may introduce a merge conflict. You can choose to add new files using the command line later. For more information, see “<a href="https://help.github.com/en/enterprise/2.14/user/articles/importing-a-git-repository-using-the-command-line">Importing a Git repository using the command line</a>,” “<a href="https://help.github.com/en/enterprise/2.14/user/articles/adding-a-file-to-a-repository-using-the-command-line">Adding a file to a repository using the command line</a>,” and “<a href="https://help.github.com/en/enterprise/2.14/user/articles/addressing-merge-conflicts">Addressing merge conflicts</a>.”</p>
</li>
</ol>
<ul>
<li>You can create a README, which is a document describing your project. For more information, see “<a href="https://help.github.com/en/enterprise/2.14/user/articles/about-readmes">About READMEs</a>.” <strong>I would recommend leaving that box unchecked as it may interfere with the process of uploading an existing project from your computer.</strong></li>
<li>You can create a  <em>.gitignore</em>  file, which is a set of ignore rules. For more information, see “<a href="https://help.github.com/en/enterprise/2.14/user/articles/ignoring-files">Ignoring files</a>.”</li>
</ul>
<ol start="6">
<li>Click <strong>Create repository</strong>.</li>
</ol>
<blockquote>
<p><strong>Important</strong><br>
When we create our repository, we will be presented with a new page. Do not close that page the link in the quick setup and the commands below will be useful in a minute.<br>
<img src="https://i.imgur.com/D4YEfoE.png" alt="desc"></p>
</blockquote>
<ol start="7">
<li>We then <strong>move on to the folder of our project on our computer</strong>. We have to navigate to this folder via the command line and when we arrive there we do the following one-by-one:</li>
</ol>
<blockquote>
<p>In the <strong>git remote add</strong> command below you must replace  <strong>put-github-username-here</strong> and <strong>put-repository-name-here</strong> with your own. Alternatively you could type git remote add origin and then paste the link that was provided to you when you created the repository, as is shown in the picture above.</p>
</blockquote>
<hr>
<pre><code>git init
git commit -m "My first commit."
git remote add origin https://github.com/put-github-username-here/put-repository-name-here.git
git push -u origin master
</code></pre>
<p>The project is now successfully uploaded.</p>

