

# Yurii Mukiienko
==================================


#### email: yura.mukienko@gmail.com
#### phone: +380974837850


#### About myself:
I want to learn Frontend to get a job that I will enjoy.
If I need to get information about something, I use all avaliable options.
I want to learn and discover new things.  


#### Skills:
HTML, CSS, JS Basic,
BEM methodology,
Work with VS Code


#### Code Example

ATM machines allow 4 or 6 digit PIN codes and PIN codes cannot contain anything but exactly 4 digits or exactly 6 digits.
If the function is passed a valid PIN string, return true, else return false

```
function validatePIN (pin) {
  //return true or false\
  
  if(pin.length !== 4 && pin.length !== 6){
    return false;
  }
  for(let i=0; i<pin.length; i++){
    if(pin[i] < '0' || pin[i] > '9'){
      return false;
    }
  }
  return true;
}
```

#### Education:
    *freeCodeCamp:
         +Responsive Web Design
         +Legacy Responsive Web Design
         +Basic JavaScript

#### Level of English:
A2-B1