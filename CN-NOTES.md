<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CN-NOTES</title>
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__html"><h1 id="computer-networking-notes">Computer Networking Notes</h1>
<h2 id="abstract">Abstract</h2>
<p>Hi, my name is Francisco Fraga and I’m currently pursuing an MSc. in Electrical Engineering at Porto University. Since I’ve been always very interested in Computer Networking and I’m currently studying towards my job interviews, I figured out that it was a good idea to write some notes based on several sources. These notes expect you to have former background on basic topics. The references:</p>
<ul>
<li><strong>Computer Networking: A Top - Down Approach.</strong> - <em>Jim Kurose and Keith Ross</em></li>
<li><strong>Computer Networks.</strong> - <em>Andrew S. Tanenbaum</em></li>
</ul>
<h2 id="what-is-the-internet">What is the Internet?</h2>
<blockquote>
<p>The Internet is a computer network that interconnects hundreds of millions of computing devices throughout the world.</p>
</blockquote>
<p>As a matter of fact:</p>
<blockquote>
<p>The Internet is not really a network at all, but a vast collection of different networks that use certain common protocols and provide certain common services. It is an unusual system in that it was not planned by anyone and is not controlled by anyone</p>
</blockquote>
<p>The devices from which we can access the Internet are called <strong>Hosts</strong> or <strong>End Systems</strong>, and their connection is assured by Internet Service Providers (ISPs), through a network of <strong>communication links</strong> and <strong>packet switches</strong>.</p>
<blockquote>
<p>The Internet is all about connecting end systems to each other, so the ISPs that provide access to end systems must also be interconnected.</p>
</blockquote>
<p>As you may know there are several types of <strong>communication links</strong>, which can provide connection by different mediums. Some examples are:</p>
<ul>
<li>Optical fiber.</li>
<li>Coaxial cable.</li>
<li>Wireless communication channels.</li>
<li>Copper wire.</li>
</ul>
<p>All those links have different characteristics and provide distinct flavours when it comes to data transmission rates (bits/second).</p>
<p>Introducing packets:</p>
<blockquote>
<p>When one end system has data to send to another end system, the sending end system segments the data and adds header bytes to each segment. The resulting packages of information, known as <strong>packets</strong> in the jargon of computer networks, are then sent through the network to the destination end system, where they are reassembled into the original data.</p>
</blockquote>
<p>A <strong>packet switch</strong> is responsible for forwarding packets towards the direction of its ultimate destination. In addition, those packets arrive and are forwarded by means of incoming/outgoing  communication links. The two most common <strong>packet switches</strong> are link-layer switches (mainly used in access networks) and routers (typically used in the network core).</p>
<blockquote>
<p>The sequence of communication links and packet switches traversed by a packet from the sending end system to the receiving end system is known as a route or path through the network.</p>
</blockquote>
</div>
</body>

</html>
