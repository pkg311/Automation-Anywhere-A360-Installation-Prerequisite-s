<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">


</head>
<body>

<div class="container">
  <h1>Network Details</h1>
  <table>
    <thead>
      <tr>
        <th>URL</th>
        <th>PORT</th>
        <th>DEVICE</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>www.automationanywhere.com</td>
        <td>TCP 443 (HTTPS)</td>
        <td>All devices</td>
      </tr>
      <tr>
        <td>https://aai-artifacts.my.automationanywhere.digital</td>
        <td>TCP 443 (HTTPS)</td>
        <td>All Control Room nodes</td>
      </tr>
      <tr>
        <td>apeople.automationanywhere.com</td>
        <td>TCP 443 (HTTPS)</td>
        <td>All devices</td>
      </tr>
      <tr>
        <td>docs.automationanywhere.com</td>
        <td>TCP 443 (HTTPS)</td>
        <td>All devices</td>
      </tr>
      <tr>
        <td>license.automationanywhere.digital (192.124.249.160)</td>
        <td>TCP 443 (HTTPS)</td>
        <td>All devices that run Automation 360 Control Room</td>
      </tr>
      <tr>
        <td>botstore.automationanywhere.com</td>
        <td>TCP 443 (HTTPS)</td>
        <td>All devices</td>
      </tr>
      <tr>
        <td>cdn.pendo.io</td>
        <td>TCP 443 (HTTPS)</td>
        <td>All devices</td>
      </tr>
      <tr>
        <td>app.pendo.io/</td>
        <td>TCP 443 (HTTPS)</td>
        <td>All devices</td>
      </tr>
      <tr>
        <td>data.pendo.io/</td>
        <td>TCP 443 (HTTPS)</td>
        <td>All devices</td>
      </tr>
      <tr>
        <td>https://pendo-static-5673999629942784.storage.googleapis.com/</td>
        <td>TCP 443 (HTTPS)</td>
        <td>All devices</td>
      </tr>
      <tr>
        <td>https://chrome.google.com/webstore/detail/automation-360/kammdlphdfejlopponbapgpbgakimokm</td>
        <td>TCP 443 (HTTPS)</td>
        <td>Bot Creator and Bot Runner devices</td>
      </tr>
      <tr>
        <td>https://microsoftedge.microsoft.com/addons/detail/automation-360/dbmodiepejcigljbmeebedkmegndokbk</td>
        <td>TCP 443 (HTTPS)</td>
        <td>Bot Creator and Bot Runner devices</td>
      </tr>
      <tr>
        <td>https://addons.mozilla.org/en-US/firefox/addon/automation-360</td>
        <td>TCP 443 (HTTPS)</td>
        <td>Bot Creator and Bot Runner devices</td>
      </tr>
    </tbody>
  </table>
</div>
<div class="container">
</div><p>
  <b>Files and folders:</b><br/>
  For information on files and folders to add to the safe list and to the antivirus exception list, see these articles:
</p>
  
</div>
<div class="container">
  <h1>Whitelisted Items and Comments</h1>
  <table>
    <thead>
      <tr>
        <th>Items to be whitelisted</th>
        <th>Comments</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Add Automation 360 On-Premises DNS to trusted list</td>
        <td>URL's for on-prem</td>
      </tr>
      <tr>
        <td>Add Automation 360 Cloud DNS to trusted list</td>
        <td>URL's for cloud</td>
      </tr>
      <tr>
        <td>Ports, protocols, and firewall requirements</td>
        <td>Ports, Firewalls</td>
      </tr>
      <tr>
        <td>C:\ProgramData\AutomationAnywhere</td>
        <td>Directory for Globalcache and Logs</td>
      </tr>
      <tr>
        <td>C:\Program Files\Automation Anywhere\Bot Agent</td>
        <td>Bot agent installation directory</td>
      </tr>
      <tr>
        <td>C:\Users\<user.profile>\</td>
        <td>Third party libraries get extracted here (e.g: openjfx)</td>
      </tr>
      <tr>
        <td>C:\Windows\System32\Automation.CredentialProvider_v11.dll</td>
        <td>To perform Autologin</td>
      </tr>
      <tr>
        <td>C:\Users\<user.profile>\AppData\Local\AA</td>
        <td>For non-admin bot agent install</td>
      </tr>
      <tr>
        <td>C:\Windows\System32\config\systemprofile\AppData\Local\AutomationAnywhere</td>
        <td>For admin level bot agent install (storing public/private keys, localdb for bot agent)</td>
      </tr>
      <tr>
        <td>https://docs.citrix.com/en-us/xenapp-and-xendesktop/7-15-ltsr/install-configure/remote-pc-access.html</td>
        <td>To enable RDP on Citrix</td>
      </tr>
      <tr>
        <td>license.automationanywhere.digital</td>
        <td>For license verification/validation</td>
      </tr>
    </tbody>
  </table>
