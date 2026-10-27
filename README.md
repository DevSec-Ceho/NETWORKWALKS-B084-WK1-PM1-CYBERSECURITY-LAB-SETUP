# NETWORKWALKS-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP
Isolated virtual penetration testing and cybersecurity lab environment built with Kali Linux on Oracle VirtualBox using an internal NAT Network architecture.




<h1>Cybersecurity &amp; Penetration Testing Lab Setup</h1>

<h2>Project Overview</h2>

<p>
  As part of my cybersecurity learning journey, I have completed the initial setup of my cybersecurity lab using Oracle VirtualBox and Kali Linux. The purpose of this project was to create a virtual environment where I can practise cybersecurity concepts, become more familiar with security tools, and prepare for future penetration-testing projects.
</p>

<p>
  I configured Kali Linux as a virtual machine and connected it to a VirtualBox NAT Network. I also worked on network connectivity and documented the configuration and challenges I encountered during the setup.
</p>

<p>
  This project is the foundation for my future hands-on projects in offensive security, network reconnaissance, vulnerability assessment, and web application security testing.
</p>

<hr>

<h2>Project Objectives</h2>

<p>The objectives of this project were to:</p>

<ul>
  <li>Install and configure Oracle VirtualBox.</li>
  <li>Set up Kali Linux as a virtual machine.</li>
  <li>Configure a virtual network for cybersecurity practice.</li>
  <li>Understand IP addressing, network gateways, and DNS configuration.</li>
  <li>Troubleshoot network connectivity issues.</li>
  <li>Verify Internet connectivity from Kali Linux.</li>
  <li>Document the setup process and lessons learned.</li>
  <li>Prepare a virtual environment for future authorized penetration-testing exercises.</li>
</ul>

<hr>

<h2>Lab Configuration</h2>

<table>
  <thead>
    <tr>
      <th align="left">Component</th>
      <th align="left">Configuration</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Host Operating System</td>
      <td>Windows</td>
    </tr>
    <tr>
      <td>Virtualization Software</td>
      <td>Oracle VirtualBox</td>
    </tr>
    <tr>
      <td>Security Operating System</td>
      <td>Kali Linux</td>
    </tr>
    <tr>
      <td>Virtual Network Type</td>
      <td>NAT Network</td>
    </tr>
    <tr>
      <td>Network Addressing</td>
      <td>IPv4</td>
    </tr>
    <tr>
      <td>Internet Connectivity</td>
      <td>Working</td>
    </tr>
    <tr>
      <td>Lab Purpose</td>
      <td>Cybersecurity learning and authorized security testing</td>
    </tr>
  </tbody>
</table>

<hr>

<h2>Tools and Technologies Used</h2>

<ul>
  <li>Oracle VirtualBox</li>
  <li>Kali Linux</li>
  <li>Windows</li>
  <li>7-Zip</li>
  <li>Linux command line</li>
  <li>NetworkManager</li>
</ul>

<hr>

<h2>Lab Setup and Implementation</h2>

<h3>1. Installing the Required Software</h3>

<p>
  I installed the software required to create my virtual cybersecurity lab. This included Oracle VirtualBox for running virtual machines and 7-Zip for handling compressed files where necessary.
</p>

<p>
  I obtained Kali Linux from the official Kali Linux website and used it as the operating system for my cybersecurity lab.
</p>

<h3>2. Setting Up Kali Linux</h3>

<p>
  I imported and configured Kali Linux in VirtualBox. I reviewed the virtual machine settings and configured its network adapter to connect to the virtual network created for the lab.
</p>

<p>
  Using a virtual machine allows me to practise cybersecurity techniques in a dedicated environment without needing a separate physical computer for Kali Linux.
</p>
<img width="1920" height="1080" alt="Screenshot (301)" src="https://github.com/user-attachments/assets/b6f07477-d9db-44a5-82eb-221ae2441312" />

<h3>3. Configuring the Virtual Network</h3>

<p>
  I configured a NAT Network in VirtualBox for my lab environment.
</p>

<p>
  I chose this network mode because it can allow multiple virtual machines connected to the same NAT Network to communicate with one another while also providing outbound network connectivity.
</p>

<p>
  This configuration provides a foundation for adding other virtual machines in future projects, including intentionally vulnerable target machines for authorized security testing.
</p>
<img width="1920" height="1080" alt="Screenshot (300)" src="https://github.com/user-attachments/assets/c932c264-d09f-4636-b96d-8878a3b9a7f9" />

<h3>4. Configuring Network Connectivity</h3>

<p>
  During the setup, I worked on configuring the network settings of my Kali Linux virtual machine. The main challenge was setting up the NAT Network correctly so that Kali Linux could connect to the internet.
</p>

