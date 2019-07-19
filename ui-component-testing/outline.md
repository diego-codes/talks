# UI Component Testing

## Intro

- Why should I test my components?
  - EXAMPLE: How _not_ to build a house
- "How can I break this?" mentality
- Testing does not prove the absence of defects
- Going from manual to automated-_ish_

## Testing component variations

- Variations in props and state (invalid user input) ?
- Manually: Using Storybook to create multiple variation stories
- Storybook serves as documentation of your components
- Manually: Using Knobs in Storybook
- Browser emulation (JSDOM)
- Why React Testing Library
- Automated: Using Jest with React Testing Library

## Testing interactions and actions

- The more your tests simulate real user behavior the better
- Manually: Using Actions in Storybook
- Automated: Using Jest with `fireEvent` for interactions
- Automated: Using Jest mock functions for actions

## Testing component clean up (don't leave a mess)

- Cleaning up anything set up outside of component like window event listeners
- Automated: Using Jest spies

## Conclusion

- ??