# `module Hash`

Provides
- `Hash` trait, which converts a value to a hash.
- `type HashKey = Hash + Eq` trait alias.
- Hashing for basic types.

# Types and aliases

# Traits and aliases

## `namespace Hash`

### `trait a : Hash`

Hashable types.

#### method `hash : a -> Std::U64`

# Trait implementations

### `impl [a : Hash::Hash, b : Hash::Hash] (a, b) : Hash::Hash`

### `impl [a : Hash::Hash] Std::Array a : Hash::Hash`

### `impl Std::I64 : Hash::Hash`

### `impl Std::String : Hash::Hash`

### `impl Std::U64 : Hash::Hash`

### `impl Std::U8 : Hash::Hash`

# Values

## `namespace Hash::Hash`

### `hash : [a : Hash::Hash] a -> Std::U64`