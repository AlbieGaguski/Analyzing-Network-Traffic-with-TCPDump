<h1>Using TCPDump to capture and analyze network traffic</h1>

<h2>Description</h2>
This Project will use a virtual environment running Linux to demonstrate the purpose and application of well-renowned network analyzing tools TCPDump and Wireshark. TCPDump is a very important tool in a secure network and I believe it's imperative to be proficient in this regard.
<br />


<h2>Programs and Utilities Used</h2>

- <b>rhyme & Linux</b> 
- <b>TCPDump</b>
- <b>Wireshark</b> 

<h2>Environments Used </h2>

- <b>Virtual machine terminal running Linux</b> (21H2)

<h2>Lab Overview:</h2>

<p align="center">
  
After opening up a new terminal it is time to use TCPDump. the command 'sudo TCPDump' will immediately begin the capture of network traffic. This will happen indefinitely until we cancel the process by inputting 'ctrl + c'. In order to make this easier on us and for the sake of the demonstration, we can use the command '-c 10' to limit our capture to 10 packets. Also, to make it easier to read we can input '-#' to add numerical bullet points to each packet <br/>
<img src="https://i.imgur.com/F5tEd5q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/jvqq2FS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/VTgu1Kx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/egEGhE6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Alternatively, we can display the output in ASCII or Hexadecimal by doing '-#A' or '-#XX' respectively <br/>
<img src="https://i.imgur.com/wCtQPjy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Ud330be.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Ok, now that some of the basics are out of the way, let's capture the traffic of a website and write some shell scripts. By creating a new file in our tool (watchdog.sh) we can open an integrated terminal, make our script executable and run it. Our script will be put into use once we refresh the website and it will also make our script human readable in multiple formats! <br/>
<img src="https://i.imgur.com/FEp1SwF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/qEwYL3X.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
We can save our work and transfer it over to another utility called 'Wireshark' which will allow us to analyze further. Our captured packets (captured.pcap) are easily viewed by fields such as time, source, protocol and even many other fields such as bytes!  <br/>
<img src="https://i.imgur.com/3x0uRrU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

TCPDump and Wireshark are perfect teammates. With these tools we can capture any packets coming into or leaving our network and then analyze them. We can sort by any fields we would need to such as time, source, bytes and even limit it down to the seconds using certain commands! There is so much more to these tools that I will delve further into in my next lab and I hope you are as excited to see it as I am to show you. 
</p>
