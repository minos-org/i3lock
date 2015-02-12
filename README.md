## i3lock

[i3lock](https://github.com/minos-org/i3lock/) is a simple screen locker like slock. This is a custom + freeze version, refer to [i3wm](http://i3wm.org/i3lock/) for the original one and to [i3lock-color](https://github.com/eBrnd/i3lock-color) for the original i3lock-color.

<p align="center">
<img src="https://raw.githubusercontent.com/minos-org/i3lock/master/i3lock.gif" alt="i3lock"/>
</p>

## Quick start

### On Ubuntu (only LTS releases)

   ```
   $ sudo add-apt-repository ppa:minos-archive/main
   ```

2. Install:

   ```
   $ sudo apt-get update && sudo apt-get install i3lock
   ```

3. Enjoy ☺!

### On other Linux distributions

1. Type `make`

## Differences

* Indicator color scheme options
  * `--insidevercolor=rrggbbaa` -- Inside of the circle while the password is being verified
  * `--insidewrongcolor=rrggbbaa` -- Inside of the circle when a wrong password was entered
  * `--insidecolor=rrggbbaa` -- Inside of the circle while typing/idle
  * `--ringvercolor=rrggbbaa` -- Outer ring while the password is being
  * `--ringwrongcolor=rrggbbaa` -- Outer ring when a wrong password was entered
  * `--ringcolor=rrggbbaa` -- Outer ring while typing/idle
  * `--linecolor=rrggbbaa` -- Line separating outer ring from inside of the circle and delimiting the highlight segments
  * `--textcolor=rrggbbaa` -- Text ("verifying", "wrong!")
  * `--keyhlcolor=rrggbbaa` -- Keypress highlight segments
  * `--bshlcolor=rrggbbaa` -- Backspace highlight segments
* Removal of text strings


## Feedback

Please drop me an [email](mailto:m@javier.io) with your suggestions or open [an issue](https://github.com/minos-org/i3lock/issues) with your comments.
