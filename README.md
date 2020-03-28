
<h3>Git Star : A simple and powerful git workflow alternative</h3>
<img src="logo.png" width="250" style="padding: 0 15px; float: left;">
<h3>To Install</h3>
<code>$>brew install git-star</code>
<h3>Typical Workflow</h3>
<pre><code>
	$><font color="green" size="4"><b>git start</b></font> my-cool-feature
		do normal edits ... 
		git add .
		git commit -m "My Descriptive Message"
		git push
	$><font color="green" size="4"><b>git test</b></font> my-cool-feature
		Branch QAv1.0 successfully created
		PR opened for QAv1.0 <- my-cool-feature
		PR URL is https://github.com/youraccount/your-repo/pull/1
		Run git staging after PR is approved and merged
	$><font color="green" size="4"><b>git acceptance</b></font>
		All approved PRs from latest QA branch will be merged to Staging
		Run git release after Product Owner approves features for release
	$><font color="green" size="4"><b>git release</b></font>
		Releasing version v1.2.0 from staging to Production (master)
		709f414 Merge branch 'staging' into master
		e035e94 Merge branch 'some-cool-feature' into staging
		67846d2 Some very descriptive comment about this feature
		Successfully released changes of v1.2.0 from staging to master 
</code>
</pre>
<p>


<ul>
	<li type="none">
		<h1>
			<ul>
				<li type="none"><!-- <b>(S)</b>tart a feature//-->
					<ul>
						<li type="none"><img src="git-start.png" zwidth="450" style="padding: 0 15px; float: left;">
						</li>
					</ul>
				</li>
				<li type="none">(T)</b>est the feature on a combined test branch after <b>(A)</b>pproving the pull request (optional)
					<ul>
						<li type="none"><img src="git-test.png" zwidth="450" style="padding: 0 15px; float: left;">
						</li>
					</ul>
				</li>
				<li type="none">(R)</b>elease the set of features to the production branch
					<ul>
						<li type="none"><img src="git-release.png" zwidth="75%" style="padding: 0 15px; float: left;">
						</li>
					</ul>
				</li>
		</h1>		
	</li>
</ul>
