# probable-disco
Absolutely! Here’s a **clear, professional README** for your `probable-disco` project. I made it beginner-friendly, explains what it does, and includes instructions to run it.

---

# probable-disco

**Probable-Disco** is a safe and legal Python project that analyzes public Instagram posts for locations that users have voluntarily tagged. This tool uses the Instagram Graph API to fetch media from a user’s account and lists all publicly tagged locations.

> ⚠️ **Important:** This project does **not** track private information or anyone without their consent. It only uses public data from accounts that allow access through the Instagram Graph API.

---

## Features

* Fetches user ID from Instagram username.
* Retrieves recent media posts from the user.
* Extracts and displays any public location tags.
* Can be expanded into a map visualization or dashboard.

---

## Requirements

* Python 3.7+
* `requests` library
* Instagram Graph API access token

---

## Installation

1. Clone this repository:

```bash
git clone https://github.com/yourusername/probable-disco.git
cd probable-disco
```

2. Install required Python libraries:

```bash
pip install requests
```

3. Get an Instagram Graph API token:
   Follow the official guide here: [Instagram Graph API](https://developers.facebook.com/docs/instagram-api/)

4. Open `probable_disco.py` and replace:

```python
ACCESS_TOKEN = "YOUR_ACCESS_TOKEN"
USERNAME = "instagram_username_here"
```

with your own API token and the username of the account you want to analyze.

---

## Usage

Run the script using Python:

```bash
python probable_disco.py
```

Output example:

```
Public locations tagged by nasa:
- Kennedy Space Center Visitor Complex
- Jet Propulsion Laboratory
- Kennedy Space Center Press Site
```

---

## Notes

* Only public media with **location tags** will be listed.
* Respect users’ privacy; do not attempt to collect data from accounts without consent.
* You can expand this project by visualizing locations on a map using libraries like `folium` or `plotly`.

---

## License

This project is open-source and available under the MIT License.

---
