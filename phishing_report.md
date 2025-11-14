From: Мicrosoft Support <support@mіcrosoft.com>
Subject: Urgent: Verify Your Account

Dear User,

We have detected unusual activity on your account. To avoid suspension, please verify your details immediately by clicking the link below:

http://secure-mіcrosoft-confirm.com/verify

Thank you,  
Microsoft Account Team


Header Analyzed
Email Subject: Urgent: Verify Your Account
Copy/Paste Warning
Copy/Pasting a header works for most people, but sometimes it can cause problems with things like DKIM Validation. For the best results, use our Email Deliverability tool
Delivery Information
Problem Icon DMARC Compliant (No DMARC Record Found)
Problem Icon SPF Alignment
Problem Icon SPF Authenticated
Problem Icon DKIM Alignment
Problem Icon DKIM Authenticated
Relay Information
Received Delay:	0 seconds

Hop	Delay	From	By	With	Time (UTC)	Blacklist
1	*	unknown 192.0.2.1		 	[]	Not blacklisted

Gmail & Yahoo are now requiring DMARC - Get yours setup with Delivery Center


SPF and DKIM Information
dmarc:xn--mcrosoft-thh.com   
Test	Result	
Status Problem	DMARC Record Published	No DMARC Record found	Information More Info
Reported by f.gtld-servers.net on 11/14/2025 at 8:40:47 AM (UTC 0), just for you.  Transcript
spf:xn--mcrosoft-thh.com:192.0.2.1   
Dkim Signature Error:
No DKIM-Signature header found - more info
Dkim Signature Error:
There must be at least one aligned DKIM-Signature for the message to be considered aligned. - more info
Headers Found
Header Name	Header Value
eturn-Path	<support@mіcrosoft.com>
Received-SPF	fail (example: domain of mіcrosoft.com does not designate 192.0.2.1 as permitted sender)
Authentication-Results	mail.example.com; dkim=fail header.d=mіcrosoft.com; dmarc=fail (p=reject dis=none) header.from=mіcrosoft.com
From	Мicrosoft Support <support@mіcrosoft.com>
To	user@example.com
Subject	Urgent: Verify Your Account
Date	Fri, 14 Nov 2025 11:59:00 +0530
Message-ID	<unique-message-id@secure-mіcrosoft-confirm.com>
MIME-Version	1.0
Content-Type	text/plain; charset=UTF-8
Content-Transfer-Encoding	7bit
Received Header
eturn-Path: <support@mіcrosoft.com>
Received: from unknown (HELO mail.secure-mіcrosoft-confirm.com) (192.0.2.1)
by mail.example.com with SMTP; Fri, 14 Nov 2025 12:30:00 +0000
Received-SPF: fail (example: domain of mіcrosoft.com does not designate 192.0.2.1 as permitted sender)
Authentication-Results: mail.example.com;
 dkim=fail header.d=mіcrosoft.com;
 dmarc=fail (p=reject dis=none) header.from=mіcrosoft.com
From: Мicrosoft Support <support@mіcrosoft.com>
To: user@example.com
Subject: Urgent: Verify Your Account
Date: Fri, 14 Nov 2025 11:59:00 +0530
Message-ID: <unique-message-id@secure-mіcrosoft-confirm.com>
MIME-Version: 1.0
Content-Type: text/plain; charset=UTF-8
Content-Transfer-Encoding: 7bit



## Phishing Indicators
- Sender email uses Cyrillic characters to mimic Microsoft domain.
- Suspicious link containing Unicode look-alike characters.
- Urgent tone requesting verification.
- Possible SPF and DKIM failures (analyzed via header tool).

## Tools Used
- Mailmodo Header Analyzer
- MxToolbox Header Analyzer
- Curl command to check URLs
- Python snippet to detect Unicode chars

## Conclusion
This phishing email employs Unicode homograph attacks to deceive users into trusting the sender and clicking malicious links. Users should verify sender authenticity and carefully inspect links before interacting.