<p>
  Working through the configuration helped me understand the importance of checking virtual network settings and ensuring that the virtual machine is connected to the intended network.
</p>

<p>
  I was able to get Internet connectivity working in Kali Linux.
</p>

<h3>5. Verifying Network Settings</h3>

<p>
  After configuring the network, I used Linux command-line tools to inspect the network settings and active connections.
</p>

<p><strong>Checking network interfaces and IP addresses:</strong></p>

<pre><code>ip -br addr
ip -4 addr</code></pre>

<p><strong>Checking the routing table:</strong></p>

<pre><code>ip route</code></pre>

<p><strong>Checking active NetworkManager connections:</strong></p>

<pre><code>nmcli connection show --active</code></pre>

<p>
  These commands help me inspect the network interfaces, IP configuration, routing information, and active network connections of my Kali Linux virtual machine.
</p>

<hr>

<h2>Challenges Faced</h2>

<p>
  The main challenge I faced during this project was setting up the NAT Network in VirtualBox. I had to work through the network configuration to get my Kali Linux virtual machine connected to the internet.
</p>

<p>
  This experience helped me understand that configuring a virtual machine's network requires more than just installing the operating system. The virtual network settings must also be configured correctly for the machine to communicate as expected.
</p>

<p>
  Working through this challenge gave me practical experience troubleshooting virtual networking as part of building my cybersecurity lab.
</p>

<hr>

<h2>What I Learned</h2>

<p>
  This project helped me strengthen my understanding of virtual machines and basic network configuration.
</p>

<h3>1. Virtualization</h3>

<p>
  I learned how VirtualBox allows me to run Kali Linux as a virtual machine on my Windows computer.
</p>

<h3>2. Virtual Network Configuration</h3>

<p>
  I gained practical experience setting up a NAT Network and understanding how it can support communication between multiple virtual machines.
</p>

<h3>3. IP Addressing and Networking</h3>

<p>
  I improved my understanding of IPv4 addressing, network interfaces, gateways, and DNS configuration.
</p>

<h3>4. Network Troubleshooting</h3>

<p>
  I learned the importance of checking virtual network settings systematically when resolving connectivity issues.
</p>

<h3>5. Practical Cybersecurity Learning</h3>

<p>
  I established a foundation for future hands-on exercises involving reconnaissance, network scanning, vulnerability assessment, and other authorized security-testing activities.
</p>

<h3>6. Technical Documentation</h3>

<p>
  I learned the importance of documenting my setup, challenges, troubleshooting process, and results as part of building a cybersecurity portfolio.
</p>

<hr>

<h2>Security and Ethical Considerations</h2>

<p>
  I will use this laboratory for educational purposes and authorized security testing only.
</p>

<p>
  Any future scanning, vulnerability assessment, or exploitation exercises will be conducted against systems I own or systems for which I have explicit permission to test.
</p>

<p>
  I will also take care to configure vulnerable target machines appropriately so they are not unnecessarily exposed to external networks.
</p>

<hr>

<h2>Future Improvements</h2>

<p>With the initial lab setup completed, I plan to build on this foundation by:</p>

<ul>
  <li>Adding intentionally vulnerable target virtual machines.</li>
  <li>Practising network reconnaissance and port scanning within the lab.</li>
  <li>Learning vulnerability assessment techniques.</li>
  <li>Performing web application security exercises in authorized environments.</li>
  <li>Improving my technical documentation by recording commands, evidence, and findings.</li>
  <li>Creating a clean baseline snapshot of Kali Linux for recovery before future experiments.</li>
</ul>

<hr>

<h2>Conclusion</h2>

<p>
  Completing this project has given me a practical starting point for my cybersecurity and offensive-security learning journey.
</p>

<p>
  Beyond setting up Kali Linux, I gained experience with virtual networking and troubleshooting connectivity issues while preparing an environment for future security exercises.
</p>

<p>
  I understand that cybersecurity requires continuous learning, practical experimentation, and proper documentation. I look forward to building more projects on this foundation and improving my skills through consistent hands-on practice.
</p>

<hr>

<h2>References</h2>

<ul>
  <li>
    <a href="https://www.virtualbox.org/">Oracle VirtualBox</a>
  </li>
  <li>
    <a href="https://www.kali.org/get-kali/">Kali Linux</a>
  </li>
  <li>
    <a href="https://www.7-zip.org/download.html">7-Zip</a>
  </li>
</ul>

<hr>

<h2>Project Information</h2>

<p><strong>Author:</strong> Chijioke Henry Okoye</p>
<p><strong>Program:</strong> Cybersecurity at Networkwalks</p>
<p><strong>Week:</strong> 01</p>
<p><strong>Project:</strong> Cybersecurity &amp; Penetration Testing Lab Setup</p>
