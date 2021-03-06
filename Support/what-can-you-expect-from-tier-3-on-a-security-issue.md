{{{
  "title": "What can you expect from CenturyLink Cloud on a Security Issue",
  "date": "11-12-2014",
  "author": "Gavin McMurdo",
  "attachments": [],
  "contentIsHTML": true
}}}

<h3>Description (goal/purpose)</h3>
<p>This KB covers what behavior customers can expect from CenturyLink Cloud Operations in the case of a security incident. </p>
<h3>Audience</h3>
<ul>
  <li>CenturyLink Cloud Customers</li>
</ul>
<h3>"A server in CenturyLink Cloud's public cloud is being scanned"</h3>
<ol>
  <li>This is a very common situation and statistically, this will happen to any server exposed on the Internet at least once every 72 hours. The majority of these scans are throttled in order to avoid detection. As such this will not trigger
    any any alarm and therefore the CenturyLink Cloud Operations will not be aware of the attack.</li>
</ol>
<h3>"A server in CenturyLink Cloud's public cloud is being attacked"</h3>
<ol>
  <li>Low-volume attack: The majority of attacks are throttled in order to avoid detection and to leverage a server exploit. As such this will not trigger any any alarm and therefore the CenturyLink Cloud Operations will not be aware of the attack.</li>
  <li>High-volume attack (DDoS): &nbsp;These types of attacks are designed to overwhelm the capabilities of the server. If the volume of the attack is high enough, it will will be detected by the CenturyLink Cloud controls and as the CenturyLink Cloud Operations staff
    will initiate a Security incident. In the majority of cases, the #1 priority is to mitigate the attack and therefore it is possible that the mitigation might interrupt the operations of the server. e.g. black holing the server IP if it
    is being DDoS attacked. The CenturyLink Cloud Operations team will open a ticket with the server administrators defined in control.</li>
</ol>
<div>
  <h3>"Someone has filed an abuse complaint"</h3>
  <ol>
    <li>The CenturyLink Cloud Operations team will initiate a Security Incident and will open a ticket against the reported server. The account contacts in control will be notified of the ticket via email.</li>
    <li>CenturyLink Cloud is contractually bound to ensure that these complaints are investigated and therefore if the server owners do not investigate this report, in extreme cases, we are required to suspend the operation of the server. </li>
  </ol>
</div>
<div>
  <h3>"What does CenturyLink Cloud Operations team do in a Security Incident?"</h3>
  <ol>
    <li>1. The team will attempt to determine if the security reports is valid. If they have access to the devices in question, such as our cloud infrastructure or a customer Managed Services server, we will investigate it.</li>
    <li>If we do not have access to the server, the team will open a ticket in the CenturyLink Cloud ticketing system will all of the account administrators of that server on the ticket. The customer will be asked to investigate the issue.</li>
    <li>In extreme cases where the security&nbsp;incident&nbsp;is impacting other customers or Internet users, DDoS attack, the team will take steps to mitigate the&nbsp;situation.</li>
  </ol>
  
  
  
</div>
<div>&nbsp;</div>