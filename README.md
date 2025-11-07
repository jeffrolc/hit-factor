# 🎯 USPSA Hit Factor Calculator

A mobile-friendly web calculator for USPSA/IPSC competitive shooters to calculate hit factors, compare performance, and plan stage strategy.

**Live Demo:** https://jeffrolc.github.io/hit-factor/

## Features

### 📊 Hit Factor Calculator
Calculate your stage performance with the standard USPSA formula:
```
Hit Factor = Total Points ÷ Time
```

Input your:
- A-zone, C-zone, D-zone hits
- Steel targets hit
- Penalties (misses, no-shoots, procedurals)
- Time

Get instant hit factor calculation with 4 decimal precision.

### 🔍 Performance Comparison
Compare your performance against a competitor's hit factor to understand the time cost of mistakes.

See exactly how much time each mistake costs:
- Miss (10 pts penalty)
- C-zone vs A-zone (1-2 pt difference)
- D-zone vs A-zone (3-4 pt difference)
- No-shoot hit (10 pts penalty)

**How to use:** If avoiding a miss takes less time than shown, it's worth slowing down to ensure the hit.

### 🏁 Stage Strategy
Plan your approach based on the stage's high hit factor (HHF).

Input:
- Stage's high hit factor
- Round count
- Number of no-penalty targets (optional)
- Hits required per no-penalty target

Get recommendations:
- **Speed vs. Accuracy approach** (Technical, Balanced, Speed, or High-Speed stage)
- **Allowable accuracy drops** (how many C/D zone hits you can afford)
- **Time costs** (what each mistake costs in seconds)
- **No-penalty target guidance** (whether to engage or skip based on time value)

#### Stage Categories

| HHF Range | Category | Recommendation |
|-----------|----------|----------------|
| ≤ 4.4 | Technical Stage | Slow and accurate - focus on precision |
| 4.4 - 7.9 | Balanced Stage | Good accuracy with reasonable speed |
| 7.9 - 11.9 | Speed Stage | Push speed - stage rewards speed over perfection |
| > 11.9 | High-Speed Stage | Maximum speed - go fast, accept some drops |

## USPSA Scoring Reference

- **A-zone:** 5 points (universal)
- **C-zone:** Major = 4 pts, Minor = 3 pts
- **D-zone:** Major = 2 pts, Minor = 1 pt
- **Steel:** 5 points (power factor independent)
- **Penalties:** -10 points each (miss, no-shoot, procedural)

*Note: B-zone was phased out in 2018 and is now scored as C-zone*

## Installation

### Add to iPhone Home Screen
1. Open Safari on your iPhone
2. Navigate to: https://jeffrolc.github.io/hit-factor/
3. Tap the **Share** button
4. Scroll down and tap **"Add to Home Screen"**
5. Tap **"Add"**

The app works offline once loaded and behaves like a native app!

### Use in Browser
Simply visit https://jeffrolc.github.io/hit-factor/ in any modern browser.

## Technology

- Pure HTML/CSS/JavaScript (no frameworks required)
- Mobile-optimized responsive design
- Works offline as Progressive Web App (PWA)
- Deployed via GitHub Pages

## Related Project

This is the web-only version. For the full dual-platform project (iOS SwiftUI + Web), see:
https://github.com/jeffrolc/hit-factor-calculator

## License

MIT License - feel free to use and modify for your shooting needs.

---

Built for competitive USPSA/IPSC shooters 🎯
