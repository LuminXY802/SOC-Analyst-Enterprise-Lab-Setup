<h1>SOC-Analyst-Enterprise-Lab-Setup</h1>
<p>This repo will hold my complete documentation of Why you may want to set this lab, How you might want to set it up, What you are setting it for, and it'll also show you my lessons learned from this project. I love setting up Virtual Machines (VMs) and Virtual Networks like these and soon I would like to do the same for when I have a home lab!</p>
<hr>
<h2>*This lab is currently under construction, currently working on getting the Wazuh dashboard installed and connected to Suricata for the IDS*</h2>

<p>
  <strong>Goals for this lab:</strong>
  <ol>
    <li>Setup Active Directory Domain Controller via Samba </li>
    <li>Setup DHCP via kea dhcp4 package</li>
    <li>Setup Security Information and Event Manager (SIEM), which will be Wazuh for this demonstration </li>
    <li>Setup Suricata for the Intrusion Detection System/Intrustion Prevention System (IDS/IPS) and for Network Security Monitoring (MSN) </li>
    <li>Establish an endpoint connection from either a Windows or Linux client (most likely going to be Windows 11, since that is most common for organizations) </li>
    <li>Establish a Kali box that will be on a separate network, mimicking an attacker for full breach like scenarios </li>
  </ol>
</p>
