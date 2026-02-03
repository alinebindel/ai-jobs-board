# AI Startups Job Board

A comprehensive job board featuring the top 50 AI application layer companies from the a16z AI Application Spending Report.

## Features

- 🔍 **Search functionality** - Search by company name or job title
- 📊 **Live statistics** - Track total companies and available jobs
- 🎨 **Modern UI** - Beautiful gradient design with smooth animations
- 📱 **Responsive** - Works seamlessly on desktop and mobile
- 🔗 **Direct links** - Quick access to company career pages
- ⚡ **Fast & lightweight** - Pure HTML, CSS, and JavaScript

## Companies Included

50 leading AI companies including:
- OpenAI (494 jobs)
- Anthropic (377+ jobs)
- Replit (56 jobs)
- Notion (50+ jobs)
- And 46 more...

## Usage

Simply open `index.html` in your browser to view the job board.

### Local Development

```bash
# Clone the repository
git clone <your-repo-url>

# Navigate to the directory
cd ai-jobs-board

# Open in browser
open index.html
```

## Data Source

Job listings sourced from company career pages based on:
**"The AI Application Spending Report: Where Startup Dollars Really Go"** by a16z (Andreessen Horowitz)

## Structure

```
ai-jobs-board/
├── index.html       # Main website file
├── jobs-data.js     # Job listings data
└── README.md        # This file
```

## Contributing

To add or update job listings:

1. Edit `jobs-data.js`
2. Add company data in the following format:

```javascript
{
    name: "Company Name",
    website: "https://company.com/careers",
    jobs: [
        "Job Title 1",
        "Job Title 2",
        // ... more jobs
    ]
}
```

## License

MIT License - Feel free to use and modify as needed.

## Last Updated

February 2026
