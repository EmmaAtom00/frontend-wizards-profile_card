# Profile Card — Frontend Wizards Stage 0 Task

A simple, responsive, and accessible **Profile Card** built with semantic HTML, CSS, and vanilla JavaScript. This project was built as part of **Frontend Wizards — Stage 0**.

### Live Demo

[ View Live Project](#)

---

### Project Structure

```
profile-card/
├── index.html       # Main HTML file
├── styles.css       # Styling with responsive design
├── script.js        # JavaScript to show current time
├── images/
│   └── atom.jpeg    # Avatar image
└── README.md        # Project documentation
```

---

### Features

- Semantic HTML5 tags
- Accessible image with `alt` text
- Live current time in milliseconds using `Date.now()`
- Responsive layout using CSS Flexbox
- Data attributes (`data-testid`) for automated testing
- Keyboard-accessible social links
- Distinct sections for hobbies and dislikes

---

### How to Run Locally

1. **Clone the repository**:

   ```bash
   git clone https://github.com/EmmaAtom00/frontend-wizards-profile_card
   cd frontend-wizards-profile_card
   ```

2. **Open the HTML file in a browser**:

   ```bash
   open index.html
   ```

   or simply drag and drop `index.html` into your browser.

---

### Testing Targets (data-testid)

| Element                | `data-testid`              |
| ---------------------- | -------------------------- |
| Card container         | `test-profile-card`        |
| Name                   | `test-user-name`           |
| Biography              | `test-user-bio`            |
| Time (milliseconds)    | `test-user-time`           |
| Avatar image           | `test-user-avatar`         |
| Social links container | `test-user-social-links`   |
| Twitter link           | `test-user-social-twitter` |
| GitHub link            | `test-user-social-github`  |
| Hobbies list           | `test-user-hobbies`        |
| Dislikes list          | `test-user-dislikes`       |

---

### JavaScript Time Logic

The time in milliseconds is rendered using `Date.now()` and injected into the DOM when the page loads:

```js
const timeElement = document.getElementById("currentTime");
timeElement.textContent = Date.now();
```

---

### Responsiveness

The layout:

- **Stacks vertically** on small screens (mobile)
- **Aligns image and text side-by-side** on wider screens (tablet/desktop)

---

### Notes

- All external links open in a new tab (`target="_blank"`) with `rel="noopener noreferrer"` for security.
- All visible elements include the specified `data-testid` attributes for reliable test targeting.
- Avatar image can be replaced with a user-uploaded image or another URL.

---

### Submission Details

- **Hosted Link**: [Hosted Link](#)
- **GitHub Repo**: https://github.com/EmmaAtom00/frontend-wizards-profile_card
---

## Author

**Emmanuel Olarewaju**
[GitHub Profile](https://github.com/emmaatom00)
Email: [emmanuelmark501@gmail.com](mailto:emmanuelmark501@gmail.com)

Feel free to reach out for questions, feedback, or collaboration!

---


