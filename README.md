# 9 Puzzle Quine

This is a playable quine, a program that outputs the source code itself.

# How to Play

```
$ php 9.php <operation>
```

Available operations:

* h: Move left
* j: Move down
* k: Move up
* l: Move right

An invalid operation is just ignored.

## How to Shuffle

There is no option to shuffle. Do manually like this:

```
$ cat 9.php | php -- l | php -- h | php -- k | ...
```
