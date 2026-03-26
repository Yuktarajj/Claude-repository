# Design QA Checklist

A comprehensive quality assurance checklist for design reviews — covering layout, typography, color, components, states, accessibility, responsiveness, documentation, and handoff readiness.

> Based on the [Design QA Checklist (Community) Figma file](https://www.figma.com/design/eHRPqU5UYeOWMx1mrmk7en/Design-QA-Checklist--Community-)

---

## 1. Layout & Spacing Checklist

- [ ] **Grid system consistently applied across all screens**
  - Why: Ensures everything lines up perfectly
  - Helps create a clean, professional look across all designs

- [ ] **Consistent spacing using defined spacing tokens**
  - What It Means: Spacing between elements follows a predefined system (e.g., 4px, 8px, 16px) instead of random values
  - Why: Consistent spacing creates a visually balanced design and makes development easier by reducing guesswork
  - Pro Tip: Define and stick to a spacing scale (e.g., 4px, 8px, 16px, 32px) to ensure uniformity across all screens

- [ ] **Content aligned properly (left, right, center as needed)**
  - What It Means: Text and elements are positioned correctly according to the layout and readability needs
  - Why: Poor alignment makes a design feel unpolished and harder to read, reducing usability and accessibility
  - Pro Tip: Follow alignment best practices — left-align body text for readability, center-align short headings when necessary, and maintain consistency throughout

- [ ] **Visual hierarchy established with proper spacing**
  - What It Means: Visual hierarchy refers to the way design elements are arranged to guide the user's attention in a logical order. Proper spacing helps differentiate between sections, making it clear which elements are most important and how they relate to each other
  - Why: Without a clear visual hierarchy, users may struggle to navigate the interface or understand the importance of different elements. Proper spacing improves readability, ensures a structured layout, and enhances the overall user experience
  - Pro Tip:
    - Use larger spacing around important elements (like section titles and call-to-action buttons) to make them stand out
    - Keep smaller spacing for related items to indicate they belong together
    - Maintain consistent spacing rules (e.g., 8px, 16px, 32px) to create a balanced and visually appealing design
    - Test your design by slightly squinting your eyes — if the most important elements don't stand out, adjust the spacing!

- [ ] **Equal padding between similar elements**
  - What It Means: Elements that belong to the same category (e.g., buttons, cards, sections) have consistent padding
  - Why: Uneven padding creates visual imbalance and makes the design feel unstructured
  - Pro Tip: Define padding rules (e.g., buttons always have 12px padding inside) and use auto-layout tools to maintain consistency

- [ ] **Appropriate margins for edge content**
  - What It Means: Content near the screen edges has enough space to avoid feeling cramped. Ensuring content has sufficient breathing room at page boundaries
  - Why: Poor edge spacing can make content look cluttered and difficult to read, especially on smaller screens
  - Pro Tip: Use safe zones (e.g., 16px margin from screen edges) to ensure readability and prevent content from being cut off

- [ ] **Related elements are visually grouped**
  - What It Means: Items that belong together (e.g., form labels and input fields, image and caption) are placed close to each other
  - Why: Grouping related elements improves scannability and helps users understand connections between different parts of the UI
  - Pro Tip: Use proximity and consistent spacing to group related elements while keeping unrelated items clearly separated

- [ ] **Adequate whitespace for readability**
  - What It Means: The empty space between design elements that helps improve readability, separates content, and creates a clean, uncluttered design
  - Why: Whitespace helps users process information more easily and improves the overall visual appeal of the design
  - Pro Tip: Don't be afraid of empty space — it improves focus and makes the UI feel more refined

- [ ] **No unintentional element overlapping**
  - What It Means: UI elements don't accidentally overlap in ways that make content unreadable or difficult to interact with
  - Why: Overlapping elements can break functionality and make the design look unpolished
  - Pro Tip: Regularly check different screen sizes and dynamic content scenarios (e.g., long text) to prevent unexpected overlaps

- [ ] **UI scales appropriately at different sizes**
  - What It Means: The design adjusts properly across different screen sizes without breaking or becoming hard to use
  - Why: A scalable UI ensures that users have a smooth experience whether they're on a phone, tablet, or desktop
  - Pro Tip: Test designs at multiple breakpoints and use flexible layouts to ensure adaptability without distortion

---

## 2. Typography Checklist

- [ ] **Font families consistent with design system**
  - What It Means: Use the same set of fonts across all design materials
  - Why It Matters:
    - Creates a unified, professional brand identity
    - Helps users recognize your product instantly
    - Reduces visual confusion
    - Makes designs look intentional and well-crafted

- [ ] **Font sizes follow type scale**
  - Why: Creates harmonious text hierarchy
  - Helps guide users through content

- [ ] **Font weights used consistently**
  - Why: Establishes clear visual hierarchy
  - Makes important information stand out predictably

- [ ] **Appropriate line height for readability**
  - Why: Ensures comfortable reading
  - Prevents eye strain and improves user experience

- [ ] **Text truncation handled gracefully**
  - What It Means: Intelligently shortening text that doesn't fit in its container
  - Why It Matters:
    - Prevents layout breaking
    - Maintains design integrity
    - Ensures critical information remains visible
    - Improves readability on different devices

- [ ] **Font styles (italic, underline) used appropriately**
  - What It Means: Apply special text treatments with clear purpose
  - Why It Matters:
    - Draws attention to important information
    - Adds visual hierarchy
    - Prevents design from looking cluttered
    - Improves content comprehension

- [ ] **Text colors meet accessibility standards**
  - What It Means: Ensure text is readable for all users, including those with visual impairments
  - Why It Matters:
    - Makes content accessible to everyone
    - Complies with legal accessibility requirements
    - Improves readability in different lighting conditions
    - Prevents eye strain

- [ ] **Headings follow hierarchy correctly**
  - What It Means: Organize text with clear importance and structure
  - Why It Matters:
    - Helps users quickly scan and understand content
    - Creates clear visual structure
    - Improves content navigation
    - Guides readers through information logically

---

## 3. Color & Styling Checklist

- [ ] **Colors from approved palette only**
  - Restricting color usage to a predefined set of colors
  - Maintains brand identity
  - Ensures visual consistency across designs

- [ ] **Color contrast meets WCAG standards**
  - Ensuring text and interactive elements have sufficient contrast
  - Makes design readable for people with visual impairments
  - Follows web accessibility guidelines

- [ ] **Colors used consistently for meaning**
  - Not relying exclusively on color to convey information
  - Important for users with color blindness
  - Using additional indicators like icons or text

- [ ] **Gradients applied consistently**
  - What It Means: Use smooth color transitions in a uniform way
  - Why:
    - Creates depth and visual interest
    - Looks professional when used carefully
    - Helps guide user's eye to important elements
  - Pro Tip: Pick 1-2 gradient styles and stick to them across the design

- [ ] **Shadow styles used consistently**
  - What It Means: Use shadows that look similar everywhere
  - Why:
    - Adds depth to your design
    - Makes UI elements feel more realistic
    - Helps users understand what they can interact with
  - Pro Tip: Create a standard set of shadow styles for different element types

- [ ] **Border styles and radius consistent**
  - What It Means: Keep corners and border looks the same across designs
  - Why:
    - Makes your design look intentional
    - Creates a unified, professional appearance
    - Helps users recognize interactive elements
  - Pro Tip: Define exact border radius values (like 4px or 8px) and use them everywhere

- [ ] **State changes visually indicated**
  - What It Means: Show clear visual changes when users interact with elements
  - Why:
    - Gives users feedback on their actions
    - Makes interface feel responsive
    - Helps users understand what's happening
  - Pro Tip: Create clear hover, active, and focus states for all interactive elements

- [ ] **Icons follow consistent style**
  - What It Means: Use icons that look like they belong together
  - Why:
    - Creates a cohesive look
    - Makes design feel more professional
    - Helps users quickly understand visual cues
  - Pro Tip: Choose one icon style (thin, bold, outlined, filled) and use it consistently

- [ ] **Dark mode tested if applicable**
  - What It Means: Create a design that works well in light and dark color schemes
  - Why:
    - Reduces eye strain
    - Provides user preference options
    - Makes your design feel modern and considerate
  - Pro Tip: Ensure all colors and elements work well in both light and dark modes

- [ ] **Visual effects used purposefully**
  - What It Means: Add visual flourishes only when they improve user experience
  - Why:
    - Prevents design from looking cluttered
    - Keeps focus on important content
    - Makes interactions more meaningful
  - Pro Tip: Ask "Does this effect help the user?" before adding any visual element

- [ ] **Visual styling consistent across screens**
  - What It Means: Keep design looking the same on all devices and views
  - Why:
    - Creates a unified brand experience
    - Helps users feel comfortable in your design
    - Shows professional, thoughtful design
  - Pro Tip: Create a style guide that works from mobile to desktop

- [ ] **Images properly sized and optimized**
  - What It Means: Use images that load quickly and look good
  - Why:
    - Improves website performance
    - Ensures images look crisp on all devices
    - Reduces loading times
  - Pro Tip: Compress images and use appropriate sizes for different screens

---

## 4. Components Checklist

- [ ] **Components match design system specifications**
  - What It Means: All UI components (buttons, inputs, cards, etc.) follow the rules defined in the design system
  - Why: Ensures consistency across the product and speeds up development

- [ ] **Component variants are properly defined**
  - What It Means: Each component has clear variants (e.g., primary/secondary buttons, small/medium/large sizes)
  - Why: Reduces ambiguity during development and ensures correct usage

- [ ] **Component naming conventions are consistent**
  - What It Means: All components follow a clear, predictable naming pattern
  - Why: Makes components easy to find, reuse, and maintain

- [ ] **Components are reusable across screens**
  - What It Means: Components are designed to be flexible enough to work in multiple contexts
  - Why: Reduces design debt and development effort

- [ ] **Component spacing and padding are standardized**
  - What It Means: Internal spacing within components follows the design system's spacing tokens
  - Why: Ensures visual consistency when components are used across different layouts

- [ ] **Interactive component states are defined**
  - What It Means: All interactive components have defined states (default, hover, active, focus, disabled)
  - Why: Provides clear guidance for developers and ensures a polished user experience

- [ ] **Component content is flexible**
  - What It Means: Components handle varying content lengths and types gracefully
  - Why: Real-world content is unpredictable — components need to accommodate different scenarios

- [ ] **Components are accessible by default**
  - What It Means: Components are built with accessibility in mind (proper contrast, focus indicators, labels)
  - Why: Ensures the product is usable by everyone, including users with disabilities

---

## 5. States Checklist

- [ ] **Default states clearly defined**
  - What It Means: Every interactive element has a clear resting/default appearance
  - Why: Users need to understand what elements look like before interaction
  - Pro Tip: Ensure default states are visually distinct and communicate the element's purpose

- [ ] **Hover states designed for all interactive elements**
  - What It Means: Visual feedback is provided when users hover over clickable elements
  - Why: Helps users identify what's interactive and provides feedback before clicking
  - Pro Tip: Keep hover effects subtle but noticeable — color shifts, shadows, or underlines

- [ ] **Active/pressed states implemented**
  - What It Means: Visual feedback when an element is being clicked or tapped
  - Why: Confirms to the user that their action is being registered
  - Pro Tip: Use slight scale changes, color darkening, or depth reduction to indicate press

- [ ] **Disabled states clearly communicated**
  - What It Means: Elements that can't be interacted with are visually muted
  - Why: Prevents confusion about what actions are currently available
  - Pro Tip: Use reduced opacity and remove hover effects for disabled elements

- [ ] **Focus states visible for keyboard navigation**
  - What It Means: Clear visual indicators when elements receive keyboard focus
  - Why: Essential for accessibility — keyboard users need to know where they are on the page
  - Pro Tip: Use visible focus rings that meet WCAG contrast requirements

- [ ] **Loading/processing states defined**
  - What It Means: Visual feedback during asynchronous actions (data loading, form submission, etc.)
  - Why: Prevents users from thinking the interface is broken during wait times
  - Pro Tip: Use skeleton screens, spinners, or progress bars depending on expected wait time

---

## 6. Accessibility Checklist

- [ ] **Color contrast ratios meet WCAG AA standards (4.5:1 for text, 3:1 for large text)**
  - What It Means: Text is readable against its background for users with visual impairments
  - Pro Tip: Use contrast checker tools to verify all text/background combinations

- [ ] **Interactive elements have minimum touch target size (44x44px)**
  - What It Means: Buttons, links, and other tappable elements are large enough to tap easily
  - Pro Tip: Ensure adequate spacing between touch targets to prevent accidental taps

- [ ] **Focus indicators are visible and clear**
  - What It Means: Keyboard users can see which element is currently focused
  - Pro Tip: Never remove focus outlines without providing an alternative visual indicator

- [ ] **Alt text or labels defined for all images and icons**
  - What It Means: Screen readers can describe visual content to users who can't see it
  - Pro Tip: Write descriptive, meaningful alt text — not just "image" or "icon"

- [ ] **Color is not the only means of conveying information**
  - What It Means: Information conveyed through color is also available through text, icons, or patterns
  - Pro Tip: Test your designs in grayscale to verify information is still understandable

- [ ] **Reading order is logical and sequential**
  - What It Means: Content flows in a logical order when read by screen readers or navigated by keyboard
  - Pro Tip: Structure your layouts so the visual order matches the DOM/reading order

- [ ] **Form fields have visible labels**
  - What It Means: Every input field has a clear, persistent label (not just placeholder text)
  - Pro Tip: Place labels above or beside inputs — never rely solely on placeholder text

- [ ] **Error messages are descriptive and helpful**
  - What It Means: Error states clearly explain what went wrong and how to fix it
  - Pro Tip: Use inline validation and specific error messages instead of generic alerts

- [ ] **Text can be resized without breaking layout**
  - What It Means: Users who zoom or increase font sizes can still use the interface
  - Pro Tip: Test your design at 200% zoom to ensure nothing breaks

- [ ] **Motion and animation can be reduced or disabled**
  - What It Means: Users with motion sensitivities can opt out of animations
  - Pro Tip: Respect the "prefers-reduced-motion" system setting in your designs

---

## 7. Responsiveness Checklist

- [ ] **Designs provided for all required breakpoints (mobile, tablet, desktop)**
  - What It Means: The layout adapts appropriately at each defined breakpoint
  - Pro Tip: Design mobile-first, then scale up to larger screens

- [ ] **Touch targets appropriately sized for mobile**
  - What It Means: Interactive elements are large enough for finger taps on touch devices
  - Pro Tip: Minimum 44x44px touch targets with adequate spacing between them

- [ ] **Content reflows properly at different widths**
  - What It Means: Content reorganizes logically as screen width changes
  - Pro Tip: Use flexible grids and avoid fixed-width layouts

- [ ] **Images and media scale proportionally**
  - What It Means: Visual assets resize without distortion or cropping issues
  - Pro Tip: Use responsive image techniques and maintain aspect ratios

- [ ] **Navigation adapts for different screen sizes**
  - What It Means: Navigation patterns change appropriately (e.g., hamburger menu on mobile)
  - Pro Tip: Test navigation at every breakpoint to ensure usability

- [ ] **Typography scales appropriately across devices**
  - What It Means: Font sizes adjust for readability on each screen size
  - Pro Tip: Use relative units and test reading comfort on actual devices

- [ ] **No horizontal scrolling on mobile devices**
  - What It Means: All content fits within the viewport width on mobile
  - Pro Tip: Check for elements with fixed widths that might cause overflow

- [ ] **Modals and overlays work on small screens**
  - What It Means: Pop-ups, dialogs, and overlays are usable on mobile devices
  - Pro Tip: Consider full-screen modals on mobile for better usability

---

## 8. Documentation Checklist

- [ ] **Design decisions are documented with rationale**
  - What It Means: Key choices (layout, color, interaction patterns) are explained with reasoning
  - Why: Helps developers and future designers understand intent behind decisions

- [ ] **Component usage guidelines are provided**
  - What It Means: Clear instructions on when and how to use each component
  - Pro Tip: Include do's and don'ts with visual examples

- [ ] **Spacing and sizing specifications are annotated**
  - What It Means: Exact measurements are noted for padding, margins, and element sizes
  - Why: Reduces guesswork during development and ensures pixel-perfect implementation

- [ ] **Interaction behaviors are described**
  - What It Means: Animations, transitions, and user flow behaviors are clearly documented
  - Pro Tip: Use annotations or prototype links to show intended behavior

- [ ] **Edge cases and empty states are documented**
  - What It Means: Designs cover scenarios like no data, errors, first-time use, and maximum content
  - Pro Tip: Document at least: empty state, error state, loading state, and overflow state

- [ ] **Design tokens and variables are listed**
  - What It Means: All reusable values (colors, spacing, typography) are cataloged
  - Why: Ensures consistent implementation and easy maintenance

- [ ] **Version history and changelog maintained**
  - What It Means: Changes to the design are tracked with dates and descriptions
  - Pro Tip: Keep a running changelog so team members can see what's changed

---

## 9. Handoff Readiness Checklist

- [ ] **All screens and flows are complete and up to date**
  - What It Means: No placeholder content, missing screens, or outdated designs in the handoff file
  - Pro Tip: Do a final walkthrough of every screen before handoff

- [ ] **Assets are exported in correct formats and sizes**
  - What It Means: Icons, images, and illustrations are provided in the required formats (SVG, PNG, etc.)
  - Pro Tip: Confirm export settings with developers before exporting

- [ ] **Design file is well-organized and clearly labeled**
  - What It Means: Layers, frames, and pages have descriptive names and logical structure
  - Pro Tip: Use a consistent naming convention throughout the file

- [ ] **Responsive behavior is documented or demonstrated**
  - What It Means: How the design adapts across breakpoints is clearly communicated
  - Pro Tip: Provide designs at key breakpoints or annotate responsive behavior

- [ ] **Interactive prototypes are linked and functional**
  - What It Means: Clickable prototypes demonstrate key user flows and interactions
  - Pro Tip: Test all prototype links before sharing to ensure they work correctly

- [ ] **Developer notes and annotations are included**
  - What It Means: Special instructions, edge cases, or technical considerations are noted
  - Pro Tip: Use Figma comments or a dedicated annotation layer for developer notes

- [ ] **Color, typography, and spacing tokens are referenced**
  - What It Means: Design specifications reference the design system tokens, not raw values
  - Pro Tip: Link to the design system documentation for easy reference

- [ ] **Feedback from stakeholders has been incorporated**
  - What It Means: All review comments and requested changes have been addressed
  - Pro Tip: Keep a feedback log and mark items as resolved

- [ ] **QA checklist has been completed and signed off**
  - What It Means: This entire checklist has been reviewed and all items are addressed
  - Pro Tip: Have a peer review the checklist before final handoff

---

## How to Use This Checklist

1. **Before Design Review**: Go through each section and check off items as you verify them
2. **During Handoff**: Share this checklist with developers to ensure nothing is missed
3. **For QA**: Use as a reference to verify the implementation matches the design

## Contributing

Create your own branch from `master` and submit a pull request with improvements.
