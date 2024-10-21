# Explained Visually is an experiment in making hard ideas intuitive.

See the live site at [setosa.io/ev](http://setosa.io/ev/).

Feel free to post more topic ideas as issues.

### Outdated

The code here is quite outdated. You'll need to do the following to get things working again.

- Only use version of NodeJS v9.x You may need to also use rosetta if you're using an M1 chip. You can do this using NVM see: https://stackoverflow.com/questions/67254339/nvm-install-node-fails-to-install-on-macos-big-sur-m1-chip

- Ensure you're using the npm version from nvm used to install node v9 when you run npm install

```bash
nvm install 9
nvm install 10
nvm use 9
nvm exec 9 node server.js --dev=true
nvm exec 10 gulp
```

## To get setup with the project locally, you'll need to first run

    npm install

Then, fire up the testing web server

    node server.js --dev=true

And also gulp in a seperate terminal tab

    gulp

Now you can open up a browser at `http://localhost:3000/ev/` to see the site.

To deploy, I run `gulp --no-watch` to make sure all the static resources are up
to date. then `make export` to copy all the static files from `_static` to the
setosa site.

## List of possible topics.

### Topic ideas

- [Logarithms](https://en.wikipedia.org/wiki/Logarithm)
- [Log scales](https://en.wikipedia.org/wiki/Logarithmic_scale)
- [Taylor Series](https://en.wikipedia.org/wiki/Taylor_series)
- [Div Grad Curl](https://en.wikipedia.org/wiki/Vector_calculus_identities)
- [Finite State Transducer](https://en.wikipedia.org/wiki/Finite_state_transducer)

### Transforms

- Function transforms (Z, Laplace, Fourier)
- [Moment Generating Function](https://en.wikipedia.org/wiki/Moment-generating_function)
- [Fourier Series](https://en.wikipedia.org/wiki/Fourier_series)
- [Partial Differential Equations](https://en.wikipedia.org/wiki/Partial_differential_equation) (all about flows and waves)

### Linear Systems

- [Determinant](https://en.wikipedia.org/wiki/Determinant)
- [Eigenvalue And Eigenvectors](https://en.wikipedia.org/wiki/Eigenvalues_and_eigenvectors)
- [Ordinary Differential Equations](https://en.wikipedia.org/wiki/Ordinary_differential_equation)
- [Birth-death Process](https://en.wikipedia.org/wiki/Birth%E2%80%93death_process) (relates to markov chains)

### Statistics

- [Gini Coeffient](https://en.wikipedia.org/wiki/Gini_coefficient)
- [Statistical Significance](https://en.wikipedia.org/wiki/Statistical_significance)
- [Bayes' Theorem](https://en.wikipedia.org/wiki/Bayes'_theorem)
- [Regression](https://en.wikipedia.org/wiki/Regression_analysis) (with instramental variables)
- [Why most published research findings are false](https://en.wikipedia.org/wiki/John_P._A._Ioannidis) (would include statistical significance)

### Chaos (Non-linear Systems)

- [Feigenbaum Constants](https://en.wikipedia.org/wiki/Feigenbaum_constants)
- [Lorenz system](https://en.wikipedia.org/wiki/Lorenz_system)

### Wildcards

- [Map projections](https://en.wikipedia.org/wiki/Map_projection)
- [Theory Of Relativity](https://en.wikipedia.org/wiki/Theory_of_relativity)

### Machine Learning

- [Logistic regression](https://en.wikipedia.org/wiki/Logistic_regression)
