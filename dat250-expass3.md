# Rapport: DAT250 Experiment 3
<p>I have completed the main part of the assignment, and due to a large workload in different courses I have not done the optional part. I have not tried too hard to catch all the exceptions and make the program robust, but there are some exceptions for catching large errors.</p>
<p>In order to complete the assignment I had to make some changes to the back-end of the program, most notably adding an "if" to handle copying of the list containing voteOptions. This was made necessary as I ran into a problem where in some cases the original list of voteOptions was attempted modified while being iterated over.</p>

<h3>Technical difficulties: </h3>
<p> 1. I had some technical difficulties pretty early with opening the.vue files on my Mac, as the project kept "collapsing" and refreshing everytime I opened a .vue file. I am pretty sure this is due to lack of available RAM, but I not to sure as I only managed to make it not collapse once. However, I have more powerful PC at home which I used to complete the assignment.</p>
<p> 2. Other issues I had was that I struggled quite a bit getting my voteOptions to show in the web browser due to different handling of the objects.</p>

<h3>"Incomplete portion of my program"</h3>
<p>In the process of making my frontend work, I made some changes to my backend. This has given me errors when attempting to manually create voteOptions on my backend. The problem is that they are not added to the existing list of voteOptions in their respective poll. Therefore, my tests on the backend will fail (as they are all in the same method), however it is only works up until step 8. I have not spent a lot of time fixing this, since everything works seamlessly if created on the frontend.</p>

<h4>Links:</h4>

<hlink>https://github.com/h599025/PollApp</hlink>
<hlink>https://github.com/h599025/PollAppFrontend</hlink>