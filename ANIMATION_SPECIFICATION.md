# Animation Specification

The prototype recording is the behavioral reference. The Figma prototype is the interaction/layout reference.

## Hero
Document and implement:
- initial state
- model/image reveal order
- V-shaped composition behavior
- text reveal
- CTA reveal
- supporting visual layers
- transition to following content
- scroll behavior
- desktop/tablet/mobile behavior

For every animation record:
- Trigger
- Initial state
- Final state
- Duration
- Delay
- Easing
- Transform
- Opacity
- Responsive behavior

## Implementation
Use Framer Motion for coordinated component animation and CSS keyframes/transitions for simple decorative effects.

Do not invent exact timings/easing until verified against the prototype recording.
