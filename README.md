# Frontend Mentor - NFT Preview Card Component

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U).  
Frontend Mentor challenges help you improve your coding skills by building realistic projects.

---

## 📸 Preview

![Project Screenshot](./preview.jpg)  

---

## 📝 Overview

### The Challenge
Users should be able to:
- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot
![Design preview for the NFT preview card component coding challenge](preview.jpg)

### Links
- Solution URL: [GitHub Repository](https://github.com/InkAndLogic/NFT-preview-card-component)
- Live Site URL: [GitHub Pages](https://inkandlogic.github.io/NFT-preview-card-component/)

---

## ⚙️ Built With
- Semantic **HTML5 markup**
- **CSS custom properties**
- **Flexbox** for layout
- Mobile-first workflow
- **Google Fonts** (Outfit family)

---

## 📚 What I Learned
This project helped me practice creating a clean, modern card component with interactive hover states. Key learnings include:

- Using CSS custom properties for consistent color theming
- Implementing smooth hover transitions and overlay effects
- Creating responsive layouts that work across different screen sizes
- Proper semantic HTML structure for accessibility
- Working with the Outfit font family and different font weights

```css
/* Example: Hover overlay effect */
.image-overlay {
  position: absolute;
  background-color: hsla(178, 100%, 50%, 0.5);
  opacity: 0;
  transition: opacity 0.3s ease;
}

.card-image:hover .image-overlay {
  opacity: 1;
}
```

---

## 🚀 Useful Resources
- [Frontend Mentor](https://www.frontendmentor.io) - Great practice projects
- [CSS Tricks](https://css-tricks.com/) - Helpful CSS tips and patterns
- [Google Fonts](https://fonts.google.com/) - For the Outfit font family

---

## 🙌 Author
- GitHub - [InkAndLogic](https://github.com/InkAndLogic)
- Frontend Mentor - [@InkAndLogic](https://www.frontendmentor.io/profile/InkAndLogic)

---

## 📄 Acknowledgments
This project is based on the Frontend Mentor challenge design. Thanks to Frontend Mentor for providing such well-designed challenges that help developers practice and improve their skills.
4. Blog about your experience building your project. Writing about your workflow, technical choices, and talking through your code is a brilliant way to reinforce what you've learned. Great platforms to write on are [dev.to](https://dev.to/), [Hashnode](https://hashnode.com/), and [CodeNewbie](https://community.codenewbie.org/).

We provide templates to help you share your solution once you've submitted it on the platform. Please do edit them and include specific questions when you're looking for feedback. 

The more specific you are with your questions the more likely it is that another member of the community will give you feedback.

## Got feedback for us?

We love receiving feedback! We're always looking to improve our challenges and our platform. So if you have anything you'd like to mention, please email hi@frontendmentor.io.

This challenge is completely free. Please share it with anyone who will find it useful for practice.

**Have fun building!** 🚀
