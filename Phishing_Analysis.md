# Phishing Analysis Report

In Phishing, malicious actors deceive users into divulging sensitive information often by exploiting the trust in electronic communications- Instant messaging, SMS, Emails. Email phishing remains a prevalent form of phishing. Fortunately, preventing this attack can be as simple as knowing how to identify phishing emails.

In this report, I have analysed the contents of five(5) sample emails for phishing signs including suspicious links, malicious files, embedded sinister scripts, and IP address of the email server used.


## Email: [Email1](Becode\Phishing\Phishing Analysis\Emails\Email1.eml)
### Email header analysis:
Timestamp: `Monday 20 Mar 2023, 16:57:04`

From: `Paypal`
Sender Email: `service@paypal.be`
Reply-to Email: `none`
Impersonated brand: `Paypal`
Originating IP (Defanged): `66[.]211[.]170[.]87`
Domain of interest (Defanged): `Paypal[.]be`

### Email Body analysis:
Embedded malicious URL: `No`
Shortened URL: `hxxps[://]www[.]paypal[.]com/cgp/app-redirect?intent=3Dx=o_email_txn_details&amp;src=3DRT000016&amp;ref_id=3D2T886045U28581329&amp;u=rl_clicked_desc=3Dtxn-id-hyperlink&amp;v=3D1&amp;utm_source=3Dunp&amp;utm_m=edium=3Demail&amp;utm_campaign=3DRT000016&amp;utm_unptid=3Dda14b2e8-c737-11=ed-a0a9-3cecef6affec&amp;ppid=3DRT000016&amp;cnac=3DBEamprsta=3Dfr_FR%28f=r-BE%29&amp;cust=3D5U9WSHT7ZXC7C&ampunptid=3Dda14b2e8-c737-11ed-a0a9-3cece=f6affec&amp;calc=3D7c0b8b9b23d6b&ampunp_tpcid=3Demail-receipt-xclick-payme=nt&amp;page=3Dmain%3Aemail%3ART000016&amppgrp=3Dmain%3Aemail&amp;e=3Dcl&am=p;mchn=3Dem&amp;s=3Dci&amp;mail=3Dsys&ampappVersion=3D1.153.0&amp;xt=3D104=038%2C127632`

### Phishing Assessment:
Following detailed assessment, it has been determined that the analysed email above does not appear to be a phishing email. This is because the domain appears to be consistent. Oftentimes, phishing emails can be easily identified by sender's name and email address mismatch. However, in this case it appears to be from a legitimate domain. 

======================================================================

## Email: [Email2](Becode\Phishing\Phishing Analysis\Emails\Email2.eml)
### Email header analysis:
Timestamp: `Monday 12 Dec 2023, 09:56:36`

From: `noreply`
Sender Email: `stainless@midnightmagicevents.com`
Reply-to Email: `stainless@midnightmagicevents.com`
Impersonated brand: `Trust Wallet`
Originating IP (Defanged): `85[.]200[.]134[.]107`
Domain of interest (Defanged): `midnightmagicevents[.]com`

### Email Body analysis:
Embedded malicious URL: `Yes`
Shortened URL: `hxxps[://]climovil[.]com=/`

### Phishing Assessment:
Given the conducted analysis, it has been found that the there are indications that suggest the assessed email may be a phishing email. Largely for the following reasons:

1. Disparity in the sender's name and email address
2. The senders email address does not correspond to the impersonated brand's official email.
3. The sender's email domain  does not reflect that of an official brand such as `Trust Wallet`
4. There appears to be an element of urgency to persuade the target into action.
5. The email body contains a deceptive `Go to verification` button which contains a malicious link intended to obtain sensitive information upon engagement.

======================================================================

## Email: [Email3](Becode\Phishing\Phishing Analysis\Emails\Email3.eml)
### Email header analysis
- Timestamp: `Sunday 26 Mar 2023, 15:31:56`
- From: `Tinder`
- Sender Email: `gq@80-78-255-128.cloudvps.regruhosting.ru`
- Reply-to Email: `gq@80-78-255-128.cloudvps.regruhosting.ru`
- Impersonated brand: `Tinder`
- Originating IP (Defanged): `80[.]78[.]255[.]128`
- Domain of interest (Defanged): `80-78-255-128.cloudvps[.]regruhosting[.]ru`

### Email Body analysis
- Embedded malicious URL: `Yes`
- Shortened URL: `http[://]blog[.]tulingxueyuan[.]cn/contradictedqm[.]php?utm_campaign=tpdjuresn`

### Phishing Assessment
Following the assessment, the email analysed above may be a phishing email, mainly for the following reasons:

1. Sender details and email address mismatch
2. The senders email address does not correspond to the impersonated brand's official email.
3. The sender's email domain does not reflect that of an official brand such as `Tinder`
4. Appealing technique to persuade the target into action
5. The email body contains a deceptive `find out who` button which contains a malicious link intended to obtain sensitive information upon engagement.

### Security Analysis

Security analysis was carried out using [Phishtool](https://app.phishtool.com/)-a program used to detect phishing emails. 

It was found that the adversary intended to run a malware on the user device. This malware was deployed through shortened url link disguised as a `find out who` button. By interacting with the button, the webpage would download malicious payloads (viruses, malware, spyware) onto the target device. This is corroborated by the security report from different fvendors:

![alt text](images/image3.png)

======================================================================

## Email: [Email4](Becode\Phishing\Phishing Analysis\Emails\Email4.eml)
### Email header analysis
- Timestamp: `Friday 3 Mar 2023, 12:44:01`
- From: `Dr Dan Miller`
- Sender Email: `babakingsouthmichael@gmail.com`
- Reply-to Email: `imorourafiatou0@gmail.com`
- Impersonated brand: `United Nations`
- Originating IP (Defanged): `209[.]85[.]220[.]41`
- Domain of interest (Defanged): `gmail[.]com`

### Email Body analysis
- Embedded malicious URL: `No`

### Phishing Assessment
Following the assessment, the email analysed above may be a phishing email, mainly for the following reasons:

1. Sender name and email address mismatch
2. The senders email address does not correspond to the impersonated brand's official email.
3. The sender's email domain does not reflect that of an official brand such as `United Nation`
4. Urgency technique to persuade the recipient into action
5. Involves huge amount of money to entice target

### Security Analysis

Security analysis was carried out using [Phishtool](https://app.phishtool.com/)-a program used to detect phishing emails. 

No malware found in the email. 

======================================================================

## Email: [Email5](Becode\Phishing\Phishing Analysis\Emails\Email5.eml)
### Email header analysis
- Timestamp: `27 August 2022, 11:42:01`
- From: `Ariana`
- Sender Email: `newsmail@app9l.serenitepure.fr`
- Reply-to Email: `news@aichakandisha.com`
- Impersonated brand: `Dating App`
- Originating IP (Defanged): `51[.]83[.]34[.]109`
- Domain of interest (Defanged): `app9l[.]serenitepure[.]fr`

### Email Body analysis
- Embedded malicious URL: `yes`

- Shortened URL: `hxxp[://]secure-netcloud[.]com/?a=71&c=76&s1=dadaa&email=phishing@pot.org`

### Phishing Assessment
Following the assessment, the email analysed above may be a phishing email, mainly for the following reasons:

1. Sender name and email address mismatch
2. Disparity in sender email address and reply-to mail
3. Bogus dating group purportedly organised via private instant messaging application
4. Free services offer to illicit swift action

### Security Analysis

Security analysis was carried out using [Phishtool](https://app.phishtool.com/)-a program used to detect phishing emails. 

Malware content reported by some vendors.
![alt text](images/image5.png)

