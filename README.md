# GRE University and Profile Building Course Shortlisting

An intelligent UiPath automation that helps students with university shortlisting based on GRE scores and finding relevant courses for skill development.

## 🎯 Features

### University Shortlisting
- Input-based university recommendations considering:
  - GRE Scores
  - GPA
  - Preferred Country
  - Desired Course
- Automated scraping of suitable universities
- Results exported to Excel
- Automated email delivery of recommendations

### Course Shortlisting
- Multi-platform course search across popular educational websites
- User-specified course topic input
- Automated scraping of top 10 relevant courses from each selected platform
- Detailed course information export to Excel
- Automated email delivery of course recommendations

## 🛠️ Technical Details

### Built With
- UiPath Studio
- Dependencies:
  - BalaReva.EasyExcel.Activities (29.1.2)
  - UiPath.Excel.Activities (2.12.0-preview)
  - UiPath.Form.Activities (1.8.0)
  - UiPath.Mail.Activities (1.13.1-preview)
  - UiPath.System.Activities (21.12.0-preview)
  - UiPath.UIAutomation.Activities (21.12.0-preview)
  - UiPath.WebAPI.Activities (1.9.3-preview)

### System Requirements
- UiPath Studio 21.10.4.0 or higher
- .NET Framework (Legacy)

## 🚀 Getting Started

1. **Setup**
   - Clone this repository
   - Open the project in UiPath Studio
   - Ensure all dependencies are properly installed

2. **Running the Automation**
   - Execute the Main.xaml workflow
   - Fill in the initial form with:
     - Name
     - Email ID
     - Select desired service (University Shortlisting or Course Shortlisting)

3. **For University Shortlisting**
   - Enter your GRE scores
   - Provide your GPA
   - Select preferred country
   - Choose desired courses
   - Wait for email with Excel sheet containing university recommendations

4. **For Course Shortlisting**
   - Select preferred educational websites
   - Enter desired course name/topic
   - Wait for email with Excel sheet containing curated course list

## 📋 Process Flow

1. Initial Form Input
2. Service Selection
3. Detailed Information Collection
4. Automated Web Scraping
5. Data Processing
6. Excel Report Generation
7. Email Delivery

## 📝 Notes

- The automation requires user interaction for initial input
- Internet connection is required for web scraping
- Email functionality must be configured properly
- Results are delivered via email in Excel format

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to check issues page if you want to contribute.
