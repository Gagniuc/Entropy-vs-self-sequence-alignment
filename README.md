# Entropy vs self sequence alignment

<i>Entropy vs self sequence alignment</i> is a Javascript implementation of a scanner that makes a comparison between two methods, namely between Shanon entropy (Information entropy) and self-sequence alignment (Information content). Information entropy (IE) and Information content (IC) are two methods that quantitatively measure information. Here, these parallel results are shown in the form of signals above a given sequence (<i>z</i>). To obtain these signals, the contents of sliding windows are analyzed with the two methods and the values are stored as discrete signals inside a vector. Specifically, here both measure the information in the sequence of characters stored in a variable called <i>z</i>:

```js
var z = "AAAAAACAGGTGAGTAAAAAAAA";
```

Thus, this comparison is made to highlight the qualitative differences between information entropy and the new method of information content described as a primary source in the book entitled <i>[Algorithms in Bioinformatics: Theory and Implementation](https://books.google.ro/books?id=y1I5EAAAQBAJ&printsec=frontcover&source=gbs_ge_summary_r&cad=0#v=onepage&q&f=false)</i>. Below, the black line represents the Shannon Entropy and the red line represents the information content over the <i>z</i> sequence. Note that this version contains the minimum code for such an implementation in order to be used by different parties in their endeavors. However, an advanced javascript implementation of this scanner is shown here in [Information content vs Information entropy](https://github.com/Gagniuc/Information-Content-vs-Information-Entropy). For those interested in the chart of the implementation, please downloaded it from [here](https://github.com/Gagniuc/World-smallest-js-chart-v1.0).

# Live demo

https://gagniuc.github.io/Entropy-vs-self-sequence-alignment/

# Screenshot

<kbd><img src="https://github.com/Gagniuc/Entropy-vs-self-sequence-alignment/blob/main/img/Entropy%20vs%20self%20sequence%20alignment.png?raw=true" /></kbd>

# References

- <i>Paul A. Gagniuc. Algorithms in Bioinformatics: Theory and Implementation. John Wiley & Sons, Hoboken, NJ, USA, 2021, ISBN: 9781119697961.</i>
