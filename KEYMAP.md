# Kyria rev2 — keymap reference
Reverse-mapped for a **German (de nodeadkeys)** OS layout. The OS is German on
every machine but the keycaps/diagram show US-QWERTY, so each binding emits the
German-physical key that produces the US character shown below. Letters (except
y/z), digits, modifiers, arrows, F-keys, media and bluetooth are unchanged.
`···` = transparent (falls through) · blank = none · diagrams mirror the physical board.
## Layers
### BASE (0) — default
```
╭────────────────────────────────────╮                         ╭────────────────────────────────────╮
│ ESC    Q     W     E     R     T   │                         │  Y     U     I     O     P    BSPC │
│ TAB    A     S     D     F     G   ╰───────────╮ ╭───────────╯  H     J     K     L     ;     '   │
│ GUI    Z     X     C     V     B     [     !   │ │  |     ]     N     M     ,     .     /     =   │
╰─────────────────╮ CTRL  ALT   SHFT  RET    @   │ │  ?    SPC   ALT   CTRL  MUTE ╭─────────────────╯
                  ╰──────────────────────────────╯ ╰──────────────────────────────╯
hold: RET→NUM · @→FUN · ?→UMLAUT · SPC→NAV
```
### NAV (1) — navigation
```
╭────────────────────────────────────╮                         ╭────────────────────────────────────╮
│ ···                                │                         │       PgUp   ↑    PgDn             │
│ ···                                ╰───────────╮ ╭───────────╯ Home   ←     ↓     →    End        │
│ ···                                 ···   ···  │ │ ···   ···    ↖     ↞           ↠     ↘         │
╰─────────────────╮ ···   ···   ···   ···   ···  │ │ ···   ···   ···   ···   ···  ╭─────────────────╯
                  ╰──────────────────────────────╯ ╰──────────────────────────────╯
··· transparent · ↞/↠ Ctrl+←/→ word · ↖/↘ Ctrl+Home/End
```
### NUM (2) — symbols + numpad
```
 ╭────────────────────────────────────╮                         ╭────────────────────────────────────╮
 │  ]     !     @     #     $     %   │                         │  *     7     8     9     =     .   │
 │  [     &     ^     (     )     |   ╰───────────╮ ╭───────────╯  +     4     5     6     ;     :   │
 │ ···    ~     `     <     >     _     {     "   │ │ ···    }     -     1     2     3     /     \   │
 ╰─────────────────╮ ···   ···   ···   ···   ···  │ │ ···   ···    0     ,    ···  ╭─────────────────╯
                   ╰──────────────────────────────╯ ╰──────────────────────────────╯
··· transparent
```
### FUN (3) — F-keys + media
```
╭────────────────────────────────────╮                         ╭────────────────────────────────────╮
│ ···   F21   F22   F23   F24   ScLk │                         │ Vol+   F7    F8    F9   F12   Prev │
│ ···   F17   F18   F19   F20   PrSc ╰───────────╮ ╭───────────╯ Vol-   F4    F5    F6   F11   Play │
│ ···   F13   F14   F15   F16   Ins   ···   ···  │ │ ···   ···   Mute   F1    F2    F3   F10   Next │
╰─────────────────╮ ···   ···   ···   ···   ···  │ │ ···   ···   ···   ···   ···  ╭─────────────────╯
                  ╰──────────────────────────────╯ ╰──────────────────────────────╯
··· transparent
```
### UMLAUT (4) — umlauts
```
╭────────────────────────────────────╮                         ╭────────────────────────────────────╮
│ ···    Ä     Ö     Ü     €    ···  │                         │ ···   ···   ···   ···   ···   ···  │
│ ···    ä     ö     ü     ß    ···  ╰───────────╮ ╭───────────╯ ···   ···   ···   ···   ···   ···  │
│ ···   ···   ···   ···   ···   ···   ···   ···  │ │ ···   ···   ···   ···   ···   ···   ···   ···  │
╰─────────────────╮ ···   ···   ···   ···   ···  │ │ ···   ···   ···   ···   ···  ╭─────────────────╯
                  ╰──────────────────────────────╯ ╰──────────────────────────────╯
··· transparent · hold ? (right thumb)
```
## Hold-taps (thumb cluster)
| key | tap | hold (layer) |
|-----|-----|--------------|
| 43 | RET | NUM (2) |
| 44 | @ | FUN (3) |
| 45 | ? | UMLAUT (4) |
| 46 | SPACE | NAV (1) |
## Combos (50 ms timeout)
### Symbols
| combo | keys | types |
|-------|------|-------|
| combo_grave | 0 + 13 | ` |
| combo_exclamation | 1 + 13 | ! |
| combo_at | 2 + 14 | @ |
| combo_hash | 3 + 15 | # |
| combo_dollar | 4 + 16 | $ |
| combo_percent | 5 + 17 | % |
| combo_caret | 6 + 18 | ^ |
| combo_ampersand | 7 + 19 | & |
| combo_asterisk | 8 + 20 | * |
| combo_left_parenthesis | 9 + 21 | ( |
| combo_right_parenthesis | 10 + 22 | ) |
| combo_minus | 11 + 23 | - |
| combo_tilde | 12 + 24 | ~ |
| combo_plus | 21 + 37 | + |
| combo_equal | 22 + 38 | = |
| combo_underscore | 23 + 39 | _ |

### Bluetooth
| combo | keys | action |
|-------|------|--------|
| combo_clear_bt | 30 + 31 | BT clear profile |
| combo_bt_prev | 43 + 44 | BT previous profile |
| combo_bt_next | 45 + 46 | BT next profile |

## Key positions (for editing combos)
```
  ╭────────────────────────╮                 ╭────────────────────────╮
  │  0   1   2   3   4   5 │                 │  6   7   8   9  10  11 │
  │ 12  13  14  15  16  17 ╰───────╮ ╭───────╯ 18  19  20  21  22  23 │
  │ 24  25  26  27  28  29  30  31 │ │ 32  33  34  35  36  37  38  39 │
  ╰───────────╮ 40  41  42  43  44 │ │ 45  46  47  48  49 ╭───────────╯
              ╰────────────────────╯ ╰────────────────────╯
```
## Reverse-map (US char → binding under de nodeadkeys)
```y->Z   z->Y    "->AT   #->BSLH   &->CARET   '->PIPE   (->STAR   )->LPAR*->LS(RBKT)   +->RBKT   -->FSLH   /->AMPS   :->GT   ;->LT   =->LS(N0)?->UNDER   @->RA(Q)   [->RA(N8)   \->RA(MINUS)   ]->RA(N9)   ^->GRAVE_->LS(FSLH)   `->PLUS   {->RA(N7)   |->RA(INT1)   }->RA(N0)   ~->RA(RBKT)<->INT1   >->LS(INT1)ä->SQT   ö->SEMI   ü->LBKT   ß->MINUS   Ä->LS(SQT)   Ö->LS(SEMI)   Ü->LS(LBKT)   €->RA(E)```