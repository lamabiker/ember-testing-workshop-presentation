---?image=assets/images/backgrounds/1.jpg

# Basic testing in Ember

An introduction to testing in Ember

---?image=assets/images/backgrounds/2.jpg

## Overview

1. Intro + stack
2. Integration tests
3. Application tests
4. Live demo + your turn yay

![Git](https://media.giphy.com/media/BX1E1z6e4G7YI/giphy.gif)

---?image=assets/images/backgrounds/3.jpg

## Intro + stack

- `ember install ember-test-selectors ember-cli-mirage ember-cli-yadda`
- _optional_ `ember-arc` [for extra awesomeness](https://storyful.github.io/ember-arc/#/docs/installation)

---?image=assets/images/backgrounds/4.jpg

## Integration tests (_aka_ Rendering tests)

Rendering Tests are, as the name suggests, rendering components and helpers by verifying the correct behavior when the component or helper interacts with the system in the same way that it will within the context of the application, including being rendered from a template and receiving Ember's lifecycle hooks.

---?image=assets/images/backgrounds/5.jpg

### Application tests

An integration test actually spins up an instance of an app and interacts with it the way a user would.
For this we need `mirage` to fake the data and `yadda` to make the specs clearer.

---?image=assets/images/backgrounds/6.jpg

## Live demo + your turn yay

- Small form
- We'll test a helper with an integration test
- We'll test a successful and a failing form with application tests

@fa[github] [repo](https://github.com/lamabiker/ember-testing-workshop)

---?image=assets/images/backgrounds/8.jpg