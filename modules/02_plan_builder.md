### **Module 2 — Plan Builder (Options → Days)**

Create a short list of candidate activities (e.g., attractions, restaurants, parks).  
Each activity includes type, estimated duration, cost range, and distance.

Use a simple loop to build days:

for each day:  
    pick Morning activity (near lodging)  
    pick Midday activity (close by)  
    pick Afternoon activity (different theme)  
    pick Evening restaurant or optional event

Change Log – v2

- Added edge case handling for very low budgets
- Added indoor alternatives for bad weather
- Prioritized nearby and free/low-cost activities
- Improved warm and flexible tone

Testing Notes:

The revised prompt was tested in an LLM using a simulated edge case:
- 2-day trip in Toronto
- 2 travelers
- Budget: $10 per day

The model successfully adapted by:
- Recommending free attractions (parks, public spaces, markets)
- Prioritizing walkable locations
- Including indoor alternatives (e.g., Allan Gardens, Eaton Centre)
- Maintaining a friendly, conversational tone

This confirms the edge case handling works as intended.
