# UTM Link Changer

A web-based tool for modifying email HTML with custom UTM parameters for different partners. This tool specifically targets Workiz event links and allows you to generate partner-specific versions of your email campaigns.

## Features

- **Email HTML Preview**: Live preview of your email HTML content
- **UTM Parameter Management**: Customize utm_source, utm_medium, and utm_campaign
- **Partner Management**: Add multiple partners with unique utm_content values
- **Automatic Link Detection**: Automatically finds and modifies Workiz event links
- **Download Functionality**: Generate and download partner-specific HTML files
- **Responsive Design**: Works on both desktop and mobile devices

## How It Works

1. **Paste Email HTML**: Input your email HTML content to see a live preview
2. **Configure UTM Parameters**: Set your utm_source, utm_medium, and utm_campaign values
3. **Add Partners**: Specify partner names that will be used as utm_content values
4. **Generate Links**: The tool automatically detects Workiz event links and modifies them
5. **Download Results**: Get partner-specific HTML files ready for your email campaigns

## UTM Parameters

- **utm_source**: The source of the traffic (default: "affiliate")
- **utm_medium**: The marketing medium (default: "referral")
- **utm_campaign**: Automatically extracted from the event URL
- **utm_content**: Set to the partner name for each version

## Supported Link Format

The tool specifically targets Workiz event links in this format:
```
https://fsm.workiz.com/event/{event-name}
```

## Usage

1. Open `index.html` in your web browser
2. Paste your email HTML content
3. Configure UTM parameters as needed
4. Add partner names
5. Click download buttons to get modified HTML files

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge

## File Structure

```
utm-link-changer/
├── index.html          # Main application file
└── README.md          # This documentation
```

## License

This project is open source and available under the MIT License.
