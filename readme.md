# Project: JSX Portfolio Website

### Objective

Create a personal portfolio website using JSX. This project will help you get comfortable with structuring a simple JSX application, nesting JSX components, and applying CSS styles in a JSX context.

### Why a JSX Portfolio?

This project will help you get accustomed to using JSX for structuring a simple static site. By focusing on component nesting and CSS styling without diving into advanced JSX concepts like props and state, you can develop a solid understanding of JSX’s core principles in a straightforward, manageable way. Dive in and create a portfolio that showcases your unique style and skills!


### Requirements

1. **Application Structure**
  - Serve the pages from a back end, using:
    - Express to respond to requests for URLS (for example, `/about` should respond with your `about.jsx` file)
    - `express-react-views` as your rendering engine
        
2. **Page Structure:**
  - Each page should have its own JSX component (for example, `projects.jsx`). You need each of the following:
    - **Home Page:** A welcoming page with a brief introduction.
    - **About Page:** Information about the individual.
    - **Projects Page:** A list of projects you've worked on.
    - **Contact Page:** Contact information and social media links.

3. **Navbar Component:**
  - Each page should include a nested `Navbar` component.
  - The Navbar should contain links to Home, About, Projects, and Contact.

4. **HTML Structure:**
  - Each page should include a full HTML skeleton (`html`, `head`, and `body` tags).

5. **Styling:**
  - Define styles in an object before the `return` statement of each component.

### Recommendations

- For extra practice, create Header and Footer components and nest them within each page.
- See [the final version of the JSX Lesson](https://github.com/abbreviatedman/jsx-lesson-endpoint) for reference if you're unsure of syntax.
