<h4 align="center">⚠️ Attention: This repository is not completed, yet.</h4>

<div align="center">
<img src="./other_files/rahnama.png" height="200"><br><br>
<a href="https://github.com/AliAlmasi/rahnama"><img src="https://komarev.com/ghpvc/?username=alialmasi-rahnama&color=2c7862&style=flat-square&label=Visits"></a>
<a href="https://github.com/AliAlmasi/rahnama/stargazers"><img src="https://img.shields.io/github/stars/alialmasi/rahnama.svg?style=flat-square&label=Stars&maxAge=2592000&color=1b727d"></a>
<a href="https://github.com/AliAlmasi/rahnama"><img src="https://img.shields.io/github/license/alialmasi/rahnama.svg?style=flat-square&label=License&maxAge=2592000&color=155b64"></a>
<br>
<a href="https://github.com/AliAlmasi/rahnama/issues"><img src="https://img.shields.io/badge/Ask%20quesions%20in-Issues-146264.svg?style=flat-square"></a>
<a href="https://github.com/AliAlmasi/rahnama/graphs/commit-activity"><img src="https://img.shields.io/badge/Maintained%3F-yes-009458.svg?style=flat-square"></a>
<h1>râhnamâ <sup>(Persian for 'Guide')</sup></h1>
<h3>Simple guide to make your personal v2ray server</h3>
<h4>based on my personal server configurations</h4>
</div>
<h2>What's This?</h2>
<p>Recently, people's access to the Internet has been disrupted by the government, and many daily Internet tools such as Instagram and WhatsApp have been cut off.</p>
<p>This guide will help you to make a personal vless/trojan server using a <a href="https://github.com/MHSanaei/3x-ui/">fork (3x-ui)</a> of a popular xray web-panel called <code>x-ui</code> by <a href="https://github.com/vaxilu/x-ui">vaxilu</a>.</p>
<p>Every step on this guide has been checked and the results have been monitorred by myself with my personal server. Don't worry, I will also tell you what kind of server you need to buy and where you should buy it from =D.</p>
<h2>What kinda server should I buy?</h2>
<p>If you have access to payment methods <b>outside Iran</b>, then I recommend you to buy a CX21 (or CPX21) cloud server from <a href="https://www.hetzner.com/cloud#:~:text=5.18%20/%20mo-,CX21,-vCPU">Hetzner</a></p>
<p>Else, you can buy <b>Ubuntu-based</b> servers from <b>Any VPS provider inside Iran</b>.</p>
<p>The location of the servers should be in European countries (especially Germany and the Netherlands) to have the best speed and less delay to send information to Iran (to you).</p>
<h2>What should I do next?</h2>
<p>You need to Install an ssh client program, to connect to your server's shell and run commands on your server.<br>It is optional so you can install any ssh client you like, (there are also some people who don't use these softwares, they run the <code>ssh</code> command on their terminal).</p>
<p>But, I recommend you to use <a href="https://mobaxterm.mobatek.net/">MobaXterm</a>. It has good features such as password manager (so you don't have to enter password every time), session manager (saving sessions so you don't have to type ssh command every time) and some more helping features like graphical SFTP browser (also available in <em>soft98</em>).</p>
<h2>How does MobaXterm works?</h2>
<p>When you finished installing MobaXterm, you can add your server as an session. Detailed guide of will be on <a href="https://github.com/AliAlmasi/rahnama/wiki/MobaXterm">Wiki</a>.</p>
<h2>Ok, what's next?</h2>
<p>Now we're getting to the exciting parts. Next step is to install the 3x-ui panel on your server.</p>
<p>To do this, the developers of 3x-ui have already made an <code>install.sh</code> script, so youdon't have to install manually.<br>Only thing you need to do is to run this on your server's shell:</p><pre><code>bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)</code></pre>
<p>Finally, you should see this:</p>
<pre><code>Install/update finished! For security it's recommended to modify panel settings
Do you want to continue with the modification [y/n]? :</code></pre>
<p>This indicates that 3x-ui has installed successfully. Now you got to set the panel's settings.</p>
<ol>
<li>Enter 'y'.</li>
<li>Enter your desired login username.</li>
<li>Enter your desired login password.</li>
<li>Enter your desired port for panel.</li>
</ol>
<p>Now you should see something like this:</p>
<pre><code>Install/update finished! For security it's recommended to modify panel settings
Do you want to continue with the modification [y/n]? :y
Please set up your username:alialmasi
Your username will be:alialmasi
Please set up your password:rahnama
Your password will be:rahnama
Please set up the panel port:8520
Your panel port is:8520
Initializing, please wait...
set username and password success
Account name and password set successfully!
set port 8520 successPanel port set successfully!
Created symlink /etc/systemd/system/multi-user.target.wants/x-ui.service → /etc/systemd/system/x-ui.service.
x-ui v1.1.4 installation finished, it is running now...

x-ui control menu usages:</code></pre>
<p>Congrats, you have sucessfully installed and configured your 3x-ui panel.<br>Now go to <code>http://YOUR-IP:PORT</code> to see the panel.</p>
<<<<<<< HEAD
<h2>What about "exciting" parts?</h2>
<p>The full step-by-step guide is on the <a href="https://github.com/AliAlmasi/rahnama/wiki/">wiki</a><br>
You can ask your questions on the <a href="https://github.com/AliAlmasi/rahnama/issues">issues</a> section.<br><a href="https://github.com/AliAlmasi/rahnama/discussions">Discussions</a> section are available for you guys.</p>
<p>In the hope of a free Iran.</p>
=======
>>>>>>> e439474b1c43303bf29a6d15daa947909663cb5c
