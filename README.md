Note:
You'll need to run the following commands to get started!

`npm install`
`bundle install`

Then in order to get the application up and running you have to open up two
tabs and run `ruby server.rb` in one and `webpack --watch` in the other!

# Steps to Practice

 1. Create a React Component `DonutDisplay` that will eventually display all the donut information (don't forget to use some dummy text to test that your component is imported the right way)

 2. Create a React Fragment called `donuts` that passes the donut's id, name, imgUrl and delicious as props. Modify your `DonutDisplay` component to display the id, name and imgUrl of these pieces of information in order to make sure that you're setting up your props the right way.

 3. Add logic to your `DonutDisplay` component that puts a className of `"yummy"` on the `div` you return if the donut is delicious.

 4. Refactor the `App` code to add a state property of `bestDonutId` on the app component. Next create a `chooseBestDonut` function that you pass down to the `DonutDisplay` component when you create the fragment. Make sure it takes in the donut's id as an argument so that donut can be selected. Also make sure to pass the `bestDonutId` as props on the `DonutDisplay`.

 5. Refactor the `DonutDisplay` component to rely on the `bestDonutId` to add the className of "yummy" depending whether the donut's id is equal to the `bestDonutId`.
