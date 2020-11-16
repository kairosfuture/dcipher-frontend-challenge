# Dcipher frontend challenge

## Spec

In this challenge, you will be doing data visualization.

You are given a dataset to visualize. The dataset have the following fields;

- AB: Abstract of the article
- PY: The published year of article
- tokens: The token collection of AB field

The full dataset can be downloaded [here](articles.json).

What we ask in this assignment is to visualize this dataset by implementing a bar chart;

- The bar chart should show the frequencies of all tokens in the dataset
- In the x axis, you can show the token value
- In the y axis, you can show token frequency
- Ability to sort bar chart data alphabetically (asc, desc)
- Ability to sort bar chart data numerically (frequencies asc, desc)
- Finally, add a second dimension as `PY` field where we can see year field as legend
  - We should be able to see token frequencies per PY field

As you might notice, it is required to post process this dataset because we don't provide the count data.

NOTE: You can hard code the non processed data in your web app.

## Technologies to be used

- React
- D3
- Typescript
- `create-react-app` with typescript template
- Redux (optional)

Additionally, you may want to use a ui framework like material-ui or tailwindcss or a ui framework of your choice.

### Good to have

- React hooks
- Fast render performance (focus on improving render performance)
- Dockerization of app
- CI build using github actions
- Dynamic projection settings of bar chart component (ability to change projection fields like x, y, color, etc.)

### Submission of challenge

- Create a `private` github repository, add @aacanakin, @Atralbus, @zafercavdar to contributors to that repository.
- A deployed app with a public url where we can test the challenge (you can use github pages)
- Readme instructions on how to run it locally
- Notify us by sending an email to `info@dcipheranalytics.com`
