# Dcipher Frontend Challenge

## Spec

You are expected to implement an interactive visualizer in this challenge.

You are given a dataset to work with. The dataset has the following fields;

- AB: Abstract of the academic articles.
- PY: Published year of the academic articles.
- tokens: Tokens extracted from AB column. `tokens` is list of JSON objects where each object has `id` and `value` keys. `value` field stores the text value of the token. A token can be a word, a phrase or a named entity. 

The full dataset can be downloaded [here](articles.json).

What we ask in this challenge is to visualize this dataset by implementing an interactive Bar chart.

## Requirements
- The bar chart should be able to show the tokens along with their frequencies among the dataset.
- X axis must display tokens' values.
- Y axis must display tokens' frequency values.
- There should be a component (button, toggle etc) to make it possible to sort the data in X-axis alphabetically (either ascending or descending)
- There should be a component (button, toggle etc) to make it possible to sort the data in Y-axis numerically (either ascending or descending)
- It should be possible to set the visible number of tokens. (minimum: 10, maximum: 100, default: 50)
- Add an another dimension for `PY` field where we can see year field as legend
  - We should be able to see token frequencies per PY field

As you might notice, it is required to post-process this dataset since frequency information is not provided.

NOTE: You can hard-code the not processed data into your web app.

## Technologies to be used
- Typescript
- `create-react-app` with typescript template
- React
- d3.js
- Redux (optional)

Additionally, you may want to use a UI framework like material-ui or tailwindcss or any framework of your choice.

## Good to have (but not required)
- React hooks
- Fast render performance (especially focus on improving render performance)
- Good modularization of components. Separate functionality of bar chart with use of react components
- Dockerization of app
- Unit tests with jest
- CI build using github actions
- Dynamic projection settings for Bar chart components (ability to change projection fields like x, y, color, etc.)

## Submission of the solution
1. Create a `private` github repository, add @aacanakin, @Atralbus, @zafercavdar to contributors to that repository.
2. Deploy your app so that it's accesible via a public URL to test the solution to the challenge (Github pages are suggested.)
3. Include a README file with instructions on how to run it locally.
4. Notify us by sending an email to `info@dcipheranalytics.com`
