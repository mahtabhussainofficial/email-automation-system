<div align="center">

  <h1>📧 Email Automation System</h1>
  <p><b>A lightweight Python script to send automated emails with logging and CSV recipient management.</b></p>

  <!-- Badges -->
  <p>
    <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge" alt="License" />
    <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" alt="Status" />
  </p>

  ---

</div>

<h2>📌 Project Structure</h2>
<pre><code>├── README.md           # Project documentation
├── email_sender.py     # Main Python script for sending emails
├── recipients.csv      # Contact list of email recipients
└── email_delivery.log  # Output log file tracking sent/failed emails</code></pre>

<hr />

<h2>⚡ Key Features</h2>

<table>
  <tr>
    <th>File / Component</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><b><code>email_sender.py</code></b></td>
    <td>Main automation script jo SMTP Server ke zariya bulk emails bhejta hai.</td>
  </tr>
  <tr>
    <td><b><code>recipients.csv</code></b></td>
    <td>CSV file jisme tamaam recipients ke email addresses aur names stored hain.</td>
  </tr>
  <tr>
    <td><b><code>email_delivery.log</code></b></td>
    <td>Log file jo har delivery ka status (Success/Failure) record karti hai.</td>
  </tr>
</table>

<hr />

<h2>🚀 How to Run</h2>

<h3>1. Repository Clone Karein</h3>
<pre><code>git clone https://github.com/mahtabhussainofficial/EMAIL-AUTOMATION-SYSTEM.git
cd EMAIL-AUTOMATION-SYSTEM</code></pre>

<h3>2. Recipients List Update Karein</h3>
<p><b><code>recipients.csv</code></b> file kholein aur apne contacts add/update karein.</p>

<h3>3. Script Run Karein</h3>
<pre><code>python email_sender.py</code></pre>

<h3>4. Status Check Karein</h3>
<p>Execution ke baad <b><code>email_delivery.log</code></b> file khol kar delivery logs verify kar sakte hain.</p>

<hr />

<div align="center">
  <p>Developed with ❤️ by <a href="https://github.com/mahtabhussainofficial"><b>Mahtab Hussain</b></a></p>
</div>
