<h1>SOC-Analyst-Enterprise-Lab-Setup</h1>
<p>This repo will hold my complete documentation of Why you may want to set this lab, How you might want to set it up, What you are setting it for, and it'll also show you my lessons learned from this project. I love setting up Virtual Machines (VMs) and Virtual Networks like these and soon I would like to do the same for when I have a home lab!</p>
<hr>
<h2 stlye="color:yellow">This lab is currently under construction, currently everything is all setup and configured Now it's connecting the client and SIEM VM to the smb file share and producing an alert to make sure everything works properly. After those final steps, now I just need to push out chapter 1 of the documentation (installation, setup, and connection)</h2>

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
  <a href="https://docs.google.com/document/d/1R1A3IuKbX8T1tKsS1E_-OJ578eTofulLlBwLbM3EHxU/edit?usp=sharing">You can find my working DOCX for the lab here</a>
</p>
