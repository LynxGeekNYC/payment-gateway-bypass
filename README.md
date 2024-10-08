# payment-gateway-bypass
Simple script that validates payment through a payment gateway even though the payment never went through. Basically fool a website that a payment has been made.
<br>
# How it Works
Request Interception
During the transaction process, it is crucial to monitor the data being exchanged between the client and the server. This can be done by intercepting all requests. Within these requests, look out for parameters with significant implications, such as:

Success: This parameter often indicates the status of the transaction.
Referrer: It might point to the source from where the request originated.
Callback: This is typically used for redirecting the user after a transaction is completed.

URL Analysis
If you encounter a parameter that contains a URL, especially one following the pattern example.com/payment/MD5HASH, it requires closer examination. Here's a step-by-step approach:

Copy the URL: Extract the URL from the parameter value.
New Window Inspection: Open the copied URL in a new browser window. This action is critical for understanding the transaction's outcome.

Parameter Manipulation
Change Parameter Values: Experiment by altering the values of parameters like Success, Referrer, or Callback. For instance, changing a parameter from false to true can sometimes reveal how the system handles these inputs.

Remove Parameters: Try removing certain parameters altogether to see how the system reacts. Some systems might have fallbacks or default behaviors when expected parameters are missing.

Cookie Tampering
Examine Cookies: Many websites store crucial information in cookies. Inspect these cookies for any data related to payment status or user authentication.
Modify Cookie Values: Alter the values stored in the cookies and observe how the website's response or behavior changes.

Session Hijacking
Session Tokens: If session tokens are used in the payment process, try capturing and manipulating them. This might give insights into session management vulnerabilities.

Response Tampering
Intercept Responses: Use tools to intercept and analyze the responses from the server. Look for any data that might indicate a successful transaction or reveal the next steps in the payment process.

Modify Responses: Attempt to modify the responses before they are processed by the browser or the application to simulate a successful transaction scenario.

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=lynxgeeknyc&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false&order=1" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=lynxgeeknyc&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false&order=2" height="150" alt="languages graph"  />
</div>

###

<div align="center">
  <img src="https://profile-counter.glitch.me/lynxgeeknyc/count.svg?"  />
</div>

###

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" height="40" alt="php logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="40" alt="mysql logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="40" alt="cplusplus logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" height="40" alt="c logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="40" alt="postgresql logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="40" alt="linux logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apache/apache-original.svg" height="40" alt="apache logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gcc/gcc-original.svg" height="40" alt="gcc logo"  />
</div>

###

<p align="center">Greetings!<br><br>I put a lot of work into some of these scripts. If you find them useful, please donate! The money goes towards me fighting scammers. Servers aren't cheap!<br><br>Donate Via CashApp or Venmo: $LynxGeekNYC<br>BitCoin: bc1q8sthd96c7chhq5kr3u80xrxs26jna9d8c0mjh7<br><br>Also Please be sure to Visit and Subscribe to my YouTube Channel: YouTube.COM/LynxNYC</p>

###
