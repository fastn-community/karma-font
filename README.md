# Karma: FPM Font Package

This repository contains a [fpm font package](https://fpm.dev/featured/fonts/) containing [Google Font: 
Karma](https://fonts.google.com/specimen/Karma/about).

Karma is an Open Source multi-script typeface supporting both the Devanagari and the Latin script. The family was developed for use in body text on screen, and five fonts are available. The characters for both scripts feature a construction style that tends toward the monolinear. The Latin script component has serif letters. Both these, and the stroke terminals in the Devanagari letterforms are generally rounded in Karma’s design.

Karma’s characters are economic in width, and the Latin sports a tall x-height. Although the knotted terminals in the Devanagari letterforms are closed, the general feeling of the Devanagari character set is open and airy. See the design of the ख (kha), छ (cha) and ध (dha), for example.

Joana Correia designed Karma for the Indian Type Foundry, who first published the fonts in 2014.


Designers: [Indian Type Foundry](http://www.indiantypefoundry.com/), Principal design

## How To Use This Font In Your FPM Package:

[Read the docs and demo](https://fifthtry.github.io/karma-font).

TLRD:

Include fifthtry.github.io/karma-font package into `FPM.ftd` file:

```ftd
-- fpm.dependency: fifthtry.github.io/karma-font
```

Inside your `FPM/config.ftd` use the font:

```ftd
-- import: fifthtry.github.io/karma-font as karma

-- fpm.type.headline-small.font: $karma.fonts.Karma
```

Now if in any file you do:

```ftd
-- ftd.text:
role: $fpm.type.headline-small
```

You will see the `Karma` font.

## 👀 Want to learn more?

Feel free to check [our documentation](https://fpm.dev/) or jump into our [FifthTry Discord 
server](https://discord.gg/bucrdvptYd).

## License

Since Karma Font is under [Open Font Licence](https://fonts.google.com/specimen/Arya/about), this FPM wrapper is also
under [Open Font License](LICENSE).




