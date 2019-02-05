# Neo 2 for ErgoDox on QWERTY

# Description

The Neo layout is an optimized German keyboard layout developed by the 
Neo Users Group, supporting many Latin-based alphabets. The positions 
of the letters are not only optimized for German letter frequency, 
but also for typical groups of two or three letters.  English is 
considered a primary target as well. 

The design tries to enforce the alternating usage of both hands to 
increase typing speed  and incorporates ideas from de-ergo and other 
ergonomic layouts. High frequency keys are placed in the home row. 
The current layout Neo 2.0 has unique features making it suited for 
many target groups such as programmers, mathematicians, scientists or 
LaTeX authors.

Neo is grouped into six layers, each dedicated to a special purpose.

# Layers

At the core this is a Neo 2.0 layout adjusted for the Ergodox Infinity. 
The keymap is laid out expecting a macOs using the US QWERTY or ABC 
Extended layout. 

[Layer 1](#layer-1) Lowercase, upppercase and typographical  characters

[Layer 2](#layer-2) Special characters for programming

[Layer 3](#layer-3) WASD-like movement keys and number block

[Layer 4](#layer-4) Greek characters

[Layer 5](#layer-5) Mathematical symbols and Greek uppercase characters

[Layer 6](#layer-6) Ergodox Infinity US QWERTY layout

[Layer 7](#layer-7) Function keys

## Legend

 * Keys marked with `----` are dead keys.
 * Blank keys are transparent and fall through to lower levels.

## Layer 1

This layer implements NEO layers 1 and 2.

```
,--------------------------------------------------.           ,--------------------------------------------------.
|  ----  |  1/° |  2/§ |  3/  |  4/» |  5/« |  ESC |           | US_1 |  6/$ |  7/€ |  8/„ |  9/“ |  0/” |  -/—   |
|--------+------+------+------+------+-------------|           |------+------+------+------+------+------+--------|
|  TAB   |   X  |   V  |   L  |   C  |   W  | LCTL |           | RCTL |   K  |   H  |   G  |   F  |   Q  |   ß    |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|  NEO_3 |   U  |   I  |   A  |   E  |   O  |------|           |------|   S  |   N  |   R  |   T  |   D  |   Y    |
|--------+------+------+------+------+------| LALT |           | RALT |------+------+------+------+------+--------|
| LSHIFT |   Ü  |   Ö  |   Ä  |   P  |   Z  |      |           |      |   B  |   M  |  ,/– |  ./• |   J  | RSHIFT |
`--------+------+------+------+------+-------------'           `-------------+------+------+------+------+--------'
  | ---- | ---- | LCTL | LALT | LGUI |                                       | RGUI | Left | Down |  Up  | Right|
  `----------------------------------'                                       `----------------------------------'
                                       ,-------------.       ,-------------.
                                       | FKEYS| Home |       | PgUp | FKEYS|
                                ,------|------|------|       |------+------+------.
                                | Back-|      | End  |       | PgDn |      |      |
                                | space|Delete|------|       |------| Enter|Space |
                                |      |      | NEO_4|       | NEO_4|      |      |
                                `--------------------'       `--------------------'
```

## Layer 2

This layer implements NEO layer 3.


```
,--------------------------------------------------.           ,--------------------------------------------------.
|  ----  | ---- | ---- | ---- |   ›  |   ‹  |      |           |      |   ¢ 	|   ¥  |   ‚  |   ‘  |   ’  |  ----  |
|--------+------+------+------+------+-------------|           |------+------+------+------+------+------+--------|
|  ----  |   …  |   _  |   [  |   ]  |   ^  |      |           |      |   !  |   <  |   >  |   =  |   &  |  ----  |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|        |   \  |   /  |   {  |   }  |   *  |------|           |------|   ?  |   (  |   )  |   -  |   :  |   @    |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|        |   #  |   $  |   |  |   ~  |   `  |      |           |      |   +  |   %  |   "  |   '  |   ;  |        |
`--------+------+------+------+------+-------------'           `-------------+------+------+------+------+--------'
  |      |      |      |      |      |                                       |      |      |      |      |      |
  `----------------------------------'                                       `----------------------------------'
                                       ,-------------.       ,-------------.
                                       |      |      |       |      |      |
                                ,------|------|------|       |------+------+------.
                                |      |      |      |       |      |      |      |
                                |      |      |------|       |------|      |      |
                                |      |      |      |       |      |      |      |
                                `--------------------'       `--------------------'
```

## Layer 3

This layer implements NEO layer 4.

```
,--------------------------------------------------.           ,--------------------------------------------------.
|  ----  |   ª  |   º  | ---- |   ·  |   £  |      |           |      | ---- | Tab  |   /  |   *  |   -  |  ----  |
|--------+------+------+------+------+-------------|           |------+------+------+------+------+------+--------|
|  ----  | PgUp |   ⌫  |  Up  |   ⌦  | PgDn |      |           |      |   ¡  |   7  |   8  |   9  |   +  |   –    |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|        | Home | Left | Down | Right| End  |------|           |------|   ¿  |   4  |   5  |   6  |   ,  |   .    |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|        | Esc  | Tab  | Ins  |Return| ---- |      |           |      |   :  |   1  |   2  |   3  |   ;  |        |
`--------+------+------+------+------+-------------'           `-------------+------+------+------+------+--------'
  |      |      |      |      |      |                                       |      |   0  |      |      |      |
  `----------------------------------'                                       `----------------------------------'
                                       ,-------------.       ,-------------.
                                       |      |      |       |      |      |
                                ,------|------|------|       |------+------+------.
                                |      |      |      |       |      |      |      |
                                |      |      |------|       |------|      |      |
                                |      |      |      |       |      |      |      |
                                `--------------------'       `--------------------'
```

## Layer 4

This layer is currently empty/reserved for NEO layer 5.

```
,--------------------------------------------------.           ,--------------------------------------------------.
|  ----  | ---- | ---- | ---- | ---- | ---- |      |           |      | ---- | ---- | ---- | ---- | ---- |  ----  |
|--------+------+------+------+------+-------------|           |------+------+------+------+------+------+--------|
|  ----  | ---- | ---- | ---- | ---- | ---- |      |           |      | ---- | ---- | ---- | ---- | ---- |  ----  |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|        | ---- |  ----| ---- | ---- | ---- |------|           |------| ---- | ---- | ---- | ---- | ---- |  ----  |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|        | ---- |  ----| ---- | ---- | ---- |      |           |      | ---- | ---- | ---- | ---- | ---- |        |
`--------+------+------+------+------+-------------'           `-------------+------+------+------+------+--------'
  |      |      |      |      |      |                                       |      |      |      |      |      |
  `----------------------------------'                                       `----------------------------------'
                                       ,-------------.       ,-------------.
                                       |      |      |       |      |      |
                                ,------|------|------|       |------+------+------.
                                |      |      |      |       |      |      |      |
                                |      |      |------|       |------|      |      |
                                |      |      |      |       |      |      |      |
                                `--------------------'       `--------------------'
```

## Layer 5

This layer is currently empty/reserved for NEO layer 6.

```
,--------------------------------------------------.           ,--------------------------------------------------.
|  ----  | ---- | ---- | ---- | ---- | ---- |      |           |      | ---- | ---- | ---- | ---- | ---- |  ----  |
|--------+------+------+------+------+-------------|           |------+------+------+------+------+------+--------|
|  ----  | ---- | ---- | ---- | ---- | ---- |      |           |      | ---- | ---- | ---- | ---- | ---- |  ----  |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|        | ---- |  ----| ---- | ---- | ---- |------|           |------| ---- | ---- | ---- | ---- | ---- |  ----  |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|        | ---- |  ----| ---- | ---- | ---- |      |           |      | ---- | ---- | ---- | ---- | ---- |        |
`--------+------+------+------+------+-------------'           `-------------+------+------+------+------+--------'
  |      |      |      |      |      |                                       |      |      |      |      |      |
  `----------------------------------'                                       `----------------------------------'
                                       ,-------------.       ,-------------.
                                       |      |      |       |      |      |
                                ,------|------|------|       |------+------+------.
                                |      |      |      |       |      |      |      |
                                |      |      |------|       |------|      |      |
                                |      |      |      |       |      |      |      |
                                `--------------------'       `--------------------'
```

## Layer 6

A bare bones implementation of the default Ergodox Infinity layout.

```
,--------------------------------------------------.           ,--------------------------------------------------.
|   =    |   1  |   2  |   3  |   4  |   5  | ESC  |           | NEO_1|   6  |   7  |   8  |   9  |   0  |    -   |
|--------+------+------+------+------+-------------|           |------+------+------+------+------+------+--------|
|   \    |   Q  |   W  |   E  |   R  |   T  | ---- |           |   [  |   Y  |   U  |   I  |   O  |   P  |    ]   |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|  TAB   |   A  |   S  |   D  |   F  |   G  |------|           |------|   H  |   J  |   K  |   L  |   ;  |    '   |
|--------+------+------+------+------+------| ---- |           | ---- |------+------+------+------+------+--------|
| LSHIFT |   Z  |   X  |   V  |   B  |   M  |      |           |      |   N  |   M  |   ,  |   .  |   /  | RSHIFT |
`--------+------+------+------+------+-------------'           `-------------+------+------+------+------+--------'
  | LGUI |   `  | ---- | ---- | FKEYS|                                       | Left | Down |  Up  | Right| RGUI |
  `----------------------------------'                                       `----------------------------------'
                                       ,-------------.       ,-------------.
                                       | LCTRL| LALT |       | RALT | RCTRL|
                                ,------|------|------|       |------+------+------.
                                |      |      | HOME |       | PGUP |      |      |
                                | BKSP | DEL  |------|       |------| ENTR | SPCE |
                                |      |      | END  |       | PGDN |      |      |
                                `--------------------'       `--------------------'
```

## Layer 7

This layer implements function and multimedia keys.

```
,--------------------------------------------------.           ,--------------------------------------------------.
|        |  F1  |  F2  |  F3  |  F4  |  F5  |  F11 |           |  F12 |  F6  |  F7  |  F8  |  F9  |  F10 |        |
|--------+------+------+------+------+-------------|           |------+------+------+------+------+------+--------|
|  Prev  |      |      |      |      |      |      |           |      |      |      |      |      |      |  VolUp |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|  Play  |      |      |      |      |      |------|           |------|      |      |      |      |      |  VolDn |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|  Next  |      |      |      |      |      |      |           |      |      |      |      |      |      |  Mute  |
`--------+------+------+------+------+-------------'           `-------------+------+------+------+------+--------'
  |      |      |      |      |      |                                       |      |      |      |      |      |
  `----------------------------------'                                       `----------------------------------'
                                       ,-------------.       ,-------------.
                                       |      |      |       |      |      |
                                ,------|------|------|       |------+------+------.
                                |      |      |      |       |      |      |      |
                                |      |      |------|       |------|      |      |
                                |      |      |      |       |      |      |      |
                                `--------------------'       `--------------------'
```
