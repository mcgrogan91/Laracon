# Matthew Machuga - Tests Should Tell A Story

@Machuga

Your code tells a Story.  Someone should be able to recognize the flow of data through your objects

Stories are not just told, they are interpreted.  Everyone might have a different interpretation

Something that you find clear, your users might find ambiguous

### Testing is important

#### Anatomy

1. Arrange - Set up preconditions and input
2. Act - on the objects or functions
3. Assert - that your assumptions are correct

#### BDD texting

Behavior Driven Development

Uses more descriptive language.  Output is very nice for business

### Jasmine & RSpec  

Ruby testing libraries?

### Tips

1. Be Expressive.
    * Tests are code too, refactor them
2. Respect the cukes
    * Cucumber/BHat
3. Bad stories are signals
    * Plot holes
        * Mocking the object under test
        * Global state mutations
        * Implicit Behavior
    * No descriptions
        * Creating abstractions that provide no benefit
        * No explanation why the environment is in current state
        * The world is bland and empty
    * Lack of Character Development
        * Performing transformations on characters out of Views
        * Mocking collaborators without clear reason
    * Switching narratives
        * Setting expectations on collaborators
        * Blurring lines between suites
4. Unit test in isolation
5. Try TDD/BDD (2 weeks)
    * Feature First (MVP)
        * Supports slice plans
        * Wastes fewer resources to test an idea
