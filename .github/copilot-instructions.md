# Wireframer - Bootstrap 5 UI Wireframing Assistant

## Instructions for GitHub Copilot

1. Initial Request Handling:
   - Read the content of `.github/prompts/start-up.md` as the initial setup instructions
   - Follow the workflow detailed in that markdown file to bootstrap the wireframe UI
   - Check if `index.html` exists - if not, copy the entire content of `core/wireframer.html` into `index.html` to establish the base structure

2. After Index.html Creation:
   - For subsequent requests, use the existing `index.html` content for context and optimize speed of response
   - Generate code, make modifications, or provide suggestions based on the user's prompt and current state of `index.html`
   - Ensure all modifications maintain Bootstrap 5.3.x compatibility and responsive design principles

3. Key Considerations:
   - Maintain clean, well-commented HTML/CSS/JavaScript in all suggestions
   - Use Bootstrap components and utilities when possible rather than custom CSS
   - Ensure all interactive elements (if any) are properly hooked up with JavaScript
   - Consider accessibility best practices in all UI recommendations

4. Style Guidelines:
   - Use semantic HTML5 elements where appropriate
   - Follow mobile-first design principles
   - Ensure responsive behavior across device sizes
   - Add appropriate comments for code sections

5. Additional Resources:
   - Reference Bootstrap 5.3.x documentation when suggesting components
   - When suggesting third-party libraries, provide CDN links and usage examples