<h1>Microsoft Windows-Defender and Firewall Project </h1>
<h2>  Project Overview:</h2>
<ul>
  <li>Locate Microsoft Windows Security Virus and Threat Protection</li>
  <li>Run Microsoft Windows Defender Antivirus Quick Scan</li>
  <li>Review Microsoft Windows Defender Antivirus Quick Scan Threat History</li>
  <li>Configure Firewall Rules using Microsoft Windows Defender Firewall with and without Advanced Security</li>
</ul>

<h3>Skills Practiced</h3>

<ul> 
  <li>Microsoft Windows Defender, troubleshooting, and cyber defense</li> </ul>

  <h2>Exercise 1 of lab # 1: Review Windows Security Virus & threat protection</h2>

<ol>
  <li> I began by locating and opening Windows Security Virus & Threat Protection. This can be done by clicking the Windows Start button and selecting Settings on the computer in the lab.</li>
  <li>Click on the Windows Settings page and select Update & Security.</li>
  <li>Under Update & Security, select Windows Security.</li>
  <li>Then select Virus and Threat Protection to arrive at the page below.</li>
</ol>

Picture here

<br> As you can see on the Virus & threat protection  page there are not any current threats that are reported.

You also have to option to see on when the last scan occurred, how long the scan took, and how many files were scanned. 

You have the option to click the button to start a quick scan or access scan options to run a full scan or a custom scan on this page. </br>

Picture

<br> On the same screen you will notice Virus & threat protection settings: Here, you can access options for managing your virus and threat protection settings. 

On The Virus & Threat Protection Updates option: Here, you can view the last time your virus definitions were updated. 

And the Ransomware protection: Here, you can choose to enable controlled folder access. This protects memory, files, and folders from unauthorized changes.</br>

<h2>Exercise 2 Task 1: Update Threat Definitions </h2>

<br>Under Virus & threat protection updates, I Clicked to Check for updates </br>

Picture
picture

<br> I then clicked check for updates again and in the screenshot below you will notice that the last update time and date have changed.</br>
Picture
<h2>Exercise 3: Run Antivirus Quick Scan</h2>
<br> In this exercise I ran an antivirus quick scan. I did this by Clicking the Quick Scan button on the Virus & Threat Protection screen. 

This scan took several minutes to run.</br> 
Picture 
picture 

<br> When the quick scan was completed I clicked on threat history to show the results of the last scan. </br>
picture

<br>The results are as follows: No threats out of 10808 files scanned. </br>

<h2>Lab # 2 
</h2>
<h2> Overview Of Lab #2 </h2>
<ul>
  <li>Configure Firewall Rules Using Windows Defender Firewall</li>
  <li>Configure Firewall Rules Using Windows Defender Firewall with Advanced Security</li>
</ul>

<h2>Exercise 1 Lab #2: Configure Firewall Rules Using Windows Defender Firewall</h2>
<br> In this exercise I reviewed the Windows Defender Firewall configuration.</br>
<ol>
  <li>First, click the Windows Start button, and then select Windows Security.</li>
  <li>Then, click Firewall & network protection.</li>
</ol>
Picture
<br> Then I clicked on Domain network and I Verified that the Windows Defender Firewall was toggled to On.</br>
Picture
<br> Then I hit the back button and clicked on a private network to verify that the  Windows Defender Firewall is toggled to On.</br>
Picture
<br> Then I did the same with the Public network. I verified that the Windows Defender Firewall is toggled to On. 

After I verified that I clicked on Allow an app through firewall and scrolled to Scroll to Mozilla Firefox. 

Then clicked the public box on Mozilla Firefox because the public box was unclicked. <br>

Picture

<br> Then I Clicked OK to return to the Firewall & network protection screen. Users will now be able to use Mozilla Firefox on the public network.</br>

picture

<h2>Exercise 2: Configure Firewall Rules using Windows Defender Firewall with Advanced Security
</h2>

<br> For this project, I explored Windows Defender Firewall with Advanced Security to change a rule already set up. I used specific guidelines for doing this.

Allow the connection for Key Management Service on the Domain and Private network.

Deny the connection for Key Management Service on the Public network.

I first Selected Advanced settings on the Firewall & network protection screen.</br>

Picture

<br> I then clicked on Inbound rules. On this page you will see a green checkmark next to a rule, it means it's turned on and ready to let things come in. 

If there's no checkmark, the rule is there but it's not turned on yet.</br>

picture

<br> I then scrolled to the Key Management Service inbound rule in the Overview panel of Windows Defender Firewall with Advanced Security. 

I noticed that the policy is currently not enabled (the Enabled column says No.) <br> 

picture

<br>I Double-click to enabled, the rule. So that the Action column would say Allow

Then I Click the Advanced tab.</br>

Picture

<br> we want to allow communication only with the domain and private networks, So I unchecked the Public box  then I clicked Apply, and then clicked Ok.</br>

Picture
Picture
<br>Now I created an inbound rule that blocks communication with the public network. Since the new rule will be similar to the last, I  then copied  the existing rule. 
I right-clicked and Ctrl v to make a second copy of the Key Management Service (TCP-In).

Then I Double-click the second rule to open the **Key Management Service *TCP-IN) Properties. 

We want to block connection with the public network,  I then selected Block the connection on the General tab and Clicked Apply</br>

picture

<br> Once that was done I Clicked on the advanced setting tab and on the Domain and Private boxes I removed the checkmarks. 
Then Click the Public to add the checkmark. And then Clicked OK.</br>

Picture

<br> Once that was complete I then Right-click each Key Management Service (TCP-In) rule and click Enable rule.
Now you will see that a green checkmark appears next to the first rule indicating that the rule allowing communication is enabled. </br>

picture

<br> A circle with a line through it appears next to the second rule indicating that the rule blocking communication is enabled.<br>


























