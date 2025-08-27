# Accordions

Accordions let users expand or collapse content within one screen. They reduce clutter, support progressive disclosure, and keep focus on one section at a time.

In insurance platforms, accordions often appear in quote breakdowns, FAQs, policy documents, endorsements, and billing histories. They are useful when space is limited and users do not need to see all content at once.

Correct use improves:

- **User experience** – Clear, efficient interactions  
- **Accessibility** – Screen reader support, keyboard navigation, and usability best practices  
- **Performance & efficiency** – Fewer errors and less friction  
- **Business impact** – Higher conversions, engagement, and consistency  

---

## Usage guidelines

### When to use accordions
- To reveal small, related chunks of content  
- To manage dense content like FAQs, coverage, or endorsements  
- To avoid long scrolls or overwhelming layouts  

### Decision tree: When to use
- **Is the content optional or secondary?**  
  - Yes → Use accordions  
  - No → Show inline or use tabs  

- **Do users need to compare sections at once?**  
  - Yes → Allow multiple panels open  
  - No → Restrict to one open at a time  

- **Will users return often?**  
  - Yes → Use clear labels and collapsible panels  
  - No → Consider default-expanded content  

### When not to use
- If critical info is hidden by default  
- If content must be read top to bottom (e.g., legal terms, instructions)  
- If it adds unnecessary interaction for basic details  

---

## User behavior and interaction

- Decide if multiple panels can open at once.  
  - Allow one open panel only when expected (e.g., step-by-step).  
- Make headings clear and scannable.  
- Decide if panels load expanded or collapsed.  

---

## Best practices
- Use clear, specific headings  
- Keep logical focus order with arrow-key navigation  
- Avoid async loading unless feedback is visible  
- Use subtle or no animation for faster interaction  

---

## Experience strategy
- Supports scanning and progressive discovery  
- Reduces clutter in dense flows  
- Improves control, especially on mobile  
- Prevents overwhelm while keeping details accessible  
- Ensures consistency across quotes, claims, and policy management  

---

## Common mistakes

| Mistake | Correct approach |
|---------|------------------|
| Using vague headings | Use clear labels like “Deductibles” or “Rental Coverage” |
| Hiding essential content | Keep critical info visible by default |
| No keyboard interaction | Support tab and arrow keys with `aria-expanded` |
| Heavy animation | Use subtle transitions or none |

---

## Pattern benefits

### User experience
- Reduces visual overwhelm  
- Improves scannability  
- Enhances user control  

### Business impact
- Improves task success for quotes, policies, or FAQs  
- Reduces support volume through better self-service  
- Keeps UI structured and brand-aligned  

---

## General rule of thumb
- **Use**: For secondary, related content in limited space  
- **Avoid**: When all content must be visible at once for decision-making  

---

## Notes for specific scenarios

**Mobile**  
- Default to collapsed  
- Use large tap targets  

**Accessibility**  
- Use native `<details>/<summary>` or ARIA-compliant components  
- Announce expanded/collapsed state with `aria-expanded`  
- Group within a region with `aria-labelledby` for screen reader context  

---

## Related components and patterns

| Component | Component | Pattern |
|-----------|-----------|---------|

---

## Changelog

| Date       | Description                                      |
|------------|--------------------------------------------------|
| 08/13/2025 | Released – EDS Team                              |
| 03/28/2025 | Reviewed – Documentation Team – AZ               |
| 03/28/2025 | Draft complete – SM                              |
