# 🔀 Traffic Routing - Rainbow Simulation

Rainbow Deployment means running multiple versions **at the same time**, and controlling **how much traffic** goes to each one.

We built a simple JavaScript router that:
- Uses `Math.random()` to "split" traffic
- Redirects users to version 1, 2, or 3 based on simple percentages

### 🧪 Traffic Split Example:
- 50% → Version 1
- 30% → Version 2
- 20% → Version 3

### 📄 Source Code (from `rainbow-router`)
```js
const random = Math.random();
if (random < 0.5) window.location.href = v1;
else if (random < 0.8) window.location.href = v2;
else window.location.href = v3;
