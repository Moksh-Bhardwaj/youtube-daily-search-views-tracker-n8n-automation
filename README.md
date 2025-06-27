# 📊 YouTube Daily Search Views Tracker Automation (n8n Workflow)

This n8n automation tracks the number of daily YouTube views generated from **YouTube Search** for your channel, using the YouTube Analytics API, and updates them into a connected Google Sheet.

---

## 🔧 Features

- Automatically runs daily at 12 PM
- Fetches views from YouTube Search (using `insightTrafficSourceType`)
- Writes data into the correct cell in a Google Sheet based on date
- Easy to modify and extend for other traffic sources

---

## ✅ Prerequisites

- A [YouTube channel](https://studio.youtube.com/)
- [n8n](https://n8n.io/) installed (locally or on cloud)
- Google OAuth2 credentials for:
  - YouTube Analytics API
  - Google Sheets API

---

## 📂 Setup Instructions

1. **Clone this repository**
2. **Import `workflow.json` into your n8n instance**
3. **Connect your own credentials**:
   - When creating the Google credentials connection inside n8n, make sure to authorize with the following scope for YouTube Analytics:
`https://www.googleapis.com/auth/yt-analytics.readonly`
   - Replace the Google credentials under:
     - `Fetch YT Analytics`
     - `Update Google Sheet`
4. **Update the Google Sheets URL** in the workflow with your actual spreadsheet
5. (Optional) Modify the trigger time, sheet range, or logic to suit your needs

---

## 🖼️ Workflow Preview

![Workflow Screenshot](https://github.com/Moksh-Bhardwaj/youtube-daily-search-views-tracker-n8n-automation/blob/main/assets/youtube-search-views-automation-workflow-screenshot.png)

## 🖼️ Google Sheet Preview

![Google Sheet Screenshot](https://github.com/Moksh-Bhardwaj/youtube-daily-search-views-tracker-n8n-automation/blob/main/assets/youtube-seo-dashboard-daily-search-views-tab-screenshot.png)

_You can copy the Google Sheet from here for testing purpose: [YouTube SEO Dashboard Sheet](https://docs.google.com/spreadsheets/d/1dCeNcuXSxSi2Yng9H5h4TvmI92MZCFv0h9i9wHtco4g/)_

---

## 📝 License

- **Code**: [MIT License](https://github.com/Moksh-Bhardwaj/youtube-daily-search-views-tracker-n8n-automation/blob/main/LICENSE)
- **Screenshots & Docs**: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — Attribution required  
  Credit: **[Moksh Bhardwaj](https://superprofile.bio/mokshbhardwaj)**

---

## 🙌 Author

**Moksh Bhardwaj**  
🔗 [YouTube](https://www.youtube.com/@GreyMattersTech)<br/>
🔗 [Super Profile](https://superprofile.bio/mokshbhardwaj)<br/>
🔗 [GitHub](https://github.com/Moksh-Bhardwaj)

🎥 Watch the full tutorial on [YouTube](https://youtu.be/U8iFlqK28fc)

⭐ Star this repo if you find it useful and want more tech tutroials!

