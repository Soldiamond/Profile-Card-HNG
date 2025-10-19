# Profile Card - HNG Internship Stage 0 Task

A responsive, accessible profile card component built with semantic HTML, modern CSS, and vanilla JavaScript.

## Live Demo
[View Live on GitHub Pages](https://soldiamond.github.io/Profile-Card-HNG)

##  Features
- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Semantic HTML5 structure
- ✅ Accessible (WCAG compliant)
- ✅ Real-time milliseconds display
- ✅ Social links with security attributes
- ✅ Hover effects and smooth transitions
- ✅ Cross-browser compatible

## Technologies Used
- HTML5 (Semantic)
- CSS3 (Grid, Flexbox, Media Queries)
- Vanilla JavaScript

## Project Structure

profile-card/
├── index.html
├── assets/
│ └── Solution.png
├── README.md
└── package.json

## Local Development

### Option 1: Simple Server
1. Clone the repository:
```bash

git clone https://github.com/your-username/hng-profile-card.git
cd hng-profile-card
open index.html

### Option 2: Install live-server globally
1. npm install -g live-server
2. live-server --port=3000
3. Open http://localhost:3000 in your browser

Testing
Automated Test Compatibility
All elements include required data-testid attributes:

test-profile-card - Main container

test-user-name - User's full name

test-user-bio - Biography text

test-user-time - Current time in milliseconds

test-user-avatar - Profile image

test-user-social-links - Social media container

test-user-social-* - Individual social links

test-user-hobbies - Hobbies list

Manual Testing Checklist
All data-testid attributes present

Time updates every 100ms

Responsive on mobile (≤768px)

Responsive on tablet (769px - 1024px)

Desktop layout (≥1025px)

Social links open in new tabs

Keyboard navigation works

Focus states visible

Images have alt text

Responsive Breakpoints
Mobile: ≤ 768px

Tablet: 769px - 1024px

Desktop: ≥ 1025px

Browser Support
Chrome (latest)
Edge (latest)

Requirements Met
Semantic HTML tags

Required data-testid attributes

Real-time milliseconds

Accessible social links

Responsive design

Cross-browser compatibility

Security attributes (noopener, noreferrer)

Author
Solution Abiola Owoche

Junior Web Developer

Creative Graphic Designer

HNG Internship Participant

test-user-dislikes - Dislikes list

