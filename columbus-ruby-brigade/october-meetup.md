# October Meetup

## Method of the Month: `.clamp`

if x &lt;=&gt; min &lt; 0, x = min, 

if x &lt;=&gt; max &gt; 0, x = max,

else x = 0

Works on positive and negative numbers \(floats and integers\) as well as letters and strings

Arguments must be ordered \(min, max\)

Best used with numbers

## Finding Testing Boundaries

* The automated testing pyramid
  * Bottom level: Unit tests
  * integration tests
  * acceptance tests
  * Top level: Manual testing
* The black box
  * Pass in some input and verify the output
  * Slow and brittle
* Unit testing
  * Slice things into tiny pieces \(grid style\)
  * A lot of mocking
  * Tend to be brittle
* No one-size-fits-all approach

### Problems

* Rails inadvertently pushes you to do things a certain way
  * Convention over configuration
* You don't know what your application will look like in three years
* Your Jira ticket doesn't say anything about the solution architecture
* You might not see the big picture

### Questions

* Identify logical groupings of functionality your system
  * If I asked you to split out some grouping of code into its own engine/project/repo/microservice, it should be relatively easy.
* What logical seams \(if any\) should we put in our code?
  * What small investment today could pay off big later on?
* How does this affect how we will test things?

