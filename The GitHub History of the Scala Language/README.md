## Scala's real-world project repository data
<p><img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fjahed.net%2F%25D9%2585%25D8%25A7-%25D9%2587%25D9%2588-%25D9%2585%25D9%2588%25D9%2582%25D8%25B9-github-%25D9%2588%25D9%2584%25D9%2585%25D8%25A7%25D8%25B0%25D8%25A7-%25D9%258A%25D8%25B3%25D8%25AA%25D8%25AE%25D8%25AF%25D9%2585&psig=AOvVaw2dVKsOnj3NHMiwi7xSzER2&ust=1633395754540000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCOCi0L_Hr_MCFQAAAAAdAAAAABAU" alt="Someone's feet on table facing a television"></p>
<p>With almost 30k commits and a history spanning over ten years, Scala is a mature programming language. It is a general-purpose programming language that has recently become another prominent language for data scientists.</p>
<p>Scala is also an open source project. Open source projects have the advantage that their entire development histories -- who made changes, what was changed, code reviews, etc. -- are publicly available. </p>
<p>We're going to read in, clean up, and visualize the real world project repository of Scala that spans data from a version control system (Git) as well as a project hosting site (GitHub). We will find out who has had the most influence on its development and who are the experts.</p>
<p>The dataset we will use, which has been previously mined and extracted from GitHub, is comprised of three files:</p>
<ol>
<li><code>pulls_2011-2013.csv</code> contains the basic information about the pull requests, and spans from the end of 2011 up to (but not including) 2014.</li>
<li><code>pulls_2014-2018.csv</code> contains identical information, and spans from 2014 up to 2018.</li>
<li><code>pull_files.csv</code> contains the files that were modified by each pull request.</li>
</ol>
