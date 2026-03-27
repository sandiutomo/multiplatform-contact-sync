[![Google Apps Script](https://img.shields.io/badge/Google%20Apps%20Script-4285F4?style=flat&logo=google-apps-script&logoColor=white)](https://developers.google.com/apps-script)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)

# Google Sheets → Multi-Platform Contact Sync Tool

Turn your Google Sheet into a one-click contact uploader for marketing platforms like Braze, CRMs, and analytics tools. No backend. No dashboard hopping. Just upload directly from Sheets.

---

## What You Get

[![Braze](https://img.shields.io/badge/Braze-FF5A5F?style=flat&logo=braze&logoColor=white)](https://www.braze.com/)
[![MoEngage](https://img.shields.io/badge/MoEngage-5200FF?style=flat&logo=moengage&logoColor=white)](https://www.moengage.com/)
[![Infobip](https://img.shields.io/badge/Infobip-1E90FF?style=flat&logo=infobip&logoColor=white)](https://www.infobip.com/)
[![Gupshup](https://img.shields.io/badge/Gupshup-00A4E4?style=flat&logo=whatsapp&logoColor=white)](https://www.gupshup.io/)
[![Mixpanel](https://img.shields.io/badge/Mixpanel-7856FF?style=flat&logo=mixpanel&logoColor=white)](https://mixpanel.com/)
[![Segment](https://img.shields.io/badge/Segment-52BD95?style=flat&logo=segment&logoColor=white)](https://segment.com/)

> ⚠️ **WORK IN PROGRESS**: This project is currently under active development. Platform integrations are being developed progressively. Features and documentation may change. Use at your own discretion.

<table>
<tr>
<img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExaDIxMms2d2d1cXVjcG0ycmM2NmtqNWliYXBocWtzbXB5bWRlaXU2bSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/rDq5czmtfL35tFADts/giphy.gif" width="100%" />
<td width="60%">

| Feature | Benefit |
|---|---|
| **One-Click Uploads** | Sync contacts directly from Google Sheets custom menu |
| **Phone Normalization** | Automatic Indonesia phone number formatting (+62 E.164 format) |
| **Status Tracking** | Real-time upload status with timestamps |
| **Batch Processing** | Handle large datasets efficiently |
| **Connection Verification** | Pre-upload API connection testing |
| **Upload Statistics** | Visual progress bars and success/failure counts |

</td>
</tr>
</table>

---

## Quick Start

### Step 1: Set Up Google Sheets

1. Open your existing contact database
2. Ensure your sheet has the following columns:
   - `Name` or `Full Name`
   - `Phone` or `Mobile`
   - `Email`

### Step 2: Add Apps Script

1. In your Google Sheet, go to **Extensions** → **Apps Script**
2. Copy the entire script code and paste it into the editor
3. Click **Save** (💾 icon)
4. Name your project (e.g., "Contact Sync Tool")

### Step 3: Configure API Credentials

In the script editor, locate the configuration section and add your API keys:
```javascript
// Example configuration
const CONFIG = {
  PLATFORM_API_KEY: 'your-platform-api-key',
  PLATFORM_ENDPOINT: 'your-platform-endpoint',
  // ... add other platform credentials
};
```

### Step 4: Authorize the Script

1. Click **Run** → Select any function (e.g., `onOpen`)
2. Click **Review Permissions**
3. Choose your Google account
4. Click **Advanced** → **Go to [Project Name] (unsafe)**
5. Click **Allow**

### Step 5: Reload Your Sheet

Close and reopen your Google Sheet. You should see a new menu item called **"Contact Sync"** or similar.

---

## Next Steps

Want to dive deeper? Read **[TECHNICAL_README.md](TECHNICAL_README.md)**

---

## License

Free to use for personal learning, testing, and demo purposes. Attribution appreciated. See LICENSE file for details.

---

[![Sandi Utomo](https://img.shields.io/badge/Made%20by-Sandi%20Utomo%20😎-5A6AE8?style=flat-square&logo=github&logoColor=white)](https://github.com/sandiutomo)
[![Sandi Utomo](https://img.shields.io/badge/LinkedIn-Sandi%20Utomo-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sandiutomo/)