</div>

<div class="container">
  <h1>Antivirus Exclusions</h1>
  <h2>For Bot Agent Installed as Admin User:</h2>
  <h3>Folders (also whitelist all subfolders inside them):</h3>
  <ul>
    <li>C:\ProgramData\AutomationAnywhere</li>
    <li>C:\ProgramData\ABBYY</li>
    <li>C:\Program Files\ABBYY SDK</li>
    <li>C:\Program Files\Automation Anywhere</li>
    <li>C:\Windows\System32\config\systemprofile\AppData\Local\AutomationAnywhere</li>
    <li>%userprofile%\.openjfx</li>
    <li>%LOCALAPPDATA%\Temp\jna-xxxxx (where "xxxxx" could be any sequence)</li>
  </ul>
  <h3>Files:</h3>
  <ul>
    <li>C:\Program Files\Automation Anywhere\Bot Agent\jre\bin\java.exe</li>
    <li>C:\Program Files\Automation Anywhere\Bot Agent\jre\bin\javaw.exe</li>
    <li>C:\Program Files\Automation Anywhere\Bot Agent\wfreerdp.exe</li>
    <li>C:\Windows\System32\Windows.Media.Ocr.dll</li>
    <li>C:\Windows\System32\Automation.CredentialProvider_v11.dll</li>
  </ul>
  <p><strong>NOTE:</strong> Ensure the user intended to execute the bots are allowed to view, read and execute content in the entire Automation Anywhere folder chain. Preferably, grant "Full Control" permission to "Everyone" in all the Automation Anywhere folders and subfolders.</p>

  <h1>Firewall and Proxy URL's Exclusions</h1>
  <p>Until other indication, all of these exclusions must be applied for any Control Room type (On-Prem, Cloud, Cloud-Enabled):</p>
  <ul>
    <li>*.my.automationanywhere.digital*</li>
    <li>*.amazonaws.com</li>
    <li>*.cloudfront.net</li>
    <li>*.rpaworker.com*</li>
    <li>www.automationanywhere.com</li>
    <li>apeople.automationanywhere.com</li>
    <li>docs.automationanywhere.com</li>
    <li>botstore.automationanywhere.com</li>
    <li>cdn.pendo.io</li>
    <li>app.pendo.io/</li>
    <li>data.pendo.io/</li>
    <li>https://pendo-static-5673999629942784.storage.googleapis.com/</li>
    <li>https://chrome.google.com/webstore/detail/automation-360*</li>
    <li>https://microsoftedge.microsoft.com/addons/detail/automation-360*</li>
    <li>https://addons.mozilla.org/en-US/firefox/addon/automation-360</li>
    <li>JUST FOR ON-PREM: license.automationanywhere.digital</li>
    <li>JUST FOR ON-PREM: *.shibumi.com*</li>
    <li>JUST FOR CLOUD: Include the full Control Room URL.</li>
  </ul>
</div>
<div class="container">
  <h1>Firewall and Proxy Ports Exclusions</h1>
  <p>If your Control Room is Cloud or Cloud-Enabled, you only need to exclude ports 80, 443 and 22113. However, if your Control Room is On-Prem, please exclude all these ports: 22, 80, 88, 389, 443, 445, 587, 636, 1234, 1433, 3268, 3269, 3389, 4567-4571, 5672, 5678-5708, 5800-5900, 8080, 22113, 47100-47200, 47500-47600.</p>
</div>
</body>
</html>
