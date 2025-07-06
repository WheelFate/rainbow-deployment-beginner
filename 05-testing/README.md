# 🧪 Testing Rainbow Deployment

Once you’ve built and connected all three versions of the app along with your rainbow-router, it’s time to test that everything actually works!

This step helps confirm:
- Versions are correctly deployed ✅
- The router sends users to different versions ✅
- Our traffic simulation behaves as expected ✅

---

## ✅ How to Test the Router

1. Open this 👇  
   🎯 [Rainbow Router](https://replit.com/@iamdakheel/rainbow-router)
   
2. Refresh the page multiple times (or open it in Incognito)
   
3. You should land on:
   - `rainbow-v1` (about 50% of the time)
   - `rainbow-v2` (about 30% of the time)
   - `rainbow-v3` (about 20% of the time)

4. Check the Replit links it sends you to — they should all be styled differently so you know which is which.

---

## 🔁 Optional Manual Check (For Fun)

| Test # | Resulting Version |
|--------|-------------------|
| 1      | V1 🌱              |
| 2      | V3 🦄              |
| 3      | V2 🚀              |
| 4      | V1 🌱              |
| ...    | ...               |

Make your own mini test table and see if the percentages roughly match over time! 🧮

---

## ⚙️ What You Can Do Next

- Change the percentage split in the router (`random < 0.5`, etc.)
- Add simple logging or page visit counters (advanced)
- Break something on purpose (!) in one version — then test rollback by removing it from the router 😅

---

🧠 Good testing means confidence when you go to a real CI/CD system later!
