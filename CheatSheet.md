<h1 align=center>Cheat Sheet</h1>

Primitive Types:
  + INTEGER:
    + `byte` (8bit),
    + `short` (16bit),
    + `int` (32bit),
    + `long` (64bit),
  + DECIM:
    + `float` (32bit),
    + `double` (64bit),
  + OTHER:
    + `boolean` (1bit),
    + `char` (Unicode)
  + HEX:
    + 0x0AF,
  + BINARY:
    + 0b01101,
  + LONG:
    + 1234567890123L
  + CHAR:
    + `a` `\n` `\t` `\\` `\'` `\”`

Primitive Operators
  + Assignment Operator: [ variable **operator** value ]
      + `=` `+=` `-=` `*=` `/=` `%=`
      + `&=` `^=` `|=` `<<=` `>>=` `>>>=`
  + Unary Operators:
    + `+` `-` `++` `--`
  + Binary Operators:
    + `+` `-` `*` `/` `%`
  + Comparision:
    + `==` `!=` `>` `>=` `<` `<=` `instanceof`
  + Binary:
    + `!` `&&` `||`
  + Bitwise:
    + `~` `&` `^` `|` `<<` `>>` `>>>`
  + Ternary:
    + `boolean ? trueValue : falseValue`

Casting, Conversion:  
 + (type)value
 + type variable = WrapperClass . parseType( value   ) ;
 + int    i      = Integer      . parseInt ( hex, 16 ) ; // from Hex
 + String hex    = Integer      . toString ( i,   16 ) ; // to   Hex
 + String str    = `""+ value` | `toString()`
 //Previous lines work w/ binary, other bases