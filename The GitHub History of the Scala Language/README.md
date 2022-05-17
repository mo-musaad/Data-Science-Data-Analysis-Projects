## Scala's real-world project repository data
<p><img src="[https://jahed.net/wp-content/uploads/2021/05/github-jahed.png](https://www.google.com/imgres?imgurl=https%3A%2F%2Fres.cloudinary.com%2Fpracticaldev%2Fimage%2Ffetch%2Fs--sWV8Y0kc--%2Fc_imagga_scale%2Cf_auto%2Cfl_progressive%2Ch_900%2Cq_auto%2Cw_1600%2Fhttps%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fi%2Fkml9j34p9taplrnqtcez.jpg&imgrefurl=https%3A%2F%2Fdev.to%2Fdieguiviti%2Fgithub-api-oauth-in-2020-5dei&tbnid=4QkcB3Wrn7oWHM&vet=12ahUKEwim6bnBnOf3AhWJxYUKHdzyCqYQMygXegUIARCIAg..i&docid=Z0DyA_kYTpAjyM&w=1600&h=900&q=github&ved=2ahUKEwim6bnBnOf3AhWJxYUKHdzyCqYQMygXegUIARCIAg)" alt="Github image"></p>
<p>With almost 30k commits and a history spanning over ten years, Scala is a mature programming language. It is a general-purpose programming language that has recently become another prominent language for data scientists.</p>
<p>Scala is also an open source project. Open source projects have the advantage that their entire development histories -- who made changes, what was changed, code reviews, etc. -- are publicly available. </p>
<p>We're going to read in, clean up, and visualize the real world project repository of Scala that spans data from a version control system (Git) as well as a project hosting site (GitHub). We will find out who has had the most influence on its development and who are the experts.</p>
<p>The dataset we will use, which has been previously mined and extracted from GitHub, is comprised of three files:</p>
<ol>
<li><code>pulls_2011-2013.csv</code> contains the basic information about the pull requests, and spans from the end of 2011 up to (but not including) 2014.</li>
<li><code>pulls_2014-2018.csv</code> contains identical information, and spans from 2014 up to 2018.</li>
<li><code>pull_files.csv</code> contains the files that were modified by each pull request.</li>
</ol>
