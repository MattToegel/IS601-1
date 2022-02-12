<table><tr><td> <em>Assignment: </em> M2 Python-HW</td></tr>
<tr><td> <em>Student: </em> Dhananjay Wagh(dw42)</td></tr>
<tr><td> <em>Generated: </em> 2/11/2022 8:05:07 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-004-S22/m2-python-hw/grade/dw42" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <p>Make sure you have the dev/prod branches created before starting this assignment.</p>
<p>Setup steps:</p>
<ol>
<li><code>git checkout dev</code> </li>
<li><code>git pull origin dev</code></li>
<li><code>git checkout -b M2-Python-HW</code></li>
</ol>
<p>You&#39;ll have 3 problems to save for this assignment.</p>
<p>Each problem you&#39;re given a template <strong>Do not edit anything in the template except where the comments tell you to</strong>.</p>
<p>The templates are done in such a way to make it easier to capture the output in a screenshot (if it&#39;s still not able to fit well, you can zoom out in your browser).</p>
<p>You&#39;ll copy each template into their own separate .py files, immediately git add, git commit these files (you can do it together) so we can capture the difference/changes between the templates and your additions. This part is required for full credit.</p>
<p>HW steps:</p>
<ol>
<li>Open PyCharm at the root of your repository folder</li>
<li>In PyCharm create a new folder/directory called M2</li>
<li>Create 3 new files in this new M2 folder (problem1.py, problem2.py, problem3.py)</li>
<li>Paste each template into their respective files</li>
<li><code>git add .</code></li>
<li><code>git commit -m &quot;adding template baselines</code></li>
<li>Do the related work (you may do steps 8 and 9 as often as needed or you can do it all at once at the end)</li>
<li><code>git add .</code></li>
<li><code>git commit -m &quot;completed hw&quot;</code></li>
<li>When you&#39;re done push the branch<ol>
<li><code>git push origin M2-Python-HW</code></li>
</ol>
</li>
<li>Create the Pull Request with <strong>dev</strong> as base and <strong>M2-Python-HW</strong> as compare</li>
<li>Create a new file in the M2 folder in PyCharm called m2_submission.md</li>
<li>Fill out the below deliverable items, save the submission, and copy to markdown<ol>
<li>For this assignment you may get screenshots from your PyCharm output or terminal/console output</li>
</ol>
</li>
<li>Paste the markdown into the m2_submission.md</li>
<li>add/commit/push the md file<ol>
<li><code>git add m2_submission.md</code></li>
<li><code>git commit -m &quot;adding submission file&quot;</code></li>
<li><code>git push origin M2-Python-HW</code></li>
</ol>
</li>
<li>Merge the pull request from step 11</li>
<li>On your local machine sync the changes<ol>
<li><code>git checkout dev</code></li>
<li><code>git pull origin dev</code></li>
</ol>
</li>
<li>Make a pull request from <strong>prod</strong> as base and <strong>dev</strong> as compare and immediately merge it</li>
<li>Submit the link to the m2_submission.md file from the prod branch to Canvas</li>
</ol>
<p><strong>Template Files</strong>
You can find all 3 template files in this gist: <a href="https://gist.github.com/MattToegel/3c55ca7bb631ff6f492bf6f1ad27270e">https://gist.github.com/MattToegel/3c55ca7bb631ff6f492bf6f1ad27270e</a></p>
</td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Problem 1 - Only output Odd values of the Array under "Odds output" </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Clearly screenshot the output of Problem 1 showing the data</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/38325252/153546416-e7940d26-19c6-4d16-a6cb-a320d13e7545.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>1st half of the output<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/38325252/153546495-b3f2741a-429f-4e3c-8da4-7817a253ef0e.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>2nd half of the output<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Describe how you solved the problem</td></tr>
<tr><td> <em>Response:</em> <p>Step 1:Used the for loop and assigned the array to a variable <br>Step<br>2:Applied a if condition where the dividing every element by 2 is not<br>equal to 0 printed that<br><br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Problem 2 - Only output the sum/total of the list values by assigning it to the 'total' variable (the number must end in 2 decimal places, if it ends in 1 it must have a 0 at the end) </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Clearly screenshot the output of Problem 2 showing the data</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/38325252/153547376-6de99e8a-1c00-4a86-ae4b-f06752a149ec.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Output Showing the total<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Describe how you solved the problem</td></tr>
<tr><td> <em>Response:</em> <p>Used the sum() function to find sum and then used the round() function<br>to round the result of this to 2 places.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Problem 3 - Output the given values as positive under the "Positive Output" message (the data otherwise shouldn't change) </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Clearly screenshot the output of Problem 3 showing the data</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/38325252/153547628-2aec5392-6e4d-4b0b-99e5-6a46fb12a3c3.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>1st Half of the output<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/38325252/153547689-8571b179-600d-4b2e-a627-154f4af4b2a8.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>2 nd Half of output<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Describe how you solved the problem</td></tr>
<tr><td> <em>Response:</em> <p>Step 1 : Converted string list into integer list <br>Step 2 : Checked<br>if list element was less than 0, if this is true multiplied the<br>element by -1 and printed it else printed it as it is <br><br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Misc Items </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Pull Request URL for M2-Python-HW to dev</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/DhananjayWagh004/IS601/pull/2">https://github.com/DhananjayWagh004/IS601/pull/2</a> </td></tr>
<tr><td> <em>Sub-Task 2: </em> Talk about what you learned, any issues you had, how you resolve them</td></tr>
<tr><td> <em>Response:</em> <p>Learned how to convert a str list to an int list <br></p><br></td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-004-S22/m2-python-hw/grade/dw42" target="_blank">Grading</a></td></tr></table>
