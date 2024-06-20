


<!--When/why `&impl` vs `impl`? Still not super clear on the borrowing.-->


Not sure what
```rust
let mut shopping_list: Vec<&'static str> = Vec::new();
```

Means, specifically the `'` char here.

# lifetimes
So is the idea that they life as long as whatever contains them lives? So like, they'd live inside the function they were defined, but would die as soon as that function exits (Assuming the function doesn't consume/return a lifetime, etc.)

```rust
    #[test]
    fn is_false_when_odd() {
        assert!(!is_even(5));
    }
```

I miss `assert not` :(



Why:

```rust
words.to_owned().into_iter().map(capitalize_first).collect::<string>()
```

Not:

```rust
words.to_owned().into_iter().map(capitalize_first).collect()
```

# Things to go back to

* Boxes
* Arc::

