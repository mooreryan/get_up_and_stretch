# Get Up And Stretch!

We all sit too much. Let's remember to get up and stretch more!

This uses the wacky `say` command. It chooses a different English voice and a random reminder to say to you after a specified interval of time.

## Usage

```
get_up_and_stretch <interval in minutes (default: 5)> <hours to run (default: 1)> <your name (default: Ryan, must =~ [a-zA-Z]+)> &
```

- Use the `&` to put it in the background if you want.
- The name must be only a-z or A-Z.

## Dependencies

It needs the `gshuf` program.

On a Mac, if you have `Homebrew`, run `brew install coreutils` to install `gshuf`.
