# web-animation-motion-design
Just recording the common technique so I don't have to rethink all this crap.

Video
https://www.youtube.com/watch?v=9eHEOAn2FOA


Supporting javascript function for interactive element
- Preserve scroll level on refresh
- Scroll detection
- Scroll percentage
- Toggle parent Scrollbar
- Element stickiness: fixed in document.body
- Element stickiness: sticky until end of space
- Screen size and child width
- Position element within nearest width and nearest height, top first, left or right.
- Scroll to position


Working with dom best practice
1. Use classList methods (add, remove, toggle) for class manipulation.
2. Use querySelector() for one element and querySelectorAll() for multiple elements.
3. Cache element references and re-cache when changes occur.
4. Use numeric IDs to simplify same structure child element naming.
5. Debounce/throttle rapid events to improve performance.
6. Remove old/stale event listeners to prevent memory leaks.
7. Avoid modifying the DOM inside loops; build elements in a variable, then insert them after the loop.
8. Reduce using innerHTML for performance sake; if needed sanitize or use appendChild() instead.
9. Use template literals for building HTML to enhance readability.
10. Use JS to store state and sync to HTML via events, reducing state in HTML.
11. RequestAnimationFrame
12. FLIP technique
13. Debouncing user actions: https://web.archive.org/web/20220117092326/http://demo.nimius.net/debounce_throttle/
14. Throttling might be useful. But I dont know on what time of interaction.
