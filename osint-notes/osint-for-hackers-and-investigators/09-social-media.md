# Social Media

## Facebook Sock Puppet Account

### Current Steps to Take
- Dummy email (gmail, yahoo, etc.)
- Have a profile, image, activity:
    - https://datafakegenerator.com/ - for creating fake biodata
    - https://thispersondoesnotexist.com/ - for creating fake profile picture
- Only use this for OSINT

### Facebook ID
- Every facebook account has a **unique identifier**.
- You can see it by using this website: https://smallseotools.com/find-facebook-id/
- Example:

![alt text](images/09-social-media/2026-07-25_13-46.png)

### Facebook Video Downloader
- **Access it here:** https://fdown.net/

<br>

## Twitter / X 

### Warning
Research studies and regulatory reports indicate that X (formerly Twitter) has experienced notable **increases in the presence and visibility of hate speech and unverified claims** since ownership changes in late 2022.

### Mind Map

![alt text](<images/09-social-media/2. ce8b2a80ba1111ec89b079d71d6922bf.map-1.png>)

### Search Tool
- is a **free OSINT utility that generates advanced X (Twitter) search queries** to find public information without requiring an account, enabling targeted filtering by location, keywords, and user history. 
- **Access it here:** https://www.aware-online.com/en/osint-tools/twitter-search-tool/

<br>

## Bypassing Youtube Login Requirement
Example:
- You can't view this video because you need to sign in and confirm your age: https://www.youtube.com/watch?v=aYsdfaDSdfs
- Delete the `watch?`. Then delete the `=` and replace it with `/`
- Final: https://www.youtube.com/v/aYsdfaDSdfs, then hit Enter to automatically download the video.

<br>

## Maigret
- is an advanced open-source intelligence (OSINT) tool **used to locate a person's online presence** across over 3,000 websites and social networks simultaneously **by using only their username**.
- Developed as a powerful Python-based fork of the popular Sherlock project, it automates the process of gathering a digital dossier from public platforms without requiring any API keys.

### Key Features
- **Massive Site Database:** Searches thousands of platforms, including X (Twitter), TikTok, Instagram, and Reddit.
- **Web Page Parsing:** Extracts metadata such as full names, gender, profile avatars, and locations directly from found account pages.
- **Recursive Searching:** Automatically utilizes newly discovered IDs or alternate names to launch deeper secondary searches.
- **Tor & I2P Support:** Capable of querying hidden services and deep-web forums safely.
- **Rich Reporting:** Generates structured dossiers in multiple formats, including HTML, PDF, JSON, and XMind maps.


### How Investigators Use It
- Unlike tools that merely check if a username is "taken," Maigret actively analyzes the returned pages to verify the presence of an active profile.
- Cybersecurity analysts, journalists, and forensic researchers utilize Maigret to track down bad actors, mapping an individual's digital footprint across geographic regions or platform categories by applying targeted search tags.

<br>

## Youtube Dataviewer
- One good web app is **MattW YouTube Metadata**
- Provides the exact upload timestamp (down to the second), absolute timezone tags, video thumbnail extractions, tag analyses, and localized geographic tags if provided by the uploader.
- **Access it here:** https://mattw.io/youtube-metadata/

<br>

## Profil3r
- is used to find a person's digital footprint across the internet. It searches for social media accounts, correlates email addresses, and checks for data breaches using a name or username.

### Core Functions
- **Social Media Search:** Looks up usernames or real names across popular websites and platforms like Twitter, Instagram, Facebook, and LinkedIn to find active profiles.
- **Email Correlation:** Generates and tests potential email addresses linked to the target person.
- **Data Breach Check:** Checks if the discovered email addresses have been compromised or leaked in public data breaches.
- **Report Generation:** Compiles the gathered information into a readable format, such as an HTML report.

<br>

## Bluesky
- is a decentralized microblogging social network built on the Authenticated Transfer (AT) Protocol.
- Its importance for Open Source Intelligence (OSINT) investigations lies in its open, unauthenticated architecture, permanent Decentralized Identifiers (DIDs), and public APIs that allow passive, **deep data extraction without requiring a logged-in user account**.

### Internect.info
- is a free, lightweight tool designed **to search and verify accounts, handles, and public profile metadata across the AT Protocol, including decentralized platforms like Bluesky**. It serves as an Open Source Intelligence (OSINT) utility for resolving DIDs, tracking handle changes, and inspecting public repository records. 

### OSoMeNet
- maps how information spreads and is shared across social platforms.
- The system pulls data using search APIs from Bluesky, Mastodon, TikTok, and OSoMe's historical archive.
- **Access it here:** https://osome.iu.edu/tools/osomenet/