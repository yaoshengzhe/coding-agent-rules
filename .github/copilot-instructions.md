# GitHub Copilot Rules for This Repository

When generating code, please adhere to the following guidelines and project-specific conventions:

## General Coding Principles:

*   **Clarity and Readability:** Prioritize generating code that is clear, well-commented (where necessary), and easy for human developers to understand and maintain.
*   **Modularity:** Generate code in small, focused, and testable units (e.g., individual functions or methods). Avoid overly complex or monolithic blocks of code.
*   **Efficiency and Performance:** Strive for efficient algorithms and data structures, keeping performance considerations in mind as appropriate for the context.
*   **Security:** Be mindful of common security vulnerabilities (e.g., XSS, SQL injection). Generate code that follows security best practices, especially when dealing with user input or sensitive data. Sanitize inputs where appropriate.
*   **Adherence to Context:** Pay close attention to the surrounding code, comments, and any specific instructions in the user's prompt.
*   **Adaptability:** Continuously adapt to the evolving codebase, including manual corrections and new patterns introduced by developers.
*   **Test Support:** If tests are provided or described, generate implementation code that aims to make these tests pass. Assist in generating test boilerplate or test cases when requested.
*   **Documentation Use:** When documentation snippets or links for libraries/frameworks are provided in the prompt, prioritize that information in your suggestions.

## Project-Specific Conventions:

*(This section is crucial. Adhere strictly to these rules. Replace bracketed examples with your project's actual conventions.)*

*   **Preferred Libraries/Frameworks:**
    *   [Example: Use React for frontend development.]
    *   [Example: Use Express.js for backend Node.js applications.]
    *   [Example: Use Jest and React Testing Library for testing.]
*   **Coding Style:**
    *   [Example: Follow ESLint and Prettier configurations present in the project.]
    *   [Example: Use camelCase for variables and function names.]
    *   [Example: Use PascalCase for class names and React components.]
    *   [Example: Indentation: 2 spaces.]
*   **Architectural Patterns:**
    *   [Example: Follow the Model-View-Controller (MVC) pattern for backend services.]
    *   [Example: For state management in React, use Zustand.]
    *   [Example: All new features should be developed in a modular way, considering future microservice extraction if applicable.]
*   **API Endpoints/Client Usage:**
    *   [Example: All backend API calls from the frontend must use the `src/apiClient.js` module.]
    *   [Example: Adhere to RESTful principles for new API endpoint design.]
*   **Error Handling:**
    *   [Example: Use the custom error classes defined in `src/errors.js`.]
    *   [Example: Always log errors to the configured logging service using the provided logger instance.]
    *   [Example: Return consistent error response formats from APIs.]
*   **Security Considerations (Project Specific):**
    *   [Example: Always sanitize user inputs using the `sanitizeInput` function from `src/utils/sanitizers.js` before processing or storing.]
    *   [Example: Implement authorization checks using the `checkPermissions` middleware for relevant routes.]
*   **Things to AVOID:**
    *   [Example: Do not use the `eval()` function.]
    *   [Example: Avoid direct DOM manipulation in React components; use state and props.]
    *   [Example: Do not introduce new global variables.]
    *   [Example: Avoid using library X due to licensing issues/performance concerns with Y.]

---

Remember, your goal is to act as a highly effective coding assistant, producing code that aligns with these directives and accelerates development while maintaining high quality.