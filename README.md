<!--hide-->
# Sorting Cards using the selection algorithm
<!--endhide-->

The "Selection Sorting Algorithm" is also another simple example of how computers work when sorting the list of things. [Here is a 5 min explanation on how the selection algorithm works](https://www.youtube.com/watch?v=g-PGLbMth_g)

https://github.com/breatheco-de/exercise-sorting-cards-with-bubble/pull/3

<onlyfor saas="false" withBanner="false">
    
## 🌱  How to start this project

Do not clone this repository because we are going to be using a different template.

We recommend opening the `vanillajs boilerplate` template, using a provisioning tool like [Codespaces](https://4geeks.com/lesson/what-is-github-codespaces) (recommended) or [Gitpod](https://4geeks.com/lesson/how-to-use-gitpod). Alternatively, you can [clone the GitHub repository](https://4geeks.com/how-to/github-clone-repository) on your local computer using the `git clone` command.

This is the repository you need to open or clone:

```sh
git clone  https://github.com/4GeeksAcademy/vanillajs-hello
```

💡 Important: Remember to create a new repository, update the remote (`git remote set-url origin <your new url>`), and upload the code to your new repository using `add`, `commit` and `push`.

</onlyfor>

## 📝Instructions

1. Create a function that generates a list of random cards with suits.
2. Let the user specify how many random cards the website should generate using a text input.
3. Add a "draw" button that when clicked it renders those cards on the website in a beautiful way.
4. Add one "sort" button that sorts the cards using the `selection` sorting algorithm.
5. Save all the changes that you had to do while sorting the list of cards in a new array.
6. Display the entire log of changes, one on top of the other.

This is an example of how your application should look:

![Bubble Sorting Cards on a website](https://raw.githubusercontent.com/breatheco-de/exercise-sorting-cards-with-select/master/preview.gif)

## 💡 Hint:

1. Strategize first, no one starts coding the solution before having a clear strategy.
2. Stick to your strategy, forget about Stack Overflow for strategy.
3. Divide and conquer, try separating the exercise in smaller exercises, for example:
    - Make the hardcoded CSS and HTML before trying to make it dynamic, that will give you a clear sense of what HTML code you need to build with your algorithm.
    - Generate an array of random cards first, and make sure is properly being generated (using the console.log) before trying to render it into the website.
    - Make a function just for building the HTML of ONE card,a nd then re-use it to render all.
