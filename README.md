# Team Name: Code Syndicate

**Live site:** https://username.github.io/team-website/

## Team

| Name            | Registration no. | GitHub username |
| --------------- | ---------------- | --------------- |
| Margaret Kilola | COM/3409/26      | margaretsanchez |
| Maryjoy Rashid  | COM/3428/26      | Mariejoeystar   |

## Who drove each part

- Part 0, 2, 4:Margaret Kilola
- Part 1, 3:Maryjoy Rashid

## Personalisation

- Our colours:
  root
  --color-primary: #155e75;
  --color-primary-dark: #0c4a6e;
  Body
  --color primary: #67e8d2;
  --colour-primary-dark: #99f6e4;
- Projects we added:
  • HTML
  • GIT and GITHUB
  Extension challenge(s) completed:

## Reflection

1. The menu toggle is a <button>, not a clickable <div>. Name two things you would lose with a <div>, and who would be affected.

## A <div> lacks built-in keyboard support and button accessibility. Keyboard users and screen-reader users would be affected.

2. What would break if you removed defer from the <script> tag in <head>? Explain why, in terms of how the browser parses HTML.

## Without defer JavaScript may execute before the HTML elements load causing errors when accessing them.

3. renderProjects uses textContent rather than innerHTML. What could go wrong with innerHTML if project titles were typed in by visitors?

## innerHTML could execute malicious code entered by visitors causing XSS attacks

4. Your form checks its input with JavaScript. Why will the server still need to validate the same data once the form is connected to one?

## JavaScript validation can be bypassed, so the server must validate data to ensure it is safe and correct

5. Your theme choice follows you from Home to Contact, but not from a double-clicked file to Live Server. Explain this using the idea of an origin.

## Home and Contact share the same origin, so they share local storage. A directly opened file has a different origin from Live Server.

6. Name something duplicated across your HTML pages. What problem does that duplication cause, and how might it be avoided?

## The header and navigation menu are duplicated. This makes updates difficult. Reusable components or templates can avoid duplication.
