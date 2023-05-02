Download Link: https://assignmentchef.com/product/solved-cloud-computing-lab-4-live-migration-in-a-group
<br>
<h2>Lab 4: Live Migration in a Group</h2>

Dear VM Nomads

<ul>

 <li>After migrate your first VM, you now need to move to a place with rich resource</li>

 <li>Migrating many docker images and doing it lively until your system halts</li>

 <li>Analysis why it halts and understand the idea of resource bottleneck</li>

</ul>

<h2>Goal for Lab 4</h2>

<ul>

 <li>Objectives:</li>

 <li>Understanding the basic techniques for VM migration</li>

 <li>Migrate containers to test your migration skill</li>

 <li>Understanding the concept of checkpoint and restore</li>

 <li>Successfully migrate multiple images either one by one or in a batch Writing a decent report</li>

</ul>

<h2>To Start</h2>

<ul>

 <li>Learn to do live migration in docker</li>

 <li>Using Checkpoint and Restore (CRIU) tool in docker to do this job</li>

 <li><a href="https://criu.org/Live_migration">https://criu.org/Live_migration</a> is your source to check</li>

 <li>Ask one of our friend/roommate and migrate your Golang job (with your ID or name) to his/her place</li>

 <li>Measure the duration of migration and collect all other runtime statistics</li>

 <li>New stuff: Write a script to move docker image automatically</li>

</ul>

<h2>Hints and Remarks</h2>

<ul>

 <li>CRIU tool is your best way to make it happen or you may implement your own code to do it</li>

 <li>More information can be found in docker-engine mail list and GitHub issues</li>

 <li>Either you steam your docker image or repeat your previous experiment in a fast loop</li>

 <li>Increase the number of concurrency and see when your system freezes</li>

 <li>In your report, you can show us when your system fails, how it fails and why</li>

</ul>

Bonus: if you find a way to fix the bottleneck and show us how it is being fixed based on reasons you found, you will get bonus points