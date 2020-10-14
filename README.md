# MykiBalance  
Fetch Myki Balance with Scriptable, add to iOS 14 Widget.    


**Important! This Widget is not affiliated to PTV or Myki. For personal use only.**

This script does not suport Myki Pass atm as I do not have a Myki Pass. No idea about the myki pass data will be like.  
For the same reason, the passenger type (Full Fare, Concession, Child etc) may not accurate, feel free to let me know how to fix them

## How to add MykiBalance Widget to my iOS14?

1. Download [Scriptable](https://apps.apple.com/us/app/scriptable/id1405459188?ign-mpt=uo%3D4) from App Store

2. Add new Script on Scriptable, copy Everything in `MykiBalance.js` and paste to your new Script

4. Replace "Your myki card" with your Card number.  
   eg. `let cardNumber = "308425123456789"`

5. Run the Code, you may see your Balance now (if not, check your card number again). You are almost there.

5. Go to your Widgets library and find Scriptable, make sure pick the Middle one and Add Widget to your home screen

6. Long press the Widget and go Edit Widget, Choose the `Script` you Added, set `When Interacting` to `Run Script`, so you can manually update your balance by tapping the widget. Left `Parameter` empty like below: <br />  
         
![setting](https://github.com/imchlorine/MykiBalance/blob/main/settings.jpg)


7. Now you may see the Magic, Enjoy!

  * Tips: Tap the Money on the Widget (Not the Widget itself, the money or the up-right side Balance Status), you will be redirect to Official Myki Topup Website in Chrome (you need Chrome installed on your phone).


#### You can even run the script on Shortcuts. eg. Ask siri to check you balance, Set a regular time to Check you balance and more!!!
   
