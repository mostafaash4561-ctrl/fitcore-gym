# FitCore Gym

A responsive, single-page gym website built with HTML and CSS only.

## Sections

- **Hero:** headline, call-to-action buttons and image
- **Why Choose Us:** feature cards and extra services
- **Reviews:** member testimonials and statistics
- **Membership Form:** sign-up form with membership plans
- **Footer:** social links, quick links and contact info

## Project Structure

```
├── index.html
├── CSS/
│   ├── style.css         # base (desktop) styles
│   └── responsive.css    # media queries
└── Images/
    ├── hero-section-img.png
    ├── why-choose-us.png
    ├── avatar-1.jpg
    ├── avatar-2.jpg
    └── avatar-3.jpg
```

## Getting Started

Open `index.html` in any modern browser. No installation or build step is needed.

## Responsive Breakpoints

| Screen width | Main changes |
|---|---|
| 1024px and up | Two-column hero, 3 cards per row, 4 stats per row |
| 1023px and below | Hero and services section stack vertically |
| 767px and below | Cards and footer in one column, stats 2 × 2 |
| 480px and below | Smaller text and spacing, full-width hero buttons |

## Reusable Classes

| Class | Purpose |
|---|---|
| `container` | Centers content with a maximum width |
| `section`, `section-gray` | Section spacing and gray background |
| `section-header` | Centered title and description |
| `btn`, `btn-dark`, `btn-light` | Buttons |
| `cards`, `card` | Card grid and card box |
| `feature`, `review` | Card types |
| `blue`, `green`, `pink` (purple shade) | Card color themes |
| `field` | Form inputs |
| `links`, `links-column` | Link groups |

## Notes

- The form has no backend, so submitted data is not saved.
- The Privacy Policy, Terms of Service and Cookie Policy links are placeholders.
