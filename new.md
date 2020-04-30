---


---

<h2 id="commiting-changes">Commiting changes</h2>
<p>So we’ve been working on our project and made some changes that we want to keep track of. This is how we do it.</p>
<ul>
<li>
<p>If we added a new file to our project since the last time that we commited a change, we have to notify git so that it can track the changes in that file as well.</p>
<ul>
<li>We do that by the <code>git add</code> command.
<ol>
<li>We first navigate into the root folder of the project we are working on.</li>
<li>Then we type <code>git add .</code> That is a space and a dot after the add and it means that we want to add all the files that are not tracked yet.</li>
<li>Then we type <code>git commit -m "our message"</code> with a meaningful message of the changes we made and/or the files we added to the project.</li>
<li>Lastly, the command <code>git push</code> will push the commit to our repository that we setup <a href="https://github.com/TasosBak/code-recipes/blob/master/github.md">here</a>.</li>
</ol>
</li>
</ul>
</li>
<li>
<p>If we didn’t add any new files or folders to our project and we just changed some existing ones we do 1, 3, and 4 of the steps above.</p>
</li>
</ul>

