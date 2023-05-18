# DAY 2
## EXPERIMENT NO 1
```
LED BULB
```
[tinker this](https://www.tinkercad.com/things/erXxVnNZ8T6-bodacious-uusam/editel)
![LED](https://github.com/DevanaKD/10-DAYS-INTERNSHIP/blob/main/img/day2exp1.png)

# EXPERIMENT NO 2
```
LED BULB ( USING SWITCH)
```
![LED](https://github.com/DevanaKD/10-DAYS-INTERNSHIP/blob/main/img/day2expt2.png)


# DAY 3
```
## experiment no 1

AND GATE
```

[tinker this](https://www.tinkercad.com/things/hzxRUv2JRk9-fantastic-bombul)
```
### BLINKING OF LED USING  ARDUINO
```

[arduino](https://www.tinkercad.com/things/3tXXgDRUF0m-mighty-hango-densor/editel?tenant=circuits)

PROGRAM

```
// C++ code
//
void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
```
# DANCING LED
```
### Led
```
[led](https://www.tinkercad.com/things/3tXXgDRUF0m-mighty-hango-densor/editel)

PROGRAM

```

// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  digitalWrite(12, LOW);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrite(13, LOW);
  digitalWrite(12, HIGH);
  delay(300); // Wait for 1000 millisecond(s)
}
```
# 7 SEGEMENT LED

[7 segement](https://www.tinkercad.com/things/4tx06v0p1Wu-powerful-amur/editel)
```
```
# DAY 5

# POTENTIOMETER 
[ANALOG SIGNAL](https://www.tinkercad.com/things/aCe0HZnyCx7-magnificent-amberis-blad/editel?tenant=circuits)


PROGRAM
```
const int potpin =A0;

void setup()
{
Serial.begin(9600);
}

void loop()
{
  int potValue = analogRead(potpin);
  Serial.println(potValue);
  delay(100);
}
```
# DISPLAY OF 7 SEGEMENT 

DISPLAY OF 7 SEGEMENT BY USIND ARDUINO
 
[7 SEGEMENT]{https://www.tinkercad.com/things/5BDLt41DD6i-fantastic-maimu-wolt/editel}

PROGRAM

```
// C++ code
//
void setup()
{
  pinMode(2, OUTPUT);
  pinMode(3, OUTPUT);
  pinMode(4, OUTPUT);
  pinMode(5, OUTPUT);
  pinMode(6, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(13, OUTPUT);
}

void loop()
{
  digitalWrite(2, HIGH);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(12, LOW);
  digitalWrite(13, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(2, LOW);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(5, LOW);
  digitalWrite(6, LOW);
  digitalWrite(12, LOW);
  digitalWrite(13, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(2, HIGH);
  digitalWrite(3, HIGH);
  digitalWrite(4, LOW);
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(12, HIGH);
  digitalWrite(13, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(2, HIGH);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(5, HIGH);
  digitalWrite(6, LOW);
  digitalWrite(12, HIGH);
  digitalWrite(13, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(2, LOW);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(5, LOW);
  digitalWrite(6, LOW);
  digitalWrite(12, HIGH);
  digitalWrite(13, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(2, HIGH);
  digitalWrite(3, LOW);
  digitalWrite(4, HIGH);
  digitalWrite(5, HIGH);
  digitalWrite(6, LOW);
  digitalWrite(12, HIGH);
  digitalWrite(13, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(2, HIGH);
  digitalWrite(3, LOW);
  digitalWrite(4, HIGH);
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(12, HIGH);
  digitalWrite(13, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(2, HIGH);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(5, LOW);
  digitalWrite(6, LOW);
  digitalWrite(12, LOW);
  digitalWrite(13, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(2, HIGH);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(12, HIGH);
  digitalWrite(13, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(2, HIGH);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(5, HIGH);
  digitalWrite(6, LOW);
  digitalWrite(12, HIGH);
  digitalWrite(13, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
}
```








