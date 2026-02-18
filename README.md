# Grade Calculator

A beautiful, modern grade calculator web application for tracking your grades in Chemistry, Calculus & Vectors, and Physics.

## Features

- 📊 **Real-time Grade Calculation**: See your current grade and highest possible grade instantly
- 💾 **Local Storage**: All your data is saved automatically in your browser
- 🎨 **Beautiful UI**: Modern, gradient-based design with smooth animations
- 📱 **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- ✏️ **Easy Input**: Add and manage assessment items with a simple interface

## How to Use

1. Open `grade-calculator.html` in your web browser
2. For each subject, add items to the subcategories:
   - **Term Work (70%)**:
     - Tests and Quizzes (40%)
     - Assignments and Labs (30%)
   - **Summative (30%)**:
     - Lab Exam (10%)
     - Written Exam (20%)
3. Enter the item name, marks earned, and maximum marks
4. Your current grade and highest possible grade will update automatically

## GitHub Pages Setup

To host this on GitHub Pages:

1. Create a new repository on GitHub
2. Upload `grade-calculator.html` to the repository
3. Rename it to `index.html` (or keep it as is and update GitHub Pages settings)
4. Go to Settings → Pages in your repository
5. Select the branch and folder containing the file
6. Your grade calculator will be live at `https://yourusername.github.io/repository-name/`

Alternatively, you can:
- Keep the file as `grade-calculator.html` and access it directly
- Or rename it to `index.html` for automatic serving

## Data Storage

All your grade data is stored locally in your browser using localStorage. This means:
- ✅ Your data stays private (never sent to any server)
- ✅ Your data persists between sessions
- ⚠️ Clearing browser data will remove your grades (consider exporting/backing up)

## Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

## Structure

Each subject follows this evaluation structure:
- **Term Work**: 70% of final grade
  - Tests and Quizzes: 40% of course
  - Assignments and Labs: 30% of course
- **Summative**: 30% of final grade
  - Lab Exam: 10% of course
  - Written Exam: 20% of course

You can add multiple items to each subcategory, and the calculator will automatically weight them correctly.
