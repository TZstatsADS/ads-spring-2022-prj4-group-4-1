### Description for A1
#### Main idea

Try to find a representation of the data, that keeps the original shape and vector norm as much as possible, while obfuscating the sensitive information.

#### Some details

* Works on the representation of the data
* Set weights that balances classification accuracy, vector difference and probability of each entry being mapped to the prototypes
* Generated DataFrame is not interpretable, the features are just combination of prototype vectors
