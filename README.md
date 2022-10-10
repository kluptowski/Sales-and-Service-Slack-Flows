<a href="https://githubsfdeploy.herokuapp.com?owner=kluptowski&repo=Sales-and-Service-Slack-Flows&ref=master">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>

<p><h4>Instructions:</h4></p>

<ol>
  <li>Log in to your Salesforce org in a separate Chrome profile or incognito window</li>
  <li>Click the Deploy to Salesforce button directly above on this page</li>
  <li>In the newly opened tab, click Deploy</li>
  <li>Wait for the install to complete; est. 15 minutes. (you can check progress in the salesforce setup menu under Deployment Status. You will see "Deployment Complete" when done.) 
</ol>

<p><h4>Full post-install instructions and video can be found <a href="https://salesforce.quip.com/5SlmA9uOJPmO" target="_blank">here</a></h4></p>

<p><h4>Disclaimers:</h4></p>

<ul>
  <li>This was built using an SDO and is not guaranteed to work with any IDO</li>
  <li>Salesforce Field Level Security only deployed for the System Administrator, *Sales, and *Service profiles. Using the screen flows in slack with connected salesforce user of a different profile may cause the flow to error.</li>
  <li>You will need to make adjustments in the Salesforce Setup Menu > Custom Metadata Types > #se-demo-constants > Manage Reecords before the Sales flow will work.</li>
</ul>

