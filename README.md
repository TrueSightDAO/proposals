# TrueSight DAO Proposals Repository

This repository contains all community proposals for the TrueSight DAO, managed through an automated proposal management system that enables transparent, democratic governance.

## 🎯 What This Repository Is

This is the **main proposals repository** where all community proposals are stored as GitHub pull requests. Each proposal goes through a structured voting process, and the results are automatically processed based on community votes.

## 🏗️ How The System Works

### 1. **Proposal Creation**
- Community members submit proposals through the **DApp interface**
- Proposals are automatically converted into GitHub pull requests
- Each PR contains the full proposal content and voting information

### 2. **Voting Process**
- DAO members vote on proposals using **digital signatures**
- Votes are posted as comments on the pull requests
- Real-time vote tabulation is maintained automatically

### 3. **Automatic Processing**
- After the voting period expires (7 days), proposals are automatically processed
- **Majority YES votes** → Pull request is **merged** (proposal approved)
- **Majority NO votes** → Pull request is **closed** (proposal rejected)
- **Insufficient votes** → Proposal remains open for extended discussion

## 🌐 DApp Interface

The proposal management system is accessible through our web interface:

### **Main DApp**: [https://truesightdao.github.io/dapp/](https://truesightdao.github.io/dapp/)

### Key Pages:
- **📝 Create Proposal**: [https://truesightdao.github.io/dapp/create_proposal.html](https://truesightdao.github.io/dapp/create_proposal.html)
- **🗳️ Review & Vote**: [https://truesightdao.github.io/dapp/review_proposal.html](https://truesightdao.github.io/dapp/review_proposal.html)
- **📋 View All Proposals**: [https://truesightdao.github.io/dapp/view_open_proposals.html](https://truesightdao.github.io/dapp/view_open_proposals.html)
- **🔐 Create Digital Signature**: [https://truesightdao.github.io/dapp/create_signature.html](https://truesightdao.github.io/dapp/create_signature.html)
- **✅ Verify Requests**: [https://truesightdao.github.io/dapp/verify_request.html](https://truesightdao.github.io/dapp/verify_request.html)

### 🎬 **See It In Action**
Click any of the links above to see the live system! The DApp is fully functional and you can:
- Browse existing proposals
- See real-time vote counts
- Experience the user interface
- Understand the complete workflow

## 📊 Data Tracking

### Google Sheets Integration
All proposal submissions and votes are tracked in our main spreadsheet:
- **Telegram Chat Logs**: [https://docs.google.com/spreadsheets/d/1qbZZhf-_7xzmDTriaJVWj6OZshyQsFkdsAV8-pyzASQ](https://docs.google.com/spreadsheets/d/1qbZZhf-_7xzmDTriaJVWj6OZshyQsFkdsAV8-pyzASQ)
- **Proposal Submissions Sheet**: Tracks all processed proposals and their status

### 📊 **Live Data Tracking**
Click the Google Sheets link above to see:
- Real-time proposal submissions
- Vote tracking and status updates
- Complete audit trail of all activities

### Data Flow
```
User Submission → DApp → Digital Signature → Google Sheets → GitHub PR → Community Voting → Automatic Processing
```

## 🔧 Technical Implementation

### Backend System
The automated processing is handled by Google Apps Script:
- **Source Code**: [https://github.com/TrueSightDAO/tokenomics/blob/main/google_app_scripts/tdg_proposal/proposal_manager.gs](https://github.com/TrueSightDAO/tokenomics/blob/main/google_app_scripts/tdg_proposal/proposal_manager.gs)
- **Repository**: [https://github.com/TrueSightDAO/tokenomics/tree/main/google_app_scripts/tdg_proposal](https://github.com/TrueSightDAO/tokenomics/tree/main/google_app_scripts/tdg_proposal)

### 🔧 **Technical Implementation**
Click the repository link above to see:
- Complete Google Apps Script source code
- Automated processing logic
- Test functions and examples
- Configuration documentation

### Key Features
- **Automated PR Creation**: Proposals become GitHub PRs automatically
- **Real-time Vote Tabulation**: Live vote counting and display
- **Daily Auto-Processing**: Expired proposals are processed automatically
- **Digital Signature Verification**: Secure voting authentication
- **Email Notifications**: Optional reports for administrators

## 📁 Repository Structure

```
proposals/
├── README.md                    # This documentation
├── [Proposal Files]            # Individual proposal markdown files
└── [Pull Request Branches]     # Branches for each proposal
```

### Proposal File Format
Each proposal is stored as a markdown file with:
- **Title**: Clear, descriptive proposal title
- **Content**: Detailed proposal description
- **Metadata**: Creation date, author, voting information

## 🗳️ How To Participate

### For Community Members

1. **Create Digital Signature**
   - Visit: [https://truesightdao.github.io/dapp/create_signature.html](https://truesightdao.github.io/dapp/create_signature.html)
   - Generate your unique digital signature for voting

2. **Submit a Proposal**
   - Visit: [https://truesightdao.github.io/dapp/create_proposal.html](https://truesightdao.github.io/dapp/create_proposal.html)
   - Fill out the proposal form with title and detailed content
   - Submit with your digital signature

3. **Vote on Proposals**
   - Visit: [https://truesightdao.github.io/dapp/view_open_proposals.html](https://truesightdao.github.io/dapp/view_open_proposals.html)
   - Browse open proposals
   - Click on a proposal to review and vote
   - Submit your YES/NO vote with reasoning

4. **Track Results**
   - Monitor voting progress in real-time
   - View final results after voting closes
   - Check proposal status in the DApp interface

### For Developers

1. **View Source Code**
   - **DApp Frontend**: [https://github.com/TrueSightDAO/dapp](https://github.com/TrueSightDAO/dapp)
   - **Backend Scripts**: [https://github.com/TrueSightDAO/tokenomics/tree/main/google_app_scripts/tdg_proposal](https://github.com/TrueSightDAO/tokenomics/tree/main/google_app_scripts/tdg_proposal)

2. **Understand the System**
   - Read the technical documentation in the backend repository
   - Review the Google Apps Script implementation
   - Check the test functions for examples

## 🔍 Understanding Pull Requests

### Open Pull Requests
- **Active Proposals**: Currently open for community voting
- **Voting Period**: 7 days from creation (configurable)
- **Vote Counts**: Displayed in real-time in the DApp

### Closed Pull Requests
- **Approved Proposals**: Merged after majority YES votes
- **Rejected Proposals**: Closed after majority NO votes
- **Insufficient Votes**: Closed after extended period

### PR Comments
- **Vote Submissions**: Each vote appears as a comment
- **Voting Tabulation**: Automated vote counting comments
- **Final Summary**: Results posted when voting closes

## 📈 Monitoring and Transparency

### Real-time Updates
- **Vote Counts**: Updated immediately when votes are submitted
- **Status Changes**: Proposals move through states automatically
- **Notifications**: Email alerts for administrators (optional)

### Audit Trail
- **Complete History**: All votes and changes are tracked
- **Digital Signatures**: Every action is cryptographically signed
- **Google Sheets**: Full audit trail maintained
- **GitHub History**: Complete proposal and voting history

## 🚀 Getting Started

### For New Users
1. **Read this README** to understand the system
2. **Create a digital signature** using the DApp
3. **Browse existing proposals** to see examples
4. **Submit your first proposal** or vote on existing ones

### For Contributors
1. **Review the technical documentation** in the backend repository
2. **Test the system** using provided test functions
3. **Understand the data flow** from DApp to GitHub
4. **Monitor the automated processing** and logs

## 🔐 Security and Trust

### Digital Signatures
- **Unique Identity**: Each member has a unique digital signature
- **Vote Integrity**: Votes cannot be forged or duplicated
- **Audit Trail**: All actions are cryptographically verified

### Transparency
- **Open Source**: All code is publicly available
- **Public Voting**: All votes are visible on GitHub
- **Automated Processing**: No human intervention in vote counting
- **Complete History**: Full audit trail maintained

## 📞 Support and Resources

### Documentation
- **Main Tokenomics Repository**: [https://github.com/TrueSightDAO/tokenomics](https://github.com/TrueSightDAO/tokenomics)
- **DApp Repository**: [https://github.com/TrueSightDAO/dapp](https://github.com/TrueSightDAO/dapp)
- **Backend Documentation**: See `/tdg_proposal/README.md` in tokenomics repository

### Getting Help
1. **Check the DApp interface** for current proposal status
2. **Review GitHub PR comments** for voting information
3. **Check Google Sheets** for submission tracking
4. **Review logs** in the Google Apps Script system

## 🎉 Key Benefits

✅ **Transparent Governance** - All proposals and votes are publicly visible  
✅ **Automated Processing** - No manual intervention required  
✅ **Secure Voting** - Digital signature verification prevents fraud  
✅ **Real-time Updates** - Live vote counting and status updates  
✅ **Complete Audit Trail** - Full history of all actions  
✅ **User-Friendly Interface** - Easy-to-use DApp for all operations  
✅ **Mobile Responsive** - Works on all devices  
✅ **Open Source** - Fully transparent and auditable system  

---

## 📋 Current Status

- **Active Proposals**: Check the [DApp interface](https://truesightdao.github.io/dapp/view_open_proposals.html) for current open proposals
- **Recent Activity**: View recent pull requests in this repository
- **System Status**: All systems operational and processing proposals automatically

## 🚀 **Quick Start - See It Now!**

**Want to see the system in action immediately?** Click these links:

1. **[View All Open Proposals](https://truesightdao.github.io/dapp/view_open_proposals.html)** - See current proposals and vote counts
2. **[Create a Test Proposal](https://truesightdao.github.io/dapp/create_proposal.html)** - Try the proposal creation interface
3. **[Check Live Data](https://docs.google.com/spreadsheets/d/1qbZZhf-_7xzmDTriaJVWj6OZshyQsFkdsAV8-pyzASQ)** - View real-time tracking in Google Sheets
4. **[Browse Source Code](https://github.com/TrueSightDAO/dapp)** - See how the frontend works
5. **[Review Backend Logic](https://github.com/TrueSightDAO/tokenomics/tree/main/google_app_scripts/tdg_proposal)** - Understand the automation

---

*This repository is part of the TrueSight DAO governance infrastructure. All proposals are processed through our automated, transparent, and secure voting system.*