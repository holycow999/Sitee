<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Welcome to Customer Center</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f2f4f7;
      color: #fff;
    }
    header {
      background-color: #1e1f23;
      padding: 10px 20px;
      color: white;
      font-size: 14px;
    }
    header ul {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
    }
    header li {
      margin-right: 20px;
    }
    .container {
      padding: 40px 20px;
      color: #000;
    }
    h1 {
      font-size: 28px;
      margin-bottom: 10px;
    }
    .description {
      font-size: 16px;
      margin-bottom: 30px;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background-color: #002f5f;
      padding: 20px;
      border-radius: 8px;
      color: white;
    }
    .card.light {
      background-color: #009cde;
    }
    .card h3 {
      margin-top: 0;
      font-size: 18px;
    }
    .card p {
      font-size: 14px;
      margin: 10px 0;
    }
    .card button {
      background-color: #003b7a;
      color: white;
      border: none;
      padding: 8px 12px;
      font-size: 13px;
      border-radius: 4px;
      cursor: pointer;
    }
    .card.light button {
      background-color: #007ab8;
    }
    .footer {
      margin-top: 30px;
      font-size: 12px;
      color: #888;
      text-align: right;
    }
  </style>
</head>
<body>

  <header>
    <ul>
      <li>DASHBOARD</li>
      <li>TOOLS</li>
      <li>REPORTS</li>
      <li>SETTINGS</li>
      <li>HELP</li>
    </ul>
  </header>

  <div class="container">
    <h1>Welcome to Customer Center</h1>
    <div class="description">
      The Customer Center gives you access to tools and services — making it easy to manage subscriptions, alerts, and more.
    </div>

    <div class="grid">
      <div class="card">
        <h3>Set up alerts</h3>
        <p>Stay informed. Get notifications via email or mobile about updates or changes important to you.</p>
        <button>SET UP ALERTS</button>
      </div>

      <div class="card">
        <h3>Manage your subscriptions</h3>
        <p>Adjust your subscriptions for updates, news, technical information, and other useful resources.</p>
        <button>MANAGE SUBSCRIPTIONS</button>
      </div>

      <div class="card light">
        <h3>Knowledge Center</h3>
        <p>Access self-service tools and request forms via the <a href="#" style="color: #fff; text-decoration: underline;">Resource Portal</a>.</p>
        <p>Start by completing the agreement. Contact us at <a href="#" style="color: #fff; text-decoration: underline;">support@example.com</a> for a copy.</p>
        <p>Check the <a href="#" style="color: #fff; text-decoration: underline;">help section</a> for guidance on how to use the portal.</p>
      </div>

      <div class="card light">
        <h3>How are we doing?</h3>
        <p>Your opinion matters. Take a moment to let us know how we can improve your experience.</p>
        <button>GIVE FEEDBACK</button>
      </div>

      <div class="card">
        <h3>Contact us</h3>
        <p>Have questions about your account? Reach out to our support team for help with login or access issues.</p>
        <p>USA: +1 123 456 7890<br/>
           Europe: +44 1234 567890<br/>
           Asia: +65 1234 5678<br/>
           support@example.com
        </p>
      </div>
    </div>

    <div class="footer">
      Privacy Notice | Terms of Use
    </div>
  </div>

</body>
</html>
