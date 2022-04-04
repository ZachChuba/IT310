<table><tr><td> <em>Assignment: </em> IT202 Milestone1 Deliverable</td></tr>
<tr><td> <em>Student: </em> Mohammad Hussain(msh52)</td></tr>
<tr><td> <em>Generated: </em> 4/4/2022 2:39:04 AM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT202-004-S22/it202-milestone1-deliverable/grade/msh52" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol>
<li>Checkout Milestone1 branch</li>
<li>Create a milestone1.md file in your Project folder</li>
<li>Git add/commit/push this empty file to Milestone1 (you&#39;ll need the link later) </li>
<li>Fill in the deliverable items<ol>
<li>For the proposal.md file use the direct link to milestone1.md from the Milestone1 branch for all of the features  </li>
<li>For each feature, add a direct link (or links) to the expected file the implements the feature from Heroku Prod (I.e, <a href="https://mt85-prod.herokuapp.com/Project/register.php">https://mt85-prod.herokuapp.com/Project/register.php</a>)</li>
</ol>
</li>
<li>Ensure your images display correctly in the sample markdown at the bottom</li>
<li>Save the submission items</li>
<li>Copy/paste the markdown from the &quot;Copy markdown to clipboard link&quot;</li>
<li>Paste the code into the milestone1.md file</li>
<li>Git add/commit/push the md file to Milestone1</li>
<li>Double check the images load when viewing the markdown file (points will be lost for invalid/non-loading images)</li>
<li>Make a pull request from Milestone1 to dev and merge it (resolve any conflicts)<ol>
<li>Make sure everything looks ok on heroku</li>
</ol>
</li>
<li>Make a pull request from dev to prod (resolve any conflicts) <ol>
<li>Make sure everything looks ok on heroku</li>
</ol>
</li>
<li>Submit the direct link from github prod branch to the milestone1.md file (no other links will be accepted and will result in 0)</li>
</ol>
</td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Feature: User will be able to register a new account </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add one or more screenshots of the application showing the form and validation errors per the feature requirements</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161477223-fa8e919d-0b48-4c2c-9be7-53a5e6afcd0f.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>invalid email<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161477545-cf77ce74-c9dd-4d73-84a3-573844b893fa.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>password dont match <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161477409-4718e0d9-cfed-4fbf-b1bd-7745cc7445f5.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>successful registration <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot of the Users table with data in it</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161477906-80dbfe53-fd2b-4235-b927-b297d0733af3.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>showing user table <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Hussain185/IT202-004/pull/19">https://github.com/Hussain185/IT202-004/pull/19</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Explain briefly how the process/code works</td></tr>
<tr><td> <em>Response:</em> <p>code checks if the correct email has been put, it checks for length<br>of the password also if the password matched, if the email is already<br>registered it gives an error message too.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Feature: User will be able to login to their account </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add one or more screenshots of the application showing the form and validation errors per the feature requirements</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161478991-d9044d5c-001c-436f-825e-40b7ef19bc44.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>email not found<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161479082-26c83c64-8816-45a8-b56c-a29cff334e10.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>invalid password <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot of successful login</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161479605-08c46577-097e-44c4-b324-07633332de40.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>successful login<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Hussain185/IT202-004/pull/20">https://github.com/Hussain185/IT202-004/pull/20</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Explain briefly how the process/code works</td></tr>
<tr><td> <em>Response:</em> <p>if the user puts correct username/email and password they will be able to<br>login otherwise ERRORS, when the registration took place it saved the user email<br>and user name and password. once the same user login it checks and<br>see if the user put the correct email/user and password recorded from user<br>table.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Feat: Users will be able to logout </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot showing the successful logout message</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161480201-78e4bee4-f070-4e96-a028-378e11c1c904.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>showing successfully logout<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot showing the logged out user can't access a login-protected page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161480835-8b79c899-f071-4a34-9209-65dbacddd465.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>showing logged out user can&#39;t access a login page<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Hussain185/IT202-004/pull/20">https://github.com/Hussain185/IT202-004/pull/20</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Explain briefly how the process/code works</td></tr>
<tr><td> <em>Response:</em> <p>anybody that was already logout can&#39;t access the page unless they login back.<br>and if u do profile.php u can&#39;t see the full page unless u<br>login.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Feature: Basic Security Rules Implemented / Basic Roles Implemented </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot showing the logged out user can't access a login-protected page (may be the same as similar request)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161480835-8b79c899-f071-4a34-9209-65dbacddd465.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>showing logged out user can&#39;t access a login page<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot showing a user without an appropriate role can't access the role-protected page (a test/dummy page is fine)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161482384-bf71fda8-9647-40b1-b822-662539a7b7b2.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>showing can&#39;t access the role-protected page<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add a screenshot of the Roles table with data</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161482612-4f2c5cea-3904-4065-a67c-5db473625fab.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>showing role table with admin<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 4: </em> Add a screenshot of the UserRoles table with data</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161482696-1ac9df71-9f5b-4f09-a157-2d480b3aa37a.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>showing user role table with data 1<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 5: </em> Add the related pull request(s) for these features</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Hussain185/IT202-004/pull/41">https://github.com/Hussain185/IT202-004/pull/41</a> </td></tr>
<tr><td> <em>Sub-Task 6: </em> Explain briefly how the process/code works for login-protected pages</td></tr>
<tr><td> <em>Response:</em> <p>code basically records the user email/ username and password and the user role<br>table shows who&#39;s the admin you can&#39;t access it without login <br></p><br></td></tr>
<tr><td> <em>Sub-Task 7: </em> Explain briefly how the process/code works for role-protected pages</td></tr>
<tr><td> <em>Response:</em> <p>can&#39;t access it if you are not the admin.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 5: </em> Feature: Site should have basic styles/theme applied; everything should be styled </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshots to show examples of your site's styles/theme</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161482384-bf71fda8-9647-40b1-b822-662539a7b7b2.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>showing basic styles<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Hussain185/IT202-004/pull/36">https://github.com/Hussain185/IT202-004/pull/36</a> </td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain your CSS at a high level</td></tr>
<tr><td> <em>Response:</em> <p>basic colors and background was added and text color and font <br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 6: </em> Feature: Any output messages/errors should be "user friendly" </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshots of some examples of errors/messages</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161483816-0e76e555-c133-4364-ae90-ff19588cf804.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>showing error message<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a related pull request</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Hussain185/IT202-004/pull/20">https://github.com/Hussain185/IT202-004/pull/20</a> </td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain how you made messages user friendly</td></tr>
<tr><td> <em>Response:</em> <p>if the user or the email is not put correctly it will show<br>a flash message of what missing or not put correctly <br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 7: </em> Feature: Users will be able to see their profile </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshots of the User Profile page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161484262-df0d19ca-7d88-43bf-92fc-7f8f8be8bf81.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>showing user be able to see their profile<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Hussain185/IT202-004/pull/23">https://github.com/Hussain185/IT202-004/pull/23</a> </td></tr>
<tr><td> <em>Sub-Task 3: </em> Explain briefly how the process/code works (view only)</td></tr>
<tr><td> <em>Response:</em> <p>if the user login successfully they will be able to see the home<br>page with everything on top. profile page has the option to edited their<br>profile<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 8: </em> Feature: User will be able to edit their profile </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshots of the User Profile page validation messages and success messages</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161484977-4482690f-19d6-4d87-b5b0-a53af7094d13.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>showing error message<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161485572-4d6b8a30-7a47-4bb5-9a13-c4f9adbd37ec.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>showing success message shah2 to shah3<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add before and after screenshots of the Users table when a user edits their profile</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161485344-723398db-24fa-4984-bef8-203b0d2a0ea9.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>showing users table before edit profile <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161485706-268804e2-0977-4c12-94d6-27fef22b3c46.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>showing users table after edit profile shah12 to shah123<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Hussain185/IT202-004/pull/23">https://github.com/Hussain185/IT202-004/pull/23</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Explain briefly how the process/code works (edit only)</td></tr>
<tr><td> <em>Response:</em> <p>user is able to change their username/email once they access edit profile page<br>and change everything the user role table updates the new username/email and replace<br>the old ones.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 9: </em> Proposal and Issues </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshots showing your updated proposal.md file with checkmarks, dates, and link to milestone1.md accordingly and a direct link to the path on heroku prod (see instructions)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161457343-3d0e49c9-4f96-4cf1-8ec7-330c26824664.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>showing checkmarks, date, link of proposal.md<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add screenshots showing which issues are done/closed (project board) Incomplete Issues should not be closed</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98345252/161486911-82a10392-4acf-4a3f-82f1-68815e2d6f7b.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>showing issues are done<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT202-004-S22/it202-milestone1-deliverable/grade/msh52" target="_blank">Grading</a></td></tr></table>