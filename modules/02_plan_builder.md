### **Module 2 — Plan Builder (Options → Days)**
Change Log (03_guardrails-debug-v2)

Refined Module 03 based on AI critique: 
  added indoor backup 
  add format check.

Create a short list of candidate activities (e.g., attractions, restaurants, parks).  
Each activity includes type, estimated duration, cost range, and distance.

Use a simple loop to build days:

for each day:  
    pick Morning activity (near lodging)  
    pick Midday activity (close by)  
    pick Afternoon activity (different theme)  
    pick Evening restaurant or optional event
