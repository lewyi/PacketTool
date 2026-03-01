# PacketTool
<h2>Introduction</h2>
C# desktop application for <b>port scanning</b> , <b>Find Local Device and packet sniffing</b>, using <b>SharpPcap</b> , <b>PacketDotNet</b> , and <b>Nmap</b>.

<h2>Important!!!</h2>
<b>This project is primarily  for ACADEMIC LEARNING and TECHNICAL DEMONSTRATION.</b>

<h2>Dependencies</h2>
<ol>
  <li>.NET 9</li>
  <li>SharpPcap</li>
  <li>PacketDotNet</li>
  <li>Nmap</a>
    <ul>
        <li>Download link: https://nmap.org/download</li>
        <li>Nmap must be downloaded separately and placed inside the `Application` directory</li>
    </ul>
  </li>
</ol>

<h2>Features</h2>
<h3>Packet Sniffer</h3>
<img src="Pic/Screenshot 2026-03-01 160016.png">
<ul>
  <li>Capture network packets in real time</li>
  <li>Select and bind a <b>specific network interface</b></li>
  <li>Display parsed packet information using PacketDotNet</li>
</ul>

<h3>Lan Discovery</h3>
<img src="Pic/Screenshot 2026-03-01 160022.png">
<ul>
  <li>Discover all devices within Local Network</li>
  <li>List down device IP and MAC Address</li>
  <li>Interface-based scanning for accurate results</li>
</ul>

<h3>Port Scanner</h3>
<img src="Pic/Screenshot 2026-03-01 160026.png">
<ul>
  <li>Scan Port using Nmap</li>
  <li>Select a specific network interface</li>
  <li> Flexible port input format supported:
      <ul>
        <li>'1-3' represent as 1 to 3</li>
        <li>'1,3 represent as 1 and 3'</li>
        <li>'1-3,5-9'represent as 1 to 3 and 5 to 9</li>
      </ul>
  </li>
  <li>Not Recommend 1-65535 it will wasting time</li>
</ul>

<h3>Export Function</h3>
<ul>
  <li>All module support CSV export</li>
  <li>Suitable for future analysis and reporting</li>
</ul>

<h2>Disclaimer</h2>
<ul>
  <li><b>This project is developed for education and academic purpose only.</b></li>
  <li>Author is <b>not responsible for any misuse </b>of this software.</li>
  <li>Users are responsible for complying with local laws and regulations.</li>  
</ul>
