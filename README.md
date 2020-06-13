# hello-world
Test y todo lo que necesite de notas y autoarranque

**el preeview se puede volver loco , al parecer tiene problemas de buffer (no borra items)**

- [ ] ver si la app de windows lo hace mejor
  - [ ] lo mismo en linux

- [ ] ?jalan rapido/lento?
- [ ] ?porque hay editores de terceros y hasta pagos?
    - [ ] ?herramientas de autor?
    - [ ] ?documentos academicos/cientificos?

[aca tambien jalan los enlaces?](https://guides.github.com/activities/hello-world/)

listas anidadas

ordenadas:

1. Item 1
2. Item 2
3. Item 3
   * Item 3a
   * Item 3b`


desordenadas:

* Item 1
* Item 2
  * Item 2a
  * Item 2b

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

```pascal
procedure TForm1.Button1Click(Sender: TObject);
begin
   if SendMessage(ComboBox2.Handle, CB_GETDROPPEDSTATE, 0, 0) <> 1 then
    SendMessage(ComboBox2.Handle, CB_SHOWDROPDOWN, 1, 0);
end;
```

```c++
//arduino , c++
void setup()
{
  Serial.begin(9600);      // connect to the serial port
  pinMode(8, OUTPUT);         // input
  pinMode(9, OUTPUT);         // input
  digitalWrite(8, LOW);     // low level
  digitalWrite(9, LOW);     // low level

}

// returns capacity on one input pin
// pin must be the bitmask for the pin e.g. (1<<PB0)
char getcap(char pin)
{
  char i = 0;
  KEYDDR &= ~pin;          // input
  KEYPORT |= pin;          // pullup on
  for(i = 0; i < 16; i++)
    if( (KEYPIN & pin) ) break;
  KEYPORT &= ~pin;         // low level
  KEYDDR |= pin;           // discharge
  return i;
}
```

```python
#Python...
def addLine(event):
    global lastx, lasty
    x, y = canvas.canvasx(event.x), canvas.canvasy(event.y)
    canvas.create_line((lastx, lasty, x, y), fill=color, width=5, tags='currentline')
    lastx, lasty = x, y

def doneStroke(event):
    canvas.itemconfigure('currentline', width=1)

canvas.bind("<Button-1>", xy)
canvas.bind("<B1-Motion>", addLine)
canvas.bind("<B1-ButtonRelease>", doneStroke)
```



ooohh el modo de edicion a pantalla completa esta BIENNNN

Y tiene un tema dark, me enamore...
