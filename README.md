<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

<ol>
 <summary>Create Network Security Groups (NSGs):</summary>
  <details>
    <ul>
      <li>In the Azure portal, navigate to the "Networking" section of your virtual machine.</li>
      <li>Under "Settings," select "Network Security Group."</li>
      <li>Create a new NSG or use an existing one. Assign the NSG to the target VMs by associating it with their network interfaces.</li>
    </ul>
  </details>
 <summary>Define Inbound and Outbound Security Rules:</summary>
   <details>
    <ul>
      <li>Within the NSG configuration, define inbound and outbound security rules to allow or deny traffic between the VMs.</li>
      <li>Specify source and destination IP addresses, ports, and protocols for each rule.</li>   
      <li>Rules are processed in a priority order, so ensure rules are in the correct sequence.</li>
    </ul>
   </details>
<summary>Inspect and Monitor Traffic:</summary>
  <details>
    <ul>
      <li>Use Azure Monitor or Azure Security Center to monitor and inspect network traffic between your virtual machines.</li>
      <li>Set up log analytics and configure security alerts for NSG rule violations or suspicious network activity.</li>
      <li>Review network flow logs to gain visibility into the traffic patterns and troubleshoot any issues.</li>
    </ul>
  </details>
  <summary>Testing and Optimization:</summary>
  <details>
    <ul>
      <li>After configuring NSG rules, perform testing to ensure that the desired traffic is allowed, and unwanted traffic is blocked.</li>
      <li>Regularly review and update NSG rules to adapt to changing security requirements and application needs.</li>
      <li>Use Azure Network Watcher tools and diagnostic logs to troubleshoot and optimize your NSG configurations.</li>
    </ul>
  </details>
  </ol>

<h2>Actions and Observations</h2>

<em>Currently under contruction</em>
<p>
<img src="#"/>
</p>
<p>

</p>
<br />

<p>
<img src="#"/>
</p>
<p>

</p>
<br />

<p>
<img src="#"/>
</p>
<p>

</p>
<br />
