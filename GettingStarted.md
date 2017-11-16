# Getting Started with Julia
Note that the number one resource for most of these questions is going to be the [Julia Docs](https://docs.julialang.org/en/stable). They are pretty comprehensive and if there's anything that doesn't make sense then let someone know (either make an issue [here](https://github.com/JuliaNeuro/julianeuro.github.io/issues) or ask on [Stack Overflow](https://stackoverflow.com/) because it's likely someone else will run into the same thing.


## Performance Tips
### Julia is supposed to be super fast why is my code so slow (& 1000 other similar questions)
The answer to this question is nearly always something related to [Type Stability](https://docs.julialang.org/en/stable/manual/performance-tips/#Write-"type-stable"-functions-1) or [Un-necessary Memory Allocation](https://docs.julialang.org/en/stable/manual/performance-tips/#Pre-allocating-outputs-1).

Resources:
[The Julia Docs](https://docs.julialang.org/en/stable/manual/performance-tips)


## Replacing MATLAB with Julia
Julia and MATLAB syntax is (on the surface) quite similar. So similar in fact that you can almost copy & paste your matlab code, change a few ( to [ and your code might run all the way through (check out the link below for an auto-translator). But to really take advantage of Julia you'll need to change a few more things.

Resources:
[The Julia Docs](https://docs.julialang.org/en/stable/manual/noteworthy-differences/#Noteworthy-differences-from-MATLAB-1) - Noteworthy Differences from MATLAB
[MATLAB2Julia Translator](http://sciencecow.mit.edu/matlab-to-julia/) - Automatically tries to translate your matlab code into Julia.

## What packages should I use for ... ?
Because its so easy to publish packages using Julia there are usually multiple packages to choose from for doing the same thing. Below we reccommend the most stable & performant packages that are best for most peoples needs. If you have super specific needs then you might need to do a bit more digging.

- Plotting - [Plots]()
- DataFrames - [DataFrames](
- Image Processing - [Images] & other packages by @tholy
- Digital Signal Processing - [DSP]()
- Baysian Inference - ()
- Dimensionality Reduction (PCA etc.) - [MultivariateStats]()
- HypothesisTesting - [HypothesisTests]()
