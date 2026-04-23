MANIRAFASHA Aphrodice project
# bridge__led_lighting_22-04-2026
a program to lighting three LEDs
the components used are:
arduino
LEDs
jumper wires
bleadboads
pushbutton
code
computer
usb cable
<img width="1366" height="544" alt="Powerful Jaban-Hillar" src="https://github.com/user-attachments/assets/280f43fc-926a-4cd9-859d-5c244582d172" />


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
