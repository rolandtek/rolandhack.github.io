---
layout: page
title: Hall of Fame
permalink: /cves/
---

<style>
  body {
    background-color: #1e1e1e;
    color: #eaeaea;
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
  }

  h1 {
    color: #b5e853;
    font-size: 36px;
    margin-top: 40px;
    text-align: center;
  }

  h2 {
    color: #f4bf75;
    font-size: 28px;
    margin-top: 30px;
  }

  h3 {
    color: #63c0f5;
    font-size: 24px;
  }

  section {
    background-color: #333;
    padding: 15px;
    border-radius: 8px;
    margin-bottom: 20px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
  }

  .cve-description, .cve-impact {
    margin-bottom: 15px;
  }

  .cve-description {
    color: #eaeaea;
    font-size: 16px;
  }

  .cve-impact {
    color: #eaeaea;
    font-size: 16px;
    margin-left: 20px;
  }

  .cve-link {
    color: #63c0f5;
    text-decoration: none;
    font-weight: bold;
  }

  .cve-link:hover {
    text-decoration: underline;
  }

  .cve-card {
    background-color: #222;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
    margin-bottom: 30px;
  }

  .cve-title {
    color: #b5e853;
    font-size: 26px;
    font-weight: bold;
  }

  .cve-meta {
    color: #f4bf75;
    font-size: 14px;
    margin-bottom: 10px;
  }

  .cve-description, .cve-impact {
    margin-top: 10px;
  }
</style>

# CVEs by Roland Hack

---

<div class="cve-card">
  <div class="cve-title">CVE-2023-28364: Open Redirect in Brave Browser (Android & iOS)</div>
  <div class="cve-meta">Published: March 2023</div>

  <section class="cve-description">
    Versions of Brave Browser for Android and iOS prior to version 1.52.117 contained an open redirect vulnerability in the built-in QR scanner. When a user scanned a malicious QR code, the browser would automatically navigate to the scanned URL without displaying or confirming it. This allows attackers to craft malicious links that lead to phishing sites or allow unauthorized file downloads.
  </section>

  <section class="cve-impact">
    Impact:
    - Phishing or malicious redirects
    - Unauthorized file downloads
  </section>

  <a href="https://nvd.nist.gov/vuln/detail/CVE-2023-28364" class="cve-link" target="_blank">View on NVD</a>
</div>

---

<div class="cve-card">
  <div class="cve-title">CVE-2024-29151: Dependency Confusion in Rocket.Chat.Audit</div>
  <div class="cve-meta">Published: January 2024</div>

  <section class="cve-description">
    In Rocket.Chat.Audit version v0.2.0, a dependency confusion vulnerability was discovered. The requirements.txt file specifies a Python module named filecachetools, which is not available on PyPI (the official Python package repository). This allows an attacker to upload a malicious package with the same name, potentially leading to remote code execution (RCE) or data compromise during installation.
  </section>

  <section class="cve-impact">
    Impact:
    - Remote Code Execution (RCE)
  </section>

  <a href="https://nvd.nist.gov/vuln/detail/CVE-2024-29151" class="cve-link" target="_blank">View on NVD</a>
</div>

---

<div class="cve-card">
  <div class="cve-title">CVE-2024-XXXX: New Vulnerability on Brave iOS (Pending)</div>
  <div class="cve-meta">Published: Pending</div>

  <section class="cve-description">
    A new vulnerability has been identified in Brave Browser for iOS. Details are currently under investigation, and the CVE ID has not yet been assigned. This vulnerability has not been publicly disclosed but could potentially affect the security of Brave Browser on iOS devices.
  </section>

  <section class="cve-impact">
    Impact:
    - Details pending
  </section>

  <a href="#" class="cve-link" target="_blank">View on NVD</a>
</div>
