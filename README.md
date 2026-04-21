# My Learning Journal

A multi-page responsive blog website designed to document my journey through a frontend development bootcamp. This project focuses on building a professional-grade layout that adapts seamlessly from mobile devices to large desktop monitors.

## 🚀 Features

- **Hero Section**: A prominent feature area with high-contrast text overlay and background images.
- **Dynamic Grid Layout**: A flexible 3-column post grid that collapses to a single column on mobile.
- **Responsive Navigation**: Includes a clean header with a hamburger menu for mobile viewports
- **Mobile-First Design**: Prioritized mobile layouts for optimal performance on smaller screens.

## 🛠️ Technologies Used

- **HTML5**: Semantic elements ( <header> , <main> , <article> ,<footer> ) for accessibility
- **CSS3**: Advanced styling techniques including:
      - **CSS Grid:** For structured, multi-column post layouts.
      - **Media Queries:** For device-specific breakpoint adjustments.
      - **Flexbox:** For navigation alignment and small-component positioning.

## 📸 Screenshots and Demo


[Project link demo](https://assadullahhassan.github.io/learning-journal/)

[Project Screenshot/video](https://drive.google.com/drive/folders/11mD8bEW1COj-IdpPSnNdO8ypP455fr3I?usp=sharing)

## 💡 What I Learned

During the development of this project, I focused on:

1. **Mastering CSS Grid**: I moved beyond simple layouts to implement a responsive grid system. I learned how to use         grid-template-columns combined with gap to create gutters that look professional without using margins on individual items.

      ```CSS
         /* Example Grid Implementation */
         .post-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            }
         @media (max-width: 768px) {
         .post-container {
         grid-template-columns: 1fr;
          }
         }
      ```

2. **Effective Breakpoint Management**: I practiced the "mobile-first" approach. By writing the base CSS for small screens first, I avoided "CSS bloat" and only added complexity within media queries for larger viewports.

3. **Typography Scalability**: I learned to manage text hierarchy across devices. Using relative units and media queries, I ensured that large headings on the desktop version (like the Hero title) don't overflow or become unreadable on mobile screens.


### ✍️ Author
   * **Assadullah Hassan**
      - GitHub: [@assadullahhassan](https://github.com/assadullahhassan/)
      - LinkedIn: [Assadullah Hassan](https://www.linkedin.com/in/assadullahhassan)

Made from Scrimba by [Assadullah Hassan](https://scrimba.com/?via=u4f4512)

---
