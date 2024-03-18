# Rust Editor

## Requirements

```
$ rustup install nightly
```

## Operations

```
$ cargo run
```

## Specifications

### Commands

| Mode            | Key            | Note                  |
|-----------------|----------------|-----------------------|
| Normal / Visual | [count]h       | move left             |
| Normal / Visual | [count]j       | move down             |
| Normal / Visual | [count]k       | move up               |
| Normal / Visual | [count]l       | move right            |
| Normal          | [count]i       | switch to insert mode |
| Normal          | [count]a       | switch to insert mode |
| Normal          | u              | undo                  |
| Normal          | ctrl + r       | redo                  |
| Normal          | [count]x       | cut word              |
| Normal          | c{motion}      | change text           |
| Normal          | .              | execute last command  |
| Normal / Visual | [count]f{char} | move cursor on char   |
| Insert / Visual | Esc            | switch to normal mode |
| Command         | w [file]       | write file            |
| Command         | q              | quit                  |

### Motions

- cursor moving
- text object
    - inner word
    - around word
    - inner {char}
    - around {char}
