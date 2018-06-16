# markov-commencement-speech
🎓 Generate your own commencement speeches with Markov chains and a [dataset](https://floydhub.com/whatrocks/datasets/commencement) of some of the world's "best" commencement speeches.

`The secret to success in start-ups, or any other collaboration, is to stick an old head on a motorcycle weaving his way down the hall, he passed a door – it was empty.`

### Try it now

[![Run on FloydHub](https://s3-us-west-2.amazonaws.com/floydhub-assets/button/button.svg)](https://floydhub.com/run?template=https://github.com/whatrocks/markov-commencement-speech)

Click this button to open a Workspace on FloydHub where you can generate your own "commencement speech style" sentences in a live JupyterLab environment. The [commencement address dataset](https://floydhub.com/whatrocks/datasets/commencement) of ~300 famous speeches will be automatically attached and available in the Workspace.

The `speech_maker` notebook has three sections for you to try:

1. Using the entire dataset
2. Filtering to only the top ten schools by count of speeches given
3. Filtering to one school at a time using an Jupyter widget

### Public dataset

The [commencement address dataset](https://floydhub.com/whatrocks/datasets/commencement) is a plaintext collection of some of the world's most famous commencement speeches. This repo contains a CSV with metadata for each speech (speaker `name`, `school`, and `year`).

The list of speeches originally started with NPR's [The Best Commencement Speeches, Ever](https://apps.npr.org/commencement/), a site I frequent often. Transcripts were available for many but not all of the speeches.

If you're in need of your daily dose of cliché, trope, and sentimentality, you can view the speeches [here](https://whatrocks.github.io/commencement-db/) in a simple Gatsby.js site.

#### Thanks to

* [markovify](https://github.com/jsvine/markovify)
* [pandas](https://pandas.pydata.org/)
* gatsby
* National Public Radio
