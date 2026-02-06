# AI Agent for Software License Analysis - Frontend

A simple, professional frontend interface that integrates with your DO agent for automated software license analysis and compliance assessment.

## Features

- **Document Upload**: Drag & drop or click to upload license documents (PDF, DOC, DOCX, TXT)
- **AI-Powered Analysis**: Integrated with DO agent for automated license review
- **Interactive Chatbot**: Direct communication with the AI agent for questions and clarifications
- **Professional UI**: Clean, responsive design matching your brand colors
- **User Role Support**: Interface designed for Legal, Procurement, Compliance, and other stakeholders

## File Structure

```
contract-ai-agent/
├── index.html          # Main HTML structure
├── styles.css          # Professional styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## DO Agent Integration

The frontend is pre-configured to work with your DO agent:

- **Agent Endpoint**: `
- **Agent ID**: `
- **Chatbot ID**: 

## Supported Document Types

### In Scope (v1.0)
- ✅ Commercial software licenses
- ✅ EULAs (End User License Agreements)
- ✅ MSAs (Master Service Agreements)
- ✅ SOWs (Statements of Work)
- ✅ DPAs/BAAs (Data Processing/Business Associate Agreements)
- ✅ Reseller/OEM agreements
- ✅ Partner/Channel agreements
- ✅ Terms & Conditions
- ✅ Open-Source Licenses (MIT, Apache-2.0, GPL, AGPL, LGPL, MPL)

### File Formats
- PDF (.pdf)
- Microsoft Word (.doc, .docx)
- Plain text (.txt)
- Maximum file size: 10MB per file

## User Roles & Permissions

The system is designed to support different user roles:

| Role | Permissions |
|------|-------------|
| **Reviewer** | View & annotate outputs, approve/reject clauses |
| **Editor** | Edit extracted terms, override flags, mark disposition |
| **Admin** | Configure policies/playbooks, manage models, data retention, audit |
| **Auditor** | Read-only logs, exports, evidence |

## Quick Start

1. **Open the Application**

   The agent is designed to run directly from the local file system. Simply open the HTML file in your browser:

   ```
   file:///Users/macuser1/Downloads/2.development/contract-ai-agent/index.html
   ```

   Or double-click on `index.html` in Finder to open it automatically in your default browser.

   **Alternative (if needed):**
   ```bash
   # You can also serve it using a local web server
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

2. **Upload License Documents**
   - Drag & drop files onto the upload area
   - Or click "Choose Files" to select documents
   - Multiple files can be uploaded simultaneously

3. **Start Analysis**
   - Click "Start Analysis" to send documents to the AI agent
   - The chatbot will provide detailed analysis results
   - Ask follow-up questions using the chatbot interface

## How It Works

1. **Document Upload**: Users upload license documents through the intuitive interface
2. **AI Processing**: Files are sent to the DO agent for automated analysis
3. **Results & Interaction**: The AI agent provides detailed analysis through the integrated chatbot
4. **Decision Support**: Users can ask questions and get recommendations for approval/rejection

## Key Analysis Features

The AI agent automatically extracts and analyzes:

- 📋 **Key Legal Terms**: Contract duration, termination clauses, liability limits
- ⚖️ **Compliance Assessment**: Risk evaluation against internal policies
- 🔍 **License Type Identification**: Categorization of license models
- ⚠️ **Critical Clauses**: Important obligations and restrictions
- ✅ **Recommendations**: Approval/rejection guidance with reasoning

## Browser Compatibility

- Chrome/Chromium 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## Security Features

- Client-side file validation
- Secure communication with DO agent
- No file storage on frontend
- HTTPS-only connections

## Troubleshooting

### Chatbot Not Loading
- Check your internet connection
- Ensure the DO agent endpoint is accessible
- Refresh the page and wait for the widget to load

### File Upload Issues
- Verify file format is supported (PDF, DOC, DOCX, TXT)
- Check file size is under 10MB
- Ensure browser supports File API

### Analysis Not Starting
- Make sure at least one file is uploaded
- Check browser console for error messages
- Try refreshing the page and uploading again

## Development

### Access Methods

**Primary Method (Recommended):**
```
Direct file access: file:///Users/macuser1/Downloads/2.development/contract-ai-agent/index.html
```

**Alternative - Local Development Server (if needed):**
```bash
# Using Python
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

### Customization

The frontend can be easily customized:

- **Colors**: Modify CSS variables in `styles.css`
- **Branding**: Update logos and text in `index.html`
- **Functionality**: Extend JavaScript in `script.js`

## Support

For issues or questions:
- Check the browser console for error messages
- Verify the DO agent endpoint is accessible
- Ensure all files are in the correct format

## License

This frontend interface is provided as-is for integration with your DO agent for software license analysis.
