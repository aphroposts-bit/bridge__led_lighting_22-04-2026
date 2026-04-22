# bridge__led_lighting_22-04-2026
a program to lighting three LEDs
the components used are:
arduino
LEDs
jumper wires
bleadboads
pushbutton
code
<img width="1366" height="544" alt="MANIRASHA Aphrodice L4 csa" src="https://github.com/user-attachments/assets/0105f1c6-397b-48d9-b26f-323417a7327f" />

int LED1=3;
int LED2=4;
int LED3=5;
int pushbutton=2;
void setup()
{
 pinMode(3,INPUT);
 pinMode(4,OUTPUT);
 pinMode(3,OUTPUT);
 pinMode(5,OUTPUT);
}

void loop()
{
  int buttonState=digitalRead(pushbutton);
    if(buttonState==HIGH){
    digitalWrite(LED1, HIGH);
    digitalWrite(LED2, HIGH);
    digitalWrite(LED3, HIGH);
  }
  else{
    digitalWrite(LED1, LOW);
    digitalWrite(LED2, LOW);
    digitalWrite(LED3, LOW);
  }
 
}
