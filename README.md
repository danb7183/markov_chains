# markov_chains

This script has been cloned from: https://github.com/spurll/markov . Thanks Spurl! Interesting & fun to use with multiple files and differing key sizes, char limits.

As per: https://github.com/spurll/markov

A Python program that generates strings of pseudorandom text using a simple Markov chain procedure.

Arguments

Positional:

Files: Any number of plaintext files to serve as the corpus for generating the Markov chain. (If multiple files are provided, only text generated using input from each file will be accepted. As files can be radically different sizes, and the generation is more or less random, it's recommended that you use files that are 'round about the same size, and not too many of them.)
Options:

-k, --key_size: The number of words to use to constitute the "present state" of the chain. (Defaults to 2.)
-l, --limit: A word (or character) limit for the generated text. (Defaults to 300.)
Flags:

-c, --limit_chars: Limits Markov text generation to the specified number of words (instead of characters).
-q, --strip_quotes: Removes all quotation marks from the corpus text before generating chains.
-b, --strip_parens: Removes all parentheses from the corpus text before generating chains.
-p, --paragraphs: Generates paragraph breaks (two line feeds) every few sentences.

epub2txt.py was obtained from:  https://github.com/kevinxiong/epub2txt to allow easy conversion from epub books to txts for markov chain fun :)